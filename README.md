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
            width: 80px;
            margin-right: 15px;
        }
        .title {
            font-size: 24px;
            font-weight: bold;
        }
        .content-container {
            display: flex;
            flex-wrap: wrap;
            align-items: center;
            justify-content: center;
            padding: 20px;
            text-align: center;
        }
        .banner {
            width: 100%;
            max-width: 600px;
            height: auto;
        }
        .text {
            font-family: sans-serif;
            max-width: 800px;
            font-size: 18px;
            margin: 0 auto;
            text-align: justify;
        }
        .nn, .vande, .tq {
            display: flex;
            flex-wrap: wrap;
            align-items: center;
            justify-content: center;
            padding: 20px;
            gap: 10px;
        }
        .nnảnh, .ảnh2, .ảnh3 {
            display: flex;
            justify-content: center;
            align-items: center;
            width: 100%;
            max-width: 400px;
        }
        .nnảnh img, .ảnh2 img, .ảnh3 img {
            max-width: 100%;
            height: auto;
        }
        .list, .vd, .tq1 {
            flex: 1;
            background: white;
            padding: 15px;
            border-radius: 10px;
            box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.1);
            text-align: center;
            font-family: sans-serif;
        }
        .list h2, .vd h2, .tq1 h2 {
            font-size: 20px;
        }
        .list p, .vd p, .tq1 p {
            font-size: 16px;
            text-align: justify;
        }
        hr {
            margin: 20px 0;
            border: 0;
            border-top: 2px solid #6d5c5c;
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
            <p><i>Trong thời đại ngày nay, vấn đề an toàn thực phẩm đang trở thành mối quan tâm hàng đầu của cộng đồng, đặc biệt là đối với học sinh – những thế hệ tương lai của đất nước...</i></p>
            <hr>
        </div>
    </div>
    <hr>
    <h1 class="kq">Nhận Thức</h1>
    <div class="nn">
        <div class="nnảnh">
            <img src="khaosat.png" alt="khaosat">
        </div>
        <div class="list">
            <h2>Nguyên nhân</h2>
            <p>Thực phẩm bẩn tràn lan</p>
            <p>Thiếu nhận thức về thực phẩm sạch</p>
            <p>Học sinh ít cơ hội tiếp xúc với quá trình chăm sóc cây</p>
            <p>Môi trường học đường là nơi phù hợp để thực hiện</p>
            <p>Bảo vệ môi trường</p>   
        </div>
        <div class="nnảnh">
            <img src="khaosat2.png" alt="khaosat">
        </div>
    </div>
    <div class="vande">
        <div class="ảnh2">
            <img src="khaosat3.png" alt="khaosat">
        </div>
        <div class="vd">
            <h2>Vấn đề</h2>
            <p>Kết quả khảo sát cho thấy nhiều học sinh vẫn gặp vấn đề với thực phẩm không an toàn...</p>
        </div>
        <div class="ảnh2">
            <img src="khaosat4.png" alt="khaosat">
        </div>
    </div>
    <div class="ảnh3">
        <img src="khaosat5.png" alt="khaosat">
        <img src="nhanthuc.jpg" alt="anh thua thai">
        <img src="khaosat6.png" alt="khaosat">
    </div>
    <div class="tq">
        <div class="ảnh2">
            <img src="khaosat7.png" alt="khaosat">
        </div>
        <div class="tq1">
            <h2>Thói quen</h2>
            <p>Kết quả khảo sát cho thấy khi phải lựa chọn giữa một món ăn rõ nguồn gốc và một món ăn sạch nhưng không quá ngon...</p>
        </div>
    </div>
    <hr>
</body>
</html>
