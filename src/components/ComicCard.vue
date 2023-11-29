<script>
export default {
    props: {
        thumb: String,
        series: String
    }
};

</script>

<template>
    <div class="p-5">
        <div class="h-48 overflow-hidden">
            <img class="w-48" :src="thumb" alt="">
        </div>
        <p class=" w-48 pt-5 text-xs">{{ series }}</p>
    </div>
</template>

<style></style>