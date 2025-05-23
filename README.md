<!DOCTYPE html>
<html lang="bn">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>BDTOPUP.COM</title>
  <style>
    body {
      font-family: 'Noto Sans Bengali', sans-serif;
      background: linear-gradient(to right, #e3f2fd, #ffffff);
      padding: 20px; margin: 0;
    }
    .container {
      max-width: 700px; margin: auto;
      background: #ffffff; padding: 20px;
      border-radius: 12px; box-shadow: 0 0 12px rgba(0,0,0,0.1);
    }
    .title { text-align: center; color: #1976d2; }
    .section { margin-top: 20px; }
    .input, select {
      width: 100%; padding: 10px; margin-top: 8px;
      border-radius: 6px; border: 1px solid #ccc;
    }
    .btn {
      margin-top: 15px; width: 100%;
      background: #1976d2; color: white;
      border: none; padding: 10px;
      border-radius: 6px; cursor: pointer;
    }
    .success {
      display: none; background: #c8e6c9;
      padding: 10px; border-radius: 6px;
      margin-top: 10px; color: #256029;
    }
    .copy-box {
      background: #fff3cd; padding: 10px;
      border-radius: 6px; border: 1px solid #ffeeba;
      margin-top: 10px;
    }
    .alert {
      background: #ffebee; border: 1px solid #f44336;
      padding: 10px; border-radius: 6px;
      margin-bottom: 20px; color: #b71c1c;
    }
    .history {
      background: #f4f4f4; padding: 10px;
      border-radius: 6px; margin-top: 10px;
    }
    .helpline {
      text-align: center; margin-top: 20px;
    }
    .helpline a {
      background: #007bff; color: white;
      padding: 10px 20px; border-radius: 6px;
      text-decoration: none;
    }
  </style>
</head>
<body>

<div class="container">
  <h2 class="title">بِسْمِ اللَّهِ الرَّحْمَٰنِ الرَّحِيمِ</h2>
  <h3 class="title">BDTOPUP.COM — বিশ্বস্ত Diamond Topup সার্ভিস</h3>
  <div style="background:#e3f2fd;padding:15px;margin-top:10px;border-radius:8px;border:1px solid #90caf9;">
    <p style="color:#000;">
      ভাবছেন ডায়মন্ড নিবেন, কিন্তু বিশ্বস্ত পেজ পাচ্ছেন না?<br/>
      <strong>বিশ্বস্ততার সাথে টপ-আপ দেওয়াই আমাদের মূল লক্ষ্য!</strong>
    </p>
    <ul style="color:#000;">
      <li>✅ অল্প দামে সব সার্ভিস</li>
      <li>✅ ৫ বছর ধরে বিশ্বস্ততার সাথে ব্যবসা</li>
      <li>✅ কাস্টমার রিভিউ Available</li>
      <li>✅ ইনস্ট্যান্ট অর্ডার সিস্টেম (UID + TrxID)</li>
      <li>⏰ ডেলিভারি টাইম: মাত্র ৩০ সেকেন্ড</li>
      <li>💸 পেমেন্ট: বিকাশ, নগদ, রকেট (Send Money)</li>
    </ul>
  </div>

  <div class="alert">⚠️ সতর্কতা: ভুল UID / TrxID দিলে অর্ডার বাতিল হতে পারে। আগে টাকা পাঠিয়ে TrxID দিন।</div>

  <div class="section">
    <label>UID:</label>
    <input type="text" class="input" id="uid" placeholder="আপনার UID দিন" />
    
    <label>প্যাকেজ:</label>
    <select class="input" id="package">
      <option disabled selected>— বাংলাদেশ সার্ভার —</option>
      <option>25 ডায়মন্ড – ২০ টাকা</option>
      <option>50 ডায়মন্ড – ৩০ টাকা</option>
      <option>115 ডায়মন্ড – ৭৫ টাকা</option>
      <option>240 ডায়মন্ড – ১৪০ টাকা</option>
      <option>610 ডায়মন্ড – ৩৬০ টাকা</option>
      <option>1240 ডায়মন্ড – ৬৯৯ টাকা</option>
      <option>2530 ডায়মন্ড – ১৪৫০ টাকা</option>
      <option>5060 ডায়মন্ড – ২৯০০ টাকা</option>
      <option>10120 ডায়মন্ড – ৬০০০ টাকা</option>
      <option disabled>— উইকলি / মাসিক / লেভেল আপ —</option>
      <option id="fridayOffer">উইকলি – ১৩০ টাকা</option>
      <option>উইকলি লাইট – ৩০ টাকা</option>
      <option>মাসিক – ৫৮০ টাকা</option>
      <option>লেভেল আপ পাশ – ১৩০ টাকা</option>
      <option disabled>— এয়ারড্রপ —</option>
      <option>0.99$ – ৮০ টাকা</option>
      <option>1.99$ – ১৮০ টাকা</option>
      <option>2.99$ – ২৮০ টাকা</option>
      <option>3.99$ – ৩৮০ টাকা</option>
      <option disabled>— ইভু এক্সেস —</option>
      <option>3 দিন – ৬৯ টাকা</option>
      <option>7 দিন – ১১০ টাকা</option>
      <option>30 দিন – ২৮৭ টাকা</option>
      <option disabled>— ইন্দোনেশিয়া সার্ভার —</option>
      <option>5 ডায়মন্ড – ১৫ টাকা</option>
      <option>50 ডায়মন্ড – ৬০ টাকা</option>
      <option>70 ডায়মন্ড – ৮০ টাকা</option>
      <option>140 ডায়মন্ড – ১৭০ টাকা</option>
      <option>355 ডায়মন্ড – ৪৪০ টাকা</option>
      <option>720 ডায়মন্ড – ৮৩০ টাকা</option>
      <option>1440 ডায়মন্ড – ১৮৯০ টাকা</option>
      <option>Level Up Pass – ১৭০ টাকা</option>
      <option>Weekly – ২৫৯ টাকা</option>
      <option>Monthly – ৮৯৯ টাকা</option>
      <option>BP Card – ৩৯৯ টাকা</option>
    </select>

    <label>TrxID:</label>
    <input type="text" class="input" id="trxid" placeholder="TrxID দিন" />

    <div class="copy-box">
      পেমেন্ট নাম্বার: <strong id="payNum">01822769871</strong><br/>
      <button class="btn" onclick="copyPayNum()">নম্বর কপি করুন</button>
    </div>

    <button class="btn" onclick="submitOrder()">✅ অর্ডার সাবমিট করুন</button>
    <div class="success" id="successMsg">✅ আপনার অর্ডার সফলভাবে গ্রহণ করা হয়েছে!</div>
  </div>

  <div class="section">
    <h4>📜 অর্ডার হিস্টোরি</h4>
    <div id="orderHistory" class="history">কোনো অর্ডার পাওয়া যায়নি।</div>
  </div>

  <div class="helpline">
    <a href="https://t.me/BDTOPUPCOM24" target="_blank">টপআপ এর যেই কোন সমস্যার সমাধান নিন</a>
  </div>
</div>

<script>
  function copyPayNum() {
    navigator.clipboard.writeText(document.getElementById('payNum').innerText);
    alert('নাম্বার কপি হয়েছে!');
  }

  function submitOrder() {
    const uid = document.getElementById('uid').value;
    const pkg = document.getElementById('package').value;
    const trxid = document.getElementById('trxid').value;
    const time = new Date().toLocaleString();
    const data = {uid, pkg, trxid, time};
    let history = JSON.parse(localStorage.getItem("orders") || "[]");
    history.push(data);
    localStorage.setItem("orders", JSON.stringify(history));
    document.getElementById('successMsg').style.display = 'block';
    loadHistory();
  }

  function loadHistory() {
    const history = JSON.parse(localStorage.getItem("orders") || "[]").reverse();
    const html = history.map(o => `
      <div style="margin-bottom:5px;background:#fff;padding:10px;border-radius:6px;">
        UID: ${o.uid}<br>প্যাকেজ: ${o.pkg}<br>TrxID: ${o.trxid}<br><small>${o.time}</small>
      </div>
    `).join("");
    document.getElementById('orderHistory').innerHTML = html || "কোনো অর্ডার পাওয়া যায়নি।";
  }

  function checkFridayOffer() {
    const today = new Date().getDay();
    if (today === 5) {
      document.getElementById("fridayOffer").textContent = "উইকলি – ৮০ টাকা (শুক্রবার অফার)";
    }
  }

  loadHistory();
  checkFridayOffer();
</script>

</body>
</html>
