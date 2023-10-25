
<!DOCTYPE html>  
<html lang = "en">  
<head>  
  <title>Calculator</title>
  <style>
.div1{  
    text-align:center;  
    padding: 10px;  
    background-color: rgba(137, 54, 31, 0.92);  
    color: rgb(23, 21, 21); 
    border: 5px solid rgb(7, 7, 7); 
    width: 1200px;  
     height:16cm; 
    }  
  
#clear{  
width: 260px;  
border: 3px solid rgb(25, 10, 10);
    border-radius: 15px;  
    padding: 10px;  
    background-color: rgb(81, 76, 76);  
}  
  
.formstyle{  
width: 300px;  
height: 470px;  
margin: auto;  
border: 5px solid rgb(7, 7, 7);  
border-radius: 5px;  
padding: 20px;  
background-color: rgb(37, 83, 67);
}  
  
  
  
input{  
width: 20px;  
background-color: rgb(86, 89, 86);  
color: rgb(224, 239, 234);  
border: 3px solid rgb(11, 11, 11);  
    border-radius: 35px;  
    padding: 27px;  
    margin: 5px;  
    font-size: 15px;  
}  
  
  
#calc{  
width: 250px;  
border: 5px solid black;  
    border-radius: 3px;  
    padding: 20px;  
    margin: auto;  
} 
</style>  
</head>  
<body> 
  <div class="div1"> 
  <h1>CALCULATOR</h1> 
<div class= "formstyle">  
<form name = "form1">  
 <!-- This input box shows the button pressed by the user in calculator. -->  
  <input id = "calc" type ="text" name = "answer"> <br> <br>  
  <!-- Display the calculator button on the screen. -->  
  <!-- onclick() function display the number prsses by the user. -->  
  <input type = "button" value = "1" onclick = "form1.answer.value += '1' ">  
  <input type = "button" value = "2" onclick = "form1.answer.value += '2' ">  
  <input type = "button" value = "3" onclick = "form1.answer.value += '3' ">  
   <input type = "button" value = "+" onclick = "form1.answer.value += '+' ">  
  <br>   
    
  <input type = "button" value = "4" onclick = "form1.answer.value += '4' ">  
  <input type = "button" value = "5" onclick = "form1.answer.value += '5' ">  
  <input type = "button" value = "6" onclick = "form1.answer.value += '6' ">  
  <input type = "button" value = "-" onclick = "form1.answer.value += '-' ">  
  <br>  
    
  <input type = "button" value = "7" onclick = "form1.answer.value += '7' ">  
  <input type = "button" value = "8" onclick = "form1.answer.value += '8' ">  
  <input type = "button" value = "9" onclick = "form1.answer.value += '9' ">  
  <input type = "button" value = "*" onclick = "form1.answer.value += '*' ">  
  <br>   
    
  <input type = "button" value = "/" onclick = "form1.answer.value += '/' ">  
  <input type = "button" value = "0" onclick = "form1.answer.value += '0' ">  
    <input type = "button" value = "." onclick = "form1.answer.value += '.' ">  
    <!-- When we click on the '=' button, the onclick() shows the sum results on the calculator screen. -->  
  <input type = "button" value = "=" onclick = "form1.answer.value = eval(form1.answer.value) ">  
  <br>   
  <!-- Display the Cancel button and erase all data entered by the user. -->  
  <input type = "button" value = "Clear All" onclick = "form1.answer.value = ' ' " id= "clear" >  
  <br>   
</form>  
</div>  
  </div>
</body>  
</html>  
