<html>
<head>
<title>Sign up for Facebook|Facebook</title>
<style>
body
{
background-color: #E9EBEE;
}
.h1
{
color:blue;
text-align: center;
font-size: 50px;
margin-top: 20px;
font-style: normal;
font-family: arial;
}
fieldset/* For box Creation*/
{
background-color: white;
width:20%;
height: 75%;
margin-left: 35%;
align-self: center;
border-radius: 10px;
border-style:outset;
border-color: white;
}
 h1
{
margin-top:10px;
font-size: 25px;
font-family: sans-serif;
font-weight: bolder;
}
fieldset p{
text-align:center;
font-weight: lighter;
}
.input{
border-radius:5px;
border-color:#E9EBEE;
width: 180px;
height: 40px;2
}
.input1
{
border-radius: 5px;
border-color:#E9EBEE;
width: 400px;
height: 40px;
color:blue;
}
fieldset label
{
font-weight: lighter;
font-family: monospace;
}
.input2
{
width: 120px;
height: 30px;
padding-left:20px;
padding-top: 5px;
margin-left: 10PX;
border-style:solid;
border-color: black ;
border-radius: 5px;
text-align: left;
font-size: 18px;
}
#b
{
background-color: green;
align-items: flex-end;
align-self: center;
margin-left: 120px;
width: 180px;
height: 30px;
margin-top:30px;
border-radius:5px;
color:white;
font-size: 20px;
}
#a
{
margin-top: 20px;
}
#a1
{
text-decoration: none;
}
#fe
{
margin-left: 20px;
border-color: #E9EBEE;
}
#Gender
{

}
</style>
</head>
<body>
<label>Time:-</label>  <span id="sai"></span>
    <script>
    function time()
    {
    var today=new Date();
    var h=today.getHours()-12;
    var m=today.getMinutes();
    var s=today.getSeconds();
    document.getElementById('sai').innerHTML=h+":"+m+":"+s;
    setInterval("time()",1000);
    }
    time();
    </script>
<h1 class="h1">fɑcebook</h1>
<div>
<fieldset>
<h1 align="center">Create a new account</h1>
<p>It's Quick And Easy</p><hrz><br>
<form>
<input type="text" size="20" placeholder="First name"n required class="input">
<input type="text" size="20" placeholder="Surname" required class="input"><br><br>
<input type="email" size="20" placeholder="Mobile or E-mail" required class="input1"><br><br>
<input type="password" size="20" placeholder="New password" required class="input1"><br><br>
<label>Date of Birth ?</label><br>
<input type="date" class="input1"><br><br>
<label id="gender">Gender</label><br><br>
<label class="input2" id="fe">Male<input type="radio" name="sex"value="Male" required></label>
<label class="input2" id="fe">Female<input type="radio" name="sex" value="Female" required></label>
<label class="input2" id="fe">Custom<input type="radio" name="sex" value="custom" required></label>
<button id="b">Sign up</button>
<p id="a"><a id="a1" href="facebooklogin.html">Already Have Account</a></p>
</fieldset>
</div>
</body>
</html>
Footer
