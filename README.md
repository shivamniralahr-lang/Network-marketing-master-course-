<!DOCTYPE html>
<html lang="hi">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width,initial-scale=1">
<title>Payment Successful - Network Marketing Mastery</title>
<style>
body{font-family:'Poppins',sans-serif;background:#e9f9ee;text-align:center;padding:40px;}
.card{background:white;max-width:500px;margin:0 auto;padding:40px;border-radius:12px;box-shadow:0 0 20px rgba(0,0,0,0.1);}
h1{color:#2d8659;}
a{background:#2d8659;color:white;padding:12px 20px;border-radius:8px;text-decoration:none;}
a:hover{background:#237147;}
</style>
</head>
<body>
<div class="card">
  <h1>🎉 पेमेंट सफल!</h1>
  <p>आपका धन्यवाद! आपका Network Marketing Mastery कोर्स सक्रिय कर दिया गया है।</p>
  <p>डाउनलोड लिंक: <br><a href="https://yourdomain.com/downloads/course.zip" target="_blank">Course डाउनलोड करें</a></p>
  <p style="font-size:0.9rem;color:#555;">यदि लिंक काम न करे तो हमें support@yourdomain.com पर लिखें।</p>
</div>
</body>
</html>
<!DOCTYPE html>
<html lang="hi">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Network Marketing Mastery - हिन्दी कोर्स</title>
<style>
body { font-family: 'Poppins', sans-serif; background:#f7f9fb; margin:0; color:#222; }
header { background:#007bff; color:white; text-align:center; padding:30px 10px; }
header h1 { margin:0; font-size:2rem; }
.container { max-width:900px; margin:30px auto; background:#fff; border-radius:12px; box-shadow:0 0 25px rgba(0,0,0,0.1); padding:30px; }
h2 { color:#007bff; }
.price { font-size:1.6rem; font-weight:700; color:#222; }
button { background:#007bff; color:#fff; border:none; padding:12px 24px; border-radius:8px; font-size:1.1rem; cursor:pointer; }
button:hover { background:#0056b3; }
section { margin-bottom:30px; }
footer { background:#111; color:#ccc; text-align:center; padding:20px; font-size:0.9rem; margin-top:40px; }
</style>
</head>
<body>

<header>
  <h1>Network Marketing Mastery (हिन्दी कोर्स)</h1>
  <p>सफल नेटवर्क मार्केटर बनने की सम्पूर्ण गाइड — PDF + Video स्क्रिप्ट्स</p>
</header>

<div class="container">
  <section>
    <h2>📘 कोर्स परिचय</h2>
    <p>यह कोर्स आपको नेटवर्क मार्केटिंग के हर पहलू को सिखाएगा — माइंडसेट से लेकर डिजिटल प्रमोशन तक। 
    इसमें 7 विस्तृत मॉड्यूल, स्टेप-बाय-स्टेप गाइड और वीडियो स्क्रिप्ट शामिल हैं।</p>
  </section>

  <section>
    <h2>💡 आपको क्या मिलेगा:</h2>
    <ul>
      <li>7 मॉड्यूल (हिन्दी नोट्स + वीडियो स्क्रिप्ट)</li>
      <li>टीम बिल्डिंग, मार्केटिंग और डिजिटल प्रमोशन ट्रेनिंग</li>
      <li>Bonus: WhatsApp & Instagram मार्केटिंग टेम्पलेट्स</li>
      <li>लाइफटाइम एक्सेस और फ्री अपडेट्स</li>
    </ul>
  </section>

  <section>
    <h2>💰 कीमत:</h2>
    <p class="price">₹999 / केवल एक बार</p>
    <button id="buyBtn">अभी खरीदें (₹999)</button>
    <p style="font-size:0.9rem; color:#666;">सुरक्षित भुगतान — Razorpay द्वारा</p>
  </section>

  <section>
    <h2>🧭 कोर्स मॉड्यूल्स:</h2>
    <ol>
      <li>नेटवर्क मार्केटिंग का परिचय</li>
      <li>सफलता की सोच (Mindset)</li>
      <li>संवाद और प्रस्तुति कौशल</li>
      <li>टीम बिल्डिंग और नेतृत्व</li>
      <li>बिक्री और मार्केटिंग रणनीति</li>
      <li>डिजिटल नेटवर्क मार्केटिंग</li>
      <li>नियम, नैतिकता और कानूनी पहलू</li>
    </ol>
  </section>
</div>

<footer>
  <p>© 2025 Network Marketing Mastery | सभी अधिकार सुरक्षित</p>
</footer>

<script src="https://checkout.razorpay.com/v1/checkout.js"></script>
<script>
document.getElementById('buyBtn').addEventListener('click', function(){
  var options = {
    "key": "RAZORPAY_KEY_ID",
    "amount": 99900,
    "currency": "INR",
    "name": "Network Marketing Mastery",
    "description": "Full Hindi Course",
    "handler": function (response){
      window.location.href = "thankyou.html";
    },
    "theme": { "color": "#007bff" }
  };
  var rzp = new Razorpay(options);
  rzp.open();
});
</script>

</body>
</html>
