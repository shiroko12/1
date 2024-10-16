<!DOCTYPE html>
<html lang="zh-TW">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>我的簡單網頁</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            margin: 0;
            padding: 20px;
            text-align: center;
        }
        h1 {
            color: #333;
        }
        p {
            font-size: 18px;
            color: #555;
        }
        .image-container {
            display: flex;
            justify-content: space-around;
            align-items: center;
            flex-wrap: wrap;
            margin: 20px 0;
        }
        .image-container img {
            max-width: 30%;
            height: auto;
            margin: 10px;
            border: 2px solid #ccc;
            box-shadow: 2px 2px 12px rgba(0, 0, 0, 0.1);
        }
        button {
            padding: 10px 20px;
            background-color: #007BFF;
            color: white;
            border: none;
            cursor: pointer;
            font-size: 16px;
        }
        button:hover {
            background-color: #0056b3;
        }
    </style>
</head>
<body>

    <h1>歡迎來到我的網頁</h1>
    <p>這是一個展示基本功能的簡單網頁，使用了Flexbox進行排版。</p>

    <h2>圖片展示</h2>
    <div class="image-container">
        <img src="(https://betabg.mofang.com.tw/admin/20201209/uploads/2021-10-07/images/244185753_138714738483993_17283884135.jpg)" alt="圖片1">
        <img src="https://i.imgur.com/oZEnldQ.jpeg" alt="圖片2">
        <img src="[https://via.placeholder.com/300x200](https://i.imgur.com/oZEnldQ.jpeg)" alt="圖片3">
    </div>

    <p>這是三張示例圖片，它們被均勻地分散並置中顯示。</p>

    <button onclick="alert('按鈕已被點擊！')">點擊我</button>

</body>
</html>
