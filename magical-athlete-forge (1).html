<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Magical Athlete Racer Forge</title>
<link href="https://fonts.googleapis.com/css2?family=Bangers&family=Nunito:wght@700;800&display=swap" rel="stylesheet">
<style>
*, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }
:root {
  --red:    #D42B1A;
  --yellow: #FFE01B;
  --white:  #FFFEF0;
  --black:  #111111;
  --blue:   #1A5FD4;
  --green:  #1DAA3C;
  --purple: #7B2FD4;
  --orange: #F07020;
  --pink:   #E01A8C;
  --teal:   #0A9688;
  --coin:   #D4A017;
  --ink: 3px solid var(--black);
  --ink4: 4px solid var(--black);
}
body {
  font-family: 'Nunito', sans-serif;
  background: var(--red);
  background-image: radial-gradient(circle, rgba(0,0,0,0.08) 1px, transparent 1px);
  background-size: 18px 18px;
  padding: 24px 20px 40px;
  min-height: 100vh;
}
h1 {
  font-family: 'Bangers', cursive;
  font-size: clamp(36px, 7vw, 68px);
  letter-spacing: 3px;
  color: var(--yellow);
  text-shadow: 3px 3px 0 var(--black), -2px -2px 0 var(--black), 2px -2px 0 var(--black), -2px 2px 0 var(--black), 5px 6px 0 rgba(0,0,0,0.4);
  text-align: center; margin-bottom: 8px; line-height: 1; text-transform: uppercase;
}
.subtitle {
  font-family: 'Bangers', cursive; font-size: 20px; color: var(--white);
  text-align: center; letter-spacing: 2px; margin-bottom: 28px; text-shadow: 2px 2px 0 var(--black);
}
.grid { display: grid; grid-template-columns: 1fr 1fr; gap: 20px; max-width: 1120px; margin: auto; }
.econ-panel { max-width: 1120px; margin: 20px auto 0; }
@media (max-width: 700px) { .grid { grid-template-columns: 1fr; } }
.panel {
  background: var(--white); border: var(--ink4); border-radius: 14px;
  padding: 22px 20px; box-shadow: 6px 7px 0 var(--black);
}
.panel-title {
  font-family: 'Bangers', cursive; font-size: 28px; letter-spacing: 2px;
  color: var(--black); margin-bottom: 16px; display: flex; align-items: center; gap: 8px; text-transform: uppercase;
}
.field { margin-bottom: 14px; }
.field label { display: block; font-size: 12px; font-weight: 800; letter-spacing: 1.5px; text-transform: uppercase; color: var(--black); margin-bottom: 5px; }
.field input, .field textarea, .field select {
  width: 100%; padding: 9px 12px; border: var(--ink); border-radius: 8px;
  background: #FFF9E0; font-family: 'Nunito', sans-serif; font-size: 14px; font-weight: 700;
  color: var(--black); appearance: none; -webkit-appearance: none;
  box-shadow: 3px 3px 0 rgba(0,0,0,0.18); outline: none; transition: box-shadow 0.1s, transform 0.1s;
}
.field input:focus, .field textarea:focus, .field select:focus { box-shadow: 4px 4px 0 var(--black); transform: translate(-1px,-1px); }
.field textarea { min-height: 72px; resize: vertical; }
.select-wrap { position: relative; }
.select-wrap::after { content: '▼'; position: absolute; right: 12px; top: 50%; transform: translateY(-50%); font-size: 11px; pointer-events: none; color: var(--black); }
.btn-row { display: flex; gap: 12px; flex-wrap: wrap; margin-top: 18px; }
.btn {
  font-family: 'Bangers', cursive; font-size: 20px; letter-spacing: 1.5px;
  padding: 10px 22px; border: var(--ink4); border-radius: 10px; cursor: pointer;
  text-transform: uppercase; box-shadow: 4px 5px 0 var(--black); transition: transform 0.1s, box-shadow 0.1s;
  background: var(--yellow); color: var(--black);
}
.btn:hover { transform: translate(-2px,-2px); box-shadow: 6px 7px 0 var(--black); }
.btn:active { transform: translate(2px,2px); box-shadow: 2px 2px 0 var(--black); }
.btn.random { background: var(--green); color: var(--white); }
.output { min-height: 200px; }
.empty-state { display: flex; flex-direction: column; align-items: center; justify-content: center; min-height: 200px; text-align: center; gap: 10px; }
.empty-state .big-icon { font-size: 52px; }
.empty-state p { font-size: 15px; font-weight: 800; color: #888; text-transform: uppercase; letter-spacing: 1px; }
.racer-name { font-family: 'Bangers', cursive; font-size: 36px; letter-spacing: 2px; color: var(--black); text-transform: uppercase; margin-bottom: 6px; line-height: 1; }
.power-box { background: #EEF6FF; border: var(--ink); border-radius: 10px; padding: 10px 14px; margin-bottom: 16px; font-size: 14px; font-weight: 700; color: #333; box-shadow: 3px 3px 0 rgba(0,0,0,0.15); }
.badge-row { display: flex; flex-wrap: wrap; gap: 8px; margin-bottom: 18px; }
.badge { font-family: 'Bangers', cursive; font-size: 20px; letter-spacing: 1px; padding: 5px 16px; border: var(--ink); border-radius: 24px; box-shadow: 3px 3px 0 rgba(0,0,0,0.25); }
.badge.tier-S { background: var(--yellow); color: var(--black); }
.badge.tier-A { background: var(--orange); color: var(--white); }
.badge.tier-B { background: var(--blue);   color: var(--white); }
.badge.tier-C { background: var(--purple); color: var(--white); }
.badge.tier-D { background: #999;          color: var(--white); }
.badge.cost   { background: var(--coin);   color: var(--black); }
.badge.score  { background: var(--black);  color: var(--yellow); }
.badge.special { background: var(--pink);  color: var(--white); font-size:14px; padding:5px 12px; }
.section-head {
  font-family: 'Bangers', cursive; font-size: 18px; letter-spacing: 1.5px; text-transform: uppercase;
  margin: 14px 0 6px; color: var(--black); display: flex; align-items: center; gap: 6px;
}
.section-head::after { content: ''; flex: 1; height: 2px; background: var(--black); margin-left: 4px; }
.tag-row { display: flex; flex-wrap: wrap; gap: 6px; margin-bottom: 10px; }
.tag { font-size: 12px; font-weight: 800; padding: 4px 12px; border: 2.5px solid var(--black); border-radius: 20px; box-shadow: 2px 2px 0 rgba(0,0,0,0.2); letter-spacing: 0.5px; }
.tag.strong { background: var(--yellow); color: var(--black); }
.tag.weak   { background: var(--pink);   color: var(--white); }
.tag.none   { background: #ddd; color: #666; }
.warn-list { list-style: none; display: flex; flex-direction: column; gap: 6px; margin-bottom: 10px; }
.warn-list li { font-size: 13px; font-weight: 800; padding: 7px 12px; border: 2.5px solid var(--black); border-radius: 8px; box-shadow: 3px 3px 0 rgba(0,0,0,0.15); }
.warn-list li.warning    { background: #FFEECC; color: #8B4A00; }
.warn-list li.suggestion { background: #DDFFD8; color: #1A6B00; }
.warn-list li.none-item  { background: #F0F0F0; color: #888; }
.design-note { font-size: 12px; font-weight: 700; color: #888; font-style: italic; margin-top: 14px; padding-top: 10px; border-top: 2px dashed #ccc; }
.stat-grid { display: grid; grid-template-columns: repeat(4, 1fr); gap: 8px; margin-bottom: 16px; }
.stat-cell { background: var(--white); border: var(--ink); border-radius: 8px; padding: 6px 8px; text-align: center; box-shadow: 2px 3px 0 rgba(0,0,0,0.2); }
.stat-label { font-size: 9px; font-weight: 800; letter-spacing: 1px; text-transform: uppercase; color: #666; display: block; }
.stat-val { font-family: 'Bangers', cursive; font-size: 22px; color: var(--black); display: block; line-height: 1.2; }
.stat-val.v0 { color: #ccc; } .stat-val.v1 { color: var(--blue); } .stat-val.v2 { color: var(--orange); } .stat-val.v3 { color: var(--red); }

/* Economy section */
.econ-block {
  background: #FFF8DC; border: var(--ink4); border-radius: 12px;
  padding: 16px; margin-top: 14px; box-shadow: 4px 5px 0 var(--black);
}
.econ-block .econ-title {
  font-family: 'Bangers', cursive; font-size: 22px; letter-spacing: 2px;
  color: var(--black); margin-bottom: 12px; text-transform: uppercase;
  display: flex; align-items: center; gap: 6px;
}
.econ-grid { display: grid; grid-template-columns: 1fr 1fr; gap: 10px; margin-bottom: 12px; }
.econ-card {
  border: var(--ink); border-radius: 10px; padding: 10px 12px;
  text-align: center; box-shadow: 3px 3px 0 rgba(0,0,0,0.15);
}
.econ-card .ec-label { font-size: 10px; font-weight: 800; letter-spacing: 1.2px; text-transform: uppercase; color: #666; display: block; margin-bottom: 4px; }
.econ-card .ec-val { font-family: 'Bangers', cursive; font-size: 28px; line-height: 1; display: block; }
.econ-card .ec-sub { font-size: 11px; font-weight: 700; color: #888; display: block; margin-top: 2px; }
.ec-cost   { background: #FFF3B0; }
.ec-dur    { background: #D8F5D8; }
.ec-risk   { background: #FFE0E0; }
.ec-ev     { background: #E0EEFF; }
.dmg-bar { margin-top: 10px; }
.dmg-bar .dmg-label { font-size: 11px; font-weight: 800; letter-spacing: 1px; text-transform: uppercase; color: #555; margin-bottom: 5px; }
.dmg-track { display: flex; gap: 4px; align-items: center; }
.dmg-pip {
  width: 22px; height: 22px; border: 2.5px solid var(--black); border-radius: 50%;
  box-shadow: 2px 2px 0 rgba(0,0,0,0.15); flex-shrink: 0;
}
.dmg-pip.full { background: var(--red); }
.dmg-pip.empty { background: #ddd; }
.dmg-consequence {
  margin-top: 10px; padding: 8px 12px; border: 2.5px solid var(--black); border-radius: 8px;
  font-size: 13px; font-weight: 800; box-shadow: 3px 3px 0 rgba(0,0,0,0.12);
}

/* Preset picker */
.preset-bar { background: #FFF3CC; border: var(--ink); border-radius: 10px; padding: 12px 14px; margin-bottom: 16px; box-shadow: 3px 3px 0 rgba(0,0,0,0.15); }
.preset-bar label { display: block; font-size: 12px; font-weight: 800; letter-spacing: 1.5px; text-transform: uppercase; color: var(--black); margin-bottom: 6px; }
.preset-bar select { width: 100%; padding: 9px 12px; border: var(--ink); border-radius: 8px; background: var(--white); font-family: 'Nunito', sans-serif; font-size: 14px; font-weight: 700; color: var(--black); appearance: none; -webkit-appearance: none; box-shadow: 3px 3px 0 rgba(0,0,0,0.18); outline: none; }

/* Toggles */
.toggles-block { margin-bottom: 14px; background: #F4EEFF; border: var(--ink); border-radius: 10px; padding: 12px 14px; box-shadow: 3px 3px 0 rgba(0,0,0,0.12); }
.toggles-block .toggle-title { font-size: 12px; font-weight: 800; letter-spacing: 1.5px; text-transform: uppercase; color: var(--black); margin-bottom: 8px; }
.toggle-grid { display: grid; grid-template-columns: 1fr 1fr; gap: 6px; }
.toggle-item { display: flex; align-items: center; gap: 8px; cursor: pointer; padding: 6px 10px; border: 2.5px solid var(--black); border-radius: 8px; background: var(--white); box-shadow: 2px 2px 0 rgba(0,0,0,0.15); transition: transform 0.1s, box-shadow 0.1s; user-select: none; }
.toggle-item:hover { transform: translate(-1px,-1px); box-shadow: 3px 3px 0 rgba(0,0,0,0.2); }
.toggle-item input[type=checkbox] { display: none; }
.toggle-dot { width: 18px; height: 18px; border: 2.5px solid var(--black); border-radius: 4px; flex-shrink: 0; display: flex; align-items: center; justify-content: center; font-size: 12px; background: #eee; transition: background 0.1s; }
.toggle-item.checked .toggle-dot { background: var(--purple); color: var(--white); }
.toggle-item.checked { background: #EDE8FF; }
.toggle-label { font-size: 12px; font-weight: 800; line-height: 1.3; color: var(--black); }

/* Budget Planner */
.budget-planner { background: var(--white); border: var(--ink4); border-radius: 14px; padding: 22px 20px; box-shadow: 6px 7px 0 var(--black); }
.bp-grid { display: grid; grid-template-columns: 1fr 1fr 1fr; gap: 16px; }
@media (max-width: 800px) { .bp-grid { grid-template-columns: 1fr 1fr; } }
.bp-control { }
.bp-control label { display: block; font-size: 12px; font-weight: 800; letter-spacing: 1.5px; text-transform: uppercase; color: var(--black); margin-bottom: 6px; }
.bp-control input[type=range] {
  width: 100%; height: 6px; appearance: none; -webkit-appearance: none;
  background: #ddd; border-radius: 3px; border: 2px solid var(--black); outline: none;
}
.bp-control input[type=range]::-webkit-slider-thumb {
  appearance: none; width: 20px; height: 20px; border-radius: 50%;
  background: var(--yellow); border: 3px solid var(--black); cursor: pointer;
  box-shadow: 2px 2px 0 rgba(0,0,0,0.2);
}
.bp-val { font-family: 'Bangers', cursive; font-size: 20px; color: var(--black); margin-top: 4px; }
.bp-output { margin-top: 20px; }
.bp-result-grid { display: grid; grid-template-columns: repeat(4, 1fr); gap: 10px; margin-bottom: 16px; }
@media (max-width: 600px) { .bp-result-grid { grid-template-columns: 1fr 1fr; } }
.bp-card {
  border: var(--ink); border-radius: 10px; padding: 12px 10px;
  text-align: center; box-shadow: 3px 4px 0 rgba(0,0,0,0.2);
}
.bp-card .bpc-label { font-size: 10px; font-weight: 800; letter-spacing: 1px; text-transform: uppercase; color: #666; display: block; margin-bottom: 4px; }
.bp-card .bpc-val { font-family: 'Bangers', cursive; font-size: 32px; line-height: 1; display: block; }
.bp-card .bpc-sub { font-size: 11px; font-weight: 700; color: #888; margin-top: 2px; display: block; }
.bpc-coins   { background: #FFF3B0; }
.bpc-pool    { background: #E0EEFF; }
.bpc-risk    { background: #FFE0E0; }
.bpc-safe    { background: #D8F5D8; }
.tier-breakdown {
  background: #F9F9F9; border: var(--ink); border-radius: 10px;
  padding: 14px; box-shadow: 3px 3px 0 rgba(0,0,0,0.12);
}
.tier-breakdown .tb-title { font-family: 'Bangers', cursive; font-size: 18px; letter-spacing: 1px; text-transform: uppercase; margin-bottom: 10px; }
.tier-row { display: flex; align-items: center; gap: 10px; margin-bottom: 8px; }
.tier-dot { width: 28px; height: 28px; border: 3px solid var(--black); border-radius: 6px; display: flex; align-items: center; justify-content: center; font-family: 'Bangers', cursive; font-size: 16px; box-shadow: 2px 2px 0 rgba(0,0,0,0.2); flex-shrink: 0; }
.tier-dot.tS { background: var(--yellow); color: var(--black); }
.tier-dot.tA { background: var(--orange); color: var(--white); }
.tier-dot.tB { background: var(--blue);   color: var(--white); }
.tier-dot.tC { background: var(--purple); color: var(--white); }
.tier-dot.tD { background: #999;          color: var(--white); }
.tier-info { flex: 1; font-size: 13px; font-weight: 700; color: #333; }
.tier-info span { font-weight: 800; color: var(--black); }
.dmg-key { display: flex; gap: 8px; flex-wrap: wrap; margin-top: 14px; }
.dmg-key-item { font-size: 12px; font-weight: 800; padding: 5px 10px; border: 2px solid var(--black); border-radius: 16px; box-shadow: 2px 2px 0 rgba(0,0,0,0.12); }
.dmg-key-item.dmi1 { background: #D8F5D8; color: #145A14; }
.dmg-key-item.dmi2 { background: #FFF3B0; color: #7A6000; }
.dmg-key-item.dmi3 { background: #FFE0B0; color: #7A3500; }
.dmg-key-item.dmi4 { background: #FFD0D0; color: #8B0000; }
.dmg-key-item.dmi5 { background: #C0A0FF; color: #2A006B; }

/* Tier limit selector */
.tier-limit-block {
  margin-bottom: 14px;
  background: #F0F8FF;
  border: var(--ink);
  border-radius: 10px;
  padding: 12px 14px;
  box-shadow: 3px 3px 0 rgba(0,0,0,0.12);
}
.tier-limit-block .tl-title {
  font-size: 12px; font-weight: 800; letter-spacing: 1.5px;
  text-transform: uppercase; color: var(--black); margin-bottom: 8px;
}
.tier-btn-row { display: flex; gap: 6px; flex-wrap: wrap; }
.tier-btn {
  font-family: 'Bangers', cursive; font-size: 18px; letter-spacing: 1px;
  padding: 5px 16px; border: 2.5px solid var(--black); border-radius: 20px;
  cursor: pointer; background: #ddd; color: #555;
  box-shadow: 2px 3px 0 rgba(0,0,0,0.2); transition: transform 0.1s, box-shadow 0.1s;
  position: relative;
}
.tier-btn:hover { transform: translate(-1px,-1px); box-shadow: 3px 4px 0 rgba(0,0,0,0.25); }
.tier-btn:active { transform: translate(1px,1px); box-shadow: 1px 1px 0 rgba(0,0,0,0.2); }
.tier-btn.active { color: var(--black); box-shadow: 3px 4px 0 var(--black); }
.tier-btn.tb-any.active  { background: var(--white); }
.tier-btn.tb-S.active    { background: var(--yellow); }
.tier-btn.tb-A.active    { background: var(--orange); color: var(--white); }
.tier-btn.tb-B.active    { background: var(--blue);   color: var(--white); }
.tier-btn.tb-C.active    { background: var(--purple); color: var(--white); }
.tier-btn.tb-D.active    { background: #888;          color: var(--white); }
.tier-unofficial {
  font-size: 10px; font-weight: 800; letter-spacing: 0.5px;
  background: var(--red); color: var(--white);
  padding: 1px 5px; border-radius: 4px; border: 1.5px solid var(--black);
  vertical-align: middle; margin-left: 3px; display: inline-block; line-height: 1.4;
}
.tl-note {
  font-size: 11px; font-weight: 700; color: #888; margin-top: 8px;
  line-height: 1.4; display: none;
}
.tl-note.visible { display: block; }

/* Collapsible tuning section */
.collapse-header {
  display: flex; align-items: center; justify-content: space-between;
  cursor: pointer; user-select: none;
  padding: 10px 14px;
  background: #F5F0FF;
  border: var(--ink);
  border-radius: 10px;
  margin-bottom: 0;
  box-shadow: 3px 3px 0 rgba(0,0,0,0.12);
  transition: transform 0.1s, box-shadow 0.1s;
}
.collapse-header:hover { transform: translate(-1px,-1px); box-shadow: 4px 4px 0 rgba(0,0,0,0.18); }
.collapse-header:active { transform: translate(1px,1px); box-shadow: 2px 2px 0 rgba(0,0,0,0.12); }
.collapse-header .ch-label {
  font-family: 'Bangers', cursive; font-size: 18px; letter-spacing: 1.5px;
  text-transform: uppercase; color: var(--black); display: flex; align-items: center; gap: 8px;
}
.collapse-header .ch-summary {
  font-size: 11px; font-weight: 800; color: #888; text-transform: uppercase;
  letter-spacing: 0.5px; text-align: right; line-height: 1.4; max-width: 180px;
}
.collapse-arrow {
  font-size: 14px; color: var(--black); transition: transform 0.2s; flex-shrink: 0; margin-left: 10px;
}
.collapse-arrow.open { transform: rotate(180deg); }
.collapse-body {
  overflow: hidden;
  max-height: 0;
  transition: max-height 0.3s ease, margin-top 0.2s;
  margin-top: 0;
}
.collapse-body.open {
  max-height: 1000px;
  margin-top: 10px;
}
.collapse-inner { padding: 2px 0 4px; display: flex; flex-direction: column; gap: 10px; }
</style>
</head>
<body>

<h1>🏁 Magical Athlete</h1>
<p class="subtitle">⚡ Racer Power Forge ⚡</p>

<div class="grid">
<div class="panel">
  <div class="panel-title"><span>🛠</span> Build a Racer</div>
  <div class="field"><label>Name</label><input id="name" placeholder="e.g. The Slip"></div>
  <div class="field"><label>Power Description</label><textarea id="powerText" placeholder="When another racer passes me, they trip."></textarea></div>

  <div class="collapse-header" onclick="toggleTuning()" id="tuning-header">
    <div class="ch-label">⚙️ Tune stats</div>
    <div class="ch-summary" id="tuning-summary">All default — expand to adjust</div>
    <span class="collapse-arrow" id="tuning-arrow">▼</span>
  </div>
  <div class="collapse-body" id="tuning-body">
    <div class="collapse-inner">

      <div style="display:grid;grid-template-columns:1fr 1fr;gap:12px;">
        <div class="field"><label>Speed</label><div class="select-wrap"><select id="speed" onchange="updateTuningSummary()"><option value="0">0 – None</option><option value="1">1 – Minor</option><option value="2">2 – Strong</option><option value="3">3 – Explosive</option></select></div></div>
        <div class="field"><label>Control</label><div class="select-wrap"><select id="control" onchange="updateTuningSummary()"><option value="0">0 – None</option><option value="1">1 – Minor</option><option value="2">2 – Tactical</option><option value="3">3 – Game Warping</option></select></div></div>
        <div class="field"><label>Disruption</label><div class="select-wrap"><select id="disruption" onchange="updateTuningSummary()"><option value="0">0 – None</option><option value="1">1 – Annoying</option><option value="2">2 – Strong</option><option value="3">3 – Brutal</option></select></div></div>
        <div class="field"><label>Combo Potential</label><div class="select-wrap"><select id="combo" onchange="updateTuningSummary()"><option value="0">0 – Standalone</option><option value="1">1 – Some Synergy</option><option value="2">2 – Repeatable</option><option value="3">3 – Dangerous</option></select></div></div>
        <div class="field"><label>Variance / Chaos</label><div class="select-wrap"><select id="variance" onchange="updateTuningSummary()"><option value="0">0 – Stable</option><option value="1">1 – Mild</option><option value="2">2 – Swingy</option><option value="3">3 – Chaos Goblin</option></select></div></div>
        <div class="field"><label>Self Risk</label><div class="select-wrap"><select id="selfRisk" onchange="updateTuningSummary()"><option value="0">0 – Safe</option><option value="1">1 – Minor</option><option value="2">2 – Dangerous</option><option value="3">3 – Self Destructive</option></select></div></div>
        <div class="field"><label>Difficulty</label><div class="select-wrap"><select id="difficulty" onchange="updateTuningSummary()"><option value="0">0 – Easy</option><option value="1">1 – Medium</option><option value="2">2 – Tactical</option><option value="3">3 – Expert</option></select></div></div>
        <div class="field"><label>Frequency</label><div class="select-wrap"><select id="frequency" onchange="updateTuningSummary()"><option value="always">Always</option><option value="often">Often</option><option value="sometimes">Sometimes</option><option value="rarely">Rarely</option></select></div></div>
      </div>

      <div class="toggles-block" style="margin-bottom:0">
        <div class="toggle-title">🔮 Special mechanics</div>
        <div class="toggle-grid">
          <label class="toggle-item" id="tog-dice"  onclick="toggleCheck('altDice')"><input type="checkbox" id="altDice"><div class="toggle-dot" id="dot-altDice"></div><span class="toggle-label">Alternate dice (D12 / D20)</span></label>
          <label class="toggle-item" id="tog-elim"  onclick="toggleCheck('canElim')"><input type="checkbox" id="canElim"><div class="toggle-dot" id="dot-canElim"></div><span class="toggle-label">Can eliminate racers</span></label>
          <label class="toggle-item" id="tog-scale" onclick="toggleCheck('permScale')"><input type="checkbox" id="permScale"><div class="toggle-dot" id="dot-permScale"></div><span class="toggle-label">Permanently scales during race</span></label>
          <label class="toggle-item" id="tog-token" onclick="toggleCheck('mapTokens')"><input type="checkbox" id="mapTokens"><div class="toggle-dot" id="dot-mapTokens"></div><span class="toggle-label">Places tokens on the map</span></label>
        </div>
      </div>

      <div class="tier-limit-block" style="margin-bottom:0">
        <div class="tl-title">🎯 Limit random tier</div>
        <div class="tier-btn-row">
          <button class="tier-btn tb-any active" onclick="setTierLimit('any')">Any</button>
          <button class="tier-btn tb-D"          onclick="setTierLimit('D')">D</button>
          <button class="tier-btn tb-C"          onclick="setTierLimit('C')">C</button>
          <button class="tier-btn tb-B"          onclick="setTierLimit('B')">B</button>
          <button class="tier-btn tb-A"          onclick="setTierLimit('A')">A</button>
          <button class="tier-btn tb-S"          onclick="setTierLimit('S')">S <span class="tier-unofficial">unofficial</span></button>
        </div>
        <p class="tl-note" id="tl-note"></p>
      </div>

    </div>
  </div>

  <div class="btn-row">
    <button class="btn" onclick="analyzeRacer()">🔍 Analyze</button>
    <button class="btn random" onclick="generateRandomRacer()">🎲 Random Racer</button>
  </div>
</div>

<div class="panel">
  <div class="panel-title"><span>📊</span> Results</div>
  <div id="output" class="output">
    <div class="empty-state"><div class="big-icon">🏟️</div><p>Forge a racer to see results</p></div>
  </div>
</div>
</div>

<!-- Budget Planner -->
<div class="econ-panel">
<div class="budget-planner">
  <div class="panel-title"><span>💰</span> Budget Planner</div>
  <p style="font-size:13px;font-weight:700;color:#555;margin-bottom:16px;line-height:1.5;">
    This economy layer is a variant on top of the base game's snake draft. Instead of drafting for free, players spend coins to recruit racers — creating risk/reward tension around expensive high-tier picks.
  </p>
  <div class="bp-grid">
    <div class="bp-control">
      <label>Players <span id="lbl-players">4</span></label>
      <input type="range" min="2" max="6" value="4" id="sl-players" oninput="updatePlanner()">
    </div>
    <div class="bp-control">
      <label>Races <span id="lbl-races">4</span></label>
      <input type="range" min="2" max="8" value="4" id="sl-races" oninput="updatePlanner()">
    </div>
    <div class="bp-control">
      <label>Budget Tightness <span id="lbl-tight">Medium</span></label>
      <input type="range" min="1" max="5" value="3" id="sl-tight" oninput="updatePlanner()">
    </div>
  </div>

  <div class="bp-output" id="bp-output"></div>
</div>
</div>

<script>
// ─── DATA ───────────────────────────────────────────────────────────────────
const CORE = {
  theSlip:        { name:"The Slip",          speed:0,control:1,disruption:3,combo:0,variance:0,selfRisk:0,difficulty:0,frequency:"always",altDice:false,canElim:false,permScale:false,mapTokens:false, power:"When a racer passes me, they trip." },
  banana:         { name:"Banana",            speed:0,control:1,disruption:3,combo:0,variance:0,selfRisk:0,difficulty:0,frequency:"always",altDice:false,canElim:false,permScale:false,mapTokens:false, power:"I trip any racer that passes me." },
  rahRah:         { name:"Rah Rah",           speed:1,control:2,disruption:0,combo:1,variance:0,selfRisk:0,difficulty:1,frequency:"always",altDice:false,canElim:false,permScale:false,mapTokens:false, power:"At start of my turn, I can make last-place racers move 2. If I do, I move 1." },
  transmute:      { name:"Transmute 'N' Scoot",speed:2,control:1,disruption:0,combo:0,variance:0,selfRisk:0,difficulty:0,frequency:"sometimes",altDice:false,canElim:false,permScale:false,mapTokens:false, power:"When I roll a 1 or 2 for my main move, I can move 4 instead." },
  blowIt:         { name:"Blow It",           speed:3,control:1,disruption:0,combo:0,variance:1,selfRisk:0,difficulty:0,frequency:"always",altDice:false,canElim:false,permScale:false,mapTokens:false, power:"Before second corner: +2 to main move. On/after that corner: -1." },
  hoofwhack:      { name:"Hoofwhack",         speed:2,control:1,disruption:2,combo:0,variance:0,selfRisk:0,difficulty:0,frequency:"always",altDice:false,canElim:false,permScale:false,mapTokens:false, power:"When I pass a racer, they move -2." },
  gunk:           { name:"Gunk",              speed:0,control:2,disruption:3,combo:1,variance:0,selfRisk:0,difficulty:0,frequency:"always",altDice:false,canElim:false,permScale:false,mapTokens:false, power:"Other racers get -1 to their main move." },
  copycat:        { name:"Copy That",         speed:1,control:3,disruption:0,combo:2,variance:2,selfRisk:0,difficulty:2,frequency:"always",altDice:false,canElim:false,permScale:false,mapTokens:false, power:"I persistently have the power of the racer currently in the lead." },
  scoocher:       { name:"Scoocher",          speed:1,control:0,disruption:0,combo:3,variance:1,selfRisk:0,difficulty:2,frequency:"always",altDice:false,canElim:false,permScale:false,mapTokens:false, power:"Whenever another racer's power happens, I move 1." },
  flipFlop:       { name:"Flip Flop",         speed:2,control:3,disruption:1,combo:0,variance:0,selfRisk:0,difficulty:1,frequency:"always",altDice:false,canElim:false,permScale:false,mapTokens:false, power:"I can skip rolling for my main move and swap spaces with another racer instead (warp)." },
  hare:           { name:"Hare",              speed:3,control:0,disruption:0,combo:0,variance:2,selfRisk:1,difficulty:1,frequency:"always",altDice:false,canElim:false,permScale:false,mapTokens:false, power:"+2 to main move. When alone in lead at start of turn: skip main move, gain a bronze point chip." },
  mouth:          { name:"M.O.U.T.H.",        speed:0,control:2,disruption:3,combo:0,variance:1,selfRisk:0,difficulty:1,frequency:"often",altDice:false,canElim:true,permScale:false,mapTokens:false, power:"When I stop on a space with exactly one other racer, they're eliminated from the race." },
  rocketScientist:{ name:"Rocket Scientist",  speed:3,control:0,disruption:0,combo:0,variance:2,selfRisk:2,difficulty:1,frequency:"sometimes",altDice:false,canElim:false,permScale:false,mapTokens:false, power:"Can move double my main roll. If I do, I trip after moving." },
  lovableLoser:   { name:"Lovable Loser",     speed:0,control:0,disruption:0,combo:0,variance:0,selfRisk:0,difficulty:0,frequency:"sometimes",altDice:false,canElim:false,permScale:false,mapTokens:false, power:"At start of my turn, gain a bronze point chip if I'm alone in last place." },
  mastermind:     { name:"Mastermind",        speed:1,control:2,disruption:2,combo:0,variance:2,selfRisk:1,difficulty:3,frequency:"sometimes",altDice:false,canElim:false,permScale:false,mapTokens:false, power:"I can predict what number I'll roll. If I'm right, I take another full turn." },
  suckerfish:     { name:"Suckerfish",        speed:1,control:0,disruption:0,combo:3,variance:1,selfRisk:0,difficulty:1,frequency:"always",altDice:false,canElim:false,permScale:false,mapTokens:false, power:"When a racer on my space moves, I can also move to their new space." }
};
const NEW_HEROES = {
  toyTrain:     { name:"Toy Train",      speed:2,control:2,disruption:0,combo:2,variance:1,selfRisk:0,difficulty:1,frequency:"sometimes",altDice:false,canElim:false,permScale:false,mapTokens:false, power:"Hold main move once per turn, then add it to next roll. If I hold, also move 2." },
  spinningTop:  { name:"Spinning Top",   speed:3,control:0,disruption:0,combo:0,variance:3,selfRisk:3,difficulty:2,frequency:"always",altDice:true,canElim:false,permScale:false,mapTokens:false, power:"Roll D6 and D20 alternately. Can choose to skip. Overshoot on D20 = eliminated." },
  yoyo:         { name:"Yo-Yo",          speed:3,control:0,disruption:0,combo:0,variance:3,selfRisk:2,difficulty:1,frequency:"always",altDice:true,canElim:false,permScale:false,mapTokens:false, power:"Only use D20. 1st overshoot: return to start. (Around The World)" },
  matryoshka:   { name:"Matryoshka",     speed:1,control:3,disruption:0,combo:0,variance:0,selfRisk:2,difficulty:2,frequency:"sometimes",altDice:true,canElim:false,permScale:true,mapTokens:false, power:"D12 only. Avoid trips/warps by moving 1 back, but permanently -2 to main move." },
  buildingBlocks:{ name:"Building Blocks",speed:2,control:1,disruption:0,combo:2,variance:0,selfRisk:0,difficulty:1,frequency:"always",altDice:false,canElim:false,permScale:true,mapTokens:true, power:"Place 6 blocks before race. Each collected block: +1 permanently to main move." },
  detective:    { name:"Detective",      speed:1,control:2,disruption:2,combo:1,variance:2,selfRisk:1,difficulty:3,frequency:"always",altDice:false,canElim:false,permScale:false,mapTokens:false, power:"Guess a racer's roll: correct → they skip, I move 2. Wrong → they move 1." },
  secretAgent:  { name:"Secret Agent",   speed:0,control:2,disruption:2,combo:1,variance:1,selfRisk:0,difficulty:1,frequency:"always",altDice:false,canElim:false,permScale:false,mapTokens:true, power:"Place a trip token within 6 spaces. 1 reusable token." },
  mime:         { name:"Mime",           speed:0,control:3,disruption:2,combo:0,variance:1,selfRisk:0,difficulty:2,frequency:"always",altDice:false,canElim:false,permScale:false,mapTokens:true, power:"Place a wall that blocks racers. Breaks on 4+. 1 reusable wall token." },
  bomber:       { name:"Bomber",         speed:0,control:2,disruption:3,combo:1,variance:2,selfRisk:2,difficulty:2,frequency:"always",altDice:false,canElim:true,permScale:false,mapTokens:true, power:"Bomb token within 6 spaces. Racer on it = eliminated. Own bomb hit = +1 point instead." },
  taxiDriver:   { name:"Taxi Driver",    speed:2,control:1,disruption:0,combo:3,variance:1,selfRisk:0,difficulty:2,frequency:"often",altDice:false,canElim:false,permScale:false,mapTokens:false, power:"Pick up to 2 racers in move path. After main move: +2 spaces per passenger." }
};
const PRESETS = Object.assign({}, CORE, NEW_HEROES);

const archetypes = ["Speedster","Control","Chaos","Combo","Tank","Disruptor","Trickster","Drifter","Hoarder","Leech","Gambler","Coward","Bully","Passenger","Cannonball"];

// ─── VOCABULARY POOLS ────────────────────────────────────────────────────────

const V = {
  trigger: [
    "At the start of my turn",
    "After my main move",
    "When another racer passes me",
    "When I pass a racer",
    "When I share a space with a racer",
    "When I roll a 1",
    "When I roll a 6",
    "When another racer trips",
    "When I'm in last place",
    "When I'm in the lead",
    "When I'm alone on a space",
    "When another racer rolls a 1",
    "When I stop on a space with exactly one other racer",
    "When I take damage",
    "Each time any racer moves",
  ],
  damageAmt: ["1","2","3"],
  target: [
    "the racer directly ahead of me",
    "the racer directly behind me",
    "every racer on my space",
    "all racers I passed this turn",
    "the racer in the lead",
    "the racer in last place",
    "a racer of my choice within 3 spaces",
    "all racers within 2 spaces of me",
  ],
  tokenName: [
    "fart token","momentum token","heat token","curse token",
    "ice token","charge token","debt token","rage token",
    "grease token","wind token","jinx token","coin token",
  ],
  spendEffect: [
    "deal 1 damage to a racer behind me",
    "deal 2 damage to a racer of my choice",
    "move forward equal to tokens spent",
    "trip a racer within 3 spaces",
    "take an extra turn",
    "push a racer back 2 spaces",
    "warp to any racer's space",
    "force a racer to reroll",
    "swap places with a racer",
    "gain +3 to my next main move",
    "place a hazard token anywhere on the board",
    "cancel another racer's power this turn",
  ],
  spendCost: ["1","2","3","all of them"],
  momentumHold: [
    "skip my roll and place a momentum token instead. On my next roll, add 2 per token to my main move",
    "skip my roll and store it. On my next turn, add my stored roll to my new roll",
    "choose not to move this turn. Next turn, move double my roll",
    "hold up to 2 movement — instead of moving the full distance, bank the remainder. Spend banked movement any future turn",
    "skip my turn entirely and place 2 momentum tokens. Each token adds +2 to one future roll of my choice",
  ],
  momentumCap: [
    "Max 3 tokens at once.",
    "Tokens expire at the end of the race if unspent.",
    "I lose all tokens if I trip.",
    "Max 5 tokens. Gain a point chip if I cross the finish with tokens remaining.",
  ],
  slideExtra: ["1","2","3","half my roll (rounded up)"],
  slideConsequence: [
    "I trip",
    "I take 1 damage",
    "I take 2 damage",
    "I lose a point chip",
    "any racer I land on is pushed back 1 space",
    "any racer I land on takes 1 damage",
    "I swap places with the racer I land on",
    "I skip my next turn",
  ],
  piggyUpside: [
    "I move with them whenever they move",
    "I copy their power until I leave their space",
    "I gain +1 to my main move for each turn we share a space",
    "they cannot trip me while I'm riding them",
    "whenever they gain a point chip, I gain one too",
    "I may redirect their move by 1 space in any direction",
  ],
  piggyDownside: [
    "they may spend their turn to shake me off, sending me back 2 spaces",
    "if they take damage, I take 1 damage too",
    "I cannot use my main move while riding",
    "if they trip, I trip too",
    "I'm placed last when we reach the same space as a third racer",
    "I lose 1 point chip when I dismount",
  ],
  sacrificeBenefit: [
    "my remaining racer gets +3 to every main move for the rest of the race",
    "my remaining racer takes an extra turn immediately",
    "my remaining racer may warp to any space on the board",
    "my remaining racer deals 2 damage to a racer of their choice",
    "my remaining racer gains immunity to trips and damage for 2 turns",
    "my remaining racer gains a point chip and moves 4",
    "my remaining racer copies the eliminated racer's power for the rest of the race",
  ],
};

// ─── TEMPLATE BUILDERS ───────────────────────────────────────────────────────

function tmplClassic() {
  const triggers2 = ["When passed","When I pass a racer","At the start of my turn","After my move","When rolling odd","When rolling even","When alone","When in last place","When in the lead","When sharing a space","When another racer trips","If I roll exactly 1","If I roll exactly 6","When I stop moving"];
  const effects2   = ["move +2","trip another racer","swap places","take another turn","copy a power","warp to any space","gain 1 VP","force a reroll","reverse my movement","place a hazard token","teleport to the leader","push all racers on my space back 1","steal 2 spaces from a racer ahead","create a duel"];
  const twists2    = ["but take 1 damage","but trip afterwards","only once per race","only on marked spaces","unless I'm in the lead","if exactly one racer is involved","but skip my next turn","","",""];
  const r = a => a[Math.floor(Math.random()*a.length)];
  const twist = r(twists2);
  return `${r(triggers2)}, I may ${r(effects2)}${twist ? ' — ' + twist : ''}.`;
}

function tmplDamage() {
  const r = a => a[Math.floor(Math.random()*a.length)];
  const amt = r(V.damageAmt);
  const tgt = r(V.target);
  const cond = r(V.trigger);
  const followup = Math.random() > 0.5
    ? ` If this brings them to 3 damage, they're eliminated.`
    : ` Damaged racers get −1 to their main move per damage token.`;
  return `${cond}, deal ${amt} damage to ${tgt}.${followup}`;
}

function tmplToken() {
  const r = a => a[Math.floor(Math.random()*a.length)];
  const tok = r(V.tokenName);
  const gain = r(V.trigger);
  const spend = r(V.spendEffect);
  const cost = r(V.spendCost);
  const cap = Math.random() > 0.5 ? ' ' + r(V.momentumCap) : '';
  return `${gain}, gain a ${tok}. Instead of rolling this turn, spend ${cost} ${tok}${cost==='1'?'':'s'} to ${spend}.${cap}`;
}

function tmplMomentum() {
  const r = a => a[Math.floor(Math.random()*a.length)];
  const cap = Math.random() > 0.4 ? ' ' + r(V.momentumCap) : '';
  return `Before my main move, I may ${r(V.momentumHold)}.${cap}`;
}

function tmplSlide() {
  const r = a => a[Math.floor(Math.random()*a.length)];
  const extra = r(V.slideExtra);
  const consequence = r(V.slideConsequence);
  const trigger = Math.random() > 0.5
    ? "After my main move, I slide an additional " + extra + " spaces forward automatically."
    : "I always move " + extra + " extra spaces beyond my roll, whether I want to or not.";
  return `${trigger} If I land on or pass through a racer's space, ${consequence}.`;
}

function tmplPiggyback() {
  const r = a => a[Math.floor(Math.random()*a.length)];
  const up = r(V.piggyUpside);
  const down = r(V.piggyDownside);
  const attach = Math.random() > 0.5
    ? "When I stop on a racer's space, I may latch onto them:"
    : "Before my main move, I may warp to any racer's space and latch on:";
  return `${attach} ${up}. But ${down}.`;
}

function tmplSacrifice() {
  const r = a => a[Math.floor(Math.random()*a.length)];
  const benefit = r(V.sacrificeBenefit);
  const when = Math.random() > 0.5
    ? "Once per game, before my main move, I may eliminate one of my own racers still on the bench."
    : "Once per game, at the start of my turn, I may eliminate one of my own racers currently on the track.";
  return `${when} If I do, ${benefit}.`;
}

// Weighted template picker
function generatePowerText() {
  const templates = [
    [tmplClassic,    30],
    [tmplDamage,     15],
    [tmplToken,      18],
    [tmplMomentum,   14],
    [tmplSlide,      10],
    [tmplPiggyback,  8],
    [tmplSacrifice,  5],
  ];
  const total = templates.reduce((s, [,w]) => s + w, 0);
  let roll = Math.random() * total;
  for (const [fn, w] of templates) {
    roll -= w;
    if (roll <= 0) return fn();
  }
  return tmplClassic();
}

function g(id) { return document.getElementById(id); }

// ─── TOGGLES ────────────────────────────────────────────────────────────────
function toggleCheck(key) {
  const cb = g(key); cb.checked = !cb.checked;
  const ids = { altDice:'tog-dice', canElim:'tog-elim', permScale:'tog-scale', mapTokens:'tog-token' };
  const item = g(ids[key]); const dot = g('dot-' + key);
  if (cb.checked) { item.classList.add('checked'); dot.textContent = '✓'; }
  else { item.classList.remove('checked'); dot.textContent = ''; }
}
function setToggle(key, val) {
  const cb = g(key); cb.checked = val;
  const ids = { altDice:'tog-dice', canElim:'tog-elim', permScale:'tog-scale', mapTokens:'tog-token' };
  const item = g(ids[key]); const dot = g('dot-' + key);
  if (val) { item.classList.add('checked'); dot.textContent = '✓'; }
  else { item.classList.remove('checked'); dot.textContent = ''; }
  if (typeof updateTuningSummary === 'function') updateTuningSummary();
}
function getSpecials() {
  return { altDice:g('altDice').checked, canElim:g('canElim').checked, permScale:g('permScale').checked, mapTokens:g('mapTokens').checked };
}

// ─── PRESET LOADER ──────────────────────────────────────────────────────────
function loadPreset() {
  // presetSelect removed from UI; loadPreset now called programmatically only
  if (!arguments[0]) return;
  const key = arguments[0];
  const p = PRESETS[key];
  g('name').value = p.name; g('powerText').value = p.power;
  g('speed').value = p.speed; g('control').value = p.control;
  g('disruption').value = p.disruption; g('combo').value = p.combo;
  g('variance').value = p.variance; g('selfRisk').value = p.selfRisk;
  g('difficulty').value = p.difficulty; g('frequency').value = p.frequency;
  setToggle('altDice', p.altDice); setToggle('canElim', p.canElim);
  setToggle('permScale', p.permScale); setToggle('mapTokens', p.mapTokens);
  analyzeRacer();
}

// ─── CORE ANALYSIS ──────────────────────────────────────────────────────────
function calculateScore(d) {
  return d.speed*2 + d.control*1.5 + d.disruption*1.5 + d.combo*2 - d.variance*1 - d.selfRisk*1.5 - d.difficulty*0.5;
}
function determineCost(score) {
  if (score<=2) return 1; if (score<=5) return 2; if (score<=8) return 3; if (score<=11) return 4; return 5;
}
function determineTier(d) {
  const ceiling = d.speed + d.combo*2 + d.disruption + d.control + d.variance;
  const floor   = d.speed + d.control - d.selfRisk - d.variance;
  if (ceiling>=10 && floor>=4) return "S";
  if (ceiling>=8) return "A";
  if (ceiling>=5) return "B";
  if (ceiling>=3) return "C";
  return "D";
}
function determineCounters(d) {
  const sa=[], wa=[];
  if (d.disruption>=2) { sa.push("Speedsters"); sa.push("Combo Racers"); }
  if (d.control>=2) sa.push("Chaos Racers");
  if (d.variance>=2) { wa.push("Reliable Racers"); wa.push("Long Tracks"); }
  if (d.selfRisk>=2) { wa.push("Hazard Tracks"); wa.push("Attrition"); }
  if (d.speed>=2) wa.push("Trip Effects");
  return { strongAgainst: sa, weakAgainst: wa };
}
function generateWarnings(d, score, sp) {
  const warnings=[], suggestions=[];
  if (d.combo>=3 && d.speed>=2) warnings.push("⚠️ High combo potential may create infinite chains.");
  if (d.disruption>=3 && d.frequency==="always") warnings.push("⚠️ Constant disruption may frustrate players.");
  if (d.speed>=3 && d.selfRisk===0 && !sp.altDice) warnings.push("⚠️ Extremely efficient — consider adding a downside.");
  if (d.variance>=3) warnings.push("🎲 Extremely chaotic. Fun ceiling is high; frustration floor is too.");
  if (sp.altDice && d.selfRisk===0) warnings.push("🎲 Alternate dice without self-risk is too safe — overshoot needs a cost.");
  if (sp.altDice && d.selfRisk>=3) warnings.push("💀 Alt dice + extreme self-risk may feel punishing. Consider one-time elimination protection.");
  if (sp.canElim) {
    warnings.push("💣 Elimination mechanics need careful scoping: can it combo infinitely? Does the eliminated player have recourse?");
    if (d.selfRisk<=1) warnings.push("💣 Elimination with low self-risk is very strong. Add a setup cost or own-bomb risk.");
  }
  if (sp.permScale) {
    if (d.control>=2) warnings.push("📈 Permanent scaling + high control is a compounding threat — can snowball.");
    if (score>=8) warnings.push("📈 A strong racer that also scales may be unrecoverable by mid-race.");
    suggestions.push("Test permanent scaling at different race lengths — it breaks at short distances.");
  }
  if (sp.mapTokens) {
    if (d.disruption>=3) warnings.push("🪤 Map tokens + brutal disruption may lock out paths entirely.");
    if (d.combo>=2) warnings.push("🪤 Reusable map tokens with combo potential need a clear limit per turn.");
    suggestions.push("Define what happens when tokens interact with each other (e.g. Bomber + Secret Agent on same space).");
  }
  if (sp.canElim && sp.mapTokens) warnings.push("💥 Elimination-via-token is the highest-impact mechanic in the game — playtest extensively.");
  if (sp.permScale && sp.altDice) warnings.push("📈🎲 Permanent scaling with alternate dice can spiral unpredictably.");
  if (score>10) { suggestions.push("Add self-damage or a skip-turn cost."); suggestions.push("Limit strongest effect to once per race."); suggestions.push("Require a positioning condition to activate."); }
  if (score<2) { suggestions.push("Increase base movement slightly."); suggestions.push("Add a synergy hook for combos."); }
  return { warnings, suggestions };
}

// ─── ECONOMY ─────────────────────────────────────────────────────────────────
function calcDurability(cost) { return Math.max(1, 6 - cost); }

function calcDamageRisk(d, sp) {
  let risk = 0;
  const srMap = [0, 10, 25, 45];
  const vrMap = [0, 5,  15, 25];
  risk += srMap[d.selfRisk] + vrMap[d.variance];
  if (sp.altDice)   risk += 15;
  if (sp.permScale) risk -= 5;
  if (sp.canElim)   risk += 5;
  return Math.min(75, Math.max(0, risk));
}

function getDamageConsequence(cost) {
  const table = {
    1: { label:"Minor Scratch",       desc:"Recovers fully — races at full power next race.",           cls:"dmi1" },
    2: { label:"Bruised",             desc:"Races at −1 to all main move rolls next race.",              cls:"dmi2" },
    3: { label:"Injured",             desc:"Benched for 1 race. Returns at full power after.",           cls:"dmi3" },
    4: { label:"Seriously Hurt",      desc:"Benched for 1 race, then races permanently at −1.",          cls:"dmi4" },
    5: { label:"Eliminated",          desc:"Removed from your roster entirely. You lose the coin investment.", cls:"dmi5" }
  };
  return table[cost];
}

function calcExpectedValue(tier, cost, damageRisk) {
  const tierPoints = { S:7.5, A:5, B:3, C:1.5, D:0.5 };
  const base = tierPoints[tier];
  const survivalRate = 1 - (damageRisk / 100);
  return (base * survivalRate).toFixed(1);
}

function renderDurabilityPips(durability) {
  let html = '<div class="dmg-track">';
  for (let i = 0; i < 5; i++) {
    html += `<div class="dmg-pip ${i < durability ? 'full' : 'empty'}"></div>`;
  }
  html += '</div>';
  return html;
}

// ─── MAIN ANALYZE ────────────────────────────────────────────────────────────
function analyzeRacer() {
  const d = {
    speed:+g("speed").value, control:+g("control").value,
    disruption:+g("disruption").value, combo:+g("combo").value,
    variance:+g("variance").value, selfRisk:+g("selfRisk").value,
    difficulty:+g("difficulty").value, frequency:g("frequency").value
  };
  const sp = getSpecials();
  const name   = g("name").value || "Unnamed Racer";
  const power  = g("powerText").value || "No power entered.";
  const score  = calculateScore(d);
  const cost   = determineCost(score);
  const tier   = determineTier(d);
  const dur    = calcDurability(cost);
  const dmgRisk = calcDamageRisk(d, sp);
  const dmgCons = getDamageConsequence(cost);
  const ev     = calcExpectedValue(tier, cost, dmgRisk);
  const counters = determineCounters(d);
  const info     = generateWarnings(d, score, sp);

  const specialBadges = [
    sp.altDice   && `<span class="badge special">🎲 Alt Dice</span>`,
    sp.canElim   && `<span class="badge special">💣 Elimination</span>`,
    sp.permScale && `<span class="badge special">📈 Scales</span>`,
    sp.mapTokens && `<span class="badge special">🪤 Map Tokens</span>`
  ].filter(Boolean).join("");

  const strongTags = counters.strongAgainst.length
    ? counters.strongAgainst.map(x=>`<span class="tag strong">${x}</span>`).join("")
    : `<span class="tag none">None</span>`;
  const weakTags = counters.weakAgainst.length
    ? counters.weakAgainst.map(x=>`<span class="tag weak">${x}</span>`).join("")
    : `<span class="tag none">None</span>`;

  const warnItems = info.warnings.length
    ? info.warnings.map(w=>`<li class="warning">${w}</li>`).join("")
    : `<li class="none-item">No warnings — clean design!</li>`;
  const suggItems = info.suggestions.length
    ? info.suggestions.map(s=>`<li class="suggestion">✅ ${s}</li>`).join("")
    : `<li class="none-item">✨ Looks healthy!</li>`;

  const coinSymbols = Array.from({length:5}, (_,i) => `<span style="font-size:20px;opacity:${i<cost?1:0.2}">🪙</span>`).join('');

  g("output").innerHTML = `
    <div class="racer-name">${name}</div>
    <div class="power-box">💬 ${power}</div>
    <div class="badge-row">
      <span class="badge tier-${tier}">Tier ${tier}</span>
      <span class="badge score">Score ${score.toFixed(1)}</span>
      ${specialBadges}
    </div>
    <div class="stat-grid">
      <div class="stat-cell"><span class="stat-label">Speed</span><span class="stat-val v${d.speed}">${d.speed}</span></div>
      <div class="stat-cell"><span class="stat-label">Control</span><span class="stat-val v${d.control}">${d.control}</span></div>
      <div class="stat-cell"><span class="stat-label">Disrupt</span><span class="stat-val v${d.disruption}">${d.disruption}</span></div>
      <div class="stat-cell"><span class="stat-label">Combo</span><span class="stat-val v${d.combo}">${d.combo}</span></div>
      <div class="stat-cell"><span class="stat-label">Variance</span><span class="stat-val v${d.variance}">${d.variance}</span></div>
      <div class="stat-cell"><span class="stat-label">Self Risk</span><span class="stat-val v${d.selfRisk}">${d.selfRisk}</span></div>
      <div class="stat-cell"><span class="stat-label">Difficulty</span><span class="stat-val v${d.difficulty}">${d.difficulty}</span></div>
      <div class="stat-cell" style="background:#FFF9E0;"><span class="stat-label">Frequency</span><span class="stat-val" style="font-size:12px">${d.frequency.toUpperCase()}</span></div>
    </div>

    <div class="econ-block">
      <div class="econ-title">💰 Economy</div>
      <div class="econ-grid">
        <div class="econ-card ec-cost">
          <span class="ec-label">Coin Cost</span>
          <span class="ec-val">${coinSymbols}</span>
          <span class="ec-sub">${cost} coin${cost!==1?'s':''} to recruit</span>
        </div>
        <div class="econ-card ec-dur">
          <span class="ec-label">Durability</span>
          ${renderDurabilityPips(dur)}
          <span class="ec-sub">${dur}/5 — ${dur>=4?'very resilient':dur>=3?'solid':dur>=2?'fragile':'very fragile'}</span>
        </div>
        <div class="econ-card ec-risk">
          <span class="ec-label">Damage Risk</span>
          <span class="ec-val" style="color:${dmgRisk>=50?'#D42B1A':dmgRisk>=25?'#F07020':'#1DAA3C'}">${dmgRisk}%</span>
          <span class="ec-sub">chance of damage per race</span>
        </div>
        <div class="econ-card ec-ev">
          <span class="ec-label">Exp. Value</span>
          <span class="ec-val">${ev}</span>
          <span class="ec-sub">pts/race after damage risk</span>
        </div>
      </div>
      <div class="dmg-consequence ${dmgCons.cls}">
        💥 <strong>If damaged:</strong> ${dmgCons.label} — ${dmgCons.desc}
      </div>
    </div>

    <div class="section-head">💪 Strong Against</div>
    <div class="tag-row">${strongTags}</div>
    <div class="section-head">😬 Weak Against</div>
    <div class="tag-row">${weakTags}</div>
    <div class="section-head">🚨 Warnings</div>
    <ul class="warn-list">${warnItems}</ul>
    <div class="section-head">💡 Suggestions</div>
    <ul class="warn-list">${suggItems}</ul>
    <p class="design-note">Great racers are interactive, situational, and slightly chaotic — not perfectly optimized.</p>
  `;
}

// ─── RANDOM RACER ────────────────────────────────────────────────────────────
// ─── COLLAPSIBLE TUNING ──────────────────────────────────────────────────────
let tuningOpen = false;

function toggleTuning() {
  tuningOpen = !tuningOpen;
  const body  = g('tuning-body');
  const arrow = g('tuning-arrow');
  body.classList.toggle('open', tuningOpen);
  arrow.classList.toggle('open', tuningOpen);
}

function updateTuningSummary() {
  const labels = {
    speed:    ['—','Minor','Strong','Explosive'],
    control:  ['—','Minor','Tactical','Warping'],
    disruption:['—','Annoying','Strong','Brutal'],
    combo:    ['—','Some','Repeatable','Dangerous'],
    variance: ['Stable','Mild','Swingy','Chaos'],
    selfRisk: ['Safe','Minor','Dangerous','Destructive'],
    difficulty:['Easy','Medium','Tactical','Expert'],
  };
  const parts = [];
  for (const [k, labs] of Object.entries(labels)) {
    const v = +g(k).value;
    if (v > 0) parts.push(labs[v]);
  }
  const sp = [];
  if (g('altDice').checked)   sp.push('Alt Dice');
  if (g('canElim').checked)   sp.push('Elim');
  if (g('permScale').checked) sp.push('Scales');
  if (g('mapTokens').checked) sp.push('Tokens');
  sp.forEach(s => parts.push(s));
  const tier = activeTierLimit !== 'any' ? 'Tier ' + activeTierLimit : '';
  const summary = parts.length === 0 && !tier
    ? 'All default — expand to adjust'
    : [...(tier ? [tier] : []), ...parts].join(' · ');
  g('tuning-summary').textContent = summary;
}

// ─── TIER LIMIT ──────────────────────────────────────────────────────────────
let activeTierLimit = 'any';

function setTierLimit(tier) {
  activeTierLimit = tier;
  document.querySelectorAll('.tier-btn').forEach(btn => btn.classList.remove('active'));
  document.querySelector('.tier-btn.tb-' + tier).classList.add('active');
  updateTuningSummary();
  const note = g('tl-note');
  if (tier === 'S') {
    note.textContent = 'Tier S racers are not in the official game. Use with care in your variant.';
    note.classList.add('visible');
  } else if (tier === 'any') {
    note.textContent = '';
    note.classList.remove('visible');
  } else {
    note.textContent = `Random racer will be rerolled until it lands in Tier ${tier}.`;
    note.classList.add('visible');
  }
}

function generateRandomRacer() {
  const r  = a => a[Math.floor(Math.random()*a.length)];
  const ri = () => Math.floor(Math.random() * 4);
  const clamp = v => Math.min(3, Math.max(0, v));

  // Pick template first, then nudge stats to match its flavour
  const templateFlavours = [
    { fn: tmplClassic,    weight:30, nudge:{} },
    { fn: tmplDamage,     weight:15, nudge:{ disruption:1, selfRisk:-1 } },
    { fn: tmplToken,      weight:18, nudge:{ combo:1, control:1, variance:-1 } },
    { fn: tmplMomentum,   weight:14, nudge:{ speed:1, combo:1, variance:-1 } },
    { fn: tmplSlide,      weight:10, nudge:{ speed:1, variance:1, selfRisk:1 } },
    { fn: tmplPiggyback,  weight:8,  nudge:{ combo:2, control:1 } },
    { fn: tmplSacrifice,  weight:5,  nudge:{ selfRisk:2, combo:1, difficulty:1 } },
  ];
  const total = templateFlavours.reduce((s,t) => s + t.weight, 0);
  let roll = Math.random() * total, chosen = templateFlavours[0];
  for (const t of templateFlavours) { roll -= t.weight; if (roll <= 0) { chosen = t; break; } }

  let stats, tier, attempts = 0;
  do {
    const base = { speed:ri(), control:ri(), disruption:ri(), combo:ri(), variance:ri(), selfRisk:ri(), difficulty:ri() };
    // Apply nudge: shift toward flavour profile, then re-randomise with bias
    stats = Object.fromEntries(Object.entries(base).map(([k,v]) => {
      const n = chosen.nudge[k] || 0;
      return [k, clamp(v + n + (Math.random() > 0.6 ? 1 : 0) - (Math.random() > 0.6 ? 1 : 0))];
    }));
    tier = determineTier(stats);
    attempts++;
  } while (activeTierLimit !== 'any' && tier !== activeTierLimit && attempts < 200);

  // Specials: token/slide/piggyback/sacrifice naturally enable certain flags
  const sp = {
    altDice:   chosen.fn === tmplSlide ? Math.random() > 0.5 : Math.random() > 0.85,
    canElim:   chosen.fn === tmplSacrifice || (chosen.fn === tmplDamage && Math.random() > 0.7),
    permScale: chosen.fn === tmplMomentum  && Math.random() > 0.5,
    mapTokens: (chosen.fn === tmplToken || chosen.fn === tmplDamage) && Math.random() > 0.4,
  };

  g("name").value     = r(archetypes) + " " + Math.floor(Math.random() * 999);
  g("powerText").value = chosen.fn();
  Object.entries(stats).forEach(([id, val]) => g(id).value = val);
  setToggle('altDice', sp.altDice); setToggle('canElim', sp.canElim);
  setToggle('permScale', sp.permScale); setToggle('mapTokens', sp.mapTokens);
  analyzeRacer();
}

// ─── BUDGET PLANNER ──────────────────────────────────────────────────────────
const tightLabels = ['Very Tight','Tight','Medium','Loose','Very Loose'];

function updatePlanner() {
  const players = +g('sl-players').value;
  const races   = +g('sl-races').value;
  const tight   = +g('sl-tight').value;
  g('lbl-players').textContent = players;
  g('lbl-races').textContent   = races;
  g('lbl-tight').textContent   = tightLabels[tight-1];

  // Avg coin per racer based on tightness (1=1.6, 5=3.2)
  const avgCoin = 1.4 + (tight * 0.4);
  const startCoins = Math.round(avgCoin * races);

  // What can you build with startCoins?
  // Greedy: spend from highest to lowest
  let remaining = startCoins;
  let prem=0, mid=0, budget=0;
  // Estimate: try 1 premium (4-5 coin) racer if budget allows
  if (tight >= 4 && remaining >= 4) { prem++; remaining -= 4; }
  while (remaining >= 3 && mid + prem < races - 1) { mid++; remaining -= 3; }
  while (remaining >= 2 && mid + prem < races - 1) { mid++; remaining -= 2; }
  while (remaining >= 1 && prem + mid + budget < races) { budget++; remaining -= 1; }

  // Pool composition (for drafting)
  const poolSize = players * races * 2;
  const premPool   = Math.max(1, Math.round(poolSize * 0.12));
  const aPool      = Math.round(poolSize * 0.18);
  const bPool      = Math.round(poolSize * 0.35);
  const cPool      = Math.round(poolSize * 0.25);
  const dPool      = poolSize - premPool - aPool - bPool - cPool;

  // Damage economy: expected coins lost to damage
  const avgDmgRisk = 0.20 + (tight * 0.04);
  const expectedLoss = (startCoins * avgDmgRisk).toFixed(1);
  const safeCoins = (startCoins * (1 - avgDmgRisk)).toFixed(1);

  g('bp-output').innerHTML = `
    <div class="bp-result-grid">
      <div class="bp-card bpc-coins">
        <span class="bpc-label">Starting Coins</span>
        <span class="bpc-val">${startCoins}</span>
        <span class="bpc-sub">per player</span>
      </div>
      <div class="bp-card bpc-pool">
        <span class="bpc-label">Draft Pool</span>
        <span class="bpc-val">${poolSize}</span>
        <span class="bpc-sub">racer cards total</span>
      </div>
      <div class="bp-card bpc-risk">
        <span class="bpc-label">Avg Coins at Risk</span>
        <span class="bpc-val">${expectedLoss}</span>
        <span class="bpc-sub">expected loss to damage</span>
      </div>
      <div class="bp-card bpc-safe">
        <span class="bpc-label">Safe Budget</span>
        <span class="bpc-val">${safeCoins}</span>
        <span class="bpc-sub">expected coins retained</span>
      </div>
    </div>

    <div class="tier-breakdown">
      <div class="tb-title">💰 What ${startCoins} coins buys you (${races} racers)</div>
      <div class="tier-row"><div class="tier-dot tS">S</div><div class="tier-info">Cost 5 — <span>~1 racer</span> if you go all-in on a single star. High EV, catastrophic if damaged.</div></div>
      <div class="tier-row"><div class="tier-dot tA">A</div><div class="tier-info">Cost 4 — <span>${Math.floor(startCoins/4)} racers max</span> at this tier. Strong floor, hard to replace.</div></div>
      <div class="tier-row"><div class="tier-dot tB">B</div><div class="tier-info">Cost 3 — <span>${Math.floor(startCoins/3)} racers max</span>. Sweet spot: good power, benched if damaged.</div></div>
      <div class="tier-row"><div class="tier-dot tC">C</div><div class="tier-info">Cost 2 — <span>${Math.floor(startCoins/2)} racers max</span>. Safe value: bruised but still racing.</div></div>
      <div class="tier-row"><div class="tier-dot tD">D</div><div class="tier-info">Cost 1 — <span>${startCoins} racers max</span>. Junk picks: lowest ceiling, scratch damage only.</div></div>

      <div style="margin-top:14px;padding-top:10px;border-top:2px dashed #ccc;">
        <div style="font-size:12px;font-weight:800;letter-spacing:1px;text-transform:uppercase;margin-bottom:8px;color:#444;">Recommended draft pool (${poolSize} cards)</div>
        <div class="dmg-key">
          <span class="dmg-key-item dmi5">S/Cost 5: ${premPool} cards</span>
          <span class="dmg-key-item dmi4">A/Cost 4: ${aPool} cards</span>
          <span class="dmg-key-item dmi3">B/Cost 3: ${bPool} cards</span>
          <span class="dmg-key-item dmi2">C/Cost 2: ${cPool} cards</span>
          <span class="dmg-key-item dmi1">D/Cost 1: ${dPool} cards</span>
        </div>
      </div>

      <div style="margin-top:12px;padding:10px 12px;background:#FFFAE0;border:2px solid var(--black);border-radius:8px;font-size:13px;font-weight:700;color:#555;line-height:1.6;">
        <strong style="color:var(--black)">💡 How damage works in this variant:</strong><br>
        After each race, any racer that triggered their self-risk clause rolls a die.
        Roll ≥ their durability rating → fully recovered.
        Roll &lt; durability → take damage per the consequence table above.
        Cost-5 racers have durability 1 — they need a 1 on the die to survive undamaged.
        This means the riskiest racers are both the most powerful AND the most likely to disappear from your roster.
      </div>
    </div>
  `;
}

// ─── INIT ────────────────────────────────────────────────────────────────────
updatePlanner();
</script>
</body>
</html>
