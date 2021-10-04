<!DOCTYPE > 
<html> 
    <head>
 <title>index</title>
 <meta charset="UTF-8">
 <link rel="stylesheet" type="text/css" href="style.css">
 <link rel="stylesheet" href="./fontawesome-free-6.0.0-beta2-web/css/all.min.css">
    </head> 
    <body> 
       <div class="header">
           <div>
           <p>PHỤ KIỆN MÁY TÍNH</p>
           <div style="display: inline-flex;">
           <P>Hotline: 19006046 </P>
           <p style="padding-left: 20px;"> Email: support@gmail.com</p>
        </div>
        </div>
       <div id="search">
           <input type="search" name="s" placeholder="Nhập từ khóa tìm kiếm" style="padding: 12px; border-radius: 10px;">
       </div>
       <div class="icon1">
        <a><i class="fas fa-shopping-cart">Giỏ Hàng</i></a>
       </div>
        </div>
        <div id="header2">
            <div class="title">
            <div class="danhmuc">
                <i class="fas fa-list"></i> Danh mục sản phẩm
            <ul class="child">
                <li><a href="">Chuột gaming</a></li>
                <li><a href="">Tai nghe</a></li>
                <li><a href="">Bàn phím</a></li>
                <li><a href="">Phụ kiện</a></li>
                <li><a href="">Âm thanh</a></li>
            </ul>
        </div>
        <div class="list">
            <ul>
                <li><a href="">Trang chủ</a></li>
                <li><a href="">Giới thiệu</a></li>
                <li><a href="">Sản phẩm</a></li>
                <li><a href="">Khuyến mãi</a></li>
                <li><a href="">Chính sách bảo hành</a></li>
                <li><a href="">Hướng dẫn thanh toán</a></li>
                <li><a href="">Tin tức</a></li>
                <li><a href="">Liên hệ</a></li>
            </ul>
        </div>
        </div>
        </div>
        <div class="slide">
        <img id="img" onclick="changeImg()" src="image1.png"  alt="">    
        </div>
        <script>
            var index = 1;
         function changeImg()  {
                var imgs = ["image1.png","image2.png"];
                document.getElementById("img").src = imgs[index];
                index++
                if(index==1){
                    index= 0;
                }
                setInterval(changeimg,8000);
            }
        </script>
    </body>  
</html>
