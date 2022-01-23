<template>
    <html>
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
            <p class="story2">I made youtube to tell stories about what happened in my life.<br>
                Subscribe Me !!!
            </p>
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
    
}
.my-story{
    width: 100%;
    height: 100%;
    display:flex;
    justify-content:center;
    align-items:center;
    
    
}
.my-story  p{
    width:800px;
    height:300px;
    text-align:center;
    color:#E5DCC3;
    font-size:20px;
    transition: transform 250ms ease-out;

}
.story2{
    text-align:center;
    color:#E5DCC3;
    font-size:20px;
    margin-bottom:20px;
}
.youtube img{
    display:flex;
    margin:auto;
}

</style>