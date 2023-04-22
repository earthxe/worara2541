<template> 
    <v-app>
        <v-row align='center' justify='center'>
         <v-card width="500">
                 <v-card-text>
                         <v-row align="center" justify='center'>
                             <h1>Anwser : {{anwser}}</h1>
                         </v-row>
                         <v-row align="center" justify="center">

                         </v-row>
                     <v-row><v-text-field outlined v-model="v1"></v-text-field>
                    </v-row> 
                     <v-row>
                         <v-text-field outlined v-model="v2"></v-text-field>
                     </v-row>
                             <v-row  align="center" justify='center'><v-btn larg color="green" @click="cal()"> button
                         </v-btn> 
                      
                             </v-row>
                 </v-card-text>       
         </v-card>   
      </v-row>
           
    </v-app>
 </template>

<script>
    export default {
        data:()=>{
            return{
                v1:99,
                v2:null,
                anwser:null,
            }
        },
        computed: { //ทำงานตลอดเวลา

        },
        watch: { 

        },
        methods: { //สร้าง function
            cal(){
                this.anwser = parseInt(this.v1) + parseInt(this.v2)
                console.log(this.anwser);
            }
        }, 
        created () {},
    }
</script>
