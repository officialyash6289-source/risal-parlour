# <!DOCTYPE html>
<html>
<head>
<title>Risal Man's Parlour</title>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
body { font-family: Arial; text-align: center; background: black; color: white; }
button { padding: 15px; font-size: 20px; width: 90%; margin-top: 15px; }
.count { font-size: 55px; font-weight: bold; color: #00ff00; }
</style>
</head>
<body>

<h1>💈 Risal Man's Parlour 💈</h1>
<p>Dolatpura, Salai Wali Masjid ke Pas</p>

<p>☎ WhatsApp: <b>+91 70679 42006</b></p>

<h2>🎟 Current Token Number</h2>
<div class="count" id="counter">1</div>

<button onclick="next()">NEXT Customer</button>
<button onclick="reset()">RESET Queue</button>

<a href="https://wa.me/917067942006?text=Sir+Kitna+Wait+Hai?" target="_blank">
<button>📲 WhatsApp Booking</button>
</a>

<script>
let count = 1;
function next(){ count++; document.getElementById("counter").innerHTML = count; }
function reset(){ count = 1; document.getElementById("counter").innerHTML = count; }
</script>

</body>
</html>
