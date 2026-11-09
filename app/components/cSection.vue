<script
    setup
    lang="ts"
>

const props = defineProps({
    bgColor: {
        type: String,
        required: true
    },

    heading: {
        type: String,
        required: true
    },

    description: {
        type: String,
        required: true
    },
})

</script>

<template>

    <section :style="{ backgroundColor: props.bgColor }">
        <div
            style="max-width: 600px;"
            :class="props.bgColor === 'black' ? 'white' : 'black'"
        >
            <h2> {{ heading }} </h2>
            <p>{{ description }}</p>
            <button> Shop now </button>
        </div>
        <div>
            <slot></slot>
        </div>

    </section>

</template>


<style scoped>
section {
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding: 12.5%;
}

h2 {
    font-size: 5rem;
    font-family: 'Bebas Neue', sans-serif;
    line-height: 100%;
    margin-bottom: 1.25rem;
    text-transform: uppercase;
    text-wrap: balance;
}

p {
    font-size: 1.25rem;
    line-height: 140%;
    text-wrap: pretty;
}

button {
    background-color: #A62121;
    border: 0;
    border-radius: 60px;
    font-size: 1.25rem;
    font-weight: 500;
    color: white;
    padding: 20px 34px;
    margin-top: 1.75rem;
    max-width: 220px;
    text-align: center;
    cursor: pointer;
    display: block;
}

button:hover {
    transition: 0.3s;
    background-color: #c02626;
}

@media only screen and (max-width: 900px) {
    section {
        flex-direction: column;
        padding: 12.5% 6.25%;
        gap: 60px;
    }

    h2,
    p {
        text-align: center;
    }

    h2 {
        font-size: 3.125rem;
    }

    p {
        font-size: 1.5rem;
    }

    button {
        margin-inline: auto;
    }
}
</style>
