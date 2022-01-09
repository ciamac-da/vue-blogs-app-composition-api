<template>
    <header>
        <h1>Vue Blogs Composition API</h1>
        <nav>
            <router-link :to="{ name : 'Home'}">Home</router-link>
            <router-link :to="{ name : 'Create'}">Create Post</router-link>
        </nav>
    </header>
</template>

<script>
export default {
    
}
</script>

<style>
header {
     display: flex;
     background: rgb(111, 49, 168);
     justify-content: space-between;
     align-items: center;
     margin: 0 auto;
     padding: 10px;
 }
 header h1 {
     color: #dfdfdf;
     font-size: 30px;
 }
 header a {
     color: #bbb;
     text-decoration: none;
     margin-left: 20px;
 }
 header a.router-link-active {
     color: #fff;
     font-weight: bolder;
 }
 @media (max-width: 600px) {
  header {
    display: flex;
    flex-direction: column;
  }
  header nav {
      padding: 15px;
  }
}
</style>