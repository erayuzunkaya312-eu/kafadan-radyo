<!DOCTYPE html>
<html lang="tr">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>KAFADAN RADYO</title>
<style>
*{box-sizing:border-box}
body{
    margin:0;
    min-height:100vh;
    font-family:Arial,sans-serif;
    background:linear-gradient(135deg,#080808,#1a1a1a);
    color:white;
    display:flex;
    justify-content:center;
    align-items:center;
    padding:20px;
}
.container{
    width:100%;
    max-width:600px;
    text-align:center;
}
.logo{
    font-size:42px;
    font-weight:900;
    letter-spacing:3px;
    margin-bottom:8px;
}
.subtitle{
    color:#aaa;
    margin-bottom:25px;
}
.live{
    display:inline-block;
    background:#e81e4d;
    padding:8px 18px;
    border-radius:30px;
    font-weight:bold;
    margin-bottom:20px;
}
.player{
    background:#111;
    border-radius:20px;
    padding:20px;
    box-shadow:0 10px 40px rgba(0,0,0,.5);
    margin-bottom:20px;
}
.buttons{
    display:flex;
    flex-direction:column;
    gap:12px;
}
.button{
    display:block;
    text-decoration:none;
    color:white;
    padding:16px;
    border-radius:12px;
    font-size:18px;
    font-weight:bold;
}
.whatsapp{
    background:#25D366;
}
.request{
    background:#e81e4d;
}
.footer{
    margin-top:25px;
    color:#777;
    font-size:13px;
}
</style>
</head>
<body>
<div class="container">
    <div class="logo">KAFADAN RADYO</div>
    <div class="subtitle">
        🎙️ Müziğin, sohbetin ve eğlencenin kafadan hali!
    </div>
    <div class="live">🔴 CANLI YAYIN</div>
    <div class="player">
        <div
        data-type="newStreamPlayer"
        data-publicToken="8682c047-02b0-48c7-9d67-2e9ef5d59c42"
        data-theme="dark"
        data-color="e81e4d"
        data-channelId="a2ab2d73-205a-47fb-87a1-2683956b9937"
        data-rendered="false"
        class="cstrEmbed">
        <a href="https://www.caster.fm">Shoutcast Hosting</a>
        <a href="https://www.caster.fm">Stream Hosting</a>
        <a href="https://www.caster.fm">Radio Server Hosting</a>
        </div>
    </div>
    <div class="buttons">
        <a
        class="button whatsapp"
        href="https://wa.me/905421908241?text=Merhaba%20KAFADAN%20RADYO%2C%20%C4%B0stek%20par%C3%A7am%20var%20%F0%9F%8E%B5"
        target="_blank">
        💬 WhatsApp'tan İstek Parça
        </a>
        <a
        class="button request"
        href="https://wa.me/905421908241?text=KAFADAN%20RADYO%20%C4%B0stek%20Par%C3%A7a%0A%0A%C5%9Eark%C4%B1%3A%0AArtist%3A%0A%0ASevgiler!"
        target="_blank">
        🎵 İstek Parça Gönder
        </a>
    </div>
    <div class="footer">
        KAFADAN RADYO © 2026
    </div>
</div>
<script src="//cdn.cloud.caster.fm//widgets/embed.js"></script>
</body>
</html>
