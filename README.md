<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Developer Profile Card</title>

<style>

*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:Arial,sans-serif;
}

body{
height:100vh;
display:flex;
justify-content:center;
align-items:center;
background:linear-gradient(135deg,#667eea,#764ba2);
}

.card{
width:320px;
background:white;
padding:25px;
border-radius:20px;
text-align:center;
box-shadow:0 10px 25px rgba(0,0,0,0.2);
transition:.3s;
}

.card:hover{
transform:translateY(-10px) scale(1.03);
}

.profile{
width:120px;
height:120px;
border-radius:50%;
margin:auto;
background:#ddd;
display:flex;
justify-content:center;
align-items:center;
font-size:50px;
}

h2{
margin-top:15px;
}

.role{
color:#666;
margin:10px 0;
}

.skills{
display:flex;
flex-wrap:wrap;
justify-content:center;
gap:8px;
margin-top:15px;
}

.skills span{
background:#667eea;
color:white;
padding:6px 12px;
border-radius:20px;
font-size:14px;
}

button{
margin-top:20px;
padding:10px 20px;
border:none;
border-radius:25px;
background:#764ba2;
color:white;
cursor:pointer;
font-weight:bold;
}

button:hover{
opacity:.9;
}

</style>
</head>
<body>

<div class="card">

<div class="profile">👩‍💻</div>

<h2>Asmita Ashmi</h2>

<p class="role">
Frontend Developer Learner
</p>

<div class="skills">
<span>HTML</span>
<span>CSS</span>
<span>JavaScript</span>
<span>Git</span>
</div>

<button onclick="showMessage()">
View Profile
</button>

</div>

<script>

function showMessage(){

alert(
"Welcome to my Developer Profile 🚀"
);

}

</script>

</body>
</html>
