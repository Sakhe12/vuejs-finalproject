<template lang="">
    <div>
        <div v-for="timeline in resume" :key="timeline" class="space">
            <h2 class="display-2"></h2>
            <p class="lead"></p>
            <p class="lead"></p>
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
                    Occupation : "Life Choices Coding Academy",
                    words : "hvhv",
                    year : 2022 - 2000
                },
                {
                    Occupation : "Mr D Food Flexi-Perm Customer Service Agent",
                    words : "Call center agent who primarily dealt with order related queries and app troubleshooting. I also sometimes dealt with escalations.",
                    year : 2020 - 2022
                },
                {
                    Occupation : "University of the Western Cape",
                    words : "I was studying Bachelor of Arts majoring in Political studies and History, unfortunately did not finish the course as it was not my passion.",
                    year : 2018 - 2021
                },
                {
                    Occupation : "Goodwood College",
                    words : "Passed with an acceptance to a bachelors degree pass",
                    year : 2013 - 2017
                }
            ]
        }
    }
}
</script>
<style scoped>
.space {
    margin: 90px auto;
    width: 360px;
    border-left: 2px solid whitesmoke;
    padding: 0 20px 0 30px;
}
    
</style>