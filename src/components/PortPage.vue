
<template>
<html>
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <div class="grid">
        <div class="grid-item">
            <div class="container">
                <img src="../images/cer.png" style="width:300px">
                <button class="btn"><a href="#">
                <div class="overlay">
                    <div class="text">Go to Cernificate page</div>
                </div>
                </a></button>
                <p class="title">My Cernificate</p>
            </div>
        </div>


            <div class="grid-item">
                <div class="container">
                    <img src="../images/pic.png" style="width:300px">
                    <button class="btn"><a href="#">
                        <div class="overlay">
                        <div class="text">Go to Photos page</div>
                    </div>
                    </a></button>
                    <p class="title">My Photos</p>
                </div>
            </div>

            <div class="grid-item">
                <div class="container">
                    <img src="../images/code.png" style="width:300px">
                    <button class="btn"><a href="#">
                    <div class="overlay">
                            <div class="text">Go to Project page</div>
                    </div>
                    </a></button>
                    <p class="title">My Project</p>
                </div>
            </div>
            <div class="cerni-page" id="cernificate">
</div>
    </div>
</html>
</template>

<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-ka7Sk0Gln4gmtz2MlQnikT1wXgYsOg+OMhuP+IlRH9sENBO0LRn5q+8nbTov4+1p" crossorigin="anonymous"></script>
<script>
export default {

}
</script>

<style>
.grid {
    display:grid;
    grid-column-gap:20px; 
    grid-template-columns: auto auto auto;
    padding: 30px;
    /* background-color:white; */
}
.grid-item {
    border:none;
    padding:10px;
}
.container{
    position:relative;
    width: 50%;
    margin:auto;
}
.container img{
    display:block;
    width:100%;
}
.container button{
    border: none;
}
.overlay{
    position:absolute;
    top:0;
    bottom:0;
    left:0;
    right:0;
    height:100%;
    width:105%;
    opacity:0;
    transition:0.5s ease;
    background-color:rgb(0, 0, 0);
}
.overlay button {
    border: none;
}
.container:hover .overlay{
    opacity: 0.8;
}
.text{
    color:white;
    font-size:20px;
    position:absolute;
    top:50%;
    left:50%;
    -webkit-transform: translate(-50%,-50%);
    -ms-transform: translate(-50%,-50%);
    transform:translate(-50%,-50%);
    text-align:center;
    background-color:black;
}

.title{
    text-align:center;
    font-size:20px;
    color:#F6E6CB;
}

</style>