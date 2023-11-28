<script>
export default {
    name: "items",
    data() {
        return {
            items: [
                {
                    src: "c.png",
                    text: "DIGITAL COMICS",
                    href: "#",
                },
                {
                    src: "buy-comics-merchandise.png",
                    text: "DC MERCHANDISE",
                    href: "#",
                },
                {
                    src: "buy-comics-subscriptions.png",
                    text: "SUBSCRIPTION",
                    href: "#",
                },
                {
                    src: "buy-comics-shop-locator.png",
                    text: "COMICS SHOP LOCATOR",
                    href: "#",
                },
                {
                    src: "buy-dc-power-visa.svg",
                    text: "DC POWER VISA",
                    href: "#",
                }
            ]
        };
    }
};
</script>

<template>
    <div class="bg-blue h-32 flex">
        <div class="m-auto grid grid-cols-5 gap-4">
            <div class="flex items-center col-span-1">
                <img class="w-9" src="img/c.png" alt="">
                <p class="pl-4 text-xs">DIGITAL COMICS</p>
            </div>
            <div class="flex items-center col-span-1">
                <img class="w-9" src="img/buy-comics-merchandise.png" alt="">
                <p class="pl-4 text-xs">DIGITAL COMICS</p>
            </div>
            <div class="flex items-center col-span-1">
                <img class="w-9" src="img/buy-comics-subscriptions.png" alt="">
                <p class="pl-4 text-xs">DIGITAL COMICS</p>
            </div>
            <div class="flex items-center col-span-1 ml-5">
                <img id="shop-locator" src="img/buy-comics-shop-locator.png" alt="">
                <p class="pl-4 text-xs">DIGITAL COMICS</p>
            </div>
            <div class="flex items-center col-span-1">
                <img class="w-9" src="img/buy-dc-power-visa.svg" alt="">
                <p class="pl-4 text-xs">DIGITAL COMICS</p>
            </div>
        </div>
    </div>
    <!-- <div class="card" v-for=" item in items">
                                                        <img :src="item.src" alt="">
                                                        <p>{{ item.text }}</p>
                                                    </div> -->
    <div class="w-screen img-bg">
        <div class="m-auto w-9/12 flex h-96 overflow-hidden">
            <div class="w-screen img-bg">
                <div class="m-auto w-9/12 flex h-96 overflow-hidden">
                    <div class=" pt-10 pr-10 pb-10 flex flex-col justify-center">
                        <h1>DC COMICS</h1>
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
                        <h1 class="pt-5">SHOP</h1>
                        <ul>
                            <li>shop DC</li>
                            <li>shop DC Collectables</li>
                        </ul>
                    </div>

                    <div class=" pt-10 pr-10 flex flex-col ">

                        <h1>DC</h1>
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
                        <h1>SITES</h1>
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
            <div>
                <img id="dc-logo" class="pl-20" src="img/dc-logo-bg.png" alt="">
            </div>
        </div>
    </div>
    <div class="w-screen bg-gray-800 text-white py-4">
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

#shop-locator {
    width: 12%;
}
</style>