<template>
  <div id="app">
    <h1> Docaid </h1>
    <Noteslist></Noteslist>
  </div>
</template>


<script>
import Note from './Note.vue'
import Noteslist from './Noteslist.vue'
export default {
  name: 'app',
  components: { Noteslist},
  data () {
    return {};
  },
  methods: {},
};
</script>

<style>
#app {
	font-family: Helvetica, Arial, sans-serif;
	text-align: center;
	color: #2c3e50;
	background-color: #878f99;
	margin: 10px auto;
	padding: 10px;
}
</style>
