<template>
  <div>
  <h1>{{ msg }}</h1>
  <input type="text" v-model="title" />
</div>
</template>

<script>
export default {
    name: "Message-hooks",
  props: ['msg'],

  data(){ 
      return{
        title: null 
      };
},

  beforeCreate() {
    console.log("beforeCreate");
  },
  created() {
    console.log("created");
  },
  beforeMount() {
    console.log("beforeMount");
  },
  mounted() {
    console.log("mounted");
  },
  beforeUpdate() {
    console.log("beforeUpdate");
  },
  updated() {
    console.log("updated");
  },

//   Good it will be shown to the console
  beforeUnmount(){
      console.log("beforeUnmount")
  },
  unmounted(){
      console.log("unmounted")
  }

// BAD
//    beforeDestroy() {
//     console.log("beforedestroy");
//   },
//    destroyed() {
//     console.log("destroyed");
//   }
}
</script>