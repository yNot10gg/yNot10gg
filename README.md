margin: 0;

padding:

box-sizing: border-box;

}

body (

display: flex;

justify-content: center;

align-items: center;

min-height: 100vh;

background: whitesmoke;

font-family: Verdana, Geneva, Tahoma, sans-serif;

.gif {

height: 100%;

width: 100%;

}

h2 {

text-align: center;

font-size: 1.5em;

color: #e94d58;

margin: 15px 0;

}

.btn-group {

width: 100%;

height: 50px;

display: flex;

justify-content: center;

margin-top: 50px;

}

button (

position: absolute;

width: 150px;

height: inherit;

color: white;

font-size: 1.2em;

border-radius: 30px;

outline: none;

; cursor: pointer

box-shadow: 2px 4px gray;

border: 2px solid #e94d58;

font-size: 1.2em;

}

button:nth-child(1) {

margin-left: -200px;

} button:nth-child(2) {

background: #e94d58;

margin-right: -200px;

background: white;

color: #e94d58;

}
<!doctype html>

<html lang="en">

<head>

<meta charset="UTF-8">

<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Message for you</title

<link rel="stylesheet" href="style.css">

</head>

<div class="wrapper">

<body>

<h2 class="question">You like me?</h2>

<img class="gif" alt="gif"

src="https://raw.githubusercontent.com/DzarelDeveloper/Img/main/gifyou.webp"> <div class="btn-group"> <button class="yes-btn">Yes</button> <button class="no-

btn">No</button>

</div>

</div>

<script src="script.js"></script>

</body>

</html>

const wrapper document.querySelector(".wrapper");

const question = document.querySelector(".question");

const gif document.querySelector(".gif");

const yesBtn = document.querySelector(".yes-btn");

const noBtn = document.querySelector(".no-btn");

yesBtn.addEventListener("click", () {

question.innerHTML = "Aaaaa, I like you too";

"https://raw.githubusercontent.com/DzarelDeveloper/Img/main/gif.webp"; });

gif.src =

noBtn.addEventListener("mouseover", () {

const noßtnRect noßtn.getBoundingClientRect(); const maxX = window.innerWidth noßtnRect.width;

const maxy window.innerHeight noßtnRect.height;

const randomX = Math.floor(Math.random() maxx); const randomy = Math.floor(Math.random()* maxY);

noßtn.style.left = randomX + "px"; noßtn.style.top randomY + "px"; });