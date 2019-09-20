<template>
    <div class="list-user">
        <!-- <p>List User Component</p> -->
        <UserDetail/>
        <UserDetail/>
        <UserDetail/>
        <UserDetail/>
    </div>
</template>

<script>
import UserDetail from './UserDetail'
export default {
    name: 'list-user',
    data(){
        return {
            
        }
    },
    components:{
        UserDetail
    }
}
</script>

<style>

</style>