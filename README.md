<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Greenwood Wellness Store – Trusted Supplements, Delivered by Amazon</title>
  <meta name="description" content="JoySpring favorites for speech, focus, and everyday wellness—plus Health & Beauty best-sellers. Fast Amazon delivery and secure checkout." />
  <meta name="theme-color" content="#059669" />

  <!-- Tailwind (CDN) -->
  <script src="https://cdn.tailwindcss.com"></script>

  <!-- Basic styles -->
  <style>
    .dot{width:6px;height:6px;border-radius:9999px;background:#9ca3af;margin-top:6px}
    .pill{border:1px solid rgba(255,255,255,.4)}
    .tab-btn{border-bottom-width:2px;border-color:transparent}
    .tab-btn.active{border-color:#059669;color:#059669;background:#ecfdf5}
  </style>
</head>
<body class="bg-gray-50 text-gray-900">
  <!-- Header / Hero -->
  <header class="relative isolate overflow-hidden bg-gradient-to-br from-emerald-600 via-emerald-500 to-teal-500 py-16 text-white">
    <div class="mx-auto max-w-6xl px-4">
      <div class="max-w-2xl">
        <h1 class="text-3xl font-bold sm:text-4xl">Greenwood Wellness Store</h1>
        <p class="mt-2 text-lg opacity-90">Trusted Supplements, Delivered by Amazon</p>
        <p class="mt-3 text-white/90">JoySpring favorites for speech, focus, and everyday wellness—plus Health & Beauty best-sellers.</p>
        <div class="mt-6 flex flex-wrap gap-3">
          <a id="shopLingo" href="#" target="_blank" rel="noopener" class="inline-flex items-center gap-2 rounded-2xl bg-white px-4 py-3 text-sm font-semibold text-emerald-700 shadow-sm transition hover:-translate-y-px">
            <span>Shop Lingo Leap</span>
            <svg xmlns="http://www.w3.org/2000/svg" class="h-4 w-4" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M3 3h7v7H3zM14 3h7v7h-7zM14 14h7v7h-7zM3 14h7v7H3z"/></svg>
          </a>
          <a href="#why" class="pill inline-flex items-center gap-2 rounded-2xl px-4 py-3 text-sm font-semibold text-white backdrop-blur-sm transition hover:-translate-y-px border border-white/40">
            Why buy through us?
          </a>
        </div>
      </div>
    </div>
    <div class="pointer-events-none absolute inset-0 -z-10 opacity-30" aria-hidden="true">
      <div class="absolute left-1/2 top-1/2 h-64 w-64 -translate-x-1/2 -translate-y-1/2 rounded-full bg-white blur-3xl"></div>
    </div>
  </header>

  <!-- Trust bar -->
  <div class="border-b bg-white/70">
    <div class="mx-auto flex max-w-6xl flex-wrap items-center justify-center gap-6 px-4 py-3 text-sm text-gray-700">
      <div class="inline-flex items-center gap-2">
        <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M3 7h13l3 5H6z"/><path d="M16 16a2 2 0 1 0 0 4 2 2 0 0 0 0-4M8 16a2 2 0 1 0 0 4 2 2 0 0 0 0-4"/></svg>
        <span>Fast Amazon delivery</span>
      </div>
      <div class="inline-flex items-center gap-2">
        <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M12 22s8-4 8-10V5l-8-3-8 3v7c0 6 8 10 8 10z"/><path d="M9 12l2 2 4-4"/></svg>
        <span>Secure checkout</span>
      </div>
      <div class="inline-flex items-center gap-2">
        <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M6 2v20M18 2v20M3 7h18M3 17h18"/></svg>
        <span>Family-friendly formulas</span>
      </div>
    </div>
  </div>

  <!-- Category Tabs -->
  <nav class="bg-white border-b">
    <div class="mx-auto max-w-6xl px-4">
      <div class="flex flex-wrap gap-2 py-3 text-sm">
        <button class="tab-btn active rounded-xl px-3 py-1.5" data-tab="joyspring">JoySpring</button>
        <button class="tab-btn rounded-xl px-3 py-1.5" data-tab="beauty">Health &amp; Beauty</button>
        <button class="tab-btn rounded-xl px-3 py-1.5" data-tab="vitamins">Vitamins &amp; Supplements</button>
        <button class="tab-btn rounded-xl px-3 py-1.5" data-tab="fitness">Fitness &amp; Weight Loss</button>
        <button class="tab-btn rounded-xl px-3 py-1.5" data-tab="kids">Baby &amp; Kids Wellness</button>
        <button class="tab-btn rounded-xl px-3 py-1.5" data-tab="grooming">Men’s Grooming Essentials</button>
      </div>
    </div>
  </nav>

  <!-- Main -->
  <main class="mx-auto max-w-6xl px-4 py-10">
    <h2 id="sectionTitle" class="text-2xl font-bold">Featured JoySpring Products</h2>
    <p id="sectionDesc" class="mt-1 text-gray-600">Carefully curated best-sellers you can recommend with confidence.</p>
    <div id="grid" class="mt-6 grid grid-cols-1 gap-4 sm:grid-cols-2 lg:grid-cols-3"></div>
  </main>

  <!-- Footer -->
  <footer class="mt-8 border-t bg-white">
    <div class="mx-auto max-w-6xl px-4 py-8 text-sm text-gray-600">
      <div id="why" class="grid grid-cols-1 gap-8 md:grid-cols-3">
        <div>
          <h3 class="font-semibold text-gray-900">Why buy through Greenwood Wellness Store?</h3>
          <ul class="mt-2 list-disc space-y-1 pl-5">
            <li>We curate top JoySpring products for speech, focus, and everyday wellness.</li>
            <li>All purchases are fulfilled by Amazon for fast shipping and easy returns.</li>
            <li>We keep links updated so you always land on the correct listing.</li>
          </ul>
        </div>
        <div>
          <h3 class="font-semibold text-gray-900">Affiliate Disclosure</h3>
          <p class="mt-2">As an Amazon Associate, Greenwood Wellness Store earns from qualifying purchases. This helps us create more educational content at no additional cost to you.</p>
        </div>
        <div>
          <h3 class="font-semibold text-gray-900">Health Disclaimer</h3>
          <p class="mt-2">Content on this site is for informational purposes only and is not a substitute for professional medical advice. Always consult a qualified healthcare provider.</p>
        </div>
      </div>
      <div class="mt-8 text-center text-xs">© 2025 Greenwood Investments Limited. All rights reserved.</div>
    </div>
  </footer>

  <!-- Single script block: data, logic, and rendering -->
  <script>
    // ---------- Affiliate tags ----------
    const AFFILIATE_TAG_US = "greenwoodinvestments-20";
    const AFFILIATE_TAG_CA = "greenwoodin01-20";

    // ---------- Region detection ----------
    const isCA =
      (navigator.language || "").toLowerCase().includes("en-ca") ||
      (Intl.DateTimeFormat().resolvedOptions().timeZone || "").includes("America/Edmonton") ||
      location.hostname.endsWith(".ca");

    // ---------- Inline placeholder image (no uploads needed) ----------
    const ph = (name) => {
      const svg = `
        <svg xmlns="http://www.w3.org/2000/svg" width="600" height="400">
          <defs>
            <linearGradient id="g" x1="0" y1="0" x2="1" y2="1">
              <stop offset="0%" stop-color="#ecfeff"/>
              <stop offset="100%" stop-color="#ecfdf5"/>
            </linearGradient>
          </defs>
          <rect width="600" height="400" fill="url(#g)"/>
          <rect x="24" y="24" width="552" height="352" rx="18" fill="#ffffff" stroke="#e5e7eb"/>
          <text x="50%" y="50%" dominant-baseline="middle" text-anchor="middle"
                fill="#065f46" font-family="system-ui, sans-serif" font-size="20" font-weight="700">
            ${name.replace(/</g,"&lt;").replace(/>/g,"&gt;")}
          </text>
        </svg>`;
      return "data:image/svg+xml;charset=UTF-8," + encodeURIComponent(svg);
    };

    // ---------- URL builder ----------
    function buyUrl(p) {
      // Prefer exact CA ASIN when in Canada, else fallback to CA search with tag
      if (isCA) {
        if (p.asinCA) return `https://www.amazon.ca/dp/${p.asinCA}?tag=${encodeURIComponent(AFFILIATE_TAG_CA)}`;
        return `https://www.amazon.ca/s?k=${encodeURIComponent(p.title)}&tag=${encodeURIComponent(AFFILIATE_TAG_CA)}`;
      }
      // Default: US exact ASIN with US tag
      return `https://www.amazon.com/dp/${p.asinUS}?tag=${encodeURIComponent(AFFILIATE_TAG_US)}`;
    }

    // ---------- Catalogs ----------
    const joyspring = [
      { title: "Lingo Leap", subtitle: "Speech & Communication Support Drops", image: ph("Lingo Leap"), asinUS:"B0D2F9CZR5", asinCA:"B0F47D7K8H", bullets:["Zeolite + D3 + B12","Language development","Kid-friendly drops"], badge:"Flagship" },
      { title: "Genius Drops (1 oz)", subtitle: "Clinically-Proven Focus Support", image: ph("Genius Drops 1 oz"), asinUS:"B075FH1P4Y", asinCA:null, bullets:["Ginkgo blend","Focus & attention","30 servings"] },
      { title: "Genius Drops (4 oz)", subtitle: "Family Size Focus Support", image: ph("Genius Drops 4 oz"), asinUS:"B07J6RFL35", asinCA:null, bullets:["Herbal nootropics","120 servings"] },
      { title: "Vitamin D3 Gummies for Kids", subtitle: "D3 + K2 – Growth & Development", image: ph("Vitamin D3 Gummies"), asinUS:"B0C87JFLDN", asinCA:null, bullets:["60 gummies","Kids & teens","Bone & immunity"] },
      { title: "Immune Drops", subtitle: "Elderberry + Echinacea + Oregon Grape Root", image: ph("Immune Drops"), asinUS:"B078WK3Q4K", asinCA:null, bullets:["Sugar-free","Herbal immunity","Family-friendly"] },
      { title: "Zeolite Drops for Kids", subtitle: "Natural Zeolite + Vitamin D3", image: ph("Zeolite Drops for Kids"), asinUS:"B0D2BKRDD7", asinCA:null, bullets:["Daily wellness","Zero-chemical zeolite","Berry flavor"] },
      { title: "Kids B-Complex", subtitle: "B Vitamins + Elderberry + Zinc + C", image: ph("Kids B-Complex"), asinUS:"B0B18RX61R", asinCA:null, bullets:["Overall wellness","30 servings","Amazon's Choice"] },
      { title: "School Backup Support Bundle", subtitle: "Immune wellness kit for kids & teens", image: ph("School Backup Support Bundle"), asinUS:"B0D9PHYCWF", asinCA:null, bullets:["Non-GMO","USA-made","Bundle savings"] }
    ];

    // Health & Beauty (global popular picks; images are inline placeholders)
    const beauty = [
      { title:"Mighty Patch Original (36 ct)", subtitle:"Hydrocolloid Acne Pimple Patches", image: ph("Mighty Patch Original"), asinUS:"B07MZ3X2W1", asinCA:null, bullets:["Overnight results","Protects & heals"], badge:"Best-seller" },
      { title:"Neutrogena Makeup Remover Wipes", subtitle:"Cleansing Towelettes", image: ph("Neutrogena Wipes"), asinUS:"B00U2VQZDS", asinCA:null, bullets:["Removes waterproof mascara","Soft on skin","Travel-friendly"] },
      { title:"e.l.f. Lash & Brow Enhancing Serum", subtitle:"Condition & boost look of lashes/brows", image: ph("e.l.f. Lash & Brow Serum"), asinUS:"B0B1F1N2H4", asinCA:null, bullets:["Peptides + vitamins","Clear, gentle formula"] },
      { title:"LANEIGE Lip Sleeping Mask", subtitle:"Overnight lip care", image: ph("LANEIGE Lip Sleeping Mask"), asinUS:"B07P9GTS1G", asinCA:null, bullets:["Ultra-moisturizing","Cult-favorite"] },
      { title:"Mielle Rosemary Mint Oil", subtitle:"Scalp & Hair Strengthening Oil (2 oz)", image: ph("Mielle Rosemary Mint Oil"), asinUS:"B07NQ98V3X", asinCA:null, bullets:["Biotin infused","For all hair types"] },
      { title:"CeraVe Eye Repair Cream", subtitle:"With Hyaluronic Acid & Ceramides", image: ph("CeraVe Eye Repair Cream"), asinUS:"B00JJPMXDO", asinCA:null, bullets:["Derm-developed","Fragrance-free"] },
      { title:"Sol de Janeiro Brazilian Crush '62", subtitle:"Body Fragrance Mist (Cheirosa '62)", image: ph("Sol de Janeiro '62 Mist"), asinUS:"B07HBTY3VJ", asinCA:null, bullets:["Pistachio & caramel","Iconic scent"] },
      { title:"Paula’s Choice 2% BHA Liquid", subtitle:"Salicylic Acid Exfoliant", image: ph("Paula’s Choice 2% BHA"), asinUS:"B00949CTQQ", asinCA:null, bullets:["Unclogs pores","Smoother skin"] },
      { title:"Good Molecules Gentle Retinol Cream", subtitle:"Beginner-friendly retinol", image: ph("Good Molecules Retinol"), asinUS:"B0BNSW5DL5", asinCA:null, bullets:["Encapsulated retinol","Soothing base"] },
      { title:"Olay Anti-Wrinkle 2-in-1", subtitle:"Day Cream + Serum", image: ph("Olay 2-in-1 Day Cream + Serum"), asinUS:"B003Y3FD2A", asinCA:null, bullets:["Niacinamide + aloe","Lightweight daily use"] }
    ];

    // Extra categories (placeholders; you can replace ASINs later if you want exact products)
    const vitamins = [
      { title:"Multivitamin (Adults)", subtitle:"Daily essential vitamins", image: ph("Multivitamin"), asinUS:"B0001V16IM", asinCA:null, bullets:["Energy support","Immune support"] },
      { title:"Vitamin C 1000 mg", subtitle:"With bioflavonoids", image: ph("Vitamin C"), asinUS:"B0001VK6Z0", asinCA:null, bullets:["Antioxidant","Immune health"] },
      { title:"Omega-3 Fish Oil", subtitle:"High EPA & DHA", image: ph("Omega-3 Fish Oil"), asinUS:"B002HWRZ2K", asinCA:null, bullets:["Heart & brain","Burpless"] }
    ];

    const fitness = [
      { title:"Electrolyte Powder", subtitle:"Hydration mix", image: ph("Electrolyte Powder"), asinUS:"B07P9X4QH8", asinCA:null, bullets:["Keto-friendly","Fast hydration"] },
      { title:"Protein Powder (Whey)", subtitle:"24g protein per scoop", image: ph("Whey Protein"), asinUS:"B000QSTBNS", asinCA:null, bullets:["Muscle support","Great taste"] },
      { title:"Creatine Monohydrate", subtitle:"5g per serving", image: ph("Creatine Monohydrate"), asinUS:"B002DYIZEO", asinCA:null, bullets:["Strength & power","Micronized"] }
    ];

    const kids = [
      { title:"Kids Multivitamin Gummies", subtitle:"Daily essential nutrients", image: ph("Kids Multivitamin Gummies"), asinUS:"B00K5N2YB4", asinCA:null, bullets:["Tasty gummies","No artificial flavors"] },
      { title:"Probiotic for Kids", subtitle:"Digestive health", image: ph("Kids Probiotic"), asinUS:"B00JZ7IBZQ", asinCA:null, bullets:["Chewable","Clinically studied strains"] }
    ];

    const grooming = [
      { title:"Beard Oil", subtitle:"Conditioning & softening", image: ph("Beard Oil"), asinUS:"B00M5E6AJ2", asinCA:null, bullets:["Natural oils","Tames frizz"] },
      { title:"Men’s Face Wash", subtitle:"Gentle daily cleanser", image: ph("Men’s Face Wash"), asinUS:"B00K2U5X5E", asinCA:null, bullets:["Non-drying","Fresh feel"] }
    ];

    // ---------- Tabs ----------
    const tabs = {
      joyspring: { title:"Featured JoySpring Products", desc:"Carefully curated best-sellers you can recommend with confidence.", items: joyspring },
      beauty:    { title:"Top Health & Beauty Best-Sellers", desc:"Highly-rated essentials added for your convenience.", items: beauty },
      vitamins:  { title:"Vitamins & Supplements", desc:"Daily essentials to support overall wellness.", items: vitamins },
      fitness:   { title:"Fitness & Weight Loss", desc:"Hydration, protein, and performance picks.", items: fitness },
      kids:      { title:"Baby & Kids Wellness", desc:"Family-friendly picks for growing kids.", items: kids },
      grooming:  { title:"Men’s Grooming Essentials", desc:"Simple upgrades for daily routines.", items: grooming },
    };

    // ---------- Render helpers ----------
    function productCard(p) {
      const li = document.createElement("div");
      li.className = "group relative flex flex-col justify-between rounded-2xl border bg-white p-4 shadow-sm transition hover:shadow-md";
      li.innerHTML = `
        <img src="${p.image}" alt="${p.title}" class="h-48 w-full rounded-xl object-cover"/>
        <div class="mt-3 flex items-start justify-between gap-3">
          <div>
            <h3 class="text-base font-semibold leading-tight">${p.title}</h3>
            <p class="text-sm text-gray-600">${p.subtitle}</p>
          </div>
          ${p.badge ? `<span class="inline-flex items-center gap-1 rounded-full border px-2 py-0.5 text-xs font-medium">⭐ ${p.badge}</span>` : ``}
        </div>
        <ul class="mt-3 space-y-1 text-sm text-gray-700">
          ${(p.bullets || []).map(b => `<li class="flex items-start gap-2"><span class="dot"></span><span>${b}</span></li>`).join("")}
        </ul>
        <div class="mt-4 flex items-center justify-end gap-2">
          <a href="${buyUrl(p)}" target="_blank" rel="nofollow sponsored noopener"
             class="inline-flex items-center gap-2 rounded-xl border bg-black px-3 py-2 text-sm font-semibold text-white transition hover:-translate-y-px hover:opacity-95">
            <svg xmlns="http://www.w3.org/2000/svg" class="h-4 w-4" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
              <path d="M6 6h15l-1.5 9h-12z"/><circle cx="9" cy="20" r="1.5"/><circle cx="18" cy="20" r="1.5"/>
            </svg>
            Add to Cart
          </a>
          <a href="${buyUrl(p)}" target="_blank" rel="nofollow sponsored noopener"
             class="inline-flex items-center gap-2 rounded-xl border px-3 py-2 text-sm font-semibold text-gray-700 transition hover:-translate-y-px hover:bg-gray-50">
            View
            <svg xmlns="http://www.w3.org/2000/svg" class="h-4 w-4" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
              <path d="M7 7h10v10"/><path d="M7 17 17 7"/>
            </svg>
          </a>
        </div>
      `;
      return li;
    }

    function renderTab(key) {
      const grid = document.getElementById("grid");
      const { title, desc, items } = tabs[key];
      document.getElementById("sectionTitle").textContent = title;
      document.getElementById("sectionDesc").textContent = desc;
      grid.innerHTML = "";
      items.forEach(p => grid.appendChild(productCard(p)));
      // Keep hero CTA pointing to Lingo Leap (JoySpring #1)
      document.getElementById("shopLingo").href = buyUrl(joyspring[0]);
    }

    // ---------- Init ----------
    document.querySelectorAll(".tab-btn").forEach(btn => {
      btn.addEventListener("click", () => {
        document.querySelectorAll(".tab-btn").forEach(b => b.classList.remove("active"));
        btn.classList.add("active");
        renderTab(btn.dataset.tab);
      });
    });
    renderTab("joyspring");
  </script>
</body>
</html>
