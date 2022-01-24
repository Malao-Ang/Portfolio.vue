
<template>
    <html>
        
        <meta name="viewport" content="width=device-width, initial-scale=1">
        <head>
            <div class="topic">
                <p class="title1"> . . . A b o u t&nbsp;&nbsp;M e</p>
            </div>
            <div class="profile">
                <img src="../images/mypic3.jpg">
            </div>
        </head>
            <div class="my-story">
                <p class="story">Hello everyone! </br></br>
                    In Thai, my name is Pim. Pim is a verb that literally meaning "to type."
                    I'm currently enrolled at Burapha University 
                    Faculty of Informatics(Computer Science) .
                    I'm interested in web development and game development,
                    therefore I'm starting with web authoring for now. In the future, 
                    I hope to create games that will motivate and guide me.
                </p>
            </div>
        
        <div class="youtube">
            <p class="title1">M y&nbsp;&nbsp;Y o u t u b e &nbsp;&nbsp;C h a n n e l . . .</p>
            <img src="../images/youtube.png" style="width:1000px">
            <p class="story2">&#10024; I made youtube to tell stories about what happened in my life. &#10024;<br>
                Subscribe Me !!!
            </p>
            <button>
                <a href="https://www.youtube.com/channel/UCm03p8JqLg8tsljn0L4FfHg" target="_blank">
                <img src="https://www.nicepng.com/png/full/4-43181_the-subscribe-button-sign.png" style="width:300px" />
                </a>
            </button>
        </div>
        <div class="vedio">
            <iframe class="grid-item" width="560" height="315" src="https://www.youtube.com/embed/OzmQxMIhC3s" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
            <iframe class="grid-item" width="560" height="315" src="https://www.youtube.com/embed/M_WvwYrrFWw" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
            <iframe class="grid-item" width="560" height="315" src="https://www.youtube.com/embed/jLNtW2w_YF8" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
            <iframe class="grid-item" width="560" height="315" src="https://www.youtube.com/embed/RrgKCsgKxx0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
            <iframe class="grid-item" width="560" height="315" src="https://www.youtube.com/embed/ZuBSwJwAD8s" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
            <iframe class="grid-item" width="560" height="315" src="https://www.youtube.com/embed/5EPywT3BBPM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
        </div>
        <div class="animal">
            <p class="title1">A n i m a l &nbsp;&nbsp;T h a t &nbsp;&nbsp;I &nbsp;&nbsp;&#128152;</p>
            <div class="grid">
                <div class="all">
                    <img class="grid-item" src="../images/cat.jpg" alt="cat">
                    <div class="overlay">&#127775; E Tip Non's Cat &#127775;</div>
                </div>
                <div class="all">
                    <img class="grid-item" src="../images/capibara.jpg" alt="cat">
                    <div class="overlay">&#127807; Capibara &#127807;</div>
                </div>
                <div class="all">
                    <img class="grid-item" src="../images/otter.jpg" alt="cat">
                    <div class="overlay">&#128167; Otter &#128167;</div>
                </div>
                <div class="all">
                    <img class="grid-item" src="../images/panda.jpg" alt="cat">
                    <div class="overlay">&#127808; Red panda &#127808;</div>
                </div>
                <div class="all">
                    <img class="grid-item" src="../images/rabbit.jpg" alt="cat">
                    <div class="overlay">&#127799; Rabbit &#127799;</div>
                </div>
                <div class="all">
                    <img class="grid-item" src="../images/fox.jpg" alt="cat">
                    <div class="overlay">&#127884; Japan fox &#127884;</div>
                </div>
            </div>
        </div>
        <div class="color">
            <p class="title1">M y &nbsp;&nbsp;f a v o r i t e &nbsp;&nbsp;A n i m e </p>
        </div>
    </html>
</template>

<script>

export default {


}

</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Courgette&family=Dancing+Script:wght@700&family=Playfair+Display:wght@500&display=swap');
head {
    display:block;
    text-align:right;
}
.profile img{
    height: 200px;
    display:flex;
    margin:auto;
    margin-top:50px;
    border: none;
    border-radius: 50%;
    transition: transform 250ms;
}
.profile img:hover {
    transform: translateY(-10px);
}
.title1{
    color:rgb(246, 230, 203);
    margin-top:10px;
    margin-right:20px;
    margin-left:20px;
    
}
.my-story{
    width: 100%;
    height: 100%;
    display:flex;
    justify-content:center;
    align-items:center;
    
    
}
.my-story  p{
    width:90%;
    height:20%;
    text-align:center;
    color:#E5DCC3;
    font-size:50px;
    transition: transform 250ms ease-out;

}
.story2{
    text-align:center;
    color:#343434;
    font-size:20px;
    margin-bottom:20px;
}
.youtube img{
    display:flex;
    margin:auto;
}
.youtube button{
    display:flex;
    margin:auto;
    border:none;
    transition: transform 250ms;
}
.youtube button:hover {
    transform: translateY(-10px);
}
.vedio {
    display: grid;
    grid-gap: 50px 20px ;
    grid-template-columns: auto auto auto;
    padding: 30px;
}
.grid-item{
    border: none;
    padding:20px;
}
.grid{
    display: grid;
    grid-gap: 50px 20px ;
    grid-template-columns: auto auto auto;
    padding: 30px;
}
.animal img{
    width :500px;
    height :500px;
    object-fit:cover;
    margin:auto;
    box-shadow: 0 4px 8px 0 rgba(0,0,0,0.2);
    
}
.all{
    position: relative;
    width:50%;
    max-width: 300px;
}
.overlay{
    position:absolute;
    bottom:0;
    background: rgb(52, 52, 52);
    background: rgba(0,0,0,0.5); /*see thoug */
    color: rgb(243, 243, 243);
    width:100%;
    transition:0.5s ease;
    opacity:0;
    font-size:20px;
    padding:50px;
    text-align: center;
}
.all:hover .overlay {
    opacity: 1;
}

</style>