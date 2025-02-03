# maiasamxarauli.github.io
<!DOCTYPE html>
<html lang="ka">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ლამაზი HTML საიტი</title>
</head>
<body style="background-color: #0d0d0d; color: white; text-align: center; padding-top: 20vh;">

    <!-- მოძრაობის მქონე ტექსტი -->
    <marquee style="font-size: 50px; font-weight: bold; color: #ff1493;">✨ ეს მხოლოდ HTML-ია! ✨</marquee>

    <!-- მბზინავი და მოძრავი ტექსტი -->
    <h1 style="font-size: 70px; color: #ff1493; text-shadow: 0 0 10px #ff1493, 0 0 20px #ff1493; animation: glow 2s infinite alternate;">
        ლამაზი HTML საიტი
    </h1>

    <!-- ჯადოსნური ტექსტი -->
    <h2 style="font-size: 40px; color: #00fa9a;">თქვენი საიტი დღეს ცოცხლდება!</h2>

    <!-- შემოსული ბრწყინვალე ღილაკი -->
    <button style="background-color: #ff1493; border: none; padding: 15px 32px; color: white; font-size: 20px; font-weight: bold; cursor: pointer; border-radius: 25px;">
        აი წაიკითხე!
    </button>

    <!-- JavaScript-ის გამოყენება ტექსტის ცვლილებისთვის -->
    <script>
        setTimeout(function() {
            document.querySelector("h2").innerHTML = "თქვენი HTML საიტი გამაოგნებელი იქნება!";
        }, 3000); // 3 წამში შეიცვლება ტექსტი
    </script>

    <style>
        @keyframes glow {
            0% {
                color: #ff1493;
                text-shadow: 0 0 10px #ff1493, 0 0 20px #ff1493, 0 0 30px #ff1493;
            }
            50% {
                color: #00fa9a;
                text-shadow: 0 0 10px #00fa9a, 0 0 20px #00fa9a, 0 0 30px #00fa9a;
            }
            100% {
                color: #ff1493;
                text-shadow: 0 0 10px #ff1493, 0 0 20px #ff1493, 0 0 30px #ff1493;
            }
        }
    </style>

</body>
</html>
