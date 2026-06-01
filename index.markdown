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
            Hi there, and welcome to my page! My name is Rusham Raj Bhatt, and I am enthusiastic about applying computational methods and machine learning to solve problems in multi-team robotics!
          </p>
          <p>
            My journey begins this Fall at Chicago, where I will be
            a first-year PhD student in the Bioinspired Robotics and Resilient Intelligence Laboratory in the Department of Mechanical and Industrial Engineering at the University of Illinois Chicago.
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
        <div class="journey-content">
          <div>
            <img src="/assets/images/research.jpeg" alt="Research presentation">
          </div>
          <div>
            <p>
              During my undergraduate studies, I worked on scientific software development,
              bioinformatics, and machine learning across several research environments.
            </p>
            <p>
              I had the privilege of working in labs and with PI's at the Protein Data Bank in Rutgers University, New Brunswick, 
              Harvard Medical School, Salk Institute of Biological Studies, and my beloved alma mater the University of Maryland, Baltimore County.
            </p>
            <p>
              Not only did these experiences taught me how to think and work like a researcher, they taught me resilience, courage, and staying optimistic
              when experiments didn't work out. I hope to continue applying these lessons to my ongoing journey as a researcher and when facing difficulties in life.
            </p>
          </div>
        </div>
        <div class="section-buttons">
          <button class="slide-button" onclick="scrollToSection('about-section')">← Back</button>
          <!-- <button class="slide-button" onclick="scrollToSection('personality-section')">Next →</button> -->
        </div>
      </div>
    </section>
    <!-- <section class="slide-section" id="personality-section">
      <div class="section-card">
        <div class="personality-content">
          <div>
            <p>
              During my spare time, I enjoy playing video games
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
    </section> -->
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