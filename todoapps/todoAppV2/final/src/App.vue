<template>
  <div>
    <new-category></new-category>
    
    <footer>
        Made with mucho love by Gus
    </footer>
  </div>
</template>

<script>
import Todo from './components/Todo'
import Category from './components/Category'
import NewCategory from './components/NewCategory'

export default {
  components: {
    NewCategory,
    Category,
    Todo
  }
}
</script>

<style>
 * {
   margin: 0;
   padding: 0;
   font-family: arial;
 }

 body {
   margin-top: -20px;
   min-height: 100%;
 }

 footer {
   position: fixed;
   width: 100%;
   bottom: 0;
   line-height: 35px;
   background-color: #f0f0f0;
   text-align: center;
   color: #cd595a;
   border-top: solid 1.5px #e0e0e0;
   font-weight: bold;
 }

</style>
