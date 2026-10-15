# Romeodurbano.github.io
<!DOCTYPE html>
<html lang="fr">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<title>ESCP AI Society · Audit d'externalisation</title>
<link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=DM+Sans:wght@400;500;700&family=JetBrains+Mono:wght@400;500&display=swap">
<style>
:root{color-scheme:dark;--bg:#030a24;--card:rgba(9,16,40,.78);--tx:#f2f4fa;--mu:#9aa4c0;--ac:#e0bf6a;--ac2:rgba(224,191,106,.12);--bd:rgba(150,170,220,.2);--bl:#5aa8e0;--ok:#5fd19b;--wa:#e0bf6a;
box-sizing:border-box;padding-top:env(safe-area-inset-top,0px);padding-bottom:env(safe-area-inset-bottom,0px)}
*{box-sizing:border-box}html{scroll-padding-top:env(safe-area-inset-top,0px)}
body{margin:0;color:var(--tx);font:16px/1.55 "DM Sans",system-ui,-apple-system,"Segoe UI",sans-serif;background:radial-gradient(900px 500px at 70% 10%,#0a1a4a55,transparent),radial-gradient(700px 500px at 10% 90%,#0c235f33,transparent),var(--bg);min-height:100vh;position:relative}
body::before{content:"";position:fixed;inset:0;pointer-events:none;background-image:radial-gradient(1px 1px at 20px 30px,#fff9,transparent),radial-gradient(1px 1px at 90px 120px,#fff6,transparent),radial-gradient(1.5px 1.5px at 160px 60px,#fffa,transparent),radial-gradient(1px 1px at 50px 170px,#fff5,transparent),radial-gradient(1px 1px at 130px 190px,#fff7,transparent);background-size:200px 200px}
.gl{position:absolute;left:22px;top:0;width:2px;height:110px;background:linear-gradient(#e0bf6a00,#e0bf6a);pointer-events:none}
.gl::after{content:"";position:absolute;bottom:-4px;left:-3px;width:8px;height:8px;border-radius:50%;background:var(--ac);box-shadow:0 0 12px var(--ac)}
.w{max-width:820px;margin:0 auto;padding:0 20px;position:relative}
header{display:flex;justify-content:space-between;align-items:center;padding:18px 0 8px}
.logo{display:flex;flex-direction:row-reverse;align-items:center;gap:14px;color:#fff;text-decoration:none}
.logo .tx{display:flex;flex-direction:column;align-items:center}
.logo .l1{font-weight:700;letter-spacing:.25em;font-size:1.2rem;display:flex;align-items:center;gap:.8em;white-space:nowrap}
.logo .l1 i{display:inline-block;width:2px;height:1.4em;background:#8a93ad}
@media(max-width:520px){.logo .l1{font-size:.85rem;letter-spacing:.14em}header>.pill{display:none}}
.mono,.lab{font-family:"JetBrains Mono",ui-monospace,monospace;text-transform:uppercase;letter-spacing:.18em;font-size:.74rem}
.lab{color:var(--ac)}
.pill{background:var(--ac2);color:var(--ac);border:1px solid rgba(224,191,106,.3);border-radius:99px;padding:4px 12px;font-size:.78rem;font-weight:500;white-space:nowrap}
.pill.b{background:rgba(90,168,224,.12);color:var(--bl);border-color:rgba(90,168,224,.3)}
.hero{padding:44px 0 26px;position:relative}
.knot{position:absolute;right:-50px;top:10px;width:300px;opacity:.55;pointer-events:none}
@media(max-width:640px){.knot{width:200px;right:-60px;opacity:.3}}
h1{font-size:clamp(1.9rem,5.4vw,2.9rem);line-height:1.12;margin:10px 0 16px;font-weight:700;max-width:620px;position:relative}
h1 u{text-decoration:none;color:var(--ac);border-bottom:2px solid var(--ac)}
.hero p{color:var(--mu);font-size:1.05rem;margin:0 0 22px;max-width:540px;position:relative}
.pills{display:flex;gap:8px;flex-wrap:wrap;margin-top:20px;position:relative}
button{font:inherit;cursor:pointer;border:0;border-radius:10px;padding:11px 22px;font-weight:700}
.p{background:var(--ac);color:#0b1230}.p:hover{filter:brightness(1.08)}
.s{background:transparent;color:var(--tx);border:1px solid var(--bd)}
.big{font-size:1.25rem;padding:20px 46px;border-radius:14px;box-shadow:0 0 30px rgba(224,191,106,.4);position:relative}
@media(max-width:640px){.big{width:100%;padding:20px 24px}}
.card{background:var(--card);border:1px solid var(--bd);border-radius:20px;padding:24px;margin:0 0 36px;backdrop-filter:blur(6px)}
.bar{height:5px;background:rgba(255,255,255,.1);border-radius:9px;overflow:hidden;margin-bottom:8px}
.bar i{display:block;height:100%;background:linear-gradient(90deg,var(--ac) 70%,var(--bl));width:25%;transition:width .3s}
.st{margin-bottom:18px;color:var(--mu)}
h2{margin:0 0 4px;font-size:1.35rem;text-transform:uppercase;letter-spacing:.05em}
.sub{color:var(--mu);margin:0 0 18px;font-size:.93rem}
label{display:block;font-weight:500;font-size:.88rem;margin:14px 0 5px}
input[type=text],input[type=email],select,textarea{width:100%;font:inherit;padding:10px 12px;border:1px solid var(--bd);border-radius:10px;background:rgba(3,10,36,.7);color:var(--tx)}
input:focus,select:focus,textarea:focus{outline:1px solid var(--ac);border-color:var(--ac)}
textarea{min-height:80px;resize:vertical}
.g2{display:grid;grid-template-columns:1fr 1fr;gap:12px}
@media(max-width:560px){.g2{grid-template-columns:1fr}}
.task{border:1px solid var(--bd);border-radius:14px;padding:12px 14px;margin-bottom:10px;transition:.2s}
.task.on{border-color:var(--ac);background:var(--ac2)}
.task>label{display:flex;gap:10px;align-items:flex-start;margin:0;cursor:pointer;font-weight:700}
.task input[type=checkbox]{accent-color:#e0bf6a;margin-top:5px}
.task small{display:block;font-weight:400;color:var(--mu)}
.det{display:none;margin-top:10px;gap:12px}
.task.on .det{display:grid;grid-template-columns:1fr 1fr}
@media(max-width:560px){.task.on .det{grid-template-columns:1fr}}
.det label{font-weight:400;font-size:.83rem;margin:0 0 4px}
.nav{display:flex;justify-content:space-between;margin-top:22px;gap:10px}
.kp{display:grid;grid-template-columns:repeat(3,1fr);gap:10px;margin:16px 0}
.kp div{border:1px solid var(--bd);border-radius:14px;padding:14px 8px;text-align:center;background:rgba(3,10,36,.5)}
.kp b{display:block;font-size:1.9rem;line-height:1.1;color:var(--ac)}.kp span{font-size:.76rem;color:var(--mu)}
.res{border:1px solid var(--bd);border-radius:14px;padding:14px;margin-bottom:10px;background:rgba(3,10,36,.45)}
.res h3{margin:0 0 4px;font-size:1rem;display:flex;justify-content:space-between;gap:8px;flex-wrap:wrap}
.tag{font-size:.72rem;padding:2px 10px;border-radius:99px;font-weight:700;background:var(--ac2);color:var(--ac);border:1px solid rgba(224,191,106,.3)}
.tag.a{background:rgba(95,209,155,.12);color:var(--ok);border-color:rgba(95,209,155,.3)}
.tag.c{background:rgba(90,168,224,.12);color:var(--bl);border-color:rgba(90,168,224,.3)}
.sc{height:5px;background:rgba(255,255,255,.1);border-radius:9px;margin:8px 0}.sc i{display:block;height:100%;background:var(--ac);border-radius:9px}
.res p{margin:4px 0 0;color:var(--mu);font-size:.88rem}
.note{background:rgba(90,168,224,.1);border:1px solid rgba(90,168,224,.3);border-radius:12px;padding:10px 14px;font-size:.88rem;margin:12px 0}
.how{display:grid;grid-template-columns:repeat(3,1fr);gap:12px;margin:10px 0 36px}
@media(max-width:560px){.how{grid-template-columns:1fr}}
.how div{background:var(--card);border:1px solid var(--bd);border-radius:16px;padding:16px;color:var(--mu);font-size:.92rem}
.how b{display:block;color:var(--ac);font-family:"JetBrains Mono",monospace;font-size:1.3rem;margin-bottom:2px}
.how strong{color:var(--tx)}
footer{color:var(--mu);font-size:.78rem;text-align:center;padding:6px 0 34px}
.hide{display:none}
@media print{body::before,.gl{display:none}body{background:#030a24}}
</style>
</head>
<body>
<div class="gl"></div>
<div class="w">
<header>
<a class="logo" href="#" aria-label="ESCP AI Society">
<div class="tx"><div class="l1">ESCP <i></i> AI SOCIETY</div></div>
<svg width="44" height="44" viewBox="0 0 100 100" fill="none" aria-hidden="true"><defs><clipPath id="lc"><circle cx="28" cy="50" r="9"/><circle cx="72" cy="50" r="9"/></clipPath></defs><g stroke-width="10"><ellipse cx="50" cy="50" rx="38" ry="17" transform="rotate(-45 50 50)" stroke="#9aa3bd"/><ellipse cx="50" cy="50" rx="38" ry="17" transform="rotate(45 50 50)" stroke="#fff"/><g clip-path="url(#lc)"><ellipse cx="50" cy="50" rx="38" ry="17" transform="rotate(-45 50 50)" stroke="#9aa3bd"/></g></g></svg>
</a>
<span class="pill b">Audit gratuit · 5 min</span>
</header>

<section class="hero">
<svg class="knot" viewBox="0 0 200 200" fill="none" aria-hidden="true"><defs><linearGradient id="kw" x1="0" y1="0" x2="1" y2="1"><stop offset="0" stop-color="#f2f5ff"/><stop offset="1" stop-color="#8f9bc0"/></linearGradient><linearGradient id="kg" x1="0" y1="1" x2="1" y2="0"><stop offset="0" stop-color="#aab4d0"/><stop offset="1" stop-color="#3a4a7a"/></linearGradient><clipPath id="kc"><circle cx="56" cy="100" r="18"/><circle cx="144" cy="100" r="18"/></clipPath></defs><g stroke-width="20"><ellipse cx="100" cy="100" rx="76" ry="34" transform="rotate(-45 100 100)" stroke="url(#kg)"/><ellipse cx="100" cy="100" rx="76" ry="34" transform="rotate(45 100 100)" stroke="url(#kw)"/><g clip-path="url(#kc)"><ellipse cx="100" cy="100" rx="76" ry="34" transform="rotate(-45 100 100)" stroke="url(#kg)"/></g></g></svg>
<div class="lab">Audit d'externalisation · ESCP AI Society</div>
<h1>Quelles tâches de votre entreprise peut-on <u>externaliser</u> ou automatiser avec l'IA ?</h1>
<p style="color:var(--tx);font-weight:500;margin-bottom:12px">ESCP AI Society accompagne les entreprises dans leur transformation vers l'IA : automatisation de processus, agents IA, analyse de données et formation des équipes.</p>
<p>Répondez à un court audit. Vous obtenez un diagnostic priorisé, une estimation du temps gagné et une piste d'accompagnement par les étudiants de l'association.</p>
<button class="p big" onclick="document.getElementById('audit').scrollIntoView({behavior:'smooth'})">Démarrer l'audit →</button>
<div class="pills"><span class="pill">Diagnostic priorisé</span><span class="pill">Temps gagné estimé</span><span class="pill b">Données protégées</span></div>
</section>

<div class="how">
<div><b>01</b><strong>Décrivez</strong><br>Votre structure et les tâches chronophages.</div>
<div><b>02</b><strong>Analysez</strong><br>Chaque tâche est notée selon son potentiel d'automatisation.</div>
<div><b>03</b><strong>Agissez</strong><br>Recevez un plan et un contact au sein de l'association.</div>
</div>

<section class="card" id="audit">
<div class="bar"><i id="pb"></i></div><div class="st mono" id="st"></div>

<div class="step" data-s="0">
<h2>Votre entreprise</h2><p class="sub">Quelques informations pour contextualiser le diagnostic.</p>
<label>Nom de l'entreprise</label><input type="text" id="nom">
<div class="g2">
<div><label>Secteur</label><select id="sec"><option>Commerce / retail</option><option>Services / conseil</option><option>Industrie</option><option>Tech / numérique</option><option>Santé</option><option>Immobilier</option><option>Finance / assurance</option><option>Autre</option></select></div>
<div><label>Taille</label><select id="tai"><option>1-9 salariés</option><option>10-49 salariés</option><option>50-249 salariés</option><option>250+ salariés</option></select></div>
</div>
<label>Email de contact</label><input type="email" id="mail" placeholder="prenom@entreprise.com">
<label style="display:flex;gap:10px;align-items:flex-start;font-weight:400;color:var(--mu);margin-top:16px"><input type="checkbox" id="cons" style="margin-top:4px;accent-color:#e0bf6a"><span>J'accepte que mes réponses soient transmises à ESCP AI Society afin d'être recontacté(e) à propos de cet audit.</span></label>
</div>

<div class="step hide" data-s="1">
<h2>Vos tâches à externaliser</h2><p class="sub">Cochez celles qui vous pèsent, puis précisez le temps passé.</p>
<div id="tasks"></div>
</div>

<div class="step hide" data-s="2">
<h2>Contexte et contraintes</h2><p class="sub">Pour adapter la solution à votre réalité.</p>
<label>Outils actuellement utilisés</label><input type="text" id="out" placeholder="Excel, Notion, HubSpot, Sage…">
<label>Avez-vous déjà utilisé l'IA dans votre activité ?</label><select id="ia"><option value="0">Jamais</option><option value="1">Quelques tests ponctuels (ChatGPT, Copilot…)</option><option value="2">Usage régulier par certains collaborateurs</option><option value="3">IA intégrée dans certains processus</option></select>
<label>Si oui, pour quels usages ? (facultatif)</label><input type="text" id="iau" placeholder="Rédaction d'emails, support client, analyse…">
<div class="g2">
<div><label>Sensibilité des données</label><select id="sen"><option value="0">Faible (publiques)</option><option value="1" selected>Moyenne (internes)</option><option value="2">Élevée (clients, RH, finances)</option></select></div>
<div><label>Budget envisagé</label><select id="bud"><option>Bénévolat / projet étudiant</option><option>Moins de 1 000 €</option><option>1 000 – 5 000 €</option><option>Plus de 5 000 €</option></select></div>
</div>
<label>Échéance souhaitée</label><select id="del"><option>Dès que possible</option><option>Sous 1 mois</option><option>Sous 3 mois</option><option>Pas de contrainte</option></select>
<label>Autre besoin ou précision</label><textarea id="lib"></textarea>
</div>

<div class="step hide" data-s="3" id="resu"></div>

<div class="nav"><button class="s" id="prev" onclick="go(-1)">Retour</button><button class="p" id="next" onclick="go(1)">Continuer</button></div>
</section>

<footer>Projet ESCP AI Society · Les estimations sont indicatives et ne remplacent pas un audit approfondi.</footer>
</div>

<script>
const ASSO_EMAIL="contact@escp-ia.example"; // à remplacer par l'adresse de l'association
const ENDPOINT="https://script.google.com/macros/s/AKfycby3nvVqyLHunfVDSI9xWzxI1yo71i-UN1L3ahZIK4F6eOcBPFwYQ9ZonVlxIAUKU7_5Kg/exec"; // URL du script Google Apps Script (voir apps_script.gs) : active l'enregistrement automatique des audits
const T=[
["Support client & FAQ","Réponses aux emails, chat, tickets",78,"Chatbot IA branché sur votre base de connaissances"],
["Documents, saisie & comptabilité","Factures, contrats, rapprochements, formulaires",82,"Extraction automatique (OCR + LLM) et rapprochements vers vos outils"],
["Veille & analyse de données","Veille marché, reporting, tableaux de bord",78,"Agent de veille et tableaux de bord automatiques"],
["Contenus, marketing & traduction","Posts, newsletters, fiches produit, traductions",76,"Génération assistée avec charte éditoriale et relecture ciblée"],
["Prospection & qualification de leads","Listes, relances, scoring",68,"Enrichissement + séquences d'emails personnalisées"],
["Recrutement & tri de candidatures","Présélection CV, planification d'entretiens",55,"Pré-tri assisté, décision finale humaine"],
["Planification & tâches administratives","Agenda, comptes rendus, courriers",80,"Assistant de transcription et de planification"],
["Formation des équipes à l'IA","Prise en main des outils, bonnes pratiques, usages par métier",30,"Atelier animé par des membres de l'association"],
["Conseil stratégique IA","Cadrage, choix d'outils, feuille de route",35,"Atelier de cadrage avec des membres de l'association"],
["Autre besoin","Une tâche qui ne figure pas dans la liste",60,"Étude de faisabilité avec l'association"]];
let s=0;const N=4,names=["Entreprise","Tâches","Contexte","Résultats"];
const tk=document.getElementById('tasks');
T.forEach((t,i)=>{tk.insertAdjacentHTML('beforeend',`<div class="task" id="t${i}"><label><input type="checkbox" onchange="document.getElementById('t${i}').classList.toggle('on',this.checked)"><span>${t[0]}<small>${t[1]}</small></span></label>
<div class="det">${i===T.length-1?`<div style="grid-column:1/-1"><label>Décrivez votre besoin</label><input type="text" id="o${i}" placeholder="Ex : tri des retours clients, génération de devis…"></div>`:''}<div><label>Heures par semaine</label><input type="number" min="1" max="80" value="5" id="h${i}" style="width:100%;padding:8px;border:1px solid var(--bd);border-radius:8px;background:rgba(3,10,36,.7);color:var(--tx);font:inherit"></div>
<div><label>Caractère répétitif</label><select id="r${i}"><option value="1">Très variable</option><option value="2" selected>Assez répétitif</option><option value="3">Très répétitif</option></select></div></div></div>`)});
const $=id=>document.getElementById(id);
function show(){document.querySelectorAll('.step').forEach(e=>e.classList.toggle('hide',+e.dataset.s!==s));
$('pb').style.width=((s+1)/N*100)+'%';$('st').textContent=`Étape ${s+1}/${N} · ${names[s]}`;
$('prev').style.visibility=s?'visible':'hidden';$('next').style.display=s===N-1?'none':'';
$('next').textContent=s===N-2?'Voir mon diagnostic':'Continuer'}
function go(d){
if(d>0){if(s===0&&(!$('nom').value.trim()||!/\S+@\S+\.\S+/.test($('mail').value)||!$('cons').checked)){alert("Merci d'indiquer le nom de l'entreprise, un email valide et d'accepter la transmission de vos réponses.");return}
if(s===1&&!document.querySelector('.task.on')){alert("Sélectionnez au moins une tâche.");return}
if(s===2)compute()}
s=Math.max(0,Math.min(N-1,s+d));show();$('audit').scrollIntoView({behavior:'smooth'})}
let SUM="";
function compute(){
const sen=+$('sen').value;let rows=[],tot=0,saved=0;
T.forEach((t,i)=>{if(!$('t'+i).classList.contains('on'))return;
const h=Math.max(1,+$('h'+i).value||1),r=+$('r'+i).value;
let p=t[2]+(r-2)*8-sen*(t[2]>50?6:0);p=Math.max(10,Math.min(97,Math.round(p)));
const g=Math.round(h*p/100*0.8*10)/10;tot+=h;saved+=g;const cu=i===T.length-1?$('o'+i).value.replace(/[<>]/g,'').trim():'';rows.push({n:cu?'Autre : '+cu:t[0],h,p,g,a:t[3]})});
rows.sort((a,b)=>b.g-a.g);
const yr=Math.round(saved*46);
const mode=p=>p>=70?['Automatisation IA','a']:p>=45?['IA + validation humaine','']:['Accompagnement expert','c'];
let html=`<h2>Votre diagnostic</h2><p class="sub">${$('nom').value} · tâches classées par temps récupérable.</p>
<div class="kp"><div><b>${tot} h</b><span>passées / semaine</span></div><div><b>${Math.round(saved*10)/10} h</b><span>récupérables / semaine</span></div><div><b>${yr} h</b><span>gain annuel estimé</span></div></div>`;
rows.forEach((r,i)=>{const m=mode(r.p);html+=`<div class="res"><h3><span>${i+1}. ${r.n}</span><span class="tag ${m[1]}">${m[0]}</span></h3><div class="sc"><i style="width:${r.p}%"></i></div><p>Potentiel ${r.p}% · ${r.h} h/sem → environ ${r.g} h gagnées. Piste : ${r.a}.</p></div>`});
if(sen===2)html+=`<div class="note">Données sensibles : privilégier un hébergement européen ou local, une anonymisation en amont et une validation RGPD avant tout déploiement.</div>`;
const ia=+$('ia').value;html+=`<div class="note">${ia===0?"Première démarche IA : nous recommandons de commencer par une tâche pilote à fort potentiel, pour obtenir un gain rapide et mesurable.":ia===1?"Vous avez déjà testé l'IA : l'enjeu est de passer des essais ponctuels à un usage structuré, avec des processus et des règles communes.":ia===2?"Votre équipe utilise déjà l'IA : formalisez les bons usages et automatisez les tâches les plus répétitives.":"Vous avez déjà de la maturité IA : l'accompagnement portera sur l'extension à d'autres processus et l'optimisation de l'existant."}</div>`;
html+=`<div class="nav" style="flex-wrap:wrap"><button class="p" onclick="sendM()">Envoyer à l'association</button><button class="s" onclick="cp()">Copier le résumé</button><button class="s" onclick="window.print()">Imprimer</button></div>`;
$('resu').innerHTML=html;save(rows,tot,saved,yr,sen);
SUM=`AUDIT D'EXTERNALISATION · ${$('nom').value}\nSecteur : ${$('sec').value} · Taille : ${$('tai').value}\nContact : ${$('mail').value}\nOutils : ${$('out').value||'n/c'}\nUsage de l'IA : ${$('ia').selectedOptions[0].text}${$('iau').value?' ('+$('iau').value+')':''}\nBudget : ${$('bud').value} · Échéance : ${$('del').value}\nSensibilité des données : ${['faible','moyenne','élevée'][sen]}\n\nTÂCHES (par priorité)\n`+rows.map((r,i)=>`${i+1}. ${r.n} : ${r.h} h/sem, potentiel ${r.p}%, ~${r.g} h gagnées. ${r.a}`).join('\n')+`\n\nGain estimé : ${Math.round(saved*10)/10} h/sem (~${yr} h/an)\nPrécisions : ${$('lib').value||'aucune'}`}
async function save(rows,tot,saved,yr,sen){
if(!ENDPOINT)return;
document.querySelector('#resu .nav').insertAdjacentHTML('beforebegin','<div class="note" id="sv">Transmission de votre audit…</div>');
const rec={date:new Date().toISOString(),entreprise:$('nom').value,secteur:$('sec').value,taille:$('tai').value,email:$('mail').value,outils:$('out').value,usageIA:$('ia').selectedOptions[0].text,detailIA:$('iau').value,sensibilite:['faible','moyenne','élevée'][sen],budget:$('bud').value,echeance:$('del').value,precisions:$('lib').value,taches:rows.map((r,i)=>`${i+1}. ${r.n} (${r.h} h/sem, potentiel ${r.p}%)`).join(' | '),heures:tot,gagnees:Math.round(saved*10)/10,annuel:yr};
const ko="Envoi automatique impossible : utilisez le bouton « Envoyer à l'association ».";
try{const r=await fetch(ENDPOINT,{method:'POST',headers:{'Content-Type':'text/plain;charset=utf-8'},body:JSON.stringify(rec)});const j=await r.json();$('sv').textContent=j.ok?"Votre audit a bien été transmis à l'association. Nous vous recontacterons.":ko}catch(e){$('sv').textContent=ko}}
function sendM(){location.href=`mailto:${ASSO_EMAIL}?subject=${encodeURIComponent("Audit ESCP AI · "+$('nom').value)}&body=${encodeURIComponent(SUM)}`}
function cp(){try{navigator.clipboard.writeText(SUM).then(()=>alert('Résumé copié.'),()=>prompt('Copiez le résumé :',SUM))}catch(e){prompt('Copiez le résumé :',SUM)}}
show();
</script>
</body>
</html>
