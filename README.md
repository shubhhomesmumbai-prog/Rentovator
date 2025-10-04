# Rentovator
My project
<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Rentovator — Monthly Excavator Rentals</title>
  <meta name="description" content="Rentovator offers reliable excavator rentals on a monthly basis. Wide range of machines, flexible terms, doorstep delivery and maintenance included." />
  <meta name="theme-color" content="#0b5f4d" />

  <!-- Open Graph -->
  <meta property="og:title" content="Rentovator — Monthly Excavator Rentals" />
  <meta property="og:description" content="Monthly excavator rentals with expert support, delivery & maintenance. Flexible terms for construction and earthmoving projects." />
  <meta property="og:image" content="https://example.com/hero-image.jpg" />
  <meta property="og:type" content="website" />
  <meta property="og:url" content="https://rentovator.example.com/" />

  <!-- Twitter -->
  <meta name="twitter:card" content="summary_large_image" />
  <meta name="twitter:title" content="Rentovator — Monthly Excavator Rentals" />
  <meta name="twitter:description" content="Monthly excavator rentals with delivery & maintenance." />
  <meta name="twitter:image" content="https://example.com/hero-image.jpg" />

  <!-- JSON-LD (Organization + Service) -->
  <script type="application/ld+json">
  {
    "@context": "https://schema.org",
    "@type": "Organization",
    "name": "Rentovator",
    "url": "https://rentovator.example.com/",
    "logo": "https://example.com/logo.png",
    "contactPoint": {
      "@type": "ContactPoint",
      "telephone": "+91-XXXXXXXXXX",
      "contactType": "customer service",
      "areaServed": "IN"
    }
  }
  </script>

  <style>
    /* Simple modern responsive CSS */
    :root{
      --accent:#0b5f4d;
      --muted:#666;
      --bg:#ffffff;
      --card:#fbfbfb;
      --radius:12px;
      --maxwidth:1100px;
      font-family: Inter, system-ui, -apple-system, "Segoe UI", Roboto, "Helvetica Neue", Arial;
    }
    *{box-sizing:border-box}
    body{margin:0;background:linear-gradient(180deg,#f7f9f8 0,#ffffff 100%);color:#111;line-height:1.5}
    .wrap{max-width:var(--maxwidth);margin:32px auto;padding:24px}
    header{display:flex;align-items:center;justify-content:space-between;gap:16px}
    .brand{display:flex;align-items:center;gap:12px}
    .logo{width:56px;height:56px;border-radius:10px;background:var(--accent);display:flex;align-items:center;justify-content:center;color:#fff;font-weight:700;font-size:18px;box-shadow:0 6px 18px rgba(11,95,77,.14)}
    nav a{margin-left:18px;color:var(--muted);text-decoration:none;font-weight:600}
    .hero{display:grid;grid-template-columns:1fr 420px;gap:28px;margin-top:28px;align-items:center}
    .hero h1{margin:0;font-size:28px}
    .hero p{color:var(--muted);margin:12px 0 20px}
    .cta{display:flex;gap:12px;flex-wrap:wrap}
    .btn{background:var(--accent);color:#fff;padding:12px 18px;border-radius:10px;text-decoration:none;font-weight:700;display:inline-block}
    .btn.ghost{background:transparent;border:2px solid rgba(11,95,77,.12);color:var(--accent)}
    .card{background:var(--card);padding:20px;border-radius:12px;box-shadow:0 8px 24px rgba(12,20,18,0.04)}
    .features{display:flex;gap:12px;flex-wrap:wrap;margin-top:18px}
    .feature{flex:1;min-width:160px;background:#fff;padding:14px;border-radius:10px;border:1px solid #f0f0f0}
    .pricing{display:grid;grid-template-columns:repeat(auto-fit,minmax(220px,1fr));gap:16px;margin-top:22px}
    .price-card{background:#fff;padding:18px;border-radius:12px;border:1px solid #eee}
    .price{font-size:22px;font-weight:800;color:var(--accent)}
    form{display:grid;gap:8px}
    input,select,textarea{width:100%;padding:10px;border-radius:8px;border:1px solid #e6e6e6}
    footer{margin-top:40px;color:var(--muted);font-size:14px;display:flex;justify-content:space-between;flex-wrap:wrap;gap:12px}
    .grid-2{display:grid;grid-template-columns:1fr 1fr;gap:12px}
    .faq details{margin-bottom:8px;background:#fff;padding:12px;border-radius:8px;border:1px solid #f0f0f0}
    /* responsive */
    @media (max-width:900px){
      .hero{grid-template-columns:1fr}
      nav{display:none}
      .wrap{padding:16px}
    }
  </style>
</head>
<body>
  <div class="wrap">
    <header>
      <div class="brand">
        <div class="logo">R</div>
        <div>
          <div style="font-weight:800">Rentovator</div>
          <div style="font-size:13px;color:var(--muted)">Monthly Excavator Rentals</div>
        </div>
      </div>

      <nav aria-label="Main navigation">
        <a href="#about">About</a>
        <a href="#pricing">Pricing</a>
        <a href="#book">Book</a>
        <a href="#contact">Contact</a>
      </nav>
    </header>

    <section class="hero" id="home">
      <div>
        <h1>Monthly excavator rentals — flexible, reliable, delivered.</h1>
        <p>Rentovator supplies tracked and wheeled excavators for construction, infrastructure and earthworks. Monthly plans, onsite delivery, preventive maintenance and optional operator hire.</p>

        <div class="cta">
          <a class="btn" href="#book">Book a Machine</a>
          <a class="btn ghost" href="#pricing">See Monthly Rates</a>
        </div>

        <div class="features" aria-hidden>
          <div class="feature">
            <strong>Delivery & Setup</strong>
            <div style="color:var(--muted);font-size:13px;margin-top:8px">We deliver to site and assist setup.</div>
          </div>
          <div class="feature">
            <strong>Maintenance Included</strong>
            <div style="color:var(--muted);font-size:13px;margin-top:8px">Monthly checks and breakdown support.</div>
          </div>
          <div class="feature">
            <strong>Operator Option</strong>
            <div style="color:var(--muted);font-size:13px;margin-top:8px">Add skilled operator to the plan.</div>
          </div>
        </div>
      </div>

      <aside class="card" aria-labelledby="availability">
        <h3 id="availability">Check availability</h3>
        <p style="color:var(--muted);margin-top:6px">Tell us where & when and we’ll confirm machine availability within 24 hours.</p>

        <form id="quick-check" onsubmit="event.preventDefault(); quickCheck()">
          <label>
            City / Project location
            <input id="q-location" type="text" required placeholder="e.g., Pune, Maharashtra">
          </label>
          <label>
            Preferred start date
            <input id="q-start" type="date" required>
          </label>
          <label>
            Type
            <select id="q-type" required>
              <option value="mini">Mini Excavator (1-3 t)</option>
              <option value="medium">Medium Excavator (5-15 t)</option>
              <option value="heavy">Heavy Excavator (20+ t)</option>
            </select>
          </label>
          <button class="btn" type="submit">Check</button>
          <div id="quick-msg" style="margin-top:10px;color:var(--muted);font-size:13px"></div>
        </form>
      </aside>
    </section>

    <section id="about" style="margin-top:28px">
      <div class="card">
        <h2>About Rentovator</h2>
        <p style="color:var(--muted)">Rentovator was built to simplify heavy equipment rentals for monthly projects. We focus on reliable machines, transparent pricing and fast support so your project stays on schedule.</p>

        <div style="margin-top:12px;display:flex;gap:10px;flex-wrap:wrap">
          <div style="min-width:200px">
            <strong>Who we serve</strong>
            <div style="color:var(--muted);font-size:13px">Contractors, builders, infrastructure firms & temp projects.</div>
          </div>
          <div style="min-width:200px">
            <strong>Service area</strong>
            <div style="color:var(--muted);font-size:13px">Nationwide (delivery charges may apply).</div>
          </div>
        </div>
      </div>
    </section>

    <section id="pricing" style="margin-top:24px">
      <h2>Monthly pricing (examples)</h2>
      <p style="color:var(--muted);margin-top:6px">All prices are indicative. Final quote depends on location, duration, and add-ons (operator, fuel, attachments).</p>

      <div class="pricing" style="margin-top:12px">
        <div class="price-card">
          <div style="font-weight:700">Mini Excavator</div>
          <div class="price">₹35,000 / month</div>
          <div style="color:var(--muted);font-size:13px;margin-top:8px">Suitable for small civil works & landscaping. 1–3 ton class.</div>
          <ul style="margin-top:8px;color:var(--muted);padding-left:18px">
            <li>Delivery included (local)</li>
            <li>Maintenance & spare parts</li>
            <li>Optional operator: ₹18,000 / month</li>
          </ul>
          <a class="btn" href="#book" style="margin-top:10px;display:inline-block">Book Mini</a>
        </div>

        <div class="price-card">
          <div style="font-weight:700">Medium Excavator</div>
          <div class="price">₹75,000 / month</div>
          <div style="color:var(--muted);font-size:13px;margin-top:8px">For most construction and earthmoving needs (5–15 ton).</div>
          <ul style="margin-top:8px;color:var(--muted);padding-left:18px">
            <li>Routine service included</li>
            <li>Operator available on request</li>
            <li>Longer-term discounts available</li>
          </ul>
          <a class="btn" href="#book" style="margin-top:10px;display:inline-block">Book Medium</a>
        </div>

        <div class="price-card">
          <div style="font-weight:700">Heavy Excavator</div>
          <div class="price">₹1,80,000 / month</div>
          <div style="color:var(--muted);font-size:13px;margin-top:8px">For major projects & heavy digging (20+ ton).</div>
          <ul style="margin-top:8px;color:var(--muted);padding-left:18px">
            <li>Dedicated support & spare supply</li>
            <li>Operator & fuel packages available</li>
          </ul>
          <a class="btn" href="#book" style="margin-top:10px;display:inline-block">Book Heavy</a>
        </div>
      </div>
    </section>

    <section id="book" style="margin-top:28px">
      <div class="card">
        <h2>Book a monthly rental</h2>
        <p style="color:var(--muted);margin-top:6px">Fill details and our sales team will contact you with a firm quote.</p>

        <form id="booking-form" onsubmit="event.preventDefault(); submitBooking()">
          <div class="grid-2">
            <label>
              Name
              <input id="name" type="text" required placeholder="Your full name">
            </label>
            <label>
              Company (optional)
              <input id="company" type="text" placeholder="Company / Contractor">
            </label>
          </div>

          <div class="grid-2" style="margin-top:6px">
            <label>
              Phone
              <input id="phone" type="tel" required placeholder="+91-XXXXXXXXXX">
            </label>
            <label>
              Email
              <input id="email" type="email" required placeholder="you@example.com">
            </label>
          </div>

          <div style="margin-top:6px" class="grid-2">
            <label>
              Project location (city)
              <input id="location" type="text" required placeholder="e.g., Mumbai">
            </label>
            <label>
              Start date
              <input id="start" type="date" required>
            </label>
          </div>

          <label style="margin-top:6px">
            Machine type
            <select id="machine" required>
              <option value="mini">Mini (1-3 t)</option>
              <option value="medium">Medium (5-15 t)</option>
              <option value="heavy">Heavy (20+ t)</option>
            </select>
          </label>

          <label>
            Additional notes
            <textarea id="notes" rows="3" placeholder="Any site access notes, attachments needed, operator required..."></textarea>
          </label>

          <div style="display:flex;gap:10px;margin-top:10px">
            <button class="btn" type="submit">Request Quote</button>
            <button type="button" class="btn ghost" onclick="callSales()">Call Sales</button>
          </div>

          <div id="booking-msg" style="margin-top:10px;color:var(--muted)"></div>
        </form>
      </div>
    </section>

    <section style="margin-top:24px">
      <div class="card">
        <h3>FAQ</h3>
        <div class="faq" style="margin-top:12px">
          <details><summary>What does monthly rental include?</summary>
            <div style="color:var(--muted);margin-top:8px">Base rental, scheduled maintenance, and local delivery are included unless stated otherwise. Fuel and operator charges are extra if chosen.</div>
          </details>
          <details><summary>Is a security deposit required?</summary>
            <div style="color:var(--muted);margin-top:8px">Yes — typically one month's rental as deposit (refundable subject to inspection).</div>
          </details>
          <details><summary>Do you provide operators?</summary>
            <div style="color:var(--muted);margin-top:8px">Yes — certified operators are available for an additional monthly fee.</div>
          </details>
        </div>
      </div>
    </section>

    <section id="contact" style="margin-top:24px">
      <div style="display:flex;gap:12px;flex-wrap:wrap">
        <div style="flex:1;min-width:280px">
          <div class="card">
            <h3>Contact</h3>
            <p style="color:var(--muted)">Sales: <strong>+91 XXXXXXXXXX</strong><br>Email: <strong>sales@rentovator.example.com</strong></p>
            <p style="color:var(--muted);font-size:13px">Office hours: Mon–Sat, 9:00–18:00</p>
            <p style="margin-top:8px"><a class="btn" href="tel:+91XXXXXXXXXX">Call Now</a></p>
          </div>
        </div>

        <div style="flex:1;min-width:280px">
          <div class="card">
            <h3>Terms for monthly rentals (summary)</h3>
            <ul style="color:var(--muted);padding-left:18px">
              <li>Minimum rental duration: 1 month.</li>
              <li>Deposit refundable after machine inspection.</li>
              <li>Damage beyond normal wear & tear charged separately.</li>
              <li>Cancellation: notify 7 days before start for full refund of deposit.</li>
            </ul>
          </div>
        </div>
      </div>
    </section>

    <footer>
      <div>&copy; <span id="yr"></span> Rentovator — All rights reserved.</div>
      <div style="color:var(--muted)">Built with care • For enquiries: sales@rentovator.example.com</div>
    </footer>
  </div>

  <script>
    // small interactive helpers
    document.getElementById('yr').textContent = new Date().getFullYear();

    function quickCheck(){
      const loc = document.getElementById('q-location').value.trim();
      const start = document.getElementById('q-start').value;
      const type = document.getElementById('q-type').value;
      const msg = document.getElementById('quick-msg');
      if(!loc || !start){ msg.textContent = 'Please enter location and start date.'; return; }
      msg.textContent = 'Thanks — we will check availability for ' + type + ' at ' + loc + ' starting ' + start + ' and contact you within 24 hours.';
      // Note: replace with actual backend / API integration.
    }

    function submitBooking(){
      const name = document.getElementById('name').value.trim();
      const phone = document.getElementById('phone').value.trim();
      const email = document.getElementById('email').value.trim();
      const location = document.getElementById('location').value.trim();
      const start = document.getElementById('start').value;
      const machine = document.getElementById('machine').value;
      const msgEl = document.getElementById('booking-msg');

      if(!name || !phone || !email || !location || !start){ msgEl.textContent = 'Please complete all required fields.'; return; }

      // For demo: create mailto link (client sends). Replace with AJAX to your API for production.
      const subject = encodeURIComponent('Booking request: ' + machine + ' - ' + name);
      const body = encodeURIComponent(
        `Name: ${name}\nCompany: ${document.getElementById('company').value}\nPhone: ${phone}\nEmail: ${email}\nLocation: ${location}\nStart: ${start}\nMachine: ${machine}\nNotes: ${document.getElementById('notes').value}`
      );

      // Try to open mail client
      window.location.href = 'mailto:sales@rentovator.example.com?subject=' + subject + '&body=' + body;
      msgEl.textContent = 'Opening mail client to send request. If nothing opens, email us at sales@rentovator.example.com';
    }

    function callSales(){
      window.location.href = 'tel:+91XXXXXXXXXX';
    }
  </script>
</body>
</html>
