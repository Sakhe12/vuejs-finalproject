<template lang="">
    <div class="till">
        <div class="container">
            <div class="row">
                <div class="col">
                    <h2 class="Display-2"><strong>About</strong></h2>
                    <p class="lead">Lorem ipsum dolor sit amet consectetur adipisicing elit. Doloremque quam, tenetur quo ullam minima laborum, nisi tempore inventore voluptatum deleniti blanditiis dolorem minus quidem earum? Ducimus modi sit dolorem architecto?</p>
                </div>
                <div class="col img">
                    <img src="https://i.postimg.cc/bNKtXXp9/DSC-3520-Photo-Room-1.png" class="img" alt="...">
                </div>
            </div>
        </div>
    </div>
</template>
<script>
export default {
    
}
</script>
<style scoped>
.till {
    height: 90vh;
}
img {
    width: 285px;
    height: 240px;
    filter: blur(5px);
}
img:hover {
    animation: Funky 0.5s ease-in-out forwards;
}
@keyframes Funky {
    0% {
        filter: blur(5px)
    }
    100% {
        filter: blur(0)
    }
}



</style>