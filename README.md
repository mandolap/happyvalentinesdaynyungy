<meta name='viewport' content='width=device-width, initial-scale=1'/><!DOCTYPE html>

<html lang="de">

<head>

    <meta charset="UTF-8">

    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Happy Valentine's Day Nyungy</title>

    <style>

        body {

            font-family: Times;

            margin: 0;

            padding: 20px;

            background-color: #f4f4f4;

        }



        h1 {

            text-align: center;

            color: #333;

        }



        ul {

            list-style-type: none;

            padding: 0;

        }



        li {

            margin: 10px 0;

        }



        a {

            text-decoration: none;

            color: #007BFF;

            font-size: 18px;

        }



        a:hover {

            color: #0056b3;

        }



        .container {

            max-width: 800px;

            margin: 0 auto;

            background-color: #fff;

            padding: 20px;

            border-radius: 8px;

            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);

        }

    </style>

</head>

<body>



    <div class="container">

        <h1>Be my Valentine &hearts; </h1>

    <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Schwebendes Zitat</title>
    <style>
        body {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 95vh;
            background-color: #ffe6f2;
            margin: 0;
            overflow: hidden;
        }
        .quote {
            font-style: italic;
            font-size: 15px;
            color: #ff1493;
            text-align: center;
            animation: gentleFloat 10s infinite ease-in-out;
        }
        @keyframes gentleFloat {
            0% { transform: translateY(0); }
            50% { transform: translateY(-5px); }
            100% { transform: translateY(0); }
        }
    </style>
</head>
<body>
    <div class="quote">"Herzen verlieren sich im Dunkeln, doch Licht wird oft wiedergefunden – durch sich selbst oder durch andere."</div>
</body>
</html>
        
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Checkliste mit Links</title>
</head>
<body>
   <style>
        body {
            font-family: "Times New Romans", serif;
            background-color: #f9f9f9;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
        }
        .notebook {
            background: white;
            width: 80%;
            max-width: 600px;
            padding: 20px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            position: relative;
            border-top: 30px solid transparent;
            transform: translateY (10%) 
        }
        .notebook::before {
            content: '';
            position: absolute; 
            top: -10px; 
            left: 50%;
            width: 90%;
            height: 20px;
            background: repeating-linear-gradient(
                to right,
                transparent,
                transparent 15px,
                #f9f9f9 15px,
                #f9f9f9 30px
            );
            background-size: 30px 20px; 
            background-position: absolute;
            transform: translateX(-50%);
        }
        ul {
            list-style: none;
            padding: 0;
        }
        li {
            margin-bottom: 20px;
        }
        a {
            text-decoration: none;
            color: #333;
            border-bottom: 1px solid #000;
            padding-bottom: 3px;
        }
        a:hover {
            color: #0073e6;
        }
        input[type="checkbox"] {
            margin-right: 10px;
        }
    </style>
</head>
<body>
    <div class="notebook">
        <ul>
            <li><input type="checkbox"> <a href="https://www.canva.com/design/DAGbtfAMiRQ/XjQm-7yKMx1WxgSzqx27FQ/edit?utm_content=DAGbtfAMiRQ&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton" target="_blank">Dear nyungy, along… &#128140;</a></li>
            <li><input type="checkbox"> <a href="https://www.canva.com/design/DAGbtip8qVQ/NhrbQYwrCuf0Z7aNjNDXGw/edit?utm_content=DAGbtip8qVQ&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton" target="_blank">  my favorite memories w you</a></li>
            <li><input type="checkbox"> <a href="https://saurabhnemade.github.io/will-you-be-my-valentine/" target="_blank">will you be my Valentine?</a></li>
            <li><input type="checkbox"> <a href="https://imgflip.com/i/9flml3" target="_blank">if yes, thank you sm!</a></li>
        </ul>
    </div>
</body>
</html>
        
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Fliegende Herzen</title>
    <style>
        body {
            margin: 0;
            overflow: hidden;
            background-color: #ffe6f2;
        }
        .heart {
            position: absolute;
            width: 20px;
            height: 20px;
            background-color: #ff69b4;
            transform: rotate(45deg);
            border-radius: 50% 50% 0 0;
            animation: float 5s infinite ease-in-out;
        }
        .heart::before,
        .heart::after {
            content: '';
            position: absolute;
            width: 20px;
            height: 20px;
            background-color: #ff69b4;
            border-radius: 50%;
        }
        .heart::before {
            top: -10px;
            left: 0;
        }
        .heart::after {
            top: 0;
            left: -10px;
        }
        @keyframes float {
            0% {
                transform: translateY(0) rotate(45deg);
                opacity: 1;
            }
            100% {
                transform: translateY(-1000px) rotate(45deg);
                opacity: 0;
            }
        }
    </style>
</head>
<body>
    <script>
        function createHeart() {
            const heart = document.createElement("div");
            heart.classList.add("heart");
            heart.style.left = Math.random() * 100 + "vw";
            heart.style.animationDuration = Math.random() * 2 + 3 + "s";
            document.body.appendChild(heart);

            setTimeout(() => {
                heart.remove();
            }, 5000);
        }
        setInterval(createHeart, 300);
    </script>
</body>
</html>

<style>
  .abschluss-punkt-rand {
    width: 100%;
    height: 20px;
    background: linear-gradient(to right, #f8a5c2, #ff6b6b);
    border-top: 3px solid #ff4d6d;
    box-shadow: 0 -4px 6px rgba(255, 77, 109, 0.2);
    background-image: radial-gradient(circle, #ff6b6b 2px, transparent 2px);
    background-size: 20px 20px;
  }
</style>

<!-- Container mit Inhalt -->
<div class="valentinstag-container valentinstag-rand">
    
  <h1>💖</h1>
  <p>~ Dein Mangu✨</p>
