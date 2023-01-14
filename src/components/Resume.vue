<template>
    <div class="words">
        <section class="space container" v-for="timeline in resume" :key="timeline">
            <div class="dev">
                <h4 class="display-4">{{timeline.occupation}}</h4>
                <p class="lead">{{timeline.words}}</p>
                <p class="lead">{{timeline.year}}</p>
            </div>
        </section>
        <section id="skills" class="container skills bg-gradient">
            <h2 class="display-2">Skills</h2>
            <p class="lead"><i class="bi bi-filetype-html"></i>HTML</p>
            <div class="progress">
              <div class="progress-bar progress-bar-striped progress-bar-animated text-bg-info" role="progressbar" aria-label="Animated striped example" aria-valuenow="75" aria-valuemin="0" aria-valuemax="100" style="width: 80%"></div>
            </div>
            <p class="lead"><i class="bi bi-filetype-css"></i>CSS</p>
            <div class="progress">
              <div class="progress-bar progress-bar-striped progress-bar-animated text-bg-danger" role="progressbar" aria-label="Animated striped example" aria-valuenow="75" aria-valuemin="0" aria-valuemax="100" style="width: 70%"></div>
            </div>
            <p class="lead"><i class="fa-brands fa-bootstrap"></i>Bootstrap</p>
            <div class="progress">
              <div class="progress-bar progress-bar-striped progress-bar-animated text-bg-success" role="progressbar" aria-label="Animated striped example" aria-valuenow="75" aria-valuemin="0" aria-valuemax="100" style="width: 85%"></div>
            </div>
            <p class="lead"><i class="fa-brands fa-node-js"></i>Javascript</p>
            <div class="progress">
              <div class="progress-bar progress-bar-striped progress-bar-animated" role="progressbar" aria-label="Animated striped example" aria-valuenow="75" aria-valuemin="0" aria-valuemax="100" style="width:60%"></div>
            </div>
            <p class="lead"><i class="fa-brands fa-vuejs"></i>Vue Js</p>
            <div class="progress">
              <div class="progress-bar progress-bar-striped progress-bar-animated text-bg-warning" role="progressbar" aria-label="Animated striped example" aria-valuenow="75" aria-valuemin="0" aria-valuemax="100" style="width:65%"></div>
            </div>
            <h2 class="display-2">Soft Skills</h2>
            <p class="lead"><i class="bi bi-screwdriver"></i>Problem-solving</p>
            <div class="progress">
              <div class="progress-bar progress-bar-striped progress-bar-animated text-bg-dark" role="progressbar" aria-label="Animated striped example" aria-valuenow="75" aria-valuemin="0" aria-valuemax="100" style="width: 80%"></div>
            </div>
            <p class="lead"><i class="bi bi-lightbulb-fill"></i>Creativity</p>
            <div class="progress">
              <div class="progress-bar progress-bar-striped progress-bar-animated text-bg-dark" role="progressbar" aria-label="Animated striped example" aria-valuenow="75" aria-valuemin="0" aria-valuemax="100" style="width: 85%"></div>
            </div>
          </section>
    </div>
</template>
<script>
export default {
    name: "timeline",
    data() {
        return {
            resume : [
                {
                    occupation : "Life Choices Coding Academy",
                    words : "Studying Web Development, would like to specialize in front-end",
                    year : "2022 - 2023"
                },
                {
                    occupation : "Mr D Food Flexi-Perm Customer Service Agent",
                    words : "Call center agent who primarily dealt with order related queries and app troubleshooting. I also sometimes dealt with escalations.",
                    year : "2020 - 2022"
                },
                {
                    occupation : "University of the Western Cape",
                    words : "I was studying Bachelor of Arts majoring in Political studies and History, unfortunately did not finish the course as it was not my passion.",
                    year : "2018 - 2021"
                },
                {
                    occupation : "Goodwood College",
                    words : "Passed with an acceptance to a bachelors degree pass",
                    year : "2013 - 2017"
                }
            ]
        }
    }
}
</script>
<style scoped>
.words
.space {
    margin: 5% auto;
    width: 100%;
    border-left: 5px solid silver;
    padding: 0 20px 0 30px;
    top: 0;
}
.dev {
    background-color: grey;
    padding: 10px 25px;
    font-size: 16px;
    box-shadow: 0px 0px 5px #ccc;
    border: 1px solid silver;
    line-height: 1.7;
    position: relative;

}

@media (min-width: 768px) {
    .timelines {
      display: flex;
      flex-wrap: nowrap;
    }
    .space {
      flex: 1;
      margin: 0 10px;
    }
  }
  
  #skills {
    padding-bottom: 2rem;
  }
  /* Vertical layout for small screens */
  @media (max-width: 767px) {
    .timelines {
      display: block;
    }
    .space {
      display: block;
      width: 100%;
      margin: 10px 0;
    }
  }
  
  
</style>