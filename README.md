<!DOCTYPE html>
<html lang="th">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>เว็บไซต์แรกของฉัน</title>
    <style>
        /* จัดรูปแบบพื้นฐาน */
        body {
            font-family: 'Sarabun', sans-serif, Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f7f6;
            color: #333;
        }
        /* แถบเมนูด้านบน */
        header {
            background-color: #2c3e50;
            color: white;
            padding: 1rem 2rem;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        nav a {
            color: white;
            text-decoration: none;
            margin-left: 20px;
        }
        nav a:hover {
            color: #1abc9c;
        }
        /* ส่วนเนื้อหาหลัก */
        .hero {
            text-align: center;
            padding: 5rem 1rem;
            background-color: white;
            margin: 2rem auto;
            max-width: 800px;
            border-radius: 8px;
            box-shadow: 0 4px 6px rgba(0,0,0,0.1);
        }
        .hero h1 {
            font-size: 2.5rem;
            color: #2c3e50;
            margin-bottom: 1rem;
        }
        .hero p {
            font-size: 1.1rem;
            color: #666;
            margin-bottom: 2rem;
        }
        .btn {
            background-color: #1abc9c;
            color: white;
            padding: 0.75rem 1.5rem;
            border: none;
            border-radius: 4px;
            font-size: 1rem;
            cursor: pointer;
            text-decoration: none;
        }
        .btn:hover {
            background-color: #16a085;
        }
        /* ส่วนท้ายเว็บไซต์ */
        footer {
            text-align: center;
            padding: 1.5rem;
            background-color: #2c3e50;
            color: white;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>

    <!-- Header -->
    <header>
        <h2>MyWebsite</h2>
        <nav>
            <a href="#">หน้าแรก</a>
            <a href="#">เกี่ยวกับเรา</a>
            <a href="#">ติดต่อ</a>
        </nav>
    </header>

    <!-- Main Content -->
    <main class="hero">
        <h1>ยินดีต้อนรับสู่เว็บไซต์ของฉัน</h1>
        <p>นี่คือตัวอย่างหน้าเว็บที่สร้างด้วย HTML และ CSS เบื้องต้น พร้อมนำไปปรับแต่งต่อได้ทันที</p>
        <a href="#" class="btn">เริ่มต้นใช้งาน</a>
    </main>

    <!-- Footer -->
    <footer>
        <p>&copy; 2026 MyWebsite. สงวนลิขสิทธิ์.</p>
    </footer>

</body>
</html>
