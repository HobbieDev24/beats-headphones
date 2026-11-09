<script
    setup
    lang="ts"
>

</script>

<template>
    <nav class="bg-black">

        <img
            style="width: 45px;"
            class="pointer"
            src="/icons/logo-white.svg"
        >

        <div class="nav-menu-list-wrapper">
            <ul class="white">
                <li> Home </li>
                <li> Product </li>
                <li> Support </li>
            </ul>
        </div>


        <div class="nav-search-container">
            <input
                class="white"
                type="text"
                placeholder="Search"
                name="search"
            >
            <img
                style="padding-right: 1rem"
                src="/icons/icon-search.svg"
            >
        </div>

    </nav>

</template>


<style scoped>
nav {
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding: 80px 8.33% 0 8.33%;
    background-color: black;
}

.nav-search-container {
    padding: 13px 0px 13px 0px;
    max-width: 267px;
    display: flex;
    justify-content: center;
    align-items: center;
    margin: 0;
    padding: 0;
    background-color: rgba(255, 255, 255, 0.25);
    border-radius: 34px;
}

ul {
    list-style: none;
    font-size: 1.25rem;
    font-family: 'Bebas Neue', sans-serif;
    display: flex;
    justify-content: center;
    align-items: center;
    cursor: pointer;
    display: flex;
    justify-content: center;
    gap: 110px;
}

li:hover {
    text-decoration: underline;
}

@media only screen and (max-width: 1300px) {
    nav {
        display: none;
    }

}

@media only screen and (max-width: 900px) {
    nav {
        flex-direction: column;
    }
}
</style>
