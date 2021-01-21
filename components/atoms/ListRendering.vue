<template>
  <div>
<ol class="list-decimal">
  <li v-for="(todo,index) in todos" :key="index">
    {{ todo.text}}
  </li>
</ol>
  </div>
</template>

<script>
export default {

  data(){
    return {
      todos:[
        {text: "Learn Nuxt"},
        { text: "Learn Vue"},
        { text: "Learn Atomic design"}
      ]
    }
  }
}
</script>
