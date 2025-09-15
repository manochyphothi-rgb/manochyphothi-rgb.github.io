# manochyphothi-rgb.github.io
<!doctype html>
<html lang="th">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>โครงงาน Gift Shop</title>
  <style>
    :root{
      --bg:#fff7fb;
      --card:#fff;
      --accent:#ffd6e8;
      --muted:#6b6b6b;
      --primary:#ff7ab6;
      --shadow: 0 6px 18px rgba(16,16,24,0.08);
      --radius:16px;
    }
    *{box-sizing:border-box}
    body{
      margin:0;
      font-family: "Noto Sans Thai", "Segoe UI", Roboto, Arial, sans-serif;
      background: linear-gradient(180deg,var(--bg), #fff);
      color:#222;
      -webkit-font-smoothing:antialiased;
    }
    .container{
      max-width:900px;
      margin:28px auto;
      padding:24px;
    }
    header{
      display:flex;
      gap:16px;
      align-items:center;
      margin-bottom:18px;
    }
    .logo{
      width:86px;
      height:86px;
      border-radius:16px;
      background:linear-gradient(135deg,#fff,#ffeaf3);
      box-shadow:var(--shadow);
      display:flex;
      align-items:center;
      justify-content:center;
      font-size:34px;
    }
    h1{
      margin:0;
      font-size:22px;
      line-height:1.1;
    }
    .sub{
      color:var(--muted);
      font-size:14px;
      margin-top:6px;
    }

    .card{
      background:var(--card);
      border-radius:var(--radius);
      padding:18px;
      box-shadow:var(--shadow);
      margin-bottom:16px;
    }
    .grid{
      display:grid;
      grid-template-columns:1fr 300px;
      gap:16px;
    }
    @media (max-width:880px){
      .grid{grid-template-columns:1fr}
    }
    .badge{
      display:inline-block;
      background:var(--accent);
      padding:6px 10px;
      border-radius:999px;
      font-weight:700;
      color: #7a1946;
      font-size:13px;
    }
    ul{padding-left:18px; margin:6px 0 12px}
    li{margin-bottom:8px}
    .price{
      font-weight:800;
      color:var(--primary);
      font-size:20px;
    }
    .promo{
      background:linear-gradient(90deg,#fff7fb,#fff0f8);
      padding:12px;
      border-radius:12px;
      border:1px dashed #ffd0e6;
    }
    .sticker{
      font-size:48px;
      display:inline-block;
      transform:rotate(-8deg);
      margin-right:8px;
    }
    footer{
      margin-top:16px;
      color:var(--muted);
      font-size:13px;
      text-align:center;
    }
    .list-number{
      display:flex;
      gap:10px;
      align-items:flex-start;
      margin-bottom:8px;
    }
    .num{
      width:34px;height:34px;border-radius:8px;background:#fff0f7;color:#8a2351;display:flex;align-items:center;justify-content:center;font-weight:700;box-shadow:0 4px 8px rgba(250,180,220,0.18)
    }
  </style>
</head>
<body>
  <div class="container">
    <header>
      <div class="logo" aria-hidden="true">🎁</div>
      <div>
        <h1>โครงงาน Gift Shop ของเรา ✨</h1>
        <div class="sub">สวัสดีค่ะ/ครับ — โครงงานวิชาการงานอาชีพ โดยคุณครูประจำชั้น: พัทยา จันทะมาตร์</div>
      </div>
    </header>

    <div class="card">
      <div style="display:flex;justify-content:space-between;align-items:center;">
        <div>
          <div style="font-weight:700">สมาชิกในกลุ่ม</div>
          <div class="sub">ด.ญ. เกศรา ทิพดง • ด.ญ. ชญาพร คำพระโว • ด.ญ. ปุญญิสา ชาหมู่</div>
        </div>
        <div class="badge">โครงงานโรงเรียน</div>
      </div>
    </div>

    <div class="grid">
      <div>
        <section class="card">
          <div style="display:flex;align-items:center;gap:12px;margin-bottom:10px">
            <div class="sticker">🌸</div>
            <div>
              <strong>ทำไมต้อง Gift Shop?</strong>
              <div class="sub">ความเป็นมาและวัตถุประสงค์</div>
            </div>
          </div>

          <ul>
            <li>ฝึกทักษะการขาย — เรียนรู้การสื่อสารและนำเสนอ</li>
            <li>ทำงานร่วมกัน — แบ่งหน้าที่และบริหารจัดการ</li>
            <li>คำนวณต้นทุน-กำไร — ฝึกคิดเลขและการเงินเบื้องต้น</li>
            <li>สร้างรายได้เสริม — นำกำไรไปเป็นทุนกิจกรรมอื่น</li>
          </ul>

          <h3>สินค้าอะไรน่ารักน่าช้อป? 🛍️</h3>
          <ul>
            <li>กิ๊บติดผมสีพาสเทล</li>
            <li>พวงกุญแจสัตว์น้อยน่ารัก</li>
            <li>สมุดโน้ตจิ๋วพร้อมปากกาสีสัน</li>
            <li>ยางลบรูปร่างแปลกใหม่</li>
            <li>สติ๊กเกอร์ไดคัทลายการ์ตูน</li>
          </ul>

          <div class="promo">
            <div style="display:flex;justify-content:space-between;align-items:center">
              <div>
                <div class="price">ราคาเริ่มต้น: 7 บาท/ชิ้น</div>
                <div class="sub">โปรโมชั่น: ซื้อ 3 ชิ้น จ่ายแค่ 20 บาท</div>
              </div>
              <div style="font-size:32px">💖</div>
            </div>
            <div class="sub" style="margin-top:8px">⚠️ สินค้ามีจำนวนจำกัด — ช้าหมดอดน่ารัก!</div>
          </div>
        </section>

        <section class="card" style="margin-top:12px">
          <h3>วิธีการขาย (หน้าร้าน)</h3>
          <ul>
            <li>ตั้งร้านค้าเล็ก ๆ ในโรงเรียน</li>
            <li>พูดเชิญชวน แนะนำสินค้าอย่างเป็นกันเอง</li>
            <li>บริการด้วยรอยยิ้ม และจัดโปรโมชั่นดึงดูด</li>
            <li>บริหารเงินสด: จัดการเงินทอนและบันทึกรายรับ-รายจ่าย</li>
          </ul>
        </section>

        <section class="card" style="margin-top:12px">
          <h3>ผลลัพธ์ที่คาดว่าจะได้รับ</h3>

          <div class="list-number">
            <div class="num">1</div>
            <div>
              <strong>ทักษะการทำงานจริง</strong><div class="sub">ได้ลงมือปฏิบัติจริงในทุกกระบวนการ</div>
            </div>
          </div>

          <div class="list-number">
            <div class="num">2</div>
            <div>
              <strong>กล้าแสดงออก</strong><div class="sub">มีความมั่นใจในการพูดคุยและนำเสนอ</div>
            </div>
          </div>

          <div class="list-number">
            <div class="num">3</div>
            <div>
              <strong>บริหารจัดการ</strong><div class="sub">เข้าใจการวางแผนและการควบคุมงาน</div>
            </div>
          </div>

          <div class="list-number">
            <div class="num">4</div>
            <div>
              <strong>หลักการขาย</strong><div class="sub">เรียนรู้จิตวิทยาในการขายและดึงดูดลูกค้า</div>
            </div>
          </div>

          <div class="list-number">
            <div class="num">5</div>
            <div>
              <strong>การตลาดเบื้องต้น</strong><div class="sub">รู้จักการทำโปรโมชั่นและสร้างจุดเด่นให้สินค้า</div>
            </div>
          </div>

        </section>
      </div>

      <aside>
        <div class="card">
          <h3 style="margin-top:0">สรุปบทเรียน ✨</h3>
          <p class="sub">โครงงาน “Gift Shop” ไม่ใช่เพียงการขายของ แต่เป็นสนามฝึกทักษะอาชีพจริง — การนำเสนอ การบริหารจัดการสินค้า การคำนวณต้นทุน-กำไร และการทำงานเป็นทีม เป็นประสบการณ์ที่มีค่ากว่าสิ่งที่ได้จากตำราเรียนเพียงอย่างเดียว</p>
        </div>

        <div class="card" style="margin-top:12px;text-align:center">
          <div style="font-size:40px">🎀</div>
          <div style="font-weight:700;margin-top:8px">ขอบคุณทุกท่านที่รับฟัง!</div>
          <div class="sub" style="margin-top:6px">พวกเราหวังว่าจะเป็นแรงบันดาลใจให้เพื่อน ๆ กล้าที่จะลงมือทำ</div>
        </div>
      </aside>
    </div>

    <footer>
      <div>Made with 💖 — ตกแต่งโครงงานโดยทีม Gift Shop</div>
    </footer>
  </div>
</body>
</html>
