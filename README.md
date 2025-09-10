<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>[Your Name] — Portfolio</title>
  <meta name="description" content="Portfolio of [Your Name] — projects, skills and contact." />
  <style>
    :root{--bg:#0f1724;--card:#0b1220;--muted:#9AA4B2;--accent:#6EE7B7;font-family:Inter,-apple-system,BlinkMacSystemFont,'Segoe UI',Roboto,'Helvetica Neue',Arial}
    *{box-sizing:border-box}
    html,body{height:100%}
    body{margin:0;background:linear-gradient(180deg,#071023 0%,var(--bg) 100%);color:#E6EEF3;-webkit-font-smoothing:antialiased}
    .container{max-width:980px;margin:36px auto;padding:28px}
    header{display:flex;align-items:center;gap:18px}
    .avatar{width:86px;height:86px;border-radius:14px;background:linear-gradient(135deg,var(--accent),#60a5fa);display:flex;align-items:center;justify-content:center;font-weight:700;color:#042029;font-size:28px}
    h1{margin:0;font-size:28px}
    p.lead{margin:6px 0 0;color:var(--muted)}
    nav{margin-top:22px;display:flex;gap:10px;flex-wrap:wrap}
    .btn{background:transparent;border:1px solid rgba(255,255,255,.06);padding:8px 12px;border-radius:10px;color:var(--muted);font-size:14px;text-decoration:none}
    main{margin-top:28px;display:grid;grid-template-columns:1fr 320px;gap:24px}
    .card{background:linear-gradient(180deg,rgba(255,255,255,0.02),rgba(255,255,255,0.01));padding:18px;border-radius:12px;border:1px solid rgba(255,255,255,0.03)}
    .about{line-height:1.6;color:#D9E8F0}
    .skills{display:flex;gap:8px;flex-wrap:wrap;margin-top:10px}
    .skill{background:rgba(255,255,255,0.03);padding:8px 10px;border-radius:8px;font-size:13px;color:var(--muted)}
    .projects{display:grid;gap:12px}
    .project{display:flex;flex-direction:column;gap:8px;padding:12px;border-radius:10px;background:rgba(0,0,0,0.18)}
    .project h3{margin:0;font-size:16px}
    .project p{margin:0;color:var(--muted);font-size:14px}
    .project-links{display:flex;gap:8px;margin-top:8px}
    .chip{padding:6px 8px;border-radius:8px;background:rgba(255,255,255,0.02);font-size:13px;color:var(--muted)}
    aside .stat{display:flex;justify-content:space-between;padding:10px;border-radius:10px;margin-bottom:10px;background:linear-gradient(90deg,rgba(255,255,255,0.01),transparent)}
    footer{margin-top:28px;text-align:center;color:var(--muted);font-size:13px}

    /* responsive */
    @media (max-width:880px){main{grid-template-columns:1fr;}}
  </style>
</head>
<body>
  <div class="container">
    <header>
      <div class="avatar">YN</div>
      <div>
        <h1>[Your Name] <span style="font-weight:400;color:var(--muted);font-size:16px">— Software developer &amp; problem solver</span></h1>
        <p class="lead">I build reliable web apps, clean APIs and cool side-projects. Open to freelance &amp; collaboration.</p>
        <nav>
          <a class="btn" href="#projects">Projects</a>
          <a class="btn" href="#about">About</a>
          <a class="btn" href="#contact">Contact</a>
          <a class="btn" href="https://github.com/your-username" target="_blank">GitHub</a>
        </nav>
      </div>
    </header>

    <main>
      <section>
        <div id="about" class="card">
          <h2 style="margin-top:0">About</h2>
          <p class="about">Hi — I'm <strong>[Your Name]</strong>, a <strong>full-stack developer</strong> from [Your City]. I enjoy taking ideas from concept to production: building responsive front-ends, solid back-end services, and automations that save time. I like clean code, tests, and shipping small iterations quickly.</p>
          <div class="skills">
            <div class="skill">JavaScript (ES6+)</div>
            <div class="skill">React</div>
            <div class="skill">Node.js</div>
            <div class="skill">Python</div>
            <div class="skill">Postgres</div>
            <div class="skill">Docker</div>
          </div>
        </div>

        <div id="projects" class="card" style="margin-top:18px">
          <h2 style="margin-top:0">Selected projects</h2>
          <div class="projects">
            <article class="project">
              <h3>Project One — <span style="font-weight:400;color:var(--muted)">SaaS dashboard</span></h3>
              <p>Responsive admin dashboard with realtime charts, auth and role-based permissions. Built with React, Recharts and Node + Postgres.</p>
              <div class="project-links">
                <a class="chip" href="https://github.com/your-username/project-one" target="_blank">GitHub</a>
                <a class="chip" href="#" target="_blank">Live</a>
                <div style="flex:1"></div>
                <span class="chip">React</span>
                <span class="chip">Node</span>
              </div>
            </article>

            <article class="project">
              <h3>Project Two — <span style="font-weight:400;color:var(--muted)">CLI tool</span></h3>
              <p>Small CLI utility to automate dev tasks and scaffold projects. Tests, docs and lightweight packaging included.</p>
              <div class="project-links">
                <a class="chip" href="https://github.com/your-username/project-two" target="_blank">GitHub</a>
                <span class="chip">Python</span>
                <span class="chip">CLI</span>
              </div>
            </article>

            <article class="project">
              <h3>Project Three — <span style="font-weight:400;color:var(--muted)">Game / creative</span></h3>
              <p>Interactive web game made for fun — uses canvas, animations and procedural levels. Lightweight and mobile-friendly.</p>
              <div class="project-links">
                <a class="chip" href="https://github.com/your-username/project-three" target="_blank">GitHub</a>
                <a class="chip" href="#" target="_blank">Play</a>
                <span class="chip">HTML5</span>
              </div>
            </article>
          </div>
        </div>

        <div class="card" style="margin-top:18px">
          <h2 style="margin-top:0">How I work</h2>
          <ul style="margin:8px 0 0 20px;color:var(--muted)">
            <li>Small, testable increments — ship early, iterate fast.</li>
            <li>Readable code &amp; clear documentation.</li>
            <li>Automate repetitive tasks with scripts and CI pipelines.</li>
          </ul>
        </div>
      </section>

      <aside>
        <div class="card">
          <div class="stat"><strong>Location</strong><span>[Your City, Country]</span></div>
          <div class="stat"><strong>Availability</strong><span>Open to work / collaborate</span></div>
          <div class="stat"><strong>Contact</strong><span><a style="color:var(--accent);text-decoration:none" href="mailto:you@example.com">you@example.com</a></span></div>
          <div class="stat"><strong>Github</strong><span><a style="color:var(--accent);text-decoration:none" href="https://github.com/your-username" target="_blank">@your-username</a></span></div>
        </div>

        <div class="card" style="margin-top:12px">
          <h3 style="margin-top:0">Quick stats</h3>
          <p style="color:var(--muted);margin:6px 0 0">Add your GitHub stats here (stars, repos, contributions). You can use GitHub profile cards or shields in your README for live badges.</p>
        </div>

        <div class="card" style="margin-top:12px">
          <h3 style="margin-top:0">Skills (level)</h3>
          <div style="display:grid;grid-template-columns:1fr 1fr;gap:8px;margin-top:8px">
            <div class="chip">JavaScript — Advanced</div>
            <div class="chip">React — Advanced</div>
            <div class="chip">Node — Intermediate</div>
            <div class="chip">Python — Intermediate</div>
            <div class="chip">Docker — Intermediate</div>
            <div class="chip">SQL — Intermediate</div>
          </div>
        </div>

        <div class="card" style="margin-top:12px">
          <h3 style="margin-top:0">Contact</h3>
          <p style="color:var(--muted);margin:6px 0">Prefer email? <a style="color:var(--accent)" href="mailto:you@example.com">you@example.com</a></p>
          <p style="color:var(--muted);margin:6px 0">Or connect on <a style="color:var(--accent)" href="https://www.linkedin.com/in/your-profile" target="_blank">LinkedIn</a></p>
        </div>
      </aside>
    </main>

    <footer>
      <div>Made with ❤️ — <a style="color:var(--accent);text-decoration:none" href="https://github.com/your-username" target="_blank">@your-username</a></div>
    </footer>
  </div>

  <script>
    // Small nicety: replace initials and name placeholders when provided via URL params
    (function(){
      function getParam(n){const p=new URLSearchParams(location.search);return p.get(n)}
      const name=getParam('name'); const initials=getParam('init'); const gh=getParam('gh');
      if(name) document.querySelector('h1').innerHTML = name + ' <span style="font-weight:400;color:var(--muted);font-size:16px">— Software developer &amp; problem solver</span>';
      if(initials) document.querySelector('.avatar').textContent = initials;
      if(gh) document.querySelectorAll('a[href*="github.com/your-username"]').forEach(a=>a.href=a.href.replace('your-username',gh));
    })();
  </script>
</body>
</html>
