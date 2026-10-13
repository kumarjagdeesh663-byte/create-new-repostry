
<!DOCTYPE html>
<html lang="hi">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<meta name="theme-color" content="#0b1730">
<meta name="description" content="Safe Drive Bhiwadi - अपनी कार के लिए ड्राइवर बुक करें।">
<title>Safe Drive Bhiwadi | ड्राइवर बुकिंग</title>
<style>
*{box-sizing:border-box}
body{margin:0;font-family:Arial,sans-serif;background:#f3f5f9;color:#172033;line-height:1.6}
header{background:linear-gradient(135deg,#09152d,#1b3760);color:white;text-align:center;padding:30px 16px}
.logo{border:3px solid #f6c453;color:#f6c453;border-radius:50%;width:75px;height:75px;display:grid;place-items:center;font-size:26px;font-weight:bold;margin:auto}
h1{color:#f6c453;margin:12px 0 4px}
header p{margin:8px 0 20px}
.btn{display:inline-block;text-align:center;padding:12px 17px;border-radius:9px;font-weight:bold;text-decoration:none;margin:4px}
.call{background:#f6c453;color:#10203c}
.wa{background:#19a95b;color:white}
main{max-width:850px;margin:auto;padding:15px}
section{background:white;padding:20px;margin:15px 0;border-radius:14px;box-shadow:0 3px 14px #0000000d}
h2{color:#10264a;margin-top:0}
.services{display:grid;grid-template-columns:1fr;gap:12px}
.service{background:#f8faff;border:1px solid #e1e7f0;border-radius:10px;padding:14px}
.service h3{margin:0 0 5px;color:#16365f}
label{display:block;font-weight:bold;margin-top:12px}
input,select,textarea{width:100%;padding:12px;border:1px solid #ccd4e0;border-radius:8px;font:inherit;margin-top:5px}
textarea{min-height:80px}
button{border:0;cursor:pointer;font:inherit}
.submit{width:100%;margin:15px 0 0}
.contact{background:#10203c;color:white;text-align:center}
.contact h2{color:#f6c453}
.number{font-size:25px;font-weight:bold}
.small{font-size:13px;color:#667085}
footer{text-align:center;padding:25px 12px 85px;color:#667085;font-size:13px}
.sticky{position:fixed;bottom:0;left:0;right:0;background:white;padding:8px;display:flex;justify-content:center;box-shadow:0 -2px 12px #0002}
.sticky a{flex:1;max-width:250px}
@media(min-width:600px){.services{grid-template-columns:1fr 1fr}}
</style>
</head>
<body>

<header>
  <div class="logo">SD</div>
  <h1>SAFE DRIVE BHIWADI</h1>
  <p>आपकी गाड़ी, हमारी ड्राइविंग सेवा।<br>
  आपका सफर, हमारी जिम्मेदारी!</p>
  <a class="btn call" href="tel:+918685842774">📞 अभी कॉल करें</a>
  <a class="btn wa" target="_blank" rel="noopener"
     href="https://wa.me/918685842774?text=Namaste%2C%20mujhe%20driver%20book%20karna%20hai">
     WhatsApp बुकिंग
  </a>
</header>

<main>
<section>
  <h2>हमारी सेवाएँ</h2>
  <div class="services">
    <div class="service">
      <h3>🚘 1. लोकल ड्राइवर</h3>
      <p>भिवाड़ी और आसपास आपकी अपनी कार के लिए ड्राइवर।</p>
    </div>
    <div class="service">
      <h3>🛣️ 2. आउटस्टेशन यात्रा</h3>
      <p>दूसरे शहरों की यात्रा के लिए ड्राइवर बुकिंग।</p>
    </div>
    <div class="service">
      <h3>🕒 3. घंटे या दिन के हिसाब से</h3>
      <p>अपनी जरूरत के अनुसार समय और किराया पूछें।</p>
    </div>
    <div class="service">
      <h3>☎️ 4. इमरजेंसी ड्राइवर</h3>
      <p>ड्राइवर की उपलब्धता के अनुसार आपातकालीन बुकिंग।</p>
    </div>
  </div>
</section>

<section>
  <h2>ड्राइवर बुकिंग करें</h2>
  <p>जानकारी भरें और WhatsApp पर बुकिंग का संदेश भेजें।</p>

  <form id="bookingForm">
    <label for="name">आपका नाम *</label>
    <input id="name" required placeholder="अपना नाम लिखें">

    <label for="service">कौन-सी सेवा चाहिए? *</label>
    <select id="service" required>
      <option value="">सेवा चुनें</option>
      <option>लोकल ड्राइवर</option>
      <option>आउटस्टेशन यात्रा</option>
      <option>घंटे के हिसाब से</option>
      <option>दिन के हिसाब से</option>
      <option>इमरजेंसी ड्राइवर</option>
    </select>

    <label for="date">तारीख और समय</label>
    <input id="date" placeholder="जैसे: 15 अक्टूबर, सुबह 9 बजे">

    <label for="pickup">पिकअप स्थान *</label>
    <input id="pickup" required placeholder="कहाँ से ड्राइवर चाहिए?">

    <label for="destination">जाने का स्थान</label>
    <input id="destination" placeholder="कहाँ जाना है?">

    <label for="details">अन्य जानकारी</label>
    <textarea id="details" placeholder="समय, वापसी या अन्य जानकारी"></textarea>

    <button class="btn wa submit" type="submit">
      WhatsApp पर बुकिंग भेजें
    </button>
  </form>
  <p class="small">बुकिंग तभी पक्की होगी जब फोन या WhatsApp पर पुष्टि मिल जाए।</p>
</section>

<section>
  <h2>बुकिंग कैसे करें?</h2>
  <ol>
    <li>कॉल करें या बुकिंग फ़ॉर्म भरें।</li>
    <li>तारीख, समय और यात्रा का स्थान बताएं।</li>
    <li>किराया और ड्राइवर की उपलब्धता पूछें।</li>
    <li>पुष्टि मिलने के बाद यात्रा तय करें।</li>
  </ol>
</section>

<section class="contact">
  <h2>आज ही संपर्क करें</h2>
  <p>Safe Drive Bhiwadi — आपके सफर का साथी</p>
  <div class="number">8685842774</div>
  <a class="btn call" href="tel:+918685842774">📞 कॉल करें</a>
  <a class="btn wa" target="_blank" rel="noopener"
     href="https://wa.me/918685842774?text=Namaste%2C%20mujhe%20driver%20book%20karna%20hai">
     WhatsApp करें
  </a>
  <p class="small" style="color:#e0e7f0">किराया और उपलब्धता पहले कन्फर्म करें।</p>
</section>
</main>

<footer>
  © <span id="year"></span> Safe Drive Bhiwadi<br>
  आपकी यात्रा के लिए ड्राइवर बुकिंग सेवा
</footer>

<div class="sticky">
  <a class="btn call" href="tel:+918685842774">📞 कॉल करें</a>
  <a class="btn wa" target="_blank" rel="noopener"
     href="https://wa.me/918685842774?text=Namaste%2C%20mujhe%20driver%20book%20karna%20hai">
     WhatsApp बुकिंग
  </a>
</div>

<script>
document.getElementById("year").textContent = new Date().getFullYear();

document.getElementById("bookingForm").addEventListener("submit", function(e){
  e.preventDefault();

  const get = id => document.getElementById(id).value.trim();
  const message =
    "नमस्ते Safe Drive Bhiwadi, मुझे ड्राइवर बुक करना है।\n" +
    "नाम: " + get("name") + "\n" +
    "सेवा: " + get("service") + "\n" +
    "तारीख/समय: " + (get("date") || "अभी तय नहीं") + "\n" +
    "पिकअप: " + get("pickup") + "\n" +
    "गंतव्य: " + (get("destination") || "अभी तय नहीं") + "\n" +
    "अन्य जानकारी: " + (get("details") || "कोई नहीं");

  window.location.href =
    "https://wa.me/918685842774?text=" + encodeURIComponent(message);
});
</script>

</body>
</html>

