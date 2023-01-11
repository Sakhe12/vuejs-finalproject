<template lang="">
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
        <div class="container-fluid">
          <a class="navbar-brand" href="#">Sakhe Mzolisa<i class="fa-solid fa-heart fa-beat" style="--fa-animation-duration: 1s;" ></i></a>
          <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
          </button>
          <div class="collapse navbar-collapse" id="navbarNav">
            <ul class="navbar-nav ms-auto mb-2 mb-lg-0 text-light gap-3">
                <li class="nav-item">
                    <router-link class="txt-col" to="/"><i class="fa-solid fa-house fa-flip" style="--fa-animation-duration: 3s;" ></i>Home</router-link>
                </li>
                <li class="nav-item">
                    <router-link class="txt-col" to="/about"><i class="fa-solid fa-briefcase fa-flip" style="--fa-animation-duration: 3s;" ></i>About</router-link>
                </li>
                <li class="nav-item">
                    <router-link class="txt-col" to="/"><i class="fa-solid fa-briefcase fa-flip" style="--fa-animation-duration: 3s;" ></i>Resume</router-link>
                </li>
                <li class="nav-item">
                    <router-link class="txt-col" to="/skills"><i class="fa-solid fa-wrench fa-flip" style="--fa-animation-duration: 3s;" ></i>Skills</router-link>
                </li>
                <li class="nav-item">
                    <router-link class="txt-col" to="/"><i class="fa-solid fa-gamepad fa-flip" style="--fa-animation-duration: 3s;" ></i>Projects</router-link>
                </li>
                <li class="nav-item">
                    <router-link class="txt-col" to="/testimonials"><i class="fa-solid fa-search fa-flip" style="--fa-animation-duration: 3s;" ></i>Testimonial</router-link>
                </li>
                <li class="nav-item">
                    <router-link class="txt-col" to="/contact"><i class="fa-solid fa-envelope fa-flip" style="--fa-animation-duration: 3s;" ></i>Contact</router-link>
                </li>
            </ul>
          </div>
        </div>
      </nav>
</template>
<script>
export default {
    
}
</script>
<style >
.txt-col {
    text-decoration: none;
    color: white;
}
.fa-solid {
    color: aqua;
}

</style>