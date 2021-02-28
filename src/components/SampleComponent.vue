<template>
    <div class="box">
        <p class="example">
            hi
            <child-component></child-component>
        </p>
    </div>
</template>

<script>
import ChildComponent from "@/components/ChildComponent.vue"

export default {
    components: {
        ChildComponent
    }
}
</script>

<style scoped>
    .example {
        color: red;
    }
    .example >>> .example {
        color: orange;
    }
    .box {
        border: 1px solid #bcbcbc;
        padding: 8px 16px;
        margin: 0px 32px;
    }
</style>s