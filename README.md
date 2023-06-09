<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tanushree-Developer Portfolio</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:ital@1&display=swap" rel="stylesheet">
    <style>
        * {
            margin: 0;
            padding: 0;

        }

        body {
            background-color: rgb(0, 0, 70);
            color: white;
            font-family: 'Poppins', sans-serif;
        }

        nav {
            display: flex;
            justify-content: space-around;
            align-items: center;
            height: 80px;
            background-color: rgb(53, 53, 115);
        }

        nav ul {
            display: flex;
            justify-content: center;

        }

        nav ul li {
            list-style: none;
            margin: 0 23px;
        }

        nav ul li a {
            text-decoration: none;
            color: white;

        }

        nav ul li a:hover {

            color: rgb(143, 143, 212);

        }

        main hr {
            border: 0;
            background: rgb(85, 85, 217);
            height: 1.2px;
            margin: 60px 84px;
        }

        .left {
            font-size: 2rem;
        }

        .firstSection {
            display: flex;
            justify-content: space-around;
            align-items: center;
            margin: 130px 0;
        }

        .firstSection>div {
            width: 30%;
        }

        .leftSection {

            font-size: 2rem;

        }
        .leftSection .button{
            padding: 23px;
        }

        .leftSection .btn{

            padding: 0 10px;
            background-color:rgb(161, 111, 208) ;
            color: white;
            border: 2px solid white;
            border-radius: 6px;
            font-size: 20px;
            cursor: pointer;


        }

        .rightSection img {
            width: 80%;
        }

        .purple {
            color: rgb(161, 111, 208);
        }

        #element {
            color: rgb(161, 111, 208);
        }
    </style>
</head>

<body>
    <header>
        <nav>
            <div class="left">Tanushree's Portfolio</div>
            <div class="right"></div>
            <ul>
                <li><a href="/">Home</a></li>
                <li><a href="/">About</a></li>
                <li><a href="/">Services</a></li>
                <li><a href="/">Projects</a></li>
                <li><a href="/">Contact me</a></li>
            </ul>
        </nav>

    </header>

    <main>
        <section class="firstSection">
            <div class="leftSection">
                Hi , My Name is <span class="purple">Tanushree</span>
                <div>and I am a Passionate</div>
                <span id="element"></span>
                <div class="button">
                    <button class="btn">Download Resume</button>
                    <button class="btn">Visit Github</button>
                </div>
            </div>
            <div class="rightSection">
                <img src="d.png" alt="">
            </div>
        </section>

    </main>

    <script src="https://unpkg.com/typed.js@2.0.16/dist/typed.umd.js"></script>
    <script>
        var typed = new Typed('#element', {
            strings: ['Web developer', 'Graphic Designer'], typeSpeed: 60,
        });
    </script>
</body>

</html>
