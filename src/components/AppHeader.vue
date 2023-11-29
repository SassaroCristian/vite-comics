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
                <a v-for="link in links" :key="link.text" class="p-5 text-xs hover-link font-bold" href="#">{{ link.text
                }}</a>
            </div>
        </div>
    </div>
</template>

<style>
.hover-link {
    position: relative;
    transition: color 0.3s ease-in-out;
    text-decoration: none;

}


.hover-link:hover {
    color: #0597F2;

}


.hover-link::after {
    content: "";
    display: block;
    position: absolute;
    bottom: -2px;
    left: 0;
    width: 100%;
    height: 2px;
    background-color: #0597F2;
    transform: scaleX(0);
    transform-origin: bottom right;
    transition: transform 0.3s ease-in-out;
}


.hover-link:hover::after {
    transform: scaleX(1);
    transform-origin: bottom left;
}
</style>