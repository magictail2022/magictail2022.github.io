<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Magic Tail - 高端宠物用品品牌</title>
    <style>
        /* 添加一些基础样式让网站更好看 */
        .product-gallery {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
            padding: 20px;
        }
        .product-card {
            border: 1px solid #ddd;
            border-radius: 8px;
            overflow: hidden;
            transition: transform 0.3s;
        }
        .product-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 5px 15px rgba(0,0,0,0.1);
        }
        .product-image {
            width: 100%;
            height: 200px;
            object-fit: cover;
        }
    </style>
</head>
<body>
    <header>
        <h1>🐾 Magic Tail</h1>
        <p>为您爱宠的每一个快乐瞬间</p>
    </header>
    
    <main>
        <section class="hero">
            <!-- 这里可以放你的全家福图片 -->
            <img src="assets/images/微信图片_20260202085722_456_7.jpg" 
                 alt="Magic Tail 产品全家福" 
                 loading="lazy"
                 style="max-width: 100%; height: auto;">
        </section>
        
        <section class="features">
            <h2>✨ 品牌特色</h2>
            <div class="feature-grid">
                <div class="feature">优质材料</div>
                <div class="feature">创新设计</div>
                <div class="feature">宠物友好</div>
                <div class="feature">环保理念</div>
            </div>
        </section>
    </main>
</body>
</html>
