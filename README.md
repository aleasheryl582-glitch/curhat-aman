# curhat-aman
website edukasi stress belajar remaja
<!DOCTYPE html>
<html lang="id">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<meta name="theme-color" content="#174477">
<title>Curhat Aman</title>
<style>
:root{--navy:#174477;--blue:#3976b9;--sky:#e4f1ff;--pale:#f5f9ff;--ink:#243449;--muted:#617187;--line:#dbe6f2;--green:#e8f7f0}
*{box-sizing:border-box}html{scroll-behavior:smooth;scroll-padding-top:80px}body{margin:0;font:16px/1.65 system-ui,-apple-system,"Segoe UI",sans-serif;color:var(--ink);background:#fff}a{color:var(--blue)}button,input,select{font:inherit}.wrap{width:min(1050px,92%);margin:auto}.header{position:sticky;top:0;background:#ffffffef;backdrop-filter:blur(10px);border-bottom:1px solid var(--line);z-index:5}.nav{display:flex;align-items:center;justify-content:space-between;gap:16px;min-height:68px}.brand{display:flex;align-items:center;gap:10px;color:var(--navy);text-decoration:none;font-weight:850}.logo{background:var(--navy);color:white;border-radius:13px;padding:7px 11px;font-size:23px}.links{display:flex;gap:18px;flex-wrap:wrap}.links a{text-decoration:none;color:var(--muted);font-size:.92rem;font-weight:650}.menu{display:none}.hero{padding:64px 0;background:radial-gradient(circle at 85% 15%,#c5e2ff,transparent 32%),linear-gradient(130deg,#edf6ff,#fbfdff)}.hero-grid{display:grid;grid-template-columns:1.15fr .85fr;gap:30px;align-items:center}.eyebrow,.pill{display:inline-block;border-radius:999px;background:white;border:1px solid var(--line);padding:5px 11px;color:var(--navy);font-size:.85rem;font-weight:750}.hero h1{font-size:clamp(2.3rem,5vw,4.2rem);line-height:1.08;letter-spacing:-.04em;color:var(--navy);margin:18px 0}.hero p{color:#50647b;font-size:1.08rem}.panel,.card{background:white;border:1px solid var(--line);border-radius:20px;padding:22px;box-shadow:0 8px 28px #1744770d}.bubble{padding:13px 15px;background:var(--pale);border-radius:14px;margin:12px 0}.bubble.reply{background:var(--green);margin-left:18px}.buttons{display:flex;gap:10px;flex-wrap:wrap;margin-top:20px}.btn{display:inline-flex;justify-content:center;align-items:center;border:0;border-radius:12px;padding:11px 17px;font-weight:800;text-decoration:none;cursor:pointer}.primary{background:var(--navy);color:#fff}.secondary{background:#fff;border:1px solid var(--line);color:var(--navy)}.section{padding:60px 0}.alt{background:var(--pale)}.heading{max-width:700px;margin-bottom:25px}.heading h2{font-size:clamp(1.8rem,3.5vw,2.6rem);line-height:1.15;color:var(--navy);margin:0 0 10px}.muted{color:var(--muted)}.grid{display:grid;grid-template-columns:repeat(3,1fr);gap:16px}.grid.two{grid-template-columns:repeat(2,1fr)}.card h3{color:var(--navy);margin:8px 0}.emoji{font-size:1.6rem;background:var(--sky);width:48px;height:48px;display:grid;place-items:center;border-radius:14px}.note{padding:15px;border-radius:14px;background:#fff7df;border:1px solid #f1dfaa;color:#644d17;margin-top:18px}.safe{padding:14px;border-radius:14px;background:var(--green);border:1px solid #c8eadb;color:#275c4b}.question{padding:17px;border:1px solid var(--line);border-radius:15px;margin:13px 0;background:#fff}.question fieldset{border:0;padding:0;margin:0}.question legend{font-weight:800;color:var(--navy);margin-bottom:8px}.choice{display:flex;gap:10px;align-items:flex-start;padding:6px 0;cursor:pointer}.choice input{margin-top:7px;accent-color:var(--blue)}.field{width:100%;padding:11px 12px;border:1px solid #cbd9e9;border-radius:11px;background:white;margin-top:8px}.result{display:block;margin-top:20px}.progress{height:9px;background:#e5edf6;border-radius:10px;overflow:hidden}.progress span{display:block;height:100%;background:var(--blue)}.clean li{margin:7px 0}.footer{background:#123253;color:#edf5ff;padding:32px 0}.footer a{color:#cce5ff}.small{font-size:.88rem}.resource{display:flex;justify-content:space-between;align-items:center;gap:16px;flex-wrap:wrap}
@media(max-width:760px){.hero-grid,.grid,.grid.two{grid-template-columns:1fr}.hero{padding:42px 0}.section{padding:44px 0}.nav{padding:10px 0}.menu{display:block;border:1px solid var(--line);background:white;border-radius:10px;padding:8px 11px}.links{display:none;position:absolute;top:67px;left:0;right:0;padding:16px 4%;background:white;border-bottom:1px solid var(--line);flex-direction:column}.links.open{display:flex}.hero h1{font-size:2.5rem}}
@media print{.header,.buttons,button{display:none!important}.section,.hero{padding:20px 0}.card,.panel{box-shadow:none}}
</style>
</head>
<body>
<header class="header"><div class="wrap nav">
<a class="brand" href="#beranda"><span class="logo">💙</span><span>Curhat Aman<small style="display:block;color:var(--muted);font-size:.72rem">Kenali tekananmu, temukan dukunganmu</small></span></a>
<button class="menu" id="menuBtn" type="button">☰ Menu</button>
<nav class="links" id="links"><a href="#tentang">Tentang</a><a href="#refleksi">Refleksi</a><a href="#tips">Tips</a><a href="#bantuan">Cari bantuan</a><a href="#privasi">Privasi & etika</a></nav>
</div></header>
<main>
<section class="hero" id="beranda"><div class="wrap hero-grid"><div>
<span class="eyebrow">🌱 Edukasi kesehatan mental remaja</span>
<h1>Kamu nggak harus menghadapi tekanan belajar sendirian.</h1>
<p>Ruang refleksi sederhana untuk mengenali tekanan belajar, mencoba strategi sehat, dan menemukan dukungan yang tepat.</p>
<div class="buttons"><a class="btn primary" href="#refleksi">Mulai refleksi →</a><a class="btn secondary" href="#bantuan">Lihat pilihan bantuan</a></div>
<p class="small">Bukan alat diagnosis. Jawaban refleksi diproses di perangkatmu dan tidak dikirim ke server oleh website ini.</p>
</div><div class="panel"><div style="font-size:2rem">☁️ 💬</div><h3 style="color:var(--navy)">Mulai dari satu langkah kecil</h3><div class="bubble">“Aku lagi kewalahan sama tugas dan ujian.”</div><div class="bubble reply">Perasaan itu layak didengarkan. Berhenti sebentar, cek kebutuhanmu, lalu pilih satu langkah yang realistis.</div><div class="safe small">Kamu tidak harus menyelesaikan semuanya sekaligus. Meminta bantuan juga sebuah langkah berani.</div></div></div></section>
<section class="section" id="tentang"><div class="wrap"><div class="heading"><h2>Apa itu Curhat Aman?</h2><p class="muted">Website edukasi yang membantu siswa kelas XII memahami tekanan belajar dengan cara sederhana, aman, dan tidak menghakimi.</p></div><div class="grid"><article class="card"><div class="emoji">🧭</div><h3>Kenali kondisi</h3><p class="muted">Perhatikan hal-hal yang belakangan terasa berat.</p></article><article class="card"><div class="emoji">🪴</div><h3>Pilih langkah kecil</h3><p class="muted">Coba membagi tugas, mengambil jeda, atau berbicara dengan orang tepercaya.</p></article><article class="card"><div class="emoji">🤝</div><h3>Temukan dukungan</h3><p class="muted">Guru BK, keluarga, dan tenaga profesional tetap berperan penting.</p></article></div><div class="note"><strong>Catatan:</strong> Curhat Aman bukan psikolog, bukan layanan darurat, dan tidak mendiagnosis kondisi kesehatan mental. Saran yang diberikan bersifat umum.</div></div></section>
<section class="section alt" id="refleksi"><div class="wrap"><div class="heading"><h2>Refleksi tekanan belajar</h2><p class="muted">Jawab sesuai keadaanmu belakangan ini. Tidak ada jawaban benar atau salah. Kamu boleh berhenti kapan saja.</p></div><div class="panel">
<div class="safe small"><strong>Privasi:</strong> jawaban diproses di browser untuk menampilkan saran umum. Website demo ini tidak mengirim atau menyimpan jawabanmu.</div>
<form id="reflectionForm">
<div class="question"><fieldset><legend>1. Dalam 7 hari terakhir, seberapa sering tugas atau ujian terasa membebani?</legend><label class="choice"><input type="radio" name="q1" value="0" required> Jarang atau tidak pernah</label><label class="choice"><input type="radio" name="q1" value="1"> Kadang-kadang</label><label class="choice"><input type="radio" name="q1" value="2"> Sering</label><label class="choice"><input type="radio" name="q1" value="3"> Hampir setiap hari</label></fieldset></div>
<div class="question"><fieldset><legend>2. Seberapa sulit kamu mulai atau menyelesaikan tugas?</legend><label class="choice"><input type="radio" name="q2" value="0" required> Tidak terlalu sulit</label><label class="choice"><input type="radio" name="q2" value="1"> Sedikit sulit</label><label class="choice"><input type="radio" name="q2" value="2"> Cukup sulit</label><label class="choice"><input type="radio" name="q2" value="3"> Sangat sulit</label></fieldset></div>
<div class="question"><fieldset><legend>3. Apakah tekanan belajar memengaruhi waktu istirahatmu?</legend><label class="choice"><input type="radio" name="q3" value="0" required> Tidak</label><label class="choice"><input type="radio" name="q3" value="1"> Sedikit</label><label class="choice"><input type="radio" name="q3" value="2"> Cukup terasa</label><label class="choice"><input type="radio" name="q3" value="3"> Sangat terasa</label></fieldset></div>
<div class="question"><fieldset><legend>4. Seberapa sering kamu khawatir tentang hasil ujian atau masa depan?</legend><label class="choice"><input type="radio" name="q4" value="0" required> Jarang atau tidak pernah</label><label class="choice"><input type="radio" name="q4" value="1"> Kadang-kadang</label><label class="choice"><input type="radio" name="q4" value="2"> Sering</label><label class="choice"><input type="radio" name="q4" value="3"> Hampir setiap hari</label></fieldset></div>
<div class="question"><fieldset><legend>5. Apakah kamu punya orang yang cukup aman untuk diajak bicara?</legend><label class="choice"><input type="radio" name="q5" value="0" required> Ya, ada dan mudah dihubungi</label><label class="choice"><input type="radio" name="q5" value="1"> Ada, tetapi sulit memulai cerita</label><label class="choice"><input type="radio" name="q5" value="2"> Belum yakin</label><label class="choice"><input type="radio" name="q5" value="3"> Saat ini belum ada</label></fieldset></div>
<div class="question"><label for="support"><strong>6. Dukungan apa yang paling kamu butuhkan? (opsional)</strong></label><select id="support" class="field"><option value="tasks">Mengatur waktu dan tugas</option><option value="exam">Menghadapi kekhawatiran ujian</option><option value="story">Mulai bercerita kepada orang tepercaya</option><option value="rest">Menjaga istirahat dan energi</option></select></div>
<div class="buttons"><button class="btn primary" type="submit">Lihat saran untukku</button><button class="btn secondary" type="reset" id="resetBtn">Ulangi</button></div>
</form><div class="result" id="result" aria-live="polite"><div class="card" style="background:#f7fbff"><span class="pill">Saran awal</span><h3 style="margin-top:14px">Mulai dari satu langkah kecil</h3><p>Setelah menjawab refleksi dan menekan tombol “Lihat saran untukku”, saran akan disesuaikan dengan jawabanmu jika JavaScript aktif. Untuk sekarang, pilih satu tugas kecil, ambil jeda, atau bicaralah dengan orang tepercaya jika kamu merasa kewalahan.</p><p class="small">Saran ini bersifat umum dan bukan diagnosis.</p></div></div>
</div></div></section>
<section class="section" id="tips"><div class="wrap"><div class="heading"><h2>Langkah kecil yang bisa dicoba</h2><p class="muted">Pilih satu saja dulu. Tidak perlu melakukan semuanya sekaligus.</p></div><div class="grid two">
<article class="card"><div class="emoji">🗂️</div><h3>Kalau tugas menumpuk</h3><ul class="clean"><li>Tulis tugas dan tenggatnya.</li><li>Pilih satu yang paling dekat tenggatnya.</li><li>Kerjakan 15–25 menit, lalu jeda.</li><li>Minta bantuan menyusun prioritas jika masih berat.</li></ul></article>
<article class="card"><div class="emoji">🌬️</div><h3>Kalau cemas menjelang ujian</h3><ul class="clean"><li>Tarik napas perlahan tanpa memaksakan diri.</li><li>Fokus pada satu topik yang bisa dipelajari sekarang.</li><li>Latihan soal sedikit demi sedikit.</li><li>Nilai penting, tetapi tidak menentukan seluruh nilai dirimu.</li></ul></article>
<article class="card"><div class="emoji">🌙</div><h3>Kalau istirahat berantakan</h3><ul class="clean"><li>Jaga waktu tidur dan jeda.</li><li>Minum air dan makan teratur.</li><li>Jauhkan tugas saat waktu istirahat.</li><li>Cari dukungan jika kesulitan terus mengganggu keseharian.</li></ul></article>

</div></div></section>
<section class="section alt" id="bantuan"><div class="wrap"><div class="heading"><h2>Kamu boleh meminta bantuan</h2><p class="muted">Berbicara dengan orang lain bukan tanda lemah. Pilih orang yang kamu rasa aman dan bisa dipercaya.</p></div><div class="grid two">
<article class="card"><div class="emoji">🏫</div><h3>Di sekolah</h3><ul class="clean"><li>Guru BK atau konselor sekolah.</li><li>Wali kelas atau guru yang kamu percaya.</li><li>Teman suportif; libatkan orang dewasa jika masalah terasa berat.</li></ul></article>
<article class="card"><div class="emoji">🏡</div><h3>Di rumah atau lingkungan</h3><ul class="clean"><li>Orang tua atau wali yang membuatmu merasa aman.</li><li>Kakak, saudara, atau orang dewasa tepercaya.</li><li>Tenaga kesehatan atau psikolog jika tekanan terus mengganggu keseharian.</li></ul></article>
</div><div class="note"><strong>Jika kamu merasa tidak aman atau menghadapi keadaan darurat:</strong> segera datangi orang dewasa tepercaya di dekatmu dan minta bantuan langsung. Jangan mengandalkan website ini untuk keadaan darurat.</div><div class="card resource" style="margin-top:18px"><div><h3>Informasi layanan dukungan</h3><p class="muted" style="margin-bottom:0">Periksa informasi terbaru dan cara akses di kanal resminya.</p></div><a href="https://www.healing119.id/" target="_blank" rel="noopener noreferrer">Kunjungi Healing119.id ↗</a></div></div></section>
<section class="section" id="privasi"><div class="wrap"><div class="heading"><h2>Privasi, etika, dan peran AI</h2><p class="muted">Teknologi dapat membantu edukasi, tetapi manusia tetap memegang peran utama dalam dukungan dan keputusan.</p></div><div class="grid two">
<article class="card"><div class="emoji">🔒</div><h3>Prinsip privasi</h3><ul class="clean"><li>Jangan masukkan nama lengkap, alamat, atau nomor telepon dalam refleksi.</li><li>Refleksi pada demo ini diproses lokal di browser.</li><li>Jangan unggah jawaban pribadi ke AI tanpa menghapus identitas dan memperoleh izin yang sesuai.</li><li>Survei sekolah perlu menjelaskan tujuan, sifat sukarela, akses data, dan waktu penghapusan.</li></ul></article>
<article class="card"><div class="emoji">🧠</div><h3>Batasan AI</h3><ul class="clean"><li>AI dapat membantu merangkum tema umum dari data anonim.</li><li>AI bisa salah memahami konteks.</li><li>AI tidak boleh memberi diagnosis atau menggantikan guru BK/tenaga profesional.</li><li>Hasil analisis harus ditinjau manusia sebelum digunakan.</li></ul></article>
</div></div></section>
</main>
<footer class="footer"><div class="wrap"><h2 style="margin-top:0">Curhat Aman 💙</h2><p>Kenali tekananmu, temukan dukunganmu. Kamu berharga, bahkan ketika hari ini terasa berat.</p><p class="small">Prototipe edukasi — bukan alat diagnosis atau layanan darurat.</p><p class="small">© <span id="year"></span> Curhat Aman</p></div></footer>
<script>
const nav=document.getElementById('links');
document.getElementById('menuBtn').addEventListener('click',()=>nav.classList.toggle('open'));
nav.querySelectorAll('a').forEach(a=>a.addEventListener('click',()=>nav.classList.remove('open')));
document.getElementById('year').textContent=new Date().getFullYear();
const advice={
 tasks:{title:'Mulai dari satu tugas kecil',text:'Tuliskan tugas yang ada, tandai tenggat terdekat, lalu pilih satu langkah yang bisa dikerjakan selama 15–25 menit. Jika masih kewalahan, minta bantuan guru atau teman untuk menyusun prioritas.'},
 exam:{title:'Belajar sedikit demi sedikit',text:'Pilih satu materi, kerjakan beberapa soal, lalu periksa kesalahan. Sisipkan jeda dan waktu istirahat. Jika kekhawatiran terus mengganggu keseharian, bicaralah dengan guru BK atau orang dewasa tepercaya.'},
 story:{title:'Mulai cerita kepada orang yang aman',text:'Kamu bisa berkata: “Aku sedang kewalahan dan ingin didengarkan. Bisa temani aku ngobrol sebentar?” Pilih guru BK, orang tua/wali, atau orang dewasa yang kamu percaya.'},
 rest:{title:'Jaga kebutuhan dasar',text:'Coba rutinitas tidur, makan, minum, dan jeda yang teratur. Pilih satu kebiasaan kecil untuk hari ini. Jika kesulitan beristirahat atau beraktivitas terus berlanjut, cari dukungan orang dewasa tepercaya.'}
};
const form=document.getElementById('reflectionForm'), result=document.getElementById('result');
form.addEventListener('submit',function(e){
 e.preventDefault();
 const data=new FormData(form);
 let score=0;
 for(let i=1;i<=5;i++){const value=data.get('q'+i);if(value===null){alert('Tolong jawab semua pertanyaan wajib terlebih dahulu.');return;}score+=Number(value);}
 let title,level,body;
 if(score<=4){title='Pertahankan kebiasaan yang mendukungmu';level='Jawabanmu menunjukkan tekanan yang relatif rendah pada pertanyaan ini.';body='Tetap perhatikan kebutuhan istirahat, waktu belajar, dan hubungan dengan orang yang kamu percaya.';}
 else if(score<=8){title='Coba satu langkah kecil hari ini';level='Ada beberapa hal yang terasa membebani menurut jawabanmu.';body='Pilih satu hal yang bisa kamu atur dan ceritakan kepada seseorang jika kamu membutuhkannya.';}
 else{title='Kamu layak mendapat dukungan';level='Kamu melaporkan beberapa tekanan yang cukup terasa.';body='Pertimbangkan untuk bicara dengan guru BK atau orang dewasa tepercaya, terutama jika tekanan mengganggu tidur, belajar, atau aktivitas harian.';}
 const selected=advice[document.getElementById('support').value];
 result.innerHTML='<div class="card" style="background:#f7fbff"><span class="pill">Refleksi pribadi — bukan diagnosis</span><h3 style="margin-top:14px">'+title+'</h3><p><strong>'+level+'</strong></p><p>'+body+'</p><div class="progress"><span style="width:'+Math.round(score/15*100)+'%"></span></div><h3>'+selected.title+'</h3><p>'+selected.text+'</p><div class="note"><strong>Ingat:</strong> skor ini bukan ukuran kesehatan mental dan tidak dapat memastikan keadaanmu. Kamu boleh meminta bantuan kapan saja, tidak perlu menunggu hasil refleksi.</div><p><a href="#bantuan">Lihat pilihan bantuan →</a></p></div>';
 result.classList.add('show');
 result.scrollIntoView({behavior:'smooth',block:'start'});
});
form.addEventListener('reset',()=>{result.innerHTML='<div class="card" style="background:#f7fbff"><span class="pill">Saran awal</span><h3 style="margin-top:14px">Mulai dari satu langkah kecil</h3><p>Setelah menjawab refleksi dan menekan tombol “Lihat saran untukku”, saran akan disesuaikan dengan jawabanmu jika JavaScript aktif. Untuk sekarang, pilih satu tugas kecil, ambil jeda, atau bicaralah dengan orang tepercaya jika kamu merasa kewalahan.</p><p class="small">Saran ini bersifat umum dan bukan diagnosis.</p></div>';});
document.getElementById('copyScript').addEventListener('click',async()=>{
 const text='Aku akhir-akhir ini merasa kewalahan dengan sekolah. Aku ingin didengarkan. Bisa temani aku ngobrol sebentar?';
 const button=document.getElementById('copyScript');
 try {
   if(navigator.clipboard && window.isSecureContext){
     await navigator.clipboard.writeText(text);
     button.textContent='Tersalin ✓';
     return;
   }
 } catch(e) {}
 // Fallback for Android local content:// files where Clipboard API is blocked.
 const old=document.getElementById('copyFallback');
 if(old) old.remove();
 const box=document.createElement('div');
 box.id='copyFallback'; box.className='note'; box.setAttribute('role','status');
 box.innerHTML='<strong>Salin kalimat ini:</strong><p id="copyText" style="user-select:text;-webkit-user-select:text;margin-bottom:8px"></p><p class="small">Tekan dan tahan teks di atas, pilih “Salin”, lalu tempelkan ke chat yang kamu inginkan.</p>';
 box.querySelector('#copyText').textContent=text;
 button.insertAdjacentElement('afterend',box);
 box.scrollIntoView({behavior:'smooth',block:'center'});
});
</script>
</body>
</html>
