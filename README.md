<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>News Aggregator</title>
  <!-- You can add external CSS here -->
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <header>
    <h1>News Aggregator</h1>
    <nav>
      <ul>
        <li><a href="#home">Home</a></li>
        <li><a href="#world">World</a></li>
        <li><a href="#technology">Technology</a></li>
        <li><a href="#sports">Sports</a></li>
        <li><a href="#entertainment">Entertainment</a></li>
      </ul>
    </nav>
  </header>

  <main>
    <section id="news-category">
      <h2>Category: Sports</h2>
      
      <!-- News Articles Container -->
      <div class="news-article">
        <h3>"India under Dhoni's leadership, won the inaugural T20 World Cup in 2007"</h3>
        <p class="summary">This is a summary of the article. Click the link below to read more.</p>
        <a href="https://en.wikipedia.org/wiki/2007_Cricket_World_Cup" target="_blank">Read full article</a>
      </div>
      </section>
    
      <section id="news-category">
        <b> <h1>catogory: Politics</h1></b>

      <!-- news article container -->
      <div class="news-article">
        <h3>2014 assembly election result</h3>
        <p class="summary">Summary of another article. Check out the full article through the link.</p>
        <a href="https://www.indiavotes.com/vidhan-sabha/2014/maharashtra/241/30" target="_blank">Read full article</a>
      </div>
      </section>

      <!-- More news articles will be added dynamically from API -->
    </section>
  </main>

  <footer>
    <p>© 2025 News Aggregator. All rights reserved.</p>
  </footer>

  <!-- Add External JS scripts (e.g., Angular, React, Vue.js) -->
  <script src="app.js"></script>
</body>
</html>
