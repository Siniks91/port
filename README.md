
<html lang="kk">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Асылжанның Портфолиосы</title>
    <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@500&family=Poppins:wght@300;400;600&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Poppins', sans-serif;
            margin: 0;
            padding: 0;
            background: linear-gradient(135deg, #001f3f, #012a4a);
            color: #ffffff;
        }
        .container {
             width: 100%;
            height: 56.25vw; 
            max-width: 1920px; 
            background: rgba(255, 255, 255, 0.1);
            padding: 30px;
            border-radius: 15px;
            box-shadow: 0px 4px 15px rgba(255, 255, 255, 0.2);
            backdrop-filter: blur(10px);
            position: relative;
            animation: fadeIn 1.5s ease-in-out;
            display: flex;
            flex-direction: column;
            justify-content: space-around;
            overflow-y: auto;
        }
        .profile-img {
            width: 220px;
            height: 320px;
            object-fit: cover;
            border-radius: 15px;
            display: block;
            margin: 20px auto;
            box-shadow: 0px 4px 10px rgba(255, 255, 255, 0.3);
        }
        .achievement-img {
            width: 55%;
            max-width: 200px;
            display: block;
            margin: 10px auto;
            border-radius: 10px;
            box-shadow: 0px 4px 10px rgba(255, 255, 255, 0.3);
        }
        h1 {
            text-align: center;
            color: #ffd700;
            font-size: 2.5rem;
        }
        h2 {
            color: #f0e68c;
            border-bottom: 2px solid #ffd700;
            display: inline-block;
            padding-bottom: 5px;
        }
        p {
            text-align: justify;
            line-height: 1.6;
        }
        ul {
            list-style-type: none;
        }
        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(-20px); }
            to { opacity: 1; transform: translateY(0); }
        }
 @media screen and (max-width: 768px) {
            .container {
                height: auto;
                width: 100%;
            }
}
.achievement-item {
            display: flex;
            justify-content: space-between;
            align-items: center;
            margin-bottom: 20px;
        }

        .achievement-item img {
            margin-left: 20px;
        }

        .achievement-item div {
            flex-grow: 1;
        }

    </style>
</head>
<body>
    <div class="container">
        <h1>Портфолио</h1>
        <img src="profile.jpg" alt="Менің суретім" class="profile-img">
        
        <h2>Мен туралы</h2>
        <p>Менің атым Асылжан РФММ мектебінің 10 В сынып оқушысымың. 2009 жылы 9 қаңтарда Алматы қаласында дүниеге келдім.</p>
        <p>Менің негізгі қызығушылықтарымның бірі – <strong>шаңғы спорты</strong>, әсіресе <strong>freeski</strong>.</p>
        <p>Бұл мен үшін тек спорт емес, сонымен қатар еркіндік пен адреналин көзі.</p>
        <p>Сонымен қатар, мен саяхаттауды жақсы көремін. Осы уақытқа дейін <strong>11 елде</strong> болдым.</p>
        <p>2021 жылыРеспубликалық Физика-Математика мектебіне 7-сынып оқушысы ретінде оқуға түстім.</p>
        
        <h2>Спорт және өнер жетістіктер</h2>
        <ul>
            <li>Gorilla Freeski Contest Qualification <strong>2x</strong>.</li>
            <img src="achievement1.jpg" alt="Gorilla Freeski Contest" class="achievement-img">
            <li>Freeski дисциплинасында <strong>180 cork, 180 flip, backflip</strong> (қауіпсіздік жастығына).</li>
            <img src="achievement2.jpg" alt="Freeski Tricks" class="achievement-img">
            <li>(<a href="https://www.strava.com/" class="links" target="_blank">15 км марафонын</a>) <strong>1 сағат 26 минут</strong> ішінде жүгірдім.</li>
            <img src="achievement3.jpg" alt="Marathon Achievement" class="achievement-img">
        </ul>
        
        <h2>Білім жетістіктер</h2>
        <ul>
            <li><a href="https://www.ioaastrophysics.org/" class="links" target="_blank">IOAA 2023, 2024 qualification</a>.</li>
            <img src="achievement4.jpg" alt="IOAA Certificate" class="achievement-img">
            <li><a href="https://tech.seas.harvard.edu/summer" class="links" target="_blank">Harvard Undergraduate Ventures-TECH Summer Program</a> (қабылдандым).</li>
            <img src="achievement5.jpg" alt="Harvard Program" class="achievement-img">
        </ul>
        
        <h2>Мамандығым</h2>
        <p>Мен АҚШ-та <strong>инженер мамандығына</strong> оқуға түсуді жоспарлап отырмын.</p>
        <p>Мен әрқашан жаңа нәрселерді зерттеуді, қиындықтарды шешуді және жаңашыл шешімдер табуды жақсы көремін.</p>
        <p>Менің мақсатым – <strong>саяхаттау индустриясын</strong> жетілдіру үшін инженерлік білімімді қолдану.</p>
        
        <h2>Болашақ</h2>
        <p>Мен тарихта атымды <strong>саяхат индустриясын өзгерту</strong> арқылы қалдырғым келеді.</p>
        <p>Мен жаңа технологиялар мен инженерлік шешімдер арқылы бұл процесті оңтайландыруға және жеңілдетуге ниеттімін.</p>
        <p>Саяхат тек элитаға ғана емес, <strong>әр адамға қолжетімді</strong> болуы керек.</p>
    </div>
</body>
</html>
