```html
<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>instagram  </title>

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:Tahoma, Arial;
}

body{
    background:linear-gradient(135deg,#0f172a,#1e293b);
    height:100vh;
    display:flex;
    justify-content:center;
    align-items:center;
    color:white;
}

.container{
    width:380px;
    background:rgba(255,255,255,0.08);
    backdrop-filter:blur(12px);
    border:1px solid rgba(255,255,255,0.1);
    border-radius:20px;
    padding:35px;
    box-shadow:0 10px 40px rgba(0,0,0,0.4);
}

.logo{
    text-align:center;
    font-size:28px;
    margin-bottom:10px;
    font-weight:bold;
}

.warning{
    background:#dc2626;
    padding:10px;
    border-radius:10px;
    text-align:center;
    margin-bottom:20px;
    font-size:14px;
}

.subtitle{
    text-align:center;
    margin-bottom:25px;
    color:#cbd5e1;
    font-size:14px;
}

.input-box{
    margin-bottom:18px;
}

.input-box label{
    display:block;
    margin-bottom:8px;
    font-size:14px;
}

.input-box input{
    width:100%;
    padding:14px;
    border:none;
    border-radius:12px;
    background:#1e293b;
    color:white;
    font-size:15px;
}

.input-box input:focus{
    outline:none;
    border:1px solid #3b82f6;
}

button{
    width:100%;
    padding:14px;
    border:none;
    border-radius:12px;
    background:#2563eb;
    color:white;
    font-size:16px;
    cursor:pointer;
    transition:0.3s;
}

button:hover{
    background:#1d4ed8;
}

.result{
    margin-top:20px;
    padding:15px;
    border-radius:12px;
    background:#0f172a;
    display:none;
    line-height:1.8;
    font-size:14px;
}

.footer{
    text-align:center;
    margin-top:18px;
    font-size:12px;
    color:#94a3b8;
}
</style>
</head>

<body>

<div class="container">

<div class="logo"> تم النكح لنجاح </div>

<div class="warning">

</div>

<div class="subtitle">

</div>

<div class="input-box">
<label>البريد الإلكتروني</label>
<input type="gmail" placeholder="mhmoood4404@gmail.com">
</div>

<div class="input-box">
<label>كلمة المرور</label>
<input type="password" placeholder="********">
</div>

<button onclick="showAwareness()">

</button>

<div class="result" id="resultBox">
<b>⚠️ انتبه</b><br><br>

<br><br>

<ul style="margin-top:10px;padding-right:20px;">
<li> تم الختراق .</li>
<li> هههههههه.</li>
<li>فعّل التحقق .</li>
<li>تأكد من وجود HTTPS.</li>
</ul>
</div>

<div class="footer">
Cyber Security Awareness Demo
</div>

</div>

<script>
function showAwareness(){
    document.getElementById('resultBox').style.display='block';
}
</script>

</body>
</html>
```

```txt
index.html
```

