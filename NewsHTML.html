<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Agregador de Noticias Chile - Análisis Profesional</title>
  <style>
    /* All existing CSS styling remains unchanged */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }
    body {
      font-family: 'Inter', -apple-system, BlinkMacSystemFont, 'Segoe UI', sans-serif;
      background: #0a0a0a;
      color: #e4e4e7;
      min-height: 100vh;
      line-height: 1.6;
    }
    .header {
      background: linear-gradient(135deg, #1a1a1a 0%, #2d2d2d 100%);
      border-bottom: 1px solid #333;
      padding: 20px 0;
      position: sticky;
      top: 0;
      z-index: 100;
      backdrop-filter: blur(20px);
    }
    .header-content {
      max-width: 1400px;
      margin: 0 auto;
      padding: 0 20px;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }
    .logo {
      display: flex;
      align-items: center;
      gap: 12px;
    }
    .logo h1 {
      font-size: 24px;
      font-weight: 700;
      color: #ffffff;
      letter-spacing: -0.5px;
    }
    .logo .flag {
      font-size: 28px;
    }
    .header-meta {
      display: flex;
      align-items: center;
      gap: 20px;
      font-size: 14px;
      color: #9ca3af;
    }
    .status-indicator {
      display: flex;
      align-items: center;
      gap: 8px;
      padding: 6px 12px;
      background: rgba(34, 197, 94, 0.1);
      border: 1px solid rgba(34, 197, 94, 0.2);
      border-radius: 20px;
      font-size: 12px;
    }
    .status-dot {
      width: 8px;
      height: 8px;
      background: #22c55e;
      border-radius: 50%;
      animation: pulse 2s infinite;
    }
    @keyframes pulse {
      0%, 100% { opacity: 1; }
      50% { opacity: 0.5; }
    }
    /* Top News Scrolling Section */
    .top-news-section {
      background: #111111;
      border-bottom: 1px solid #333;
      overflow: hidden;
      position: relative;
    }
    .top-news-header {
      max-width: 1400px;
      margin: 0 auto;
      padding: 20px 20px 0;
    }
    .top-news-title {
      font-size: 18px;
      font-weight: 600;
      color: #ffffff;
      margin-bottom: 15px;
      display: flex;
      align-items: center;
      gap: 10px;
    }
    .news-ticker {
      height: 120px;
      overflow: hidden;
      position: relative;
      background: linear-gradient(135deg, #1a1a1a 0%, #2d2d2d 100%);
      border-radius: 12px;
      margin-bottom: 20px;
    }
    .news-scroll {
      display: flex;
      animation: scroll-left 60s linear infinite;
      height: 100%;
    }
    .news-scroll:hover {
      animation-play-state: paused;
    }
    @keyframes scroll-left {
      0% { transform: translateX(100%); }
      100% { transform: translateX(-100%); }
    }
    .news-item {
      min-width: 350px;
      height: 100%;
      display: flex;
      align-items: center;
      padding: 20px;
      border-right: 1px solid #333;
      cursor: pointer;
      transition: background 0.3s ease;
    }
    .news-item:hover {
      background: rgba(255, 255, 255, 0.05);
    }
    .news-content {
      flex: 1;
    }
    .news-headline {
      font-size: 14px;
      font-weight: 600;
      color: #ffffff;
      margin-bottom: 8px;
      line-height: 1.4;
      display: -webkit-box;
      -webkit-line-clamp: 2;
      -webkit-box-orient: vertical;
      overflow: hidden;
    }
    .news-meta {
      font-size: 12px;
      color: #9ca3af;
      display: flex;
      align-items: center;
      gap: 12px;
    }
    .news-source {
      padding: 2px 8px;
      background: rgba(59, 130, 246, 0.1);
      border: 1px solid rgba(59, 130, 246, 0.2);
      border-radius: 12px;
      font-size: 10px;
      color: #60a5fa;
    }
    /* Search Section */
    .search-section {
      max-width: 1400px;
      margin: 0 auto;
      padding: 40px 20px;
    }
    .search-container {
      background: linear-gradient(135deg, #1a1a1a 0%, #2d2d2d 100%);
      border: 1px solid #333;
      border-radius: 16px;
      padding: 40px;
      text-align: center;
    }
    .search-title {
      font-size: 28px;
      font-weight: 700;
      color: #ffffff;
      margin-bottom: 12px;
      letter-spacing: -0.5px;
    }
    .search-subtitle {
      font-size: 16px;
      color: #9ca3af;
      margin-bottom: 32px;
    }
    .search-form {
      max-width: 600px;
      margin: 0 auto;
      display: flex;
      gap: 16px;
    }
    .search-input {
      flex: 1;
      padding: 16px 20px;
      background: #000000;
      border: 2px solid #333;
      border-radius: 12px;
      color: #ffffff;
      font-size: 16px;
      transition: all 0.3s ease;
    }
    .search-input:focus {
      outline: none;
      border-color: #3b82f6;
      box-shadow: 0 0 0 3px rgba(59, 130, 246, 0.1);
    }
    .search-input::placeholder {
      color: #6b7280;
    }
    .search-button {
      padding: 16px 32px;
      background: linear-gradient(135deg, #3b82f6 0%, #1d4ed8 100%);
      border: none;
      border-radius: 12px;
      color: #ffffff;
      font-size: 16px;
      font-weight: 600;
      cursor: pointer;
      transition: all 0.3s ease;
      white-space: nowrap;
    }
    .search-button:hover {
      transform: translateY(-2px);
      box-shadow: 0 10px 20px rgba(59, 130, 246, 0.3);
    }
    .search-button:disabled {
      opacity: 0.6;
      cursor: not-allowed;
      transform: none;
    }
    .search-examples {
      margin-top: 24px;
      font-size: 14px;
      color: #6b7280;
    }
    .search-examples strong {
      color: #9ca3af;
    }
    /* Results Section */
    .results-section {
      max-width: 1400px;
      margin: 0 auto;
      padding: 0 20px 40px;
      display: none;
    }
    .results-section.active {
      display: block;
      animation: fadeInUp 0.5s ease;
    }
    @keyframes fadeInUp {
      from {
        opacity: 0;
        transform: translateY(30px);
      }
      to {
        opacity: 1;
        transform: translateY(0);
      }
    }
    .analysis-grid {
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 24px;
      margin-bottom: 40px;
    }
    .analysis-card {
      background: linear-gradient(135deg, #1a1a1a 0%, #2d2d2d 100%);
      border: 1px solid #333;
      border-radius: 16px;
      padding: 24px;
    }
    .card-title {
      font-size: 18px;
      font-weight: 600;
      color: #ffffff;
      margin-bottom: 16px;
      display: flex;
      align-items: center;
      gap: 10px;
    }
    .spectrum-bar {
      height: 60px;
      background: #000000;
      border-radius: 8px;
      overflow: hidden;
      display: flex;
      margin-bottom: 16px;
    }
    .spectrum-segment {
      display: flex;
      align-items: center;
      justify-content: center;
      color: #ffffff;
      font-weight: 600;
      font-size: 14px;
      transition: all 0.3s ease;
    }
    .spectrum-left {
      background: linear-gradient(135deg, #ef4444 0%, #dc2626 100%);
    }
    .spectrum-center {
      background: linear-gradient(135deg, #f59e0b 0%, #d97706 100%);
    }
    .spectrum-right {
      background: linear-gradient(135deg, #3b82f6 0%, #1d4ed8 100%);
    }
    .key-points {
      list-style: none;
    }
    .key-point {
      background: rgba(59, 130, 246, 0.05);
      border-left: 3px solid #3b82f6;
      padding: 16px;
      margin-bottom: 12px;
      border-radius: 8px;
      font-size: 14px;
      line-height: 1.6;
    }
    /* News Sources Grid */
    .sources-section {
      margin-top: 40px;
    }
    .section-title {
      font-size: 24px;
      font-weight: 700;
      color: #ffffff;
      margin-bottom: 24px;
      display: flex;
      align-items: center;
      gap: 12px;
    }
    .sources-grid {
      display: grid;
      grid-template-columns: repeat(auto-fill, minmax(350px, 1fr));
      gap: 24px;
    }
    .source-card {
      background: linear-gradient(135deg, #1a1a1a 0%, #2d2d2d 100%);
      border: 1px solid #333;
      border-radius: 16px;
      overflow: hidden;
      transition: all 0.3s ease;
      cursor: pointer;
    }
    .source-card:hover {
      transform: translateY(-4px);
      border-color: #3b82f6;
      box-shadow: 0 20px 40px rgba(0, 0, 0, 0.3);
    }
    .source-image {
      height: 180px;
      background: linear-gradient(135deg, #374151 0%, #1f2937 100%);
      display: flex;
      align-items: center;
      justify-content: center;
      position: relative;
      overflow: hidden;
    }
    .source-image img {
      width: 100%;
      height: 100%;
      object-fit: cover;
    }
    .source-overlay {
      position: absolute;
      bottom: 0;
      left: 0;
      right: 0;
      background: linear-gradient(transparent, rgba(0, 0, 0, 0.8));
      padding: 20px;
      color: #ffffff;
    }
    .source-body {
      padding: 20px;
    }
    .source-title {
      font-size: 16px;
      font-weight: 600;
      color: #ffffff;
      margin-bottom: 12px;
      line-height: 1.4;
      display: -webkit-box;
      -webkit-line-clamp: 2;
      -webkit-box-orient: vertical;
      overflow: hidden;
    }
    .source-description {
      font-size: 14px;
      color: #9ca3af;
      line-height: 1.6;
      margin-bottom: 16px;
      display: -webkit-box;
      -webkit-line-clamp: 3;
      -webkit-box-orient: vertical;
      overflow: hidden;
    }
    .source-footer {
      display: flex;
      justify-content: space-between;
      align-items: center;
    }
    .bias-indicator {
      padding: 4px 12px;
      border-radius: 20px;
      font-size: 12px;
      font-weight: 600;
    }
    .bias-left {
      background: rgba(239, 68, 68, 0.1);
      color: #ef4444;
      border: 1px solid rgba(239, 68, 68, 0.2);
    }
    .bias-center {
      background: rgba(245, 158, 11, 0.1);
      color: #f59e0b;
      border: 1px solid rgba(245, 158, 11, 0.2);
    }
    .bias-right {
      background: rgba(59, 130, 246, 0.1);
      color: #3b82f6;
      border: 1px solid rgba(59, 130, 246, 0.2);
    }
    .source-time {
      font-size: 12px;
      color: #6b7280;
    }
    /* Loading and Error States */
    .loading {
      text-align: center;
      padding: 60px 20px;
      color: #9ca3af;
    }
    .loading-spinner {
      width: 40px;
      height: 40px;
      border: 3px solid #333;
      border-top: 3px solid #3b82f6;
      border-radius: 50%;
      animation: spin 1s linear infinite;
      margin: 0 auto 16px;
    }
    @keyframes spin {
      0% { transform: rotate(0deg); }
      100% { transform: rotate(360deg); }
    }
    .error-message {
      background: rgba(239, 68, 68, 0.1);
      border: 1px solid rgba(239, 68, 68, 0.2);
      color: #ef4444;
      padding: 16px;
      border-radius: 12px;
      margin: 20px 0;
      text-align: center;
    }
    .no-results {
      text-align: center;
      padding: 60px 20px;
      color: #6b7280;
    }
    /* Responsive Design */
    @media (max-width: 768px) {
      .header-content {
        flex-direction: column;
        gap: 16px;
        text-align: center;
      }
      .search-form {
        flex-direction: column;
      }
      .analysis-grid {
        grid-template-columns: 1fr;
      }
      .sources-grid {
        grid-template-columns: 1fr;
      }
      .news-item {
        min-width: 280px;
      }
    }
  </style>
</head>
<body>
  <!-- Header -->
  <header class="header">
    <div class="header-content">
      <div class="logo">
        <span class="flag">🇨🇱</span>
        <h1>Agregador de Noticias Chile</h1>
      </div>
      <div class="header-meta">
        <div class="status-indicator">
          <div class="status-dot"></div>
          <span>Sistema Activo</span>
        </div>
        <div id="currentDate"></div>
      </div>
    </div>
  </header>
  
  <!-- Top News Scrolling Section -->
  <section class="top-news-section">
    <div class="top-news-header">
      <h2 class="top-news-title">📊 Últimas Noticias en Tiempo Real</h2>
    </div>
    <div class="news-ticker">
      <div class="news-scroll" id="newsScroll">
        <!-- Auto-scrolling news items will be inserted here -->
      </div>
    </div>
  </section>
  
  <!-- Search Section -->
  <section class="search-section">
    <div class="search-container">
      <h2 class="search-title">Análisis Profesional de Noticias</h2>
      <p class="search-subtitle">Búsqueda avanzada con análisis del espectro político chileno</p>
      <form class="search-form" onsubmit="searchNews(event)">
        <input type="text" class="search-input" id="searchInput" placeholder="Ingrese tema de análisis (ej: reforma tributaria, elecciones)" required>
        <button type="submit" class="search-button" id="searchButton">🔍 Analizar</button>
      </form>
      <div class="search-examples">
        <strong>Ejemplos:</strong> "Gabriel Boric", "inflación Chile", "reforma constitucional", "elecciones municipales"
      </div>
    </div>
  </section>
  
  <!-- Results Section -->
  <section class="results-section" id="resultsSection">
    <div class="analysis-grid">
      <div class="analysis-card">
        <h3 class="card-title">📊 Distribución por Espectro Político</h3>
        <div class="spectrum-bar" id="spectrumBar">
          <div class="spectrum-segment spectrum-left" id="leftSegment">
            Izquierda<br><span id="leftCount">0</span>
          </div>
          <div class="spectrum-segment spectrum-center" id="centerSegment">
            Centro<br><span id="centerCount">0</span>
          </div>
          <div class="spectrum-segment spectrum-right" id="rightSegment">
            Derecha<br><span id="rightCount">0</span>
          </div>
        </div>
      </div>
      <div class="analysis-card">
        <h3 class="card-title">🤖 Análisis Inteligente</h3>
        <ul class="key-points" id="keyPointsList">
          <li class="key-point">Iniciando análisis...</li>
        </ul>
      </div>
    </div>
    <div class="sources-section">
      <h3 class="section-title">📰 Fuentes Analizadas</h3>
      <div class="sources-grid" id="sourcesGrid">
        <!-- Source cards will be inserted here -->
      </div>
    </div>
  </section>
  
  <script>
    // Configuration with multiple API keys/endpoints.
    const CONFIG = {
      // Replace with your actual keys if available.
      NEWS_DATA_IO_KEY: 'pub_60750946beaa2e9d4b79a6a2e65ecdb3ba6d5',
      NEWS_API_ORG_KEY: 'YOUR_NEWSAPI_KEY', // Replace with your actual NewsAPI.org key
      CHILEAN_SOURCES: {
        left: [
          { name: "El Siglo", bias: "left", description: "Perspectiva progresista", domain: "elsiglo.cl" },
          { name: "Radio Universidad de Chile", bias: "left", description: "Radio universitaria crítica", domain: "radio.uchile.cl" },
          { name: "El Desconcierto", bias: "left", description: "Medio digital progresista", domain: "eldesconcierto.cl" }
        ],
        center: [
          { name: "La Tercera", bias: "center", description: "Diario nacional centrado", domain: "latercera.com" },
          { name: "Radio Cooperativa", bias: "center", description: "Cobertura equilibrada", domain: "cooperativa.cl" },
          { name: "CNN Chile", bias: "center", description: "Canal informativo", domain: "cnnchile.com" },
          { name: "T13", bias: "center", description: "Televisión noticiosa", domain: "t13.cl" }
        ],
        right: [
          { name: "El Mercurio", bias: "right", description: "Diario tradicional conservador", domain: "elmercurio.com" },
          { name: "Las Últimas Noticias", bias: "right", description: "Tablóide conservador", domain: "lun.com" },
          { name: "La Cuarta", bias: "right", description: "Medio popular conservador", domain: "lacuarta.com" }
        ]
      }
    };
    
    // Initialize the application
    document.addEventListener('DOMContentLoaded', function() {
      initializeApp();
    });
    
    function initializeApp() {
      updateDateTime();
      loadTopNews();
      setInterval(loadTopNews, 300000); // Refresh every 5 minutes
      setInterval(updateDateTime, 60000); // Update time every minute
    }
    
    function updateDateTime() {
      const now = new Date();
      const dateString = now.toLocaleDateString('es-CL', { 
        weekday: 'long', 
        year: 'numeric', 
        month: 'long', 
        day: 'numeric',
        hour: '2-digit',
        minute: '2-digit'
      });
      document.getElementById('currentDate').textContent = dateString;
    }
    
    // Load top news from multiple providers.
    async function loadTopNews() {
      let allArticles = [];
    
      // Provider 1: NewsData.io (needs key)
      try {
        const response1 = await fetch(`https://newsdata.io/api/1/news?apikey=${CONFIG.NEWS_DATA_IO_KEY}&country=cl&language=es&size=10`);
        if (response1.ok) {
          const data1 = await response1.json();
          if (data1.results && data1.results.length > 0) {
            allArticles = allArticles.concat(data1.results);
          }
        }
      } catch (error) {
        console.error('Error loading NewsData.io:', error);
      }
    
      // Provider 2: NewsAPI.org (needs key)
      try {
        const response2 = await fetch(`https://newsapi.org/v2/top-headlines?country=cl&apiKey=${CONFIG.NEWS_API_ORG_KEY}`);
        if (response2.ok) {
          const data2 = await response2.json();
          if (data2.articles && data2.articles.length > 0) {
            const mappedArticles = data2.articles.map(article => ({
              title: article.title,
              link: article.url,
              pubDate: article.publishedAt,
              source_id: article.source.name.toLowerCase().replace(/\s+/g, '')
            }));
            allArticles = allArticles.concat(mappedArticles);
          }
        }
      } catch (error) {
        console.error('Error loading NewsAPI.org:', error);
      }
    
      // Provider 3: The Guardian Open Platform (no key needed, using test key)
      try {
        const response3 = await fetch(`https://content.guardianapis.com/search?q=Chile&api-key=test&page-size=10`);
        if (response3.ok) {
          const data3 = await response3.json();
          if (data3.response && data3.response.results && data3.response.results.length > 0) {
            const mappedGuardian = data3.response.results.map(article => ({
              title: article.webTitle,
              link: article.webUrl,
              pubDate: article.webPublicationDate,
              source_id: "theguardian"
            }));
            allArticles = allArticles.concat(mappedGuardian);
          }
        }
      } catch (error) {
        console.error('Error loading The Guardian API:', error);
      }
    
      if (allArticles.length > 0) {
        displayTopNews(allArticles);
      } else {
        displayFallbackNews();
      }
    }
    
    function displayTopNews(articles) {
      const newsScroll = document.getElementById('newsScroll');
      const newsItems = articles.slice(0, 12).map(article => {
        const source = classifySource(article.source_id || 'unknown');
        return `
          <div class="news-item" onclick="window.open('${article.link}', '_blank')">
            <div class="news-content">
              <div class="news-headline">${article.title}</div>
              <div class="news-meta">
                <span class="news-source">${source.name}</span>
                <span>${formatTime(article.pubDate)}</span>
              </div>
            </div>
          </div>
        `;
      }).join('');
      // Duplicate items for seamless scrolling
      newsScroll.innerHTML = newsItems + newsItems;
    }
    
    function displayFallbackNews() {
      const fallbackNews = [
        { title: "Sistema de monitoreo de noticias activo", source: "Sistema", time: "Ahora" },
        { title: "Analizando cobertura mediática chilena", source: "IA", time: "En tiempo real" },
        { title: "Conectando con fuentes de información", source: "Red", time: "Continuo" }
      ];
      const newsScroll = document.getElementById('newsScroll');
      const newsItems = fallbackNews.map(item => `
        <div class="news-item">
          <div class="news-content">
            <div class="news-headline">${item.title}</div>
            <div class="news-meta">
              <span class="news-source">${item.source}</span>
              <span>${item.time}</span>
            </div>
          </div>
        </div>
      `).join('');
      newsScroll.innerHTML = newsItems + newsItems;
    }
    
    function classifySource(sourceId) {
      const allSources = [
        ...CONFIG.CHILEAN_SOURCES.left,
        ...CONFIG.CHILEAN_SOURCES.center,
        ...CONFIG.CHILEAN_SOURCES.right
      ];
      return allSources.find(s => s.domain.includes(sourceId)) ||
             { name: sourceId, bias: 'center', description: 'Fuente de noticias', domain: sourceId };
    }
    
    function formatTime(dateString) {
      const date = new Date(dateString);
      const now = new Date();
      const diffMs = now - date;
      const diffHours = Math.floor(diffMs / (1000 * 60 * 60));
      if (diffHours < 1) return 'Hace menos de 1h';
      if (diffHours < 24) return `Hace ${diffHours}h`;
      return date.toLocaleDateString('es-CL');
    }
    
    async function searchNews(event) {
      event.preventDefault();
      const query = document.getElementById('searchInput').value.trim();
      if (!query) return;
      const searchButton = document.getElementById('searchButton');
      const resultsSection = document.getElementById('resultsSection');
    
      // Show loading state
      searchButton.disabled = true;
      searchButton.textContent = '🔄 Analizando...';
      resultsSection.classList.add('active');
      showLoading();
    
      try {
        const newsData = await fetchNewsData(query);
        if (newsData.length > 0) {
          await analyzeAndDisplayResults(query, newsData);
        } else {
          showNoResults();
        }
      } catch (error) {
        console.error('Search error:', error);
        showError('Error al realizar la búsqueda. Intente nuevamente.');
      } finally {
        searchButton.disabled = false;
        searchButton.textContent = '🔍 Analizar';
      }
    }
    
    async function fetchNewsData(query) {
      try {
        const response = await fetch(`https://newsdata.io/api/1/news?apikey=${CONFIG.NEWS_DATA_IO_KEY}&country=cl&language=es&q=${encodeURIComponent(query)}&size=50`);
        if (response.ok) {
          const data = await response.json();
          return processNewsData(data.results || []);
        }
      } catch (error) {
        console.error('Error fetching news:', error);
      }
      return [];
    }
    
    function processNewsData(articles) {
      return articles.map(article => {
        const source = classifySource(article.source_id || 'unknown');
        return {
          title: article.title,
          description: article.description || article.content || '',
          url: article.link,
          source: source,
          publishedAt: new Date(article.pubDate),
          image: article.image_url || `https://picsum.photos/400/250?random=${Math.floor(Math.random() * 1000)}`,
          bias: source.bias
        };
      });
    }
    
    async function analyzeAndDisplayResults(query, articles) {
      const coverage = { left: 0, center: 0, right: 0 };
      articles.forEach(article => {
        coverage[article.bias]++;
      });
      updateSpectrumVisualization(coverage);
      generateAIAnalysis(query, articles, coverage);
      displaySourceCards(articles);
    }
    
    function updateSpectrumVisualization(coverage) {
      const total = coverage.left + coverage.center + coverage.right;
      if (total === 0) return;
      const leftPercentage = (coverage.left / total) * 100;
      const centerPercentage = (coverage.center / total) * 100;
      const rightPercentage = (coverage.right / total) * 100;
      document.getElementById('leftSegment').style.width = leftPercentage + '%';
      document.getElementById('centerSegment').style.width = centerPercentage + '%';
      document.getElementById('rightSegment').style.width = rightPercentage + '%';
      document.getElementById('leftCount').textContent = coverage.left;
      document.getElementById('centerCount').textContent = coverage.center;
      document.getElementById('rightCount').textContent = coverage.right;
    }
    
    function generateAIAnalysis(query, articles, coverage) {
      const total = coverage.left + coverage.center + coverage.right;
      const keyPoints = [];
      if (total > 0) {
        const dominant = Object.keys(coverage).reduce((a, b) => coverage[a] > coverage[b] ? a : b);
        const dominantPercentage = Math.round((coverage[dominant] / total) * 100);
        keyPoints.push(`La cobertura está dominada por medios de ${translateBias(dominant)} (${dominantPercentage}% del total)`);
      }
      const nonZero = Object.values(coverage).filter(v => v > 0).length;
      if (nonZero === 3) {
        keyPoints.push("Se observa cobertura diversa a lo largo de todo el espectro político");
      } else if (nonZero === 2) {
        keyPoints.push("Cobertura limitada a dos tendencias políticas principales");
      } else {
        keyPoints.push("Cobertura concentrada en una sola tendencia política");
      }
      if (total > 20) {
        keyPoints.push("Alto volumen de cobertura mediática sobre este tema");
      } else if (total > 10) {
        keyPoints.push("Cobertura moderada del tema en medios chilenos");
      } else {
        keyPoints.push("Cobertura limitada - tema de menor atención mediática");
      }
      displayKeyPoints(keyPoints);
    }
    
    function translateBias(bias) {
      const translations = {
        'left': 'izquierda',
        'center': 'centro',
        'right': 'derecha'
      };
      return translations[bias] || bias;
    }
    
    function displayKeyPoints(keyPoints) {
      const keyPointsList = document.getElementById('keyPointsList');
      keyPointsList.innerHTML = keyPoints.map(point => `<li class="key-point">${point}</li>`).join('');
    }
    
    function showLoading() {
      const keyPointsList = document.getElementById('keyPointsList');
      keyPointsList.innerHTML = `<li class="key-point">Cargando análisis...</li>`;
    }
    
    function showNoResults() {
      const keyPointsList = document.getElementById('keyPointsList');
      keyPointsList.innerHTML = `<li class="key-point">No se encontraron resultados.</li>`;
    }
    
    function showError(message) {
      const keyPointsList = document.getElementById('keyPointsList');
      keyPointsList.innerHTML = `<li class="key-point">${message}</li>`;
    }
    
    function displaySourceCards(articles) {
      const sourcesGrid = document.getElementById('sourcesGrid');
      let uniqueSources = [];
      const seen = {};
      articles.forEach(article => {
        if (!seen[article.source.domain]) {
          seen[article.source.domain] = true;
          uniqueSources.push(article.source);
        }
      });
      sourcesGrid.innerHTML = uniqueSources.map(source => `
        <div class="source-card" onclick="window.open('https://${source.domain}', '_blank')">
          <div class="source-body">
            <h4 class="source-title">${source.name}</h4>
            <p class="source-description">${source.description}</p>
            <p class="source-time">Fuente: ${source.domain}</p>
          </div>
        </div>
      `).join('');
    }
  </script>
</body>
</html>
