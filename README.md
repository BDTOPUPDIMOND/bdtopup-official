<!DOCTYPE html>
<html lang="bn">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>BDTOPUP.COM — বিশ্বস্ত Diamond Topup সার্ভিস</title>
  <style>
    body { font-family: 'Arial'; background: #f2f2f2; padding: 10px; text-align: center; }
    .section-title { font-size: 20px; margin-top: 25px; font-weight: bold; color: #333; }
    .box {
      background: #fff;
      border: 2px solid #00bcd4;
      padding: 10px;
      margin: 5px auto;
      width: 90%;
      border-radius: 8px;
      cursor: pointer;
    }
    .box:hover { background: #e0f7fa; }
    .box-friday { background: #ffebee; border-color: #e53935; color: #b71c1c; }
    .warn {
      background: #fff3cd;
      color: #856404;
      padding: 10px;
      border-radius: 6px;
      margin-top: 10px;
      border: 1px solid #ffeeba;
    }
    .success {
      background: #d4edda;
      color: #155724;
      padding: 10px;
      border-radius: 6px;
      margin-top: 10px;
      display: none;
      border: 1px solid #c3e6cb;
    }
    .input-box {
      padding: 8px;
      margin: 5px;
      width: 80%;
      border-radius: 5px;
      border: 1px solid #ccc;
    }
    button {
      padding: 10px 20px;
      margin-top: 10px;
      background: #00bcd4;
      color: white;
      border: none;
      border-radius: 6px;
      cursor: pointer;
    }
    button:hover { background: #0097a7; }
  </style>
</head>
<body>

<h3 style="color:green;">بِسْمِ اللَّهِ الرَّحْمَٰنِ الرَّحِيمِ</h3>
<h2 style="color:#007bff;">BDTOPUP.COM — বিশ্বস্ত Diamond Topup সার্ভিস</h2>

<div class="warn">
  ⚠️ সতর্কতা: প্রথমে টাকা Send করে তারপর সঠিকভাবে UID ও TrxID দিয়ে অর্ডার করুন। ভুল দিলে অর্ডার বাতিল হতে পারে।
</div>

<input class="input-box" placeholder="আপনার Game UID" id="uid" />
<input class="input-box" placeholder="TrxID" id="trxid" />
<input class="input-box" id="selectedPack" placeholder="আপনার প্যাকেজ অটো বসবে" readonly />

<div class="section-title">বিকাশ/নগদ নাম্বার</div>
<div class="box" onclick="copy('01822769871')">01822769871 (Send Money করুন)</div>

<div class="section-title">শুক্রবারের বিশেষ অফার</div>
<div class="box box-friday" id="fridayBox" style="display:none;" onclick="selectPack('শুক্রবার উইকলি অফার – ৮০ টাকা')">
  শুক্রবার অফার: উইকলি – ৮০ টাকা
</div>

<div class="section-title">বাংলাদেশ সার্ভার</div>
<div class="box" onclick="selectPack('২৫ ডায়মন্ড – ২০ টাকা')">২৫ ডায়মন্ড – ২০ টাকা</div>
<div class="box" onclick="selectPack('৫০ ডায়মন্ড – ৩০ টাকা')">৫০ ডায়মন্ড – ৩০ টাকা</div>
<div class="box" onclick="selectPack('১১৫ ডায়মন্ড – ৭৫ টাকা')">১১৫ ডায়মন্ড – ৭৫ টাকা</div>
<div class="box" onclick="selectPack('২৪০ ডায়মন্ড – ১৪০ টাকা')">২৪০ ডায়মন্ড – ১৪০ টাকা</div>
<div class="box" onclick="selectPack('৬১০ ডায়মন্ড – ৩৬০ টাকা')">৬১০ ডায়মন্ড – ৩৬০ টাকা</div>
<div class="box" onclick="selectPack('১২৪০ ডায়মন্ড – ৬৯৯ টাকা')">১২৪০ ডায়মন্ড – ৬৯৯ টাকা</div>
<div class="box" onclick="selectPack('২৫৩০ ডায়মন্ড – ১৪৫০ টাকা')">২৫৩০ ডায়মন্ড – ১৪৫০ টাকা</div>
<div class="box" onclick="selectPack('৫০৬০ ডায়মন্ড – ২৯০০ টাকা')">৫০৬০ ডায়মন্ড – ২৯০০ টাকা</div>
<div class="box" onclick="selectPack('১০১২০ ডায়মন্ড – ৬০০০ টাকা')">১০১২০ ডায়মন্ড – ৬০০০ টাকা</div>

<div class="section-title">ইভো এক্সেস</div>
<div class="box" onclick="selectPack('৩ দিন – ৬৯ টাকা')">৩ দিন – ৬৯ টাকা</div>
<div class="box" onclick="selectPack('৭ দিন – ১১০ টাকা')">৭ দিন – ১১০ টাকা</div>
<div class="box" onclick="selectPack('৩০ দিন – ২৮৭ টাকা')">৩০ দিন – ২৮৭ টাকা</div>

<div class="section-title">এয়ারড্রপ</div>
<div class="box" onclick="selectPack('০.৯৯$ – ৮০ টাকা')">০.৯৯$ – ৮০ টাকা</div>
<div class="box" onclick="selectPack('১.৯৯$ – ১৮০ টাকা')">১.৯৯$ – ১৮০ টাকা</div>
<div class="box" onclick="selectPack('২.৯৯$ – ২৮০ টাকা')">২.৯৯$ – ২৮০ টাকা</div>
<div class="box" onclick="selectPack('৩.৯৯$ – ৩৮০ টাকা')">৩.৯৯$ – ৩৮০ টাকা</div>

<div class="section-title">ইন্দোনেশিয়া সার্ভার</div>
<div class="box" onclick="selectPack('৫ ডায়মন্ড – ১৫ টাকা')">৫ ডায়মন্ড – ১৫ টাকা</div>
<div class="box" onclick="selectPack('৫০ ডায়মন্ড – ৬০ টাকা')">৫০ ডায়মন্ড – ৬০ টাকা</div>
<div class="box" onclick="selectPack('৭০ ডায়মন্ড – ৮০ টাকা')">৭০ ডায়মন্ড – ৮০ টাকা</div>
<div class="box" onclick="selectPack('১৪০ ডায়মন্ড – ১৭০ টাকা')">১৪০ ডায়মন্ড – ১৭০ টাকা</div>
<div class="box" onclick="selectPack('৩৫৫ ডায়মন্ড – ৪৪০ টাকা')">৩৫৫ ডায়মন্ড – ৪৪০ টাকা</div>
<div class="box" onclick="selectPack('৭২০ ডায়মন্ড – ৮৩০ টাকা')">৭২০ ডায়মন্ড – ৮৩০ টাকা</div>
<div class="box" onclick="selectPack('১৪৪০ ডায়মন্ড – ১৮৯০ টাকা')">১৪৪০ ডায়মন্ড – ১৮৯০ টাকা</div>
<div class="box" onclick="selectPack('Level Up Pass – ১৭০ টাকা')">Level Up Pass – ১৭০ টাকা</div>
<div class="box" onclick="selectPack('Weekly – ২৫৯ টাকা')">Weekly – ২৫৯ টাকা</div>
<div class="box" onclick="selectPack('Monthly – ৮৯৯ টাকা')">Monthly – ৮৯৯ টাকা</div>
<div class="box" onclick="selectPack('BP Card – ৩৯৯ টাকা')">BP Card – ৩৯৯ টাকা</div>

<button onclick="order()">✅ অর্ডার করুন</button>

<div class="success" id="successMsg"></div>

<div style="margin-top:20px;">
  <a href="https://t.me/BDTOPUPCOM24" target="_blank">
    <button style="background:#1976d2;">টপআপ এর যেকোন সমস্যার সমাধান নিন</button>
  </a>
</div>

<script>
  function selectPack(text) {
    document.getElementById("selectedPack").value = text;
  }

  function copy(text) {
    navigator.clipboard.writeText(text);
    alert("পেমেন্ট নাম্বার কপি হয়েছে: " + text);
  }

  function order() {
    const uid = document.getElementById("uid").value.trim();
    const trxid = document.getElementById("trxid").value.trim();
    const pack = document.getElementById("selectedPack").value.trim();
    if (!uid || !trxid || !pack) {
      alert("UID, TrxID ও প্যাকেজ সিলেক্ট করতে হবে!");
      return;
    }
    document.getElementById("successMsg").innerHTML = 
      `✅ অর্ডার সফল হয়েছে!<br>UID: ${uid}<br>প্যাকেজ: ${pack}<br>আপনার গেমে ডায়মন্ড পৌঁছে যাবে ইনশাআল্লাহ।`;
    document.getElementById("successMsg").style.display = "block";
  }

  if (new Date().getDay() === 5) {
    document.getElementById("fridayBox").style.display = "block";
  }
</script>

</body>
</html>
