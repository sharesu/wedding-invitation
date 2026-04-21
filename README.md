[index.html](https://github.com/user-attachments/files/26925019/index.html)[<!DOCTYPE html>
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
        <img width="900" height="1269" alt="BillWilson" src="https://github.com/user-attachments/assets/0ff941f3-ceab-4f15-a70e-c7185beac233" />
 alt="Invitation Cover" class="invite-img">

        <div class="section">
            <h2 style="font-style: italic;">Wedding Invitation</h2>
            <p>We joyfully invite you to celebrate the marriage of</p>
            <p style="font-family: 'Playfair Display', serif; font-size: 1.6em; color: #d18ba3;">Yenni Wu & Bill Wilson</p>
        </div>

        <img src="BillWilson1.jpg" alt="Wedding Details" class="invite-img">

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
                <div class="film-frame"><img src="yenni1.jpg"></div>
                <div class="film-frame"><img src="yenni2.jpg"></div>
                <div class="film-frame"><img src="yenni3.jpg"></div>
                <div class="film-frame"><img src="yenni4.jpg"></div>
                <div class="film-frame"><img src="yenni5.jpg"></div>
                <div class="film-frame"><img src="yenni6.jpg"></div>
                <div class="film-frame"><img src="yenni7.jpg"></div>
                <div class="film-frame"><img src="yenni8.jpg"></div>
                <div class="film-frame"><img src="yenni9.jpg"></div>
                <div class="film-frame"><img src="yenni10.jpg"></div>
                
                <div class="film-frame"><img src="yenni1.jpg"></div>
                <div class="film-frame"><img src="yenni2.jpg"></div>
                <div class="film-frame"><img src="yenni3.jpg"></div>
                <div class="film-frame"><img src="yenni4.jpg"></div>
                <div class="film-frame"><img src="yenni5.jpg"></div>
                <div class="film-frame"><img src="yenni6.jpg"></div>
                <div class="film-frame"><img src="yenni7.jpg"></div>
                <div class="film-frame"><img src="yenni8.jpg"></div>
                <div class="film-frame"><img src="yenni9.jpg"></div>
                <div class="film-frame"><img src="yenni10.jpg"></div>
            </div>
        </div>

        <div class="rsvp-section">
            <h2>RSVP</h2>
            <p>Please kindly respond by clicking the button below.<br>We look forward to seeing you!</p>
            <a href="https://forms.gle/vtsvyGpvdMXDehzh9" target="_blank" class="rsvp-btn">Confirm Attendance</a>
        </div>

        <div class="footer">
            <p>With Love, Yenni & Bill</p>
        </div>
    </div>

</body>
</html>Uploading index.html…]()
