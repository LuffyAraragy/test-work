<template>
    <div class="app-content-block-1">
        <div class="app-content-block-1__content block-1">
            1
        </div>
        <div class="app-content-block-1__content block-2">
            2
        </div>
        <div class="app-content-block-1__content block-3">
            3
        </div>
        <div class="app-content-block-1__content block-4">
            4
        </div>
        <div class="app-content-block-1__content block-5">
            5
        </div>
    </div>
</template>

<script>

export default {
    name: "AppContentBlock1"
}

</script>

<style scoped>
.app-content-block-1 {
    margin-top: 15px;
    background-color: #B3F95A;
    display: grid;
    /* width: 100%; */
    grid-template-columns: minmax(0, 390px) minmax(0, 590px) minmax(0, 160px);
    gap: 15px;
}

.app-content-block-1__content {
    background-color: #8AD191;
    min-height: 198px;
}

.block-1 {
    grid-column: 1;
} 

.block-2 {
    grid-column: 2;
}

.block-3 {
    grid-column: 3;
}

.block-4 {
    grid-column: 1/3;
}

.block-5 {
    grid-column: 3;
}  

</style>