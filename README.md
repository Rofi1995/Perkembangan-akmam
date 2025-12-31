<!DOCTYPE html>
<html lang="id">
<head>
<meta charset="UTF-8">
<title>Laporan Perkembangan Karakter Santri</title>

<!-- BLOK TOTAL MESIN PENCARI -->
<meta name="robots" content="noindex, nofollow">
<meta name="googlebot" content="noindex, nofollow">
<meta name="bingbot" content="noindex, nofollow">

<meta name="viewport" content="width=device-width, initial-scale=1.0">

<style>
:root{
  --bg:#f6f7fb;
  --card:#ffffff;
  --primary:#5b7cfa;
  --secondary:#f1f4ff;
  --text:#2c2f38;
  --muted:#6b7280;
  --border:#e6e8f0;

  --A:#22c55e;
  --B:#3b82f6;
  --C:#f59e0b;
  --D:#ef4444;
}

@media (prefers-color-scheme: dark){
  :root{
    --bg:#0f1220;
    --card:#181b2e;
    --primary:#8aa2ff;
    --secondary:#1e2140;
    --text:#e5e7eb;
    --muted:#9ca3af;
    --border:#2b2f55;
  }
}

*{box-sizing:border-box}

body{
  margin:0;
  font-family: "Inter", "Segoe UI", system-ui, sans-serif;
  background:var(--bg);
  color:var(--text);
  line-height:1.65;
}

.wrapper{
  max-width:960px;
  margin:auto;
  padding:24px;
}

.header{
  background:linear-gradient(135deg,#5b7cfa,#7c9cff);
  color:white;
  padding:36px 28px;
  border-radius:20px;
  box-shadow:0 20px 40px rgba(0,0,0,.15);
}

.header h1{
  margin:0;
  font-size:1.8rem;
  font-weight:700;
}

.header p{
  margin-top:6px;
  opacity:.9;
}

.info{
  margin-top:24px;
  display:grid;
  grid-template-columns:repeat(auto-fit,minmax(220px,1fr));
  gap:14px;
}

.info div{
  background:var(--card);
  border:1px solid var(--border);
  border-radius:14px;
  padding:14px 16px;
  box-shadow:0 6px 16px rgba(0,0,0,.05);
}

.section{
  margin-top:40px;
}

.section h2{
  font-size:1.4rem;
  margin-bottom:18px;
  color:var(--primary);
}

.summary{
  display:grid;
  grid-template-columns:repeat(auto-fit,minmax(120px,1fr));
  gap:12px;
}

.summary div{
  background:var(--secondary);
  padding:14px;
  border-radius:14px;
  text-align:center;
  font-weight:600;
}

.card{
  background:var(--card);
  border:1px solid var(--border);
  border-radius:18px;
  padding:20px;
  margin-bottom:16px;
  box-shadow:0 10px 24px rgba(0,0,0,.06);
  transition:.25s ease;
}

.card:hover{
  transform:translateY(-3px);
}

.card-header{
  display:flex;
  justify-content:space-between;
  align-items:center;
  margin-bottom:12px;
}

.card-header h3{
  margin:0;
  font-size:1.1rem;
}

.badge{
  padding:6px 14px;
  border-radius:999px;
  color:white;
  font-weight:700;
}

.A{background:var(--A)}
.B{background:var(--B)}
.C{background:var(--C)}
.D{background:var(--D)}

.desc{
  background:var(--secondary);
  padding:12px 14px;
  border-radius:12px;
  margin-top:8px;
}

.note{
  background:linear-gradient(135deg,#fff7ed,#ffedd5);
  border-left:6px solid #fb923c;
  padding:18px;
  border-radius:16px;
}

.footer{
  margin-top:50px;
  display:grid;
  grid-template-columns:1fr 1fr;
  gap:40px;
  font-size:.95rem;
}

.sign{
  text-align:center;
}

@media(max-width:700px){
  .footer{grid-template-columns:1fr}
}

@media print{
  body{background:white}
  .header{box-shadow:none}
  .card{page-break-inside:avoid}
}
</style>
</head>

<body>
<div class="wrapper">

  <div class="header">
    <h1>Laporan Perkembangan Karakter Santri</h1>
    <p>Tahun Ajaran 2025–2026</p>
  </div>

  <div class="info">
    <div><strong>Nama Santri</strong><br>Muadz</div>
    <div><strong>Kelas</strong><br>1 (Mutawashitoh)</div>
    <div><strong>Asrama</strong><br>Aqsha</div>
    <div><strong>Semester</strong><br>I (Gasal)</div>
  </div>

  <div class="section">
    <h2>Ringkasan Umum</h2>
    <div class="summary">
      <div>🌱 Banyak potensi positif</div>
      <div>📌 Perlu penguatan disiplin</div>
      <div>🤝 Sosial & kepedulian baik</div>
      <div>📖 Ibadah & hafalan stabil</div>
    </div>
  </div>

  <div class="section">
    <h2>Penilaian Karakter</h2>

    <div class="card">
      <div class="card-header">
        <h3>1. Jujur</h3>
        <div class="badge C">C</div>
      </div>
      <div class="desc">Biasanya jujur dalam berkata, namun terkadang masih menutupi sebagian informasi.</div>
      <div class="desc">Jujur dalam mengerjakan tugas dan jarang mengambil yang bukan haknya.</div>
    </div>

    <div class="card">
      <div class="card-header">
        <h3>2. Disiplin</h3>
        <div class="badge D">D</div>
      </div>
      <div class="desc">Memahami peraturan pondok, namun saat bosan atau kecewa terkadang melanggar.</div>
    </div>

    <div class="card">
      <div class="card-header">
        <h3>4. Bersemangat</h3>
        <div class="badge A">A</div>
      </div>
      <div class="desc">Selalu antusias dalam beladiri dan kegiatan ekstrakurikuler.</div>
    </div>

    <!-- pola card sama untuk karakter lainnya -->

  </div>

  <div class="section">
    <h2>Catatan Pembimbing</h2>
    <div class="note">
      Ananda perlu lebih disiplin dan bertanggung jawab dalam segala hal, dengan pendampingan dan pembiasaan yang konsisten.
    </div>
  </div>

  <div class="footer">
    <div class="sign">
      Brebes, 17 Desember 2025<br><br>
      <strong>Mengetahui</strong><br>
      M. Sholahudin Rofi, Lc
    </div>
    <div class="sign">
      <br><br>
      <strong>Musyrif Kepengasuhan</strong><br>
      Mujahid Bamiftah
    </div>
  </div>

</div>
</body>
</html>