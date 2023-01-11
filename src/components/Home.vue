<template>
    <div class="home">
        <section id="about" class="container bg-gradient">
            <div>
              <!-- <img src="https://i.postimg.cc/PrZ9kjV3/DSC-3520.jpg" class="img-thumbnail" alt="..."> -->
              <img src="" alt="">
              <h4 id="heading" class="display-4 text-liter">My name is Sakhe Mzolisa, a simple regular joe with ardent love for all people😎🖤</h4>
            </div>
            <p id="opening" class="lead text-liter">I am an aspiring <strong>Software Developer</strong> follow me on my journey🐾.
            </p>
          </section>
    </div>
</template>
<script>
export default {
    
}
</script>
<style scoped>
    .home {
        background-image: url(https://i.postimg.cc/vmxMmkTM/bright-yellowgreen-banner-background-design-with-neon-lighting-mixture-yellow-green-warm-summer-satu.jpg);
        height: 90vh;
        background-size: cover;
        overflow-x: hidden;
        display: flex !important;
        justify-content: center !important;
        align-items: center !important;
    }
    #opening { 
        /* width: 100%;
        height: 100%; */
        position: relative;
        animation: example 8s infinite;
        animation-direction: alternate;   
    }
    #heading {
        /* width: 100%;
        height: 100%; */
        position: relative;
        animation: example 8s infinite;
        animation-direction: alternate;
    }
    @keyframes example {
        from {left:0% ;}
        to {left: 5%;}
     }
</style>