# aboutsubleadmarcom
<!DOCTYPE html>
<html lang="vi">
<head>
<meta charset="UTF-8">
<title>Kết quả Tuyển Chọn</title>

<style>
body{
    font-family: Arial, sans-serif;
    background: linear-gradient(135deg,#0f2027,#203a43,#2c5364);
    height:100vh;
    display:flex;
    justify-content:center;
    align-items:center;
    color:white;
}

.container{
    text-align:center;
}

h1{
    margin-bottom:40px;
}

.grid{
    display:grid;
    grid-template-columns:repeat(2,250px);
    gap:30px;
    justify-content:center;
}

.card{
    background:rgba(255,255,255,0.08);
    border-radius:12px;
    padding:25px;
    backdrop-filter:blur(10px);
    transition:0.4s;
}

.card:hover{
    transform:translateY(-5px);
}

.position{
    font-size:18px;
    opacity:0.7;
}

.result{
    font-size:22px;
    font-weight:bold;
    margin-top:15px;
    letter-spacing:1px;
}

.hidden{
    filter:blur(8px);
}

button{
    margin-top:40px;
    padding:12px 28px;
    border:none;
    border-radius:8px;
    font-size:16px;
    cursor:pointer;
    background:#ffcc00;
}

button:hover{
    background:#ffd633;
}
</style>

</head>

<body>

<div class="container">

<h1>RESULT ANNOUNCEMENT</h1>

<div class="grid">

<div class="card">
<div class="position">Vị trí 01</div>
<div class="result hidden">Nguyễn A</div>
</div>

<div class="card">
<div class="position">Vị trí 02</div>
<div class="result hidden">Trần B</div>
</div>

<div class="card">
<div class="position">Vị trí 03</div>
<div class="result hidden">Lê C</div>
</div>

<div class="card">
<div class="position">Vị trí 04</div>
<div class="result hidden">Phạm D</div>
</div>

</div>

<button onclick="reveal()">Công bố kết quả</button>

</div>

<script>

function reveal(){

let results = document.querySelectorAll(".result")

results.forEach((item,index)=>{
    
    setTimeout(()=>{
        item.classList.remove("hidden")
    }, index*1200)

})

}

</script>

</body>
</html>








