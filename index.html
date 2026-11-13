<!doctype html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>RIDE Calapan</title>
<meta name="description" content="RIDE (Real-time Itinerary and Destination Explorer) helps you discover places in Calapan City and plan your day.">
<link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Bricolage+Grotesque:opsz,wght@12..96,500;12..96,700;12..96,800&family=Inter:wght@400;500;600&family=IBM+Plex+Mono:wght@400;500&display=swap">
<style>
:root {
  --bg: #F4F4EA;
  --surface: #FCFCF7;
  --ink: #10201C;
  --muted: #4A5A53;
  --line: #D6DAC8;
  --accent: #0F5C54;
  --accent-2: #14A394;
  --accent-ink: #FFFFFF;
  --soft: #E3ECDB;
  --route: #C97A12;
  --route-2: #F2B24C;
  --glow: rgba(20, 163, 148, 0.28);
  --shadow: 0 24px 50px -28px rgba(10, 30, 25, 0.55);
  --font-display: "Bricolage Grotesque", "Inter", system-ui, sans-serif;
  --font-body: "Inter", system-ui, -apple-system, "Segoe UI", sans-serif;
  --font-mono: "IBM Plex Mono", ui-monospace, "SFMono-Regular", Menlo, monospace;
}
@media (prefers-color-scheme: dark) {
  :root:not([data-theme="light"]) {
    --bg: #0B1412; --surface: #13211D; --ink: #EAF2EC; --muted: #A5B8AE; --line: #263832;
    --accent: #6FD6C4; --accent-2: #2EC4AE; --accent-ink: #052019; --soft: #162822; --route: #F0B14A; --route-2: #FFD27A;
    --glow: rgba(111, 214, 196, 0.22); --shadow: 0 24px 50px -28px rgba(0,0,0,0.9); color-scheme: dark;
  }
}
:root[data-theme="dark"] {
  --bg: #0B1412; --surface: #13211D; --ink: #EAF2EC; --muted: #A5B8AE; --line: #263832;
  --accent: #6FD6C4; --accent-2: #2EC4AE; --accent-ink: #052019; --soft: #162822; --route: #F0B14A; --route-2: #FFD27A;
  --glow: rgba(111, 214, 196, 0.22); --shadow: 0 24px 50px -28px rgba(0,0,0,0.9); color-scheme: dark;
}

* { box-sizing: border-box; }
html { scroll-behavior: smooth; }
html, body { margin: 0; }
body {
  background: var(--bg); color: var(--ink);
  font-family: var(--font-body); font-size: 16px; line-height: 1.65;
  padding-left: max(16px, env(safe-area-inset-left, 0px));
  padding-right: max(16px, env(safe-area-inset-right, 0px));
  overflow-x: hidden;
}
body::before { content: ""; position: fixed; inset: 0 0 auto; height: env(safe-area-inset-top, 0px); z-index: 40; background: var(--bg); }
/* soft ambient glow behind everything */
body::after {
  content: ""; position: fixed; inset: 0; z-index: -1; pointer-events: none;
  background:
    radial-gradient(60vmax 40vmax at 85% -10%, var(--glow), transparent 60%),
    radial-gradient(50vmax 36vmax at -10% 30%, rgba(201,122,18,0.12), transparent 60%);
}
a { color: var(--accent); text-underline-offset: 3px; }
a:focus-visible, button:focus-visible, summary:focus-visible, input:focus-visible, textarea:focus-visible { outline: 3px solid var(--route); outline-offset: 3px; border-radius: 6px; }
h1, h2, h3 { font-family: var(--font-display); line-height: 1.08; letter-spacing: -0.02em; text-wrap: balance; margin: 0; }
h1 { font-size: clamp(2.5rem, 6.6vw, 4.8rem); font-weight: 800; }
h2 { font-size: clamp(1.7rem, 3.6vw, 2.5rem); font-weight: 800; }
h3 { font-size: 1.2rem; font-weight: 700; }
p { margin: 0; }
.wrap { max-width: 1120px; margin-inline: auto; }
.eyebrow { font-family: var(--font-mono); font-size: 0.78rem; letter-spacing: 0.1em; text-transform: uppercase; color: var(--route); display: inline-flex; align-items: center; gap: 8px; }
.eyebrow::before { content: ""; width: 22px; height: 2px; background: var(--route); border-radius: 2px; }
.lead { font-size: 1.15rem; color: var(--muted); max-width: 58ch; }
.grad { background: linear-gradient(100deg, var(--accent) 10%, var(--accent-2) 55%, var(--route) 110%); -webkit-background-clip: text; background-clip: text; color: transparent; }

/* header */
.site-header {
  position: sticky; top: env(safe-area-inset-top, 0px); z-index: 30;
  background: color-mix(in srgb, var(--bg) 82%, transparent);
  backdrop-filter: blur(14px) saturate(1.3); -webkit-backdrop-filter: blur(14px) saturate(1.3);
  border-bottom: 1px solid var(--line);
  margin-inline: calc(-1 * max(16px, env(safe-area-inset-left, 0px)));
  padding-inline: max(16px, env(safe-area-inset-left, 0px));
}
.bar { display: flex; flex-wrap: wrap; align-items: center; justify-content: space-between; gap: 6px 20px; padding-block: 10px; max-width: 1120px; margin-inline: auto; }
.brand { display: inline-flex; align-items: center; gap: 10px; text-decoration: none; color: var(--ink); font-family: var(--font-display); font-weight: 800; font-size: 1.55rem; letter-spacing: 0.03em; }
.brand svg { width: 30px; height: 30px; }
.nav-right { display: flex; align-items: center; gap: 8px; flex-wrap: wrap; }
nav ul { list-style: none; display: flex; flex-wrap: wrap; gap: 2px; margin: 0; padding: 4px; background: var(--soft); border-radius: 999px; }
nav a { display: block; padding: 7px 14px; border-radius: 999px; text-decoration: none; color: var(--muted); font-weight: 500; font-size: 0.92rem; transition: background .2s, color .2s; }
nav a:hover { color: var(--ink); }
nav a[aria-current="page"] { color: var(--accent-ink); background: var(--accent); }
.theme { width: 40px; height: 40px; border-radius: 50%; border: 1px solid var(--line); background: var(--surface); color: var(--ink); cursor: pointer; display: grid; place-items: center; }
.theme:hover { background: var(--soft); }
.theme svg { width: 20px; height: 20px; }

/* buttons */
.btn { display: inline-flex; align-items: center; gap: 8px; padding: 14px 26px; border-radius: 999px; transition: transform .15s ease, box-shadow .2s, background .2s; font-weight: 600; text-decoration: none; border: 2px solid var(--accent); font: inherit; font-weight: 600; cursor: pointer; }
.btn svg { width: 18px; height: 18px; }
.btn.primary { background: linear-gradient(135deg, var(--accent), var(--accent-2)); border-color: transparent; color: var(--accent-ink); box-shadow: 0 12px 26px -12px var(--accent-2); }
.btn.primary:hover { transform: translateY(-2px); box-shadow: 0 16px 30px -12px var(--accent-2); }
.btn.ghost { color: var(--accent); background: transparent; }
.btn.ghost:hover { background: var(--soft); transform: translateY(-2px); }
.actions { display: flex; flex-wrap: wrap; gap: 12px; }

/* pages */
.page { padding-block: 40px 72px; }
.page[hidden] { display: none; }
.hero-wrap { background: linear-gradient(145deg, var(--soft), color-mix(in srgb, var(--soft) 55%, var(--bg))); border: 1px solid var(--line); border-radius: 32px; padding: 60px 52px; position: relative; overflow: hidden; }
.hero-wrap::before { content: ""; position: absolute; inset: 0; background-image: radial-gradient(var(--line) 1.2px, transparent 1.4px); background-size: 22px 22px; opacity: .55; mask-image: linear-gradient(120deg, transparent 20%, #000 90%); -webkit-mask-image: linear-gradient(120deg, transparent 20%, #000 90%); pointer-events: none; }
.hero-wrap::after { content: ""; position: absolute; right: -110px; top: -110px; width: 340px; height: 340px; border-radius: 50%; background: radial-gradient(circle, var(--route-2), transparent 70%); opacity: .35; pointer-events: none; }
.hero { display: grid; grid-template-columns: minmax(0, 1.1fr) minmax(0, 0.9fr); gap: 48px; align-items: center; position: relative; z-index: 1; }
.hero-copy { display: grid; gap: 24px; justify-items: start; min-width: 0; }
.pill { display: inline-flex; align-items: center; gap: 8px; padding: 6px 14px 6px 8px; background: var(--surface); border: 1px solid var(--line); border-radius: 999px; font-size: .85rem; font-weight: 500; }
.pill i { width: 9px; height: 9px; border-radius: 50%; background: var(--accent-2); box-shadow: 0 0 0 0 var(--accent-2); animation: ping 2s infinite; margin-left: 6px; }
@keyframes ping { 70% { box-shadow: 0 0 0 9px transparent; } 100% { box-shadow: 0 0 0 0 transparent; } }
.hero-note { display: flex; flex-wrap: wrap; gap: 8px 22px; color: var(--muted); font-size: .9rem; }
.hero-note span { display: inline-flex; align-items: center; gap: 7px; }
.hero-note svg { width: 16px; height: 16px; color: var(--accent); }

.hero-art { position: relative; min-width: 0; display: grid; justify-items: center; padding-block: 10px 26px; }
.hero-art .routeart { position: absolute; inset: -6% -12%; width: 124%; height: 112%; opacity: .9; z-index: 0; }

.phone {
  position: relative; z-index: 1; width: min(330px, 100%);
  background: var(--surface); border: 1px solid var(--line); border-radius: 36px;
  padding: 14px 18px 22px; box-shadow: var(--shadow); animation: float 7s ease-in-out infinite;
}
@keyframes float { 50% { transform: translateY(-8px) rotate(-.4deg); } }
.notch { width: 84px; height: 6px; border-radius: 6px; background: var(--line); margin: 0 auto 14px; }
.phone-top { display: flex; justify-content: space-between; align-items: baseline; margin-bottom: 14px; }
.phone-top strong { font-family: var(--font-display); font-size: 1.15rem; }
.tag { font-family: var(--font-mono); font-size: .7rem; letter-spacing: .06em; text-transform: uppercase; color: var(--muted); }
.stops { list-style: none; margin: 0; padding: 0; position: relative; display: grid; gap: 6px; }
.stops::before { content: ""; position: absolute; left: 15px; top: 14px; bottom: 14px; border-left: 2px dashed var(--route); opacity: .7; }
.stops li { position: relative; padding: 9px 10px 9px 40px; border-radius: 14px; transition: background .25s, transform .25s; cursor: default; animation: pop .45s ease both; }
.stops li:hover { background: var(--soft); transform: translateX(3px); }
.stops li::before { content: attr(data-n); position: absolute; left: 6px; top: 10px; width: 20px; height: 20px; border-radius: 50%; background: var(--accent); color: var(--accent-ink); font: 600 .7rem/20px var(--font-mono); text-align: center; box-shadow: 0 0 0 3px var(--surface); }
@keyframes pop { from { opacity: 0; transform: translateY(8px); } }
.stops time { font-family: var(--font-mono); font-size: .74rem; color: var(--route); font-weight: 500; display: block; }
.stops b { display: block; font-weight: 600; line-height: 1.3; }
.stops span { color: var(--muted); font-size: .86rem; line-height: 1.4; display: block; }
.phone-note { margin-top: 12px; padding-top: 10px; border-top: 1px solid var(--line); font-size: .76rem; color: var(--muted); }
.mini { position: absolute; z-index: 2; left: -30px; bottom: 0; background: var(--surface); border: 1px solid var(--line); border-radius: 16px; padding: 10px 16px 10px 10px; display: flex; align-items: center; gap: 10px; box-shadow: var(--shadow); font-weight: 600; font-size: .9rem; line-height: 1.3; animation: float 8s ease-in-out -2s infinite; }
.mini small { display: block; font-weight: 400; color: var(--muted); font-size: .78rem; }
.icon { width: 48px; height: 48px; border-radius: 14px; background: linear-gradient(135deg, var(--accent), var(--accent-2)); color: var(--accent-ink); display: grid; place-items: center; flex: none; }
.icon svg { width: 25px; height: 25px; }
.mini .icon { width: 36px; height: 36px; border-radius: 10px; }
.mini .icon svg { width: 19px; height: 19px; }

/* marquee */
.marquee { margin-top: 56px; overflow: hidden; border-block: 1px solid var(--line); padding-block: 16px; mask-image: linear-gradient(90deg, transparent, #000 8%, #000 92%, transparent); -webkit-mask-image: linear-gradient(90deg, transparent, #000 8%, #000 92%, transparent); }
.track { display: flex; gap: 14px; width: max-content; animation: slide 38s linear infinite; }
.marquee:hover .track { animation-play-state: paused; }
@keyframes slide { to { transform: translateX(-50%); } }
.chip { white-space: nowrap; padding: 8px 18px; border-radius: 999px; background: var(--surface); border: 1px solid var(--line); font-weight: 500; font-size: .95rem; display: inline-flex; align-items: center; gap: 8px; }
.chip::before { content: ""; width: 8px; height: 8px; border-radius: 50%; background: var(--route); }

.section { margin-top: 88px; display: grid; gap: 30px; }
.section-head { display: grid; gap: 12px; max-width: 60ch; }

/* stats */
.stats { display: grid; grid-template-columns: repeat(4, minmax(0, 1fr)); gap: 16px; margin-top: 56px; }
.stat { background: var(--surface); border: 1px solid var(--line); border-radius: 20px; padding: 22px; display: grid; gap: 4px; }
.stat b { font-family: var(--font-display); font-size: clamp(1.8rem, 3.4vw, 2.6rem); font-weight: 800; line-height: 1; }
.stat span { color: var(--muted); font-size: .92rem; }

/* bento */
.bento { display: grid; grid-template-columns: repeat(6, minmax(0, 1fr)); gap: 16px; }
.card { background: var(--surface); border: 1px solid var(--line); border-radius: 24px; padding: 28px; display: grid; gap: 10px; align-content: start; position: relative; overflow: hidden; transition: transform .25s, box-shadow .25s, border-color .25s; }
.card:hover { transform: translateY(-4px); box-shadow: var(--shadow); border-color: var(--accent-2); }
.card p { color: var(--muted); }
.card .icon { margin-bottom: 10px; }
.card.span2 { grid-column: span 2; }
.card.span3 { grid-column: span 3; }
.card.span4 { grid-column: span 4; }
.card.feature { background: linear-gradient(145deg, var(--accent), color-mix(in srgb, var(--accent) 60%, #000)); color: var(--accent-ink); border-color: transparent; }
.card.feature p, .card.feature .who { color: color-mix(in srgb, var(--accent-ink) 82%, transparent); }
.card.feature .icon { background: color-mix(in srgb, var(--accent-ink) 16%, transparent); color: var(--accent-ink); }
.card.feature::after { content: ""; position: absolute; right: -50px; bottom: -50px; width: 200px; height: 200px; border-radius: 50%; border: 2px dashed color-mix(in srgb, var(--accent-ink) 35%, transparent); }
.who { font-family: var(--font-mono); font-size: .76rem; text-transform: uppercase; letter-spacing: .07em; color: var(--route); }

/* demo builder */
.demo { display: grid; grid-template-columns: minmax(0, 1fr) minmax(0, 1fr); gap: 0; background: var(--surface); border: 1px solid var(--line); border-radius: 28px; overflow: hidden; box-shadow: var(--shadow); }
.demo-pick, .demo-plan { padding: 30px; display: grid; gap: 16px; align-content: start; }
.demo-plan { background: var(--soft); border-left: 1px solid var(--line); }
.places { display: grid; gap: 10px; }
.place { display: flex; align-items: center; justify-content: space-between; gap: 12px; text-align: left; width: 100%; font: inherit; color: var(--ink); background: var(--bg); border: 1px solid var(--line); border-radius: 16px; padding: 14px 16px; cursor: pointer; transition: border-color .2s, transform .15s, background .2s; }
.place:hover { transform: translateX(3px); border-color: var(--accent-2); }
.place b { display: block; font-weight: 600; }
.place small { color: var(--muted); }
.place .add { flex: none; width: 30px; height: 30px; border-radius: 50%; border: 2px solid var(--accent); color: var(--accent); display: grid; place-items: center; font-family: var(--font-mono); font-size: 1.1rem; line-height: 1; transition: background .2s, color .2s; }
.place[aria-pressed="true"] { border-color: var(--accent); background: color-mix(in srgb, var(--accent) 10%, var(--bg)); }
.place[aria-pressed="true"] .add { background: var(--accent); color: var(--accent-ink); }
.plan { list-style: none; margin: 0; padding: 0; display: grid; gap: 10px; counter-reset: p; min-height: 120px; }
.plan li { counter-increment: p; display: grid; grid-template-columns: 34px minmax(0,1fr); gap: 12px; align-items: center; background: var(--surface); border: 1px solid var(--line); border-radius: 14px; padding: 12px 14px; animation: pop .35s ease both; }
.plan li::before { content: counter(p); width: 30px; height: 30px; border-radius: 50%; background: var(--route); color: #1b1200; display: grid; place-items: center; font: 600 .8rem var(--font-mono); }
.plan time { font-family: var(--font-mono); font-size: .74rem; color: var(--route); display: block; }
.plan .empty { grid-template-columns: 1fr; color: var(--muted); background: transparent; border-style: dashed; text-align: center; }
.plan .empty::before { display: none; }
.plan-foot { color: var(--muted); font-size: .82rem; }

/* steps */
.steps { list-style: none; margin: 0; padding: 0; display: grid; grid-template-columns: repeat(3, minmax(0, 1fr)); gap: 16px; counter-reset: step; position: relative; }
.steps li { counter-increment: step; background: var(--surface); border: 1px solid var(--line); border-radius: 24px; padding: 28px; display: grid; gap: 8px; align-content: start; }
.steps li::before { content: counter(step, decimal-leading-zero); font-family: var(--font-display); font-size: 2.8rem; font-weight: 800; line-height: 1; background: linear-gradient(180deg, var(--route), transparent 120%); -webkit-background-clip: text; background-clip: text; color: transparent; }
.steps p { color: var(--muted); }

.cta-band { background: linear-gradient(120deg, var(--accent), var(--accent-2)); color: var(--accent-ink); border-radius: 28px; padding: 48px 44px; display: flex; flex-wrap: wrap; align-items: center; justify-content: space-between; gap: 22px; position: relative; overflow: hidden; }
.cta-band h2 { color: var(--accent-ink); max-width: 18ch; }
.cta-band .btn { background: var(--accent-ink); color: var(--accent); border-color: var(--accent-ink); }
.cta-band::after { content: ""; position: absolute; right: -70px; top: -70px; width: 260px; height: 260px; border-radius: 50%; border: 2px dashed color-mix(in srgb, var(--accent-ink) 45%, transparent); }
.cta-band::before { content: ""; position: absolute; right: 30px; bottom: -80px; width: 200px; height: 200px; border-radius: 50%; background: color-mix(in srgb, var(--accent-ink) 10%, transparent); }
.cta-band > * { position: relative; z-index: 1; }

/* inner page header */
.page-head { display: grid; grid-template-columns: minmax(0, 1fr) minmax(0, .8fr); gap: 32px; align-items: center; background: linear-gradient(145deg, var(--soft), color-mix(in srgb, var(--soft) 55%, var(--bg))); border: 1px solid var(--line); border-radius: 32px; padding: 48px; position: relative; overflow: hidden; }
.page-head::after { content: ""; position: absolute; right: -80px; top: -80px; width: 260px; height: 260px; border-radius: 50%; background: radial-gradient(circle, var(--route-2), transparent 70%); opacity: .35; pointer-events: none; }
.page-head > div { display: grid; gap: 16px; min-width: 0; justify-items: start; }
.page-head .routeart { width: 100%; height: auto; max-height: 210px; position: relative; z-index: 1; }

.cols { display: grid; grid-template-columns: repeat(2, minmax(0, 1fr)); gap: 40px; }
.prose { display: grid; gap: 16px; max-width: 62ch; align-content: start; }
.prose p { color: var(--muted); }
.panel { background: var(--surface); border: 1px solid var(--line); border-radius: 24px; padding: 28px; display: grid; gap: 14px; align-content: start; }
.facts { display: grid; gap: 0; margin: 0; }
.facts div { display: grid; grid-template-columns: 120px minmax(0, 1fr); gap: 12px; padding-block: 12px; border-top: 1px solid var(--line); }
.facts div:first-child { border-top: 0; padding-top: 0; }
.facts dt { font-family: var(--font-mono); font-size: .76rem; text-transform: uppercase; letter-spacing: .06em; color: var(--muted); padding-top: 3px; }
.facts dd { margin: 0; font-weight: 500; overflow-wrap: anywhere; }

/* acronym */
.acro { display: grid; grid-template-columns: repeat(4, minmax(0, 1fr)); gap: 14px; }
.acro > div { background: var(--surface); border: 1px solid var(--line); border-radius: 22px; padding: 22px; display: grid; gap: 4px; transition: transform .25s, border-color .25s; }
.acro > div:hover { transform: translateY(-4px); border-color: var(--route); }
.acro b { font-family: var(--font-display); font-size: 3.4rem; font-weight: 800; line-height: 1; color: var(--route); }
.acro strong { font-family: var(--font-display); font-size: 1.1rem; }
.acro span { color: var(--muted); font-size: .9rem; }
.values { display: grid; grid-template-columns: repeat(3, minmax(0, 1fr)); gap: 16px; }

details { background: var(--surface); border: 1px solid var(--line); border-radius: 18px; padding-inline: 22px; transition: border-color .2s; }
details + details { margin-top: 12px; }
details[open] { border-color: var(--accent-2); }
summary { cursor: pointer; padding-block: 18px; font-family: var(--font-display); font-weight: 700; font-size: 1.15rem; list-style: none; display: flex; justify-content: space-between; align-items: center; gap: 16px; }
summary::-webkit-details-marker { display: none; }
summary::after { content: "+"; flex: none; width: 30px; height: 30px; border-radius: 50%; background: var(--soft); color: var(--accent); display: grid; place-items: center; font-family: var(--font-mono); font-size: 1.2rem; }
details[open] summary::after { content: "–"; background: var(--accent); color: var(--accent-ink); }
details p { color: var(--muted); padding-bottom: 20px; max-width: 64ch; }

/* contact form */
form { display: grid; gap: 14px; }
label { display: grid; gap: 6px; font-weight: 600; font-size: .9rem; }
input, textarea, select { font: inherit; color: var(--ink); background: var(--bg); border: 1px solid var(--line); border-radius: 12px; padding: 12px 14px; width: 100%; }
textarea { min-height: 120px; resize: vertical; }
.copy { font: inherit; font-size: .8rem; font-weight: 600; cursor: pointer; margin-left: 10px; padding: 3px 10px; border-radius: 8px; border: 1px solid var(--accent); color: var(--accent); background: transparent; }
.copy:hover { background: var(--soft); }

footer { border-top: 1px solid var(--line); padding-block: 36px 44px; display: grid; gap: 12px; color: var(--muted); font-size: .9rem; max-width: 1120px; margin-inline: auto; }
footer .row { display: flex; flex-wrap: wrap; gap: 8px 24px; justify-content: space-between; align-items: center; }

/* reveal */
.reveal { opacity: 0; transform: translateY(22px); transition: opacity .7s ease, transform .7s ease; }
.reveal.in { opacity: 1; transform: none; }

@media (max-width: 900px) {
  .hero, .page-head, .cols, .demo { grid-template-columns: minmax(0, 1fr); }
  .hero { gap: 44px; }
  .hero-art .routeart { inset: 0; width: 100%; height: 100%; }
  .hero-wrap { padding: 34px 20px 40px; border-radius: 24px; }
  .page-head { padding: 28px 20px; }
  .stats, .acro { grid-template-columns: repeat(2, minmax(0, 1fr)); }
  .steps, .values { grid-template-columns: minmax(0, 1fr); }
  .bento { grid-template-columns: minmax(0, 1fr); }
  .card.span2, .card.span3, .card.span4 { grid-column: auto; }
  .demo-plan { border-left: 0; border-top: 1px solid var(--line); }
  .section { margin-top: 64px; }
  .cta-band { padding: 30px 24px; }
  .facts div { grid-template-columns: minmax(0, 1fr); gap: 2px; }
  .page-head .routeart { max-height: 140px; }
  .mini { left: 6px; }
  nav ul { border-radius: 18px; }
}
@media (prefers-reduced-motion: reduce) {
  html { scroll-behavior: auto; }
  .phone, .mini, .track, .pill i { animation: none; }
  .reveal { opacity: 1; transform: none; transition: none; }
}
</style>
</head>
<body>

<svg width="0" height="0" style="position:absolute" aria-hidden="true" focusable="false">
  <symbol id="pin" viewBox="0 0 32 32">
    <path d="M16 2C9.9 2 5 6.8 5 12.8 5 21 16 30 16 30s11-9 11-17.2C27 6.8 22.1 2 16 2z" fill="currentColor"/>
    <circle cx="16" cy="12.5" r="4.2" fill="var(--bg)"/>
  </symbol>
  <symbol id="i-search" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><circle cx="11" cy="11" r="7"/><path d="m20 20-3.5-3.5"/></symbol>
  <symbol id="i-route" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><circle cx="6" cy="19" r="2"/><circle cx="18" cy="5" r="2"/><path d="M8 19h6a4 4 0 0 0 0-8h-4a4 4 0 0 1 0-8h6"/></symbol>
  <symbol id="i-bookmark" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M6 3h12v18l-6-4-6 4z"/></symbol>
  <symbol id="i-phone" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><rect x="7" y="2" width="10" height="20" rx="2.5"/><path d="M11 18h2"/></symbol>
  <symbol id="i-check" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.4" stroke-linecap="round" stroke-linejoin="round"><path d="m5 12 5 5 9-10"/></symbol>
  <symbol id="i-arrow" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.2" stroke-linecap="round" stroke-linejoin="round"><path d="M5 12h14m-6-6 6 6-6 6"/></symbol>
  <symbol id="i-clock" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><circle cx="12" cy="12" r="9"/><path d="M12 7v5l3 2"/></symbol>
  <symbol id="i-theme" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><circle cx="12" cy="12" r="9"/><path d="M12 3v18" /><path d="M12 3a9 9 0 0 1 0 18z" fill="currentColor"/></symbol>
  <symbol id="routemap" viewBox="0 0 600 300">
    <g fill="none" stroke="var(--line)" stroke-width="2">
      <path d="M-10 230C90 190 150 250 260 220S430 150 610 200"/>
      <path d="M-10 190C100 150 170 215 270 185S440 110 610 160"/>
      <path d="M-10 150C110 110 190 180 285 150S450 70 610 120"/>
      <path d="M-10 110C120 70 210 145 300 115S460 30 610 80"/>
      <path d="M-10 70C130 30 230 110 315 80S470 -10 610 40"/>
    </g>
    <path class="rline" d="M70 250C140 190 190 230 250 175S350 150 400 105S500 90 540 45" fill="none" stroke="var(--route)" stroke-width="4" stroke-linecap="round" stroke-dasharray="2 12"/>
    <circle cx="70" cy="250" r="9" fill="var(--accent)"/>
    <circle cx="250" cy="175" r="9" fill="var(--accent)"/>
    <circle cx="400" cy="105" r="9" fill="var(--accent)"/>
    <circle cx="540" cy="45" r="9" fill="var(--route)"/>
    <circle cx="70" cy="250" r="16" fill="none" stroke="var(--accent)" stroke-width="2"/>
    <circle cx="540" cy="45" r="18" fill="none" stroke="var(--route)" stroke-width="2" opacity=".6"/>
  </symbol>
</svg>

<header class="site-header">
  <div class="bar">
    <a class="brand" href="#home" aria-label="RIDE home">
      <svg viewBox="0 0 32 32" aria-hidden="true" style="color: var(--accent)"><use href="#pin"/></svg>
      RIDE
    </a>
    <div class="nav-right">
      <nav aria-label="Main">
        <ul>
          <li><a href="#home" data-link="home">Home</a></li>
          <li><a href="#about" data-link="about">About Us</a></li>
          <li><a href="#services" data-link="services">Services</a></li>
          <li><a href="#faq" data-link="faq">FAQ</a></li>
          <li><a href="#contact" data-link="contact">Contact Us</a></li>
        </ul>
      </nav>
      <button class="theme" id="theme" type="button" aria-label="Toggle light and dark theme"><svg viewBox="0 0 24 24" aria-hidden="true"><use href="#i-theme"/></svg></button>
    </div>
  </div>
</header>

<main class="wrap" id="main">

  <!-- HOME -->
  <section class="page" data-page="home" aria-labelledby="h-home">
    <div class="hero-wrap">
      <div class="hero">
        <div class="hero-copy">
          <span class="pill"><i></i> Now exploring Calapan City, Oriental Mindoro</span>
          <h1 id="h-home" tabindex="-1">Plan your day in <span class="grad">Calapan City.</span></h1>
          <p class="lead">RIDE, the Real-time Itinerary and Destination Explorer, helps visitors and locals find places to go in Calapan City and arrange them into an itinerary they can follow on their phone.</p>
          <div class="actions">
            <a class="btn primary" href="https://rideapp-web-4pfi.onrender.com/" target="_blank" rel="noopener">Open the RIDE app <svg viewBox="0 0 24 24" aria-hidden="true"><use href="#i-arrow"/></svg></a>
            <a class="btn ghost" href="#services">See what RIDE does</a>
          </div>
          <div class="hero-note">
            <span><svg viewBox="0 0 24 24" aria-hidden="true"><use href="#i-check"/></svg>Free to open in your browser</span>
            <span><svg viewBox="0 0 24 24" aria-hidden="true"><use href="#i-check"/></svg>Nothing to download</span>
            <span><svg viewBox="0 0 24 24" aria-hidden="true"><use href="#i-check"/></svg>Made for phones</span>
          </div>
        </div>
        <div class="hero-art">
          <svg class="routeart" viewBox="0 0 600 300" preserveAspectRatio="xMidYMid slice" aria-hidden="true"><use href="#routemap"/></svg>
          <div class="phone" role="img" aria-label="Sample itinerary for a day in Calapan City">
            <div class="notch"></div>
            <div class="phone-top"><strong>Saturday in Calapan</strong><span class="tag">Sample</span></div>
            <ul class="stops">
              <li data-n="1" style="animation-delay:.1s"><time>08:00</time><b>Calapan Port</b><span>Arrive, get oriented, pick up a map</span></li>
              <li data-n="2" style="animation-delay:.25s"><time>10:00</time><b>Mangyan Heritage Center</b><span>Culture and local history</span></li>
              <li data-n="3" style="animation-delay:.4s"><time>12:30</time><b>Lunch at the city market</b><span>Local dishes, short walk from the center</span></li>
              <li data-n="4" style="animation-delay:.55s"><time>15:30</time><b>Waterfront walk</b><span>Easy stop before the evening ferry</span></li>
            </ul>
            <p class="phone-note">Sample plan for illustration. Build your own in the app.</p>
          </div>
          <div class="mini"><span class="icon"><svg viewBox="0 0 24 24" aria-hidden="true"><use href="#i-bookmark"/></svg></span><span>Saved places<small>Your favorites, in one list</small></span></div>
        </div>
      </div>
    </div>

    <div class="marquee reveal" aria-label="Kinds of places you can look for">
      <div class="track" aria-hidden="true">
        <span class="chip">Heritage and culture</span><span class="chip">Local food</span><span class="chip">City market</span><span class="chip">Waterfront</span><span class="chip">Churches and landmarks</span><span class="chip">Parks and plazas</span><span class="chip">Port and transport</span><span class="chip">Souvenirs</span>
        <span class="chip">Heritage and culture</span><span class="chip">Local food</span><span class="chip">City market</span><span class="chip">Waterfront</span><span class="chip">Churches and landmarks</span><span class="chip">Parks and plazas</span><span class="chip">Port and transport</span><span class="chip">Souvenirs</span>
      </div>
    </div>

    <div class="stats reveal">
      <div class="stat"><b>1</b><span>City, covered properly</span></div>
      <div class="stat"><b>3</b><span>Steps from browsing to a plan</span></div>
      <div class="stat"><b>0</b><span>Downloads or app store visits</span></div>
      <div class="stat"><b>24/7</b><span>Open in any browser</span></div>
    </div>

    <div class="section reveal">
      <div class="section-head">
        <p class="eyebrow">What RIDE gives you</p>
        <h2>One place to decide where to go.</h2>
      </div>
      <div class="bento">
        <div class="card feature span4"><span class="icon"><svg viewBox="0 0 24 24" aria-hidden="true"><use href="#i-route"/></svg></span><h3>Plan an itinerary</h3><p>Put the places you pick into a day plan, in the order you want to visit them. Spend less time deciding and more time out in the city.</p></div>
        <div class="card span2"><span class="icon"><svg viewBox="0 0 24 24" aria-hidden="true"><use href="#i-search"/></svg></span><h3>Discover</h3><p>Browse places in Calapan City before you leave your hotel.</p></div>
        <div class="card span2"><span class="icon"><svg viewBox="0 0 24 24" aria-hidden="true"><use href="#i-bookmark"/></svg></span><h3>Save</h3><p>Keep places you like in one list and come back when you are ready.</p></div>
        <div class="card span4"><span class="icon"><svg viewBox="0 0 24 24" aria-hidden="true"><use href="#i-phone"/></svg></span><h3>Made for the road</h3><p>RIDE runs in your phone's browser and is designed for small screens first, so your plan goes where you go. It also works on laptops and desktops.</p></div>
      </div>
    </div>

    <div class="section reveal">
      <div class="section-head">
        <p class="eyebrow">Try it</p>
        <h2>Build a sample day in a few taps.</h2>
        <p class="lead">Pick places on the left and watch your plan take shape. This is a small preview of what the app does.</p>
      </div>
      <div class="demo">
        <div class="demo-pick">
          <h3>Choose your stops</h3>
          <div class="places" id="places">
            <button class="place" type="button" aria-pressed="false" data-name="Calapan Port" data-note="Arrive and get oriented"><span><b>Calapan Port</b><small>Arrival point</small></span><span class="add" aria-hidden="true">+</span></button>
            <button class="place" type="button" aria-pressed="false" data-name="Mangyan Heritage Center" data-note="Culture and local history"><span><b>Mangyan Heritage Center</b><small>Culture and history</small></span><span class="add" aria-hidden="true">+</span></button>
            <button class="place" type="button" aria-pressed="false" data-name="City market lunch" data-note="Local dishes near the center"><span><b>City market lunch</b><small>Food</small></span><span class="add" aria-hidden="true">+</span></button>
            <button class="place" type="button" aria-pressed="false" data-name="Waterfront walk" data-note="Easy stop before the ferry"><span><b>Waterfront walk</b><small>Outdoors</small></span><span class="add" aria-hidden="true">+</span></button>
          </div>
        </div>
        <div class="demo-plan">
          <h3>Your plan</h3>
          <ol class="plan" id="plan" aria-live="polite"><li class="empty">Tap a place to add it here.</li></ol>
          <p class="plan-foot">Sample only. The real planner lives in the app.</p>
          <a class="btn primary" href="https://rideapp-web-4pfi.onrender.com/" target="_blank" rel="noopener" style="justify-self:start">Plan for real <svg viewBox="0 0 24 24" aria-hidden="true"><use href="#i-arrow"/></svg></a>
        </div>
      </div>
    </div>

    <div class="section reveal">
      <div class="section-head">
        <p class="eyebrow">How it works</p>
        <h2>From first search to finished plan.</h2>
      </div>
      <ol class="steps">
        <li><h3>Browse places</h3><p>Open RIDE and look through places in Calapan City.</p></li>
        <li><h3>Build your itinerary</h3><p>Add the places you want and arrange them into your day.</p></li>
        <li><h3>Follow it on your phone</h3><p>RIDE is a web app made for mobile screens, so your plan goes where you go.</p></li>
      </ol>
    </div>

    <div class="section reveal">
      <div class="cta-band">
        <h2>Ready to plan your Calapan trip?</h2>
        <a class="btn" href="https://rideapp-web-4pfi.onrender.com/" target="_blank" rel="noopener">Open the RIDE app <svg viewBox="0 0 24 24" aria-hidden="true"><use href="#i-arrow"/></svg></a>
      </div>
    </div>
  </section>

  <!-- ABOUT -->
  <section class="page" data-page="about" aria-labelledby="h-about" hidden>
    <div class="page-head">
      <div>
        <p class="eyebrow">About Us</p>
        <h1 id="h-about" tabindex="-1">A local trip planner built for <span class="grad">Calapan City.</span></h1>
        <p class="lead">RIDE started as a second-year student project with one aim: make Calapan City easier to explore.</p>
      </div>
      <svg class="routeart" viewBox="0 0 600 300" role="img" aria-label="Illustration of a route with stops"><use href="#routemap"/></svg>
    </div>

    <div class="section reveal">
      <div class="section-head">
        <p class="eyebrow">What the name means</p>
        <h2>Real-time Itinerary and Destination Explorer.</h2>
      </div>
      <div class="acro">
        <div><b>R</b><strong>Real-time</strong><span>Plans for the day you are actually in.</span></div>
        <div><b>I</b><strong>Itinerary</strong><span>Stops arranged in the order you will visit.</span></div>
        <div><b>D</b><strong>Destination</strong><span>Places worth your time in Calapan City.</span></div>
        <div><b>E</b><strong>Explorer</strong><span>Made for visitors and locals who like to wander.</span></div>
      </div>
    </div>

    <div class="section reveal">
      <div class="cols">
        <div class="prose">
          <h2>Our background</h2>
          <p>Calapan City is the capital of Oriental Mindoro and a port city that many travelers pass through. Information about what to see and how to fit it into a day is spread across social media posts, word of mouth and scattered web pages.</p>
          <p>RIDE brings that information into one mobile-friendly web app. Visitors and residents can discover places, plan an itinerary and save their favorites in one place.</p>
        </div>
        <div class="prose">
          <h2>Our mission</h2>
          <p>To help people enjoy Calapan City by making places easy to find and trips easy to plan.</p>
        </div>
      </div>
    </div>

    <div class="section reveal">
      <div class="section-head"><p class="eyebrow">What we value</p><h2>Three ideas behind every screen.</h2></div>
      <div class="values">
        <div class="card"><h3>Local first</h3><p>We focus on Calapan City and do it well before covering anywhere else.</p></div>
        <div class="card"><h3>Simple to use</h3><p>A visitor should be able to build a plan in a few taps.</p></div>
        <div class="card"><h3>Made for phones</h3><p>Most people plan on the go, so RIDE is designed for small screens first.</p></div>
      </div>
    </div>

    <div class="section reveal">
      <div class="panel">
        <h3>RIDE at a glance</h3>
        <dl class="facts">
          <div><dt>Name</dt><dd>RIDE: Real-time Itinerary and Destination Explorer</dd></div>
          <div><dt>Type</dt><dd>Mobile-friendly web app for trip planning</dd></div>
          <div><dt>Coverage</dt><dd>Calapan City, Oriental Mindoro, Philippines</dd></div>
          <div><dt>Origin</dt><dd>Second-year student project</dd></div>
        </dl>
      </div>
    </div>
  </section>

  <!-- SERVICES -->
  <section class="page" data-page="services" aria-labelledby="h-services" hidden>
    <div class="page-head">
      <div>
        <p class="eyebrow">Products and Services</p>
        <h1 id="h-services" tabindex="-1">What <span class="grad">RIDE</span> offers.</h1>
        <p class="lead">Everything you need to go from "where should we go?" to a plan you can follow.</p>
      </div>
      <svg class="routeart" viewBox="0 0 600 300" role="img" aria-label="Illustration of a route with stops"><use href="#routemap"/></svg>
    </div>

    <div class="section reveal">
      <div class="bento">
        <div class="card feature span3"><span class="icon"><svg viewBox="0 0 24 24" aria-hidden="true"><use href="#i-search"/></svg></span><h3>Place discovery</h3><span class="who">For visitors and locals</span><p>Browse places in Calapan City and decide what fits your day. Use it when you arrive at the port with a few hours to spare, or when you want to see your own city again.</p></div>
        <div class="card span3"><span class="icon"><svg viewBox="0 0 24 24" aria-hidden="true"><use href="#i-route"/></svg></span><h3>Itinerary planning</h3><span class="who">For trip planners</span><p>Turn the places you like into a day plan. Arrange the stops in the order you will visit them so you spend less time deciding and more time out.</p></div>
        <div class="card span3"><span class="icon"><svg viewBox="0 0 24 24" aria-hidden="true"><use href="#i-bookmark"/></svg></span><h3>Saved places</h3><span class="who">For anyone still deciding</span><p>Keep the places you want to remember in a Saved list. Come back later, compare your options and add them to a plan when you are ready.</p></div>
        <div class="card span3"><span class="icon"><svg viewBox="0 0 24 24" aria-hidden="true"><use href="#i-phone"/></svg></span><h3>Mobile web app</h3><span class="who">For people on the move</span><p>RIDE runs in your phone's browser, so there is nothing to download from an app store. It is designed for small screens and can be added to your phone's home screen.</p></div>
      </div>
    </div>

    <div class="section reveal">
      <div class="cta-band">
        <h2>Try RIDE for your next trip.</h2>
        <a class="btn" href="https://rideapp-web-4pfi.onrender.com/" target="_blank" rel="noopener">Open the RIDE app <svg viewBox="0 0 24 24" aria-hidden="true"><use href="#i-arrow"/></svg></a>
      </div>
    </div>
  </section>

  <!-- FAQ -->
  <section class="page" data-page="faq" aria-labelledby="h-faq" hidden>
    <div class="page-head">
      <div>
        <p class="eyebrow">Frequently Asked Questions</p>
        <h1 id="h-faq" tabindex="-1">Quick answers about <span class="grad">RIDE.</span></h1>
        <p class="lead">Can't find what you need? Visit the Contact Us page.</p>
      </div>
      <svg class="routeart" viewBox="0 0 600 300" role="img" aria-label="Illustration of a route with stops"><use href="#routemap"/></svg>
    </div>

    <div class="section reveal">
      <div>
        <details open>
          <summary>What is RIDE?</summary>
          <p>RIDE is a web app for exploring Calapan City, Oriental Mindoro. You can discover places and plan an itinerary around them.</p>
        </details>
        <details>
          <summary>Do I need to download anything?</summary>
          <p>No. RIDE opens in your phone or computer browser. On a phone you can also add it to your home screen for quicker access.</p>
        </details>
        <details>
          <summary>Which area does RIDE cover?</summary>
          <p>RIDE focuses on Calapan City in Oriental Mindoro, Philippines.</p>
        </details>
        <details>
          <summary>How do I keep places I like?</summary>
          <p>Use the Saved page in the app to keep your favorite places in one list. You can go back to it any time and use it to build your itinerary.</p>
        </details>
        <details>
          <summary>Does RIDE work on my phone?</summary>
          <p>Yes. RIDE is designed for mobile screens first and also works on laptops and desktops.</p>
        </details>
        <details>
          <summary>The app takes a moment to open. Is that normal?</summary>
          <p>The first visit after a quiet period can load a little slower while the app wakes up. Give it a few seconds and it will be ready.</p>
        </details>
        <details>
          <summary>How do I report a problem or suggest a place?</summary>
          <p>Send us a message using the form on the Contact Us page. Tell us what you saw and which page you were on, and we will look into it.</p>
        </details>
      </div>
    </div>
  </section>

  <!-- CONTACT -->
  <section class="page" data-page="contact" aria-labelledby="h-contact" hidden>
    <div class="page-head">
      <div>
        <p class="eyebrow">Contact Us</p>
        <h1 id="h-contact" tabindex="-1">Get in touch with the <span class="grad">RIDE team.</span></h1>
        <p class="lead">Questions, feedback or a place we should add? We would like to hear from you.</p>
      </div>
      <svg class="routeart" viewBox="0 0 600 300" role="img" aria-label="Illustration of a route with stops"><use href="#routemap"/></svg>
    </div>

    <div class="section reveal">
      <div class="cols">
        <div class="panel">
          <h3>Contact details</h3>
          <dl class="facts">
            <div><dt>Email</dt><dd><span id="c-email">evitafayelmasculino.bsit@gmail.com</span><button class="copy" type="button" data-copy="c-email">Copy</button></dd></div>
            <div><dt>Phone</dt><dd><span id="c-phone">+63 900 000 0000</span><button class="copy" type="button" data-copy="c-phone">Copy</button></dd></div>
            <div><dt>Location</dt><dd>Calapan City, Oriental Mindoro, Philippines</dd></div>
            <div><dt>Web app</dt><dd><a href="https://rideapp-web-4pfi.onrender.com/" target="_blank" rel="noopener">rideapp-web-4pfi.onrender.com</a></dd></div>
          </dl>
        </div>
        <div class="panel">
          <h3>Send a message</h3>
          <form id="msg">
            <label>Your name<input name="name" autocomplete="name" required></label>
            <label>Topic
              <select name="topic"><option>Question</option><option>Problem with the app</option><option>Suggest a place</option><option>Feedback</option></select>
            </label>
            <label>Message<textarea name="body" placeholder="For a problem, tell us which page you were on and what happened. For a place, send its name and where it is." required></textarea></label>
            <button class="btn primary" type="submit" style="justify-self:start">Open in my email app</button>
          </form>
        </div>
      </div>
    </div>
  </section>
</main>

<footer>
  <div class="row">
    <b style="color:var(--ink);font-family:var(--font-display);font-size:1.2rem">RIDE</b>
    <span>Discover places in Calapan City, Oriental Mindoro, and plan your itinerary.</span>
  </div>
  <div class="row">
    <span>© 2026 RIDE. A second-year student project.</span>
    <span>evitafayelmasculino.bsit@gmail.com · +63 900 000 0000</span>
  </div>
</footer>

<script>
(function () {
  var pages = ["home", "about", "services", "faq", "contact"];
  var sections = document.querySelectorAll("[data-page]");
  var links = document.querySelectorAll("[data-link]");
  var first = true;
  var io = null;

  function observe() {
    var els = document.querySelectorAll("[data-page]:not([hidden]) .reveal:not(.in)");
    if (!("IntersectionObserver" in window)) { els.forEach(function (e) { e.classList.add("in"); }); return; }
    if (!io) io = new IntersectionObserver(function (entries) {
      entries.forEach(function (en) { if (en.isIntersecting) { en.target.classList.add("in"); io.unobserve(en.target); } });
    }, { threshold: 0.12 });
    els.forEach(function (e) { io.observe(e); });
  }

  function show() {
    var name = (location.hash || "").replace("#", "");
    if (pages.indexOf(name) === -1) name = "home";
    sections.forEach(function (s) { s.hidden = s.getAttribute("data-page") !== name; });
    links.forEach(function (a) {
      if (a.getAttribute("data-link") === name) a.setAttribute("aria-current", "page");
      else a.removeAttribute("aria-current");
    });
    if (!first) {
      window.scrollTo(0, 0);
      var h = document.querySelector('[data-page="' + name + '"] h1');
      if (h) h.focus({ preventScroll: true });
    }
    first = false;
    observe();
  }
  window.addEventListener("hashchange", show);
  show();

  /* theme toggle */
  var root = document.documentElement;
  document.getElementById("theme").addEventListener("click", function () {
    var cur = root.getAttribute("data-theme");
    if (!cur) cur = window.matchMedia("(prefers-color-scheme: dark)").matches ? "dark" : "light";
    root.setAttribute("data-theme", cur === "dark" ? "light" : "dark");
  });

  /* sample itinerary builder */
  var plan = document.getElementById("plan");
  var picked = [];
  var times = ["08:00", "10:00", "12:30", "15:30", "17:30"];
  function render() {
    plan.innerHTML = "";
    if (!picked.length) {
      var li = document.createElement("li"); li.className = "empty"; li.textContent = "Tap a place to add it here."; plan.appendChild(li); return;
    }
    picked.forEach(function (p, i) {
      var li = document.createElement("li");
      var d = document.createElement("div");
      var t = document.createElement("time"); t.textContent = times[i] || "";
      var b = document.createElement("b"); b.textContent = p.name;
      var s = document.createElement("span"); s.textContent = p.note; s.style.cssText = "display:block;color:var(--muted);font-size:.86rem";
      d.appendChild(t); d.appendChild(b); d.appendChild(s); li.appendChild(d); plan.appendChild(li);
    });
  }
  document.querySelectorAll(".place").forEach(function (btn) {
    btn.addEventListener("click", function () {
      var name = btn.getAttribute("data-name");
      var idx = picked.findIndex(function (p) { return p.name === name; });
      if (idx > -1) { picked.splice(idx, 1); btn.setAttribute("aria-pressed", "false"); btn.querySelector(".add").textContent = "+"; }
      else { picked.push({ name: name, note: btn.getAttribute("data-note") }); btn.setAttribute("aria-pressed", "true"); btn.querySelector(".add").textContent = "✓"; }
      render();
    });
  });

  /* contact form -> mailto */
  document.getElementById("msg").addEventListener("submit", function (e) {
    e.preventDefault();
    var f = e.target;
    var subject = "RIDE: " + f.topic.value;
    var body = f.body.value + "\n\n— " + f.name.value;
    location.href = "mailto:evitafayelmasculino.bsit@gmail.com?subject=" + encodeURIComponent(subject) + "&body=" + encodeURIComponent(body);
  });

  /* copy buttons */
  document.querySelectorAll(".copy").forEach(function (btn) {
    btn.addEventListener("click", function () {
      var el = document.getElementById(btn.getAttribute("data-copy"));
      var text = el.textContent;
      function done() { btn.textContent = "Copied"; setTimeout(function () { btn.textContent = "Copy"; }, 1500); }
      function select() {
        var r = document.createRange(); r.selectNodeContents(el);
        var s = window.getSelection(); s.removeAllRanges(); s.addRange(r);
      }
      try { navigator.clipboard.writeText(text).then(done, select); } catch (e) { select(); }
    });
  });
})();
</script>

</body>
</html>
