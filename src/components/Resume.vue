<template lang="">
    <div>
        <div class=".space" v-for="timeline in resume" :key="timeline">
            <div class="row justify-content-center">
                <div class="col-md-6">
                  <div class="card">
                    <div class="card-body">
                      <h5 class="card-title"><strong>{{timeline.occupation}}</strong></h5>
                      <p class="card-text">{{timeline.words}}</p>
                      <p class="card-text">{{timeline.year}}</p>
                    </div>
                  </div>
                </div>
              </div>
        </div>
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
                    year : "2022 - 2000"
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
.row {
    padding-bottom: 3rem;
}
.card {
    background-color: #A3BB98;
    overflow-x: hidden;
}
</style>