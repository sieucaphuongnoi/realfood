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
            align-items: flex-start;
            justify-content: flex-start; 
            padding: 20px;
            text-align: left; 
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
            align-items: flex-start; /* Changed from center to flex-start */
            justify-content: space-between; /* Changed from center to space-between */
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
            <p><i>Trong thời đại ngày nay, vấn đề an toàn thực phẩm đang trở thành mối quan tâm hàng đầu của cộng đồng, đặc biệt là đối với học sinh – những thế hệ tương lai của đất nước. Nhận thấy thực trạng thực phẩm bẩn, hàng giả tràn lan trên thị trường và tác động tiêu cực của chúng đến sức khỏe, nhóm chúng tôi quyết định thực hiện dự án "Thay đổi nhận thức về thực phẩm sạch cho học sinh tại Vinschool Thăng Long".<br>Mục tiêu của dự án không chỉ đơn thuần là cung cấp thực phẩm sạch mà quan trọng hơn, chúng tôi mong muốn nâng cao nhận thức của học sinh về tầm quan trọng của thực phẩm an toàn. Bằng cách tự trồng các loại rau sạch và chia sẻ miễn phí, chúng tôi khuyến khích mọi người trải nghiệm thực phẩm lành mạnh, từ đó dần thay đổi thói quen tiêu dùng và góp phần xây dựng một cộng đồng quan tâm hơn đến sức khỏe.Dự án này không chỉ là một mô hình thử nghiệm mà còn là một bước khởi đầu để lan tỏa ý thức về thực phẩm sạch trong nhà trường và rộng hơn là trong cộng đồng. Chúng tôi hy vọng rằng, với sự đồng hành của thầy cô, bạn bè và sự quan tâm của toàn xã hội, dự án sẽ đạt được những thành công nhất định và mang lại giá trị thiết thực.</i></p>
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
            <p>Kết quả khảo sát cho thấy nhiều học sinh vẫn gặp vấn đề với thực phẩm không an toàn. Dù 72.2% tin rằng thực phẩm hàng ngày đảm bảo sạch, vẫn có 27.8% nghi ngờ. Đáng lo ngại, hơn 66% từng bị ảnh hưởng sức khỏe do ăn đồ bên ngoài, trong đó 18.5% bị thường xuyên. Ngoài ra, thói quen ăn vặt khá phổ biến, với 31.5% ăn hàng ngày và 40.7% ăn hàng tuần, làm tăng nguy cơ tiếp xúc với thực phẩm kém chất lượng.Những vấn đề này cho thấy cần nâng cao nhận thức về an toàn thực phẩm để bảo vệ sức khỏe học sinh.</p>
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
            <p>Kết quả khảo sát cho thấy khi phải lựa chọn giữa một món ăn rõ nguồn gốc và một món ăn sạch nhưng không quá ngon, 57.4% học sinh ưu tiên thực phẩm có nguồn gốc rõ ràng, trong khi 42.6% sẵn sàng chọn thực phẩm an toàn dù không ngon miệng. Điều này phản ánh rằng mùi vị vẫn là yếu tố quan trọng trong thói quen ăn uống, nhưng nhận thức về nguồn gốc thực phẩm cũng dần được học sinh quan tâm. Tuy nhiên, vẫn có một tỷ lệ lớn học sinh chưa đặt yếu tố an toàn thực phẩm lên hàng đầu, cho thấy cần có thêm các hoạt động nâng cao ý thức về thực phẩm sạch trong cộng đồng học đường.</p>
        </div>
    </div>
    <hr>
</body>
</html>
