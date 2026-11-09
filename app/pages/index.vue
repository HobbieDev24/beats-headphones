<script
    setup
    lang="ts"
>

</script>

<template>

    <head>
        <meta
            name="viewport"
            content="width=device-width, initial-scale=1"
        />
        <meta charset="UTF-8">
        <meta
            http-equiv="X-UA-Compatible"
            content="IE=edge"
        >
        <title>Beats by Dr Dre</title>
    </head>

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
                description="And if you’re in need of extra juice, use 5-minute Fast Fuel for 1 hour of playback when battery is low."
            >
                <img
                    style="max-width: 640px;"
                    src="/images/wireless-headphones.png"
                >

                <!-- <p>Up to <b>15 hours</b> of listening time</p> -->
                <!-- <div> -->
                <!-- </div> -->

                <!-- <div class="component-column wireless-column-right pad-top-bot-260 pad-left-d-130-m-0"> -->

                <!-- <img
                        style="margin-right: 1rem; margin-bottom: 20px; width: 40px"
                        src="/icons/icon-battery.svg"
                    > -->
                <!-- </div> -->

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
            >
                <div>
                    <img src="/images/pair-devices.png">
                </div>
            </cSection>


            <cSection
                :bg-color="'black'"
                heading="built by musicians for musicians"
                description="Founded by producer and rapper Dr. Dre and Interscope Records co-founder Jimmy Iovine, for the past 10 years Beats has occupied a space in the public imagination that very few audio brands have achieved."
            >

                <div>
                    <img
                        style="max-width: 240px;"
                        src="/images/musicians-dre.png"
                    >
                </div>

            </cSection>

            <cFooter></cFooter>

        </main>

    </body>

</template>

<style>
@import url('https://fonts.googleapis.com/css2?family=IBM+Plex+Sans&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Bebas+Neue&family=IBM+Plex+Sans&display=swap');


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
h6 {
    margin: 0;
    padding: 0;
}

img {
    width: 100%;
    height: auto;
}

.pointer {
    cursor: pointer;
}

input {
    font-size: 1rem;
    background: none;
    border: none;
    padding: 13px 0px 13px 1rem;
    margin: 0;
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

@media only screen and (max-width: 900px) {

    /* .section-6,
    .section-4,
    .section-2 {
        flex-direction: column-reverse;
    } */

}
</style>