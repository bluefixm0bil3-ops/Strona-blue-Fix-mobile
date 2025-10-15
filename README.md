
<!doctype html>
<html lang="pl">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>BlueFix Mobile — Serwis telefonów | Rzeszów</title>
  <meta name="description" content="BlueFix Mobile — szybka i profesjonalna naprawa telefonów w Rzeszowie. Wymiana szybki, baterii, czyszczenie, diagnoza i inne." />
  <style>
    :root{--blue:#0b74ff;--dark:#070707;--muted:#6b6b6b;--card:#0f0f10}
    *{box-sizing:border-box;font-family:Inter, system-ui, -apple-system, 'Segoe UI', Roboto, 'Helvetica Neue', Arial}
    body{margin:0;background:linear-gradient(180deg,#000 0%, #070707 100%);color:#e9eef8}
    a{color:var(--blue);text-decoration:none}
    header{background:linear-gradient(90deg, rgba(11,116,255,0.06), rgba(11,116,255,0.02));backdrop-filter:blur(2px);position:sticky;top:0;z-index:50;border-bottom:1px solid rgba(255,255,255,0.03)}
    .container{max-width:980px;margin:0 auto;padding:24px}
    .nav{display:flex;align-items:center;justify-content:space-between}
    .brand{display:flex;align-items:center;gap:12px}
    .logo{display:inline-grid;place-items:center;width:52px;height:52px;background:linear-gradient(180deg,var(--blue),#0070e0);border-radius:10px}
    .logo svg{width:34px;height:34px;filter:drop-shadow(0 2px 6px rgba(11,116,255,0.15))}
    .brand h1{font-size:18px;margin:0;letter-spacing:0.5px}
    nav ul{display:flex;gap:14px;list-style:none;margin:0;padding:0}
    nav a{padding:10px 8px;border-radius:8px;color:#dfeefd;font-weight:600}
    nav a:hover{background:rgba(255,255,255,0.02)}
    .hero{padding:48px 0;display:grid;grid-template-columns:1fr 380px;gap:24px;align-items:center}
    .card{background:linear-gradient(180deg,rgba(255,255,255,0.02),rgba(255,255,255,0.01));padding:18px;border-radius:12px;border:1px solid rgba(255,255,255,0.03)}
    .hero h2{font-size:32px;margin:0 0 8px}
    .hero p{margin:0 0 18px;color:var(--muted)}
    .cta{display:flex;gap:10px}
    .btn{background:var(--blue);color:#fff;padding:10px 14px;border-radius:10px;font-weight:700;border:none;cursor:pointer}
    .btn.secondary{background:transparent;border:1px solid rgba(255,255,255,0.06)}
    .services{display:grid;grid-template-columns:repeat(3,1fr);gap:12px;margin-top:18px}
    .service{padding:12px;border-radius:10px;background:rgba(255,255,255,0.01);text-align:center}
    .service h4{margin:8px 0 4px}
    .grid{display:grid;grid-template-columns:1fr 1fr;gap:18px;margin-top:18px}
    .pricing table{width:100%;border-collapse:collapse}
    table td,table th{padding:10px;border-bottom:1px solid rgba(255,255,255,0.03);text-align:left}
    .gallery{display:grid;grid-template-columns:repeat(3,1fr);gap:8px}
    .gallery img{width:100%;height:140px;object-fit:cover;border-radius:8px}
    footer{padding:20px 0;margin-top:30px;border-top:1px solid rgba(255,255,255,0.03);color:var(--muted)}
    .contact-grid{display:flex;flex-direction:column;gap:8px}
    .icon{width:18px;display:inline-block;vertical-align:middle;margin-right:8px}
    /* responsive */
    @media (max-width:900px){.hero{grid-template-columns:1fr;background:transparent}.services{grid-template-columns:repeat(2,1fr)}.grid{grid-template-columns:1fr}.gallery{grid-template-columns:repeat(2,1fr)}}
    @media (max-width:520px){nav ul{display:none}.nav{padding:8px 0}.brand h1{font-size:16px}.hero{padding:28px 0;grid-template-columns:1fr}.logo{width:44px;height:44px}}
  </style>
</head>
<body>
  <header>
    <div class="container nav">
      <div class="brand">
        <div class="logo" aria-hidden>
          <!-- inline SVG logo: phone + lightning -->
          <svg viewBox="0 0 64 64" fill="none" xmlns="http://www.w3.org/2000/svg">
            <rect x="10" y="7" width="44" height="50" rx="6" fill="#012"/>
            <rect x="12" y="9" width="40" height="46" rx="4" fill="url(#g)"/>
            <path d="M34 18 L28 34 L36 34 L30 46" stroke="white" stroke-width="3" stroke-linecap="round" stroke-linejoin="round"/>
            <defs><linearGradient id="g" x1="0" x2="1"><stop offset="0" stop-color="#0b74ff" stop-opacity="1"/><stop offset="1" stop-color="#0066d6" stop-opacity="0.9"/></linearGradient></defs>
          </svg>
        </div>
        <div>
          <h1>BlueFix Mobile<br/><small style="color:var(--muted);font-weight:600">Serwis telefonów • Rzeszów</small></h1>
        </div>
      </div>
      <nav>
        <ul>
          <li><a href="#home">Strona główna</a></li>
          <li><a href="#services">Usługi</a></li>
          <li><a href="#pricing">Cennik</a></li>
          <li><a href="#gallery">Galeria</a></li>
          <li><a href="#contact">Kontakt</a></li>
        </ul>
      </nav>
    </div>
  </header>

  <main class="container">
    <section id="home" class="hero">
      <div>
        <div class="card">
          <h2>BlueFix Mobile — szybka naprawa telefonów w Rzeszowie</h2>
          <p>Wymiana szybki, baterii, czyszczenie, diagnoza i naprawa głośników. Szybko, profesjonalnie i z gwarancją.</p>
          <div class="cta">
            <a class="btn" href="tel:+48690881387">Zadzwoń: 690 881 387</a>
            <a class="btn secondary" href="#contact">Umów wizytę</a>
          </div>

          <div class="services" style="margin-top:14px">
            <div class="service"><strong>Wymiana szybki</strong><div style="color:var(--muted);font-size:13px">Ekspresowo</div></div>
            <div class="service"><strong>Wymiana baterii</strong><div style="color:var(--muted);font-size:13px">Test po wymianie</div></div>
            <div class="service"><strong>Czyszczenie & diagnoza</strong><div style="color:var(--muted);font-size:13px">Porty, głośniki</div></div>
          </div>
        </div>
      </div>

      <aside>
        <div class="card">
          <h3 style="margin:0 0 8px">Znajdź nas</h3>
          <p style="margin:0 0 12px;color:var(--muted)">Rzeszów — Bohaterów Westerplatte 5</p>
          <div style="display:flex;gap:8px;margin-bottom:10px">
            <a class="btn" href="https://maps.app.goo.gl/5nb4r6T8Rky7Tyvr6" target="_blank" rel="noopener">Znajdź w Google</a>
            <a class="btn secondary" href="https://www.instagram.com/blue.fix.mobile?igsh=MWsxNm0yODE4Zmo5dQ==" target="_blank" rel="noopener">Napisz na Instagramie</a>
          </div>

          <div class="contact-grid">
            <div><strong>Tel:</strong> <a href="tel:+48690881387">690 881 387</a></div>
            <div><strong>Email:</strong> <a href="mailto:Blue.Fix.M0bil3@gmail.com">Blue.Fix.M0bil3@gmail.com</a></div>
          </div>
        </div>
      </aside>
    </section>

    <section id="services" style="margin-top:20px">
      <h3>Usługi</h3>
      <div class="grid">
        <div class="card">
          <h4>Co naprawiamy</h4>
          <p style="color:var(--muted)">Wymiana szybki i plecków, wymiana baterii, czyszczenie, diagnoza głośników, naprawy po zalaniu i więcej.</p>
          <ul style="color:var(--muted);margin:10px 0 0;padding-left:18px">
            <li>Wymiana szybki</li>
            <li>Wymiana baterii</li>
            <li>Czyszczenie portów i głośników</li>
            <li>Diagnoza i serwis oprogramowania</li>
            <li>Naprawy po zalaniu</li>
          </ul>
        </div>
        <div class="card pricing">
          <h4>Dlaczego my?</h4>
          <p style="color:var(--muted)">Lokalny serwis w Rzeszowie. Szybka diagnoza, części jakościowe i gwarancja na naprawę.</p>
          <ul style="color:var(--muted);margin:10px 0 0;padding-left:18px">
            <li>Darmowa wycena</li>
            <li>Gwarancja na części</li>
            <li>Szybkie terminy</li>
          </ul>
        </div>
      </div>
    </section>

    <section id="pricing" style="margin-top:18px">
      <h3>Cennik (orientacyjny)</h3>
      <div class="card">
        <table>
          <thead>
            <tr><th>Usługa</th><th>Cena od</th></tr>
          </thead>
          <tbody>
            <tr><td>Wymiana szybki</td><td>150 zł</td></tr>
            <tr><td>Wymiana baterii</td><td>120 zł</td></tr>
            <tr><td>Czyszczenie i diagnostyka</td><td>50 zł</td></tr>
            <tr><td>Naprawa głośnika</td><td>od 80 zł</td></tr>
            <tr><td>Naprawy po zalaniu</td><td>od 120 zł</td></tr>
          </tbody>
        </table>
        <p style="color:var(--muted);font-size:13px;margin-top:10px">*Ceny orientacyjne. Dokładna wycena po diagnozie.</p>
      </div>
    </section>

    <section id="gallery" style="margin-top:18px">
      <h3>Galeria</h3>
      <div class="gallery">
        <!-- stock images -->
        <img src="https://images.unsplash.com/photo-1512496015851-a90fb38ba796?q=80&w=800&auto=format&fit=crop&ixlib=rb-4.0.3&s=1e2f3b3c" alt="naprawa telefonu"/>
        <img src="https://images.unsplash.com/photo-1517433456452-f9633a875f6f?q=80&w=800&auto=format&fit=crop&ixlib=rb-4.0.3&s=8f5b3b9f" alt="technician repairing phone"/>
        <img src="https://images.unsplash.com/photo-1580910051074-6b4b8b4f6d1a?q=80&w=800&auto=format&fit=crop&ixlib=rb-4.0.3&s=4b7f9b2a" alt="phone tools"/>
        <img src="https://images.unsplash.com/photo-1555617117-08fda2d5f2f3?q=80&w=800&auto=format&fit=crop&ixlib=rb-4.0.3&s=9f0e6d5b" alt="clean phone"/>
        <img src="https://images.unsplash.com/photo-1585386959984-a415522f3f9e?q=80&w=800&auto=format&fit=crop&ixlib=rb-4.0.3&s=ab6c6a2f" alt="screen replacement"/>
        <img src="https://images.unsplash.com/photo-1581579181401-4f1c6b0f3d4e?q=80&w=800&auto=format&fit=crop&ixlib=rb-4.0.3&s=2b6a7e5d" alt="battery replacement"/>
      </div>
    </section>

    <section id="contact" style="margin-top:20px">
      <h3>Kontakt</h3>
      <div class="grid">
        <div class="card">
          <h4>Umów naprawę</h4>
          <form onsubmit="event.preventDefault(); alert('Dziękujemy — otrzymaliśmy wiadomość. Skontaktujemy się wkrótce.');" style="display:grid;gap:8px">
            <input required placeholder="Imię" style="padding:10px;border-radius:8px;border:1px solid rgba(255,255,255,0.03);background:transparent;color:inherit"/>
            <input required placeholder="Telefon" style="padding:10px;border-radius:8px;border:1px solid rgba(255,255,255,0.03);background:transparent;color:inherit"/>
            <input placeholder="Email (opcjonalnie)" style="padding:10px;border-radius:8px;border:1px solid rgba(255,255,255,0.03);background:transparent;color:inherit"/>
            <textarea placeholder="Krótki opis problemu" rows="4" style="padding:10px;border-radius:8px;border:1px solid rgba(255,255,255,0.03);background:transparent;color:inherit"></textarea>
            <div style="display:flex;gap:8px">
              <button class="btn" type="submit">Wyślij</button>
              <a class="btn secondary" href="tel:+48690881387">Zadzwoń</a>
            </div>
          </form>
        </div>

        <div class="card">
          <h4>Dane</h4>
          <p style="color:var(--muted);margin:0 0 8px">Rzeszów, Bohaterów Westerplatte 5</p>
          <p style="margin:0 0 8px"><strong>Tel:</strong> <a href="tel:+48690881387">690 881 387</a></p>
          <p style="margin:0 0 8px"><strong>Email:</strong> <a href="mailto:Blue.Fix.M0bil3@gmail.com">Blue.Fix.M0bil3@gmail.com</a></p>
          <p style="margin:0 0 12px;color:var(--muted)">Godziny otwarcia: Pon–Pt 10:00–18:00 (proszę dzwonić po wcześniejsze umówienie)</p>
          <div style="display:flex;gap:8px">
            <a class="btn" href="https://maps.app.goo.gl/5nb4r6T8Rky7Tyvr6" target="_blank" rel="noopener">Mapa</a>
            <a class="btn" href="https://www.instagram.com/blue.fix.mobile?igsh=MWsxNm0yODE4Zmo5dQ==" target="_blank" rel="noopener">Instagram</a>
          </div>
        </div>
      </div>
    </section>

    <footer>
      <div style="display:flex;justify-content:space-between;align-items:center;flex-wrap:wrap;gap:12px">
        <div>© <strong>BlueFix Mobile</strong> • Rzeszów</div>
        <div style="color:var(--muted);font-size:13px">Projekt strony: gotowy plik HTML — możesz wdrożyć na Netlify / GitHub Pages</div>
      </div>
    </footer>
  </main>

  <script>
    // smooth scroll for anchor links
    document.querySelectorAll('a[href^="#"]').forEach(a=>{
      a.addEventListener('click',e=>{
        e.preventDefault();const t=document.querySelector(a.getAttribute('href'));
        if(t) t.scrollIntoView({behavior:'smooth',block:'start'});
      });
    });
  </script>
</body>
</html>
