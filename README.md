<body>

<div class="wrapper">

<p id="question">Mahal mo ba ako?</p>

<div class="container"> <button class="btn" id="hindi">Hindi</button>

<button class="btn" id="yes">Yes</button>

</div>

</div>

</body>

<script>

const noBtn = document.getElementById('hindi');

const yesBtn = document.getElementById('yes');

const ques= document.getElementById('question");

noBtn.addEventListener("click", ()=>{

let rand Math.floor(Math.random() (see - 100) + 1);

let rand2 = Math.floor(Math.random() (-308 - 100) + 1); noBtn.style.transform="translate("+rand+"px, "+rand2+"px)";

yesBtn.addEventListener("click", ()->{

ques.innerHTML = "I love you too mark"

})

</script> </html>
