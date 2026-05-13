<html lang="th">
<head>
    <meta charset="UTF-8">
    <title>ครัววรรณคดี ม.1</title>
    <style>
        body { font-family: 'Sarabun', sans-serif; background-color: #f4e1d2; text-align: center; }
        .card { background: white; width: 80%; margin: 20px auto; padding: 20px; border-radius: 15px; box-shadow: 0 4px 8px rgba(0,0,0,0.1); }
        h1 { color: #8b4513; }
        .verse { font-style: italic; color: #555; background: #fff5e6; padding: 10px; border-left: 5px solid #d2691e; }
        .ingredients { display: flex; justify-content: center; gap: 10px; margin-top: 20px; }
        .item { background: #d2691e; color: white; padding: 5px 15px; border-radius: 20px; cursor: pointer; }
        .item:hover { background: #a0522d; }
    </style>
</head>
<body>
    <div class="card">
        <h1>เมนู: มัสมั่นไก่</h1>
        <p class="verse">"มัสมั่นแกงแก้วตา หอมยี่หร่ารสร้อนแรง <br> ชายใดได้กลืนแกง แรงอยากให้ใฝ่ฝันหา"</p>
        
        <h3>วัตถุดิบที่ปรากฏในบทประพันธ์:</h3>
        <div class="ingredients">
            <div class="item" onclick="alert('ยี่หร่า: ช่วยให้มีกลิ่นหอมและรสเผ็ดร้อน')">ยี่หร่า</div>
            <div class="item" onclick="alert('พริกแกงมัสมั่น: หัวใจของความอร่อย')">พริกแกง</div>
            <div class="item" onclick="alert('ไก่/เนื้อ: เนื้อสัตว์หลักในแกง')">เนื้อสัตว์</div>
        </div>
    </div>
</body>
</html>
