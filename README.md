[index.html](https://github.com/user-attachments/files/26924213/index.html)
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Wedding Invitation | Yenni & Bill</title>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Playfair+Display:ital,wght@0,400;0,700;1,400&family=Lato:wght@300;400&display=swap');

        body {
            font-family: 'Lato', sans-serif;
            background-color: #fff5f7;
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            flex-direction: column;
            color: #4a4a4a;
        }
        .container {
            max-width: 500px;
            width: 100%; /* 寬度自適應手機 */
            background: #ffffff;
            box-shadow: 0 10px 30px rgba(0,0,0,0.05);
            text-align: center;
            overflow-x: hidden;
            border-radius: 0;
        }
        img.invite-img {
            width: 100%;
            display: block;
            height: auto;
        }
        .section {
            padding: 30px 20px;
        }
        h2 {
            font-family: 'Playfair Display', serif;
            color: #d18ba3;
            font-size: 1.6em;
            margin-bottom: 15px;
        }
        .btn {
            display: inline-block;
            background-color: #ffffff;
            color: #d18ba3;
            padding: 12px 20px;
            text-decoration: none;
            border-radius: 4px;
            margin: 10px 5px;
            font-size: 0.8em;
            letter-spacing: 1px;
            border: 1px solid #d18ba3;
            text-transform: uppercase;
        }

        /* 🎬 膠卷動畫優化 🎬 */
        .filmstrip-container {
            width: 100%;
            background: #212121;
            overflow: hidden;
            position: relative;
            padding: 20px 0;
        }
        .filmstrip-row {
            display: flex;
            width: fit-content;
            animation: scrollFilmstrip 30s linear infinite;
        }
        @keyframes scrollFilmstrip {
            0% { transform: translateX(0); }
            100% { transform: translateX(-50%); }
        }
        .filmstrip-slide {
            flex: 0 0 auto;
            width: 250px;
            height: 350px;
            margin: 0 8px;
            border-radius: 4px;
            overflow: hidden;
            background: #000;
        }
        .filmstrip-slide img {
            width: 100%;
            height: 100%;
            object-fit: cover;
        }

        .rsvp-section {
            background-color: #fff9fa;
            padding: 40px 20px;
            border-top: 1px solid #fce4ec;
        }
        .rsvp-btn {
            background-color: #d18ba3;
            color: white;
            padding: 15px 40px;
            border-radius: 30px;
            font-weight: bold;
            text-decoration: none;
            display: inline-block;
            box-shadow: 0 4px 10px rgba(209,139,163,0.3);
        }
    </style>
</head>
<body>

    <div class="container">
        <img src="Bill Wilson.jpg" alt="Invitation" class="invite-img">

        <div class="section">
            <h2 style="font-style: italic;">Save the Date</h2>
            <p>For the Wedding of Yenni Wu & Bill Wilson</p>
        </div>

        <img src="Bill Wilson (1).jpg" alt="Details" class="invite-img">

        <div class="section">
            <h2>Location</h2>
            <p><strong>Ceremony</strong><br>New Life Tondo</p>
            <a href="https://www.google.com/maps/search/?api=1&query=New+Life+Tondo" target="_blank" class="btn">View Map</a>
            <div style="height: 20px;"></div>
            <p><strong>Reception</strong><br>The Heritage Hotel Manila</p>
            <a href="https://www.google.com/maps/search/?api=1&query=The+Heritage+Hotel+Manila" target="_blank" class="btn">View Map</a>
        </div>

        <div class="filmstrip-container">
            <div class="filmstrip-row">
                <div class="filmstrip-slide"><img src="S__28753935_0.jpg"></div>
                <div class="filmstrip-slide"><img src="S__28753936_0.jpg"></div>
                <div class="filmstrip-slide"><img src="S__28753939_0.jpg"></div>
                <div class="filmstrip-slide"><img src="S__28753942_0.jpg"></div>
                <div class="filmstrip-slide"><img src="S__28753943_0.jpg"></div>
                <div class="filmstrip-slide"><img src="S__28753927_0.jpg"></div>
                <div class="filmstrip-slide"><img src="S__28753928_0.jpg"></div>
                <div class="filmstrip-slide"><img src="S__28753933_0.jpg"></div>
                <div class="filmstrip-slide"><img src="S__28753925_0.jpg"></div>
                <div class="filmstrip-slide"><img src="S__28753924_0.jpg"></div>
                <div class="filmstrip-slide"><img src="S__28753935_0.jpg"></div>
                <div class="filmstrip-slide"><img src="S__28753936_0.jpg"></div>
                <div class="filmstrip-slide"><img src="S__28753939_0.jpg"></div>
                <div class="filmstrip-slide"><img src="S__28753942_0.jpg"></div>
                <div class="filmstrip-slide"><img src="S__28753943_0.jpg"></div>
                <div class="filmstrip-slide"><img src="S__28753927_0.jpg"></div>
                <div class="filmstrip-slide"><img src="S__28753928_0.jpg"></div>
                <div class="filmstrip-slide"><img src="S__28753933_0.jpg"></div>
                <div class="filmstrip-slide"><img src="S__28753925_0.jpg"></div>
                <div class="filmstrip-slide"><img src="S__28753924_0.jpg"></div>
            </div>
        </div>

        <div class="rsvp-section">
            <h2>RSVP</h2>
            <p>We can't wait to see you there!</p>
            <br>
            <a href="YOUR_GOOGLE_FORM_URL" target="_blank" class="rsvp-btn">Submit Your RSVP</a>
        </div>
    </div>

</body>
</html>
<img width="1240" height="1748" alt="Bill Wilson" src="https://github.com/user-attachments/assets/fbf91602-061c-4041-9fe7-b0167dbb32e0" />
<img width="1240" height="1748" alt="Bill Wilson (1)" src="https://github.com/user-attachments/assets/9f4aeb58-7131-4e89-aaa0-c3adebfb8781" />
<img width="1036" height="1582" alt="S__28753935_0" src="https://github.com/user-attachments/assets/0a797608-d3e0-4dbf-8781-cb48e4c3afa0" />
<img width="1108" height="1477" alt="S__28753936_0" src="https://github.com/user-attachments/assets/5c8bd939-af4e-456b-b982-663a2f226926" />
<img width="720" height="854" alt="S__28753939_0" src="https://github.com/user-attachments/assets/7e8fb239-1644-49fc-ab54-443893990169" />
<img width="1108" height="1477" alt="S__28753942_0" src="https://github.com/user-attachments/assets/dc359aae-dc32-47f9-994c-91fb7e3cddb2" />
<img width="1424" height="1150" alt="S__28753943_0" src="https://github.com/user-attachments/assets/539e0b24-7cfc-4127-9e40-21b5e9661008" />
<img width="1567" height="1045" alt="S__28753927_0" src="https://github.com/user-attachments/assets/9ba96f85-897f-4b9b-9453-5b7e6440a8b8" />
<img width="1352" height="1210" alt="S__28753928_0" src="https://github.com/user-attachments/assets/6980bc54-1ceb-4943-84f3-6c6405220fcc" />
<img width="1108" height="1477" alt="S__28753933_0" src="https://github.com/user-attachments/assets/c5e3d396-81bb-421e-8d19-7fccf2454ab6" />
<img width="769" height="1024" alt="S__28753924_0" src="https://github.com/user-attachments/assets/1425b305-e156-48c1-80e5-4a3140979728" />
<img width="508" height="677" alt="S__28753925_0" src="https://github.com/user-attachments/assets/02face34-540a-4f5e-9052-7e9fdfcbdaee" />
