[index.html](https://github.com/user-attachments/files/26924552/index.html)[Uploa<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Wedding Invitation | Yenni & Bill</title>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Playfair+Display:ital,wght@0,400;0,700;1,400&family=Lato:wght@300;400&display=swap');

        /* 基礎設定 */
        body {
            font-family: 'Lato', sans-serif;
            background-color: #fff5f7;
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
            color: #4a4a4a;
        }

        /* 網頁主容器 */
        .main-wrapper {
            max-width: 500px;
            width: 100%;
            background: #ffffff;
            box-shadow: 0 10px 30px rgba(0,0,0,0.05);
            text-align: center;
            overflow-x: hidden; /* 防止膠卷超出邊界 */
        }

        img.invite-img {
            width: 100%;
            height: auto;
            display: block;
        }

        .section {
            padding: 40px 20px;
        }

        h2 {
            font-family: 'Playfair Display', serif;
            color: #d18ba3;
            font-size: 1.8em;
            margin-bottom: 15px;
        }

        /* 按鈕樣式 */
        .btn {
            display: inline-block;
            background-color: #ffffff;
            color: #d18ba3;
            padding: 12px 25px;
            text-decoration: none;
            border-radius: 4px;
            margin: 10px 5px;
            font-size: 0.85em;
            letter-spacing: 1px;
            border: 1px solid #d18ba3;
            text-transform: uppercase;
            transition: 0.3s;
        }
        .btn:hover {
            background-color: #d18ba3;
            color: #ffffff;
        }

        /* 🎬 膠卷動畫核心設定 🎬 */
        .film-container {
            width: 100%;
            background: #1a1a1a; /* 膠卷底色 */
            padding: 20px 0;
            position: relative;
            margin: 20px 0;
        }

        .film-track {
            display: flex;
            width: max-content; /* 關鍵：讓容器根據內容無限延伸 */
            animation: slideLeft 40s linear infinite; /* 滾動動畫 */
        }

        @keyframes slideLeft {
            0% { transform: translateX(0); }
            100% { transform: translateX(-50%); } /* 滾動到總長度一半實現無縫循環 */
        }

        .film-frame {
            flex: 0 0 auto;
            width: 260px; /* 每張照片寬度 */
            height: 360px; /* 每張照片高度 */
            margin: 0 10px;
            border-radius: 5px;
            overflow: hidden;
            background: #000;
        }

        .film-frame img {
            width: 100%;
            height: 100%;
            object-fit: cover;
        }

        /* RSVP 區塊 */
        .rsvp-section {
            background-color: #fff9fa;
            padding: 60px 20px;
            border-top: 1px solid #fce4ec;
        }

        .rsvp-btn {
            background-color: #d18ba3;
            color: #ffffff;
            padding: 16px 45px;
            border-radius: 40px;
            font-weight: bold;
            font-size: 1.1em;
            text-decoration: none;
            display: inline-block;
            box-shadow: 0 5px 15px rgba(209,139,163,0.3);
            margin-top: 20px;
        }

        .footer {
            padding: 40px 20px;
            font-family: 'Playfair Display', serif;
            font-style: italic;
            color: #d18ba3;
        }
    </style>
</head>
<body>

    <div class="main-wrapper">
        <img src="Bill Wilson.jpg" alt="Invitation Cover" class="invite-img">

        <div class="section">
            <h2 style="font-style: italic;">Wedding Invitation</h2>
            <p>We joyfully invite you to celebrate the marriage of</p>
            <p style="font-family: 'Playfair Display', serif; font-size: 1.6em; color: #d18ba3;">Yenni Wu & Bill Wilson</p>
        </div>

        <img src="Bill Wilson (1).jpg" alt="Wedding Details" class="invite-img">

        <div class="section">
            <h2>Location & Directions</h2>
            <p><strong>Ceremony (2:00 PM)</strong><br>New Life Tondo</p>
            <a href="https://www.google.com/maps/search/?api=1&query=New+Life+Tondo" target="_blank" class="btn">Open Maps</a>
            
            <div style="height: 30px;"></div>
            
            <p><strong>Reception (6:00 PM)</strong><br>The Heritage Hotel Manila</p>
            <a href="https://www.google.com/maps/search/?api=1&query=The+Heritage+Hotel+Manila" target="_blank" class="btn">Open Maps</a>
        </div>

        <div class="film-container">
            <div class="film-track">
                <div class="film-frame"><img src="S__28753935_0.jpg"></div>
                <div class="film-frame"><img src="S__28753936_0.jpg"></div>
                <div class="film-frame"><img src="S__28753939_0.jpg"></div>
                <div class="film-frame"><img src="S__28753942_0.jpg"></div>
                <div class="film-frame"><img src="S__28753943_0.jpg"></div>
                <div class="film-frame"><img src="S__28753927_0.jpg"></div>
                <div class="film-frame"><img src="S__28753928_0.jpg"></div>
                <div class="film-frame"><img src="S__28753933_0.jpg"></div>
                <div class="film-frame"><img src="S__28753925_0.jpg"></div>
                <div class="film-frame"><img src="S__28753924_0.jpg"></div>
                
                <div class="film-frame"><img src="S__28753935_0.jpg"></div>
                <div class="film-frame"><img src="S__28753936_0.jpg"></div>
                <div class="film-frame"><img src="S__28753939_0.jpg"></div>
                <div class="film-frame"><img src="S__28753942_0.jpg"></div>
                <div class="film-frame"><img src="S__28753943_0.jpg"></div>
                <div class="film-frame"><img src="S__28753927_0.jpg"></div>
                <div class="film-frame"><img src="S__28753928_0.jpg"></div>
                <div class="film-frame"><img src="S__28753933_0.jpg"></div>
                <div class="film-frame"><img src="S__28753925_0.jpg"></div>
                <div class="film-frame"><img src="S__28753924_0.jpg"></div>
            </div>
        </div>

        <div class="rsvp-section">
            <h2>RSVP</h2>
            <p>Please kindly respond by clicking the button below.<br>We look forward to seeing you!</p>
            <a href="https://forms.gle/您的表單連結" target="_blank" class="rsvp-btn">Confirm Attendance</a>
        </div>

        <div class="footer">
            <p>With Love, Yenni & Bill</p>
        </div>
    </div>

</body>
</html>ding index.html…]()
<img width="1240" height="1748" alt="Bill Wilson" src="https://github.com/user-attachments/assets/ad89fb96-f0b7-454e-aab1-bf9c20856bc8" />
<img width="1240" height="1748" alt="Bill Wilson (1)" src="https://github.com/user-attachments/assets/5c5c9260-a5fd-4445-83b2-e51998417a2b" />
<img width="1036" height="1582" alt="S__28753935_0" src="https://github.com/user-attachments/assets/52ba3240-6f65-438c-a730-7f4fabfd139a" />
<img width="1108" height="1477" alt="S__28753936_0" src="https://github.com/user-attachments/assets/1c49451c-3591-4947-a547-36ac6101469e" />
<img width="720" height="854" alt="S__28753939_0" src="https://github.com/user-attachments/assets/ab65d090-6fda-4769-91b3-05f86986c40d" />
<img width="1108" height="1477" alt="S__28753942_0" src="https://github.com/user-attachments/assets/c3fd9583-6913-48ac-9b0d-0a5890ba596f" />
<img width="1424" height="1150" alt="S__28753943_0" src="https://github.com/user-attachments/assets/2289e254-dbda-47a0-910e-c8fb9a7f5cd8" />
<img width="1567" height="1045" alt="S__28753927_0" src="https://github.com/user-attachments/assets/9e773222-82f5-4a04-8c83-9ac1ef61c97b" />
<img width="1352" height="1210" alt="S__28753928_0" src="https://github.com/user-attachments/assets/f514983f-b981-43a6-996f-7fad10c370d7" />
<img width="1108" height="1477" alt="S__28753933_0" src="https://github.com/user-attachments/assets/7988085c-dde8-4dcd-8d4a-0806aec53976" />
<img width="769" height="1024" alt="S__28753924_0" src="https://github.com/user-attachments/assets/c9794b0b-c521-4077-af08-ae713bccd97b" />
<img width="508" height="677" alt="S__28753925_0" src="https://github.com/user-attachments/assets/fd041c1c-a0ca-49b2-bb8d-068baecea802" />
