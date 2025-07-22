
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>yeongEundiary</title>
    <link href="../chat.css" rel="stylesheet">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Noto+Serif+KR:wght@400;700&display=swap" rel="stylesheet">
</head>
<body>
    <div class="container">

        <main class="chat-screen">
            <section class="chat-screen__bar">
                <div class="user">
                    <div class="user__column">
                        <div class="user__pic"></div>
                    </div>
                    <div class="user__column">
                        <p class="user__nick">친구</p>
                        <p class="user__count">2</p>
                    </div>
                </div>
            </section>
        </main>

        <form class= "chat-form">
            <section class="chat-form__field">
                <textarea class="chat-form__msg"></textarea>
                <input type="submit" value="전송" class="chat-form__bt">
            </section>
        </form>
    </div>
</body>
</html>
