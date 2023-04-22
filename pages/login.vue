<template> 
   <v-app>
       <v-row align='center' justify='center'>
        <v-card width="600">
                <v-card-text>
                        <v-row align="center" justify='center'>
                            <h1> Project </h1>
                        </v-row>
                    <v-row><v-text-field outlined label='E-mail'>
                        </v-text-field></v-row> 
                    <v-row>
                        <v-text-field outlined label='password' type="password">
                        </v-text-field>
                    </v-row>
                            <v-row  align="center" justify='center'><v-btn larg color="green" outlined rounded x-large> login 
                        </v-btn> 
                     <v-btn  larg color="red" outlined rounded x-large> reset </v-btn>
                            </v-row>
                </v-card-text>       
        </v-card>   
     </v-row>
          
   </v-app>
</template>