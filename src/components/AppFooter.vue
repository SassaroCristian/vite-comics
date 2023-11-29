<script>
export default {
    name: "items",
    data() {
        return {
            items: [
                {
                    src: "img/c.png",
                    text: "DIGITAL COMICS",
                    href: "#",
                },
                {
                    src: "img/buy-comics-merchandise.png",
                    text: "DC MERCHANDISE",
                    href: "#",
                },
                {
                    src: "img/buy-comics-subscriptions.png",
                    text: "SUBSCRIPTION",
                    href: "#",
                },
                {
                    src: "img/buy-comics-shop-locator.png",
                    text: "COMICS SHOP LOCATOR",
                    href: "#",
                },
                {
                    src: "img/buy-dc-power-visa.svg",
                    text: "DC POWER VISA",
                    href: "#",
                }
            ]
        };
    }
};
// methods: {
//     getImagePath(img) {
//         return new URL('..img/${src}', import.meta.url).href;
//     }
// }
</script>

<template>
    <div class="grid grid-cols-5 gap-4 bg-blue h-32 ">
        <div class="flex items-center justify-center col-span-1" v-for="(item, index) in items" :key="index">
            <img class="w-10 h-10" :src="item.src" alt="">
            <p class="pl-4 text-xs">{{ item.text }}</p>
        </div>
    </div>
    <div class=" img-bg">
        <div class="m-auto w-9/12 flex h-96 overflow-hidden">
            <div class="w-screen img-bg">
                <div class="m-auto w-9/12 flex h-96 overflow-hidden">
                    <div class=" pt-10 pr-10 pb-10 flex flex-col justify-center">
                        <h1 class="font-bold">DC COMICS</h1>
                        <ul>
                            <li>Characters</li>
                            <li>Characters</li>
                            <li>Characters</li>
                            <li>Characters</li>
                            <li>Characters</li>
                            <li>Characters</li>
                            <li>Characters</li>
                            <li>Characters</li>
                        </ul>
                        <h1 class="pt-5 font-bold">SHOP</h1>
                        <ul>
                            <li>shop DC</li>
                            <li>shop DC Collectables</li>
                        </ul>
                    </div>

                    <div class=" pt-10 pr-10 flex flex-col ">

                        <h1 class="font-bold">DC</h1>
                        <ul>
                            <li>shop DC</li>
                            <li>shop DC</li>
                            <li>shop DC</li>
                            <li>shop DC</li>
                            <li>shop DC</li>
                            <li>shop DC</li>
                            <li>shop DC</li>
                            <li>shop DC</li>
                            <li>shop DC</li>
                            <li>shop DC</li>
                        </ul>
                    </div>

                    <div class="pt-10 flex flex-col ">
                        <h1 class="font-bold">SITES</h1>
                        <ul>
                            <li>shop DC</li>
                            <li>shop DC</li>
                            <li>shop DC</li>
                            <li>shop DC</li>
                            <li>shop DC</li>
                        </ul>
                    </div>
                </div>
            </div>
            <div class="">
                <img id="dc-logo" class="pl-20" src="img/dc-logo-bg.png" alt="">
            </div>
        </div>
    </div>
    <div class=" bg-gray-800 text-white py-4">
        <div class="m-auto w-9/12 flex justify-between items-center">
            <div>
                <button class="bg-blue-500 hover:bg-blue-700 text-white font-bold py-2 px-4 rounded">
                    <a href="#">SIGN UP NOW!</a>
                </button>
            </div>

            <div class="flex items-center space-x-4">
                <p>FOLLOW US </p>
                <img src="img/footer-facebook.png" alt="Facebook">
                <img src="img/footer-twitter.png" alt="Twitter">
                <img src="img/footer-youtube.png" alt="YouTube">
                <img src="img/footer-pinterest.png" alt="Pinterest">
                <img src="img/footer-periscope.png" alt="Periscope">
            </div>
        </div>
    </div>
</template>

<style>
.bg-blue {
    background-color: #0597F2;
}

.img-bg {
    background-image: url('img/footer-bg.jpg');
    background-size: cover;

}

#dc-logo {
    width: 1500px;
}

#shop-locator {
    width: 12%;
}
</style>