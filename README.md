# Jones-Junk-Removal
Junk removal business 
<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Jones Junk Removal | Charlotte Metro Junk Hauling</title>
  <meta name="description" content="Jones Junk Removal provides fast, reliable junk removal in the Charlotte metro area. Call or text for a free quote." />
  <style>
    :root{
      --bg:#0b0f12;
      --card:#0f151a;
      --muted:#a7b3bd;
      --text:#eef3f6;
      --line:rgba(255,255,255,.10);
      --accent:#38d07f; /* clean “eco” green */
      --accent2:#f2c14e; /* warm gold */
      --shadow:0 10px 30px rgba(0,0,0,.35);
      --radius:18px;
      --max:1100px;
    }
    *{box-sizing:border-box}
    html,body{margin:0; padding:0; background:radial-gradient(1200px 700px at 20% -10%, rgba(56,208,127,.18), transparent 60%),
                               radial-gradient(900px 600px at 90% 0%, rgba(242,193,78,.12), transparent 55%),
                               var(--bg);
             color:var(--text); font-family: system-ui, -apple-system, Segoe UI, Roboto, Arial, sans-serif;}
    a{color:inherit}
    .wrap{max-width:var(--max); margin:0 auto; padding:24px}
    header{
      position:sticky; top:0; z-index:50;
      backdrop-filter: blur(10px);
      background:rgba(11,15,18,.65);
      border-bottom:1px solid var(--line);
    }
    .nav{
      display:flex; align-items:center; justify-content:space-between; gap:14px;
      max-width:var(--max); margin:0 auto; padding:14px 24px;
    }
    .brand{
      display:flex; align-items:center; gap:12px; text-decoration:none;
      font-weight:800; letter-spacing:.2px;
    }
    .logoMark{
      width:38px; height:38px; border-radius:12px;
      display:grid; place-items:center;
      background:linear-gradient(135deg, rgba(56,208,127,.28), rgba(242,193,78,.18));
      border:1px solid var(--line);
      box-shadow: var(--shadow);
      font-size:18px;
    }
    .brand small{display:block; font-weight:600; color:var(--muted); margin-top:2px}
    .navLinks{display:flex; gap:14px; flex-wrap:wrap; justify-content:flex-end}
    .navLinks a{
      text-decoration:none; color:var(--muted); font-weight:650; font-size:14px;
      padding:8px 10px; border-radius:12px;
    }
    .navLinks a:hover{color:var(--text); background:rgba(255,255,255,.05)}
    .ctaRow{display:flex; gap:10px; flex-wrap:wrap}
    .btn{
      display:inline-flex; align-items:center; justify-content:center; gap:10px;
      padding:12px 14px; border-radius:14px; text-decoration:none; font-weight:800;
      border:1px solid var(--line); background:rgba(255,255,255,.04);
    }
    .btn:hover{transform:translateY(-1px)}
    .btnPrimary{
      background:linear-gradient(135deg, rgba(56,208,127,.92), rgba(56,208,127,.72));
      color:#08110c; border:0;
    }
    .btnGhost{color:var(--text)}
    .pill{
      display:inline-flex; gap:10px; align-items:center;
      padding:8px 12px; border-radius:999px;
      background:rgba(255,255,255,.05);
      border:1px solid var(--line);
      color:var(--muted); font-weight:650; font-size:13px;
      width:max-content;
    }
    .hero{
      padding:44px 0 26px;
      display:grid; grid-template-columns: 1.2fr .8fr; gap:20px;
      align-items:stretch;
    }
    .heroCard{
      border-radius:var(--radius);
      background:linear-gradient(180deg, rgba(255,255,255,.06), rgba(255,255,255,.03));
      border:1px solid var(--line);
      padding:28px;
      box-shadow: var(--shadow);
      position:relative;
      overflow:hidden;
    }
    .heroCard:before{
      content:"";
      position:absolute; inset:-2px;
      background:radial-gradient(600px 350px at 20% 0%, rgba(56,208,127,.18), transparent 60%),
                 radial-gradient(450px 280px at 100% 20%, rgba(242,193,78,.14), transparent 58%);
      pointer-events:none;
    }
    .heroCard > *{position:relative}
    h1{margin:10px 0 10px; font-size:40px; line-height:1.05; letter-spacing:-.6px}
    .sub{margin:0 0 16px; color:var(--muted); font-size:16px; line-height:1.5}
    .kpis{display:flex; gap:10px; flex-wrap:wrap; margin:16px 0 20px}
    .kpis .pill b{color:var(--text)}
    .heroActions{display:flex; gap:10px; flex-wrap:wrap; margin-top:10px}
    .mini{
      border-radius:var(--radius);
      background:rgba(255,255,255,.03);
      border:1px solid var(--line);
      padding:20px;
      box-shadow: var(--shadow);
    }
    .mini h3{margin:0 0 10px; font-size:16px}
    .mini ul{margin:0; padding-left:18px; color:var(--muted); line-height:1.6}
    section{padding:18px 0}
    .grid3{display:grid; grid-template-columns:repeat(3, 1fr); gap:14px}
    .card{
      border-radius:var(--radius);
      background:rgba(255,255,255,.03);
      border:1px solid var(--line);
      padding:18px;
    }
    .card h3{margin:0 0 8px; font-size:16px}
    .card p{margin:0; color:var(--muted); line-height:1.55}
    .tag{
      display:inline-flex; align-items:center; gap:8px;
      font-size:12px; font-weight:800; letter-spacing:.2px;
      padding:7px 10px; border-radius:999px;
      background:rgba(56,208,127,.10);
      border:1px solid rgba(56,208,127,.25);
      color:#c9ffe3;
      margin-bottom:10px;
    }
    .tag.gold{
      background:rgba(242,193,78,.10);
      border-color:rgba(242,193,78,.25);
      color:#fff1cf;
    }
    .split{
      display:grid; grid-template-columns:1fr 1fr; gap:14px;
      align-items:start;
    }
    .how ol{margin:0; padding-left:18px; color:var(--muted); line-height:1.75}
    .serviceList{display:grid; grid-template-columns:repeat(2, 1fr); gap:10px; margin-top:8px}
    .serviceItem{
      padding:10px 12px; border-radius:14px;
      border:1px solid var(--line);
      background:rgba(255,255,255,.02);
      color:var(--muted); font-weight:700; font-size:14px;
    }
    .serviceItem span{color:var(--text)}
    form{display:grid; gap:10px; margin-top:8px}
    input, textarea{
      width:100%;
      padding:12px 12px;
      border-radius:14px;
      border:1px solid var(--line);
      background:rgba(0,0,0,.25);
      color:var(--text);
      outline:none;
      font-size:14px;
    }
    input::placeholder, textarea::placeholder{color:rgba(167,179,189,.70)}
    textarea{min-height:110px; resize:vertical}
    .formRow{display:grid; grid-template-columns:1fr 1fr; gap:10px}
    .fine{color:var(--muted); font-size:12px; line-height:1.5}
    .footer{
      padding:26px 0 40px;
      color:var(--muted);
      border-top:1px solid var(--line);
      margin-top:18px;
    }
    .footer .cols{display:grid; grid-template-columns:1.2fr .8fr; gap:14px}
    .footer a{color:var(--text); text-decoration:none}
    .footer a:hover{text-decoration:underline}
    .stickyMobileCTA{
      position:fixed; left:0; right:0; bottom:0; z-index:60;
      padding:10px 12px;
      background:rgba(11,15,18,.72);
      border-top:1px solid var(--line);
      backdrop-filter: blur(10px);
      display:none;
    }
    .stickyMobileCTA .row{display:flex; gap:10px}
    .stickyMobileCTA .row a{flex:1}
    .hide{display:none !important}

    @media (max-width: 920px){
      .hero{grid-template-columns:1fr; padding-top:26px}
      h1{font-size:34px}
      .grid3{grid-template-columns:1fr}
      .split{grid-template-columns:1fr}
      .formRow{grid-template-columns:1fr}
      .navLinks{display:none}
      .stickyMobileCTA{display:block}
    }
  </style>
</head>

<body>
  <header>
    <div class="nav">
      <a class="brand" href="#top" aria-label="Jones Junk Removal Home">
        <div class="logoMark">🛻</div>
        <div>
          Jones Junk Removal
          <small>Charlotte Metro • Call or Text</small>
        </div>
      </a>

      <div class="ctaRow">
        <!-- Replace 7045550123 with your real number later -->
        <a class="btn btnPrimary" id="callBtnTop" href="tel:+17045550123">📞 Call</a>
        <a class="btn btnGhost" id="textBtnTop" href="sms:+17045550123">💬 Text</a>
      </div>
    </div>
  </header>

  <main id="top" class="wrap">
    <section class="hero">
      <div class="heroCard">
        <span class="pill">⭐ Fast quotes • Charlotte metro</span>
        <h1>Junk removal that feels easy.</h1>
        <p class="sub">
          We haul away furniture, appliances, yard debris, and cleanouts—quick, respectful, and straightforward.
          Call or text for a free quote.
        </p>

        <div class="kpis">
          <span class="pill"><b>Same-day</b> availability (when open)</span>
          <span class="pill"><b>Up-front</b> pricing</span>
          <span class="pill"><b>Responsible</b> disposal</span>
          <!-- INSURED LINE (ADD LATER):
               When you get insured, remove the "hide" class below. -->
          <span class="pill hide" id="insuredPill"><b>Insured</b> service</span>
        </div>

        <div class="heroActions">
          <a class="btn btnPrimary" id="callBtnHero" href="tel:+17045550123">📞 Call for a quote</a>
          <a class="btn btnGhost" id="textBtnHero" href="sms:+17045550123">💬 Text a photo</a>
          <a class="btn btnGhost" href="#quote">🧾 Request a quote</a>
        </div>

        <p class="fine" style="margin-top:14px">
          Tip: texting a photo + your address gets the fastest estimate.
        </p>
      </div>

      <aside class="mini">
        <h3>What we take</h3>
        <ul>
          <li>Furniture, mattresses, box springs</li>
          <li>Appliances & bulky items</li>
          <li>Garage, attic, storage unit cleanouts</li>
          <li>Yard debris & brush</li>
          <li>Light construction debris (ask first)</li>
        </ul>
        <div style="height:12px"></div>
        <h3>What to expect</h3>
        <ul>
          <li>Clear communication</li>
          <li>Careful removal (no damage chaos)</li>
          <li>Respectful, local service</li>
        </ul>
      </aside>
    </section>

    <section id="services">
      <div class="grid3">
        <div class="card">
          <div class="tag">🏠 Residential</div>
          <h3>Home junk removal</h3>
          <p>Furniture, mattresses, appliances, and general clutter—gone without the headache.</p>
        </div>
        <div class="card">
          <div class="tag gold">🏢 Small commercial</div>
          <h3>Office & property cleanouts</h3>
          <p>Move-outs, storage cleanouts, and landlord/property turnovers. Quick and reliable.</p>
        </div>
        <div class="card">
          <div class="tag">🌿 Responsible disposal</div>
          <h3>Donate / recycle when possible</h3>
          <p>We aim to dispose responsibly and keep usable items out of the landfill when we can.</p>
        </div>
      </div>

      <div class="card" style="margin-top:14px">
        <h3>Popular haul-aways</h3>
        <div class="serviceList" aria-label="Service list">
          <div class="serviceItem"><span>🛋️</span> Couch & furniture removal</div>
          <div class="serviceItem"><span>🧺</span> Appliance removal</div>
          <div class="serviceItem"><span>🛏️</span> Mattress removal</div>
          <div class="serviceItem"><span>📦</span> Garage cleanouts</div>
          <div class="serviceItem"><span>🏚️</span> Move-out cleanouts</div>
          <div class="serviceItem"><span>🌲</span> Yard debris & brush</div>
        </div>
        <p class="fine" style="margin-top:10px">
          Not sure if we take it? Text a photo and we’ll tell you.
        </p>
      </div>
    </section>

    <section class="split">
      <div class="card how" id="how">
        <h3>How it works</h3>
        <ol>
          <li><b>Call or text</b> us what you need removed (photos help).</li>
          <li>We give you a <b>clear quote</b> based on volume and item type.</li>
          <li>We show up, load it, and <b>haul it away</b>.</li>
        </ol>
        <div style="height:10px"></div>
        <p class="fine">
          We’ll always confirm pricing before we start loading.
        </p>
      </div>

      <div class="card" id="area">
        <h3>Service area</h3>
        <p class="sub" style="margin:0">
          We serve the <b>Charlotte metro</b> and nearby areas (depending on the job).
        </p>
        <div style="height:10px"></div>
        <div class="serviceList" style="grid-template-columns:repeat(2,1fr)">
          <div class="serviceItem"><span>📍</span> Charlotte</div>
          <div class="serviceItem"><span>📍</span> Matthews</div>
          <div class="serviceItem"><span>📍</span> Pineville</div>
          <div class="serviceItem"><span>📍</span> Ballantyne</div>
          <div class="serviceItem"><span>📍</span> Huntersville</div>
          <div class="serviceItem"><span>📍</span> Concord</div>
        </div>
        <p class="fine" style="margin-top:10px">
          Outside these? Text your zip code and we’ll confirm.
        </p>
      </div>
    </section>

    <section id="quote">
      <div class="card">
        <h3>Request a quote</h3>
        <p class="sub" style="margin-top:0">
          Fill this out and we’ll respond ASAP. (You can also text photos for the fastest estimate.)
        </p>

        <form id="quoteForm">
          <div class="formRow">
            <input name="name" placeholder="Your name" autocomplete="name" />
            <input name="phone" placeholder="Phone number" autocomplete="tel" />
          </div>
          <div class="formRow">
            <input name="address" placeholder="Pickup location (optional)" autocomplete="street-address" />
            <input name="timeline" placeholder="When do you need it removed? (ex: today / this weekend)" />
          </div>
          <textarea name="details" placeholder="What needs to be removed? (items + any photos you’ll text)"></textarea>

          <button class="btn btnPrimary" type="submit">Send quote request</button>

          <p class="fine">
            This form opens your email app to send the request. Later, we can upgrade it to a real form that sends
            directly to your inbox without the customer needing email.
          </p>
        </form>
      </div>
    </section>

    <section>
      <div class="card">
        <h3>Ready to clear the clutter?</h3>
        <p class="sub" style="margin-top:0">
          Call or text <b>Jones Junk Removal</b> for a quick quote in the Charlotte metro area.
        </p>
        <div class="heroActions">
          <a class="btn btnPrimary" id="callBtnBottom" href="tel:+17045550123">📞 Call</a>
          <a class="btn btnGhost" id="textBtnBottom" href="sms:+17045550123">💬 Text</a>
        </div>
      </div>
    </section>

    <footer class="footer">
      <div class="cols">
        <div>
          <div style="font-weight:900; color:var(--text)">Jones Junk Removal</div>
          <div class="fine">Charlotte Metro • Call or Text</div>
          <div class="fine" style="margin-top:8px">
            © <span id="year"></span> Jones Junk Removal. All rights reserved.
          </div>
        </div>
        <div style="text-align:left">
          <div class="fine"><b>Contact</b></div>
          <div class="fine" style="margin-top:6px">
            Phone: <a id="phoneLink" href="tel:+17045550123">(704) 555-0123</a><br/>
            Text: <a id="textLink" href="sms:+17045550123">(704) 555-0123</a>
          </div>
          <div class="fine" style="margin-top:10px">
            Want “Insured” on the site later? We’ll switch it on after your policy is active.
          </div>
        </div>
      </div>
    </footer>
  </main>

  <!-- Mobile sticky CTA -->
  <div class="stickyMobileCTA">
    <div class="row">
      <a class="btn btnPrimary" href="tel:+17045550123">📞 Call</a>
      <a class="btn btnGhost" href="sms:+17045550123">💬 Text</a>
    </div>
  </div>

  <script>
    // Set current year
    document.getElementById("year").textContent = new Date().getFullYear();

    // Quote form: opens user's email client via mailto (simple pre-launch approach)
    const form = document.getElementById("quoteForm");
    form.addEventListener("submit", function(e){
      e.preventDefault();

      const data = new FormData(form);
      const name = (data.get("name") || "").toString().trim();
      const phone = (data.get("phone") || "").toString().trim();
      const address = (data.get("address") || "").toString().trim();
      const timeline = (data.get("timeline") || "").toString().trim();
      const details = (data.get("details") || "").toString().trim();

      // TODO: Replace with your real email later
      const toEmail = "youremail@example.com";
      const subject = encodeURIComponent("Quote Request - Jones Junk Removal");
      const body = encodeURIComponent(
        `Name: ${name}\n` +
        `Phone: ${phone}\n` +
        `Address: ${address}\n` +
        `When Needed: ${timeline}\n\n` +
        `Details:\n${details}\n`
      );

      window.location.href = `mailto:${toEmail}?subject=${subject}&body=${body}`;
    });

    // OPTIONAL: Turn on the "Insured" pill later by removing the "hide" class:
    // document.getElementById("insuredPill").classList.remove("hide");
  </script>
</body>
</html>
