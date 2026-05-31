---
layout: page
title: Home
---

<div
  class="portfolio-background"
  style="background-image: linear-gradient(rgba(15, 23, 42, 0.65), rgba(15, 23, 42, 0.65)), url('/assets/images/salon-bg.jpeg');"
>
  <div class="horizontal-page">
    <section class="slide-section" id="about-section">
      <div class="home-page">
        <div class="about-me-text">
          <p>
            Hello world! My name is Rusham Raj Bhatt, and I am an incoming PhD student at the University of Illinois Chicago.
          </p>
          <p>
            I hope you enjoy my page!
          </p>
          <button class="slide-button" onclick="scrollToSection('journey-section')">
            Learn more about me →
          </button>
        </div>
        <div class="image-block">
          <div class="profile-image">
            <img src="/assets/images/profile.jpeg" alt="Rusham Bhatt Graduation">
          </div>
        </div>
      </div>
    </section>
    <section class="slide-section" id="journey-section">
      <div class="section-card">
        <h2>My Research Journey</h2>
        <div class="journey-content">
          <div>
            <img src="/assets/images/pointing.jpg" alt="Research presentation">
          </div>
          <div>
            <p>
              During my undergraduate studies, I worked on scientific software development,
              bioinformatics, and machine learning across several research environments.
            </p>
          </div>
        </div>
        <div class="section-buttons">
          <button class="slide-button" onclick="scrollToSection('about-section')">← Back</button>
          <button class="slide-button" onclick="scrollToSection('personality-section')">Next →</button>
        </div>
      </div>
    </section>
    <section class="slide-section" id="personality-section">
      <div class="section-card">
        <h2>Outside the Lab</h2>
        <div class="personality-content">
          <div>
            <p>
              I am very goated at soccer you know.
            </p>
          </div>
          <div>
            <img src="/assets/images/pointing.jpg" alt="Soccer">
          </div>
        </div>
        <div class="section-buttons">
          <button class="slide-button" onclick="scrollToSection('journey-section')">← Back</button>
        </div>
      </div>
    </section>
  </div>
</div>

<script>
  function scrollToSection(sectionId) {
    document.getElementById(sectionId).scrollIntoView({
      behavior: "smooth",
      inline: "start",
      block: "nearest"
    });
  }
</script>