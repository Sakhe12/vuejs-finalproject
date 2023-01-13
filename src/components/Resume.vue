<template>
    <div class="words">
        <section class=" space container" v-for="timeline in resume" :key="timeline">
            <div class="dev">
                <h4 class="display-4">{{timeline.occupation}}</h4>
                <p class="lead">{{timeline.words}}</p>
                <p class="lead">{{timeline.year}}</p>
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
                    words : "hvhv",
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
    margin: 90px auto;
    width: 360px;
    border-left: 5px solid silver;
    padding: 0 20px 0 30px;
    top: 0;
}
.dev {
    background-color: grey;
    padding: 10px 25px;
    font-size: 16px;
    border: 1px solid silver;
    line-height: 1.7;
    position: relative;

}
.dev:before {
    content: "";
    display: block;
    width: 20px;
    min-height: 20px;
    border-radius: 50%;
    background-color: black;
    border: 1px solid whitesmoke;
    position: absolute;
    top: 10%;
    left: -14%;
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