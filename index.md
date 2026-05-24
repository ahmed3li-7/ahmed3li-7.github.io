---
layout: default
title: Ahmed Ali Hakim Abdulgawad
---

<style>
  :root {
    --cv-text: #1f2937;
    --cv-muted: #6b7280;
    --cv-border: #e5e7eb;
    --cv-accent: #2563eb;
    --cv-bg: #ffffff;
    --cv-soft: #f8fafc;
  }

  .cv-page {
    color: var(--cv-text);
    line-height: 1.65;
    max-width: 920px;
    margin: 0 auto;
  }

  .cv-header {
    display: grid;
    grid-template-columns: 150px 1fr;
    gap: 24px;
    align-items: center;
    padding: 28px;
    margin-bottom: 28px;
    background: var(--cv-soft);
    border: 1px solid var(--cv-border);
    border-radius: 18px;
  }

  .profile-photo {
    width: 150px;
    height: 150px;
    object-fit: cover;
    border-radius: 22px;
    border: 4px solid var(--cv-bg);
    box-shadow: 0 8px 24px rgba(15, 23, 42, 0.12);
  }

  .cv-title h1 {
    margin: 0 0 8px;
    font-size: 2rem;
    line-height: 1.2;
    color: #111827;
  }

  .cv-subtitle {
    margin: 0 0 14px;
    font-weight: 600;
    color: var(--cv-accent);
  }

  .contact-line {
    margin: 0;
    color: var(--cv-muted);
    font-size: 0.98rem;
  }

  .cv-section {
    margin: 0 0 24px;
    padding-bottom: 22px;
    border-bottom: 1px solid var(--cv-border);
  }

  .cv-section:last-child {
    border-bottom: 0;
  }

  .cv-section h2 {
    margin: 0 0 12px;
    font-size: 1.25rem;
    color: #111827;
    border-left: 4px solid var(--cv-accent);
    padding-left: 10px;
  }

  .cv-section ul {
    margin-top: 8px;
  }

  .tag-list {
    display: flex;
    flex-wrap: wrap;
    gap: 8px;
    padding: 0;
    list-style: none;
  }

  .tag-list li {
    padding: 6px 10px;
    background: var(--cv-soft);
    border: 1px solid var(--cv-border);
    border-radius: 999px;
    font-size: 0.95rem;
  }

  .item-title {
    font-weight: 700;
    color: #111827;
  }

  .item-meta {
    color: var(--cv-muted);
  }

  @media (max-width: 640px) {
    .cv-header {
      grid-template-columns: 1fr;
      text-align: center;
      padding: 22px;
    }

    .profile-photo {
      margin: 0 auto;
    }

    .cv-title h1 {
      font-size: 1.65rem;
    }
  }
</style>

<div class="cv-page">
  <header class="cv-header">
    <img class="profile-photo" src="assets/profile-placeholder.svg" alt="Profile photo of Ahmed Ali Hakim Abdulgawad">
    <div class="cv-title">
      <h1>Ahmed Ali Hakim Abdulgawad</h1>
      <p class="cv-subtitle">Medical Student | Aspiring Healthcare & Learning Technology Contributor</p>
      <p class="contact-line">
        <strong>Email:</strong> <a href="mailto:ahmedali17v@gmail.com">ahmedali17v@gmail.com</a> |
        <strong>Phone:</strong> <a href="tel:+201008988182">+20 100 898 8182</a> |
        <strong>WhatsApp:</strong> <a href="https://wa.me/201101452846">+20 110 145 2846</a>
      </p>
    </div>
  </header>

  <section class="cv-section">
    <h2>Profile</h2>
    <p>
      Motivated medical student with strong curiosity, a commitment to continuous learning, and an interest in combining healthcare, education, and technology. I am proactive, adaptable, and determined to create opportunities for growth rather than waiting for them.
    </p>
  </section>

  <section class="cv-section">
    <h2>Education</h2>
    <ul>
      <li>
        <span class="item-title">Medical Student</span> — Faculty of Medicine, Minia University
      </li>
    </ul>
  </section>

  <section class="cv-section">
    <h2>Experience</h2>
    <p>
      Although I am still at the beginning of my professional journey, I am actively developing my skills through learning, self-improvement, and personal projects. I aim to gain meaningful experience in medical education, healthcare innovation, and technology-supported learning.
    </p>
  </section>

  <section class="cv-section">
    <h2>Skills</h2>
    <ul>
      <li><strong>Languages:</strong> English — B2; French — A2.</li>
      <li><strong>Digital skills:</strong> Microsoft Word, Microsoft PowerPoint, presentation preparation, and basic programming knowledge.</li>
      <li><strong>Professional strengths:</strong> Curiosity, self-learning, analytical thinking, communication, and presentation skills.</li>
    </ul>
  </section>

  <section class="cv-section">
    <h2>Projects</h2>
    <ul>
      <li>
        <span class="item-title">RafeeQ</span> — A learning platform designed to support medical students with accessible educational resources and a structured study experience.
      </li>
    </ul>
  </section>

  <section class="cv-section">
    <h2>Interests</h2>
    <p>
      My interests reflect a balance between strategic thinking, scientific curiosity, physical activity, and global awareness.
    </p>
    <ul class="tag-list">
      <li>Chess</li>
      <li>Swimming</li>
      <li>Video Games</li>
      <li>Politics</li>
      <li>Historical Studies</li>
      <li>Historical Geography</li>
      <li>Political Geography</li>
      <li>Data Analysis</li>
      <li>Statistics &amp; Probability</li>
      <li>Electromagnetism</li>
      <li>Modern Physics</li>
    </ul>
  </section>

  <section class="cv-section">
    <h2>Contact</h2>
    <ul>
      <li><strong>Email:</strong> <a href="mailto:ahmedali17v@gmail.com">ahmedali17v@gmail.com</a></li>
      <li><strong>WhatsApp:</strong> <a href="https://wa.me/201101452846">+20 110 145 2846</a></li>
      <li><strong>Phone:</strong> <a href="tel:+201008988182">+20 100 898 8182</a></li>
    </ul>
  </section>
</div>

> To use your real profile picture, upload it to `assets/profile.jpg` and replace `assets/profile-placeholder.svg` in the image source above with `assets/profile.jpg`.
