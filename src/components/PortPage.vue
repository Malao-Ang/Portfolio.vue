
<template>
<html>
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/css/bootstrap.min.css" integrity="sha384-Gn5384xqQ1aoWXA+058RXPxPg6fy4IWvTNh0E263XmFcJlSAwiGgFAW/dAiS6JXm" crossorigin="anonymous">
        <div class="card-deck">
            <div class="card">
                <img class="card-img-top" src="@/images/cerni.jpg" alt="Card image cap">
                <div class="card-body">
                <h5 class="card-title">Cernificate</h5>
                <p class="card-text">You can examine the certificates I attempted to obtain in order to obtain these items. Ma isn't perfect, but I'm hoping things will come in handy in the future.</p>
                <button class="button_" ><span><a href="#">Click</a></span></button>
                </div>
        </div>
        <div class="card">
            <img class="card-img-top" src="https://scontent.fbkk2-8.fna.fbcdn.net/v/t1.6435-9/118382235_1273899476286503_7485940584378868862_n.jpg?_nc_cat=105&ccb=1-5&_nc_sid=730e14&_nc_eui2=AeGraTLfn1sF-nqW4fcu0_GggJPTSHuuJfiAk9NIe64l-L2OOnATwQbj5o_iHK1VBR88TgD-KiTpYFRlcd5qcLMy&_nc_ohc=6nC-tdpd55YAX-L1SU5&_nc_ht=scontent.fbkk2-8.fna&oh=00_AT-M15H3HQgfdeydP_yxTNGfHXT3Ux1cjrKn9wUvq7zVJg&oe=620FDFD4" alt="Card image cap" style="height:450px">
                <div class="card-body">
                    <h5 class="card-title">My Images</h5>
                    <p class="card-text">These are photos of all the activities I've participated in that I'd want to share with you.</p>
                    <button class="button_" ><span><a href="#">Click</a></span></button>
                </div>
        </div>
        <div class="card">
            <img class="card-img-top" src="https://camo.githubusercontent.com/d4c77e0ecd1192dfa105d7a167948356bebd41a8e00c906d55a9961bc78a3289/68747470733a2f2f313030306c6f676f732e6e65742f77702d636f6e74656e742f75706c6f6164732f323032312f30352f4769744875622d6c6f676f2e706e67" alt="Card image cap" style="height:450px">
            <div class="card-body">
                <h5 class="card-title">My Project</h5>
                <p class="card-text">You can recommend me for a project that I'm working on to enhance my coding skills.</p>
                <button class="button_" ><span><a href="#">Click</a></span></button>
            </div>
        </div>
        </div>
</html>
</template>

<script>
export default {

}
</script>

<style>
*{
    text-decoration: none;
}
.card{
    box-shadow: 0 4px 8px 0 rgba(0,0,0,0.2);
    transition: 0.3s;
}
.card:hover {
    box-shadow: 0 8px 20px 0 rgba(0,0,0,0.2);
}
.card img{
    background-color: white;
}
.card-body{
    background-color: rgb(199, 190, 162);
}
.card-title{
    background-color: rgb(199, 190, 162);
}
.card-text{
    background-color: rgb(199, 190, 162);
}
.button_{
    padding: 15px 25px;
    font-size: 24px;
    text-align: center;
    cursor: pointer;
    outline: none;
    color: #fff;
    background-color: rgb(229, 220, 195);
    border: none;
    border-radius: 15px;
}
.button_ span a{
    text-decoration:none;
    color: #fff;
}
.button_ span {
    cursor: pointer;
    display: inline-block;
    position: relative;
    transition: 0.5s;
    background-color:rgb(229, 220, 195);
}
.button_ span:after {
    content: '\00bb';
    position: absolute;
    opacity: 0;
    top: 0;
    right: -20px;
    transition: 0.5s;
}
.button_:hover span {
    padding-right: 25px;
}
.button_:hover span:after {
    opacity: 1;
    right: 0;
}

</style>