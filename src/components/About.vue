<template lang="">
    <div class="till">
        <div class="container">
            <div class="row">
                <div class="col">
                    <h2 class="Display-2"><strong>About</strong></h2>
                    <p class="lead">I was born in the township of Gugulethu at the beginning of the new century. I started and completed my High School education at Goodwood College, matriculating with a bachelor's pass in 2017. I then enrolled at UWC in the year 2018 studying BA majoring in Politics and History since I love History. I however dropped out in 2021 as I fell out of love with politics and then joined the workforce for a couple of years as I was searching for my true passion. There was always something about programming and software development that intrigued me. The problem solving, the software creation, the web-development. I just knew that I was somehow made for this. I was then fortunate enough to get accepted to study Web development at Life Choices Academy, an opportunity I have grabbed with both hands and I must say I love it with all it's glory and challenges.</p>
                </div>
                <div class="col img">
                    <img src="https://i.postimg.cc/bNKtXXp9/DSC-3520-Photo-Room-1.png" class="img-width=" alt="...">
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
    padding-bottom: 2rem;
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