# JQuery-assignment
<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <script src="jquery-3.7.1.slim.js"></script>
</head>
<body>
    <button id="hello">click me</button>
    <div id="clickme" style="width: 400px; height: 400px; background-color: aqua;"></div>
    <button id="test">Test</button>
    <script>
        const browser = $(window);
        browser.ready(function(){
            $('#hello').click(function(){
                $("#clickme").css('background', 'red');
            });
            $('#clickme').toggle('4000');
        });
    </script>
</body>
</html>
