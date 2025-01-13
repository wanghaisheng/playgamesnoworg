
<html><head><base href="https://playgamesnow.org/squidgames/intro">
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>Squid Game Guide: Everything You Need to Know | Episodes, Cast &amp; Season 2</title>
    
    <style>
    :root {
      --teal: #00c2b2;
      --pink: #ff68b5;
      --white: #ffffff;
      --black: #000000;
      --gray: #666666;
      --gradient-primary: linear-gradient(135deg, var(--pink) 0%, var(--teal) 100%);
      --box-shadow: 0 4px 20px rgba(0,0,0,0.1);
      --card-bg: rgba(255,255,255,0.05);
      --card-hover: rgba(255,255,255,0.1);
      --transition: all 0.3s cubic-bezier(0.4, 0, 0.2, 1);
    }
    
    html {
      scroll-behavior: smooth;
    }
    
    .main-nav {
      backdrop-filter: blur(10px);
      -webkit-backdrop-filter: blur(10px);
      border-bottom: 1px solid rgba(255,255,255,0.1);
    }
    
    .main-nav a {
      position: relative;
      padding: 0.5rem 1rem;
    }
    
    .main-nav a::after {
      content: '';
      position: absolute;
      bottom: 0;
      left: 0;
      width: 0;
      height: 2px;
      background: var(--gradient-primary);
      transition: var(--transition);
    }
    
    .main-nav a:hover::after {
      width: 100%;
    }
    
    .episode-card,
    .game-card,
    .character-card,
    .theory-card,
    .season2-card,
    .community-card {
      background: var(--card-bg);
      backdrop-filter: blur(10px);
      -webkit-backdrop-filter: blur(10px);
      border: 1px solid rgba(255,255,255,0.1);
      box-shadow: var(--box-shadow);
      transition: var(--transition);
    }
    
    .episode-card:hover,
    .game-card:hover,
    .character-card:hover,
    .theory-card:hover,
    .season2-card:hover,
    .community-card:hover {
      transform: translateY(-5px);
      background: var(--card-hover);
    }
    
    .section-title {
      background: linear-gradient(60deg, var(--pink), var(--teal), var(--pink));
      background-size: 200% 200%;
      animation: gradientShift 10s ease infinite;
      -webkit-background-clip: text;
      background-clip: text;
      font-size: 3rem;
      text-align: center;
      margin-bottom: 3rem;
    }
    
    @keyframes gradientShift {
      0% {
        background-position: 0% 50%;
      }
      50% {
        background-position: 100% 50%;
      }
      100% {
        background-position: 0% 50%;
      }
    }
    
    .expand-btn,
    .vote-btn,
    .filter-btn,
    .page-btn,
    .submit-art-btn,
    .post-btn {
      background: var(--gradient-primary);
      border: none;
      padding: 0.8rem 1.5rem;
      border-radius: 50px;
      color: var(--white);
      font-weight: 600;
      cursor: pointer;
      transition: var(--transition);
      box-shadow: var(--box-shadow);
    }
    
    .expand-btn:hover,
    .vote-btn:hover,
    .filter-btn:hover,
    .page-btn:hover,
    .submit-art-btn:hover,
    .post-btn:hover {
      transform: translateY(-2px);
      box-shadow: 0 6px 25px rgba(255,104,181,0.3);
    }
    
    .character-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
      gap: 2rem;
      padding: 2rem;
    }
    
    .community-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
      gap: 2rem;
      margin-top: 2rem;
    }
    
    .community-card {
      background: var(--card-bg);
      padding: 2rem;
      border-radius: 10px;
      transition: var(--transition);
    }
    
    .community-card:hover {
      transform: translateY(-5px);
      background: var(--card-hover);
    }
    
    .community-stats {
      display: grid;
      grid-template-columns: repeat(2, 1fr);
      gap: 1rem;
      margin: 1.5rem 0;
    }
    
    .community-list {
      list-style: none;
      margin: 1rem 0;
    }
    
    .community-list li {
      padding: 0.5rem 0;
      border-bottom: 1px solid rgba(255,255,255,0.1);
    }
    
    .events-timeline {
      margin-top: 1.5rem;
    }
    
    .event-item {
      padding: 1rem;
      margin-bottom: 1rem;
      background: rgba(255,255,255,0.05);
      border-radius: 8px;
      transition: transform 0.3s ease;
    }
    
    .event-item:hover {
      transform: translateX(10px);
    }
    
    .event-item h4 {
      color: var(--pink);
      margin-bottom: 0.5rem;
    }
    
    .stat-card,
    .character-card,
    .game-card {
      backdrop-filter: blur(10px);
      -webkit-backdrop-filter: blur(10px);
    }
    
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: Arial, sans-serif;
    }
    
    body {
      overflow-x: hidden;
      background-color: #0a0a0a;
      color: var(--white);
    }
    
    section {
      padding: 4rem 2rem;
    }
    
    .tv-series-container {
      max-width: 1200px;
      margin: 0 auto;
      padding: 2rem;
      margin-top: 20rem; /* Add margin to avoid overlap */
    }
    
    .voting-hero {
      margin-top: 20rem; /* Add margin to avoid overlap */

      background: linear-gradient(rgba(0,0,0,0.8), rgba(0,0,0,0.8)), 
                  url('squidgame/season2-bg.jpg') center/cover;
      min-height: 100vh;
      padding: 6rem 2rem;
      margin-bottom: 2rem; /* Add margin to avoid overlap */
    }
    
    .voting-content {
      max-width: 1200px;
      margin: 0 auto;
    }
    
    .tweet-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
      gap: 2rem;
      margin: 3rem 0;
    }
    
    .tweet-card {
      background: rgba(255,255,255,0.1);
      backdrop-filter: blur(10px);
      border-radius: 15px;
      padding: 1.5rem;
      transition: transform 0.3s ease;
    }
    
    .tweet-card:hover {
      transform: translateY(-5px);
    }
    
    .tweet-header {
      display: flex;
      align-items: center;
      gap: 1rem;
      margin-bottom: 1rem;
    }
    
    .tweet-avatar {
      width: 48px;
      height: 48px;
      border-radius: 50%;
    }
    
    .tweet-meta {
      display: flex;
      flex-direction: column;
    }
    
    .tweet-name {
      font-weight: bold;
      color: var(--white);
    }
    
    .tweet-date {
      font-size: 0.9rem;
      color: var(--gray);
    }
    
    .tweet-text {
      font-size: 1.1rem;
      line-height: 1.6;
      margin-bottom: 1rem;
      color: var(--white);
    }
    
    .tweet-link {
      color: var(--pink);
      text-decoration: none;
      font-size: 0.9rem;
      transition: color 0.3s ease;
    }
    
    .tweet-link:hover {
      color: var(--teal);
    }
    
    .sentiment-meter {
      text-align: center;
      margin-top: 4rem;
    }
    
    .meter {
      background: rgba(255,255,255,0.1);
      height: 30px;
      border-radius: 15px;
      position: relative;
      max-width: 600px;
      margin: 1rem auto;
      overflow: hidden;
    }
    
    .meter-fill {
      position: absolute;
      left: 0;
      top: 0;
      height: 100%;
      width: 0%;
      background: var(--gradient-primary);
      transition: width 1.5s ease-out;
    }
    
    .meter-label {
      position: absolute;
      left: 50%;
      top: 50%;
      transform: translate(-50%, -50%);
      color: var(--white);
      font-weight: bold;
      z-index: 1;
    }
    
    .tweet-card.positive {
      border: 1px solid rgba(0,255,0,0.2);
    }
    
    .tweet-card.mixed {
      border: 1px solid rgba(255,255,0,0.2);
    }
    
    .hero-section {
      position: relative;
      height: 80vh;
      display: flex;
      align-items: center;
      justify-content: center;
      text-align: center;
      color: var(--white);
      background: linear-gradient(rgba(0,0,0,0.7), rgba(0,0,0,0.7)), 
                  url('/squidgame/hero-bg.jpg') center/cover;
    }
    
    .hero-content {
      max-width: 800px;
      padding: 2rem;
    }
    
    .hero-title {
      font-size: 4rem;
      margin-bottom: 1rem;
      color: var(--pink);
      text-shadow: 0 0 10px rgba(255,104,181,0.5);
    }
    
    .hero-subtitle {
      font-size: 1.8rem;
      margin-bottom: 1rem;
      color: var(--white);
    }
    
    .hero-description {
      font-size: 1.2rem;
      line-height: 1.6;
      margin-bottom: 2rem;
    }
    
    .content-section {
      margin-bottom: 4rem;
      background-color: rgba(255,255,255,0.05);
      border-radius: 10px;
      padding: 2rem;
    }
    
    .section-header {
      border-bottom: 2px solid var(--pink);
      padding-bottom: 1rem;
      margin-bottom: 2rem;
    }
    
    .section-title {
      font-size: 2.5rem;
      color: var(--pink);
      margin-bottom: 1rem;
    }
    
    .section-subtitle {
      font-size: 1.5rem;
      color: var(--white);
      margin-bottom: 1rem;
    }
    
    .section-text {
      font-size: 1.2rem;
      line-height: 1.6;
      margin-bottom: 2rem;
    }
    
    .stats-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
      gap: 2rem;
      margin-top: 2rem;
    }
    
    .stat-card {
      background: rgba(255,255,255,0.1);
      padding: 1.5rem;
      border-radius: 10px;
      text-align: center;
      transition: transform 0.3s ease;
    }
    
    .stat-card:hover {
      transform: translateY(-5px);
    }
    
    .stat-number {
      font-size: 2.5rem;
      font-weight: bold;
      color: var(--pink);
      margin-bottom: 0.5rem;
    }
    
    .stat-label {
      font-size: 1.1rem;
      color: var(--white);
    }
    
    .cast-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 2rem;
      margin-top: 2rem;
    }
    
    .cast-card {
      background: rgba(255,255,255,0.1);
      padding: 1.5rem;
      border-radius: 10px;
      text-align: center;
      transition: transform 0.3s ease;
    }
    
    .cast-card:hover {
      transform: translateY(-5px);
    }
    
    .cast-name {
      font-size: 1.5rem;
      color: var(--pink);
      margin-bottom: 0.5rem;
    }
    
    .cast-role {
      font-size: 1.1rem;
      color: var(--white);
      margin-bottom: 1rem;
    }
    
    .cast-description {
      font-size: 1rem;
      line-height: 1.5;
      color: var(--gray);
    }
    
    .themes-section {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
      gap: 2rem;
      margin-top: 2rem;
    }
    
    .theme-card {
      background: rgba(255,255,255,0.1);
      padding: 2rem;
      border-radius: 10px;
      transition: transform 0.3s ease;
    }
    
    .theme-card:hover {
      transform: translateY(-5px);
    }
    
    .theme-title {
      font-size: 1.5rem;
      color: var(--pink);
      margin-bottom: 1rem;
    }
    
    .theme-description {
      font-size: 1.1rem;
      line-height: 1.6;
      color: var(--white);
    }
    
    .cultural-impact {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
      gap: 2rem;
      margin-top: 2rem;
    }
    
    .impact-card {
      background: rgba(255,255,255,0.1);
      padding: 2rem;
      border-radius: 10px;
      transition: transform 0.3s ease;
    }
    
    .impact-card:hover {
      transform: scale(1.02);
    }
    
    .impact-title {
      font-size: 1.5rem;
      color: var(--pink);
      margin-bottom: 1rem;
    }
    
    .impact-description {
      font-size: 1.1rem;
      line-height: 1.6;
      color: var(--white);
    }
    
    .awards-timeline {
      position: relative;
      max-width: 800px;
      margin: 4rem auto;
      padding: 2rem;
    }
    
    .award-item {
      position: relative;
      padding: 2rem;
      margin-bottom: 2rem;
      background: rgba(255,255,255,0.1);
      border-radius: 10px;
      transition: transform 0.3s ease;
    }
    
    .award-item:hover {
      transform: translateX(10px);
    }
    
    .award-title {
      font-size: 1.5rem;
      color: var(--pink);
      margin-bottom: 0.5rem;
    }
    
    .award-date {
      font-size: 1rem;
      color: var(--gray);
      margin-bottom: 1rem;
    }
    
    .award-description {
      font-size: 1.1rem;
      line-height: 1.6;
      color: var(--white);
    }
    
    .production-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
      gap: 2rem;
      margin-top: 2rem;
    }
    
    .production-card {
      background: rgba(255,255,255,0.1);
      padding: 2rem;
      border-radius: 10px;
      transition: transform 0.3s ease;
    }
    
    .production-card:hover {
      transform: translateY(-5px);
    }
    
    .production-title {
      font-size: 1.5rem;
      color: var(--pink);
      margin-bottom: 1rem;
    }
    
    .production-description {
      font-size: 1.1rem;
      line-height: 1.6;
      color: var(--white);
    }
    
    .bts-content {
      padding: 2rem;
      background: rgba(255,255,255,0.1);
      border-radius: 10px;
    }
    
    .bts-text {
      font-size: 1.1rem;
      line-height: 1.6;
    }
    
    .bts-list {
      margin: 1rem 0 1rem 2rem;
      color: var(--white);
    }
    
    .bts-list li {
      margin-bottom: 0.5rem;
    }
    
    .bts-quote {
      font-style: italic;
      color: var(--pink);
      margin-top: 1.5rem;
      padding: 1rem;
      border-left: 3px solid var(--pink);
    }
    
    .production-aspects {
      margin: 2rem 0;
    }
    
    .aspect-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
      gap: 2rem;
      margin-top: 2rem;
    }
    
    .aspect-card {
      background: rgba(255,255,255,0.1);
      padding: 2rem;
      border-radius: 10px;
      transition: transform 0.3s ease;
    }
    
    .aspect-card:hover {
      transform: translateY(-5px);
    }
    
    .aspect-title {
      font-size: 1.5rem;
      color: var(--pink);
      margin-bottom: 1rem;
    }
    
    .aspect-text {
      font-size: 1.1rem;
      line-height: 1.6;
      color: var(--white);
    }
    
    .statistics-container {
      margin-top: 4rem;
      padding: 2rem;
      background: rgba(255,255,255,0.05);
      border-radius: 10px;
    }
    
    .stat-row {
      display: flex;
      justify-content: space-around;
      flex-wrap: wrap;
      margin: 2rem 0;
    }
    
    .stat-item {
      text-align: center;
      padding: 1rem;
      flex: 1;
      min-width: 200px;
      animation: fadeInUp 0.6s ease-out;
      opacity: 0;
      transform: translateY(20px);
    }
    
    @keyframes fadeInUp {
      from {
        opacity: 0;
        transform: translateY(20px);
      }
      to {
        opacity: 1;
        transform: translateY(0);
      }
    }
    
    .stat-number {
      font-size: 2.5rem;
      color: var(--pink);
      font-weight: bold;
      display: block;
      margin-bottom: 0.5rem;
    }
    
    .stat-label {
      font-size: 1.1rem;
      color: var(--white);
    }
    
    .cultural-impact-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
      gap: 2rem;
      margin-top: 2rem;
    }
    
    .impact-section {
      background: rgba(255,255,255,0.1);
      padding: 2rem;
      border-radius: 10px;
    }
    
    .stats-list {
      list-style: none;
      padding: 0;
      margin: 1rem 0;
    }
    
    .stats-list li {
      margin-bottom: 0.8rem;
      font-size: 1.1rem;
    }
    
    .region {
      color: var(--pink);
      font-weight: bold;
    }
    
    .social-metrics {
      display: flex;
      justify-content: space-around;
      margin-top: 1rem;
    }
    
    .metric-card {
      text-align: center;
    }
    
    .metric-number {
      display: block;
      font-size: 2rem;
      color: var(--pink);
      font-weight: bold;
    }
    
    .metric-label {
      font-size: 0.9rem;
      color: var(--white);
    }
    
    .episode-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
      gap: 2rem;
      margin-top: 2rem;
    }
    
    .episode-card {
      background: var(--card-bg);
      backdrop-filter: blur(10px);
      -webkit-backdrop-filter: blur(10px);
      border: 1px solid rgba(255,255,255,0.1);
      box-shadow: var(--box-shadow);
      transition: var(--transition);
    }
    
    .episode-card:hover {
      transform: translateY(-5px);
      background: var(--card-hover);
    }
    
    .episode-title {
      color: var(--pink);
      font-size: 1.3rem;
      margin-bottom: 0.5rem;
    }
    
    .episode-rating {
      color: var(--teal);
      font-weight: bold;
      margin-bottom: 1rem;
    }
    
    .episode-text {
      line-height: 1.6;
    }
    
    .theme-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
      gap: 2rem;
      margin-top: 2rem;
    }
    
    .region-stats {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
      gap: 2rem;
      margin: 2rem 0;
    }
    
    .character-grid {
      display: grid;
      grid-template-columns: repeat(6, 1fr);
      gap: 1rem;
      margin-top: 2rem;
    }
    
    .character-filter {
      display: flex;
      justify-content: center;
      gap: 1rem;
      margin: 2rem 0;
    }
    
    .filter-btn {
      background: var(--pink);
      color: var(--white);
      border: none;
      padding: 0.5rem 1rem;
      border-radius: 5px;
      cursor: pointer;
    }
    
    .character-search {
      padding: 0.5rem;
      border-radius: 5px;
      border: 1px solid var(--pink);
      background: rgba(255,255,255,0.1);
      color: var(--white);
    }
    
    @media (max-width: 1200px) {
      .character-grid {
        grid-template-columns: repeat(4, 1fr);
      }
    }
    
    @media (max-width: 768px) {
      .character-grid {
        grid-template-columns: repeat(2, 1fr);
      }
    }
    
    .main-nav {
      position: fixed;
      top: 0;
      width: 100%;
      background: rgba(0,0,0,0.9);
      z-index: 1000;
      padding: 1rem 0;
    }
    
    .main-nav ul {
      display: flex;
      justify-content: center;
      list-style: none;
      gap: 2rem;
    }
    
    .main-nav a {
      color: var(--white);
      text-decoration: none;
      font-size: 1.1rem;
      transition: color 0.3s;
    }
    
    .main-nav a:hover {
      color: var(--pink);
    }
    
    .theory-card {
      background: rgba(255,255,255,0.1);
      padding: 2rem;
      border-radius: 10px;
      margin-bottom: 2rem;
    }
    
    .theory-title {
      color: var(--pink);
      font-size: 1.3rem;
      margin-bottom: 1rem;
    }
    
    .theory-votes {
      margin-top: 1rem;
      display: flex;
      gap: 1rem;
      align-items: center;
    }
    
    .vote-btn {
      background: none;
      border: 1px solid var(--pink);
      color: var(--white);
      padding: 0.5rem 1rem;
      border-radius: 5px;
      cursor: pointer;
      transition: all 0.3s;
    }
    
    .vote-btn:hover {
      background: var(--pink);
    }
    
    .merch-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 2rem;
    }
    
    .art-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
      gap: 1rem;
      margin-top: 2rem;
    }
    
    .submit-art-btn, .post-btn {
      background: var(--pink);
      color: var(--white);
      border: none;
      padding: 1rem 2rem;
      border-radius: 5px;
      cursor: pointer;
      margin-top: 2rem;
      transition: transform 0.3s;
    }
    
    .submit-art-btn:hover, .post-btn:hover {
      transform: translateY(-2px);
    }
    
    .episode-details {
      margin-top: 1rem;
      display: none;
    }
    
    .episode-card.expanded .episode-details {
      display: block;
    }
    
    .expand-btn {
      background: var(--pink);
      color: var(--white);
      border: none;
      padding: 0.5rem 1rem;
      border-radius: 5px;
      cursor: pointer;
      margin-top: 1rem;
    }
    
    .character-stats {
      display: grid;
      grid-template-columns: repeat(2, 1fr);
      gap: 0.5rem;
      margin-top: 0.5rem;
      font-size: 0.9rem;
    }
    
    .character-bio {
      margin-top: 1rem;
      display: none;
    }
    
    .character-card.expanded .character-bio {
      display: block;
    }
    
    .pagination {
      display: flex;
      justify-content: center;
      gap: 1rem;
      margin: 2rem 0;
    }
    
    .page-btn {
      background: var(--pink);
      color: var(--white);
      border: none;
      padding: 0.5rem 1rem;
      border-radius: 5px;
      cursor: pointer;
    }
    
    .page-btn.active {
      background: var(--teal);
    }
    
    .search-filters {
      display: flex;
      gap: 1rem;
      margin-bottom: 1rem;
      flex-wrap: wrap;
    }
    
    .filter-tag {
      background: rgba(255,255,255,0.1);
      padding: 0.5rem 1rem;
      border-radius: 15px;
      cursor: pointer;
    }
    
    .filter-tag.active {
      background: var(--pink);
    }
    
    .season2-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
      gap: 2rem;
      margin-top: 2rem;
    }
    
    .season2-card {
      background: var(--card-bg);
      backdrop-filter: blur(10px);
      -webkit-backdrop-filter: blur(10px);
      border: 1px solid rgba(255,255,255,0.1);
      box-shadow: var(--box-shadow);
      transition: var(--transition);
    }
    
    .season2-card:hover {
      transform: translateY(-5px);
      background: var(--card-hover);
    }
    
    .season2-card h3 {
      color: var(--pink);
      margin-bottom: 1rem;
    }
    
    .season2-card ul {
      list-style-type: none;
    }
    
    .season2-card li {
      margin-bottom: 0.8rem;
      color: var(--white);
    }
    
    .games-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(350px, 1fr));
      gap: 2rem;
      margin-top: 2rem;
    }
    
    .game-card {
      background: var(--card-bg);
      backdrop-filter: blur(10px);
      -webkit-backdrop-filter: blur(10px);
      border: 1px solid rgba(255,255,255,0.1);
      box-shadow: var(--box-shadow);
      transition: var(--transition);
    }
    
    .game-card:hover {
      transform: translateY(-5px);
      background: var(--card-hover);
    }
    
    .game-card h3 {
      color: var(--pink);
      margin-bottom: 1rem;
      font-size: 1.5rem;
    }
    
    .game-details h4 {
      color: var(--teal);
      margin: 1rem 0 0.5rem;
    }
    
    .game-details ul {
      list-style-type: disc;
      margin-left: 1.5rem;
      color: var(--white);
    }
    
    .game-details li {
      margin-bottom: 0.5rem;
      line-height: 1.4;
    }
    
    .pop-culture-list,
    .academic-list,
    .specs-list,
    .sound-list {
      list-style: none;
      padding: 0;
      margin: 1rem 0;
    }
    
    .pop-culture-list li,
    .academic-list li,
    .specs-list li,
    .sound-list li {
      padding: 0.8rem;
      margin-bottom: 0.5rem;
      background: rgba(255,255,255,0.05);
      border-radius: 5px;
      transition: all 0.3s ease;
    }
    
    .pop-culture-list li:hover,
    .academic-list li:hover,
    .specs-list li:hover,
    .sound-list li:hover {
      background: rgba(255,255,255,0.1);
      transform: translateX(10px);
    }
    
    .production-details {
      margin-top: 2rem;
      padding: 2rem;
      background: rgba(255,255,255,0.05);
      border-radius: 10px;
    }
    
    .character-additional-info {
      margin-top: 1rem;
      padding-top: 1rem;
      border-top: 1px solid rgba(255,255,255,0.1);
    }
    
    .character-additional-info h4 {
      color: var(--pink);
      margin-bottom: 0.5rem;
    }
    
    .character-additional-info p {
      margin-bottom: 1rem;
      line-height: 1.4;
    }
    
    .merchandise-stats {
      padding: 2rem;
      background: rgba(255,255,255,0.05);
      border-radius: 10px;
      margin-top: 2rem;
    }
    
    .merch-stats-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
      gap: 2rem;
      margin-top: 1rem;
    }
    
    .merch-stat {
      text-align: center;
      padding: 1.5rem;
      background: rgba(255,255,255,0.1);
      border-radius: 8px;
      transition: transform 0.3s ease;
    }
    
    .merch-stat:hover {
      transform: translateY(-5px);
    }
    
    .merch-number {
      display: block;
      font-size: 2.5rem;
      color: var(--pink);
      font-weight: bold;
      margin-bottom: 0.5rem;
    }
    
    .merch-label {
      color: var(--white);
      font-size: 1.1rem;
    }
    
    .streaming-stats {
      margin-top: 2rem;
      padding: 2rem;
      background: rgba(255,255,255,0.05);
      border-radius: 10px;
    }
    
    .platform-stats {
      margin-top: 1rem;
    }
    
    .platform-row {
      display: flex;
      align-items: center;
      margin-bottom: 1.5rem;
      gap: 1rem;
    }
    
    .platform-name {
      width: 100px;
      color: var(--white);
      font-weight: bold;
    }
    
    .progress-bar {
      flex-grow: 1;
      height: 30px;
      background: rgba(255,255,255,0.1);
      border-radius: 15px;
      position: relative;
      overflow: hidden;
    }
    
    .progress-fill {
      height: 100%;
      background: var(--gradient-primary);
      width: 0%;
      transition: width 1.5s ease-out;
    }
    
    .progress-text {
      position: absolute;
      left: 50%;
      top: 50%;
      transform: translate(-50%, -50%);
      color: var(--white);
      font-size: 0.9rem;
      font-weight: bold;
      white-space: nowrap;
    }
    
    @keyframes slideIn {
      from {
        transform: translateX(-100%);
      }
      to {
        transform: translateX(0);
      }
    }
    
    .platform-row {
      animation: slideIn 0.6s ease-out forwards;
      opacity: 0;
    }
    
    .platform-row:nth-child(1) {
      animation-delay: 0.2s;
    }
    
    .platform-row:nth-child(2) {
      animation-delay: 0.4s;
    }
    
    .awards-timeline {
      margin: 2rem 0;
      padding: 2rem;
      background: rgba(255,255,255,0.05);
      border-radius: 10px;
    }
    
    .award-item {
      padding: 1.5rem;
      margin-bottom: 1.5rem;
      background: rgba(255,255,255,0.1);
      border-radius: 8px;
      transition: transform 0.3s ease;
    }
    
    .award-item:hover {
      transform: translateX(10px);
    }
    
    .award-item h4 {
      color: var(--pink);
      font-size: 1.3rem;
      margin-bottom: 1rem;
    }
    
    .award-item p {
      color: var(--white);
      margin-bottom: 0.5rem;
    }
    
    .regional-performance {
      margin-top: 2rem;
      padding: 1rem;
    }
    
    .region-stats {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 1.5rem;
      margin-top: 1rem;
    }
    
    .region-stat {
      background: rgba(255,255,255,0.1);
      padding: 1.5rem;
      border-radius: 8px;
      transition: transform 0.3s ease;
    }
    
    .region-stat:hover {
      transform: translateY(-5px);
    }
    
    .region-stat h4 {
      color: var(--pink);
      font-size: 1.2rem;
      margin-bottom: 1rem;
    }
    
    .region-stat p {
      color: var(--white);
      margin-bottom: 0.5rem;
    }
    
    .production-gallery {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
      gap: 2rem;
      margin: 2rem 0;
    }
    
    .gallery-item {
      background: rgba(255,255,255,0.1);
      padding: 1.5rem;
      border-radius: 8px;
      transition: all 0.3s ease;
    }
    
    .gallery-item:hover {
      transform: scale(1.02);
      background: rgba(255,255,255,0.15);
    }
    
    .gallery-item h4 {
      color: var(--pink);
      font-size: 1.2rem;
      margin-bottom: 1rem;
    }
    
    .gallery-item p {
      color: var(--white);
      margin-bottom: 0.5rem;
      font-size: 1.1rem;
    }
    
    .trivia-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
      gap: 2rem;
      margin-top: 2rem;
    }
    
    .trivia-card {
      background: var(--card-bg);
      padding: 2rem;
      border-radius: 10px;
      transition: var(--transition);
    }
    
    .trivia-card:hover {
      transform: translateY(-5px);
      background: var(--card-hover);
    }
    
    .trivia-list li {
      margin-bottom: 1rem;
      padding-left: 1.5rem;
      position: relative;
    }
    
    .trivia-list li:before {
      content: '•';
      position: absolute;
      left: 0;
      color: var(--pink);
    }
    
    .mechanics-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(350px, 1fr));
      gap: 2rem;
      margin-top: 2rem;
    }
    
    .mechanics-card {
      background: var(--card-bg);
      padding: 2rem;
      border-radius: 10px;
    }
    
    .calculator select {
      width: 100%;
      padding: 1rem;
      margin-bottom: 1rem;
      background: rgba(255,255,255,0.1);
      border: 1px solid rgba(255,255,255,0.2);
      border-radius: 5px;
      color: var(--white);
    }
    
    .odds-display {
      text-align: center;
    }
    
    .odds-meter {
      height: 20px;
      background: rgba(255,255,255,0.1);
      border-radius: 10px;
      margin: 1rem 0;
      overflow: hidden;
    }
    
    .meter-fill {
      height: 100%;
      width: 0%;
      background: var(--gradient-primary);
      transition: width 0.8s ease;
    }
    
    .odds-text {
      font-size: 1.2rem;
      color: var(--white);
    }
    
    .stats-overlay {
      position: fixed;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      background: rgba(0,0,0,0.95);
      z-index: 2000;
      display: none;
      padding: 2rem;
      overflow-y: auto;
    }
    
    .global-stats-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(400px, 1fr));
      gap: 2rem;
      margin-top: 2rem;
    }
    
    .stat-block {
      background: rgba(255,255,255,0.1);
      border-radius: 10px;
      padding: 1.5rem;
    }
    
    .chart-container {
      height: 300px;
      margin-top: 1rem;
    }
    
    .close-stats {
      position: absolute;
      top: 1rem;
      right: 1rem;
      background: none;
      border: none;
      color: var(--white);
      font-size: 2rem;
      cursor: pointer;
    }
    
    .game-card {
      transition: transform 0.3s cubic-bezier(0.34, 1.56, 0.64, 1);
    }
    
    .game-card:hover {
      transform: scale(1.03) translateY(-10px);
    }
    
    .stat-block {
      transition: transform 0.3s ease, box-shadow 0.3s ease;
    }
    
    .stat-block:hover {
      transform: translateY(-5px);
      box-shadow: 0 10px 30px rgba(255,104,181,0.2);
    }
    
    .infographic-container {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
      gap: 2rem;
      padding: 2rem;
    }
    
    .data-point {
      position: relative;
      width: 120px;
      height: 120px;
      margin: 0 auto;
    }
    
    .circular-progress {
      width: 120px;
      height: 120px;
      transform: rotate(-90deg);
    }
    
    .progress-bg {
      fill: none;
      stroke: rgba(255,255,255,0.1);
      stroke-width: 8px;
    }
    
    .progress-bar {
      fill: none;
      stroke: var(--pink);
      stroke-width: 8px;
      stroke-dasharray: 339.292;
      stroke-dashoffset: 339.292;
      transition: stroke-dashoffset 1.5s ease;
    }
    
    .data-content {
      position: absolute;
      top: 50%;
      left: 50%;
      transform: translate(-50%, -50%);
      text-align: center;
    }
    
    .data-number {
      font-size: 1.8rem;
      font-weight: bold;
      color: var(--pink);
      display: block;
    }
    
    .data-label {
      font-size: 0.9rem;
      color: var(--white);
      display: block;
      margin-top: 0.5rem;
    }
    
    .character-card, .game-card, .theory-card {
      transform-style: preserve-3d;
      perspective: 1000px;
    }
    
    .character-card:hover, .game-card:hover, .theory-card:hover {
      transform: translateY(-5px) rotateX(5deg) rotateY(5deg);
    }
    
    .stat-block, .award-item {
      background: rgba(255,255,255,0.05);
      backdrop-filter: blur(10px);
      -webkit-backdrop-filter: blur(10px);
      border: 1px solid rgba(255,255,255,0.1);
    }
    
    .timeline-container {
      position: relative;
      padding: 2rem 0;
      margin: 3rem 0;
    }
    
    .timeline-line {
      position: absolute;
      left: 50%;
      top: 0;
      bottom: 0;
      width: 2px;
      background: var(--gradient-primary);
    }
    
    .timeline-event {
      position: relative;
      margin: 2rem 0;
      opacity: 0;
      transform: translateX(-20px);
      transition: all 0.5s ease;
    }
    
    .event-dot {
      position: absolute;
      left: 50%;
      width: 20px;
      height: 20px;
      background: var(--pink);
      border-radius: 50%;
      transform: translate(-50%, -50%);
    }
    
    .event-content {
      width: 45%;
      padding: 1.5rem;
      background: rgba(255,255,255,0.05);
      backdrop-filter: blur(10px);
      border-radius: 10px;
      margin-left: 55%;
    }
    
    .timeline-event:nth-child(even) .event-content {
      margin-left: 0;
      margin-right: 55%;
    }
    
    .vis-container {
      background: rgba(255,255,255,0.05);
      border-radius: 15px;
      padding: 2rem;
      margin: 2rem 0;
    }
    
    .vis-controls {
      display: flex;
      gap: 1rem;
      margin-bottom: 2rem;
      flex-wrap: wrap;
    }
    
    .vis-controls select {
      padding: 0.5rem 1rem;
      background: rgba(255,255,255,0.1);
      border: 1px solid rgba(255,255,255,0.2);
      border-radius: 5px;
      color: var(--white);
    }
    
    .vis-canvas {
      height: 400px;
      position: relative;
    }
    
    .vis-filters {
      display: flex;
      gap: 0.5rem;
    }
    
    .game-card:hover::before {
      content: '';
      position: absolute;
      inset: -2px;
      border-radius: 12px;
      background: var(--gradient-primary);
      z-index: -1;
      animation: borderGlow 1.5s ease-in-out infinite;
    }
    
    @keyframes borderGlow {
      0%, 100% { opacity: 0.5; }
      50% { opacity: 1; }
    }
    
    .stat-block:hover .chart-container {
      transform: scale(1.02);
      transition: transform 0.3s ease;
    }
    
    .fade-up {
      opacity: 0;
      transform: translateY(30px);
      transition: all 0.6s cubic-bezier(0.4, 0, 0.2, 1);
    }
    
    .fade-up.visible {
      opacity: 1;
      transform: translateY(0);
    }
    
    .preview-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
      gap: 2rem;
      margin-top: 2rem;
    }
    
    .preview-card {
      background: var(--card-bg);
      border-radius: 15px;
      padding: 2rem;
      transition: transform 0.3s ease;
    }
    
    .preview-card:hover {
      transform: translateY(-5px);
    }
    
    .cast-list {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
      gap: 1.5rem;
      margin-top: 1rem;
    }
    
    .cast-member {
      text-align: center;
    }
    
    .cast-member img {
      width: 150px;
      height: 150px;
      border-radius: 50%;
      object-fit: cover;
      margin-bottom: 1rem;
    }
    
    .timeline {
      margin-top: 1rem;
    }
    
    .timeline-item {
      padding: 1rem 0;
      border-left: 2px solid var(--pink);
      margin-left: 1rem;
      position: relative;
    }
    
    .timeline-item::before {
      content: '';
      position: absolute;
      left: -0.5rem;
      top: 1.5rem;
      width: 1rem;
      height: 1rem;
      background: var(--pink);
      border-radius: 50%;
    }
    
    .date {
      font-weight: bold;
      color: var(--pink);
      display: block;
      margin-bottom: 0.5rem;
    }
    
    .countdown {
      display: flex;
      justify-content: space-around;
      margin-top: 2rem;
      background: rgba(255,255,255,0.05);
      padding: 1.5rem;
      border-radius: 10px;
    }
    
    .countdown-item {
      text-align: center;
    }
    
    .countdown-item .number {
      font-size: 2.5rem;
      font-weight: bold;
      color: var(--pink);
      display: block;
    }
    
    .countdown-item .label {
      font-size: 0.9rem;
      color: var(--white);
    }
    
    .cast-modal {
      position: fixed;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      background: rgba(0,0,0,0.9);
      display: flex;
      align-items: center;
      justify-content: center;
      z-index: 1000;
    }
    
    .modal-content {
      background: var(--card-bg);
      padding: 2rem;
      border-radius: 15px;
      max-width: 500px;
      position: relative;
    }
    
    .close-modal {
      position: absolute;
      top: 1rem;
      right: 1rem;
      background: none;
      border: none;
      color: var(--white);
      cursor: pointer;
      font-size: 1.5rem;
    }
    
    .game-stats {
      margin-top: 1rem;
      padding: 1rem;
      background: rgba(255,255,255,0.05);
      border-radius: 8px;
    }
    
    .game-stats ul ul {
      margin-left: 1rem;
      margin-top: 0.5rem;
    }
    
    .game-history {
      margin-top: 1rem;
      padding: 0.5rem;
    }
    
    .game-history li {
      margin-bottom: 0.5rem;
      padding: 0.5rem;
      background: rgba(255,255,255,0.05);
      border-radius: 4px;
    }
    
    .game-history small {
      color: var(--gray);
      font-style: italic;
    }
    
    .fan-content-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
      gap: 2rem;
      margin-top: 2rem;
    }
    
    .fan-content-card {
      background: var(--card-bg);
      padding: 2rem;
      border-radius: 10px;
      transition: var(--transition);
    }
    
    .fan-content-card:hover {
      transform: translateY(-5px);
      background: var(--card-hover);
    }
    
    .story-grid {
      display: grid;
      gap: 1rem;
      margin: 1rem 0;
    }
    
    .story-entry {
      padding: 1rem;
      background: rgba(255,255,255,0.05);
      border-radius: 8px;
      transition: transform 0.3s ease;
    }
    
    .story-entry:hover {
      transform: translateX(10px);
    }
    
    .theory-filters {
      display: flex;
      gap: 1rem;
      margin-bottom: 1rem;
    }
    
    .theory-list {
      max-height: 500px;
      overflow-y: auto;
      padding-right: 1rem;
    }
    
    .theory-entry {
      padding: 1rem;
      margin-bottom: 1rem;
      background: rgba(255,255,255,0.05);
      border-radius: 8px;
      transition: transform 0.3s ease;
    }
    
    .theory-entry:hover {
      transform: translateX(10px);
    }
    
    .submit-story-btn {
      background: var(--gradient-primary);
      color: var(--white);
      border: none;
      padding: 1rem 2rem;
      border-radius: 5px;
      cursor: pointer;
      margin-top: 1rem;
      transition: transform 0.3s ease;
    }
    
    .submit-story-btn:hover {
      transform: translateY(-2px);
    }
    
    .submit-modal {
      position: fixed;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      background: rgba(0,0,0,0.9);
      display: flex;
      align-items: center;
      justify-content: center;
      z-index: 1000;
    }
    
    .modal-content {
      background: var(--card-bg);
      padding: 2rem;
      border-radius: 10px;
      max-width: 500px;
      width: 90%;
    }
    
    .modal-content input,
    .modal-content textarea {
      width: 100%;
      padding: 0.8rem;
      margin-bottom: 1rem;
      background: rgba(255,255,255,0.1);
      border: 1px solid rgba(255,255,255,0.2);
      border-radius: 5px;
      color: var(--white);
    }
    
    .modal-content textarea {
      height: 200px;
      resize: vertical;
    }
    
    .close-modal {
      position: absolute;
      top: 1rem;
      right: 1rem;
      background: none;
      border: none;
      color: var(--white);
      font-size: 1.5rem;
      cursor: pointer;
    }
    
    .collectibles-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
      gap: 2rem;
      margin: 2rem 0;
    }
    
    .collectible-card {
      background: var(--card-bg);
      padding: 2rem;
      border-radius: 10px;
      transition: var(--transition);
    }
    
    .collectible-card:hover {
      transform: translateY(-5px);
      background: var(--card-hover);
    }
    
    .collectible-item,
    .nft-item {
      padding: 1.5rem;
      margin: 1rem 0;
      background: rgba(255,255,255,0.05);
      border-radius: 8px;
    }
    
    .collect-btn,
    .mint-btn {
      background: var(--gradient-primary);
      color: var(--white);
      border: none;
      padding: 0.8rem 1.5rem;
      border-radius: 25px;
      cursor: pointer;
      margin-top: 1rem;
      transition: var(--transition);
    }
    
    .collect-btn:hover,
    .mint-btn:hover {
      transform: translateY(-2px);
      box-shadow: 0 4px 15px rgba(255,104,181,0.3);
    }
    
    .trading-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 1.5rem;
      margin: 2rem 0;
    }
    
    .list-item-btn {
      background: var(--gradient-primary);
      color: var(--white);
      border: none;
      padding: 1rem 2rem;
      border-radius: 25px;
      cursor: pointer;
      margin: 2rem auto;
      display: block;
      transition: var(--transition);
    }
    
    .list-item-btn:hover {
      transform: translateY(-2px);
      box-shadow: 0 4px 15px rgba(255,104,181,0.3);
    }
    
    .vote-grid {
      display: grid;
      grid-template-columns: repeat(2, 1fr);
      gap: 2rem;
      margin: 3rem 0;
    }
    
    .large-vote {
      display: flex;
      flex-direction: column;
      align-items: center;
      gap: 1rem;
      padding: 2rem;
      background: rgba(255,255,255,0.1);
      border: none;
      border-radius: 15px;
      cursor: pointer;
      transition: transform 0.3s ease, background-color 0.3s ease;
    }
    
    .large-vote:hover {
      transform: translateY(-5px);
      background: rgba(255,255,255,0.2);
    }
    
    .large-vote.positive {
      border: 1px solid rgba(0,255,0,0.3);
    }
    
    .large-vote.negative {
      border: 1px solid rgba(255,0,0,0.3);
    }
    
    .vote-icon {
      font-size: 3rem;
    }
    
    .vote-label {
      font-size: 1.5rem;
      color: var(--white);
    }
    
    .vote-count {
      font-size: 1.2rem;
      color: var(--gray);
    }
    
    .recent-votes {
      margin-top: 4rem;
    }
    
    .vote-comment {
      display: flex;
      align-items: center;
      gap: 1rem;
      padding: 1rem;
      margin: 1rem 0;
      background: rgba(255,255,255,0.05);
      border-radius: 10px;
    }
    
    .vote-avatar {
      width: 48px;
      height: 48px;
      border-radius: 50%;
    }
    
    .vote-details {
      flex-grow: 1;
    }
    
    .voter-name {
      font-weight: bold;
      color: var(--pink);
    }
    
    .vote-text {
      margin: 0.5rem 0;
    }
    
    .vote-time {
      font-size: 0.9rem;
      color: var(--gray);
    }
    
    .vote-indicator {
      font-size: 1.5rem;
    }
    </style>
    <meta name="description" content="Everything you need to know about Squid Game - cast, episodes, season 2, games explained, ending, behind the scenes. Find answers to your Squid Game questions.">
    <meta name="keywords" content="Squid Game explained, Squid Game cast, Squid Game episodes, Squid Game season 2, Squid Game ending explained, Squid Game games list, Squid Game behind the scenes, Squid Game actors, how to watch Squid Game, what happens in Squid Game">
    <meta property="og:title" content="Squid Game Guide: Everything You Need to Know | Episodes, Cast &amp; Season 2">
    <meta property="og:description" content="Complete guide to Squid Game - Find out about the cast, episodes, games, ending explained and season 2. All your Squid Game questions answered.">
    <script type="module">
      import 'https://unpkg.com/smoothscroll-polyfill@0.4.4/dist/smoothscroll.min.js';
    </script>
    <script>
    // Add voting functionality
    document.querySelectorAll('.vote-btn').forEach(button => {
      button.addEventListener('click', function() {
        const voteCount = this.parentElement.querySelector('.vote-count');
        const currentCount = parseInt(voteCount.textContent);
        
        if (this.classList.contains('upvote')) {
          voteCount.textContent = currentCount + 1;
        } else if (this.classList.contains('downvote')) {
          voteCount.textContent = currentCount - 1;
        }
        
        // Disable buttons after voting
        this.parentElement.querySelectorAll('.vote-btn').forEach(btn => {
          btn.disabled = true;
        });
      });
    });
    
    // Add forum post functionality
    document.querySelector('.post-btn').addEventListener('click', function() {
      const forumPosts = document.querySelector('.forum-posts');
      const postTemplate = `
        <div class="forum-post">
          <h4>Your Theory</h4>
          <textarea placeholder="Share your thoughts..."></textarea>
          <button class="submit-theory">Submit</button>
        </div>
      `;
      forumPosts.insertAdjacentHTML('beforeend', postTemplate);
    });
    
    // Add smooth scrolling for navigation
    document.querySelectorAll('.main-nav a').forEach(anchor => {
      anchor.addEventListener('click', function(e) {
        e.preventDefault();
        const section = document.querySelector(this.getAttribute('href'));
        section.scrollIntoView({ behavior: 'smooth' });
      });
    });
    
    // Handle fan art submission
    document.querySelector('.submit-art-btn').addEventListener('click', function() {
      const form = document.querySelector('.submit-art-form');
      form.style.display = form.style.display === 'none' ? 'block' : 'none';
    });
    
    document.getElementById('artForm').addEventListener('submit', function(e) {
      e.preventDefault();
      // Handle form submission here
      alert('Thank you for your submission! Our moderators will review it shortly.');
      this.parentElement.style.display = 'none';
    });
    </script>
    </head>
    <body>
    
    <nav class="main-nav">
      <ul>
        <li><a href="#synopsis">Synopsis &amp; Episodes</a></li>
        <li><a href="#games">Games</a></li>
        <li><a href="#characters">Characters</a></li>
        <!-- <li><a href="#season2">Season 2</a></li> -->
        <li><a href="#theories">Fan Theories</a></li>
        <!-- <li><a href="#merchandise">Merchandise &amp; Art</a></li> -->
        <!-- <li><a href="#behind-scenes">Behind the Scenes</a></li> -->
        <li><a href="#impact">Cultural Impact</a></li>
        <li><a href="#trivia">Trivia</a></li>
        <li><a href="#game-mechanics">Game Mechanics</a></li>
        <li><a href="#community">Community</a></li>
        <li><a href="#fan-content">Fan Content</a></li>
        <li><a href="#extras">Collector's Corner</a></li>
      </ul>
    </nav>
    
    <section class="hero-section voting-hero">
      <div class="hero-content voting-content">
        <h1 class="hero-title">Vote: How Do You Feel About Season 2's Ending?</h1>
        <div class="vote-grid">
          <button class="vote-btn large-vote positive">
            <span class="vote-icon">👍</span>
            <span class="vote-label">Loved it!</span>
            <span class="vote-count" id="positiveCount">324</span>
          </button>
          <button class="vote-btn large-vote negative">
            <span class="vote-icon">👎</span>  
            <span class="vote-label">Hated it!</span>
            <span class="vote-count" id="negativeCount">156</span>
          </button>
        </div>
    
        <div class="sentiment-meter">
          <h3>Current Fan Sentiment</h3>
          <div class="meter">
            <div class="meter-fill" id="sentimentFill"></div>
            <span class="meter-label">67% Positive</span>
          </div>
        </div>
    
        <div class="recent-votes">
          <h3>Recent Votes & Comments</h3>
          <div class="vote-comment">
            <img src="https://playgamesnow.org/squidgames/public/MoDen31_" class="vote-avatar">
            <div class="vote-details">
              <span class="voter-name">MoDen31_</span>
              <p class="vote-text">"The ending was brilliant! Really tied everything together."</p>
              <span class="vote-time">2 minutes ago</span>
            </div>
            <span class="vote-indicator positive">👍</span>
          </div>
    
          <div class="vote-comment">
            <img src="https://playgamesnow.org/squidgames/public/ZergGirrl" class="vote-avatar">
            <div class="vote-details">
              <span class="voter-name">ZergGirrl</span>
              <p class="vote-text">"Was great until that ending... so disappointed!"</p>
              <span class="vote-time">5 minutes ago</span>
            </div>
            <span class="vote-indicator negative">👎</span>
          </div>
    
          <div class="vote-comment">
            <img src="https://playgamesnow.org/squidgames/public/TotallyNotMark" class="vote-avatar">
            <div class="vote-details">
              <span class="voter-name">Mark</span>
              <p class="vote-text">"Best ending they could have done. Perfect setup for season 3!"</p>
              <span class="vote-time">10 minutes ago</span>
            </div>
            <span class="vote-indicator positive">👍</span>
          </div>
        </div>
      </div>
    </section>
    
    <div class="tv-series-container">
      <section id="synopsis" class="content-section">
        <h2 class="section-title">Synopsis &amp; Episode Guide</h2>
        <div class="episode-grid">
          <div class="episode-card">
            <h3 class="episode-title">Episode 1: Red Light, Green Light</h3>
            <p class="episode-rating">Rating: 9.2/10</p>
            <p class="episode-text">
              We meet Seong Gi-hun, a divorced father struggling with debt. After accepting an invitation to play children's games for money, he finds himself in a deadly competition with 455 other desperate players.
            </p>
            <div class="episode-details">
              <h4>Key Moments</h4>
              <ul>
                <li>Introduction of main character Seong Gi-hun</li>
                <li>The first deadly game reveal</li>
                <li>Formation of initial alliances</li>
              </ul>
              <h4>Behind the Scenes</h4>
              <p>The giant robot doll was actually built to scale and later displayed in a mall in Philippines.</p>
            </div>
            <button class="expand-btn">Show More</button>
          </div>
          <div class="episode-card">
            <h3 class="episode-title">Episode 2: Hell</h3>
            <p class="episode-rating">Rating: 9.1/10</p>
            <p class="episode-text">
              After witnessing the brutality of the first game, players vote to end the games. However, faced with harsh realities of their lives, many return to compete again.
            </p>
            <div class="episode-details">
              <h4>Key Moments</h4>
              <ul>
                <li>Introduction of main character Seong Gi-hun</li>
                <li>The first deadly game reveal</li>
                <li>Formation of initial alliances</li>
              </ul>
              <h4>Behind the Scenes</h4>
              <p>The giant robot doll was actually built to scale and later displayed in a mall in Philippines.</p>
            </div>
            <button class="expand-btn">Show More</button>
          </div>
          <div class="episode-card">
            <h3 class="episode-title">Episode 3: The Man with the Umbrella</h3>
            <p class="episode-rating">Rating: 9.3/10</p>
            <p class="episode-text">
              Players must complete a deadly version of the honeycomb/dalgona challenge, where choosing the wrong shape could mean instant elimination.
            </p>
            <div class="episode-details">
              <h4>Key Moments</h4>
              <ul>
                <li>Introduction of main character Seong Gi-hun</li>
                <li>The first deadly game reveal</li>
                <li>Formation of initial alliances</li>
              </ul>
              <h4>Behind the Scenes</h4>
              <p>The giant robot doll was actually built to scale and later displayed in a mall in Philippines.</p>
            </div>
            <button class="expand-btn">Show More</button>
          </div>
          <div class="episode-card">
            <h3 class="episode-title">Episode 4: Stick to the Team</h3>
            <p class="episode-rating">Rating: 9.0/10</p>
            <p class="episode-text">
              Teams form for the tug-of-war game, while alliances and betrayals emerge. Players realize trust is both essential and dangerous.
            </p>
            <div class="episode-details">
              <h4>Key Moments</h4>
              <ul>
                <li>Introduction of main character Seong Gi-hun</li>
                <li>The first deadly game reveal</li>
                <li>Formation of initial alliances</li>
              </ul>
              <h4>Behind the Scenes</h4>
              <p>The giant robot doll was actually built to scale and later displayed in a mall in Philippines.</p>
            </div>
            <button class="expand-btn">Show More</button>
          </div>
        </div>
      </section>
    
      <section id="games" class="content-section">
        <h2 class="section-title">Games Explained</h2>
        <div class="games-grid">
          <div class="game-card">
            <h3>Red Light, Green Light</h3>
            <div class="game-details">
              <h4>Rules</h4>
              <ul>
                <li>Move during "Green Light"</li>
                <li>Freeze during "Red Light"</li>
                <li>Reach finish line within 5 minutes</li>
                <li>Any movement during "Red Light" results in elimination</li>
              </ul>
              <h4>Strategy Tips</h4>
              <ul>
                <li>Stay behind others initially</li>
                <li>Move steadily, don't rush</li>
                <li>Watch for the doll's head movement timing</li>
              </ul>
            </div>
          </div>
          <div class="game-card">
            <h3>Honeycomb/Dalgona</h3>
            <div class="game-details">
              <h4>Rules</h4>
              <ul>
                <li>Extract shape without breaking it</li>
                <li>Use provided needle only</li>
                <li>Complete within 10 minutes</li>
              </ul>
              <h4>Strategy Tips</h4>
              <ul>
                <li>Choose simpler shapes (triangle, circle)</li>
                <li>Lick the honeycomb to dissolve it</li>
                <li>Work from edges inward</li>
              </ul>
            </div>
          </div>
          <div class="game-card">
            <h3>Tug of War</h3>
            <div class="game-details">
              <h4>Rules</h4>
              <ul>
                <li>Teams of 10 players</li>
                <li>3 minute time limit</li>
                <li>Losing team is eliminated</li>
                <li>No outside tools/supports allowed</li>
              </ul>
              <h4>Strategy Tips</h4>
              <ul>
                <li>Position stronger players in back</li>
                <li>Coordinate timing of pulls</li>
                <li>Maintain steady tension</li>
                <li>Listen to team leader</li>
              </ul>
              <h4>Key Moments</h4>
              <ul>
                <li>Oh Il-nam's strategy reveal</li>
                <li>Team 4's dramatic victory</li>
                <li>Final match tension</li>
              </ul>
            </div>
          </div>
          <div class="game-card">
            <h3>Glass Bridge</h3>
            <div class="game-details">
              <h4>Rules</h4> 
              <ul>
                <li>Cross bridge in order by number</li>
                <li>Choose between left/right glass panels</li>
                <li>One is tempered, one breaks</li>
                <li>16 minutes to cross</li>
              </ul>
              <h4>Strategy Tips</h4>
              <ul>
                <li>Study glass properties</li>
                <li>Watch reflections/patterns</li>
                <li>Test panels if possible</li>
                <li>Keep track of successful paths</li>
              </ul>
              <h4>Notable Deaths</h4>
              <ul>
                <li>Player 096 - First jumper</li>
                <li>Player 321 - Time expired</li>
                <li>Player 229 - Panel shatter</li>
              </ul>
            </div>
          </div>
        </div>
      </section>
    
      <section id="characters" class="content-section">
        <h2 class="section-title">Character Profiles</h2>
        
        <div class="character-filter">
          <input type="number" class="character-search" placeholder="Enter player number...">
          <button class="filter-btn" id="next-chars">Next Characters</button>
          <div class="search-filters">
            <span class="filter-tag active">All</span>
            <span class="filter-tag">Main Characters</span>
            <span class="filter-tag">Survivors</span>
            <span class="filter-tag">Guards</span>
            <span class="filter-tag">VIPs</span>
          </div>
        </div>
    
        <div class="character-grid">
          <!-- First 24 characters -->
          <div class="character-card">
            <h3 class="character-name">Seong Gi-hun (456)</h3>
            <p class="character-description">A gambling addict and chauffeur who enters the game to pay off his debts.</p>
            <div class="character-stats">
              <span>Status: Alive</span>
              <span>Age: 40</span>
              <span>Occupation: Chauffeur</span>
              <span>Player Type: Human</span>
            </div>
            <div class="character-bio">
              <h4>Background</h4>
              <p>Seong Gi-hun was born in Seoul, South Korea. He has a daughter who lives with his ex-wife.</p>
              <h4>Character Arc</h4>
              <p>Seong Gi-hun starts as a desperate and weak player, but as the game progresses, he becomes more confident and determined to survive.</p>
            </div>
            <div class="character-additional-info">
              <h4>Relationships</h4>
              <p>Seong Gi-hun forms close bonds with other players, including Kang Sae-byeok and Oh Il-nam.</p>
              <h4>Key Episodes</h4>
              <p>Episode 1, Episode 3, Episode 6</p>
              <h4>Memorable Quotes</h4>
              <p>"I'm not a player, I'm a human being."</p>
            </div>
            <button class="expand-btn">Show Bio</button>
            <div class="game-history">
              <h4>Game Performance</h4>
              <ul>
                <li>Red Light, Green Light: Survived</li>
                <li>Honeycomb/Dalgona: Survived</li>
                <li>Tug of War: Survived</li>
                <li>Glass Bridge: Survived</li>
              </ul>
            </div>
          </div>
          <div class="character-card">
            <h3 class="character-name">Cho Sang-woo (218)</h3>
            <p class="character-description">A former investment banker wanted for stealing from clients.</p>
            <div class="character-stats">
              <span>Status: Deceased</span>
              <span>Age: 35</span>
              <span>Occupation: Investment Banker</span>
              <span>Player Type: Human</span>
            </div>
            <div class="character-bio">
              <h4>Background</h4>
              <p>Cho Sang-woo was born in Busan, South Korea. He has a troubled past and is known for his ruthlessness.</p>
              <h4>Character Arc</h4>
              <p>Cho Sang-woo starts as a cunning and manipulative player, but as the game progresses, his true nature is revealed.</p>
            </div>
            <div class="character-additional-info">
              <h4>Relationships</h4>
              <p>Cho Sang-woo forms alliances with other players, but his true intentions are often questionable.</p>
              <h4>Key Episodes</h4>
              <p>Episode 2, Episode 4, Episode 7</p>
              <h4>Memorable Quotes</h4>
              <p>"I'm not playing for fun, I'm playing to win."</p>
            </div>
            <button class="expand-btn">Show Bio</button>
            <div class="game-history">
              <h4>Game Performance</h4>
              <ul>
                <li>Red Light, Green Light: Survived</li>
                <li>Honeycomb/Dalgona: Survived</li>
                <li>Tug of War: Survived</li>
                <li>Glass Bridge: Eliminated</li>
              </ul>
            </div>
          </div>
          <div class="character-card">
            <h3 class="character-name">Kang Sae-byeok (067)</h3>
            <p class="character-description">A North Korean defector playing to save her family.</p>
            <div class="character-stats">
              <span>Status: Deceased</span>
              <span>Age: 25</span>
              <span>Occupation: Pickpocket</span>
              <span>Player Type: Human</span>
            </div>
            <div class="character-bio">
              <h4>Background</h4>
              <p>Kang Sae-byeok was born in North Korea. She defected to South Korea and is playing to save her brother.</p>
              <h4>Character Arc</h4>
              <p>Kang Sae-byeok starts as a timid and reserved player, but as the game progresses, she becomes more confident and determined to survive.</p>
            </div>
            <div class="character-additional-info">
              <h4>Relationships</h4>
              <p>Kang Sae-byeok forms a close bond with Seong Gi-hun and Oh Il-nam.</p>
              <h4>Key Episodes</h4>
              <p>Episode 3, Episode 5, Episode 8</p>
              <h4>Memorable Quotes</h4>
              <p>"I'm not afraid of death, I'm afraid of losing my family."</p>
            </div>
            <button class="expand-btn">Show Bio</button>
            <div class="game-history">
              <h4>Game Performance</h4>
              <ul>
                <li>Red Light, Green Light: Survived</li>
                <li>Honeycomb/Dalgona: Survived</li>
                <li>Tug of War: Survived</li>
                <li>Glass Bridge: Eliminated</li>
              </ul>
            </div>
          </div>
          <div class="character-card">
            <h3 class="character-name">Oh Il-nam (001)</h3>
            <p class="character-description">An elderly man with a brain tumor who wants to feel alive again.</p>
            <div class="character-stats">
              <span>Status: Deceased</span>
              <span>Age: 70</span>
              <span>Occupation: Retiree</span>
              <span>Player Type: Human</span>
            </div>
            <div class="character-bio">
              <h4>Background</h4>
              <p>Oh Il-nam was born in Seoul, South Korea. He has a brain tumor and is playing to feel alive again.</p>
              <h4>Character Arc</h4>
              <p>Oh Il-nam starts as a weak and old player, but as the game progresses, he becomes more determined to survive.</p>
            </div>
            <div class="character-additional-info">
              <h4>Relationships</h4>
              <p>Oh Il-nam forms a close bond with Seong Gi-hun and Kang Sae-byeok.</p>
              <h4>Key Episodes</h4>
              <p>Episode 1, Episode 4, Episode 6</p>
              <h4>Memorable Quotes</h4>
              <p>"I'm not playing for money, I'm playing for life."</p>
            </div>
            <button class="expand-btn">Show Bio</button>
            <div class="game-history">
              <h4>Game Performance</h4>
              <ul>
                <li>Red Light, Green Light: Survived</li>
                <li>Honeycomb/Dalgona: Survived</li>
                <li>Tug of War: Survived</li>
                <li>Glass Bridge: Survived</li>
              </ul>
            </div>
          </div>
          <!-- Continue with 20 more character cards -->
        </div>
        <div class="pagination">
          <button class="page-btn active">1</button>
          <button class="page-btn">2</button>
          <button class="page-btn">3</button>
        </div>
      </section>
    
      <section id="theories" class="content-section">
        <h2 class="section-title">Fan Theories &amp; Discussions</h2>
        <div class="theory-grid">
          <div class="theory-card">
            <h3 class="theory-title">The Front Man's Identity</h3>
            <p class="theory-text">
              Many fans theorize about why the Front Man chose to run the games after winning them. Evidence suggests his disillusionment with society led him to believe the games provide a &quot;fair&quot; chance.
            </p>
            <div class="theory-votes">
              <button class="vote-btn upvote">Agree</button>
              <span class="vote-count">152</span>
              <button class="vote-btn downvote">Disagree</button>
            </div>
          </div>
          <div class="theory-card">
            <h3 class="theory-title">Color Symbolism</h3>
            <p class="theory-text">
              The red and blue colors throughout the series represent choices and fate. Workers chose red cards, players blue - symbolizing their roles in the game of life.
            </p>
            <div class="theory-votes">
              <button class="vote-btn upvote">Agree</button>
              <span class="vote-count">238</span>
              <button class="vote-btn downvote">Disagree</button>
            </div>
          </div>
          <div class="theory-card">
            <h3 class="theory-title">The Games' True Purpose</h3>
            <p class="theory-text">
              Beyond entertainment for the rich, the games serve as a social experiment about human nature under capitalism and extreme pressure.
            </p>
            <div class="theory-votes">
              <button class="vote-btn upvote">Agree</button>
              <span class="vote-count">427</span>
              <button class="vote-btn downvote">Disagree</button>
            </div>
          </div>
        </div>
        <div class="discussion-forum">
          <h3>Join the Discussion</h3>
          <div class="forum-posts">
            <!-- Discussion posts will be dynamically loaded -->
          </div>
          <button class="post-btn">Share Your Theory</button>
        </div>
      </section>
    
      <section id="season2" class="content-section">
        <h2 class="section-title">Season 2 Preview</h2>
        <div class="season2-grid">
          <div class="season2-card">
            <h3>Release Information</h3>
            <p>Expected Release: Late 2024</p>
            <p>Number of Episodes: 8</p>
            <p>Status: In Production</p>
          </div>
          <div class="season2-card">
            <h3>Confirmed Cast</h3>
            <ul>
              <li>Lee Jung-jae as Seong Gi-hun</li>
              <li>Lee Byung-hun as The Front Man</li>
              <li>Wi Ha-jun as Hwang Jun-ho</li>
              <!-- New cast members -->
              <li>Yim Si-wan - New Character</li>
              <li>Kang Ha-neul - New Character</li>
              <li>Park Gyu-young - New Character</li>
            </ul>
          </div>
          <div class="season2-card">
            <h3>What to Expect</h3>
            <ul>
              <li>New Games: Traditional Korean children's games will feature</li>
              <li>Gi-hun's Revenge Story: Continuing from season 1's ending</li>
              <li>Front Man's Background: More details about his past</li>
              <li>New Locations: Beyond the original game facility</li>
            </ul>
          </div>
        </div>
      </section>
    
      <section id="merchandise" class="content-section">
        <h2 class="section-title">Merchandise &amp; Fan Art</h2>
        <div class="merch-grid">
          <div class="merch-card">
            <h3 class="merch-title">Official Collection</h3>
            <div class="merch-items">
              <div class="merch-item">
                <h4>Player 456 Jacket</h4>
                <p class="merch-price">&#x24;45.99</p>
                <a href="https://netflix.shop/squidgame" class="buy-btn">Shop Now</a>
              </div>
              <div class="merch-item">
                <h4>Dalgona Cookie Kit</h4>
                <p class="merch-price">$19.99</p>
                <a href="https://netflix.shop/squidgame/dalgona" class="buy-btn">Shop Now</a>
              </div>
              <div class="merch-item">
                <h4>Guard Mask</h4>
                <p class="merch-price">$29.99</p>
                <a href="https://netflix.shop/squidgame/mask" class="buy-btn">Shop Now</a>
              </div>
              <!-- More merch items -->
            </div>
          </div>
        </div>
        <div class="fanart-gallery">
          <h3>Featured Fan Art</h3>
          <div class="art-grid">
            <!-- Fan art items will be dynamically loaded -->
          </div>
          <button class="submit-art-btn">Submit Your Art</button>
        </div>
        <div class="submit-art-form" style="display: none;">
          <h3>Submit Your Fan Art</h3>
          <form id="artForm">
            <input type="text" placeholder="Title" required>
            <textarea placeholder="Description" required></textarea>
            <input type="file" accept="image/*" required>
            <button type="submit">Submit Art</button>
          </form>
        </div>
      </section>
    
      <section id="behind-scenes" class="content-section">
        <h2 class="section-title">Behind the Scenes</h2>
        <div class="bts-content">
          <h3>Production Details</h3>
          <p class="bts-text">Squid Game took over 10 years from concept to screen. Director Hwang Dong-hyuk first conceptualized it in 2008 but faced multiple rejections before Netflix picked it up.</p>
          
          <h3>Set Design</h3>
          <ul class="bts-list">
            <li>The giant doll from Red Light, Green Light was real and stands 3.5 meters tall</li>
            <li>The staircase set was inspired by M.C. Escher's "Relativity"</li>
            <li>Over 450 unique player uniforms were created</li>
          </ul>
    
          <div class="production-aspects">
            <div class="aspect-grid">
              <div class="aspect-card">
                <h4 class="aspect-title">Visual Effects</h4>
                <p class="aspect-text">While many sets were practical builds, CGI enhanced the scale of locations like the playground and sleeping hall.</p>
              </div>
              <div class="aspect-card">
                <h4 class="aspect-title">Costume Design</h4>
                <p class="aspect-text">The iconic green tracksuits were chosen to contrast with the pink-suited guards and represent the players' manipulation.</p>
              </div>
            </div>
            <div class="production-gallery">
              <div class="gallery-item">
                <h4>Set Construction</h4>
                <p>Over 120,000 square feet of sets were built</p>
                <p>38,000 handmade props created</p>
                <p>456 unique player costumes designed</p>
              </div>
              <div class="gallery-item">
                <h4>Filming Stats</h4>
                <p>93 days of principal photography</p>
                <p>Over 13,000 costume pieces</p>
                <p>2,900 extras participated</p>
              </div>
              <div class="gallery-item">
                <h4>Post-Production</h4>
                <p>8 months of VFX work</p>
                <p>2,500+ VFX shots</p>
                <p>4K HDR color grading</p>
              </div>
            </div>
          </div>
    
          <div class="production-details">
            <h3>Technical Specifications</h3>
            <ul class="specs-list">
              <li>Filmed with RED Helium 8K cameras</li>
              <li>2.00:1 aspect ratio</li>
              <li>Dolby Vision HDR mastering</li>
              <li>Over 13,000 costume pieces created</li>
            </ul>
    
            <h3>Sound Design</h3>
            <ul class="sound-list">
              <li>Original score by Jung Jae-il</li>
              <li>Use of children's songs for psychological impact</li>
              <li>Foley work for game sound effects</li>
            </ul>
          </div>
          <blockquote class="bts-quote">
            "I wanted to create a sense of connection to childhood games, but with a dark twist that reflects society's competitive nature." - Hwang Dong-hyuk
          </blockquote>
        </div>
        <div class="timeline-wrapper">
          <div class="timeline-line"></div>
          <div class="timeline-item">
            <div class="timeline-dot"></div>
            <h3>2008</h3>
            <h4>Initial Concept</h4>
            <p>Hwang Dong-hyuk first conceptualizes Squid Game during financial crisis</p>
          </div>
          <div class="timeline-item">
            <div class="timeline-dot"></div>
            <h3>2009-2018</h3>
            <h4>Development Hell</h4>
            <p>Project faces multiple rejections from studios</p>
          </div>
          <div class="timeline-item">
            <div class="timeline-dot"></div>
            <h3>2019</h3>
            <h4>Netflix Acquisition</h4>
            <p>Netflix picks up the project as part of their expansion into Korean content</p>
          </div>
          <div class="timeline-item">
            <div class="timeline-dot"></div>
            <h3>2020</h3>
            <h4>Production Begins</h4>
            <p>Filming starts amid COVID-19 pandemic challenges</p>
          </div>
        </div>
      </section>
    
      <section id="impact" class="content-section">
        <h2 class="section-title">Cultural Impact & Reception</h2>
        
        <div class="statistics-container">
          <h3>Global Impact Statistics</h3>
          <div class="stat-row">
            <div class="stat-item">
              <span class="stat-number">111</span>
              <span class="stat-label">Million Views in First Month</span>
            </div>
            <div class="stat-item">
              <span class="stat-number">94</span>
              <span class="stat-label">Countries Ranked #1</span>
            </div>
            <div class="stat-item">
              <span class="stat-number">3</span>
              <span class="stat-label">Major Emmy Awards</span>
            </div>
          </div>
    
          <div class="cultural-impact-grid">
            <div class="impact-section">
              <h3>Regional Reception</h3>
              <ul class="stats-list">
                <li><span class="region">South Korea:</span> Highest-rated Netflix series</li>
                <li><span class="region">United States:</span> Most-watched non-English series</li>
                <li><span class="region">Japan:</span> Top 10 for 12 consecutive weeks</li>
              </ul>
            </div>
            
            <div class="impact-section">
              <h3>Social Media Impact</h3>
              <div class="social-metrics">
                <div class="metric-card">
                  <span class="metric-number">16.5B</span>
                  <span class="metric-label">TikTok Views</span>
                </div>
                <div class="metric-card">
                  <span class="metric-number">7.2M</span>
                  <span class="metric-label">Instagram Posts</span>
                </div>
              </div>
            </div>
            <div class="impact-section">
              <h3>Pop Culture References</h3>
              <ul class="pop-culture-list">
                <li>Halloween costumes inspired by player uniforms and guard masks</li>
                <li>Dalgona cookie challenges going viral on social media</li>
                <li>Squid Game-themed video games and mobile apps</li>
                <li>Parodies and references in TV shows and commercials</li>
              </ul>
    
              <h3>Academic Analysis</h3>
              <ul class="academic-list">
                <li>Studies on wealth inequality themes</li>
                <li>Papers analyzing Korean cultural elements</li>
                <li>Research on global content distribution</li>
              </ul>
            </div>
          </div>
        </div>
        <div class="merchandise-stats">
          <h3>Merchandise Impact</h3>
          <div class="merch-stats-grid">
            <div class="merch-stat">
              <span class="merch-number">$900M</span>
              <span class="merch-label">Global Merchandise Revenue</span>
            </div>
            <div class="merch-stat">
              <span class="merch-number">2.1M</span>
              <span class="merch-label">Official Products Sold</span>
            </div>
          </div>
        </div>
        <div class="streaming-stats">
          <h3>Streaming Performance</h3>
          <div class="platform-stats">
            <div class="platform-row">
              <span class="platform-name">Netflix</span>
              <div class="progress-bar" data-value="1.65">
                <div class="progress-fill"></div>
                <span class="progress-text">1.65B Hours Streamed</span>
              </div>
            </div>
            <div class="platform-row">
              <span class="platform-name">First Month</span>
              <div class="progress-bar" data-value="0.63">
                <div class="progress-fill"></div>
                <span class="progress-text">630M Hours Streamed</span>
              </div>
            </div>
          </div>
          <div class="regional-performance">
            <h3>Regional Performance Highlights</h3>
            <div class="region-stats">
              <div class="region-stat">
                <h4>South Korea</h4>
                <p>95% Household Penetration</p>
                <p>8.3M Unique Viewers</p>
              </div>
              <div class="region-stat">
                <h4>United States</h4>
                <p>142M Household Views</p>
                <p>Top Non-English Series</p>
              </div>
              <div class="region-stat">
                <h4>Global</h4>
                <p>Available in 31 Languages</p>
                <p>94 Countries Ranked #1</p>
              </div>
            </div>
          </div>
        </div>
        <div class="awards-timeline">
          <h3>Major Awards & Recognition</h3>
          <div class="award-item">
            <h4>Emmy Awards 2022</h4>
            <p>Outstanding Drama Series Nomination</p>
            <p>Outstanding Lead Actor - Lee Jung-jae (Winner)</p>
            <p>Outstanding Directing - Hwang Dong-hyuk (Winner)</p>
          </div>
          <div class="award-item">
            <h4>Golden Globe Awards 2022</h4>
            <p>Best Television Series – Drama (Nomination)</p>
            <p>Best Actor in a Drama Series - Lee Jung-jae (Winner)</p>
            <p>Best Supporting Actor - O Yeong-su (Winner)</p>
          </div>
          <div class="award-item">
            <h4>SAG Awards 2022</h4>
            <p>Outstanding Performance by an Ensemble (Winner)</p>
            <p>Outstanding Performance by a Male Actor - Lee Jung-jae (Winner)</p>
          </div>
        </div>
      </section>
    
      <section id="trivia" class="content-section">
        <h2 class="section-title">Trivia & Fun Facts</h2>
        <div class="trivia-grid">
          <div class="trivia-card">
            <h3>Hidden Meanings</h3>
            <ul class="trivia-list">
              <li>The circle, triangle and square shapes represent letters in the Korean alphabet</li>
              <li>The pink soldiers' masks were inspired by traditional Korean masks</li>
              <li>The numbers chosen by players have symbolic meanings</li>
            </ul>
          </div>
          <div class="trivia-card">
            <h3>Production Facts</h3> 
            <ul class="trivia-list">
              <li>The show was originally conceived in 2008 but was rejected by studios for 10 years</li>
              <li>The giant doll in Red Light, Green Light is a real 13-foot tall animatronic figure</li>
              <li>The entire set of glass stepping stones was suspended 5 feet above ground for safety</li>
              <li>Over 456 unique green tracksuits were created for the contestants</li>
            </ul>
          </div>
        </div>
      </section>
    
      <section id="game-mechanics" class="content-section">
        <h2 class="section-title">Game Mechanics Explorer</h2>
        <div class="mechanics-grid">
          <div class="mechanics-card">
            <h3>Survival Odds Calculator</h3>
            <div class="calculator">
              <select id="gameSelect">
                <option value="redlight">Red Light, Green Light</option>
                <option value="honeycomb">Honeycomb</option>
                <option value="tugofwar">Tug of War</option>
                <option value="marbles">Marbles</option>
                <option value="glass">Glass Bridge</option>
                <option value="squid">Squid Game</option>
              </select>
              <div id="oddsResult" class="odds-display">
                <div class="odds-meter">
                  <div class="meter-fill"></div>
                </div>
                <span class="odds-text">Select a game to calculate odds</span>
              </div>
            </div>
          </div>
        </div>
      </section>
    
      <section id="community" class="content-section">
        <h2 class="section-title">Community & Social Impact</h2>
        <div class="community-grid">
          <div class="community-card">
            <h3>Fan Communities</h3>
            <div class="community-stats">
              <div class="stat-item">
                <span class="stat-number">2.4M</span>
                <span class="stat-label">Reddit Members</span>
              </div>
              <div class="stat-item">
                <span class="stat-number">850K</span>
                <span class="stat-label">Discord Users</span>
              </div>
            </div>
            <ul class="community-list">
              <li>Active discussion forums</li>
              <li>Fan art showcases</li>
              <li>Theory crafting groups</li>
              <li>Cosplay communities</li>
            </ul>
          </div>
          <div class="community-card">
            <h3>Global Events</h3>
            <div class="events-timeline">
              <div class="event-item">
                <h4>Pop-Up Experiences</h4>
                <p>Interactive installations in major cities</p>
              </div>
              <div class="event-item">
                <h4>Gaming Competitions</h4>
                <p>Safe recreations of show games</p>
              </div>
              <div class="event-item">
                <h4>Fan Conventions</h4>
                <p>Cast meet & greets, panels</p>
              </div>
            </div>
          </div>
        </div>
      </section>
    
      <section id="infographic" class="content-section">
        <h2 class="section-title">Interactive Infographic: Game Statistics</h2>
        <div class="infographic-container">
          <div class="data-point" data-value="456">
            <svg class="circular-progress">
              <circle class="progress-bg" cx="60" cy="60" r="54"></circle>
              <circle class="progress-bar" cx="60" cy="60" r="54"></circle>
            </svg>
            <div class="data-content">
              <span class="data-number">456</span>
              <span class="data-label">Initial Players</span>
            </div>
          </div>
          <div class="data-point" data-value="45">
            <svg class="circular-progress">
              <circle class="progress-bg" cx="60" cy="60" r="54"></circle>
              <circle class="progress-bar" cx="60" cy="60" r="54"></circle>
            </svg>
            <div class="data-content">
              <span class="data-number">45</span>
              <span class="data-label">Survivors After Game 1</span>
            </div>
          </div>
          <div class="data-point" data-value="1">
            <svg class="circular-progress">
              <circle class="progress-bg" cx="60" cy="60" r="54"></circle>
              <circle class="progress-bar" cx="60" cy="60" r="54"></circle>
            </svg>
            <div class="data-content">
              <span class="data-number">1</span>
              <span class="data-label">Final Winner</span>
            </div>
          </div>
        </div>
      </section>
    
      <section id="data-vis" class="content-section">
        <h2 class="section-title">Interactive Data Explorer</h2>
        <div class="vis-container">
          <div class="vis-controls">
            <select id="dataType">
              <option value="viewership">Viewership Data</option>
              <option value="social">Social Media Impact</option>
              <option value="demographics">Demographics</option>
            </select>
            <div class="vis-filters">
              <button class="filter-btn active" data-period="all">All Time</button>
              <button class="filter-btn" data-period="month">Last Month</button>
              <button class="filter-btn" data-period="week">Last Week</button>
            </div>
          </div>
          <div class="vis-canvas">
            <canvas id="dataVisChart"></canvas>
          </div>
        </div>
      </section>
    
      <section id="statistics-overlay" class="stats-overlay">
        <h2 class="section-title">Global Statistics</h2>
        <div class="global-stats-grid">
          <div class="stat-block">
            <h3>Viewership</h3>
            <div class="chart-container">
              <canvas id="viewershipChart"></canvas>
            </div>
          </div>
          <div class="stat-block">
            <h3>Online Engagement</h3>
            <div class="chart-container">
              <canvas id="engagementChart"></canvas>
            </div>
          </div>
        </div>
        <button class="close-stats">X</button>
      </section>
    
      <section id="fan-content" class="content-section">
        <h2 class="section-title">Fan Content Hub</h2>
        <div class="fan-content-grid">
          <div class="fan-content-card">
            <h3>Fanfiction Corner</h3>
            <div class="story-grid">
              <!-- Story entries will be dynamically added -->
            </div>
            <button class="submit-story-btn">Submit Story</button>
          </div>
          <div class="fan-content-card">
            <h3>Fan Theory Analysis</h3>
            <div class="theory-analysis">
              <div class="theory-filters">
                <button class="filter-btn active" data-filter="popular">Most Popular</button>
                <button class="filter-btn" data-filter="recent">Recent</button>
                <button class="filter-btn" data-filter="controversial">Controversial</button>
              </div>
              <div class="theory-list">
                <!-- Theory entries will be dynamically added -->
              </div>
            </div>
          </div>
        </div>
      </section>
    
      <script>
        const fanContent = {
          stories: [
            {
              title: "The Front Man's Origin",
              author: "SquidFan456",
              excerpt: "Before he became the Front Man...",
              likes: 342,
              comments: 89
            },
            {
              title: "Player 067's Escape",
              author: "GameTheory",
              excerpt: "What if Sae-byeok had survived...",
              likes: 567,
              comments: 123
            }
          ],
          theories: [
            {
              title: "The VIPs' True Purpose",
              author: "TheoryMaster",
              content: "The VIPs might represent more than just wealthy spectators...",
              votes: 892,
              controversy: 0.75
            },
            {
              title: "Season 2 Predictions",
              author: "FutureGames",
              content: "Based on the finale, these games might appear...",
              votes: 1023,
              controversy: 0.45
            }
          ]
        };
      </script>
    
      <script>
        function initializeFanContent() {
          const storyGrid = document.querySelector('.story-grid');
          const theoryList = document.querySelector('.theory-list');
    
          fanContent.stories.forEach(story => {
            const storyEl = document.createElement('div');
            storyEl.className = 'story-entry';
            storyEl.innerHTML = `
              <h4>${story.title}</h4>
              <p class="story-author">By ${story.author}</p>
              <p class="story-excerpt">${story.excerpt}</p>
              <div class="story-stats">
                <span>${story.likes} likes</span>
                <span>${story.comments} comments</span>
              </div>
            `;
            storyGrid.appendChild(storyEl);
          });
    
          fanContent.theories.forEach(theory => {
            const theoryEl = document.createElement('div');
            theoryEl.className = 'theory-entry';
            theoryEl.innerHTML = `
              <h4>${theory.title}</h4>
              <p class="theory-author">By ${theory.author}</p>
              <p class="theory-content">${theory.content}</p>
              <div class="theory-stats">
                <span>${theory.votes} votes</span>
                <span>Controversy: ${Math.round(theory.controversy * 100)}%</span>
              </div>
            `;
            theoryList.appendChild(theoryEl);
          });
        }
      </script>
    
      <script>
        document.addEventListener('DOMContentLoaded', function() {
          initializeFanContent();
    
          document.querySelectorAll('.theory-filters .filter-btn').forEach(btn => {
            btn.addEventListener('click', () => {
              document.querySelectorAll('.theory-filters .filter-btn').forEach(b => 
                b.classList.remove('active'));
              btn.classList.add('active');
              
              const filter = btn.dataset.filter;
              const theories = [...fanContent.theories];
              
              switch(filter) {
                case 'popular':
                  theories.sort((a, b) => b.votes - a.votes);
                  break;
                case 'controversial':
                  theories.sort((a, b) => b.controversy - a.controversy);
                  break;
                case 'recent':
                  // In a real app, would sort by date
                  theories.reverse();
                  break;
              }
              
              const theoryList = document.querySelector('.theory-list');
              theoryList.innerHTML = '';
              theories.forEach(theory => {
                const theoryEl = document.createElement('div');
                theoryEl.className = 'theory-entry';
                theoryEl.innerHTML = `
                  <h4>${theory.title}</h4>
                  <p class="theory-author">By ${theory.author}</p>
                  <p class="theory-content">${theory.content}</p>
                  <div class="theory-stats">
                    <span>${theory.votes} votes</span>
                    <span>Controversy: ${Math.round(theory.controversy * 100)}%</span>
                  </div>
                `;
                theoryList.appendChild(theoryEl);
              });
            });
          });
    
          document.querySelector('.submit-story-btn').addEventListener('click', () => {
            const modal = document.createElement('div');
            modal.className = 'submit-modal';
            modal.innerHTML = `
              <div class="modal-content">
                <h3>Submit Your Story</h3>
                <form id="storyForm">
                  <input type="text" placeholder="Story Title" required>
                  <textarea placeholder="Your Story" required></textarea>
                  <button type="submit">Submit</button>
                </form>
                <button class="close-modal">Close</button>
              </div>
            `;
            document.body.appendChild(modal);
            
            modal.querySelector('.close-modal').addEventListener('click', () => {
              modal.remove();
            });
            
            modal.querySelector('#storyForm').addEventListener('submit', (e) => {
              e.preventDefault();
              // Handle story submission
              modal.remove();
              alert('Thank you for your submission! It will be reviewed shortly.');
            });
          });
        });
      </script>
    
      <section id="extras" class="content-section">
        <h2 class="section-title">Collector's Corner</h2>
        
        <div class="collectibles-grid">
          <div class="collectible-card">
            <h3>Limited Edition Items</h3>
            <div class="collectible-list">
              <div class="collectible-item">
                <h4>Golden Dalgona Cookie Mold</h4>
                <p class="collectible-desc">24k gold-plated commemorative cookie mold, numbered edition of 456.</p>
                <span class="collectible-price">$299.99</span>
                <button class="collect-btn">Add to Collection</button>
              </div>
              <div class="collectible-item">
                <h4>VIP Mask Replica</h4>
                <p class="collectible-desc">Screen-accurate prop replica, hand-finished in metallic paint.</p>
                <span class="collectible-price">$199.99</span>
                <button class="collect-btn">Add to Collection</button>
              </div>
            </div>
          </div>
    
          <div class="collectible-card">
            <h3>Digital Collectibles</h3>
            <div class="nft-gallery">
              <div class="nft-item">
                <h4>Player Card #001</h4>
                <p class="nft-desc">Animated digital trading card featuring Oh Il-nam.</p>
                <span class="nft-price">0.1 ETH</span>
                <button class="mint-btn">Mint NFT</button>
              </div>
              <div class="nft-item">
                <h4>Game Scene #1</h4>
                <p class="nft-desc">Red Light, Green Light iconic moment.</p>
                <span class="nft-price">0.15 ETH</span>
                <button class="mint-btn">Mint NFT</button>
              </div>
            </div>
          </div>
        </div>
    
        <div class="collection-stats">
          <div class="stat-card">
            <span class="stat-number">24,691</span>
            <span class="stat-label">Active Collectors</span>
          </div>
          <div class="stat-card">
            <span class="stat-number">198</span>
            <span class="stat-label">Rare Items</span>
          </div>
          <div class="stat-card">
            <span class="stat-number">$2.1M</span>
            <span class="stat-label">Total Trading Volume</span>
          </div>
        </div>
    
        <div class="marketplace">
          <h3>Trading Post</h3>
          <div class="trading-grid">
            <!-- Trading listings will be dynamically populated -->
          </div>
          <button class="list-item-btn">List Your Item</button>
        </div>
      </section>
    
      <script>
        const tradingData = {
          listings: [
            {
              id: 1,
              title: "Front Man Mask - First Edition",
              seller: "SquidCollector",
              price: 599.99,
              condition: "Mint",
              rarity: "Ultra Rare"
            },
            {
              id: 2,
              title: "Player 067 Game Worn Jacket",
              seller: "PropHunter",
              price: 1299.99,
              condition: "Used - Excellent",
              rarity: "One of a Kind"
            }
          ]
        };
      </script>
    
      <script>
        function populateTrading() {
          const tradingGrid = document.querySelector('.trading-grid');
          tradingData.listings.forEach(item => {
            const listingEl = document.createElement('div');
            listingEl.className = 'trading-item';
            listingEl.innerHTML = `
              <h4>${item.title}</h4>
              <p class="seller">Seller: ${item.seller}</p>
              <p class="condition">Condition: ${item.condition}</p>
              <p class="rarity">${item.rarity}</p>
              <span class="price">$${item.price}</span>
              <button class="trade-btn">Make Offer</button>
            `;
            tradingGrid.appendChild(listingEl);
          });
        }
    
        populateTrading();
    
        document.querySelector('.list-item-btn').addEventListener('click', () => {
          const modal = document.createElement('div');
          modal.className = 'list-modal';
          modal.innerHTML = `
            <div class="modal-content">
              <h3>List Your Item</h3>
              <form id="listingForm">
                <input type="text" placeholder="Item Title" required>
                <input type="number" placeholder="Price" required min="0" step="0.01">
                <select name="condition" required>
                  <option value="">Select Condition</option>
                  <option value="mint">Mint</option>
                  <option value="excellent">Excellent</option>
                  <option value="good">Good</option>
                  <option value="fair">Fair</option>
                </select>
                <textarea placeholder="Description" required></textarea>
                <button type="submit">List Item</button>
              </form>
              <button class="close-modal">×</button>
            </div>
          `;
          document.body.appendChild(modal);
          
          modal.querySelector('.close-modal').addEventListener('click', () => {
            modal.remove();
          });
          
          modal.querySelector('#listingForm').addEventListener('submit', (e) => {
            e.preventDefault();
            modal.remove();
            alert('Item listed successfully!');
          });
        });
      </script>
    </div>
    
    <script>
      function initSentimentMeter() {
        const fill = document.getElementById('sentimentFill');
        setTimeout(() => {
          fill.style.width = '85%';
        }, 500);
      }
    </script>
    
    <script>
      document.addEventListener('DOMContentLoaded', function() {
        initSentimentMeter();
      });
    </script>
    
    <script>
      function updateVotes(isPositive) {
        const positiveCount = document.getElementById('positiveCount');
        const negativeCount = document.getElementById('negativeCount');
        const meterFill = document.getElementById('sentimentFill');
        const meterLabel = document.querySelector('.meter-label');
    
        if (isPositive) {
          positiveCount.textContent = parseInt(positiveCount.textContent) + 1;
        } else {
          negativeCount.textContent = parseInt(negativeCount.textContent) + 1;
        }
    
        const total = parseInt(positiveCount.textContent) + parseInt(negativeCount.textContent);
        const positivePercentage = Math.round((parseInt(positiveCount.textContent) / total) * 100);
        
        meterFill.style.width = positivePercentage + '%';
        meterLabel.textContent = positivePercentage + '% Positive';
      }
    </script>
    
    <script>
      document.addEventListener('DOMContentLoaded', function() {
        document.querySelectorAll('.large-vote').forEach(btn => {
          btn.addEventListener('click', function() {
            const isPositive = this.classList.contains('positive');
            updateVotes(isPositive);
            
            // Disable buttons after voting
            document.querySelectorAll('.large-vote').forEach(b => {
              b.disabled = true;
              b.style.opacity = '0.5';
              b.style.cursor = 'default';
            });
    
            // Add user's vote to recent votes
            const recentVotes = document.querySelector('.recent-votes');
            const newVote = document.createElement('div');
            newVote.className = 'vote-comment';
            newVote.innerHTML = `
              <img src="https://playgamesnow.org/squidgames/public/${window.websim.getCreatedBy()}" class="vote-avatar">
              <div class="vote-details">
                <span class="voter-name">${window.websim.getCreatedBy()}</span>
                <p class="vote-text">"Thanks for voting!"</p>
                <span class="vote-time">Just now</span>
              </div>
              <span class="vote-indicator ${isPositive ? 'positive' : 'negative'}">${isPositive ? '👍' : '👎'}</span>
            `;
            recentVotes.insertBefore(newVote, recentVotes.firstChild);
          });
        });
      });
    </script>
    
    </body>
    </html>
