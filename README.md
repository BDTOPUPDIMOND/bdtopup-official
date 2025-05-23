# bdtopup-official <!DOCTYPE html>
<html lang="bn">
<head>
  <meta charset="UTF-8">
  <title>BDTOPUP.COM | Premium Order System</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <style>
    body {
      margin: 0; font-family: 'Noto Sans Bengali', sans-serif;
      background: linear-gradient(to right, #8E2DE2, #4A00E0);
      color: #fff;
    }
    .container {
      max-width: 600px;
      margin: auto;
      background: #ffffff;
      color: #000;
      padding: 20px;
      border-radius: 12px;
      box-shadow: 0 0 12px rgba(0,0,0,0.2);
      margin-top: 40px;
    }
    h1, h2 {
      text-align: center;
      color: #1E88E5;
    }
    .bismillah {
      text-align: center;
      font-size: 22px;
      font-weight: bold;
      color: #4A00E0;
      margin-bottom: 10px;
    }
    select, input, button {
      width: 100%;
      padding: 12px;
      margin: 10px 0;
      border-radius: 8px;
      border: 1px solid #ccc;
      font-size: 16px;
    }
    button {
      background: linear-gradient(to right, #FF512F, #DD2476);
      color: white;
      border: none;
      font-weight: bold;
      cursor: pointer;
    }
    .success-msg {
      display: none;
      background: #4CAF50;
      color: white;
      padding: 10px;
      text-align: center;
      border-radius: 5px;
      margin-top: 10px;
    }
    .copy-box {
      background: #f2f2f2;
      padding: 10px;
      border-radius: 6px;
      text-align: center;
      margin-bottom: 10px;
    }
  </style>
</head>
<body>

<div class="container">
  <div class="bismillah">Ø¨ÙØ³Ù’Ù…Ù Ø§Ù„Ù„ÙŽÙ‘Ù‡Ù Ø§Ù„Ø±ÙŽÙ‘Ø­Ù’Ù…ÙŽÙ°Ù†Ù Ø§Ù„Ø±ÙŽÙ‘Ø­ÙÙŠÙ…Ù</div>
  <h1>BDTOPUP.COM</h1>
  <h2>à¦«à§à¦°à¦¿ à¦«à¦¾à§Ÿà¦¾à¦° à¦…à¦°à§à¦¡à¦¾à¦° à¦¸à¦¿à¦¸à§à¦Ÿà§‡à¦®</h2>

  <label>UID</label>
  <input type="text" id="uid" placeholder="à¦†à¦ªà¦¨à¦¾à¦° UID à¦²à¦¿à¦–à§à¦¨">

  <label>à¦ªà§à¦¯à¦¾à¦•à§‡à¦œ à¦¸à¦¿à¦²à§‡à¦•à§à¦Ÿ à¦•à¦°à§à¦¨</label>
  <select id="diamond">
<option>25 à¦¡à¦¾à§Ÿà¦®à¦¨à§à¦¡ â€“ à§¨à§¦ à¦Ÿà¦¾à¦•à¦¾</option>
<option>50 à¦¡à¦¾à§Ÿà¦®à¦¨à§à¦¡ â€“ à§©à§¦ à¦Ÿà¦¾à¦•à¦¾</option>
<option>115 à¦¡à¦¾à§Ÿà¦®à¦¨à§à¦¡ â€“ à§­à§« à¦Ÿà¦¾à¦•à¦¾</option>
<option>240 à¦¡à¦¾à§Ÿà¦®à¦¨à§à¦¡ â€“ à§§à§ªà§¦ à¦Ÿà¦¾à¦•à¦¾</option>
<option>610 à¦¡à¦¾à§Ÿà¦®à¦¨à§à¦¡ â€“ à§©à§¬à§¦ à¦Ÿà¦¾à¦•à¦¾</option>
<option>1240 à¦¡à¦¾à§Ÿà¦®à¦¨à§à¦¡ â€“ à§¬à§¯à§¯ à¦Ÿà¦¾à¦•à¦¾</option>
<option>2530 à¦¡à¦¾à§Ÿà¦®à¦¨à§à¦¡ â€“ à§§à§ªà§«à§¦ à¦Ÿà¦¾à¦•à¦¾</option>
<option>5060 à¦¡à¦¾à§Ÿà¦®à¦¨à§à¦¡ â€“ à§¨à§¯à§¦à§¦ à¦Ÿà¦¾à¦•à¦¾</option>
<option>10120 à¦¡à¦¾à§Ÿà¦®à¦¨à§à¦¡ â€“ à§¬à§¦à§¦à§¦ à¦Ÿà¦¾à¦•à¦¾</option>
<option>à¦‰à¦‡à¦•à¦²à¦¿ à¦²à¦¾à¦‡à¦Ÿ â€“ à§©à§¦ à¦Ÿà¦¾à¦•à¦¾</option>
<option>à¦‰à¦‡à¦•à¦²à¦¿ â€“ à§§à§©à§¦ à¦Ÿà¦¾à¦•à¦¾</option>
<option>à¦®à¦¾à¦Ÿà¦²à¦¿ â€“ à§«à§®à§¦ à¦Ÿà¦¾à¦•à¦¾</option>
<option>à¦²à§‡à¦­à§‡à¦² à¦†à¦ª à¦ªà¦¾à¦¶ â€“ à§§à§©à§¦ à¦Ÿà¦¾à¦•à¦¾</option>
<option>à§¦.à§¯à§¯$ â€“ à§®à§¦ à¦Ÿà¦¾à¦•à¦¾</option>
<option>à§§.à§¯à§¯$ â€“ à§§à§®à§¦ à¦Ÿà¦¾à¦•à¦¾</option>
<option>à§¨.à§¯à§¯$ â€“ à§¨à§®à§¦ à¦Ÿà¦¾à¦•à¦¾</option>
<option>à§©.à§¯à§¯$ â€“ à§©à§®à§¦ à¦Ÿà¦¾à¦•à¦¾</option>
<option>à¦‡à¦­à§ à¦à¦•à§à¦¸à¦¸à§‡à¦¸ â€“ à§© à¦¦à¦¿à¦¨ â€“ à§¬à§¯ à¦Ÿà¦¾à¦•à¦¾</option>
<option>à¦‡à¦­à§ à¦à¦•à§à¦¸à¦¸à§‡à¦¸ â€“ à§­ à¦¦à¦¿à¦¨ â€“ à§§à§§à§¦ à¦Ÿà¦¾à¦•à¦¾</option>
<option>à¦‡à¦­à§ à¦à¦•à§à¦¸à¦¸à§‡à¦¸ â€“ à§©à§¦ à¦¦à¦¿à¦¨ â€“ à§¨à§®à§­ à¦Ÿà¦¾à¦•à¦¾</option>
<option>à§« à¦¡à¦¾à§Ÿà¦®à¦¨à§à¦¡ â€“ à§§à§« à¦Ÿà¦¾à¦•à¦¾</option>
<option>à§«à§¦ à¦¡à¦¾à§Ÿà¦®à¦¨à§à¦¡ â€“ à§¬à§¦ à¦Ÿà¦¾à¦•à¦¾</option>
<option>à§­à§¦ à¦¡à¦¾à§Ÿà¦®à¦¨à§à¦¡ â€“ à§®à§¦ à¦Ÿà¦¾à¦•à¦¾</option>
<option>à§§à§ªà§¦ à¦¡à¦¾à§Ÿà¦®à¦¨à§à¦¡ â€“ à§§à§­à§¦ à¦Ÿà¦¾à¦•à¦¾</option>
<option>à§©à§«à§« à¦¡à¦¾à§Ÿà¦®à¦¨à§à¦¡ â€“ à§ªà§ªà§¦ à¦Ÿà¦¾à¦•à¦¾</option>
<option>à§­à§¨à§¦ à¦¡à¦¾à§Ÿà¦®à¦¨à§à¦¡ â€“ à§®à§©à§¦ à¦Ÿà¦¾à¦•à¦¾</option>
<option>à§§à§ªà§ªà§¦ à¦¡à¦¾à§Ÿà¦®à¦¨à§à¦¡ â€“ à§§à§®à§¯à§¦ à¦Ÿà¦¾à¦•à¦¾</option>
<option>Level Up Pass â€“ à§§à§­à§¦ à¦Ÿà¦¾à¦•à¦¾</option>
<option>Weekly â€“ à§¨à§«à§¯ à¦Ÿà¦¾à¦•à¦¾</option>
<option>Monthly â€“ à§®à§¯à§¯ à¦Ÿà¦¾à¦•à¦¾</option>
<option>BP Card â€“ à§©à§¯à§¯ à¦Ÿà¦¾à¦•à¦¾</option>
</select>

<button onclick="toggleMode()" style="margin-top:10px;background:#444;">ðŸŒ™ Light/Dark à¦®à§‹à¦¡</button>

  <label>à¦Ÿà¦¾à¦•à¦¾</label>
  <input type="text" id="amount" placeholder="à¦Ÿà¦¾à¦•à¦¾ à¦²à¦¿à¦–à§à¦¨">

  <label>TrxID</label>
  <input type="text" id="trxid" placeholder="à¦¬à¦¿à¦•à¦¾à¦¶ / à¦¨à¦—à¦¦ TrxID à¦¦à¦¿à¦¨">

  <label>Server</label>
  <select id="server">
    <option>Bangladesh</option>
    <option>Indonesia</option>
  </select>

  <div class="copy-box">
    à¦¬à¦¿à¦•à¦¾à¦¶/à¦¨à¦—à¦¦ à¦¨à¦®à§à¦¬à¦°: <strong id="payNum">01822769871</strong><br>
    <button onclick="copyNumber()">à¦•à¦ªà¦¿ à¦•à¦°à§à¦¨ + Send Money à¦•à¦°à§à¦¨</button>
  </div>

  <button onclick="placeOrder()">âœ… à¦…à¦°à§à¦¡à¦¾à¦° à¦•à¦°à§à¦¨</button>

  <div class="success-msg" id="successBox">âœ… à¦…à¦°à§à¦¡à¦¾à¦° à¦¸à¦«à¦² à¦¹à§Ÿà§‡à¦›à§‡!</div>

<div id="historyBox" style="margin-top:30px; background:#f0f0f0; padding:15px; border-radius:8px; color:#000;">
  <h3>ðŸ“œ à¦…à¦°à§à¦¡à¦¾à¦° à¦¹à¦¿à¦¸à§à¦Ÿà§‹à¦°à¦¿</h3>
  <div id="historyList">à¦à¦–à¦¨à¦“ à¦•à§‹à¦¨à§‹ à¦…à¦°à§à¦¡à¦¾à¦° à¦ªà¦¾à¦“à§Ÿà¦¾ à¦¯à¦¾à§Ÿà¦¨à¦¿à¥¤</div>
</div>


<script>
  function copyNumber() {
    const text = document.getElementById("payNum").innerText;
    navigator.clipboard.writeText(text);
    alert("à¦¨à¦¾à¦®à§à¦¬à¦¾à¦° à¦•à¦ªà¦¿ à¦¹à§Ÿà§‡à¦›à§‡: " + text);
  }

  function placeOrder() {
    const uid = document.getElementById("uid").value;
    const diamond = document.getElementById("diamond").value;
    const amount = document.getElementById("amount").value;
    const trxid = document.getElementById("trxid").value;
    const server = document.getElementById("server").value;

    const message = `âœ… à¦¨à¦¤à§à¦¨ à¦…à¦°à§à¦¡à¦¾à¦°
UID: ${uid}
à¦ªà§à¦¯à¦¾à¦•à§‡à¦œ: ${diamond}
à¦Ÿà¦¾à¦•à¦¾: ${amount}
TrxID: ${trxid}
Server: ${server}`;

    const token = "<YOUR_BOT_ID>" + ":" + "<YOUR_BOT_TOKEN>";
    const chatId = "6108340963";

    fetch(`https://api.telegram.org/bot${token}/sendMessage`, {
      method: "POST",
      headers: { "Content-Type": "application/json" },
      body: JSON.stringify({ chat_id: chatId, text: message })
    }).then(res => {
      if (res.ok) {
  document.getElementById("successBox").style.display = "block";
  const history = JSON.parse(localStorage.getItem("orderHistory") || "[]");
  history.push({ uid, diamond, amount, trxid, server, time: new Date().toLocaleString() });
  localStorage.setItem("orderHistory", JSON.stringify(history));
  loadOrderHistory();
        document.getElementById("successBox").style.display = "block";
      }
    });
  }

function toggleMode() {
  const body = document.body;
  if (body.style.background === "black") {
    body.style.background = "";
    body.style.color = "";
  } else {
    body.style.background = "black";
    body.style.color = "white";
  }
}

// Auto Friday offer
document.addEventListener("DOMContentLoaded", () => {
  const today = new Date().getDay();
  if (today === 5) {
    const diamondDropdown = document.getElementById("diamond");
    for (let i = 0; i < diamondDropdown.options.length; i++) {
      if (diamondDropdown.options[i].text.includes("à¦‰à¦‡à¦•à¦²à¦¿ â€“ à§§à§©à§¦ à¦Ÿà¦¾à¦•à¦¾")) {
        diamondDropdown.options[i].text = "à¦‰à¦‡à¦•à¦²à¦¿ â€“ à§®à§¦ à¦Ÿà¦¾à¦•à¦¾ (à¦¶à§à¦•à§à¦°à¦¬à¦¾à¦° à¦…à¦«à¦¾à¦°)";
      }
    }
  }

  loadOrderHistory();
});

function loadOrderHistory() {
  const history = JSON.parse(localStorage.getItem("orderHistory") || "[]").reverse();
  const historyList = document.getElementById("historyList");
  if (!history.length) {
    historyList.innerHTML = "à¦à¦–à¦¨à¦“ à¦•à§‹à¦¨à§‹ à¦…à¦°à§à¦¡à¦¾à¦° à¦ªà¦¾à¦“à§Ÿà¦¾ à¦¯à¦¾à§Ÿà¦¨à¦¿à¥¤";
    return;
  }
  historyList.innerHTML = history.map(o => `
    <div style='margin-bottom:10px;padding:10px;border-radius:6px;background:#fff;color:#000'>
      <b>UID:</b> ${o.uid}<br>
      <b>à¦ªà§à¦¯à¦¾à¦•à§‡à¦œ:</b> ${o.diamond}<br>
      <b>à¦Ÿà¦¾à¦•à¦¾:</b> ${o.amount}<br>
      <b>TrxID:</b> ${o.trxid}<br>
      <b>Server:</b> ${o.server}<br>
      <small>${o.time}</small>
    </div>
  `).join("");
}

</script>

</body>
</html>
