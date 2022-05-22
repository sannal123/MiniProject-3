# MiniProject-3
JavaScript Working to create Mini Project #3
<!DOCTYPE html>
<html lang="en">
<head>
<title>Mini Project 3</title>
</head>
    <body>
        <h1>Mini Project #3</h1>
        <h4 id="elem"></h4>
     
        <script>
            var num =prompt("Enter a Number ")
            console.log(typeof(num))
            num = Number(num)
            
            if(num){
                if(num>=18){
                    var elem = document.getElementById("elem");
                    elem.innerHTML="You are 18 or older!!!"
                }
            }
        
        </script>
    </body>
</html>
