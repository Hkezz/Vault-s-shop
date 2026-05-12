<!DOCTYPE html>
<html lang="fr">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Vault's shop</title>
<style>


</style>
</head>
<body>

<div class="topbar">
  <div class="tl">
    <div class="li">☣️</div>
    <span class="lt">Vault's shop<span class="dot"></span></span>
  </div>
  <button class="ob" onclick="openO()">📋 Commander</button>
</div>

<div class="tabs">
  <div class="tab tm" onclick="sw('mil',this)">🪖 Militaire</div>
  <div class="tab"    onclick="sw('merc',this)">💀 Mercenaire</div>
  <div class="tab"    onclick="sw('veh',this)">🚗 Véhicules</div>
</div>

<!-- MIL -->
<div class="panel active" id="p-mil">
  <div class="sub"> Armes</div>
  <div class="grid">
    <div class="card cm"><div class="ia am"><img src="https://cdn.restoremonarchy.com/unturned/assets/california-2/items/645c87c8d12d4bdf8440e1c98953d7c3.webp" onerror="this.classList.add('err')"><span class="tag tm2">MIL</span></div><div class="cb"><div class="cn">Tensor</div><div class="sts"><span class="st">SMG</span><span class="st">30 rds</span><span class="st">200m</span></div><div class="prs"><div class="pr"><span class="pl">Basique</span><span class="pv pm">500 $</span></div><div class="pr"><span class="pl">Équipé</span><span class="pv pm">750 $</span></div></div></div></div>
    <div class="card cm"><div class="ia am"><img src="https://cdn.restoremonarchy.com/unturned/assets/california-2/items/f1f411eaabe74d148dd11e1744651bc2.webp" onerror="this.classList.add('err')"><span class="tag tm2">MIL</span></div><div class="cb"><div class="cn">Porto</div><div class="sts"><span class="st">AR</span><span class="st">30 rds</span><span class="st">550m</span></div><div class="prs"><div class="pr"><span class="pl">Basique</span><span class="pv pm">750 $</span></div><div class="pr"><span class="pl">Équipé</span><span class="pv pm">1 000 $</span></div></div></div></div>
    <div class="card cm"><div class="ia am"><img src="https://cdn.restoremonarchy.com/unturned/assets/california-2/items/5f03c95aea2e456facc5dacca96acc3e.webp" onerror="this.classList.add('err')"><span class="tag tm2">MIL</span></div><div class="cb"><div class="cn">Quicksilver</div><div class="sts"><span class="st">SMG</span><span class="st">30 rds</span><span class="st">250m</span></div><div class="prs"><div class="pr"><span class="pl">Basique</span><span class="pv pm">500 $</span></div><div class="pr"><span class="pl">Équipé</span><span class="pv pm">750 $</span></div></div></div></div>
    <div class="card cm"><div class="ia am"><img src="https://cdn.restoremonarchy.com/unturned/assets/california-2/items/559808a689534181b76039fa0f1db6e3.webp" onerror="this.classList.add('err')"><span class="tag tm2">MIL</span></div><div class="cb"><div class="cn">Raven</div><div class="sts"><span class="st">Sniper</span><span class="st">5 rds</span><span class="st">825m</span></div><div class="prs"><div class="pr"><span class="pl">Basique</span><span class="pv pm">1 500 $</span></div><div class="pr"><span class="pl">Équipé</span><span class="pv pm">1 750 $</span></div></div></div></div>
    <div class="card cm"><div class="ia am"><img src="https://cdn.restoremonarchy.com/unturned/assets/california-2/items/cae8950860fb4f269e40b6495c088022.webp" onerror="this.classList.add('err')"><span class="tag tm2">MIL</span></div><div class="cb"><div class="cn">Romeo</div><div class="sts"><span class="st">Pistolet</span><span class="st">21 rds</span><span class="st">210m</span></div><div class="prs"><div class="pr"><span class="pl">Basique</span><span class="pv pm">500 $</span></div><div class="pr"><span class="pl">Équipé</span><span class="pv pm">750 $</span></div></div></div></div>
  </div>
  <div class="sub"> Tenues &amp; Protection</div>
  <div class="grid">
    <div class="card cm"><div class="ia am"><img src="C:\Users\prieu\Desktop\Serv unturned\Images\Riot Helmet.png" onerror="this.classList.add('err')"><span class="tag tm2">MIL</span></div><div class="cb"><div class="cn">Riot Helmet</div><div class="prs"><div class="pr"><span class="pl">Prix</span><span class="pv pm">2 000 $</span></div></div></div></div>
    <div class="card cm"><div class="ia am"><img src="C:\Users\prieu\Desktop\Serv unturned\Images\Riot Top.png" onerror="this.classList.add('err')"><span class="tag tm2">MIL</span></div><div class="cb"><div class="cn">Riot Top</div><div class="prs"><div class="pr"><span class="pl">Prix</span><span class="pv pm">2 000 $</span></div></div></div></div>
    <div class="card cm"><div class="ia am"><img src="C:\Users\prieu\Desktop\Serv unturned\Images\Riot Bottom.png" onerror="this.classList.add('err')"><span class="tag tm2">MIL</span></div><div class="cb"><div class="cn">Riot Bottom</div><div class="prs"><div class="pr"><span class="pl">Prix</span><span class="pv pm">2 000 $</span></div></div></div></div>
    <div class="card cm"><div class="ia am"><img src="C:\Users\prieu\Desktop\Serv unturned\Images\Swat Carrying Rig.png" onerror="this.classList.add('err')"><span class="tag tm2">MIL</span></div><div class="cb"><div class="cn">SWAT Carrying Rig</div><div class="prs"><div class="pr"><span class="pl">Prix</span><span class="pv pm">1 000 $</span></div></div></div></div>
    <div class="card cm"><div class="ia am"><img src="C:\Users\prieu\Desktop\Serv unturned\Images\Military Nightvision.png" onerror="this.classList.add('err')"><span class="tag tm2">MIL</span></div><div class="cb"><div class="cn">Military Nightvision</div><div class="prs"><div class="pr"><span class="pl">Prix</span><span class="pv pm">2 000 $</span></div></div></div></div>
    <div class="card cm"><div class="ia am"><img src="C:\Users\prieu\Desktop\Serv unturned\Images\Military Rig.png" onerror="this.classList.add('err')"><span class="tag tm2">MIL</span></div><div class="cb"><div class="cn">Full Military Suit</div><div class="prs"><div class="pr"><span class="pl">Prix</span><span class="pv pm">2 500 $</span></div></div></div></div>
    <div class="card cm"><div class="ia am"><img src="C:\Users\prieu\Desktop\Serv unturned\Images\Ghillie Hood.png" onerror="this.classList.add('err')"><span class="tag tm2">MIL</span></div><div class="cb"><div class="cn">Full Ghillie Suit</div><div class="prs"><div class="pr"><span class="pl">Prix</span><span class="pv pm">5 000 $</span></div></div></div></div>
  </div>
</div>

<!-- MERC -->
<div class="panel" id="p-merc">
  <div class="sub"> Armes</div>
  <div class="grid"> 
    <div class="card cc"><div class="ia ac"><img src="https://cdn.restoremonarchy.com/unturned/assets/california-2/items/041b20d8e8454a0ab9a2f1198d96bae0.webp" onerror="this.classList.add('err')"><span class="fb">🔫</span><span class="tag tc2">MERC</span></div><div class="cb"><div class="cn">Umbra</div><div class="sts"><span class="st">AR</span><span class="st">30 rds</span><span class="st">550m</span></div><div class="prs"><div class="pr"><span class="pl">Basique</span><span class="pv pc">1 500 $</span></div><div class="pr"><span class="pl">Équipé</span><span class="pv pc">1 750 $</span></div></div></div></div>
    <div class="card cc"><div class="ia ac"><img src="https://cdn.restoremonarchy.com/unturned/assets/california-2/items/8d1b9d16dc504345a4c298af7c7b13de.webp" onerror="this.classList.add('err')"><span class="fb">🔫</span><span class="tag tc2">MERC</span></div><div class="cb"><div class="cn">Rebel</div><div class="sts"><span class="st">AR</span><span class="st">30 rds</span><span class="st">525m</span></div><div class="prs"><div class="pr"><span class="pl">Basique</span><span class="pv pc">750 $</span></div><div class="pr"><span class="pl">Équipé</span><span class="pv pc">1 000 $</span></div></div></div></div>
    <div class="card cc"><div class="ia ac"><img src="https://cdn.restoremonarchy.com/unturned/assets/california-2/items/126305c0ee03456989cb5cf5a123fda1.webp" onerror="this.classList.add('err')"><span class="fb">🔫</span><span class="tag tc2">MERC</span></div><div class="cb"><div class="cn">Vonya</div><div class="sts"><span class="st">Shotgun</span><span class="st">7 rds</span><span class="st">35m</span></div><div class="prs"><div class="pr"><span class="pl">Basique</span><span class="pv pc">1 500 $</span></div><div class="pr"><span class="pl">Équipé</span><span class="pv pc">1 750 $</span></div></div></div></div>
    <div class="card cc"><div class="ia ac"><img src="https://cdn.restoremonarchy.com/unturned/assets/california-2/items/2fcf38c6c0c74ecbb3693e7da131640d.webp" onerror="this.classList.add('err')"><span class="fb">🔫</span><span class="tag tc2">MERC</span></div><div class="cb"><div class="cn">Dnipro</div><div class="sts"><span class="st">AR</span><span class="st">30 rds</span><span class="st">600m</span></div><div class="prs"><div class="pr"><span class="pl">Basique</span><span class="pv pc">750 $</span></div><div class="pr"><span class="pl">Équipé</span><span class="pv pc">1 000 $</span></div></div></div></div>
    <div class="card cc"><div class="ia ac"><img src="https://cdn.restoremonarchy.com/unturned/assets/california-2/items/186c96b5fa724b9e8897d9b8aff18aa5.webp" onerror="this.classList.add('err')"><span class="fb">🎯</span><span class="tag tc2">MERC</span></div><div class="cb"><div class="cn">Sokol</div><div class="sts"><span class="st">Sniper</span><span class="st">10 rds</span><span class="st">550m</span></div><div class="prs"><div class="pr"><span class="pl">Basique</span><span class="pv pc">1 500 $</span></div><div class="pr"><span class="pl">Équipé</span><span class="pv pc">1 750 $</span></div></div></div></div>
    <div class="card cc"><div class="ia ac"><img src="https://cdn.restoremonarchy.com/unturned/assets/california-2/items/b149e0475a6c448d954879bfaf94c4fa.webp" onerror="this.classList.add('err')"><span class="fb">🎯</span><span class="tag tc2">MERC</span></div><div class="cb"><div class="cn">Phantom</div><div class="sts"><span class="st">Sniper</span><span class="st">20 rds</span><span class="st">550m</span></div><div class="prs"><div class="pr"><span class="pl">Basique</span><span class="pv pc">1 500 $</span></div><div class="pr"><span class="pl">Équipé</span><span class="pv pc">1 750 $</span></div></div></div></div>
    <div class="card cc"><div class="ia ac"><img src="https://cdn.restoremonarchy.com/unturned/assets/california-2/items/27332701923f4732b4ee97cea1e23674.webp" onerror="this.classList.add('err')"><span class="fb">💥</span><span class="tag tc2">MERC</span></div><div class="cb"><div class="cn">Trident</div><div class="sts"><span class="st">Lance-gren.</span><span class="st">3 rds</span></div><div class="prs"><div class="pr"><span class="pl">Basique</span><span class="pv pc">1 500 $</span></div><div class="pr"><span class="pl">Équipé</span><span class="pv pc">1 750 $</span></div></div></div></div>
    <div class="card cc"><div class="ia ac"><img src="https://cdn.restoremonarchy.com/unturned/assets/california-2/items/8fad3a31b1024d1ba1e82c2dff08b25f.webp" onerror="this.classList.add('err')"><span class="fb">💥</span><span class="tag tc2">MERC</span></div><div class="cb"><div class="cn">Koshmar</div><div class="sts"><span class="st">Shotgun</span><span class="st">4 rds</span><span class="st">400m</span></div><div class="prs"><div class="pr"><span class="pl">Basique</span><span class="pv pc">1 500 $</span></div><div class="pr"><span class="pl">Équipé</span><span class="pv pc">1 750 $</span></div></div></div></div>
    <div class="card cg"><div class="ia ag"><img src="https://cdn.restoremonarchy.com/unturned/assets/california-2/items/ce5a7249f01a42c0908c9adf81083ba3.webp" onerror="this.classList.add('err')"><span class="fb">⭐</span><span class="tag tg2">RARE</span></div><div class="cb"><div class="cn gn">Golden Palmov</div><div class="sts"><span class="st">AR Dorée</span><span class="st">30 rds</span><span class="st">525m</span></div><div class="prs"><div class="pr"><span class="pl">Basique</span><span class="pv pg">4 000 $</span></div><div class="pr"><span class="pl">Équipé</span><span class="pv pg">4 250 $</span></div></div></div></div>
  </div>
  <div class="sub"> Tenues &amp; Équipements</div>
  <div class="grid">
    <div class="card cc"><div class="ia ac"><img src="C:\Users\prieu\Desktop\Serv unturned\Images\Mercenary Alicepack.png" onerror="this.classList.add('err')"><span class="tag tc2">MERC</span></div><div class="cb"><div class="cn">Merc. Alicepack</div><div class="prs"><div class="pr"><span class="pl">Prix</span><span class="pv pc">3 000 $</span></div></div></div></div>
    <div class="card cc"><div class="ia ac"><img src="C:\Users\prieu\Desktop\Serv unturned\Images\Mercenary Rucksack.png" onerror="this.classList.add('err')"><span class="tag tc2">MERC</span></div><div class="cb"><div class="cn">Merc. Rucksack</div><div class="prs"><div class="pr"><span class="pl">Prix</span><span class="pv pc">2 000 $</span></div></div></div></div>
    <div class="card cc"><div class="ia ac"><img src="C:\Users\prieu\Desktop\Serv unturned\Images\Advanced Mercenary Top.png" onerror="this.classList.add('err')"><span class="tag tc2">MERC</span></div><div class="cb"><div class="cn">Adv. Merc. Top</div><div class="prs"><div class="pr"><span class="pl">Prix</span><span class="pv pc">2 000 $</span></div></div></div></div>
    <div class="card cc"><div class="ia ac"><img src="C:\Users\prieu\Desktop\Serv unturned\Images\Advanced Mercenary Bottom.png" onerror="this.classList.add('err')"><span class="tag tc2">MERC</span></div><div class="cb"><div class="cn">Adv. Merc. Bottom</div><div class="prs"><div class="pr"><span class="pl">Prix</span><span class="pv pc">2 000 $</span></div></div></div></div>
    <div class="card cc"><div class="ia ac"><img src="C:\Users\prieu\Desktop\Serv unturned\Images\Mercenary Helmet.png" onerror="this.classList.add('err')"><span class="tag tc2">MERC</span></div><div class="cb"><div class="cn">Merc. Helmet</div><div class="prs"><div class="pr"><span class="pl">Prix</span><span class="pv pc">1 000 $</span></div></div></div></div>
    <div class="card cc"><div class="ia ac"><img src="C:\Users\prieu\Desktop\Serv unturned\Images\Mercenary Rig.png" onerror="this.classList.add('err')"><span class="tag tc2">MERC</span></div><div class="cb"><div class="cn">Merc. Carrying Rig</div><div class="prs"><div class="pr"><span class="pl">Prix</span><span class="pv pc">1 000 $</span></div></div></div></div>
  </div>
  <div class="sub"> Divers</div>
  <div class="grid">
    <div class="card co"><div class="ia ao"><img src="C:\Users\prieu\Desktop\Serv unturned\Images\Grenade Bundle.png" onerror="this.classList.add('err')"><span class="tag to2">UTIL</span></div><div class="cb"><div class="cn">Grenade Bundle</div><div class="prs"><div class="pr"><span class="pl">Prix</span><span class="pv pg">500 $</span></div></div></div></div>
    <div class="card co"><div class="ia ao"><img src="C:\Users\prieu\Desktop\Serv unturned\Images\Light Hostile Sentry.png" onerror="this.classList.add('err')"><span class="tag to2">UTIL</span></div><div class="cb"><div class="cn">Sentry</div><div class="prs"><div class="pr"><span class="pl">Prix</span><span class="pv pg">1 000 $</span></div></div></div></div>
    <div class="card co"><div class="ia ao"><img src="C:\Users\prieu\Desktop\Serv unturned\Images\MRE.png" onerror="this.classList.add('err')"><span class="tag to2">UTIL</span></div><div class="cb"><div class="cn">MRE</div><div class="prs"><div class="pr"><span class="pl">Prix</span><span class="pv pg">500 $</span></div></div></div></div>
  </div>
</div>

<!-- VEH -->
<div class="panel" id="p-veh">
  <div class="empty"><div style="font-size:40px">🚧</div><h3>Réapprovisionnement en cours</h3><p>Contactez le vendeur pour les commandes spéciales.</p></div>
</div>

<footer class="ftr"><span>Vault's shop — Saute Dupont — California 2 Roleplay</span><span>Stock soumis à dispo.</span></footer>

<!-- MODAL -->
<div class="ov" id="ov" onclick="if(event.target===this)closeO()">
<div class="mo">
  <div class="mh"><h2>📋 Bon de commande</h2><button class="cx" onclick="closeO()">✕</button></div>
  <div class="mb">
    <div class="ir">
      <div class="fg"><span class="fl">Pseudo in-game</span><input class="fi" type="text" placeholder="Votre nom…"></div>
      <div class="fg"><span class="fl">Faction / Groupe</span><input class="fi" type="text" placeholder="Ex: Vault…"></div>
    </div>
    <div class="os osm"> Militaire — Armes</div><div id="omw"></div>
    <div class="os osm"> Militaire — Tenues</div><div id="omg"></div>
    <div class="os osc"> Mercenaire — Armes</div><div id="ocw"></div>
    <div class="os osc"> Mercenaire — Tenues</div><div id="ocg"></div>
    <div class="os oso"> Divers</div><div id="odv"></div>
    <textarea class="nt" placeholder="Remarques, lieu de rendez-vous…"></textarea>
    <div class="tb"><span class="tbl">Total estimé</span><span class="tbv" id="tv">0 $</span></div>
  </div>
</div>
</div>

<script>
function sw(id,el){document.querySelectorAll('.panel').forEach(p=>p.classList.remove('active'));document.querySelectorAll('.tab').forEach(t=>t.className='tab');document.getElementById('p-'+id).classList.add('active');el.classList.add({mil:'tm',merc:'tc',veh:'tv'}[id])}
const CAT={'omw':[{n:'Tensor',b:500,e:750,h:1},{n:'Porto',b:750,e:1000,h:1},{n:'Quicksilver',b:500,e:750,h:1},{n:'Raven',b:1500,e:1750,h:1},{n:'Romeo',b:500,e:750,h:1}],'omg':[{n:'Riot Helmet',b:2000,h:0},{n:'Riot Top',b:2000,h:0},{n:'Riot Bottom',b:2000,h:0},{n:'SWAT Carrying Rig',b:1000,h:0},{n:'Military Nightvision',b:2000,h:0},{n:'Full Military Suit',b:2500,h:0},{n:'Full Ghillie Suit',b:5000,h:0}],'ocw':[{n:'Umbra',b:1500,e:1750,h:1},{n:'Rebel',b:750,e:1000,h:1},{n:'Vonya',b:1500,e:1750,h:1},{n:'Dnipro',b:750,e:1000,h:1},{n:'Sokol',b:1500,e:1750,h:1},{n:'Phantom',b:1500,e:1750,h:1},{n:'Trident',b:1500,e:1750,h:1},{n:'Koshmar',b:1500,e:1750,h:1},{n:'Golden Palmov',b:4000,e:4250,h:1,g:1}],'ocg':[{n:'Merc. Alicepack',b:3000,h:0},{n:'Merc. Rucksack',b:2000,h:0},{n:'Adv. Merc. Top',b:2000,h:0},{n:'Adv. Merc. Bottom',b:2000,h:0},{n:'Merc. Helmet',b:1000,h:0},{n:'Merc. Carrying Rig',b:1000,h:0}],'odv':[{n:'Grenade Bundle',b:500,h:0},{n:'Sentry',b:1000,h:0},{n:'MRE',b:500,h:0}]};
const SC={'omw':'sm','omg':'sm','ocw':'sc','ocg':'sc','odv':'sg'};
const ST={};
function gi(k){const p=k.split('-');const i=parseInt(p.pop());return CAT[p.join('-')][i]}
function rp(k){const it=gi(k);const s=ST[k];const u=(it.h&&s.eq)?it.e:it.b;document.getElementById('ip-'+k).textContent=(u*s.qty).toLocaleString('fr-FR')+' $'}
function ct(){let t=0;document.querySelectorAll('.irow.sel').forEach(r=>{const k=r.dataset.k;const it=gi(k);const s=ST[k];t+=((it.h&&s.eq)?it.e:it.b)*s.qty});document.getElementById('tv').textContent=t.toLocaleString('fr-FR')+' $'}
function build(){Object.entries(CAT).forEach(([sec,items])=>{const c=document.getElementById(sec);items.forEach((it,i)=>{const k=sec+'-'+i;ST[k]={qty:1,eq:false};const r=document.createElement('div');r.className='irow';r.dataset.k=k;r.dataset.sc=SC[sec];r.innerHTML=`<div class="ck"></div><span class="iname${it.g?' gn':''}">${it.n}</span>${it.h?`<div class="ew"><span class="eq on" onclick="se(event,'${k}',0)">Basique</span><span class="eq" onclick="se(event,'${k}',1)">équipé</span></div>`:''}<div class="qw"><button class="qb" onclick="cq(event,'${k}',-1)">−</button><span class="qn" id="qn-${k}">1</span><button class="qb" onclick="cq(event,'${k}',1)">+</button></div><span class="ip" id="ip-${k}">${it.b.toLocaleString('fr-FR')} $</span>`;r.addEventListener('click',e=>{if(e.target.classList.contains('qb')||e.target.classList.contains('eq'))return;const sel=!r.classList.contains('sel');r.classList.toggle('sel',sel);r.classList.toggle(SC[sec],sel);rp(k);ct()});c.appendChild(r)})})}
function se(e,k,w){e.stopPropagation();ST[k].eq=!!w;const r=document.querySelector(`[data-k="${k}"]`);r.querySelectorAll('.eq').forEach((b,i)=>b.classList.toggle('on',i===w));rp(k);ct()}
function cq(e,k,d){e.stopPropagation();ST[k].qty=Math.max(1,ST[k].qty+d);document.getElementById('qn-'+k).textContent=ST[k].qty;rp(k);ct()}
function openO(){document.getElementById('ov').classList.add('open');document.body.style.overflow='hidden'}
function closeO(){document.getElementById('ov').classList.remove('open');document.body.style.overflow=''}
build();
</script>
</body>
</html>
