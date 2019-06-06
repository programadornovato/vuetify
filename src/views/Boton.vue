<template>
    <v-container>
        <v-layout>
            <v-flex>
                <v-btn color="success">boton</v-btn>
                <v-btn dark color="blue">boton</v-btn>
                <v-btn flat color="blue">boton</v-btn>
                <v-btn small color="blue">boton</v-btn>
                <v-btn color="blue">boton</v-btn>
                <v-btn large color="blue">boton</v-btn>
                <v-btn dark depressed color="blue">boton</v-btn>
                <v-btn  flat icon color="success"><v-icon>account_balance</v-icon></v-btn>
                <v-btn :large="largo" color="success"><v-icon>account_balance</v-icon></v-btn>
                <v-btn @click="largo^=true;" >click</v-btn>
            </v-flex>
        </v-layout>
    </v-container>    
</template>
<script>
export default {
    data(){
        return{
            largo:true
        };
    }
}
</script>

