<!doctype html>
<html lang="en">
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Komil Dobilov — Data Science Portfolio</title>
  <meta name="description" content="Data science & machine learning portfolio: selected projects, skills, and contact." />
  <meta property="og:title" content="Komil Dobilov — Data Science Portfolio" />
  <meta property="og:description" content="Selected ML projects with metrics and code." />
  <meta property="og:type" content="website" />
  <link rel="stylesheet" href="styles.css" />
  <body>
    <header class="hero">
      <h1>Komil Dobilov</h1>
      <p>Data Science • Machine Learning • Analytics</p>
      <p class="usp">I turn messy business data into decisions with reproducible ML.</p>
      <nav>
        <a href="#projects">Projects</a>
        <a href="#skills">Skills</a>
        <a href="#about">About</a>
        <a href="#contact">Contact</a>
      </nav>
    </header>

    <main>
      <section id="projects">
        <h2>Featured Projects</h2>

        <article class="card">
          <h3><a href="https://github.com/YOU/churn-prediction">Churn Prediction</a></h3>
          <p>Tree-based models + SHAP; targeted offers reduce expected churn. <strong>F1: 0.88</strong>.</p>
          <ul>
            <li>Data: contracts, usage, payments</li>
            <li>Models: LightGBM, logistic regression</li>
          </ul>
        </article>

        <article class="card">
          <h3><a href="https://github.com/YOU/imdb-sentiment">IMDB Sentiment</a></h3>
          <p>BERT fine-tuning for movie reviews; robust to slang/negations. <strong>F1: 0.90</strong>.</p>
          <ul>
            <li>EDA + error analysis</li>
            <li>Deployment: inference notebook</li>
          </ul>
        </article>

        <article class="card">
          <h3><a href="https://github.com/YOU/used-car-prices">Used-Car Price Model</a></h3>
          <p>Gradient boosting with feature engineering; <strong>RMSE: $X,XXX</strong>.</p>
          <ul>
            <li>Features: age, trim, mileage, region</li>
            <li>Model: LightGBM + cross-validation</li>
          </ul>
        </article>
      </section>

      <section id="skills">
        <h2>Skills</h2>
        <p>Python, pandas, NumPy, scikit-learn, LightGBM, SQL, Jupyter, Git, SHAP, matplotlib.</p>
      </section>

      <section id="about">
        <h2>About</h2>
        <p>Brief, business-focused bio: your background, the problems you solve, and how you work.</p>
      </section>

      <section id="contact">
        <h2>Contact</h2>
        <p><a href="mailto:you@example.com">you@example.com</a> • <a href="https://www.linkedin.com/in/you">LinkedIn</a> • <a href="https://github.com/YOURUSERNAME">GitHub</a></p>
      </section>
    </main>

    <footer>
      <small>© <span id="y"></span> Your Name</small>
      <script>document.getElementById('y').textContent=new Date().getFullYear()</script>
    </footer>
  </body>
</html>
