<template>



<div class="page">
<div class="stickybar">
    <ul>
        <center><li><a href="..">Comeback na projektsiema</a></li>
        <li><a href="stah">Główna</a></li>
        <li><a href="stah">Forum</a></li>
        <li><a href="stah">Kontakt</a></li>
        <li><a href="stah">Pomoc</a></li></center>


    </ul>
 </div>

    <div class="container">
        <div class="contentcontainer">

            <button onclick="myFunction()">
                
                
                Click me


            </button>


            <div class="topbar">
                Topbar here ofkors <center> tu center jest</center>
            </div>
            <div class="sidebar">
                tutaj sidebar here?
            </div>

            <div class="content">
                tutaj kontent-
            </div>
            


        </div>
    </div>
</div>
    


</template>



<style>
@import url('..\Pliki CSS\stah\styles.css');
</style>

<script>
export default {
    head:{
        title: 'stronka here'
    }


    
}

function myFunction() {
  document.getElementById("demo").innerHTML = "Hello World";
}
</script>


