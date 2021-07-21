<template>
  <div class="hello">
    <h1>第一次修改</h1>
    
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
			// radio的选项
      value:"",
			options : []
  	}

  },
  mounted(){
  	
  },
  methods:{	
		check(){
			console.log(this.value)
    }
  }

}
</script>
<!-- Add "scoped" attribute t  CSS to this component only -->
<style scoped>
h1, h2 {
  font-weight: normal;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
