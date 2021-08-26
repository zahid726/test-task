<template>
    <footer>
        <div class="content">
          <p> 2021 @all copyRight Reserved</p> <span><p>privary policy | terms and condtions</p></span>
        </div>
   </footer>
</template>
<script>
export default {
   name: 'Footer'
}
</script>
<style scoped>
footer{
    padding-top: 30px;
    margin-top: 20px;
    box-shadow: 0px 2px 15px rgba(0, 0, 0, 0.5);
}
.content{
    background-color: black;
    color: white;
    padding:10px;
    display: flex;
    justify-content: space-between;
}
</style>