<
<metacharset=“UTF-8”>
<metaname="viewport"content=“width=device-width, initial-scale=1.0”>
<metahttp-equiv="X-UA-Compatible"content=“ie=edge”>
<title>Twitter Like</title>
<style>
body {!DOCTYPE html>
<htmllang=“en”>
<head>
display: flex;
justify-content: center;
align-items: center;
height: 100vh;
margin: 0;
}
.like{
background-color: white;
border: 0;
cursor: pointer;
/width: 100px;
height: 100px;/
width: 50px;
height: 50px;
background-image: url(‘corazon.png’);
outline: 0;
background-size: 1450px50px;
}
.like.is-liked{
animation-name: like;
animation-duration: .8s;
animation-timing-function: steps(28);
animation-fill-mode: forwards;
}
@keyframes like {
0%{
background-position: 00;
}
100%{
/background-position: -2800px 0;/
/background-position: -1450px 0;/
background-position: right;
}
}
</style>
</head>
<body>
<divclass=“tweet-box”>
<buttonclass="like"id=“like”>
</button>
</div>
<script>
const $like = document.getElementById(‘like’);
/* $like.addEventListener(‘evento’, que hace el evento)*/
$like.addEventListener(‘click’, (event) => {
/console.log(event);/
$like.classList.toggle(‘is-liked’)
})
</script>
</body>
</html>```
