---
layout: page
title: Career
include_in_header: true
nav_order: 2
---

<div class="career-hero">
  <h1 class="career-title">Join Our Mission</h1>
  <p class="career-subtitle">Help us revolutionize short-term rental and peer-to-peer commerce</p>
</div>

<div class="career-content">

  <div class="jobs-section">
    <h2 class="section-title">Open Positions</h2>
    
    <div class="job-grid">
      <div class="job-card">
        <div class="job-header">
          <h3 class="job-title">Social Media Marketing & Creator Internship</h3>
          <span class="job-type">Part-time</span>
        </div>
        <div class="job-details">
          <p class="job-location">📍 Remote (Campus-based)</p>
          <p class="job-department">Marketing</p>
          <p class="job-description">Be the face of Apateu on your campus! Create content, host events, and grow our student community through TikTok, Reels, and campus activations.</p>
        </div>
        <div class="job-footer">
          <a href="/career/social-media-marketing-creator-internship" target="_self" class="job-link">View Details →</a>
        </div>
      </div>

      <div class="job-card">
        <div class="job-header">
          <h3 class="job-title">UGC Content Creator</h3>
          <span class="job-type">Freelance</span>
        </div>
        <div class="job-details">
          <p class="job-location">📍 Remote</p>
          <p class="job-department">Marketing</p>
          <p class="job-description">Create authentic user-generated content that showcases real experiences with Apateu. Produce engaging videos for TikTok, Instagram, and other social platforms.</p>
        </div>
        <div class="job-footer">
          <a href="/career/ugc-content-creator" target="_self" class="job-link">View Details →</a>
        </div>
      </div>
    </div>
  </div>

  <div class="why-apateu">
    <h2 class="section-title">Why Apateu?</h2>
    <div class="benefits-grid">
      <div class="benefit-item">
        <div class="benefit-icon">🚀</div>
        <h4>Growth Opportunity</h4>
        <p>Join an early-stage startup with massive growth potential</p>
      </div>
      <div class="benefit-item">
        <div class="benefit-icon">💡</div>
        <h4>Innovation Focus</h4>
        <p>Work with cutting-edge AI and fintech technologies</p>
      </div>
      <div class="benefit-item">
        <div class="benefit-icon">🏠</div>
        <h4>Remote Friendly</h4>
        <p>Flexible work arrangements with optional LA office access</p>
      </div>
      <div class="benefit-item">
        <div class="benefit-icon">🎓</div>
        <h4>Impact Mission</h4>
        <p>Help solve real problems for students and young professionals</p>
      </div>
    </div>
  </div>

  <div class="no-openings">
    <h3>Don't see a perfect match?</h3>
    <p>We're always looking for talented individuals who share our vision. Send us your resume and tell us how you'd like to contribute to Apateu's mission.</p>
    <a href="mailto:apateu.app@gmail.com" class="contact-button">Get In Touch</a>
  </div>
</div>

<style>
.career-hero {
  text-align: center;
  padding: 4rem 0 3rem;
  background: linear-gradient(135deg, 
    rgba(173, 216, 230, 0.8) 0%,    /* Light Blue */
    rgba(221, 160, 221, 0.6) 35%,   /* Soft Lavender */
    rgba(255, 218, 185, 0.7) 70%,   /* Warm Peach */
    rgba(255, 255, 255, 0.9) 100%   /* White */
  );
  backdrop-filter: blur(20px);
  border-radius: 40px;
  position: relative;
  margin: -2rem -2rem 3rem -2rem;
  overflow: hidden;
}

.career-hero::before {
  content: '';
  position: absolute;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
  background: linear-gradient(45deg,
    rgba(255, 255, 255, 0.3) 0%,
    rgba(173, 216, 230, 0.2) 25%,
    rgba(221, 160, 221, 0.15) 50%,
    rgba(255, 218, 185, 0.2) 75%,
    rgba(255, 255, 255, 0.3) 100%
  );
  filter: blur(1px);
  z-index: 1;
}

.career-hero > * {
  position: relative;
  z-index: 2;
}

.career-title {
  font-size: 3rem;
  font-weight: 700;
  color: #000000;
  margin-bottom: 1rem;
}

.career-subtitle {
  font-size: 1.25rem;
  color: #666666;
  max-width: 600px;
  margin: 0 auto;
}

.career-content {
  max-width: 1200px;
  margin: 0 auto;
  padding: 0 2rem;
}

.career-intro {
  text-align: center;
  margin-bottom: 4rem;
}

.career-intro p {
  font-size: 1.1rem;
  color: #555555;
  max-width: 800px;
  margin: 0 auto;
  line-height: 1.6;
}

.section-title {
  font-size: 2.5rem;
  font-weight: 600;
  color: #000000;
  text-align: center;
  margin-bottom: 3rem;
}

.job-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(350px, 1fr));
  gap: 2rem;
  margin-bottom: 4rem;
}

.job-card {
  background: #ffffff;
  border: 1px solid #e5e7eb;
  border-radius: 16px;
  padding: 2rem;
  transition: all 0.3s ease;
  box-shadow: 0 2px 8px rgba(0, 0, 0, 0.04);
}

.job-card:hover {
  transform: translateY(-4px);
  box-shadow: 0 8px 24px rgba(139, 92, 246, 0.15);
  border-color: #8b5cf6;
}

.job-header {
  display: flex;
  justify-content: between;
  align-items: flex-start;
  margin-bottom: 1rem;
  flex-wrap: wrap;
  gap: 0.5rem;
}

.job-title {
  font-size: 1.5rem;
  font-weight: 600;
  color: #000000;
  margin: 0;
  flex: 1;
}

.job-type {
  background: #f3f4f6;
  color: #374151;
  padding: 0.25rem 0.75rem;
  border-radius: 20px;
  font-size: 1.1rem;
  font-weight: 500;
}

.job-details {
  margin-bottom: 1.5rem;
}

.job-location, .job-department {
  font-size: 1.2rem;
  color: #8b5cf6;
  font-weight: 500;
  margin-bottom: 0.5rem;
}

.job-description {
  color: #555555;
  line-height: 1.6;
  margin: 1rem 0;
}

.job-footer {
  border-top: 1px solid #f3f4f6;
  padding-top: 1.5rem;
}

.job-link {
  color: #8b5cf6;
  text-decoration: none;
  font-weight: 600;
  font-size: 1rem;
  transition: color 0.2s ease;
}

.job-link:hover {
  color: #7c3aed;
}

.why-apateu {
  margin: 4rem 0;
  padding: 3rem;
  background: #f8f9ff;
  border-radius: 24px;
}

.benefits-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 2rem;
  margin-top: 2rem;
}

.benefit-item {
  text-align: center;
  padding: 1rem;
}

.benefit-icon {
  font-size: 3rem;
  margin-bottom: 1rem;
}

.benefit-item h4 {
  font-size: 1.25rem;
  font-weight: 600;
  color: #000000;
  margin-bottom: 0.5rem;
}

.benefit-item p {
  color: #666666;
  line-height: 1.5;
}

.no-openings {
  text-align: center;
  padding: 3rem 2rem;
  background: #ffffff;
  border: 2px dashed #e5e7eb;
  border-radius: 16px;
  margin: 3rem 0;
}

.no-openings h3 {
  font-size: 1.5rem;
  color: #000000;
  margin-bottom: 1rem;
}

.no-openings p {
  color: #666666;
  margin-bottom: 2rem;
  max-width: 500px;
  margin-left: auto;
  margin-right: auto;
}

.contact-button {
  display: inline-block;
  background: #8b5cf6;
  color: #ffffff;
  padding: 1rem 2rem;
  border-radius: 8px;
  text-decoration: none;
  font-weight: 600;
  transition: background-color 0.2s ease;
}

.contact-button:hover {
  background: #7c3aed;
  color: #ffffff;
}

@media (max-width: 768px) {
  .career-title {
    font-size: 2.5rem;
  }
  
  .career-hero {
    padding: 3rem 1rem 2rem;
    margin: -1rem -1rem 2rem -1rem;
  }
  
  .career-content {
    padding: 0 1rem;
  }
  
  .job-grid {
    grid-template-columns: 1fr;
    gap: 1.5rem;
  }
  
  .job-card {
    padding: 1.5rem;
  }
  
  .why-apateu {
    padding: 2rem 1.5rem;
  }
  
  .benefits-grid {
    grid-template-columns: 1fr;
    gap: 1.5rem;
  }
}
</style>