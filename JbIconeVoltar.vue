<template>
    <div>
        <v-btn icon small :href="href" color="white">
            <v-icon dark color="primary" small>arrow_back</v-icon>
        </v-btn>
    </div>
</template>

<script>

    export default {
        props: {
            href:{type:String,default:"javascript:history.back()"}
        },
        data: function () {
            return {
                vmodel:this.value
            }
        },
        methods: {
            voltar: function(){
                if(!this.href){

                }
            }
        },
        watch: {
        },
    }
</script>