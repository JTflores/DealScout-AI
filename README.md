<!DOCTYPE html>
<html lang="en" data-theme="dark">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
<meta name="description" content="DealScout AI — Find better prices and smarter alternatives in seconds." />
<title>DealScout AI — Are You Getting the Best Deal?</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700;800;900&display=swap" rel="stylesheet">
<link rel="stylesheet" href="style.css" />
</head>
<body>

<!-- ============ NAVBAR ============ -->
<nav class="navbar">
  <div class="nav-container">
    <a href="#" class="logo" data-go-home>
      <span class="logo-icon">
        <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.2" stroke-linecap="round" stroke-linejoin="round">
          <circle cx="11" cy="11" r="7"></circle>
          <path d="m21 21-4.3-4.3"></path>
          <path d="M8 11h6M11 8v6" opacity=".7"></path>
        </svg>
      </span>
      <span class="logo-text">DealScout <span class="logo-accent">AI</span></span>
    </a>

    <div class="nav-actions">
      <button class="nav-btn" id="historyBtn" title="Search history">
        <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M3 12a9 9 0 1 0 3-6.7L3 8"/><path d="M3 3v5h5"/><path d="M12 7v5l3 2"/></svg>
        <span class="hide-sm">History</span>
      </button>
      <button class="nav-btn" id="favoritesBtn" title="Favorites">
        <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M20.84 4.61a5.5 5.5 0 0 0-7.78 0L12 5.67l-1.06-1.06a5.5 5.5 0 0 0-7.78 7.78l1.06 1.06L12 21.23l7.78-7.78 1.06-1.06a5.5 5.5 0 0 0 0-7.78z"/></svg>
        <span class="hide-sm">Saved</span>
      </button>
      <button class="nav-btn" id="compareBtn" title="Compare">
        <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M8 3H5a2 2 0 0 0-2 2v14a2 2 0 0 0 2 2h3"/><path d="M16 3h3a2 2 0 0 1 2 2v14a2 2 0 0 1-2 2h-3"/><path d="M12 3v18"/></svg>
        <span class="hide-sm">Compare</span>
      </button>
      <button class="nav-btn theme-toggle" id="themeToggle" title="Toggle theme">
        <svg class="icon-sun" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><circle cx="12" cy="12" r="4"/><path d="M12 2v2M12 20v2M4.93 4.93l1.41 1.41M17.66 17.66l1.41 1.41M2 12h2M20 12h2M4.93 19.07l1.41-1.41M17.66 6.34l1.41-1.41"/></svg>
        <svg class="icon-moon" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M21 12.79A9 9 0 1 1 11.21 3 7 7 0 0 0 21 12.79z"/></svg>
      </button>
    </div>
  </div>
</nav>

<!-- ============ HOMEPAGE ============ -->
<section id="home" class="page active">
  <div class="hero">
    <div class="hero-glow"></div>
    <div class="hero-glow hero-glow-2"></div>

    <span class="hero-badge">
      <span class="pulse-dot"></span>
      AI-powered shopping assistant
    </span>

    <h1 class="hero-title">
      Are You Getting the <span class="gradient-text">Best Deal?</span>
    </h1>
    <p class="hero-subtitle">
      Paste a product link or search for a product, and let AI find better prices and alternatives.
    </p>

    <form id="searchForm" class="search-box" autocomplete="off">
      <div class="search-inner">
        <svg class="search-icon" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><circle cx="11" cy="11" r="7"/><path d="m21 21-4.3-4.3"/></svg>
        <input type="text" id="searchInput" placeholder="Enter a product name or paste a product link..." required />
        <button type="submit" class="search-btn">
          <span>Find Better Deals</span>
          <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.2" stroke-linecap="round" stroke-linejoin="round"><path d="M5 12h14M13 5l7 7-7 7"/></svg>
        </button>
      </div>
    </form>

    <div class="example-chips">
      <span class="chip-label">Try:</span>
      <button class="chip" data-query="Wireless headphones">🎧 Wireless headphones</button>
      <button class="chip" data-query="Gaming laptop">💻 Gaming laptop</button>
      <button class="chip" data-query="Smartphone">📱 Smartphone</button>
      <button class="chip" data-query="Running shoes">👟 Running shoes</button>
      <button class="chip" data-query="4K TV">📺 4K TV</button>
      <button class="chip" data-query="Smartwatch">⌚ Smartwatch</button>
    </div>

    <div class="stats-bar">
      <div class="stat"><span class="stat-num">12K+</span><span class="stat-label">Products tracked</span></div>
      <div class="stat"><span class="stat-num">$2.4M</span><span class="stat-label">Saved by users</span></div>
      <div class="stat"><span class="stat-num">98%</span><span class="stat-label">Accuracy score</span></div>
    </div>
  </div>

  <div class="features-grid">
    <div class="feature-card">
      <div class="feature-icon">💰</div>
      <h3>Price Comparison</h3>
      <p>Compare prices across dozens of stores in real time.</p>
    </div>
    <div class="feature-card">
      <div class="feature-icon">🤖</div>
      <h3>AI Recommendations</h3>
      <p>Get smart advice on whether to buy now or wait.</p>
    </div>
    <div class="feature-card">
      <div class="feature-icon">📉</div>
      <h3>Price History</h3>
      <p>See how prices change over time to spot the best moment.</p>
    </div>
    <div class="feature-card">
      <div class="feature-icon">🎯</div>
      <h3>Worth-It Score</h3>
      <p>A single score that tells you if it's a great, fair, or bad deal.</p>
    </div>
  </div>
</section>

<!-- ============ LOADING ============ -->
<section id="loading" class="page">
  <div class="loading-wrap">
    <div class="loader">
      <div class="loader-ring"></div>
      <div class="loader-core">
        <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><circle cx="11" cy="11" r="7"/><path d="m21 21-4.3-4.3"/></svg>
      </div>
    </div>
    <h2 class="loading-title">Analyzing the deal…</h2>
    <p class="loading-step" id="loadingStep">Scanning stores</p>
    <div class="loading-bar"><div class="loading-bar-fill" id="loadingBarFill"></div></div>
  </div>
</section>

<!-- ============ RESULTS ============ -->
<section id="results" class="page">
  <div class="results-container">

    <div class="results-header">
      <button class="back-btn" id="backBtn">
        <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M19 12H5M12 19l-7-7 7-7"/></svg>
        Search another product
      </button>
      <div class="results-actions">
        <button class="icon-btn" id="favToggle" title="Save to favorites">
          <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M20.84 4.61a5.5 5.5 0 0 0-7.78 0L12 5.67l-1.06-1.06a5.5 5.5 0 0 0-7.78 7.78l1.06 1.06L12 21.23l7.78-7.78 1.06-1.06a5.5 5.5 0 0 0 0-7.78z"/></svg>
        </button>
        <button class="icon-btn" id="copyBtn" title="Copy results">
          <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><rect x="9" y="9" width="13" height="13" rx="2"/><path d="M5 15H4a2 2 0 0 1-2-2V4a2 2 0 0 1 2-2h9a2 2 0 0 1 2 2v1"/></svg>
        </button>
        <button class="icon-btn" id="shareBtn" title="Share results">
          <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><circle cx="18" cy="5" r="3"/><circle cx="6" cy="12" r="3"/><circle cx="18" cy="19" r="3"/><path d="m8.59 13.51 6.83 3.98M15.41 6.51l-6.82 3.98"/></svg>
        </button>
        <button class="icon-btn" id="addCompareBtn" title="Add to compare">
          <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M12 5v14M5 12h14"/></svg>
        </button>
      </div>
    </div>

    <!-- 1. Product Overview -->
    <div class="card overview-card">
      <div class="overview-image" id="overviewImage">📦</div>
      <div class="overview-info">
        <div class="overview-store" id="overviewStore">Store</div>
        <h2 class="overview-name" id="overviewName">Product</h2>
        <div class="overview-meta">
          <span class="rating" id="overviewRating">★★★★★ 4.5</span>
          <span class="divider">•</span>
          <span id="overviewCategory">Category</span>
          <span class="divider">•</span>
          <span id="overviewSku">SKU</span>
        </div>
        <div class="overview-price-row">
          <div class="price-main" id="overviewPrice">$0</div>
          <div class="price-change" id="overviewPriceChange">—</div>
        </div>
        <p class="overview-desc" id="overviewDesc">Description</p>
      </div>
    </div>

    <!-- 2. Worth-It Score -->
    <div class="card worth-card">
      <div class="worth-left">
        <div class="worth-label">Worth-It Score</div>
        <div class="worth-score" id="worthScore">0</div>
        <div class="worth-verdict" id="worthVerdict">Analyzing…</div>
      </div>
      <div class="worth-right">
        <div class="worth-ring-wrap">
          <svg class="worth-ring" viewBox="0 0 120 120">
            <circle cx="60" cy="60" r="52" class="ring-bg"/>
            <circle cx="60" cy="60" r="52" class="ring-fg" id="worthRingFg"/>
          </svg>
          <div class="worth-ring-text" id="worthRingText">0</div>
        </div>
        <p class="worth-explain" id="worthExplain">—</p>
      </div>
    </div>

    <!-- 3. Price Comparison -->
    <div class="card">
      <div class="card-head">
        <h3>💰 Price Comparison</h3>
        <span class="card-sub">Across multiple retailers</span>
      </div>
      <div class="price-table" id="priceTable"></div>
    </div>

    <!-- 4. Cheaper Alternatives -->
    <div class="card">
      <div class="card-head">
        <h3>🏷️ Cheaper Alternatives</h3>
        <span class="card-sub">Save more with similar products</span>
      </div>
      <div class="product-grid" id="alternativesGrid"></div>
    </div>

    <!-- 5. Similar Products -->
    <div class="card">
      <div class="card-head">
        <h3>🔍 Similar Products</h3>
        <span class="card-sub">Same category, comparable features</span>
      </div>
      <div class="product-grid" id="similarGrid"></div>
    </div>

    <!-- 6. Pros & Cons -->
    <div class="card proscons-card">
      <div class="pros-col">
        <h3><span class="check-icon">✓</span> Pros</h3>
        <ul id="prosList"></ul>
      </div>
      <div class="cons-col">
        <h3><span class="x-icon">✗</span> Cons</h3>
        <ul id="consList"></ul>
      </div>
    </div>

    <!-- 7. Price History -->
    <div class="card">
      <div class="card-head">
        <h3>📉 Price History <span class="demo-badge">Demo data</span></h3>
        <span class="card-sub">Last 6 months</span>
      </div>
      <div class="price-history-chart">
        <canvas id="priceChart" width="800" height="260"></canvas>
      </div>
      <div class="history-stats">
        <div class="hs"><span class="hs-label">Lowest</span><span class="hs-val" id="histLow">—</span></div>
        <div class="hs"><span class="hs-label">Highest</span><span class="hs-val" id="histHigh">—</span></div>
        <div class="hs"><span class="hs-label">Current</span><span class="hs-val" id="histCur">—</span></div>
        <div class="hs"><span class="hs-label">Best time to buy</span><span class="hs-val" id="histBest">—</span></div>
      </div>
    </div>

    <!-- 8. AI Recommendation -->
    <div class="card recommend-card" id="recommendCard">
      <div class="rec-icon" id="recIcon">💡</div>
      <div class="rec-content">
        <div class="rec-label">Our Recommendation</div>
        <p class="rec-text" id="recText">—</p>
      </div>
    </div>

    <button class="cta-btn" id="searchAnother">🔎 Search Another Product</button>
  </div>
</section>

<!-- ============ MODALS ============ -->
<div class="modal-backdrop" id="modalBackdrop">
  <div class="modal" id="modal">
    <div class="modal-head">
      <h3 id="modalTitle">Modal</h3>
      <button class="icon-btn" id="modalClose" title="Close">
        <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M18 6 6 18M6 6l12 12"/></svg>
      </button>
    </div>
    <div class="modal-body" id="modalBody"></div>
  </div>
</div>

<!-- Toast -->
<div class="toast" id="toast"></div>

<footer class="footer">
  <div class="footer-inner">
    <div class="footer-brand">
      <span class="logo-text">DealScout <span class="logo-accent">AI</span></span>
      <p>Smart shopping, powered by AI.</p>
    </div>
    <div class="footer-note">
      <strong>Disclaimer:</strong> Prices shown are <em>demo data</em> for illustration. Connect a live shopping API (e.g., Amazon Product Advertising, Best Buy, Walmart) for real-time results.
    </div>
  </div>
</footer>

<script src="script.js"></script>
</body>
</html>
