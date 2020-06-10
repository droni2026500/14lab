<template>
  <div id="app">
    <notebook></notebook>
  </div>
</template>

<script>
import MyNotebook from './components/notebook.vue';

export default {
  name: 'App',
  components: {
    notebook: MyNotebook,
  }
}
</script>
<style>
#app {
    margin: 50px 15px 15px 50px;

}

div label {
    float: left;
    width: 15%;
}

.knopka {
    margin: 15px 15px 15px 0px;
    width: 27%;
    border: 17px;
    padding: 5px 10px;
    border: 2px solid;
}

.book {
    border:1px solid;
}

#button-change {
    background-color: green;
    margin: 10px 10px 10px 0px;
    width: 10%;
    border: 10px;
    padding: 5px 10px;
    border: 0.4px solid;
}

#button-delete {
    background-color: red;
    margin: 10px 10px 10px 0px;
    width: 10%;
    border: 10px;
    padding: 5px 10px;
    border: 0.4px solid;
}

</style>
