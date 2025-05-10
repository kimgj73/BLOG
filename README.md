# BLOG
<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>뉴현대모터스
        010-5310-9095
        - 홈</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: Arial, sans-serif;
        }
        body {
            background-color: #f4f4f4;
        }
        nav {
            background-color: #333;
            padding: 15px 0;
            position: fixed;
            width: 100%;
            top: 0;
            z-index: 1000;
        }
        nav ul {
            list-style: none;
            text-align: center;
        }
        nav ul li {
            display: inline;
            margin: 0 20px;
        }
        nav ul li a {
            color: white;
            text-decoration: none;
            font-size: 18px;
        }
        nav ul li a:hover {
            color: #ffd700;
        }
        .hero {
            height: 100vh;
            background: url('https://via.placeholder.com/1920x1080?text=회사전경') no-repeat center/cover;
            display: flex;
            justify-content: center;
            align-items: center;
            text-align: center;
            color: white;
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.7);
        }
        .hero h1 {
            font-size: 48px;
            margin-bottom: 20px;
        }
        .hero p {
            font-size: 24px;
            max-width: 600px;
        }
        .container {
            max-width: 1200px;
            margin: 80px auto 20px;
            padding: 20px;
        }
        .thumbnail-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
        }
        .thumbnail {
            background-color: white;
            border-radius: 10px;
            overflow: hidden;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
            text-align: center;
        }
        .thumbnail img {
            width: 100%;
            height: 150px;
            object-fit: cover;
        }
        .thumbnail h3 {
            margin: 10px 0;
        }
        .case, .contact-form {
            background-color: white;
            padding: 20px;
            margin-bottom: 20px;
            border-radius: 10px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
        }
        .contact-form input, .contact-form textarea {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
        .contact-form button {
            padding: 10px 20px;
            background-color: #333;
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        .contact-form button:hover {
            background-color: #ffd700;
            color: black;
        }
        footer {
            text-align: center;
            padding: 20px;
            background-color: #333;
            color: white;
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <nav>
        <ul>
            <li><a href="index.html">홈</a></li>
            <li><a href="about.html">회사 소개</a></li>
            <li><a href="cars.html">판매 차량</a></li>
            <li><a href="cases.html">매매 사례</a></li>
            <li><a href="contact.html">문의 및 연락처</a></li>
        </ul>
    </nav>
    <div class="hero">
        <div>
            <h1>뉴현대모터스</h1>
            <p>고객의 신뢰를 바탕으로 최고의 중고차 매매 서비스를 제공합니다.</p>
        </div>
    </div>
    <footer>
        <p>&copy; 2025 뉴현대모터스. All Rights Reserved.</p>
    </footer>
</body>
</html>

