```html
<!DOCTYPE html>
<html lang="en" class="scroll-smooth">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
  <title>EmmyGrowth — Premier Capital Growth & Wealth Syndicate</title>
  
  <!-- PWA & Mobile Web App Meta Tags -->
  <meta name="apple-mobile-web-app-capable" content="yes">
  <meta name="apple-mobile-web-app-status-bar-style" content="black-translucent">
  <meta name="apple-mobile-web-app-title" content="EmmyGrowth">
  <meta name="application-name" content="EmmyGrowth">
  <meta name="theme-color" content="#04070f">
  <meta name="description" content="EmmyGrowth — Disciplined wealth growth, guaranteed private capital cycles, and high-yield syndicates. Direct customer care: +234 907 065 3906.">

  <!-- Manifest Data URI for immediate PWA installability -->
  <link rel="manifest" href="data:application/manifest+json;utf-8,%7B%22name%22%3A%22EmmyGrowth%20Syndicate%22%2C%22short_name%22%3A%22EmmyGrowth%22%2C%22start_url%22%3A%22.%22%2C%22display%22%3A%22standalone%22%2C%22background_color%22%3A%22%2304070f%22%2C%22theme_color%22%3A%22%2310b981%22%2C%22description%22%3A%22Premier%20Capital%20Growth%20%26%20Wealth%20Syndicate%22%2C%22icons%22%3A%5B%7B%22src%22%3A%22https%3A%2F%2Fapi.iconify.design%2Flucide%3Atrending-up.svg%3Fcolor%3D%252310b981%22%2C%22sizes%22%3A%22192x192%22%2C%22type%22%3A%22image%2Fsvg%2Bxml%22%7D%5D%7D">

  <!-- Tailwind CSS CDN -->
  <script src="https://cdn.tailwindcss.com"></script>
  <script>
    tailwind.config = {
      darkMode: 'class',
      theme: {
        extend: {
          colors: {
            brand: {
              50: '#ecfdf5',
              100: '#d1fae5',
              300: '#6ee7b7',
              400: '#34d399',
              500: '#10b981',
              600: '#059669',
              700: '#047857',
              800: '#065f46',
              900: '#064e3b',
            },
            navy: {
              800: '#0f172a',
              850: '#0b1120',
              900: '#070d18',
              950: '#04070f',
            }
          },
          fontFamily: {
            sans: ['"Plus Jakarta Sans"', 'Inter', 'system-ui', 'sans-serif'],
            mono: ['"JetBrains Mono"', 'monospace']
          }
        }
      }
    }
  </script>

  <!-- FontAwesome & Google Fonts -->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=JetBrains+Mono:wght@400;500;700&family=Plus+Jakarta+Sans:wght@300;400;500;600;700;800&display=swap" rel="stylesheet">

  <style>
    body {
      font-family: 'Plus Jakarta Sans', sans-serif;
      background-color: #04070f;
      color: #f1f5f9;
      -webkit-tap-highlight-color: transparent;
    }
    .font-mono-numbers {
      font-family: 'JetBrains Mono', monospace;
    }
    .glass-panel {
      background: rgba(11, 17, 32, 0.75);
      backdrop-filter: blur(16px);
      -webkit-backdrop-filter: blur(16px);
      border: 1px solid rgba(255, 255, 255, 0.08);
    }
    .glass-glow {
      box-shadow: 0 0 35px -5px rgba(16, 185, 129, 0.15);
    }
    .emerald-gradient-text {
      background: linear-gradient(135deg, #6ee7b7 0%, #10b981 50%, #059669 100%);
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
    }
    input[type=range] {
      -webkit-appearance: none;
      background: #1e293b;
      height: 8px;
      border-radius: 9999px;
    }
    input[type=range]::-webkit-slider-thumb {
      -webkit-appearance: none;
      height: 24px;
      width: 24px;
      border-radius: 50%;
      background: #10b981;
      cursor: pointer;
      box-shadow: 0 0 14px rgba(16, 185, 129, 0.8);
      border: 2px solid #ffffff;
    }
    /* Subtle custom scrollbar */
    ::-webkit-scrollbar {
      width: 6px;
      height: 6px;
    }
    ::-webkit-scrollbar-track {
      background: #04070f;
    }
    ::-webkit-scrollbar-thumb {
      background: #1e293b;
      border-radius: 9999px;
    }
    ::-webkit-scrollbar-thumb:hover {
      background: #10b981;
    }
  </style>
</head>
<body class="min-h-screen flex flex-col selection:bg-brand-500 selection:text-navy-950">

  <!-- ================= TOP CARE & CREDENTIAL ANNOUNCEMENT ================= -->
  <div class="bg-navy-900 border-b border-white/5 py-2 px-3 sm:px-6 text-xs text-slate-300">
    <div class="max-w-7xl mx-auto flex flex-wrap items-center justify-between gap-2">
      <div class="flex items-center gap-3">
        <span class="inline-flex items-center gap-1.5 text-brand-400 font-semibold">
          <span class="relative flex h-2 w-2">
            <span class="animate-ping absolute inline-flex h-full w-full rounded-full bg-brand-400 opacity-75"></span>
            <span class="relative inline-flex rounded-full h-2 w-2 bg-brand-500"></span>
          </span>
          Guaranteed Syndicate Capital
        </span>
        <span class="hidden md:inline text-slate-700">|</span>
        <span class="hidden md:inline text-slate-400">RC: 3892014 • Fixed Yield Escrow Protocol</span>
      </div>

      <div class="flex items-center space-x-3 ml-auto text-xs">
        <span class="text-slate-400 hidden sm:inline">24/7 Investor Care:</span>
        <a href="tel:+2349070653906" class="text-brand-400 font-bold hover:text-brand-300 flex items-center gap-1.5 transition">
          <i class="fa-solid fa-phone text-[11px]"></i> +234 907 065 3906
        </a>
        <a href="https://wa.me/2349070653906?text=Hello%20EmmyGrowth%20Customer%20Desk,%20I%20am%20interested%20in%20investing" target="_blank" class="bg-brand-500/15 hover:bg-brand-500/25 text-brand-400 px-2.5 py-0.5 rounded-full border border-brand-500/30 flex items-center gap-1 font-semibold transition">
          <i class="fa-brands fa-whatsapp text-sm text-brand-400"></i> WhatsApp
        </a>
      </div>
    </div>
  </div>

  <!-- ================= NAVIGATION HEADER ================= -->
  <header class="sticky top-0 z-40 bg-navy-950/85 backdrop-blur-xl border-b border-white/10">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 h-20 flex items-center justify-between">
      
      <!-- Logo & Brand -->
      <div class="flex items-center space-x-3 cursor-pointer" onclick="switchTab('public')">
        <div class="w-11 h-11 rounded-2xl bg-gradient-to-tr from-brand-600 via-brand-500 to-emerald-300 flex items-center justify-center text-navy-950 shadow-lg shadow-brand-500/25 ring-2 ring-brand-400/30">
          <i class="fa-solid fa-arrow-trend-up text-xl font-black"></i>
        </div>
        <div>
          <span class="text-2xl font-black tracking-tight text-white flex items-center gap-0.5">
            Emmy<span class="emerald-gradient-text">Growth</span>
          </span>
          <span class="block text-[10px] text-slate-400 -mt-1 font-semibold tracking-wider uppercase">Private Syndicate • RC 3892014</span>
        </div>
      </div>

      <!-- Center Dynamic Role Bar -->
      <div class="hidden lg:flex items-center bg-navy-900/90 border border-white/10 rounded-2xl p-1 text-xs shadow-inner">
        <button onclick="switchTab('public')" id="pill-public" class="role-pill px-4 py-2 rounded-xl text-white bg-white/10 font-bold transition flex items-center gap-2">
          <i class="fa-solid fa-earth-africa text-brand-400"></i> Public Site
        </button>
        <button onclick="switchTab('user')" id="pill-user" class="role-pill px-4 py-2 rounded-xl text-slate-400 hover:text-white font-bold transition flex items-center gap-2">
          <i class="fa-solid fa-wallet text-brand-400"></i> Investor Portal
        </button>
        <button onclick="switchTab('admin')" id="pill-admin" class="role-pill px-4 py-2 rounded-xl text-slate-400 hover:text-white font-bold transition flex items-center gap-2">
          <i class="fa-solid fa-shield-halved text-amber-400"></i> Admin Console
        </button>
      </div>

      <!-- Utilities & Install -->
      <div class="flex items-center space-x-2.5">
        <!-- Install / Download PWA Modal Trigger -->
        <button onclick="triggerPWAInstall()" class="bg-brand-500/10 hover:bg-brand-500/20 text-brand-300 border border-brand-500/30 px-3.5 py-2 rounded-xl text-xs font-bold transition flex items-center gap-1.5 shadow-sm">
          <i class="fa-solid fa-mobile-screen-button text-xs text-brand-400"></i>
          <span>Download / Install App</span>
        </button>

        <!-- Customer Care Trigger -->
        <button onclick="openModal('supportModal')" class="bg-white/5 hover:bg-white/10 text-white border border-white/10 px-3 py-2 rounded-xl text-xs font-bold transition flex items-center gap-1.5">
          <i class="fa-solid fa-headset text-brand-400"></i>
          <span class="hidden md:inline">Support</span>
        </button>

        <!-- Standalone HTML Exporter -->
        <button onclick="exportSingleFileSource()" title="Download Complete Standalone Source (.html)" class="bg-navy-900 hover:bg-navy-800 text-slate-300 border border-white/10 p-2.5 rounded-xl text-xs font-bold transition">
          <i class="fa-solid fa-file-arrow-down text-brand-400"></i>
        </button>

        <!-- Mobile Drawer Toggle -->
        <button onclick="toggleMobileNav()" class="lg:hidden text-slate-300 hover:text-white p-2 text-xl ml-1">
          <i class="fa-solid fa-bars-staggered"></i>
        </button>
      </div>

    </div>

    <!-- Mobile Navigation Drawer -->
    <div id="mobileDrawer" class="hidden lg:hidden bg-navy-950 border-b border-white/10 px-5 py-4 space-y-3">
      <div class="grid grid-cols-3 gap-2 pb-3 border-b border-white/10">
        <button onclick="switchTab('public'); toggleMobileNav();" class="py-2.5 px-2 text-center rounded-xl bg-white/5 text-xs font-bold text-white border border-white/10">Public</button>
        <button onclick="switchTab('user'); toggleMobileNav();" class="py-2.5 px-2 text-center rounded-xl bg-brand-500/15 text-xs font-bold text-brand-400 border border-brand-500/30">Investor</button>
        <button onclick="switchTab('admin'); toggleMobileNav();" class="py-2.5 px-2 text-center rounded-xl bg-amber-500/15 text-xs font-bold text-amber-300 border border-amber-500/30">Admin</button>
      </div>
      <div class="flex flex-col gap-2.5 text-xs font-medium text-slate-300 pt-1">
        <a href="tel:+2349070653906" class="flex items-center justify-between p-3 rounded-xl bg-navy-900 border border-white/5">
          <span class="flex items-center gap-2"><i class="fa-solid fa-phone text-brand-400"></i> Dial Customer Care Desk</span>
          <span class="font-bold text-brand-400">+234 907 065 3906</span>
        </a>
        <a href="https://wa.me/2349070653906?text=Hello%20EmmyGrowth%20Desk" target="_blank" class="flex items-center justify-between p-3 rounded-xl bg-emerald-950/60 border border-emerald-500/20 text-emerald-300">
          <span class="flex items-center gap-2"><i class="fa-brands fa-whatsapp text-emerald-400"></i> Chat on WhatsApp</span>
          <span class="font-bold">+234 907 065 3906</span>
        </a>
      </div>
    </div>
  </header>

  <!-- ================= MAIN BODY CONTENT ================= -->
  <main class="flex-1 pb-20">

    <!-- ======================================================== -->
    <!-- VIEW 1: PUBLIC LANDING PAGE                              -->
    <!-- ======================================================== -->
    <section id="view-public" class="space-y-20 pt-8 sm:pt-14">
      
      <!-- Hero Banner -->
      <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 relative text-center">
        <div class="inline-flex items-center gap-2 px-4 py-1.5 rounded-full bg-brand-500/10 border border-brand-500/30 text-brand-300 text-xs font-semibold mb-6 shadow-sm">
          <i class="fa-solid fa-certificate text-brand-400"></i> Institutional Yields for Private Co-Investors
        </div>

        <h1 class="text-4xl sm:text-6xl lg:text-7xl font-extrabold tracking-tight text-white max-w-4xl mx-auto leading-[1.15]">
          Invest directly with us for <span class="emerald-gradient-text">predictable capital</span> compounding.
        </h1>

        <p class="mt-6 text-base sm:text-lg text-slate-300 max-w-2xl mx-auto leading-relaxed">
          EmmyGrowth combines trade-finance liquidity, real estate bridge notes, and agricultural export contracts into secure, contract-backed monthly and quarterly return instruments.
        </p>

        <!-- CTA Buttons -->
        <div class="mt-8 flex flex-wrap justify-center items-center gap-4">
          <button onclick="switchTab('user')" class="px-7 py-4 rounded-2xl font-bold bg-brand-500 hover:bg-brand-400 text-navy-950 transition shadow-xl shadow-brand-500/20 text-sm flex items-center gap-2">
            Open Investor Account <i class="fa-solid fa-arrow-right"></i>
          </button>
          <a href="tel:+2349070653906" class="px-6 py-4 rounded-2xl font-semibold bg-navy-900 hover:bg-navy-850 text-white border border-white/10 transition text-sm flex items-center gap-2">
            <i class="fa-solid fa-phone text-brand-400"></i> Customer Care: +234 907 065 3906
          </a>
        </div>

        <!-- Metric Badges -->
        <div class="grid grid-cols-2 md:grid-cols-4 gap-4 max-w-4xl mx-auto mt-14 pt-8 border-t border-white/10">
          <div class="p-4 rounded-2xl bg-navy-900/60 border border-white/5">
            <div class="text-2xl sm:text-3xl font-extrabold text-white font-mono-numbers" id="public-hero-aum">₦1.85B+</div>
            <div class="text-[11px] text-slate-400 mt-1 uppercase tracking-wider font-semibold">Capital Managed (AUM)</div>
          </div>
          <div class="p-4 rounded-2xl bg-navy-900/60 border border-white/5">
            <div class="text-2xl sm:text-3xl font-extrabold text-brand-400 font-mono-numbers">2,410+</div>
            <div class="text-[11px] text-slate-400 mt-1 uppercase tracking-wider font-semibold">Active Co-Investors</div>
          </div>
          <div class="p-4 rounded-2xl bg-navy-900/60 border border-white/5">
            <div class="text-2xl sm:text-3xl font-extrabold text-white font-mono-numbers">100%</div>
            <div class="text-[11px] text-slate-400 mt-1 uppercase tracking-wider font-semibold">Yield Fulfillment</div>
          </div>
          <div class="p-4 rounded-2xl bg-navy-900/60 border border-white/5">
            <div class="text-2xl sm:text-3xl font-extrabold text-emerald-400 font-mono-numbers">14% - 60%</div>
            <div class="text-[11px] text-slate-400 mt-1 uppercase tracking-wider font-semibold">Annualized Rates</div>
          </div>
        </div>
      </div>

      <!-- Live Interactive Yield Calculator -->
      <section class="max-w-5xl mx-auto px-4 sm:px-6 lg:px-8">
        <div class="glass-panel rounded-3xl p-6 sm:p-10 border border-brand-500/20 glass-glow">
          <div class="text-center max-w-xl mx-auto mb-8">
            <span class="text-xs font-bold text-brand-400 uppercase tracking-widest">TRANSPARENT FORECAST</span>
            <h2 class="text-2xl sm:text-3xl font-bold text-white mt-1">Live Profit Calculator</h2>
            <p class="text-xs sm:text-sm text-slate-400 mt-1">Simulate exactly what your principal capital yields upon maturity.</p>
          </div>

          <div class="grid lg:grid-cols-12 gap-8 items-center">
            <!-- Controls -->
            <div class="lg:col-span-7 space-y-6">
              <div>
                <div class="flex justify-between items-center mb-2">
                  <label class="text-xs font-bold text-slate-300">Investment Capital (₦)</label>
                  <span id="calc-display-amount" class="text-xl font-extrabold text-white font-mono-numbers">₦500,000</span>
                </div>
                <input type="range" id="calc-slider" min="50000" max="10000000" step="25000" value="500000" class="w-full" oninput="runCalculator()">
                <div class="flex justify-between text-[11px] text-slate-500 mt-1.5 font-mono">
                  <span>₦50,000</span>
                  <span>₦5,000,000</span>
                  <span>₦10,000,000</span>
                </div>
              </div>

              <div>
                <label class="block text-xs font-bold text-slate-300 mb-2.5">Select Tenure Duration</label>
                <div class="grid grid-cols-3 gap-2 sm:gap-3">
                  <button type="button" onclick="setCalcTenor(3, 14)" id="calc-btn-3" class="calc-tenor py-3 px-2 rounded-xl text-xs font-bold border border-white/10 bg-white/5 hover:border-brand-500/40 transition">
                    3 Months <span class="block text-[11px] text-brand-400 font-normal">14% Total</span>
                  </button>
                  <button type="button" onclick="setCalcTenor(6, 30)" id="calc-btn-6" class="calc-tenor py-3 px-2 rounded-xl text-xs font-bold border border-brand-500 bg-brand-500/20 text-brand-300 transition">
                    6 Months <span class="block text-[11px] text-brand-400 font-normal">30% Total</span>
                  </button>
                  <button type="button" onclick="setCalcTenor(12, 60)" id="calc-btn-12" class="calc-tenor py-3 px-2 rounded-xl text-xs font-bold border border-white/10 bg-white/5 hover:border-brand-500/40 transition">
                    12 Months <span class="block text-[11px] text-brand-400 font-normal">60% Total</span>
                  </button>
                </div>
              </div>

              <div class="p-3 rounded-xl bg-navy-900 border border-white/5 text-[11px] text-slate-400 flex items-center gap-2.5">
                <i class="fa-solid fa-shield-halved text-brand-400 text-sm"></i>
                <span>Backed by executive deeds of agreement and verified physical collateral.</span>
              </div>
            </div>

            <!-- Breakdown Summary Box -->
            <div class="lg:col-span-5 bg-navy-900/90 rounded-2xl p-6 border border-white/10 space-y-4">
              <div class="text-xs font-bold uppercase tracking-wider text-slate-400">Estimated Return Ledger</div>
              <div class="flex justify-between text-xs py-2 border-b border-white/5">
                <span class="text-slate-400">Principal Allocation:</span>
                <span id="calc-sum-principal" class="font-bold text-white font-mono-numbers">₦500,000</span>
              </div>
              <div class="flex justify-between text-xs py-2 border-b border-white/5">
                <span class="text-slate-400">Guaranteed Return (<span id="calc-sum-rate">30%</span>):</span>
                <span id="calc-sum-profit" class="font-bold text-brand-400 font-mono-numbers">+₦150,000</span>
              </div>
              <div class="pt-2">
                <span class="text-xs text-slate-400">Total Maturity Settlement:</span>
                <div id="calc-sum-total" class="text-3xl font-black text-white font-mono-numbers mt-1">₦650,000</div>
              </div>

              <button onclick="subscribeCalculatedPlan()" class="w-full mt-4 py-3.5 rounded-xl font-bold text-xs bg-brand-500 hover:bg-brand-400 text-navy-950 transition flex items-center justify-center gap-2 shadow-lg shadow-brand-500/20">
                Lock in this Allocation <i class="fa-solid fa-arrow-right"></i>
              </button>
            </div>
          </div>
        </div>
      </section>

      <!-- Syndicate Investment Tiers -->
      <section class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
        <div class="text-center max-w-2xl mx-auto mb-12">
          <span class="text-xs font-bold text-brand-400 uppercase tracking-widest">OFFICIAL PACKAGES</span>
          <h2 class="text-3xl font-extrabold text-white mt-1">Syndicate Investment Tiers</h2>
          <p class="text-xs sm:text-sm text-slate-400 mt-2">Choose your desired liquidity tenor. Payouts are made directly to your verified local bank account.</p>
        </div>

        <div class="grid md:grid-cols-3 gap-6">
          <!-- Tier 1 -->
          <div class="glass-panel rounded-3xl p-7 flex flex-col justify-between hover:border-brand-500/40 transition group">
            <div>
              <div class="flex justify-between items-center mb-4">
                <span class="text-xs font-extrabold px-3 py-1 rounded-full bg-white/5 text-slate-300 border border-white/10">Tier 01</span>
                <span class="text-xs font-bold text-brand-400"><i class="fa-solid fa-clock mr-1"></i> 90 Days</span>
              </div>
              <h3 class="text-xl font-bold text-white">Starter Seed</h3>
              <p class="text-xs text-slate-400 mt-1">Short-term liquidity pool designed for new private partners.</p>
              
              <div class="my-6 p-4 rounded-2xl bg-white/5 border border-white/5">
                <span class="text-xs text-slate-400">Fixed Return</span>
                <div class="text-3xl font-black text-brand-400 font-mono-numbers mt-0.5">14% <span class="text-xs font-normal text-slate-400">/ 3 Mos</span></div>
              </div>

              <ul class="space-y-2.5 text-xs text-slate-300 mb-6">
                <li><i class="fa-solid fa-check text-brand-400 mr-2"></i> Min: <strong>₦50,000</strong> — Max: <strong>₦249,000</strong></li>
                <li><i class="fa-solid fa-check text-brand-400 mr-2"></i> Monthly Yield Withdrawal</li>
                <li><i class="fa-solid fa-check text-brand-400 mr-2"></i> Digital Contract Certificate</li>
              </ul>
            </div>
            <button onclick="quickInvest('Starter Seed', 50000, 14, 3)" class="w-full py-3 rounded-xl font-bold text-xs bg-white/10 hover:bg-brand-500 hover:text-navy-950 text-white transition">
              Select Starter Seed
            </button>
          </div>

          <!-- Tier 2 -->
          <div class="glass-panel rounded-3xl p-7 flex flex-col justify-between border-brand-500/60 shadow-2xl shadow-brand-500/10 relative group">
            <div class="absolute -top-3 left-1/2 -translate-x-1/2 bg-brand-500 text-navy-950 text-[10px] font-black uppercase tracking-wider px-3.5 py-1 rounded-full">
              Most Popular
            </div>
            <div>
              <div class="flex justify-between items-center mb-4 mt-2">
                <span class="text-xs font-extrabold px-3 py-1 rounded-full bg-brand-500/20 text-brand-300 border border-brand-500/30">Tier 02</span>
                <span class="text-xs font-bold text-brand-400"><i class="fa-solid fa-clock mr-1"></i> 180 Days</span>
              </div>
              <h3 class="text-xl font-bold text-white">Growth Syndicate</h3>
              <p class="text-xs text-slate-400 mt-1">Accelerated compounding backed by active trade-finance supply chains.</p>
              
              <div class="my-6 p-4 rounded-2xl bg-brand-500/15 border border-brand-500/30">
                <span class="text-xs text-brand-200">Fixed Return</span>
                <div class="text-3xl font-black text-brand-400 font-mono-numbers mt-0.5">30% <span class="text-xs font-normal text-slate-400">/ 6 Mos</span></div>
              </div>

              <ul class="space-y-2.5 text-xs text-slate-300 mb-6">
                <li><i class="fa-solid fa-check text-brand-400 mr-2"></i> Min: <strong>₦250,000</strong> — Max: <strong>₦999,000</strong></li>
                <li><i class="fa-solid fa-check text-brand-400 mr-2"></i> Priority Disbursal Queue</li>
                <li><i class="fa-solid fa-check text-brand-400 mr-2"></i> Dedicated Desk Officer</li>
              </ul>
            </div>
            <button onclick="quickInvest('Growth Syndicate', 250000, 30, 6)" class="w-full py-3 rounded-xl font-bold text-xs bg-brand-500 hover:bg-brand-400 text-navy-950 transition shadow-lg shadow-brand-500/25">
              Select Growth Syndicate
            </button>
          </div>

          <!-- Tier 3 -->
          <div class="glass-panel rounded-3xl p-7 flex flex-col justify-between hover:border-brand-500/40 transition group">
            <div>
              <div class="flex justify-between items-center mb-4">
                <span class="text-xs font-extrabold px-3 py-1 rounded-full bg-white/5 text-slate-300 border border-white/10">Tier 03</span>
                <span class="text-xs font-bold text-brand-400"><i class="fa-solid fa-clock mr-1"></i> 365 Days</span>
              </div>
              <h3 class="text-xl font-bold text-white">Institutional Whale</h3>
              <p class="text-xs text-slate-400 mt-1">High-yield asset management portfolio for seasoned investors.</p>
              
              <div class="my-6 p-4 rounded-2xl bg-white/5 border border-white/5">
                <span class="text-xs text-slate-400">Fixed Return</span>
                <div class="text-3xl font-black text-brand-400 font-mono-numbers mt-0.5">60% <span class="text-xs font-normal text-slate-400">/ 1 Year</span></div>
              </div>

              <ul class="space-y-2.5 text-xs text-slate-300 mb-6">
                <li><i class="fa-solid fa-check text-brand-400 mr-2"></i> Min: <strong>₦1,000,000</strong> — Max: <strong>₦50,000,000+</strong></li>
                <li><i class="fa-solid fa-check text-brand-400 mr-2"></i> Hardcopy Notarized Deed</li>
                <li><i class="fa-solid fa-check text-brand-400 mr-2"></i> 24/7 VIP Direct Telephone Line</li>
              </ul>
            </div>
            <button onclick="quickInvest('Institutional Whale', 1000000, 60, 12)" class="w-full py-3 rounded-xl font-bold text-xs bg-white/10 hover:bg-brand-500 hover:text-navy-950 text-white transition">
              Select Institutional
            </button>
          </div>
        </div>
      </section>

      <!-- Customer Consultation Banner -->
      <section class="max-w-5xl mx-auto px-4 sm:px-6 lg:px-8">
        <div class="p-8 sm:p-10 rounded-3xl bg-gradient-to-r from-navy-900 via-navy-850 to-navy-900 border border-brand-500/30 text-center relative overflow-hidden shadow-2xl">
          <div class="w-14 h-14 rounded-2xl bg-brand-500/20 text-brand-400 flex items-center justify-center text-2xl mx-auto mb-4 border border-brand-500/30">
            <i class="fa-solid fa-headset"></i>
          </div>
          <h3 class="text-2xl font-extrabold text-white">Need Consultation Before Depositing?</h3>
          <p class="text-xs sm:text-sm text-slate-300 max-w-xl mx-auto mt-2">
            Speak directly with our Syndicate Coordinator or Customer Desk for physical confirmations and institutional onboarding.
          </p>
          <div class="mt-6 flex flex-wrap justify-center items-center gap-3">
            <a href="tel:+2349070653906" class="px-6 py-3.5 rounded-xl bg-brand-500 hover:bg-brand-400 text-navy-950 font-bold text-xs transition flex items-center gap-2">
              <i class="fa-solid fa-phone"></i> Call +234 907 065 3906
            </a>
            <a href="https://wa.me/2349070653906?text=Hello%20EmmyGrowth,%20I%20would%20like%20to%20learn%20more%20about%20your%20investment%20options." target="_blank" class="px-6 py-3.5 rounded-xl bg-emerald-600/30 hover:bg-emerald-600/50 border border-emerald-500/40 text-emerald-300 font-bold text-xs transition flex items-center gap-2">
              <i class="fa-brands fa-whatsapp text-sm"></i> WhatsApp Support Desk
            </a>
          </div>
        </div>
      </section>
    </section>

    <!-- ======================================================== -->
    <!-- VIEW 2: INVESTOR DASHBOARD VIEW                          -->
    <!-- ======================================================== -->
    <section id="view-user" class="hidden max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 pt-6 space-y-6">
      
      <!-- User Profile Header -->
      <div class="p-6 glass-panel rounded-3xl flex flex-col md:flex-row md:items-center justify-between gap-4 border border-white/10">
        <div>
          <div class="flex items-center gap-2.5">
            <h2 class="text-2xl font-bold text-white">Investor Portfolio</h2>
            <span class="text-[10px] font-bold px-2.5 py-0.5 rounded-full bg-brand-500/20 text-brand-300 border border-brand-500/30 flex items-center gap-1">
              <i class="fa-solid fa-circle-check text-[9px]"></i> Tier-1 Verified
            </span>
          </div>
          <p class="text-xs text-slate-400 mt-1">Logged in as <strong class="text-white">Chief Emmanuel</strong> • Account ID: <span class="font-mono text-brand-400">EMG-9034</span></p>
        </div>

        <div class="flex flex-wrap items-center gap-2">
          <button onclick="openModal('depositModal')" class="px-4 py-2.5 rounded-xl text-xs font-bold bg-brand-500 hover:bg-brand-400 text-navy-950 transition flex items-center gap-1.5 shadow-md shadow-brand-500/20">
            <i class="fa-solid fa-circle-arrow-down"></i> Deposit Funds
          </button>
          <button onclick="openModal('withdrawModal')" class="px-4 py-2.5 rounded-xl text-xs font-bold bg-white/10 hover:bg-white/15 text-white border border-white/10 transition flex items-center gap-1.5">
            <i class="fa-solid fa-circle-arrow-up"></i> Request Withdrawal
          </button>
          <button onclick="openModal('newPlanModal')" class="px-4 py-2.5 rounded-xl text-xs font-bold bg-brand-600 hover:bg-brand-500 text-white transition flex items-center gap-1.5">
            <i class="fa-solid fa-plus"></i> Invest in Tier
          </button>
        </div>
      </div>

      <!-- Financial KPI Cards -->
      <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-4">
        
        <div class="glass-panel rounded-2xl p-5 border border-white/10">
          <span class="text-xs font-semibold text-slate-400">Active Capital</span>
          <div id="user-kpi-invested" class="text-2xl font-black text-white font-mono-numbers mt-1.5">₦0</div>
          <div class="text-[11px] text-brand-400 mt-1 flex items-center gap-1 font-semibold">
            <i class="fa-solid fa-vault"></i> <span id="user-kpi-plan-count">0 Active Contracts</span>
          </div>
        </div>

        <div class="glass-panel rounded-2xl p-5 border border-white/10">
          <span class="text-xs font-semibold text-slate-400">Accrued Yield Profit</span>
          <div id="user-kpi-yield" class="text-2xl font-black text-brand-400 font-mono-numbers mt-1.5">₦0</div>
          <div class="text-[11px] text-slate-400 mt-1">Maturity-guaranteed</div>
        </div>

        <div class="glass-panel rounded-2xl p-5 border border-white/10">
          <span class="text-xs font-semibold text-slate-400">Available Liquid Wallet</span>
          <div id="user-kpi-balance" class="text-2xl font-black text-white font-mono-numbers mt-1.5">₦0</div>
          <div class="text-[11px] text-emerald-400 mt-1 flex items-center gap-1 font-semibold">
            <i class="fa-solid fa-arrow-down-up-across-line"></i> Ready for payout
          </div>
        </div>

        <div class="glass-panel rounded-2xl p-5 border border-white/10">
          <span class="text-xs font-semibold text-slate-400">Support Desk Hotline</span>
          <div class="text-sm font-bold text-white mt-1.5">EmmyGrowth Care</div>
          <div class="text-[11px] text-brand-400 mt-1 font-mono">
            <a href="tel:+2349070653906" class="hover:underline flex items-center gap-1">
              <i class="fa-solid fa-phone text-[10px]"></i> +234 907 065 3906
            </a>
          </div>
        </div>

      </div>

      <!-- Active Contracts Section -->
      <div class="glass-panel rounded-3xl p-6 border border-white/10">
        <div class="flex justify-between items-center mb-5">
          <div>
            <h3 class="text-lg font-bold text-white">Active Investment Contracts</h3>
            <p class="text-xs text-slate-400">Live contracts, completion cycle, and expected returns.</p>
          </div>
          <button onclick="openModal('newPlanModal')" class="text-xs text-brand-400 hover:text-brand-300 font-bold">
            + New Contract
          </button>
        </div>

        <div id="user-plans-list" class="space-y-3.5">
          <!-- Populated by JavaScript -->
        </div>
      </div>

      <!-- Transaction Ledger Section -->
      <div class="glass-panel rounded-3xl p-6 border border-white/10">
        <div class="flex justify-between items-center mb-5">
          <div>
            <h3 class="text-lg font-bold text-white">Transaction History</h3>
            <p class="text-xs text-slate-400">Full record of deposits, investments, and payouts.</p>
          </div>
          <button onclick="triggerToast('Official audited statement generated. Ready for export.', 'info')" class="text-xs bg-white/5 hover:bg-white/10 px-3 py-1.5 rounded-lg text-slate-300 border border-white/10">
            Export Statement
          </button>
        </div>

        <div class="overflow-x-auto">
          <table class="w-full text-left text-xs">
            <thead class="text-slate-400 uppercase tracking-wider border-b border-white/10 bg-white/5 font-semibold">
              <tr>
                <th class="py-3 px-4">Ref Code</th>
                <th class="py-3 px-4">Type</th>
                <th class="py-3 px-4">Details</th>
                <th class="py-3 px-4">Amount</th>
                <th class="py-3 px-4">Date</th>
                <th class="py-3 px-4">Status</th>
              </tr>
            </thead>
            <tbody id="user-ledger-tbody" class="divide-y divide-white/5 text-slate-300">
              <!-- Populated by JavaScript -->
            </tbody>
          </table>
        </div>
      </div>

    </section>

    <!-- ======================================================== -->
    <!-- VIEW 3: ADMIN MANAGEMENT CONSOLE                         -->
    <!-- ======================================================== -->
    <section id="view-admin" class="hidden max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 pt-6 space-y-6">
      
      <!-- Admin Header Banner -->
      <div class="p-6 glass-panel rounded-3xl flex flex-col md:flex-row md:items-center justify-between gap-4 border border-amber-500/25 bg-amber-500/5">
        <div>
          <div class="flex items-center gap-2">
            <span class="w-2.5 h-2.5 rounded-full bg-amber-400 animate-pulse"></span>
            <h2 class="text-2xl font-bold text-white">Syndicate Super-Admin Console</h2>
          </div>
          <p class="text-xs text-slate-400 mt-1">Review capital submissions, approve manual bank receipts, and clear investor payouts.</p>
        </div>

        <div class="flex items-center gap-3">
          <div class="text-right text-xs">
            <span class="text-slate-400 block">Customer Care Hotline</span>
            <span class="text-brand-400 font-bold font-mono">+234 907 065 3906</span>
          </div>
          <button onclick="promptBroadcast()" class="px-3.5 py-2 rounded-xl text-xs font-bold bg-amber-500/20 text-amber-300 border border-amber-500/30 hover:bg-amber-500/30 transition">
            <i class="fa-solid fa-bullhorn mr-1"></i> Broadcast
          </button>
        </div>
      </div>

      <!-- Global Metrics -->
      <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-4">
        <div class="glass-panel rounded-2xl p-5 border border-white/10">
          <span class="text-xs font-semibold text-slate-400">Total System AUM</span>
          <div id="admin-kpi-aum" class="text-2xl font-black text-white font-mono-numbers mt-1.5">₦0</div>
          <div class="text-[11px] text-brand-400 mt-1 font-semibold">Active Capital Pool</div>
        </div>

        <div class="glass-panel rounded-2xl p-5 border border-white/10">
          <span class="text-xs font-semibold text-slate-400">Pending Queue</span>
          <div id="admin-kpi-pending" class="text-2xl font-black text-amber-400 font-mono-numbers mt-1.5">0</div>
          <div class="text-[11px] text-slate-400 mt-1">Needs verification</div>
        </div>

        <div class="glass-panel rounded-2xl p-5 border border-white/10">
          <span class="text-xs font-semibold text-slate-400">Verified Investors</span>
          <div id="admin-kpi-investors" class="text-2xl font-black text-white font-mono-numbers mt-1.5">4</div>
          <div class="text-[11px] text-brand-400 mt-1">100% KYC Compliant</div>
        </div>

        <div class="glass-panel rounded-2xl p-5 border border-white/10">
          <span class="text-xs font-semibold text-slate-400">Reserve Liquid Buffer</span>
          <div class="text-2xl font-black text-emerald-400 font-mono-numbers mt-1.5">₦340,000,000</div>
          <div class="text-[11px] text-slate-400 mt-1">Zenith Bank Escrow</div>
        </div>
      </div>

      <!-- Pending Approval Queue -->
      <div class="glass-panel rounded-3xl p-6 border border-white/10">
        <div class="flex justify-between items-center mb-5">
          <div>
            <h3 class="text-lg font-bold text-white">Pending Requests Queue</h3>
            <p class="text-xs text-slate-400">Confirm deposit proofs or authorize withdrawal clearances.</p>
          </div>
          <span id="admin-queue-count-badge" class="text-xs font-bold px-3 py-1 rounded-full bg-amber-500/20 text-amber-300 border border-amber-500/30">
            0 Action Required
          </span>
        </div>

        <div class="overflow-x-auto">
          <table class="w-full text-left text-xs">
            <thead class="text-slate-400 uppercase tracking-wider border-b border-white/10 bg-white/5 font-semibold">
              <tr>
                <th class="py-3 px-4">Ticket</th>
                <th class="py-3 px-4">Investor</th>
                <th class="py-3 px-4">Action</th>
                <th class="py-3 px-4">Amount</th>
                <th class="py-3 px-4">Reference / Bank Details</th>
                <th class="py-3 px-4 text-center">Manage</th>
              </tr>
            </thead>
            <tbody id="admin-queue-tbody" class="divide-y divide-white/5 text-slate-300">
              <!-- Populated by JavaScript -->
            </tbody>
          </table>
        </div>
      </div>

      <!-- Investor Registry -->
      <div class="glass-panel rounded-3xl p-6 border border-white/10">
        <div class="flex justify-between items-center mb-5">
          <div>
            <h3 class="text-lg font-bold text-white">Investor Accounts Registry</h3>
            <p class="text-xs text-slate-400">All registered portfolio members.</p>
          </div>
        </div>

        <div class="overflow-x-auto">
          <table class="w-full text-left text-xs">
            <thead class="text-slate-400 uppercase tracking-wider border-b border-white/10 bg-white/5 font-semibold">
              <tr>
                <th class="py-3 px-4">Full Name</th>
                <th class="py-3 px-4">Telephone</th>
                <th class="py-3 px-4">Capital Allocated</th>
                <th class="py-3 px-4">KYC State</th>
                <th class="py-3 px-4 text-center">Direct Call</th>
              </tr>
            </thead>
            <tbody id="admin-investors-tbody" class="divide-y divide-white/5 text-slate-300">
              <!-- Populated by JavaScript -->
            </tbody>
          </table>
        </div>
      </div>

    </section>

  </main>

  <!-- ================= MODALS ================= -->

  <!-- MODAL: Deposit Funds -->
  <div id="depositModal" class="fixed inset-0 z-50 hidden bg-black/80 backdrop-blur-sm flex items-center justify-center p-4">
    <div class="glass-panel bg-navy-900 border border-white/10 rounded-3xl max-w-lg w-full p-6 sm:p-8 relative">
      <button onclick="closeModal('depositModal')" class="absolute top-5 right-5 text-slate-400 hover:text-white text-lg">
        <i class="fa-solid fa-xmark"></i>
      </button>

      <h3 class="text-xl font-bold text-white mb-1">Deposit Funds to EmmyGrowth</h3>
      <p class="text-xs text-slate-400 mb-4">Transfer directly to the custody account below and submit your reference.</p>

      <!-- Bank Details Box -->
      <div class="p-4 rounded-2xl bg-navy-950 border border-brand-500/30 space-y-2 mb-4 font-mono text-xs">
        <div class="flex justify-between"><span class="text-slate-400">Bank:</span> <span class="text-white font-bold">Zenith Bank Plc</span></div>
        <div class="flex justify-between"><span class="text-slate-400">Account Name:</span> <span class="text-white font-bold">EmmyGrowth Syndicate Ltd</span></div>
        <div class="flex justify-between items-center pt-1 border-t border-white/5">
          <span class="text-slate-400">Account Number:</span>
          <span class="text-brand-400 font-bold text-sm tracking-wider">1029384756</span>
        </div>
      </div>

      <form onsubmit="handleDepositSubmit(event)" class="space-y-4 text-xs">
        <div>
          <label class="block text-slate-300 font-semibold mb-1">Deposit Amount (₦)</label>
          <input type="number" id="depositAmountInput" min="10000" placeholder="e.g. 200000" required class="w-full bg-navy-950 border border-white/10 rounded-xl px-4 py-3 text-sm text-white focus:outline-none focus:border-brand-500 font-mono">
        </div>
        <div>
          <label class="block text-slate-300 font-semibold mb-1">Sending Bank & Account Name</label>
          <input type="text" id="depositSenderInput" placeholder="e.g. GTBank - Emmanuel Okonkwo" required class="w-full bg-navy-950 border border-white/10 rounded-xl px-4 py-3 text-sm text-white focus:outline-none focus:border-brand-500">
        </div>
        <div>
          <label class="block text-slate-300 font-semibold mb-1">Transfer Reference / Session ID</label>
          <input type="text" id="depositRefInput" placeholder="e.g. 09029384729103" class="w-full bg-navy-950 border border-white/10 rounded-xl px-4 py-3 text-sm text-white focus:outline-none focus:border-brand-500 font-mono">
        </div>

        <div class="p-3 rounded-xl bg-white/5 text-[11px] text-slate-400 flex items-center justify-between">
          <span>Need priority receipt clearance?</span>
          <a href="tel:+2349070653906" class="text-brand-400 font-bold hover:underline">+234 907 065 3906</a>
        </div>

        <button type="submit" class="w-full py-3.5 rounded-xl font-bold text-xs bg-brand-500 hover:bg-brand-400 text-navy-950 transition shadow-lg shadow-brand-500/20">
          Submit Deposit Proof to Queue
        </button>
      </form>
    </div>
  </div>

  <!-- MODAL: Withdraw Funds -->
  <div id="withdrawModal" class="fixed inset-0 z-50 hidden bg-black/80 backdrop-blur-sm flex items-center justify-center p-4">
    <div class="glass-panel bg-navy-900 border border-white/10 rounded-3xl max-w-md w-full p-6 sm:p-8 relative">
      <button onclick="closeModal('withdrawModal')" class="absolute top-5 right-5 text-slate-400 hover:text-white text-lg">
        <i class="fa-solid fa-xmark"></i>
      </button>

      <h3 class="text-xl font-bold text-white mb-1">Request Capital Payout</h3>
      <p class="text-xs text-slate-400 mb-4">Transfer liquid wallet funds to your registered bank account.</p>

      <div class="p-3 rounded-xl bg-white/5 border border-white/10 text-xs flex justify-between items-center mb-4">
        <span class="text-slate-400">Available Balance:</span>
        <span id="withdrawModalBalance" class="font-bold text-brand-400 text-sm font-mono-numbers">₦0</span>
      </div>

      <form onsubmit="handleWithdrawSubmit(event)" class="space-y-4 text-xs">
        <div>
          <label class="block text-slate-300 font-semibold mb-1">Amount to Withdraw (₦)</label>
          <input type="number" id="withdrawAmountInput" min="5000" placeholder="e.g. 50000" required class="w-full bg-navy-950 border border-white/10 rounded-xl px-4 py-3 text-sm text-white focus:outline-none focus:border-brand-500 font-mono">
        </div>
        <div>
          <label class="block text-slate-300 font-semibold mb-1">Destination Bank & Account</label>
          <input type="text" id="withdrawAccountInput" value="Access Bank — 0029381729 (Emmanuel O.)" required class="w-full bg-navy-950 border border-white/10 rounded-xl px-4 py-3 text-sm text-white focus:outline-none focus:border-brand-500">
        </div>

        <button type="submit" class="w-full py-3.5 rounded-xl font-bold text-xs bg-brand-500 hover:bg-brand-400 text-navy-950 transition">
          Confirm Withdrawal Request
        </button>
      </form>
    </div>
  </div>

  <!-- MODAL: Open New Plan / Allocation -->
  <div id="newPlanModal" class="fixed inset-0 z-50 hidden bg-black/80 backdrop-blur-sm flex items-center justify-center p-4">
    <div class="glass-panel bg-navy-900 border border-white/10 rounded-3xl max-w-md w-full p-6 sm:p-8 relative">
      <button onclick="closeModal('newPlanModal')" class="absolute top-5 right-5 text-slate-400 hover:text-white text-lg">
        <i class="fa-solid fa-xmark"></i>
      </button>

      <h3 class="text-xl font-bold text-white mb-1">Subscribe Investment Contract</h3>
      <p class="text-xs text-slate-400 mb-4">Deploy wallet funds to initiate an automated cycle.</p>

      <form onsubmit="handleNewPlanSubmit(event)" class="space-y-4 text-xs">
        <div>
          <label class="block text-slate-300 font-semibold mb-1">Select Investment Plan</label>
          <select id="planSelectBox" onchange="syncPlanMinNotice()" class="w-full bg-navy-950 border border-white/10 rounded-xl px-4 py-3 text-sm text-white focus:outline-none focus:border-brand-500">
            <option value="Starter Seed" data-rate="14" data-months="3" data-min="50000">Starter Seed (3 Months @ 14%)</option>
            <option value="Growth Syndicate" data-rate="30" data-months="6" data-min="250000" selected>Growth Syndicate (6 Months @ 30%)</option>
            <option value="Institutional Whale" data-rate="60" data-months="12" data-min="1000000">Institutional Whale (12 Months @ 60%)</option>
          </select>
        </div>

        <div>
          <label class="block text-slate-300 font-semibold mb-1">Investment Amount (₦)</label>
          <input type="number" id="planAmountInput" min="50000" value="250000" required class="w-full bg-navy-950 border border-white/10 rounded-xl px-4 py-3 text-sm text-white focus:outline-none focus:border-brand-500 font-mono">
          <p id="planMinNotice" class="text-[11px] text-brand-400 mt-1 font-semibold">Minimum tier requirement: ₦250,000</p>
        </div>

        <div class="p-3.5 rounded-xl bg-white/5 border border-white/10 space-y-1.5 text-xs">
          <div class="flex justify-between"><span class="text-slate-400">Available Wallet:</span> <span id="planModalWallet" class="text-white font-bold font-mono">₦0</span></div>
          <div class="flex justify-between"><span class="text-slate-400">Maturity Return Rate:</span> <span id="planModalRate" class="text-brand-400 font-bold">30% Fixed</span></div>
        </div>

        <button type="submit" class="w-full py-3.5 rounded-xl font-bold text-xs bg-brand-500 hover:bg-brand-400 text-navy-950 transition">
          Confirm Contract Lock-in
        </button>
      </form>
    </div>
  </div>

  <!-- MODAL: Customer Care Support -->
  <div id="supportModal" class="fixed inset-0 z-50 hidden bg-black/80 backdrop-blur-sm flex items-center justify-center p-4">
    <div class="glass-panel bg-navy-900 border border-white/10 rounded-3xl max-w-md w-full p-6 sm:p-8 relative text-center">
      <button onclick="closeModal('supportModal')" class="absolute top-5 right-5 text-slate-400 hover:text-white text-lg">
        <i class="fa-solid fa-xmark"></i>
      </button>

      <div class="w-14 h-14 rounded-2xl bg-brand-500/20 text-brand-400 flex items-center justify-center text-2xl mx-auto mb-3 border border-brand-500/30">
        <i class="fa-solid fa-headset"></i>
      </div>
      <h3 class="text-xl font-extrabold text-white">EmmyGrowth Customer Care</h3>
      <p class="text-xs text-slate-400 mt-1 mb-6">Our dedicated desk is active 24/7 to resolve queries, manual deposit verifications, and VIP onboarding.</p>

      <div class="space-y-3">
        <a href="tel:+2349070653906" class="w-full py-3.5 px-4 rounded-xl bg-brand-500 hover:bg-brand-400 text-navy-950 font-bold text-xs transition flex items-center justify-center gap-2">
          <i class="fa-solid fa-phone"></i> Call Direct: +234 907 065 3906
        </a>
        <a href="https://wa.me/2349070653906?text=Hello%20EmmyGrowth%20Customer%20Desk,%20I%20need%20assistance%20with%20my%20account." target="_blank" class="w-full py-3.5 px-4 rounded-xl bg-emerald-600/30 hover:bg-emerald-600/50 border border-emerald-500/40 text-emerald-300 font-bold text-xs transition flex items-center justify-center gap-2">
          <i class="fa-brands fa-whatsapp text-base"></i> Message on WhatsApp
        </a>
      </div>

      <div class="mt-6 pt-4 border-t border-white/5 text-[11px] text-slate-400">
        RC: 3892014 • Victoria Island, Lagos, Nigeria.
      </div>
    </div>
  </div>

  <!-- MODAL: Install / Download App -->
  <div id="pwaModal" class="fixed inset-0 z-50 hidden bg-black/80 backdrop-blur-sm flex items-center justify-center p-4">
    <div class="glass-panel bg-navy-900 border border-white/10 rounded-3xl max-w-md w-full p-6 sm:p-8 relative">
      <button onclick="closeModal('pwaModal')" class="absolute top-5 right-5 text-slate-400 hover:text-white text-lg">
        <i class="fa-solid fa-xmark"></i>
      </button>

      <div class="w-12 h-12 rounded-2xl bg-brand-500/20 text-brand-400 flex items-center justify-center text-xl mx-auto mb-3">
        <i class="fa-solid fa-mobile-screen"></i>
      </div>
      <h3 class="text-xl font-bold text-white text-center mb-1">Install EmmyGrowth App</h3>
      <p class="text-xs text-slate-400 text-center mb-5">Access your portfolio directly from your phone's home screen or download the standalone app file.</p>

      <div class="space-y-3 text-xs text-slate-300">
        <div class="p-3.5 rounded-xl bg-white/5 border border-white/5">
          <strong class="text-white block mb-1"><i class="fa-brands fa-apple mr-1 text-slate-400"></i> iPhone / iPad (Safari):</strong>
          1. Tap the <strong>Share</strong> button <i class="fa-solid fa-arrow-up-from-bracket mx-1 text-brand-400"></i> in Safari.<br>
          2. Scroll down and choose <strong>"Add to Home Screen"</strong>.
        </div>
        <div class="p-3.5 rounded-xl bg-white/5 border border-white/5">
          <strong class="text-white block mb-1"><i class="fa-brands fa-android mr-1 text-emerald-400"></i> Android (Chrome):</strong>
          1. Tap the <strong>three dots menu (⋮)</strong>.<br>
          2. Tap <strong>"Install app"</strong> or <strong>"Add to Home screen"</strong>.
        </div>
      </div>

      <div class="mt-5 flex gap-2">
        <button id="pwaTriggerNativeBtn" onclick="executeNativeInstall()" class="flex-1 py-3 rounded-xl bg-brand-500 hover:bg-brand-400 text-navy-950 font-bold text-xs transition">
          Install PWA
        </button>
        <button onclick="exportSingleFileSource()" class="flex-1 py-3 rounded-xl bg-white/10 hover:bg-white/15 text-white font-bold text-xs border border-white/10 transition">
          Download File (.html)
        </button>
      </div>
    </div>
  </div>

  <!-- Toast Feedbacks -->
  <div id="toastStack" class="fixed top-5 right-5 z-50 space-y-2 pointer-events-none max-w-sm w-full"></div>

  <!-- Floating Customer Care Button -->
  <div class="fixed bottom-6 right-6 z-40 flex items-center space-x-2">
    <a href="https://wa.me/2349070653906?text=Hello%20EmmyGrowth,%20I%20need%20assistance." target="_blank" class="w-12 h-12 rounded-full bg-emerald-600 hover:bg-emerald-500 text-white flex items-center justify-center shadow-xl shadow-emerald-600/30 transition transform hover:scale-105" title="WhatsApp Customer Desk">
      <i class="fa-brands fa-whatsapp text-2xl"></i>
    </a>
    <a href="tel:+2349070653906" class="h-12 px-4 rounded-full bg-brand-500 hover:bg-brand-400 text-navy-950 font-extrabold flex items-center gap-2 shadow-xl shadow-brand-500/30 transition transform hover:scale-105 text-xs" title="Call Customer Care Hotline">
      <i class="fa-solid fa-headset text-base"></i>
      <span class="hidden sm:inline">+234 907 065 3906</span>
    </a>
  </div>

  <!-- ================= JAVASCRIPT STATE ENGINE ================= -->
  <script>
    const STORAGE_KEY = 'EMMYGROWTH_DATA_V1';

    // Default Initial State
    const DEFAULT_DATA = {
      user: {
        id: 'EMG-9034',
        name: 'Chief Emmanuel',
        phone: '+234 907 065 3906',
        walletBalance: 125000,
        totalInvested: 750000,
        accruedYield: 142500,
        plans: [
          {
            id: 'INV-3021',
            name: 'Growth Syndicate',
            principal: 500000,
            rate: 30,
            months: 6,
            daysLeft: 78,
            progressPct: 62,
            targetReturn: 150000
          },
          {
            id: 'INV-2980',
            name: 'Starter Seed',
            principal: 250000,
            rate: 14,
            months: 3,
            daysLeft: 22,
            progressPct: 75,
            targetReturn: 35000
          }
        ],
        transactions: [
          { ref: 'TX-9901', type: 'Yield Credited', desc: 'Quarterly Cycle Yield (INV-2980)', amount: '+₦35,000', date: 'Oct 10, 2026', status: 'Confirmed' },
          { ref: 'TX-9844', type: 'Deposit', desc: 'Direct Transfer - Zenith Bank', amount: '+₦150,000', date: 'Sep 29, 2026', status: 'Confirmed' },
          { ref: 'TX-9781', type: 'Withdrawal', desc: 'Settlement to Access Bank (0029381729)', amount: '-₦60,000', date: 'Sep 12, 2026', status: 'Confirmed' }
        ]
      },
      admin: {
        aum: 1850750000,
        pendingQueue: [
          {
            ticket: 'REQ-502',
            user: 'Alhaji Sanusi B.',
            phone: '+234 802 334 1180',
            type: 'Deposit',
            amount: 500000,
            ref: 'ZEN-NIP-9923812 (First Bank)',
            time: '25 mins ago'
          }
        ],
        investors: [
          { name: 'Chief Emmanuel', phone: '+234 907 065 3906', invested: 750000, kyc: 'Verified' },
          { name: 'Alhaji Sanusi B.', phone: '+234 802 334 1180', invested: 2500000, kyc: 'Verified' },
          { name: 'Dr. Folashade Adeleke', phone: '+234 813 552 9012', invested: 10000000, kyc: 'Verified' },
          { name: 'Kelvin Obi', phone: '+234 705 441 2291', invested: 300000, kyc: 'Verified' }
        ]
      },
      calc: {
        principal: 500000,
        rate: 30,
        months: 6
      }
    };

    // Load State from localStorage
    function loadState() {
      try {
        const stored = localStorage.getItem(STORAGE_KEY);
        if (stored) {
          return JSON.parse(stored);
        }
      } catch (e) {
        console.error('Error loading state from localStorage:', e);
      }
      return JSON.parse(JSON.stringify(DEFAULT_DATA));
    }

    // Save State to localStorage
    function saveState() {
      try {
        localStorage.setItem(STORAGE_KEY, JSON.stringify(STATE));
      } catch (e) {
        console.error('Error saving state:', e);
      }
    }

    const STATE = loadState();

    // Currency Formatter
    function formatNaira(num) {
      return '₦' + Number(num).toLocaleString('en-NG');
    }

    // Tab Switcher
    function switchTab(tabKey) {
      const views = ['public', 'user', 'admin'];
      views.forEach(v => {
        const el = document.getElementById(`view-${v}`);
        const pill = document.getElementById(`pill-${v}`);
        if (el) el.classList.add('hidden');
        if (pill) {
          pill.classList.remove('bg-white/10', 'text-white');
          pill.classList.add('text-slate-400');
        }
      });

      const activeView = document.getElementById(`view-${tabKey}`);
      const activePill = document.getElementById(`pill-${tabKey}`);
      if (activeView) activeView.classList.remove('hidden');
      if (activePill) {
        activePill.classList.remove('text-slate-400');
        activePill.classList.add('bg-white/10', 'text-white');
      }

      window.scrollTo({ top: 0, behavior: 'smooth' });
    }

    function toggleMobileNav() {
      const drawer = document.getElementById('mobileDrawer');
      drawer.classList.toggle('hidden');
    }

    // Modal Handlers
    function openModal(id) {
      const m = document.getElementById(id);
      if (m) m.classList.remove('hidden');
    }

    function closeModal(id) {
      const m = document.getElementById(id);
      if (m) m.classList.add('hidden');
    }

    // Calculator Functions
    function setCalcTenor(months, rate) {
      STATE.calc.months = months;
      STATE.calc.rate = rate;

      [3, 6, 12].forEach(m => {
        const b = document.getElementById(`calc-btn-${m}`);
        if (b) {
          if (m === months) {
            b.className = 'calc-tenor py-3 px-2 rounded-xl text-xs font-bold border border-brand-500 bg-brand-500/20 text-brand-300 transition';
          } else {
            b.className = 'calc-tenor py-3 px-2 rounded-xl text-xs font-bold border border-white/10 bg-white/5 hover:border-brand-500/40 transition';
          }
        }
      });

      runCalculator();
    }

    function runCalculator() {
      const slider = document.getElementById('calc-slider');
      const principal = Number(slider.value);
      STATE.calc.principal = principal;

      const rate = STATE.calc.rate;
      const profit = (principal * rate) / 100;
      const total = principal + profit;

      document.getElementById('calc-display-amount').innerText = formatNaira(principal);
      document.getElementById('calc-sum-principal').innerText = formatNaira(principal);
      document.getElementById('calc-sum-rate').innerText = `${rate}%`;
      document.getElementById('calc-sum-profit').innerText = `+${formatNaira(profit)}`;
      document.getElementById('calc-sum-total').innerText = formatNaira(total);
    }

    function subscribeCalculatedPlan() {
      switchTab('user');
      openModal('newPlanModal');

      const select = document.getElementById('planSelectBox');
      if (STATE.calc.months === 3) select.value = 'Starter Seed';
      else if (STATE.calc.months === 6) select.value = 'Growth Syndicate';
      else select.value = 'Institutional Whale';

      document.getElementById('planAmountInput').value = STATE.calc.principal;
      syncPlanMinNotice();
      triggerToast('Calculated allocation values loaded. Ready to invest.', 'info');
    }

    function quickInvest(planName, minAmount, rate, months) {
      switchTab('user');
      openModal('newPlanModal');
      const select = document.getElementById('planSelectBox');
      select.value = planName;
      document.getElementById('planAmountInput').value = minAmount;
      syncPlanMinNotice();
    }

    function syncPlanMinNotice() {
      const select = document.getElementById('planSelectBox');
      const option = select.options[select.selectedIndex];
      const min = option.getAttribute('data-min');
      const rate = option.getAttribute('data-rate');
      
      document.getElementById('planMinNotice').innerText = `Minimum tier requirement: ${formatNaira(min)}`;
      document.getElementById('planModalRate').innerText = `${rate}% Fixed`;
    }

    // Render User Portal
    function renderUserScreen() {
      document.getElementById('user-kpi-invested').innerText = formatNaira(STATE.user.totalInvested);
      document.getElementById('user-kpi-yield').innerText = formatNaira(STATE.user.accruedYield);
      document.getElementById('user-kpi-balance').innerText = formatNaira(STATE.user.walletBalance);
      document.getElementById('withdrawModalBalance').innerText = formatNaira(STATE.user.walletBalance);
      document.getElementById('planModalWallet').innerText = formatNaira(STATE.user.walletBalance);
      document.getElementById('user-kpi-plan-count').innerText = `${STATE.user.plans.length} Active Contracts`;

      // Render Active Contracts
      const plansContainer = document.getElementById('user-plans-list');
      plansContainer.innerHTML = '';
      if (STATE.user.plans.length === 0) {
        plansContainer.innerHTML = `<div class="p-6 text-center text-xs text-slate-400 bg-white/5 rounded-2xl">No active contracts. Click "+ New Contract" to allocate capital.</div>`;
      } else {
        STATE.user.plans.forEach(plan => {
          const div = document.createElement('div');
          div.className = 'p-4 rounded-2xl bg-white/5 border border-white/5 hover:border-brand-500/20 transition';
          div.innerHTML = `
            <div class="flex flex-col sm:flex-row justify-between sm:items-center gap-2 mb-2.5">
              <div>
                <div class="flex items-center gap-2">
                  <span class="text-white font-bold text-sm">${plan.name}</span>
                  <span class="text-[10px] font-mono px-2 py-0.5 rounded bg-brand-500/20 text-brand-300 font-bold">${plan.id}</span>
                </div>
                <span class="text-[11px] text-slate-400 font-semibold">${plan.daysLeft} days to maturity • ${plan.months} Months Tenor</span>
              </div>
              <div class="sm:text-right">
                <span class="text-[11px] text-slate-400">Principal:</span>
                <span class="text-base font-extrabold text-white font-mono-numbers block">${formatNaira(plan.principal)}</span>
              </div>
            </div>
            <div class="space-y-1">
              <div class="flex justify-between text-[11px]">
                <span class="text-slate-400">Cycle Progress</span>
                <span class="text-brand-400 font-bold font-mono-numbers">${plan.progressPct}% (+${formatNaira(plan.targetReturn)} Target Yield)</span>
              </div>
              <div class="w-full h-1.5 rounded-full bg-navy-950 overflow-hidden">
                <div class="h-full bg-gradient-to-r from-brand-600 to-brand-400 rounded-full" style="width: ${plan.progressPct}%"></div>
              </div>
            </div>
          `;
          plansContainer.appendChild(div);
        });
      }

      // Render Transaction Ledger
      const ledgerTbody = document.getElementById('user-ledger-tbody');
      ledgerTbody.innerHTML = '';
      if (STATE.user.transactions.length === 0) {
        ledgerTbody.innerHTML = `<tr><td colspan="6" class="py-5 text-center text-slate-500">No transactions recorded yet.</td></tr>`;
      } else {
        STATE.user.transactions.forEach(tx => {
          const row = document.createElement('tr');
          row.className = 'hover:bg-white/5 transition';
          row.innerHTML = `
            <td class="py-3 px-4 font-mono font-bold text-brand-400">${tx.ref}</td>
            <td class="py-3 px-4"><span class="px-2 py-0.5 rounded text-[10px] font-bold bg-white/10 text-slate-300">${tx.type}</span></td>
            <td class="py-3 px-4 text-slate-300">${tx.desc}</td>
            <td class="py-3 px-4 font-bold font-mono-numbers ${tx.amount.startsWith('+') ? 'text-brand-400' : 'text-slate-200'}">${tx.amount}</td>
            <td class="py-3 px-4 text-slate-400">${tx.date}</td>
            <td class="py-3 px-4"><span class="text-emerald-400 font-semibold"><i class="fa-solid fa-check text-[9px] mr-1"></i>${tx.status}</span></td>
          `;
          ledgerTbody.appendChild(row);
        });
      }
    }

    // Render Admin Console
    function renderAdminScreen() {
      document.getElementById('admin-kpi-aum').innerText = formatNaira(STATE.admin.aum);
      document.getElementById('admin-kpi-pending').innerText = `${STATE.admin.pendingQueue.length} Ticket(s)`;
      document.getElementById('admin-queue-count-badge').innerText = `${STATE.admin.pendingQueue.length} Action(s) Required`;
      document.getElementById('admin-kpi-investors').innerText = `${STATE.admin.investors.length} Co-Partners`;

      // Pending Queue Table
      const queueTbody = document.getElementById('admin-queue-tbody');
      queueTbody.innerHTML = '';
      if (STATE.admin.pendingQueue.length === 0) {
        queueTbody.innerHTML = `<tr><td colspan="6" class="py-6 text-center text-slate-500">All submissions cleared. Verification queue is empty.</td></tr>`;
      } else {
        STATE.admin.pendingQueue.forEach((item, index) => {
          const row = document.createElement('tr');
          row.className = 'hover:bg-white/5 transition';
          row.innerHTML = `
            <td class="py-3 px-4 font-mono font-bold text-amber-400">${item.ticket}</td>
            <td class="py-3 px-4 font-bold text-white">${item.user}<span class="block text-[10px] text-slate-400 font-mono">${item.phone}</span></td>
            <td class="py-3 px-4"><span class="px-2 py-0.5 rounded text-[10px] font-bold ${item.type === 'Deposit' ? 'bg-emerald-500/20 text-emerald-300' : 'bg-blue-500/20 text-blue-300'}">${item.type}</span></td>
            <td class="py-3 px-4 font-bold text-white font-mono-numbers">${formatNaira(item.amount)}</td>
            <td class="py-3 px-4 text-slate-300 font-mono text-[11px]">${item.ref}</td>
            <td class="py-3 px-4 text-center">
              <div class="flex items-center justify-center gap-1.5">
                <button onclick="approveQueueItem(${index})" class="px-2.5 py-1 bg-brand-500 hover:bg-brand-400 text-navy-950 font-bold rounded-lg text-[11px] transition">Approve</button>
                <button onclick="rejectQueueItem(${index})" class="px-2.5 py-1 bg-rose-500/20 text-rose-300 hover:bg-rose-500/30 rounded-lg text-[11px] transition">Decline</button>
              </div>
            </td>
          `;
          queueTbody.appendChild(row);
        });
      }

      // Investors Registry Table
      const invTbody = document.getElementById('admin-investors-tbody');
      invTbody.innerHTML = '';
      STATE.admin.investors.forEach(inv => {
        const row = document.createElement('tr');
        row.className = 'hover:bg-white/5 transition';
        row.innerHTML = `
          <td class="py-3 px-4 font-bold text-white">${inv.name}</td>
          <td class="py-3 px-4 font-mono text-slate-300"><a href="tel:${inv.phone}" class="hover:text-brand-400">${inv.phone}</a></td>
          <td class="py-3 px-4 font-bold text-brand-400 font-mono-numbers">${formatNaira(inv.invested)}</td>
          <td class="py-3 px-4"><span class="px-2 py-0.5 rounded bg-emerald-500/20 text-emerald-400 font-semibold">${inv.kyc}</span></td>
          <td class="py-3 px-4 text-center">
            <a href="tel:${inv.phone}" class="text-brand-400 hover:text-brand-300 p-1" title="Call Investor"><i class="fa-solid fa-phone"></i></a>
          </td>
        `;
        invTbody.appendChild(row);
      });
    }

    // Handlers
    function handleDepositSubmit(e) {
      e.preventDefault();
      const amount = Number(document.getElementById('depositAmountInput').value);
      const sender = document.getElementById('depositSenderInput').value;
      const ref = document.getElementById('depositRefInput').value || `MAN-${Math.floor(100000 + Math.random() * 900000)}`;

      if (amount <= 0) return;

      const ticketId = `DEP-${Math.floor(600 + Math.random() * 300)}`;

      STATE.admin.pendingQueue.push({
        ticket: ticketId,
        user: STATE.user.name,
        phone: STATE.user.phone,
        type: 'Deposit',
        amount: amount,
        ref: `${ref} (${sender})`,
        time: 'Just now'
      });

      saveState();
      closeModal('depositModal');
      renderAdminScreen();
      triggerToast(`Deposit of ${formatNaira(amount)} queued for admin clearance! Check "Admin Console" to verify.`);
    }

    function approveQueueItem(index) {
      const item = STATE.admin.pendingQueue[index];
      if (!item) return;

      if (item.type === 'Deposit') {
        STATE.user.walletBalance += item.amount;
        STATE.admin.aum += item.amount;
        STATE.user.transactions.unshift({
          ref: item.ticket,
          type: 'Deposit',
          desc: `Approved Deposit Ref: ${item.ref}`,
          amount: `+${formatNaira(item.amount)}`,
          date: 'Oct 14, 2026',
          status: 'Confirmed'
        });
      } else if (item.type === 'Withdrawal') {
        STATE.admin.aum -= item.amount;
        STATE.user.transactions.unshift({
          ref: item.ticket,
          type: 'Withdrawal',
          desc: `Disbursed to ${item.ref}`,
          amount: `-${formatNaira(item.amount)}`,
          date: 'Oct 14, 2026',
          status: 'Paid Out'
        });
      }

      STATE.admin.pendingQueue.splice(index, 1);
      saveState();
      renderUserScreen();
      renderAdminScreen();
      triggerToast(`Ticket ${item.ticket} approved successfully!`);
    }

    function rejectQueueItem(index) {
      const item = STATE.admin.pendingQueue[index];
      if (item && item.type === 'Withdrawal') {
        // Refund back to user's wallet if withdrawal was rejected
        STATE.user.walletBalance += item.amount;
      }
      STATE.admin.pendingQueue.splice(index, 1);
      saveState();
      renderUserScreen();
      renderAdminScreen();
      triggerToast(`Ticket ${item ? item.ticket : ''} was declined.`, 'warning');
    }

    function handleWithdrawSubmit(e) {
      e.preventDefault();
      const amount = Number(document.getElementById('withdrawAmountInput').value);
      const destination = document.getElementById('withdrawAccountInput').value;

      if (amount > STATE.user.walletBalance) {
        triggerToast(`Insufficient liquid wallet balance (${formatNaira(STATE.user.walletBalance)} available).`, 'error');
        return;
      }

      STATE.user.walletBalance -= amount;

      const ticketId = `WD-${Math.floor(1000 + Math.random() * 9000)}`;

      STATE.admin.pendingQueue.push({
        ticket: ticketId,
        user: STATE.user.name,
        phone: STATE.user.phone,
        type: 'Withdrawal',
        amount: amount,
        ref: destination,
        time: 'Just now'
      });

      saveState();
      closeModal('withdrawModal');
      renderUserScreen();
      renderAdminScreen();
      triggerToast(`Withdrawal of ${formatNaira(amount)} queued for disbursal authorization.`);
    }

    function handleNewPlanSubmit(e) {
      e.preventDefault();
      const select = document.getElementById('planSelectBox');
      const planName = select.value;
      const option = select.options[select.selectedIndex];
      const min = Number(option.getAttribute('data-min'));
      const rate = Number(option.getAttribute('data-rate'));
      const months = Number(option.getAttribute('data-months'));
      const amount = Number(document.getElementById('planAmountInput').value);

      if (amount < min) {
        triggerToast(`Minimum allocation for ${planName} is ${formatNaira(min)}.`, 'warning');
        return;
      }

      if (amount > STATE.user.walletBalance) {
        triggerToast(`Insufficient wallet funds (${formatNaira(STATE.user.walletBalance)}). Please deposit funds or call +234 907 065 3906.`, 'warning');
        return;
      }

      STATE.user.walletBalance -= amount;
      STATE.user.totalInvested += amount;
      const targetReturn = (amount * rate) / 100;

      STATE.user.plans.unshift({
        id: `INV-${Math.floor(3200 + Math.random() * 800)}`,
        name: planName,
        principal: amount,
        rate: rate,
        months: months,
        daysLeft: months * 30,
        progressPct: 5,
        targetReturn: targetReturn
      });

      STATE.user.transactions.unshift({
        ref: `PLN-${Math.floor(100 + Math.random() * 900)}`,
        type: 'Plan Allocation',
        desc: `Subscribed to ${planName} (${months} Months)`,
        amount: `-${formatNaira(amount)}`,
        date: 'Oct 14, 2026',
        status: 'Confirmed'
      });

      saveState();
      closeModal('newPlanModal');
      renderUserScreen();
      triggerToast(`🎉 Subscription to ${planName} confirmed! Contract active.`);
    }

    function promptBroadcast() {
      const msg = prompt('Enter syndicate broadcast announcement for all investors:');
      if (msg) triggerToast(`Broadcast sent to ${STATE.admin.investors.length} registered investors: "${msg}"`);
    }

    // Toast Feedback System
    function triggerToast(text, type = 'success') {
      const stack = document.getElementById('toastStack');
      const toast = document.createElement('div');
      
      let border = 'border-brand-500/40 bg-navy-900/95 text-white';
      let icon = 'fa-circle-check text-brand-400';
      if (type === 'warning') {
        border = 'border-amber-500/40 bg-navy-900/95 text-white';
        icon = 'fa-triangle-exclamation text-amber-400';
      } else if (type === 'error') {
        border = 'border-rose-500/40 bg-navy-900/95 text-white';
        icon = 'fa-circle-xmark text-rose-400';
      } else if (type === 'info') {
        border = 'border-blue-500/40 bg-navy-900/95 text-white';
        icon = 'fa-circle-info text-blue-400';
      }

      toast.className = `p-4 rounded-2xl border ${border} shadow-2xl flex items-center gap-3 text-xs font-semibold pointer-events-auto transform transition-all duration-300 translate-y-2 opacity-0`;
      toast.innerHTML = `<i class="fa-solid ${icon} text-base"></i> <span>${text}</span>`;
      stack.appendChild(toast);

      setTimeout(() => {
        toast.classList.remove('translate-y-2', 'opacity-0');
      }, 30);

      setTimeout(() => {
        toast.classList.add('opacity-0', '-translate-y-2');
        setTimeout(() => toast.remove(), 400);
      }, 4200);
    }

    // PWA & Export System
    let deferredPrompt = null;

    window.addEventListener('beforeinstallprompt', (e) => {
      e.preventDefault();
      deferredPrompt = e;
      const nativeBtn = document.getElementById('pwaTriggerNativeBtn');
      if (nativeBtn) nativeBtn.classList.remove('hidden');
    });

    function triggerPWAInstall() {
      if (deferredPrompt) {
        deferredPrompt.prompt();
        deferredPrompt.userChoice.then((choiceResult) => {
          if (choiceResult.outcome === 'accepted') {
            triggerToast('EmmyGrowth installed to your home screen!');
          }
          deferredPrompt = null;
        });
      } else {
        openModal('pwaModal');
      }
    }

    function executeNativeInstall() {
      if (deferredPrompt) {
        triggerPWAInstall();
      } else {
        triggerToast('Follow the on-screen instructions for your device browser.', 'info');
      }
    }

    function exportSingleFileSource() {
      const htmlContent = document.documentElement.outerHTML;
      const blob = new Blob([htmlContent], { type: 'text/html;charset=utf-8' });
      const a = document.createElement('a');
      a.href = URL.createObjectURL(blob);
      a.download = 'EmmyGrowth_App.html';
      document.body.appendChild(a);
      a.click();
      document.body.removeChild(a);
      triggerToast('Downloaded standalone EmmyGrowth app file (.html)! You can run it offline on any device.');
    }

    // Initialize application on page load
    window.onload = function() {
      renderUserScreen();
      renderAdminScreen();
      runCalculator();
    };
  </script>
</body>
</html>
```