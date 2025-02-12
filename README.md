<!DOCTYPE html>
<html lang="vi">
<head>
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>An Toàn Thực Phẩm</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f8f1e4;
            width: 100%;
            max-width: none;
            overflow-x: hidden;
        }
        .header {
            display: flex;
            align-items: center;
            padding: 10px 20px;
            background-color: #6d5c5c;
            color: white;
        }
        .logo {
            width: 60px;
            margin-right: 15px;
        }
        .title {
            font-size: 22px;
            font-weight: bold;
        }
        .content-container {
            display: flex;
            flex-wrap: wrap;
            align-items: center;
            justify-content: center;
            padding: 20px;
            gap: 20px;
        }
        .banner {
            width: 100%;
            max-width: 600px;
            height: auto;
        }
        .text {
            font-size: 16px;
            max-width: 800px;
            text-align: justify;
        }
        .nn, .vande, .tq {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            align-items: center;
            padding: 20px;
            gap: 10px;
        }
        .nnảnh img, .ảnh2 img, .ảnh3 img {
            max-width: 100%;
            height: auto;
            display: block;
        }
        .list, .vd, .tq1 {
            flex: 1;
            background: white;
            padding: 15px;
            border-radius: 10px;
            box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.1);
            text-align: center;
        }
        .list h2, .vd h2, .tq1 h2 {
            font-size: 20px;
        }
        .list p, .vd p, .tq1 p {
            font-size: 14px;
            text-align: justify;
        }
        @media (max-width: 768px) {
            .title {
                font-size: 18px;
            }
            .logo {
                width: 50px;
            }
            .text {
                font-size: 14px;
                padding: 10px;
            }
            .list h2, .vd h2, .tq1 h2 {
                font-size: 18px;
            }
            .list p, .vd p, .tq1 p {
                font-size: 12px;
            }
        }
    </style>
</head>
<body>
    <div class="header">
        <img src="logo.jpg" alt="Logo" class="logo">
        <div class="title">An Toàn Thực Phẩm</div>
    </div>
    <div class="content-container">
        <img src="banner.jpg" alt="banner" class="banner">
        <div class="text">
            <h2>Lời nói đầu</h2>
            <p><i>Trong thời đại ngày nay, vấn đề an toàn thực phẩm...</i></p>
        </div>
    </div>
    <h1 class="kq">Nhận Thức</h1>
    <div class="nn">
        <div class="nnảnh"><img src="khaosat.png" alt="khaosat"></div>
        <div class="list">
            <h2>Nguyên nhân</h2>
            <p>Thực phẩm bẩn tràn lan...</p>
        </div>
        <div class="nnảnh"><img src="khaosat2.png" alt="khaosat"></div>
    </div>
    <div class="vande">
        <div class="ảnh2"><img src="khaosat3.png" alt="khaosat"></div>
        <div class="vd">
            <h2>Vấn đề</h2>
            <p>Kết quả khảo sát cho thấy nhiều học sinh...</p>
        </div>
        <div class="ảnh2"><img src="khaosat4.png" alt="khaosat"></div>
    </div>
    <div class="ảnh3">
        <img src="khaosat5.png" alt="khaosat">
        <img src="nhanthuc.jpg" alt="anh thua thai">
        <img src="khaosat6.png" alt="khaosat">
    </div>
    <div class="tq">
        <div class="ảnh2"><img src="khaosat7.png" alt="khaosat"></div>
        <div class="tq1">
            <h2>Thói quen</h2>
            <p>Kết quả khảo sát cho thấy khi phải lựa chọn...</p>
        </div>
    </div>
</body>
</html>
