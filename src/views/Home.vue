<template>
    <div class="about">
        <Todos v-bind:todos="todos"/>
    </div>


</template>

<script>
import Todos from '@/components/Todos'
export default {
    name: 'Home',
    components:{
        Todos 
    },
    data(){
        return{
            todos:[
                {
                    "id":1,
                    "title":"Learn VUE",
                    "completeed":false
                },
                {
                    "id":2,
                    "title":"Learn Angular",
                    "completeed":false
                },
                {
                    "id":3,
                    "title":"Learn REACT",
                    "completeed":false
                },
                {
                    "id":4,
                    "title":"Learn Redusss",
                    "completeed":false
                }
            ]
        }
    }
}
</script>