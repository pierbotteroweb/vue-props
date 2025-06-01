<template>
    <div>
        <h1>I'm the Parent Component</h1>
        <Child />
    </div>
</template>
<script>
import Child from './Child.vue';

/* eslint-disable */
export default {
    name: 'Parent',
    components:{
        Child
    }
}
</script>
