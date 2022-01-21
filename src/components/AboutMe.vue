<template>
    <html>
        <head>
            <div class="topic">
                <p class="title1"> . . . A b o u t&nbsp;&nbsp;M e</p>
            </div>
        </head>
            <div class="my-story">
                <img class="about-img" src="../images/aboutpic2.png"/>
                <p class="story">Hello everyone! </br></br>
                    In Thai, my name is Pim. Pim is a verb that literally meaning "to type." </br>
                    I'm currently enrolled at Burapha University 
                    Faculty of Informatics</br>(Computer Science) .
                    I'm interested in web development and game development,
                    therefore I'm starting with web authoring for now. In the future, 
                    I hope to create games that will motivate and guide me.
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
    /* line-height:0; */
}
.title1{
    color:rgb(246, 230, 203);
    margin-top:10px;
    margin-right:20px;
    
}
.my-story{
    display:inline-flex;
    flex-direction: row;
}
.about-img{
    height:1500px;
    width:150px;
    object-fit: cover;
    display:block;
    position:relative;
    margin-top:10px;
    /* display:flex;
    flex:left; */
}

.my-story p{
    display:flex;
    margin-left:50px;
    margin-right:300px;
    color:#E5DCC3;
    font-size:20px;
}




</style>