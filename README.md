<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="author" content="Aditya raj singh">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="keywords" content="About Phone/Computer">
    <title>Properties by Aditya raj singh ©.</title>
    <script>
        alert(" Welcome to my Webpage " + "By " + " Aditya raj singh ©. ");
    </script>
    <style>
        body {
            background: black;
            transition-property: background;
            transition-duration: 3s;
        }
        
        body:hover {
            background: rgb(225, 225, 225);
        }
        
        .user {
            box-shadow: 0 4px 8px 0 rgb(0, 0, 0, 0.2), 0 8px 16px 0 rgb(0, 0, 0, 0.4);
            border-radius: 100px;
            width: 95%;
            max-height: auto;
            background: rgb(6, 181, 240);
            font-size: 25px;
            text-align: center;
            line-height: 2rem;
            font-family: monospace;
        }
        
        .cards {
            box-shadow: 0 4px 8px 0 rgb(0, 0, 0, 0.2);
            transition: 0.3s;
            width: 80%;
            font-size: 20px;
            background: white;
            text-align: center;
            text-decoration: none;
            font-family: Comic Sans MS;
            border: 1px double blue;
            border-radius: 5px;
            letter-spacing: 0px;
            transition-property: background, color, border-radius, letter-spacing, border, text-decoration, box-shadow;
            transition-duration: 1s, 2s, 2s, 3s, 2s, 2s, 3s;
        }
        
        .cards:hover {
            box-shadow: 0 8px 16px 0 rgb(250, 246, 246, 0.2), 0 16px 32px 0 rgb(250, 246, 246, 0.2);
            background: rgb(191, 233, 250);
            color: darkblue;
            border-radius: 30px;
            border: 10px double blue;
            letter-spacing: 1px;
            text-decoration: underline;
        }
        
        span {
            color: darkred;
            transition-property: color;
            transition-duration: 2s;
        }
        
        span:hover {
            color: red
        }
        
        html {
            animation-name: myAnimation;
            animation-duration: 6s;
            animation-fill-mode: both;
        }
        
        p {
            animation-name: myAnimation;
            animation-duration: 6s;
            animation-fill-mode: both;
        }
        
        #copywrite {
            animation-name: copywrite;
            animation-duration: 4s;
            animation-iteration-count: infinite;
            animation-direction: alternate;
            animation-play-state: running;
            animation-timing-function: easy-out;
        }
        
        @keyframes myAnimation {
            from {
                font-size: 0px;
                color: green;
            }
            to {
                font-size: 20px;
                color: black;
            }
        }
        
        @keyframes copywrite {
            0% {
                width: 20%;
                background: rgb(42, 42, 255);
                color: white;
                border-radius: 0px;
            }
            15% {
                background: green;
                color: gold;
                border-radius: 4.5%;
            }
            25% {
                background: rgb(245, 4, 4);
                color: rgb(11, 255, 44);
                border-radius: 7.5px;
            }
            50% {
                background: rgb(18, 142, 151);
                color: darkblue;
                border-radius: 15px;
            }
            75% {
                background: rgba(243, 247, 0, 0.596);
                color: rgb(8, 223, 19);
                border-radius: 22.5px;
            }
            85% {
                background: rgb(255, 194, 194);
                color: maroon;
                border-radius: 25.5px;
            }
            100% {
                width: 95%;
                background: rgb(6, 240, 123);
                color: black;
                border-radius: 30px;
            }
        }
        
         ::-webkit-scrollbar {
            width: 0%;
        }
        
         ::-webkit-scrollbar-track {
            box-shadow: inset 5px 6px 10px skyblue;
        }
        
         ::-webkit-scrollbar-thumb {
            background: blue;
            border-radius: 100%;
        }
        
        #can-not-print {
            color: darkblue;
            display: none;
        }
        
        #property {
            animation-name: property;
            animation-duration: 6s;
            animation-iteration-count: infinite;
            animation-direction: alternate;
            animation-play-state: running;
            animation-timing-function: easy-out;
        }
        
        @keyframes property {
            0% {
                color: darkblue;
            }
            5% {
                color: aqua;
            }
            15% {
                color: white;
            }
            25% {
                color: black;
            }
            35% {
                color: darkgreen;
            }
            50% {
                color: yellow;
            }
            55% {
                color: rgb(206, 51, 206);
            }
            75% {
                color: red;
            }
            85% {
                color: lime;
            }
            95% {
                color: purple;
            }
            100% {
                color: green;
            }
        }
        
        @media print {
            html {
                display: none;
            }
        }
    </style>
</head>

<body>
    <section>
        <article>
            <center>
                <p class="user" id="property">Properties</p>
                <p class="cards" style="margin-top:50px;">Online : <span id="onLine"></span></p>
                <p class="cards">Width of the screen : <span id="width"></span></p>
                <p class="cards">Height of the screen : <span id="height"></span></p>
                <p class="cards">Available vertical space of the screen : <span id="available-width"></span></p>
                <p class="cards">Available horizontal space of the screen: <span id="available-height"></span></p>
                <p class="cards">Orientation of the screen : <span id="orientation"></span></p>
                <p class="cards">Bit or pixel of the screen : <span id="bit-or-pixel"></span></p>
                <p class="cards">Color depth of the screen : <span id="color-depth"></span></p>
                <p class="cards">Product : <span id="product"></span></p>
                <p class="cards">Product Sub : <span id="productSub"></span></p>
                <p class="cards">User Agent : <span id="userAgent"></span></p>
                <p class="cards">Permissions : <span id="permissions"></span></p>
                <p class="cards">Vendor : <span id="vendor"></span></p>
                <p class="cards">Platform : <span id="platform"></span></p>
                <p class="cards">Language : <span id="language"></span></p>
                <p class="cards">App Name : <span id="appName"></span></p>
                <p class="cards">App Code Name : <span id="appCodeName"></span></p>
                <p class="cards">App Version : <span id="appVersion"></span></p>
                <p class="user" id="copywrite" style="margin-top:50px;">Aditya raj singh<sup>&copy;</sup></p>
            </center>
            <h1 id="can-not-print">You can't <mark>Print</mark> this webpage.</h1>
        </article>
    </section>

    <script>
        document.getElementById("onLine").innerHTML = navigator.onLine;
        document.getElementById("width").innerHTML = screen.width;
        document.getElementById("height").innerHTML = screen.height;
        document.getElementById("available-width").innerHTML = screen.availWidth;
        document.getElementById("available-height").innerHTML = screen.availHeight;
        document.getElementById("orientation").innerHTML = screen.orientation.type;
        document.getElementById("bit-or-pixel").innerHTML = screen.pixelDepth;
        document.getElementById("color-depth").innerHTML = screen.colorDepth;
        document.getElementById("product").innerHTML = navigator.product;
        document.getElementById("productSub").innerHTML = navigator.productSub;
        document.getElementById("userAgent").innerHTML = navigator.userAgent;
        document.getElementById("permissions").innerHTML = navigator.permissions;
        document.getElementById("vendor").innerHTML = navigator.vendor;
        document.getElementById("platform").innerHTML = navigator.platform;
        document.getElementById("language").innerHTML = navigator.language;
        document.getElementById("appName").innerHTML = navigator.appName;
        document.getElementById("appCodeName").innerHTML = navigator.appCodeName;
        document.getElementById("appVersion").innerHTML = navigator.appVersion;
    </script>
</body>

</html>
