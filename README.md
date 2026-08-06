<html>
<head>
    <title>Vocab App</title>
</head>
<body style="font-family:sans-serif; text-align:center; background:#f4f7f6; padding-top:50px;">
    <h1>Aplikasi Hafalan Vocab Ari Studio</h1>
    
    <div id="card" style="border:2px solid #007bff; border-radius:15px; padding:40px; width:250px; margin:30px auto; font-size:28px; font-weight:bold; cursor:pointer; background:#ffffff; box-shadow:0 4px 8px rgba(0,0,0,0.1);" onclick="flip()">
        Book
    </div>
    
    <p style="color:#666;">Klik kotak di atas untuk melihat artinya</p>

    <script>
        function flip() {
            const card = document.getElementById("card");
            if (card.innerText === "Book") {
                card.innerText = "Buku";
                card.style.background = "#e6f2ff";
            } else {
                card.innerText = "Book";
                card.style.background = "#ffffff";
            }
        }
    </script>
</body>
</html>
