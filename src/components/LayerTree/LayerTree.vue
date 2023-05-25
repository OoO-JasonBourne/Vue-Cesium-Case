<template>
<vue-draggable-resizable :w="200" :h="200" :x="200" :y="200" style="background-color: antiquewhite;">

</vue-draggable-resizable>

</template>

<script>
import './zTree/js/jquery.ztree.core.min.js';
import './zTree/js/jquery.ztree.excheck.min.js';
import VueDraggableResizable from 'vue-draggable-resizable';
import 'vue-draggable-resizable/dist/VueDraggableResizable.css';
import './zTree/css/zTreeStyle/zTreeStyle.css';
import './zTree/css/metroStyle/metroStyle.css';
export default {
    data() {
        return {
            
        };
    },
    components: {
        VueDraggableResizable,
    },
    mounted() {
        
    },

    methods: {
        
    },
};
</script>

<style lang="less" scoped>
// test
</style>