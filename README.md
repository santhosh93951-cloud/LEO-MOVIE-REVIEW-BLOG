
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>LEO — Movie Review (Lokesh Kanagaraj | 2023)</title>
  <meta name="description" content="A detailed review of 'Leo' (2023) directed by Lokesh Kanagaraj — performances, direction, cinematography, music and critical verdict." />

  <!-- Google Font (optional) -->
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700;800&display=swap" rel="stylesheet">

  <style>
    :root{
      --bg: #0f1720;
      --card: #0b1220;
      --muted: #9aa4b2;
      --accent: #e74b24;
      --glass: rgba(255,255,255,0.04);
      --radius: 12px;
      --max-width: 1100px;
      color-scheme: dark;
    }

    *{box-sizing:border-box}
    html,body{height:100%}
    body{
      margin:0;
      font-family: "Inter", system-ui, -apple-system, "Segoe UI", Roboto, "Helvetica Neue", Arial;
      background: linear-gradient(180deg,#07111a 0%, #071218 60%, #0b0f14 100%);
      color:#e7eef6;
      -webkit-font-smoothing:antialiased;
      -moz-osx-font-smoothing:grayscale;
      line-height:1.45;
      padding:40px 20px;
      display:flex;
      justify-content:center;
      align-items: flex-start;
      gap:24px;
    }

    .container{
      width:100%;
      max-width:var(--max-width);
    }

    header.page-header{
      display:flex;
      gap:20px;
      align-items:flex-start;
      margin-bottom:22px;
    }

    .poster{
      min-width:170px;
      width:220px;
      aspect-ratio:2/3;
      border-radius:10px;
      overflow:hidden;
      box-shadow:0 8px 30px rgba(0,0,0,0.7);
      flex-shrink:0;
      background:
        linear-gradient(180deg, rgba(0,0,0,0.35), rgba(0,0,0,0.6)),
        url('https://via.placeholder.com/440x660?text=LEO+Poster') center/cover no-repeat;
    }

    .meta{
      flex:1;
      display:flex;
      flex-direction:column;
      gap:8px;
    }

    .title{
      display:flex;
      flex-direction:column;
      gap:4px;
    }
    .title h1{
      margin:0;
      font-size: clamp(20px, 3.6vw, 34px);
      letter-spacing: -0.02em;
    }
    .sub{
      color:var(--muted);
      font-size:14px;
    }

    .badges{
      display:flex;
      gap:8px;
      align-items:center;
      margin-top:8px;
      flex-wrap:wrap;
    }
    .badge{
      background:var(--glass);
      padding:6px 10px;
      border-radius:999px;
      font-size:13px;
      color:var(--muted);
      border:1px solid rgba(255,255,255,0.03);
    }

    .rating{
      margin-left:auto;
      display:flex;
      gap:8px;
      align-items:center;
    }
    .score{
      background: linear-gradient(90deg,#ffb86b,#ff6b4a);
      color:#06121a;
      padding:8px 12px;
      border-radius:10px;
      font-weight:700;
      font-size:16px;
      box-shadow:0 6px 18px rgba(231,75,36,0.12);
    }

    main.card{
      margin-top:12px;
      background: linear-gradient(180deg, rgba(255,255,255,0.02), rgba(255,255,255,0.01));
      border-radius:var(--radius);
      padding:22px;
      box-shadow: 0 6px 30px rgba(3,8,12,0.6);
      border:1px solid rgba(255,255,255,0.03);
    }

    .grid{
      display:grid;
      grid-template-columns: 1fr 360px;
      gap:20px;
    }

    @media (max-width:980px){
      .grid{ grid-template-columns: 1fr; }
      .poster{ width:160px; aspect-ratio: 2/3; }
    }

    .lead{
      color:var(--muted);
      margin-bottom:14px;
    }

    .acronym{
      display:flex;
      flex-direction:column;
      gap:12px;
    }

    .entry{
      display:flex;
      gap:14px;
      align-items:flex-start;
      background: rgba(255,255,255,0.015);
      padding:12px;
      border-radius:10px;
    }

    .letter{
      width:56px;
      height:56px;
      border-radius:10px;
      flex-shrink:0;
      display:flex;
      align-items:center;
      justify-content:center;
      font-weight:800;
      font-size:20px;
      background: linear-gradient(180deg,#0b1720, #07202b);
      color: #ffcfb8;
      border:1px solid rgba(255,255,255,0.035);
      box-shadow: 0 4px 18px rgba(0,0,0,0.6);
    }

    .entry h3{
      margin:0 0 6px 0;
      font-size:16px;
    }
    .entry p{ margin:0;color:var(--muted); font-size:14px; }

    aside.side{
      position:relative;
      display:flex;
      flex-direction:column;
      gap:12px;
    }

    .card-block{
      background: linear-gradient(180deg, rgba(255,255,255,0.015), rgba(255,255,255,0.01));
      padding:14px;
      border-radius:10px;
      border:1px solid rgba(255,255,255,0.03);
    }

    .details dt{ color:var(--muted); font-size:13px; }
    .details dd{ margin:6px 0 12px 0; font-weight:600; }

    .cast-list{
      display:flex;
      gap:8px;
      flex-wrap:wrap;
    }
    .chip{
      padding:8px 10px;
      border-radius:999px;
      background:rgba(255,255,255,0.02);
      color:var(--muted);
      font-size:13px;
      border:1px solid rgba(255,255,255,0.02);
    }

    .score-bar{
      display:flex;
      align-items:center;
      gap:10px;
      margin-top:6px;
    }

    .stars{
      display:inline-flex;
      gap:4px;
      font-size:16px;
      color: #ffd166;
    }

    footer.credits{
      margin-top:18px;
      display:flex;
      justify-content:space-between;
      gap:12px;
      color:var(--muted);
      font-size:13px;
      align-items:center;
      flex-wrap:wrap;
    }

    /* Read more */
    .toggle-more{
      margin-top:10px;
      background:transparent;
      border:1px solid rgba(255,255,255,0.04);
      color:var(--muted);
      padding:8px 12px;
      border-radius:8px;
      cursor:pointer;
      font-weight:600;
    }

    /* Print */
    @media print{
      body{background:white;color:black}
      .poster{background:none}
      .title h1{color:black}
    }

  </style>
</head>
<body>
  <div class="container" role="main">
    <header class="page-header" aria-labelledby="pageTitle">
      <div class="poster" role="img" aria-label="Leo poster (placeholder)"></div>

      <div class="meta">
        <div class="title">
          <h1 id="pageTitle">LEO — Legendary Comeback of a Silent Hero</h1>
          <div class="sub">Director: Lokesh Kanagaraj • Release: October 19, 2023 • Genre: Action Thriller / Psychological Drama</div>
        </div>

        <div class="badges" aria-hidden="true">
          <div class="badge">Music: Anirudh Ravichander</div>
          <div class="badge">Cinematography: Manoj Paramahamsa</div>
          <div class="badge">Production: Seven Screen Studio</div>
          <div class="badge">Cast: Thalapathy Vijay, Trisha, Sanjay Dutt, Arjun</div>
        </div>

        <div style="display:flex;align-items:center;margin-top:10px;">
          <div style="font-size:14px;color:var(--muted);">Rating</div>
          <div class="rating" style="margin-left:12px;">
            <div class="stars" aria-hidden="true">★ ★ ★ ★ ☆</div>
            <div class="score" aria-label="4.7 out of 5">4.7 / 5</div>
          </div>
        </div>
      </div>
    </header>

    <main class="card" aria-labelledby="reviewHeading">
      <div class="grid">
        <section>
          <p class="lead">A masterful blend of emotion, violence, and vision — <strong>“Leo” roars with purpose and precision.</strong></p>

          <h2 id="reviewHeading" style="margin-top:0">L-E-O — R-E-V-I-E-W</h2>

          <div class="acronym">

            <article class="entry" aria-labelledby="lTitle">
              <div class="letter" id="lTitle">L</div>
              <div>
                <h3>Legendary Comeback of a Silent Hero</h3>
                <p>
                  Vijay transforms into Parthi — a quiet man in the Kashmir hills whose hidden past resurfaces. The film’s slow-burn first half builds suspense and allows the actor to convey emotional depth with controlled, subtle performances.
                </p>
              </div>
            </article>

            <article class="entry" aria-labelledby="eTitle">
              <div class="letter" id="eTitle">E</div>
              <div>
                <h3>Extraordinary Direction and Storytelling</h3>
                <p>
                  Lokesh Kanagaraj balances style with narrative purpose: silence, color, and slow reveals emphasize the film’s psychological core. The screenplay keeps tension tight while allowing ambiguity about Parthi’s true identity.
                </p>
              </div>
            </article>

            <article class="entry" aria-labelledby="oTitle">
              <div class="letter" id="oTitle">O</div>
              <div>
                <h3>Outstanding Performances Across the Board</h3>
                <p>
                  Trisha, Sanjay Dutt, Arjun Sarja and cameo appearances enrich the film’s emotional and dramatic landscape — making the movie a collective triumph rather than a single-star show.
                </p>
              </div>
            </article>

            <article class="entry" aria-labelledby="rTitle">
              <div class="letter" id="rTitle">R</div>
              <div>
                <h3>Riveting Action and Realism</h3>
                <p>
                  Practical effects, grounded choreography (notably the café fight), and realistic sound design keep the action visceral and consequential rather than exaggerated spectacle.
                </p>
              </div>
            </article>

            <article class="entry" aria-labelledby="e2Title">
              <div class="letter" id="e2Title">E</div>
              <div>
                <h3>Emotional Core that Connects</h3>
                <p>
                  At its heart, Leo is about redemption and family. The emotional stakes — guilt, reconciliation, and identity — provide weight to each act of violence and the film’s final choices.
                </p>
              </div>
            </article>

            <article class="entry" aria-labelledby="vTitle">
              <div class="letter" id="vTitle">V</div>
              <div>
                <h3>Visual Excellence and Technical Brilliance</h3>
                <p>
                  Manoj Paramahamsa’s cinematography, Philomin Raj’s editing and thoughtful production design make each frame purposeful — from wide, isolating landscapes to intimate close-ups.
                </p>
              </div>
            </article>

            <article class="entry" aria-labelledby="iTitle">
              <div class="letter" id="iTitle">I</div>
              <div>
                <h3>Intense Background Score and Music</h3>
                <p>
                  Anirudh’s score functions as a narrative engine — motifs, electronic tension and songs like <em>Naa Ready</em> and <em>Badass</em> heighten emotion and swagger.
                </p>
              </div>
            </article>

            <article class="entry" aria-labelledby="e3Title">
              <div class="letter" id="e3Title">E</div>
              <div>
                <h3>Exceptional Blend of Mass & Class</h3>
                <p>
                  The movie satisfies mass aesthetics while engaging cinephiles through psychological depth — a rare combination that broadens its appeal.
                </p>
              </div>
            </article>

            <article class="entry" aria-labelledby="wTitle">
              <div class="letter" id="wTitle">W</div>
              <div>
                <h3>Worthy Addition to the LCU Universe</h3>
                <p>
                  Subtle nods to the Lokesh Cinematic Universe expand the mythology without detracting from Parthi’s standalone journey — fans get more while newcomers remain unaffected.
                </p>
              </div>
            </article>

          </div>

          <div style="margin-top:14px;display:flex;gap:12px;flex-wrap:wrap;align-items:center;">
            <button class="toggle-more" id="toggleNotes" aria-expanded="false">Show critical verdict & technical notes</button>
            <div style="color:var(--muted);font-size:14px;">Best Song: <strong style="color:#fff">Naa Ready</strong></div>
          </div>

          <div id="moreBlock" style="display:none;margin-top:12px;color:var(--muted);font-size:14px;">
            <h3 style="margin-top:0">Critical Verdict</h3>
            <p>
              “Leo” is technically superior, emotionally rich and narratively gripping. Its greatest success is duality — an emotional drama and a mass entertainer — that elevates Tamil cinema’s global storytelling potential.
            </p>
            <p style="margin:0"><strong>Rating:</strong> ★★★★★ 4.7/5</p>
          </div>

        </section>

        <aside class="side" aria-labelledby="detailsHeading">
          <div class="card-block details" aria-hidden="false">
            <h4 id="detailsHeading" style="margin:0 0 10px 0">Quick Details</h4>
            <dl style="margin:0">
              <dt>Director</dt><dd>Lokesh Kanagaraj</dd>
              <dt>Cast</dt><dd><div class="cast-list"><span class="chip">Thalapathy Vijay</span><span class="chip">Trisha Krishnan</span><span class="chip">Sanjay Dutt</span><span class="chip">Arjun Sarja</span></div></dd>
              <dt>Music</dt><dd>Anirudh Ravichander</dd>
              <dt>Cinematography</dt><dd>Manoj Paramahamsa</dd>
              <dt>Production</dt><dd>Seven Screen Studio</dd>
              <dt>Release Date</dt><dd>October 19, 2023</dd>
            </dl>
          </div>

          <div class="card-block" aria-hidden="false">
            <h4 style="margin:0 0 10px 0">Why watch?</h4>
            <ul style="margin:0 0 0 18px;color:var(--muted);">
              <li>Vijay in a refreshing, restrained role.</li>
              <li>Lokesh’s tight, character-driven direction.</li>
              <li>High-quality cinematography & grounded action.</li>
            </ul>
          </div>

          <div class="card-block" aria-hidden="false">
            <h4 style="margin:0 0 8px 0">Share & Save</h4>
            <div style="display:flex;gap:8px;flex-wrap:wrap;">
              <a class="chip" href="#" onclick="navigator.clipboard?.writeText(location.href);return false">Copy link</a>
              <a class="chip" href="#" onclick="window.print();return false">Print</a>
              <a class="chip" href="#" onclick="alert('Pretend share — integrate social SDK');return false">Share</a>
            </div>
          </div>

        </aside>
      </div>

      <footer class="credits" role="contentinfo">
        <div>Review by — <strong>Anonymous Critic</strong></div>
        <div style="color:var(--muted)">Technical & editorial notes included</div>
      </footer>
    </main>
  </div>

  <script>
    // Small interactivity: toggle the 'more' block
    (function(){
      const btn = document.getElementById('toggleNotes');
      const more = document.getElementById('moreBlock');
      btn.addEventListener('click', ()=>{
        const expanded = btn.getAttribute('aria-expanded') === 'true';
        btn.setAttribute('aria-expanded', String(!expanded));
        if(!expanded){
          more.style.display = 'block';
          btn.textContent = 'Hide critical verdict & technical notes';
        } else {
          more.style.display = 'none';
          btn.textContent = 'Show critical verdict & technical notes';
        }
      });
    })();
  </script>
</body>
</html>
