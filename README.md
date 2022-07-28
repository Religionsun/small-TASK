# small-TASK<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>gift </title>
</head>

<style>
    * {
        background-color: darkgoldenrod;
    }
    
    .container {
        position: relative;
        display: block;
        height: auto;
        width: 75vw;
        margin: 4rem;
    }
    
    .containertxt {
        position: relative;
        top: 50vh;
    }
    
    .images {
        position: relative;
        top: 30vh;
        width: auto;
        height: 100vh;
        margin: 1rem;
        display: flex;
        left: 50%;
        transform: translate(-50%, -50%);
        justify-content: space-between;
    }
    
    .images img {
        top: 0;
        width: 20rem;
        height: auto;
        margin-left: 10%;
    }
    
    .img1 {
        float: left;
        box-shadow: 0 1rem 2rem rgba(0, 0, 0, 100%);
    }
    
    .img2 {
        float: right;
        box-shadow: 0 1rem 2rem rgba(0, 0, 0, 100%);
    }
    
    .img3 {
        position: relative;
        left: 45%;
        top: 1vh;
        transform: translateX(-50%, -50%);
        box-shadow: 0 1rem 2rem rgba(0, 0, 0, 100%);
    }
    
    .centerimg {
        width: 75%;
        height: auto;
        margin: 1rem;
    }
    
    #btm {
        position: relative;
        top: 75vh;
        font-style: oblique;
    }
    
    img {
        -webkit-box-reflect: below 0px linear-gradient(to bottom, rgba(0, 0, 0, 0.0), rgba(0, 0, 0, 0.4));
    }
    
    .animate-charcter {
        text-transform: uppercase;
        background-image: linear-gradient( -225deg, #231557 0%, #44107a 29%, #ff1361 67%, #fff800 100%);
        background-size: auto auto;
        background-clip: border-box;
        background-size: 200% auto;
        color: #fff;
        background-clip: text;
        text-fill-color: transparent;
        -webkit-background-clip: text;
        -webkit-text-fill-color: transparent;
        animation: textclip 2s linear infinite;
        display: inline-block;
        font-size: 5rem;
        margin-left: 3rem;
    }
    
    @keyframes textclip {
        to {
            background-position: 200% center;
        }
    }
    
    .clearfix::after {
        content: "";
        clear: both;
        display: table;
    }
    
    #spoiler {
        height: 1000vh;
        width: 1000vw;
        background-color: rgba(155, 155, 155, 0.987);
        z-index: 1000;
        position: absolute;
        top: 0;
    }
    
    #btn {
        z-index: 200;
        width: 5rem;
        height: 5rem;
        border-radius: 50%;
        transition: all .5s;
    }
</style>

</head>

<body>



    <audio style="display: none;" src="sadly.mp3" id="myAudio" controls loop 873y>

    </audio>

    <div class="clearfix container images">
        <img class="img1" src="1.jpg" alt="">
        <img class="img2" src="2.jpg" alt="">
    </div>

    <div class="centerimg">
        <img class="img3" src="salama.jpeg" alt="">
    </div>




    <h1 id="btm" class="animate-charcter"> يسألونى عن صديق الستة اعوام 🥦فقلت انه سلامه 🥦له مكان فى خاطرى *وله عندى مكانه 🥦ان لم يكن له صديقا*فلا يكن به ندامه 🥦لانى موجود هنا* اكفيه وازيد بزعامه 🥦نتذكر يوم ما كنا نلعب معا* فهو بتكثيف وانا بحصانه 🥦كانت ايام جيدة حقا 🥦اتمنى لو تعود يوما
        ولو مثقلاه 🥦كل عام وانت بخير يا صديقى🥦 واعذرنا عن تقصيرنا بزيادة 🥦فانت تعلم حال العبد الفقير لله *دعواك له باالتوفيق فى العلامه 🥦🥦🥦🥦 🥦🥦🥦وجمعنا اللة جيمعا فى جنته * واكرم مثواك وحسن ختامه 🥦🥦🥦🥦🥦
    </h1>




    <div id="spoiler" onclick="startAudio()">
        <button id="btn" onclick="startAudio()">أنقر للبدء</button>



        <script>
            function startAudio() {
                document.body.style.overflowY = "scroll"
                document.getElementById('btn').style.display = "none"
                document.getElementById('spoiler').style.display = "none"
                const audio = document.getElementById('myAudio')
                audio.play()
            }
        </script>
</body>

</html>
