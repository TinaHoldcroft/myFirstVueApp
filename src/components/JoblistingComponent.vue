<template>
    <div class="[ row ]">
        <div class="[ col-sm-4 ]">
            <div class="[ card ]">
                <div><img></div>
                <div class="[ card--information ]"><br>
                    <span>Date Created: </span><br>
                    <span>Title: </span><br>
                    <span>Company Name: </span><br>
                    <span>Location: </span><br>
                    <span>Type: </span><br>
                    <span>Description: </span><br>
                    <span>How to apply: </span><br>
                    <span>Company Website: </span><a href="" target="_blank">Click Here</a><br>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'JobListingComponent',
}
</script>

<style scoped>
.card{
    border-radius: 10px;
    padding: 0px 20px 30px;
    position: absolute;
    top: 50vh;
    left: 50vw;
    width: 30rem;
    margin-left: -15rem;
    margin-top: -15rem;
    box-shadow: 4px 2px 16px rgba(136, 165, 191, 0.48), -4px -2px 16px #FFFFFF;
}
.card img{
    width: 100%;
    padding-top: 20px;
}
.card span{
    font-weight: bold;
}
</style>