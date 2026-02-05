
<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <title>Gửi em</title>

    <style>
        body {
            margin: 0;
            height: 100vh;
            background: linear-gradient(135deg, #667eea, #764ba2);
            display: flex;
            justify-content: center;
            align-items: center;
            font-family: 'Segoe UI', sans-serif;
            color: white;
            text-align: center;
        }

        .box {
            background: rgba(255, 255, 255, 0.15);
            padding: 30px;
            border-radius: 16px;
            max-width: 420px;
            box-shadow: 0 0 30px rgba(0,0,0,0.3);
            animation: fadeIn 2s ease;
        }

        h1 {
            margin-bottom: 15px;
            font-size: 28px;
        }

        p {
            line-height: 1.6;
            font-size: 16px;
        }

        button {
            margin-top: 20px;
            padding: 12px 24px;
            border: none;
            border-radius: 25px;
            background: white;
            color: #764ba2;
            font-size: 16px;
            cursor: pointer;
            transition: 0.3s;
        }

        button:hover {
            background: #f1f1f1;
            transform: scale(1.05);
        }

        @keyframes fadeIn {
            from {
                opacity: 0;
                transform: translateY(20px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }
    </style>
</head>

<body>
    <div class="box">
        <h1>Gửi em 💜</h1>
        <p>
            Có những người không cần ở cạnh mỗi ngày,<br>
            nhưng chỉ cần nghĩ tới thôi là đã thấy ấm rồi.
        </p>

        <button onclick="showMessage()">Bấm thử đi</button>
    </div>

    <script>
        function showMessage() {
            alert("Hùng chỉ muốn nói là… Hùng trân trọng em nhiều lắm 🌙");
        }
    </script>
</body>
</html>