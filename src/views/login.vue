<template>
    <div class="login">
        
        <com-login></com-login>
    </div>
</template>
<script>
import comLogin from '@/components/com-login.vue'


import { Button, Select } from 'element-ui';
export default {
   
    data:function(){
        return{
            msg:"你好世界"
        }
    },
    components:{
        comLogin
    }
}
</script>