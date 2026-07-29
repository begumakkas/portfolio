+++
title = "Projects"
+++


<section class="projects-list projects-wide">

  <!-- Project 1 – Insight Out – image left, text right -->
  <article class="project-row">
    <div class="project-image">
        <div class="flip-card" tabindex="0">
            <div class="flip-card-inner">
            <div class="flip-card-front">
                <img src="/images/insightoutFront.png" alt="Insight Out (front)">
            </div>
            <div class="flip-card-back">
                <img src="/images/insightout.png" alt="Insight Out (back)">
            </div>
            </div>
        </div>
    </div>
    <div class="project-content">
      <p class="project-label">Web Application</p>
      <h3 class="project-title">
            <a href="https://insightout.civic.garden/" target="_blank">
            Insight Out
            </a>
        </h3>
      <ul class="project-description">
        <li>A deployed self-service tool that lets nonprofit staff define their own target metrics and identify beneficiary populations in any geography, without engineering support.</li>
        <li>On this team project, I built the frontend from scratch in Svelte and implemented the authentication system in Django, developing against jointly designed API contracts so the frontend and backend could progress in parallel.</li>
      </ul>
      <p class="project-tech">Svelte · Django · REST APIs</p>
    </div>
  </article>

  <!-- Project 2 – Green Space – image right, text left -->
  <article class="project-row project-row--reverse">
    <div class="project-image">
        <div class="flip-card" tabindex="0">
            <div class="flip-card-inner">
            <div class="flip-card-front">
                <img src="/images/grantPark.jpeg" alt="Green Space Accessibility (front)">
            </div>
            <div class="flip-card-back">
                <img src="/images/greenSpaceCrop.png" alt="Green Space Accessibility (back)">
            </div>
            </div>
        </div>
    </div>
    <div class="project-content">
      <p class="project-label">Geospatial Analysis</p>
      <h3 class="project-title">
            <a href="https://github.com/begumakkas/Green-Space-Access" target="_blank">
            Green Space Accessibility in Chicago
            </a>
        </h3>
      <ul class="project-description">
        <li>This project analyzes disparities in access to high-quality public parks near affordable housing buildings in Chicago.</li>
        <li>As part of this group project, my main role was synthesizing the
        different data sources and building our accessibility index.</li>
      </ul>
      <p class="project-tech">Python · GeoPandas</p>
    </div>
  </article>

  <!-- Project 3 – Fraym – image left, text right -->
  <article class="project-row">
        <div class="project-image">
        <div class="flip-card" tabindex="0">
            <div class="flip-card-inner">
            <div class="flip-card-front">
                <img src="/images/fraymLogo.jpg" alt="Fraym Model Performance (front)">
            </div>
            <div class="flip-card-back">
                <img src="/images/fraymBarChart.png" alt="Fraym Model Performance (back)">
            </div>
            </div>
        </div>
    </div>
    <div class="project-content">
      <p class="project-label">Dashboard</p>
      <h3 class="project-title">
            <a>
            Fraym's Model Performance
            </a>
        </h3>
      <ul class="project-description">
        <li>This dashboard provides high-level analytics on Fraym model performance, including model/feature frequency and comparisons of RMSE and training time across jobs and models. It runs on a customizable sample of Fraym-produced layers.</li>
        <li>The dashboard was built as a first step toward broader transparency into model performance.</li>
      </ul>
      <p class="project-tech">Python · Streamlit · AWS S3 · DBeaver</p>
    </div>
  </article>

  <!-- Project 4 – Hottest Songs – image right, text left -->
  <article class="project-row project-row--reverse">
    <div class="project-image">
        <div class="flip-card" tabindex="0">
            <div class="flip-card-inner">
            <div class="flip-card-front">
                <img src="/images/billboardCover.png" alt="Hottest U.S. Songs (front)">
            </div>
            <div class="flip-card-back">
                <img src="/images/raceTime.png" alt="Hottest U.S. Songs (back)">
            </div>
            </div>
        </div>
    </div>
    <div class="project-content">
      <p class="project-label">Interactive Visualization</p>
      <h3 class="project-title">
        <a href="https://charting-bars.pages.dev/" target="_blank">
        Hottest U.S. Songs
        </a>
      </h3>
      <ul class="project-description">
        <li>Visualizes trends for songs that hit #1 on the Billboard chart
        since 1958.</li>
        <li>The visualization reveals some disparities in the music industry.
        For example, women are much more often singers but less often songwriters.</li>
      </ul>
      <p class="project-tech">Python · D3 · JS · HTML/CSS · Cloudflare</p>
    </div>
  </article>

  <!-- Project 5 – Homework Tracker – image left, text right -->
  <article class="project-row">
    <div class="project-image">
        <div class="flip-card" tabindex="0">
            <div class="flip-card-inner">
            <div class="flip-card-front">
                <img src="/images/hw_logo.png" alt="Homework Tracker App (front)">
            </div>
            <div class="flip-card-back">
                <img src="/images/hw_app.png" alt="Homework Tracker App (back)">
            </div>
            </div>
        </div>
    </div>
    <div class="project-content">
      <p class="project-label">Web Application</p>
      <h3 class="project-title">
        <a href="https://github.com/begumakkas/hw-scheduler" target="_blank">
        Homework Tracker App
        </a>
      </h3>
      <ul class="project-description">
        <li>Ingests PDF syllabi and extracts structured assignment data such as due dates, priority,
        and exam flags into a sortable task dashboard.</li>
        <li>Built to eliminate the overhead of manually inputting and tracking assignments
        across multiple courses.</li>
      </ul>
      <p class="project-tech">Ruby on Rails · HTML/CSS · PostgreSQL</p>
    </div>
  </article>

</section>


<h2>My current tech stack</h2>
<br>
<div class="techstack">
  <span class="tech"><i class="devicon-python-plain colored"></i><span>Python</span></span>
  <span class="tech"><i class="devicon-mysql-original colored"></i><span>MySQL</span></span>
  <span class="tech"><i class="devicon-javascript-plain colored"></i><span>JavaScript</span></span>
  <span class="tech"><i class="devicon-d3js-plain colored"></i><span>D3</span></span>
  <span class="tech"><i class="devicon-svelte-plain colored"></i><span>Svelte</span></span>
  <span class="tech"><i class="devicon-django-plain colored"></i><span>Django</span></span>
  <span class="tech"><i class="devicon-html5-plain colored"></i><span>HTML</span></span>
  <span class="tech"><i class="devicon-css3-plain colored"></i><span>CSS</span></span>
  <span class="tech"><i class="devicon-r-plain colored"></i><span>R</span></span>
  <span class="tech"><i class="devicon-git-plain colored"></i><span>Git</span></span>
  <span class="tech"><i class="devicon-amazonwebservices-plain-wordmark colored"></i><span>AWS</span></span>
  <span class="tech"><i class="devicon-rails-plain colored"></i><span>Ruby on Rails</span></span>
</div>