<template>
   <div id="app1">
             <button v-on:click ="str()">Button1</button> <br /><br />

             <div id="div1" v-on:mouseover="changeName()">
               <p> {{name}}</p>
                 

             </div>
   </div>


</template>

<script>
      export default {
        name: "para1",

        data: function(){

            return {
         
            name: "Ria"
            } 
        },
      
       methods: {

         str(){
           alert("hello");
         },

          changeName(){
            
            this.name = "Rucha";
          }
       }
        

       
        
      } 

</script>