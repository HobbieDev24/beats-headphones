<script
    setup
    lang="ts"
>

</script>

<template>

    <footer>
        <img
            class="pointer"
            src="/icons/logo-black.svg"
        >

        <div class="footer-column">
            <h4 class=""> Products </h4>
            <ul class="grey">
                <li> Beats Flex </li>
                <li> Beats Pro </li>
                <li> Powerbeats </li>
                <li> Powerbeats Pro </li>
                <li> Beats Solo </li>
                <li> Beats Studio </li>
                <li> Beats EP </li>
            </ul>
        </div>

        <div class="footer-column">
            <h4 class=""> Support </h4>
            <ul class="footer-list grey">
                <li> Product help </li>
                <li> Service & Warranty </li>
                <li> Register your Beats </li>
                <li> Update your Beats </li>
                <li> Authorised Retailers </li>
                <li> Contact support </li>
                <li> Int. numbers </li>
            </ul>
        </div>

        <div class="footer-column">
            <h4 class=""> Company </h4>
            <ul class="footer-list grey">
                <li> About </li>
                <li> Careers </li>
            </ul>
        </div>

        <div class="footer-column">
            <h4 class=" black"> Legal </h4>
            <ul class="footer-list grey">
                <li> Terms of use </li>
                <li> Privacy Policy </li>
                <li> Trademarks </li>
                <li> Promotion terms </li>
            </ul>
        </div>


        <div>
            <h4 class="black"> Follow us </h4>
            <div class="socials">
                <img src="/icons/iconmonstr-facebook-4.svg">
                <img src="/icons/iconmonstr-instagram-14.svg">
                <img src="/icons/iconmonstr-twitter-4.svg">
                <img src="/icons/iconmonstr-youtube-4.svg">
            </div>
        </div>
    </footer>

</template>


<style scoped>
footer {
    display: flex;
    justify-content: space-evenly;
    align-items: flex-start;
    gap: 120px;
    padding-block: 130px;

    ul {
        list-style: none;
        display: flex;
        flex-direction: column;
        gap: 12px;
        font-size: 1rem;
        padding: 0;
        margin: 0;
    }

    li {
        cursor: pointer;
    }

    li:hover {
        text-decoration: underline;
    }

    h4 {
        font-size: 1.25rem;
        font-family: 'Bebas Neue', sans-serif;
        margin-bottom: 20px;
    }

    img {
        max-width: 45px;
        cursor: pointer;
    }
}

.socials {
    display: flex;
    gap: 14px;
}

@media only screen and (max-width: 900px) {
    footer {
        flex-direction: column;
        padding: 10% 6.25%;
        align-items: center;
        justify-content: center;
        gap: 32px;
        text-align: center;
    }

}
</style>
