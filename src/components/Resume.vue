<template>
    <section class="timelines container-fluid">
        <div class="row space" v-for="timeline in resume" :key="timeline">
            <div class=" attack-titan">
                <h4 class="display-4">{{timeline.occupation}}</h4>
                <p class="lead">{{timeline.words}}</p>
                <p class="lead">{{timeline.year}}</p>
            </div>
        </div>
    </section>
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
  
</style>