<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        #box {
            width: 150px;
            height: 150px;
            background-color: coral;
            text-align: center;
            line-height: 150px;
            color: white;
            font-weight: bold;
            border-radius: 10px;
        
        }
    </style>
</head>
<body>
    <h1> Mouse Events</h1>
    <div id="box">Hover Me</div>
    <script>
        let box= document.getElementById("box");
        box.onmouseover= () => box.innerText="Mouse Over";
        box.onmouseout= () => box.innerText="Mouse Out";
        box.onclick= () => box.innerText="Mouse Clicked";
        </script>
</body>
</html>
