<script>
export default {
    name: "menuLinks",
    data() {
        return {
            links: [
                {
                    text: "CHARACTERS",
                    href: "#",
                },
                {
                    text: "COMICS",
                    href: "#",
                },
                {
                    text: "MOVIES",
                    href: "#",
                },
                {
                    text: "TV",
                    href: "#",
                },
                {
                    text: "GAMES",
                    href: "#",
                },
                {
                    text: "COLLECTABLES",
                    href: "#",
                },
                {
                    text: "VIDEOS",
                    href: "#",
                },
                {
                    text: "FANS",
                    href: "#",
                },
                {
                    text: "NEWS",
                    href: "#",
                },
                {
                    text: "SHOP",
                    href: "#",
                },
            ]
        };
    }
};



</script>

<template>
    <div class="bg-white">
    <div class="grid grid-cols-12 p-4"> 
        <div class="col-span-6 flex justify-center"> 
            <img src="img/dc-logo.png" alt="" class="justify-center"> 
        </div>
        <div class="col-span-6 flex justify-center items-center text-black"> 
            <a v-for="link in links" :key="link.text" class="p-1 text-xs" href="#">{{ link.text }}</a>
        </div>
    </div>
</div>
</template>

<style>
</style>