f<template>
    <div>
        <h1>그누보드 마스터</h1>
        <router-view></router-view>
    </div>
</template>
<script>
    import BoardDynamic from "./BoardDynamic";
    export default {
        name: "GnuBoardMaster",
        components: {BoardDynamic}
    }
</script>

<style scoped>

</style>