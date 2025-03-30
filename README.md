<!DOCTYPE html>
<html>
<head>
    <title>background change</title>
<link rel="stylesheet" href="rcg2.css">
    
</head>
<body  id="bd">

    
    <!--<button id="bu" onclick="colour()" >Change background</button>-->


    <script>
        var clicks = 0;
        function tclick() {
            clicks += 1;
            document.getElementById("clickss").textContent = clicks;
 

            switch(clicks){
    case 1:
    document.getElementById("bd").style.background="blue";
    break;
    case 2:
        document.getElementById("bd").style.background="green";
        break;    
        case 3:
    document.getElementById("bd").style.background="blue";
    break;
    case 4:
    document.getElementById("bd").style.background="red";
    break;
    case 5:
    document.getElementById("bd").style.background="yellow";
    break;
    case 6:
    document.getElementById("bd").style.background="rgb(2,4,5)";
    break;case 7:
    document.getElementById("bd").style.background="cyan";
    break;
    case 8:
    document.getElementById("bd").style.background="violet";
    break;
    case 9:
    document.getElementById("bd").style.background="purple";
    break;
    case 10:
    document.getElementById("bd").style.background="rgb(56,98,101)";
    break;
    case 11:
    document.getElementById("bd").style.background="black";
    break;
    case 12:
    document.getElementById("bd").style.background="skyblue";
    break;
    case 13:
    document.getElementById("bd").style.background="aqua";
    break;
    case 14:
    document.getElementById("bd").style.background="blue";
    break;
    case 15:
    document.getElementById("bd").style.background="pink";
    break;
 default:
        document.getElementById("bd").style.background="white";
        };}
        </script>
       <div id="bdt">
       <button id="bp" type="button" onClick="tclick()">Click me</button>
        <p id="pa">Clicks: <span id="clickss">0</span></p>
        </div>

    



</body>
</html>
//css
#bdt{
    margin-top: 500px;
    

    padding-left: 400px;
}
#pa{
    font-size: large;
}
#bp{
    border:10px solid  yellowgreen;
    color: lightseagreen;
    font-size: larger;
}
#pa{
    font-size: x-large;
    padding-left: 8px;
    color: skyblue;
}
