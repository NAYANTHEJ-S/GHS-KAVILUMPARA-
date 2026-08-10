# GHS-KAVILUMPARA-
This is a website for school                                                                                             

designed by                                                                                                               
Nayanthej.S 
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

/* HEADER & LOGO */
header{
    background: linear-gradient(135deg, #0d3b66, #005f73, #0a9396);
    color: white;
    text-align: center;
    padding: 40px 20px;
    box-shadow: 0 4px 12px rgba(0,0,0,0.15);
}

.school-logo {
    width: 110px;
    height: 110px;
    background: #ffffff
    border-radius: 50%;
    margin: 0 auto 15px auto;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    box-shadow: 0 6px 15px rgba(0,0,0,0.3);
}

.logo-icon {
    font-size: 40px;
    line-height: 1;
}

.logo-text {
    font-size: 10px;
    font-weight: bold;
    color: #0d3b66;
    margin-top: 4px;
}

header h1{
    font-size: 40px;
    font-weight: 700;
    margin-bottom: 8px;
    text-shadow: 1px 1px 3px rgba(0,0,0,0.3);
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

/* ANIMATED NOTICE TICKER */
.ticker-container {
    background: #001524;
    color: #ffb703;
    display: flex;
    align-items: center;
    overflow: hidden;
    border-bottom: 3px solid #ee9b00;
}

.ticker-title {
    background: #e63946;
    color: #fff;
    padding: 10px 20px;
    font-weight: bold;
    white-space: nowrap;
    z-index: 2;
    box-shadow: 2px 0 5px rgba(0,0,0,0.3);
}

.ticker-text {
    white-space: nowrap;
    padding-left: 100%;
    display: inline-block;
    animation: marquee 22s linear infinite;
    font-size: 17px;
    font-weight: 600;
}

@keyframes marquee {
    0% { transform: translate(0, 0); }
    100% { transform: translate(-100%, 0); }
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

/* INFO BOXES */
.info-box{
    background: #ffffff;
    padding: 30px;
    border-radius: 12px;
    box-shadow: 0 4px 12px rgba(0,0,0,0.06);
    border-left: 5px solid #0a9396;
}

/* MAP & CONTACT */
iframe{
    width: 100%;
    height: 380px;
    border: none;
    border-radius: 12px;
    box-shadow: 0 4px 12px rgba(0,0,0,0.08);
}

.contact-info p {
    font-size: 17px;
    margin-bottom: 10px;
}

/* FOOTER */
footer{
    background: #001524;
    color: white;
    text-align: center;
    padding: 40px 20px 25px 20px;
    margin-top: 40px;
}

footer h3{
    margin-bottom: 15px;
    font-weight: 500;
    font-size: 20px;
}

.credit-box {
    margin-top: 20px;
    padding: 18px;
    background: rgba(255, 255, 255, 0.05);
    border-radius: 8px;
    border: 1px solid #0a9396;
    display: inline-block;
}

.credit{
    color: #00f5d4;
    font-size: 16px;
    font-weight: bold;
    letter-spacing: 0.5px;
}

.copyright {
    margin-top: 15px;
    color: #94a3b8;
    font-size: 14px;
    border-top: 1px solid rgba(255,255,255,0.1);
    padding-top: 15px;
}

@media(max-width: 768px){
    header h1{ font-size: 30px; }
    .hero h2{ font-size: 24px; }
    .section-title{ font-size: 26px; }
    .ticker-title{ font-size: 14px; padding: 10px 10px; }
}
</style>
</head>

<body>

<header>
    <div class="school-logo">
        <span class="logo-icon"><img src="School logo.jpg" alt="സ്‌കൂൾ ലോഗോ" width="500">
</span>
       
    </div>
    <h1>ജി.എച്ച്.എസ് കാവിലുംപാറ</h1>
    <p>ഗവൺമെന്റ് ഹൈസ്കൂൾ കാവിലുംപാറ</p>
    <p>സ്ഥാപിതം : 1954</p>
    <img src="School photo for website.png" alt="സ്‌കൂൾ ഫോട്ടോ" width="500">

</header>

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

<div class="ticker-container">
    <div class="ticker-title">📢 വാർത്തകൾ:</div>
    <div class="ticker-text">
        🎉 2025-26 SSLC പരീക്ഷയിൽ 100% വിജയം! &nbsp;&nbsp;&nbsp;&nbsp;🏆 INSPIRE AWARD, NMMS, USS, LSS സ്കോളർഷിപ്പ് പരീക്ഷകളിൽ ഉപജില്ലാ തലത്തിൽ ഉജ്ജ്വല വിജയം നേടി ജി.എച്ച്.എസ് കാവിലുംപാറ! &nbsp;&nbsp;&nbsp;&nbsp;✨ പ്രവേശനവും അക്കാദമിക പ്രവർത്തനങ്ങളും പുരോഗമിക്കുന്നു.
    </div>
</div>

<div class="hero">
    <h2>കേരളത്തിന്റെ അഭിമാന പൊതുവിദ്യാലയം</h2>
    <p>1954 മുതൽ വിദ്യാഭ്യാസ രംഗത്ത് പ്രവർത്തിച്ചു വരുന്ന ജി.എച്ച്.എസ് കാവിലുംപാറ, മികവുറ്റ അക്കാദമിക അന്തരീക്ഷവും അത്യാധുനിക പഠന സൗകര്യങ്ങളും വിദ്യാർത്ഥികൾക്കായി ഒരുക്കുന്നു.</p>
</div>

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

<section id="administration">
    <h2 class="section-title">👨‍🏫 ഭരണസമിതി</h2>
    <div class="cards">
        <div class="card">
            <h3>ഹെഡ്മിസ്ട്രസ്</h3>
            <p><strong>ശ്രീജ പി ഇ</strong></p>
        </div> 
  
        <div class="card">
            <h3>പി.ടി.എ പ്രസിഡണ്ട്</h3>
            <p><strong>രാജീവൻ</strong></p>
        </div>
    </div>
</section>

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

<section id="history">
    <h2 class="section-title">📜 സ്കൂളിന്റെ ചരിത്രം</h2>
    <div class="info-box">
        <p>1954-ൽ മലബാർ ഡിസ്ട്രിക് ബോർഡിന്റെ അംഗീകാരത്തോടെ കല്ലുംപുറം എന്ന സ്ഥലത്ത് ഏകാധ്യാപക വിദ്യാലയമായി പ്രവർത്തനം ആരംഭിച്ച വിദ്യാലയമാണിത്. ശ്രീ. പങ്കജാക്ഷൻ മാസ്റ്ററായിരുന്നു ആദ്യ അധ്യാപകൻ. 1964-ൽ സ്കൂൾ ഇപ്പോഴുള്ള എരഞ്ഞാറ്റിൽ പ്രദേശത്തേക്ക് മാറ്റി സ്ഥാപിച്ചു. പിന്നീട് നാട്ടുകാരുടെയും അധ്യാപകരുടെയും പി.ടി.എയുടെയും സഹകരണത്തോടെ സ്കൂൾ വികസിക്കുകയും ഇന്ന് ഉപജില്ലയിലെ പ്രമുഖ പൊതുവിദ്യാലയമായി മാറുകയും ചെയ്തു.</p>
        
        <div id="more-text" style="display: none;">
            <p>കാവിനടുത്ത് പാറക്കൂട്ടങ്ങൾ കണ്ടതുകൊണ്ടാകാം കാവിലുംപാറ എന്ന പേരിൽ ഈ പ്രദേശം അറിയപ്പെടുന്നത്. കാവിലുംപാറയുടെ സിരാകേന്ദ്രമായ തൊട്ടിൽപ്പാലം പട്ടണത്തിൽ നിന്ന് ഏകദേശം ഒരു കിലോമീറ്ററിനുളളിൽ പ്രകൃതിരമണീയമായ എരഞ്ഞാറ്റിൽ എന്നറിയപ്പെടുന്ന സ്ഥലത്താണ് കാവിലുംപാറ ഗവൺമെൻറ് ഹൈസ്കൂൾ സ്ഥിതി ചെയ്യുന്നത്. കാവിലുംപാറ പഞ്ചായത്തിലെ സാമൂഹിക സാംസ്കാരിക രാഷ്ട്രീയ വിദ്യാഭ്യാസ രംഗങ്ങളിൽ ഈ സരസ്വതീ ക്ഷേത്രം ഗണ്യമായ പങ്ക് വഹിക്കുന്നു.</p>
            
            <p>ശ്രീ. പി.ടി. ഭാസ്കരപ്പണിക്കർ ഡിസ്ട്രിക് ബോർഡ് പ്രസിഡൻറായിരിക്കെ സ്വാതന്ത്ര്യ സമര സേനാനിയായിരുന്ന ശ്രീ. എ.വി. കുഞ്ഞിരാമൻ നായരുടെ നിർദേശം അനുസരിച്ച് മലബാർ ഡിസ്ട്രിക് ബോർഡിൻെറ അംഗീകാരത്തോടെ 1954ൽ ഏകാധ്യാപക സ്കൂളായി കല്ലുംപുറം എന്ന സ്ഥലത്ത് ഇന്നത്തെ കാവിലുംപാറ ഗവൺമെൻറ് ഹൈസ്കൂൾ പ്രവർത്തനമാരംഭിച്ചു. തുടക്കത്തിൽ ശ്രീ. കുരിക്കണ്ടി കേളുനമ്പ്യാർ, ചെമ്പോട്ടുമ്മൽ ഗോവിന്ദൻ മാസ്ററർ എന്നിവർ ഈ സ്കൂളിനു വേണ്ട ഭൗതിക സാഹചര്യങ്ങൾ ഒരുക്കിക്കൊടുത്തു. കോഴിക്കോട്ടുകാരനായ ശ്രീ. പങ്കജാക്ഷൻ മാസ്റ്ററായിരുന്നു ആദ്യ അധ്യാപകൻ. ആദ്യ വിദ്യാർത്ഥിയായി ശ്രീ. കുഞ്ഞിപ്പറമ്പത്ത് കുഞ്ഞിരാമൻ സ്കൂളിൽ ചേർന്നു. പ്രഥമ ബാച്ചിൽ 20 വിദ്യാർത്ഥികൾ ഉണ്ടായിരുന്നു. പങ്കജാക്ഷൻ മാസ്റ്റർക്കു ശേഷം ടി. കൃഷ്ണൻ മാസ്റ്റർ, രാഘവൻ മാസ്റ്റർ, നാരായണി ടീച്ചർ, നാണു മാസ്റ്റർ എന്നിവർ ആദ്യകാല അധ്യാപകരിൽ പെടുന്നു. 1 മുതൽ 4 വരെയായിരുന്നു ഇവിടെ ക്ലാസ് നടത്തിയിരുന്നത്.</p>
            
            <p>1960ൽ പി.സി. മാധവൻ നമ്പൂതിരി പ്രധാനാധ്യാപകനായി ചുമതലയേററു. 1964ൽ സ്കൂളിനു വേണ്ടി ചേലോട്ട് ഇല്ലത്ത് തമ്പായി എന്നറിയപ്പെടുന്ന വിഷ്ണു നമ്പൂതിരിയിൽ നിന്നും 19 സെൻറ് സ്ഥലം സൗജന്യമായി ലഭിച്ചതിനാൽ സ്കൂൾ കല്ലുംപുറം എന്ന സ്ഥലത്ത് നിന്നും ഇപ്പോൾ സ്ഥിതി ചെയ്യുന്ന എരഞ്ഞാറ്റിൽ എന്ന സ്ഥലത്തേക്ക് മാറ്റി സ്ഥാപിച്ചു. 1966ൽ അന്നത്തെ രക്ഷിതാക്കളും നാട്ടുകാരുമായിരുന്ന സർവ്വശ്രീ. കണ്ണങ്കോട്ട് കണാരൻ, ചൂഴികപ്പളളി ചാത്തു, പുലക്കുന്നുമ്മൽ ചെമ്മേരിക്കണ്ടി കണ്ണൻ, മരുതോറ ഗോപാലൻ നായർ, കല്ലുംപുറത്ത് കുഞ്ഞിരാമൻ നായർ, കെ.ടി. നാരായണൻ നമ്പ്യാർ, എം. കെ. കേളുക്കുറുപ്പ്, മഞ്ചക്കടവത്ത് ഗോവിന്ദക്കുറുപ്പ്, തുണ്ടിയിൽ കുമാരൻ, പാമ്പിനിയിൽ കേളുനായർ തുടങ്ങിയവരുടെ സേവനങ്ങൾ സ്തുത്യർഹമായിരുന്നു.</p>
            
            <p>സ്കൂളിൻെറ അഭ്യുദയകാംക്ഷികളുടെ പരിശ്രമഫലമായി 4 ക്ളാസ് മുറികളുള്ള ഓല ഷെഡ്ഡ് നിർമ്മിച്ചു. സ്കൂളിൻെറ പ്രവർത്തനത്തിന് അന്നത്തെ ഉപജില്ലാ വിദ്യാഭ്യാസ ഓഫീസർ ശ്രീ. കുഞ്ഞമ്പുവിൻെറ സഹകരണം എടുത്തുപറയേണ്ടതാണ്. തുടർന്ന് അഞ്ച് മുറികളുള്ള സ്കൂൾ കെട്ടിടം ഡോ. കെ.ജി. അടിയോടി മന്ത്രിയായിരിക്കെ ഉദ്ഘാടനം ചെയ്യുകയുണ്ടായി. യൂ. പി. സ്കൂൾ ആയി ഉയർത്തുവാൻ വേണ്ടി സർവ്വശ്രീ. തുണ്ടിയിൽ കുമാരൻ, എം. കെ. കേളുക്കുറുപ്പ് എന്നീ പി.ടി.എ. പ്രസിഡൻറുമാരും അധ്യാപകരായിരുന്ന പി.സി. മാധവൻ നമ്പൂതിരി, എം.വി. തങ്കച്ചൻ, പി.സി. മധുസൂദനൻ തുടങ്ങിയവരും പരിശ്രമിക്കുകയുണ്ടായി. 5 മുറികളുള്ള കെട്ടിടത്തിനു വേണ്ട മരങ്ങൾ ശ്രീ. ഹരിദാസൻ വൈദ്യർ സംഭാവനയായി നൽകിയതായിരുന്നു.</p>
            
            <p>യൂ. പി. സ്കൂൾ ആയി ഉയർത്തുവാൻ വേണ്ടി ചേലോട്ട് ഇല്ലത്ത് സുഭദ്ര അന്തർജനത്തിൽ നിന്നും ഒരു ഏക്കർ സ്ഥലം കൂടി വില കൊടുത്തു വാങ്ങുകയുണ്ടായി. 1978ൽ യൂ. പി. സ്കൂൾ ആയി ഉയർത്തുവാൻ എൻ. കെ. അമ്മത് മാസ്റ്ററുടെയും ബേപ്പൂർ എം.എൽ.എ. ആയിരുന്ന ശ്രീ. എൻ. പി. മൊയ്തീൻെറയും സഹായ സഹകരണങ്ങൾ ലഭിക്കുകയുണ്ടായി. കൂടാതെ മന്ത്രി ബേബി ജോണിൻെറയും സ്ഥലം എം.എൽ.എ. ശ്രീ. കെ.ടി. കണാരൻെറയും സഹായഹസ്തങ്ങൾ ഓർമ്മിക്കത്തക്കതായിരുന്നു.</p>
            
            <p>1981ൽ ശ്രീ. സി.ഐ. ഭാനു മാസ്ററർ ഹെഡ്മാസ്റ്ററായി ചാർജെടുത്തു. തുടർന്നുള്ള 15 വർഷത്തോളം സ്കൂളിൻെറ സർവോൻമുഖമായ പുരോഗതിയിൽ ഹെഡ്മാസ്റ്ററായ സി.ഐ. ഭാനു മാസ്റ്ററുടെയും അന്നത്തെ പി.ടി.എ. പ്രസിഡന്റായിരുന്ന എം. കേളുക്കുറുപ്പിൻെറയും സേവനങ്ങൾ എക്കാലവും സ്മരിക്കത്തക്കതായിരുന്നു. ഈ കാലഘട്ടം സ്കൂളിൻെറ സുവർണ്ണ കാലഘട്ടമായിരുന്നു. ഈ കാലഘട്ടത്തിൽ പി.ടി.എ. പ്രസിഡന്റുമാരായിരുന്ന സർവ്വശ്രീ. ചാത്തു നായർ, കുയ്യടി അശോകൻ, പി.ടി.ജോയ്, സുരേഷ് ബാബു, വി.പി. ബാലകൃഷ്ണൻ, എം. ബാലൻ, കുണ്ടുകുളങ്ങര രവീന്ദ്രൻ, ടി. ഒ. രവീന്ദ്രൻ, കുയ്യാലിൽ സുരേഷ് എന്നിവർ ആത്മാർത്ഥമായി സ്കൂളിൻെറ പുരോഗതിക്കു വേണ്ടി പ്രവർത്തിച്ചിട്ടുണ്ട്.</p>
        </div>

        <button id="read-more-btn" onclick="toggleText()" style="background: none; border: none; color: #0066cc; cursor: pointer; font-weight: bold; margin-top: 10px; padding: 0;">
            Read More...
        </button>
    </div>
</section>

<script>
function toggleText() {
    var moreText = document.getElementById("more-text");
    var btnText = document.getElementById("read-more-btn");

    if (moreText.style.display === "none") {
        moreText.style.display = "block";
        btnText.innerHTML = "Read Less";
    } else {
        moreText.style.display = "none";
        btnText.innerHTML = "Read More...";
    }
}
</script>


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
            <h3>🤝 സ്കൂൾ സോഷ്യൽ സർവീസ് സ്കീം (SSSS)</h3>
            <p>വിദ്യാർത്ഥികളിൽ സാമൂഹിക സേവന താല്പര്യവും പൊതുനന്മയ്ക്കായുള്ള പങ്കാളിത്തവും വളർത്തുന്നു.</p>
        </div>
    </div>
</section>

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

<section id="notice">
    <h2 class="section-title">📢 നോട്ടീസ് ബോർഡ്</h2>
    <div class="info-box">
        <p>സ്കൂളിന്റെ പ്രധാന അറിയിപ്പുകൾ, പരീക്ഷാ തീയതികൾ, ഔദ്യോഗിക പരിപാടികൾ എന്നിവ ഈ വിഭാഗത്തിൽ ലഭ്യമാക്കുന്നതാണ്.</p>
    </div>
</section>

<section id="location">
    <h2 class="section-title">📍 സ്കൂൾ ലൊക്കേഷൻ</h2>
    <iframe src="https://www.google.com/maps?q=Kavilumpara&output=embed"></iframe>
</section>

<section id="contact">
    <h2 class="section-title">📞 ബന്ധപ്പെടാൻ</h2>
    <div class="info-box contact-info">
        <p><strong>ഫോൺ:</strong> 0496 2564436</p>
        
        <p><strong>ഇമെയിൽ:</strong> ghskavilumpara@gmail.com</p>
        <p><strong>വിലാസം:</strong> ഗവൺമെന്റ് ഹൈസ്കൂൾ കാവിലുംപാറ, കാവിലുംപാറ പി.ഒ, കോഴിക്കോട് - 673513</p>
    </div>
</section>.
<h3>സ്കൂൾ വിക്കിയിലേക്കുള്ള നേരിട്ടുള്ള ലിങ്ക്</h3>
<a href="https://schoolwiki.in/%E0%B4%9C%E0%B4%BF.%E0%B4%8E%E0%B4%9A%E0%B5%8D%E0%B4%9A%E0%B5%8D.%E0%B4%8E%E0%B4%B8%E0%B5%8D._%E0%B4%95%E0%B4%BE%E0%B4%B5%E0%B4%BF%E0%B4%B2%E0%B5%81%E0%B4%82%E0%B4%AA%E0%B4%BE%E0%B4%B1" target="_blank">GHS Kavilumpara School Wiki</a>


<footer>
    <h3>GHS Kavilumpara official website</h3>
    
    <div class="credit-box">
        <p class="credit">💻Designed & Developed by NAYANTHEJ.S.</p>
        <p>LITTLE KITES UNIT GHS KAVILUMPARA</p>
    </div>

    <p class="copyright">Copyright © GHS Kavilumpara. All Rights Reserved.</p>
</footer>

</body>
</html>
