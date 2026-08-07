# GHS-KAVILUMPARA-
This is a website for school 
<!DOCTYPE html>
<html lang="ml">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>ജി.എച്ച്.എസ് കാവിലുംപാറ</title>

<style>
*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Segoe UI', Arial, sans-serif;
    scroll-behavior: smooth;
}

body{
    background: #f0f4f8;
    color: #1a252c;
    line-height: 1.8;
}

/* HEADER */
header{
    background: linear-gradient(135deg, #0d3b66, #005f73, #0a9396);
    color: white;
    text-align: center;
    padding: 50px 20px;
    box-shadow: 0 4px 12px rgba(0,0,0,0.15);
}

.logo-container {
    width: 100px;
    height: 100px;
    background: #ffffff;
    border-radius: 50%;
    margin: 0 auto 15px auto;
    display: flex;
    align-items: center;
    justify-content: center;
    box-shadow: 0 4px 10px rgba(0,0,0,0.2);
}

.logo-icon {
    font-size: 48px;
    color: #0d3b66;
}

header h1{
    font-size: 42px;
    font-weight: 700;
    margin-bottom: 8px;
    letter-spacing: 0.5px;
}

header p{
    font-size: 18px;
    opacity: 0.95;
}

/* NAVIGATION */
nav{
    background: #002b49;
    padding: 12px 10px;
    position: sticky;
    top: 0;
    z-index: 1000;
    box-shadow: 0 2px 8px rgba(0,0,0,0.2);
}

nav ul{
    display: flex;
    justify-content: center;
    flex-wrap: wrap;
    list-style: none;
    gap: 10px;
}

nav ul li a{
    color: #e0f2fe;
    text-decoration: none;
    padding: 8px 16px;
    border-radius: 6px;
    font-size: 15px;
    font-weight: 500;
    transition: all 0.3s ease;
}

nav ul li a:hover{
    background: #0a9396;
    color: #ffffff;
}

/* HERO SECTION */
.hero{
    background: #ffffff;
    padding: 50px 20px;
    text-align: center;
    border-bottom: 3px solid #e2e8f0;
}

.hero h2{
    font-size: 32px;
    color: #0d3b66;
    margin-bottom: 15px;
}

.hero p{
    max-width: 900px;
    margin: auto;
    font-size: 18px;
    color: #4a5568;
}

/* SECTIONS */
section{
    padding: 50px 20px;
    max-width: 1200px;
    margin: auto;
}

.section-title{
    text-align: center;
    font-size: 32px;
    margin-bottom: 35px;
    color: #0d3b66;
    position: relative;
}

.section-title::after {
    content: '';
    display: block;
    width: 60px;
    height: 4px;
    background: #0a9396;
    margin: 8px auto 0 auto;
    border-radius: 2px;
}

/* STATS HIGHLIGHTS */
.stats-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
    gap: 20px;
    margin-bottom: 40px;
}

.stat-card {
    background: #ffffff;
    padding: 25px;
    border-radius: 12px;
    text-align: center;
    box-shadow: 0 4px 12px rgba(0,0,0,0.05);
    border-top: 4px solid #0a9396;
}

.stat-card h3 {
    font-size: 32px;
    color: #0d3b66;
    margin-bottom: 5px;
}

.stat-card p {
    font-size: 16px;
    color: #4a5568;
    font-weight: 600;
}

/* CARDS */
.cards{
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
    gap: 20px;
}

.card{
    background: #ffffff;
    padding: 25px;
    border-radius: 12px;
    box-shadow: 0 4px 12px rgba(0,0,0,0.06);
    border: 1px solid #e2e8f0;
    transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.card:hover{
    transform: translateY(-5px);
    box-shadow: 0 8px 20px rgba(0,0,0,0.1);
}

.card h3{
    margin-bottom: 12px;
    color: #005f73;
    font-size: 20px;
}

/* TABLE */
table{
    width: 100%;
    border-collapse: collapse;
    background: #ffffff;
    border-radius: 10px;
    overflow: hidden;
    box-shadow: 0 4px 12px rgba(0,0,0,0.06);
}

table th{
    background: #0d3b66;
    color: white;
    padding: 14px;
    text-align: left;
    font-size: 16px;
}

table td{
    padding: 14px;
    border-bottom: 1px solid #edf2f7;
    color: #2d3748;
}

/* HISTORY & NOTICE BOXES */
.info-box{
    background: #ffffff;
    padding: 30px;
    border-radius: 12px;
    box-shadow: 0 4px 12px rgba(0,0,0,0.06);
    border-left: 5px solid #0a9396;
}

/* CONTACT & MAP */
.contact-info p {
    font-size: 17px;
    margin-bottom: 10px;
}

iframe{
    width: 100%;
    height: 380px;
    border: none;
    border-radius: 12px;
    box-shadow: 0 4px 12px rgba(0,0,0,0.08);
}

/* FOOTER */
footer{
    background: #002b49;
    color: white;
    text-align: center;
    padding: 35px 20px;
    margin-top: 40px;
}

footer h3{
    margin-bottom: 10px;
    font-weight: 500;
}

.credit{
    margin-top: 15px;
    color: #cbd5e1;
    font-size: 14px;
    border-top: 1px solid #1e40af;
    padding-top: 15px;
}

@media(max-width: 768px){
    header h1{ font-size: 30px; }
    .hero h2{ font-size: 24px; }
    .section-title{ font-size: 26px; }
}
</style>
</head>

<body>

<!-- HEADER -->
<header>
    <div class="logo-container">
        <span class="logo-icon">🏫</span>
    </div>
    <h1>ജി.എച്ച്.എസ് കാവിലുംപാറ</h1>
    <p>ഗവൺമെന്റ് ഹൈസ്കൂൾ കാവിലുംപാറ</p>
    <p>സ്ഥാപിതം : 1954</p>
</header>

<!-- NAVIGATION -->
<nav>
    <ul>
        <li><a href="#details">വിവരങ്ങൾ</a></li>
        <li><a href="#administration">ഭരണസമിതി</a></li>
        <li><a href="#facilities">സൗകര്യങ്ങൾ</a></li>
        <li><a href="#about">പ്രത്യേകതകൾ</a></li>
        <li><a href="#history">ചരിത്രം</a></li>
        <li><a href="#clubs">ക്ലബ്ബുകൾ</a></li>
        <li><a href="#training">പരിശീലനങ്ങൾ</a></li>
        <li><a href="#achievements">നേട്ടങ്ങൾ</a></li>
        <li><a href="#notice">നോട്ടീസ്</a></li>
        <li><a href="#location">ലൊക്കേഷൻ</a></li>
        <li><a href="#contact">ബന്ധപ്പെടാൻ</a></li>
    </ul>
</nav>

<!-- HERO -->
<div class="hero">
    <h2>കേരളത്തിന്റെ അഭിമാന പൊതുവിദ്യാലയം</h2>
    <p>1954 മുതൽ വിദ്യാഭ്യാസ രംഗത്ത് പ്രവർത്തിച്ചു വരുന്ന ജി.എച്ച്.എസ് കാവിലുംപാറ, മികവുറ്റ അക്കാദമിക അന്തരീക്ഷവും അത്യാധുനിക പഠന സൗകര്യങ്ങളും വിദ്യാർത്ഥികൾക്കായി ഒരുക്കുന്നു.</p>
</div>

<!-- QUICK STATS -->
<section>
    <div class="stats-grid">
        <div class="stat-card">
            <h3>900+</h3>
            <p>വിദ്യാർത്ഥികൾ</p>
        </div>
        <div class="stat-card">
            <h3>50+</h3>
            <p>അധ്യാപകരും ജീവനക്കാരും</p>
        </div>
        <div class="stat-card">
            <h3>50+</h3>
            <p>ഹൈടെക് ക്ലാസ് മുറികൾ</p>
        </div>
        <div class="stat-card">
            <h3>100%</h3>
            <p>ഡിജിറ്റൽ സൗകര്യം</p>
        </div>
    </div>
</section>

<!-- SCHOOL DETAILS -->
<section id="details">
    <h2 class="section-title">📚 സ്കൂൾ വിവരങ്ങൾ</h2>
    <table>
        <tr><th>വിവരം</th><th>വിശദാംശം</th></tr>
        <tr><td>സ്കൂളിന്റെ പേര്</td><td>ഗവൺമെന്റ് ഹൈസ്കൂൾ കാവിലുംപാറ</td></tr>
        <tr><td>സ്ഥലം</td><td>കാവിലുംപാറ, കോഴിക്കോട് ജില്ല</td></tr>
        <tr><td>പിൻകോഡ്</td><td>673513</td></tr>
        <tr><td>സ്ഥാപിതം</td><td>1 ജൂൺ 1954</td></tr>
        <tr><td>സ്കൂൾ കോഡ്</td><td>16083</td></tr>
        <tr><td>യുഡൈസ് കോഡ്</td><td>32040700116</td></tr>
        <tr><td>വിദ്യാഭ്യാസ ജില്ല</td><td>വടകര</td></tr>
        <tr><td>ഉപജില്ല</td><td>കുന്നുമ്മൽ</td></tr>
        <tr><td>പഞ്ചായത്ത്</td><td>കാവിലുംപാറ</td></tr>
        <tr><td>പഠന വിഭാഗങ്ങൾ</td><td>എൽ.പി, യു.പി, ഹൈസ്കൂൾ (1 മുതൽ 10 വരെ)</td></tr>
        <tr><td>പഠനമാധ്യമം</td><td>മലയാളം, ഇംഗ്ലീഷ്</td></tr>
    </table>
</section>

<!-- ADMINISTRATION -->
<section id="administration">
    <h2 class="section-title">👨‍🏫 ഭരണസമിതി</h2>
    <div class="cards">
        <div class="card">
            <h3>ഹെഡ്മിസ്ട്രസ്</h3>
            <p><strong>ശ്രീജ പി</strong></p>
        </div>
 <div>
        <div class="card">
            <h3>പി.ടി.എ പ്രസിഡണ്ട്</h3>
            <p><strong>രാജീവ്</strong></p>
        </div>
    </div>
</section>

<!-- FACILITIES -->
<section id="facilities">
    <h2 class="section-title">💻 ആധുനിക സൗകര്യങ്ങൾ</h2>
    <div class="cards">
        <div class="card">
            <h3>🖥 50+ ഹൈടെക് ക്ലാസ് മുറികൾ</h3>
            <p>ഡിജിറ്റൽ പ്രൊജക്ടറുകളും സ്മാർട്ട് ബോർഡുകളും അടങ്ങിയ അത്യാധുനിക ക്ലാസ് മുറികൾ.</p>
        </div>
        <div class="card">
            <h3>🧪 സയൻസ് & ഹൈടെക് ലാബുകൾ</h3>
            <p>ഫിസിക്സ്, കെമിസ്ട്രി, ബയോളജി പരീക്ഷണങ്ങൾക്കായി പൂർണ്ണ സജ്ജമായ പ്രായോഗിക ലാബുകൾ.</p>
        </div>
        <div class="card">
            <h3>🤖 അറ്റൽ ടിങ്കറിംഗ് ലാബ് (ATL)</h3>
            <p>റോബോട്ടിക്സ്, കോഡിംഗ്, നവീകരണ ആശയങ്ങൾ എന്നിവ പ്രോത്സാഹിപ്പിക്കുന്ന കേന്ദ്രം.</p>
        </div>
        <div class="card">
            <h3>💻 ലിറ്റിൽ കൈറ്റ്സ് ഐ.ടി ലാബ്</h3>
            <p>മികച്ച കമ്പ്യൂട്ടർ ശൃംഖലയും ഐ.ടി പരിശീലന സൗകര്യങ്ങളും.</p>
        </div>
        <div class="card">
            <h3>📚 വിപുലമായ ലൈബ്രറി</h3>
            <p>ആയിരക്കണക്കിന് പുസ്തകങ്ങളും റഫറൻസ് ഗ്രന്ഥങ്ങളും അടങ്ങിയ വായനശാല.</p>
        </div>
    </div>
</section>

<!-- ABOUT -->
<section id="about">
    <h2 class="section-title">🏫 സ്കൂളിന്റെ പ്രത്യേകതകൾ</h2>
    <div class="cards">
        <div class="card">
            <h3>അക്കാദമിക മികവ്</h3>
            <p>പരീക്ഷകളിൽ മികച്ച വിജയശതമാനവും സ്കോളർഷിപ്പ് പരീക്ഷകളിൽ ഉയർന്ന നേട്ടങ്ങളും.</p>
        </div>
        <div class="card">
            <h3>സാങ്കേതിക വിദ്യാഭ്യാസം</h3>
            <p>പ്രായോഗിക ഐ.ടി വിദ്യാഭ്യാസവും സാങ്കേതിക വികസന പരിപാടികളും.</p>
        </div>
        <div class="card">
            <h3>ഭാഷാപഠനം</h3>
            <p>മലയാളം, ഇംഗ്ലീഷ് മീഡിയങ്ങൾക്ക് പുറമെ അറബിക്, സംസ്കൃതം ഭാഷാപഠന സൗകര്യം.</p>
        </div>
        <div class="card">
            <h3>വ്യക്തിത്വ വികസനം</h3>
            <p>കലാ-കായിക മത്സരങ്ങൾ, സാമൂഹിക സേവനം, നേതൃത്വ പരിശീലനങ്ങൾ എന്നിവ.</p>
        </div>
    </div>
</section>

<!-- HISTORY -->
<section id="history">
    <h2 class="section-title">📜 സ്കൂളിന്റെ ചരിത്രം</h2>
    <div class="info-box">
        <p>1954-ൽ മലബാർ ഡിസ്ട്രിക് ബോർഡിന്റെ അംഗീകാരത്തോടെ കല്ലുംപുറം എന്ന സ്ഥലത്ത് ഏകാധ്യാപക വിദ്യാലയമായി പ്രവർത്തനം ആരംഭിച്ച വിദ്യാലയമാണിത്. ശ്രീ. പങ്കജാക്ഷൻ മാസ്റ്ററായിരുന്നു ആദ്യ അധ്യാപകൻ. 1964-ൽ സ്കൂൾ ഇപ്പോഴുള്ള എരഞ്ഞാറ്റിൽ പ്രദേശത്തേക്ക് മാറ്റി സ്ഥാപിച്ചു. പിന്നീട് നാട്ടുകാരുടെയും അധ്യാപകരുടെയും പി.ടി.എയുടെയും സഹകരണത്തോടെ സ്കൂൾ വികസിക്കുകയും ഇന്ന് ഉപജില്ലയിലെ പ്രമുഖ പൊതുവിദ്യാലയമായി മാറുകയും ചെയ്തു.</p>
    </div>
</section>

<!-- CLUBS -->
<section id="clubs">
    <h2 class="section-title">🚩 പ്രധാന ക്ലബ്ബുകൾ</h2>
    <div class="cards">
        <div class="card">
            <h3>👮 സ്റ്റുഡന്റ് പോലീസ് കേഡറ്റ് (SPC)</h3>
            <p>ക്രമശിക്ഷയും സാമൂഹിക പ്രതിബദ്ധതയും വളർത്തുന്നു.</p>
        </div>
        <div class="card">
            <h3>⛑ ജൂനിയർ റെഡ് ക്രോസ് (JRC)</h3>
            <p>ആരോഗ്യ ബോധവത്കരണവും കരുണാർദ്രമായ സേവന പ്രവർത്തനങ്ങളും.</p>
        </div>
        <div class="card">
            <h3>💻 ലിറ്റിൽ കൈറ്റ്സ്</h3>
            <p>ഡിജിറ്റൽ സാങ്കേതികവിദ്യയിലും ഐ.ടി രംഗത്തും കുട്ടികളുടെ കഴിവുകൾ വികസിപ്പിക്കുന്നു.</p>
        </div>
        <div class="card">
            <h3>🌱 എൻവയോൺമെന്റ് ക്ലബ്ബ്</h3>
            <p>പ്രകൃതി സംരക്ഷണ പ്രവർത്തനങ്ങളും പരിസ്ഥിതി ബോധവത്കരണവും.</p>
        </div>
    </div>
</section>

<!-- TRAINING -->
<section id="training">
    <h2 class="section-title">🏅 പരിശീലനങ്ങൾ</h2>
    <div class="cards">
        <div class="card"><h3>എൻ.എം.എം.എസ് പരിശീലനം</h3></div>
        <div class="card"><h3>എൽ.എസ്.എസ് / യു.എസ്.എസ് പരിശീലനം</h3></div>
        <div class="card"><h3>കരാട്ടെ & കായിക പരിശീലനം</h3></div>
        <div class="card"><h3>ചിത്രരചന പരിശീലനം</h3></div>
        <div class="card"><h3>വർക്ക് എക്സ്പീരിയൻസ് പരിശീലനം</h3></div>
    </div>
</section>

<!-- ACHIEVEMENTS -->
<section id="achievements">
    <h2 class="section-title">🏆 നേട്ടങ്ങൾ</h2>
    <div class="cards">
        <div class="card">
            <h3>ഉയർന്ന വിജയശതമാനം</h3>
            <p>എസ്.എസ്.എൽ.സി പരീക്ഷകളിൽ തുടർച്ചയായി മികച്ച വിജയം.</p>
        </div>
        <div class="card">
            <h3>മികച്ച ലിറ്റിൽ കൈറ്റ്സ് യൂണിറ്റ്</h3>
            <p>ഐ.ടി മേഖലയിലെ മികവിന് ഉപജില്ലാതല അംഗീകാരങ്ങൾ.</p>
        </div>
        <div class="card">
            <h3>കലാ-കായിക നേട്ടങ്ങൾ</h3>
            <p>കലാകായിക മേളകളിൽ വിവിധ തലങ്ങളിൽ ലഭിച്ച നേട്ടങ്ങൾ.</p>
        </div>
    </div>
</section>

<!-- NOTICE -->
<section id="notice">
    <h2 class="section-title">📢 നോട്ടീസ് ബോർഡ്</h2>
    <div class="info-box">
        <p>സ്കൂളിന്റെ പ്രധാന അറിയിപ്പുകൾ, പരീക്ഷാ തീയതികൾ, ഔദ്യോഗിക പരിപാടികൾ എന്നിവ ഈ വിഭാഗത്തിൽ ലഭ്യമാക്കുന്നതാണ്.</p>
    </div>
</section>

<!-- LOCATION -->
<section id="location">
    <h2 class="section-title">📍 സ്കൂൾ ലൊക്കേഷൻ</h2>
    <iframe src="https://www.google.com/maps?q=Kavilumpara&output=embed"></iframe>
</section>

<!-- CONTACT -->
<section id="contact">
    <h2 class="section-title">📞 ബന്ധപ്പെടാൻ</h2>
    <div class="info-box contact-info">
        <p><strong>ഫോൺ:</strong> 0496 2564436</p>
        <p><strong>മൊബൈൽ:</strong> 97454 04453, 89210 35867, 9656503005</p>
        <p><strong>ഇമെയിൽ:</strong> ghskavilumpara@gmail.com</p>
        <p><strong>വിലാസം:</strong> ഗവൺമെന്റ് ഹൈസ്കൂൾ കാവിലുംപാറ, കാവിലുംപാറ പി.ഒ, കോഴിക്കോട് - 673513</p>
    </div>
</section>

<!-- FOOTER -->
<footer>
    <h3>ജി.എച്ച്.എസ് കാവിലുംപാറ ഔദ്യോഗിക വെബ്സൈറ്റ്</h3>
    <p class="credit">Made By Little Kites Unit GHS KAVILUMPARA and NAYANTHEJ.S</p>
</footer>

</body>
</html>
