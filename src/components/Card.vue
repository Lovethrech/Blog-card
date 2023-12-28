<template>
    <div class="card-container">
        <div class="card-image-container">
            <img src="../assets/illustration-article.svg" alt="illustration image" class="card-image">
        </div>
        <div class="text">
            <button class="action">Learning</button>
            <p class="date">Published 21 Dec 2023</p>
            <h1 class="title">HTML & CSS foundations</h1>
            <p class="title-text">These languages are the backbone of every website,
                defining structure, content, and presentation. 
            </p>
            <div class="author">
                <div class="author-image-container">
                    <img src="../assets/image-avatar.webp" alt="Author" class="author-image">
                </div>
                <div class="author-name">Greg Hooper</div>
            </div>
            <!--  -->
        </div>
        <p class="challenge">Challenge by Frontend Mentor. Coded by <a href="https://github.com/Lovethrech" style="text-decoration:none; color: hsl(47, 88%, 63%); ">Lovethrech</a></p>
    </div>
</template>

<style scoped>
.card-container{
    background-color: hsl(0, 100%, 100%);
    padding:3vh 2vw;
    margin:40px;
    border-radius:20px;
    box-shadow: 10px 10px 0px hsl(0,0%,0%);
}
.card-container:hover{
    box-shadow: 10px 10px 0px #000000;
}
.card-image-container{
    text-align: center;
}
.card-image{
    width:100%;
    border-radius:20px;

}
.text{
    margin-top:2vh;
}
.action{
    background-color: hsl(47, 88%, 63%);
    padding:0 0.2vw 0 0.2vw;
    font-weight:600;
    border:2px solid hsl(47, 88%, 63%);
}
.title{
    font-weight: 800;
}
.title:hover{
    cursor:pointer;
    color:hsl(47, 88%, 63%);
}
.title-text{
    color:hsl(0, 0%, 50%);
}
.author{
    display:flex;
    gap: 10px;
}
.author-image{
    width:30px;
}
.author-name{
    margin:auto 0;
    font-weight:600;
}
.challenge{
    font-size:10px;
    text-align:center;
}
</style>
