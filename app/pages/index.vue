<script
    setup
    lang="ts"
>

useSeoMeta({
    title: 'Beats by Dr Dre',
})

</script>

<template>

    <body>
        <main>

            <cNav></cNav>

            <cSection
                :bgColor="'black'"
                :heading="'Unleash your demon with Beats by Dr. Dre'"
                :description="'Featuring Active Noise Cancelling, which gives you the space to create with fully immersive sound.'"
            >

                <div>
                    <img src="/images/hero-headphones.png">
                </div>

            </cSection>

            <cSection
                :bg-color="'white'"
                :heading="'Wireless headphones for all-day activity'"
                :is-reverse="true"
                description="And if you’re in need of extra juice, use 5-minute Fast Fuel for 1 hour of playback when battery is low."
            >

                <template v-slot:icon-text>
                    <div style="margin-bottom: 1.4rem">
                        <img
                            style="margin-right:0.6rem; width: 1rem; vertical-align: middle;"
                            src="/icons/icon-battery.svg"
                        >
                        <span>Up to <b>15 hours</b> of listening time</span>
                    </div>
                </template>

                <img
                    style="max-width: 640px;"
                    src="/images/wireless-headphones.png"
                >

            </cSection>

            <cSection
                :bgColor="'black'"
                heading="Designed to fit everywhere"
                description="Made for travel, these premium headphones fold flat and store in tight spaces. Just make sure you treat them right."
            >

                <img
                    style="max-width: 800px;"
                    src="/images/fit-headphones.png"
                >

            </cSection>

            <cSection
                :bgColor="'white'"
                heading="For every mood & every setting"
                description="Whether you want the coolest wireless earphones for the gym or the most sophisticated noise-canceling headphones for travel, Beats headphones look as good as they sound."
                :is-reverse="true"
            >
                <div style="display: flex; gap: 14px;">

                    <div style="display: flex; flex-direction: column; gap: 14px">
                        <img src="/images/gallery-item-2.png">
                        <img src="/images/gallery-item-3.png">
                    </div>

                    <div style="display: flex; flex-direction: column; gap: 14px">
                        <img src="/images/gallery-item-4.png">
                        <img src="/images/gallery-item-1.png">
                    </div>
                </div>

            </cSection>

            <cSection
                :bgColor="'black'"
                heading="suit your style with any color"
                description="Colorful headphones just make sense. Match your headphones, earbuds, and accessories to the shade of your mood or the aura of your shoelaces."
            >

                <div style="display: flex; gap: 48px;">

                    <div style="display: flex; flex-direction: column; gap: 24px">
                        <img src="/images/color-green.png">
                        <img src="/images/color-blue.png">
                    </div>

                    <div style="display: flex; flex-direction: column; gap: 24px">
                        <img src="/images/color-red.png">
                        <img src="/images/color-yellow.png">
                    </div>
                </div>


            </cSection>

            <cSection
                :bg-color="'white'"
                heading="Pair easily, switch seamlessly."
                description="With iOS and the Apple W1 chip, one press and you're paired with your
                    device.
                    Now you can easily go from taking a call on your iPhone to watching a film on your MacBook."
                :is-reverse="true"
            >
                <div>
                    <img
                        src="/images/pair-devices.png"
                        style="max-width: 1024px;"
                    >
                </div>
            </cSection>


            <cSection
                :bg-color="'black'"
                heading="built by musicians for musicians"
                description="Founded by producer and rapper Dr. Dre and Interscope Records co-founder Jimmy Iovine, for the past 10 years Beats has occupied a space in the public imagination that very few audio brands have achieved."
            >

                <div>
                    <img
                        style="max-width: 360px;"
                        src="/images/musicians-dre.png"
                    >
                </div>

            </cSection>

            <cFooter></cFooter>

        </main>
    </body>

</template>

<style>
* {
    box-sizing: border-box;
}

body {
    width: 100%;
    font-family: 'IBM Plex Sans', sans-serif;
    margin: 0;
    padding: 0;
}

p,
h1,
h2,
h3,
h4,
h5,
h6,
input {
    margin: 0;
    padding: 0;
}

img {
    width: 100%;
    height: auto;
}

input {
    font-size: 1rem;
    background: none;
    border: none;
    padding: 13px 0px 13px 1rem;
}

input[type=text]:focus {
    outline: none;
}

.grey {
    color: #7F7F7F;
}

.black {
    color: black;
}

.white {
    color: white;
}

.pointer {
    cursor: pointer;
}
</style>