<template>
	<div id="app">
		<img width="800px" height="250px" alt="Vue logo" sr c="./assets/dis.png">
		<HelloWorld msg="Know thou System"/>
		<router-link to="/kelas">Data Kelas</router-link>
		<router-link to="/kelas">Data Siswa</router-link>
		<br><router-link to="/kelas/tambah">Tambah Data Kelas</router-link>&nbsp
		<router-link to="/siswa/tambah">Tambah Data Siswa</router-link>
		<router-view/>
	</div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
	name: 'App',
	components: {
		HelloWorld
	}
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>