<html>
<head> How this appears? </head>
<body> 12345 </body>
</html>


Window {
    width: 200px;
    height: 200px;
    Rectangle {
        x: 100px;
        y: 70px;
        width: parent.width - x;
        height: parent.height - y;
        background: blue;
        Rectangle {
            x: 10px;
            y: 5px;
            width: 50px;
            height: 30px;
            background: green;
        }
    }
}
