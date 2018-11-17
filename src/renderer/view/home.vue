<template>
    <div id="home">
        <button class="start">开始抽奖</button>
    </div>
</template>

<script>
	export default {
		name: 'Home',
		data() {
			return {
				msg: 'Welcome to Your Vue.js App'
			}
		},
        methods:{
		    start(){

            }
        }
	}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.start{
    display: block;
    width: 200px;
    height: 40px;
    background: red;
    font-size: 24px;
}
</style>
