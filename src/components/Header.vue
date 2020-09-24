<template>

    <div>
        <h1 class="display-1">MY APPLICATION</h1>
        <a @click.stop href="#gwapo">
          <Button @click="submit">
            <span>Contact us!</span>
          </Button>
        </a>
    </div>

</template>

<script>
export default {
methods: {
    submit() {
   

    alert("Aw");
     
    }
  }
}
</script>

<style scode>
h1 {
  background-color:slategrey;
  color: white;
  text-align: left;
  font-family: verdana;
  font-size: 50px;
}
.tablink {
  background-color: #555;
  color: white;
  float: left;
  border: none;
  outline: none;
  cursor: pointer;
  padding: 14px 16px;
  font-size: 17px;
  width: 25%;
}
.tablink:hover {
  background-color: #777;
}
</style>