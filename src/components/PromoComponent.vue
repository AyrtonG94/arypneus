<template>
    <div class="container">
        <h1 class="neonText">
            40% off
        </h1>
        <h2 class="neonText">Promoção válida até  15/11/23</h2>

    </div>
</template>

<style scoped>
.neonText {
    animation: flicker 1.5s infinite alternate;
    color: #fff;
}

h1 {
    font-size: 3.0rem;
}

/* Flickering animation */
@keyframes flicker {

    0%,
    18%,
    22%,
    25%,
    53%,
    57%,
    100% 
    {

        text-shadow:
            0 0 4px #fff,
            0 0 11px #fff,
            0 0 19px #fff,
            0 0 40px #0fa,
            0 0 80px #0fa,
            0 0 90px #0fa,
            0 0 100px #0fa,
            0 0 150px #0fa;

    }

    20%,
    24%,
    55% {
        text-shadow: none;
    }
}

h2 {
    font-size: 1.0rem;
}
h1,
h2 {
    text-align: center;
    text-transform: uppercase;
    font-weight: 400;
}
</style>