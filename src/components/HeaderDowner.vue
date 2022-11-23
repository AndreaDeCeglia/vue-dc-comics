<template>
  <div id="header-downer">
    <div id="content-header">
        <h6>
            Content goes here 
        </h6>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HeaderDowner',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">

#header-downer{
    background-color: #1C1C1C;
    color: white;
    // height: 50%;
   
        #content-header{
            padding: 3% 0;
            width: 80%;
            margin: auto;
            display: flex;
            justify-content: flex-start;
            align-items: center;

                h6{
                    margin-left: 2%;
                }
        }
}

</style>