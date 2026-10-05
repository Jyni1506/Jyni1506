## Hi I'm Jiya👋

<H2>Data Analyst</H2>

<p>I'm an aspiring Data Analyst with a strong interest in Data Analytics and Data Science, passionate about turning raw data into meaningful insights and solving real-world problems through analytical thinking.</p>

📊 Currently learning & working with:

- Python
- SQL
- Excel
- Power BI & Tableau
- Data Visualization
- Data Analysis & DAX

🚀 I'm building my skills through hands-on training and practical projects, working with real-world datasets and exploring how data can be used to make better decisions.

🎯 My goal: Build a strong portfolio of practical data projects, continuously improve my analytical and technical skills, and grow toward a career in Data Analytics and Data Science.

💡 Always learning. Always building. Always curious about data.
<html>
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <style>
    :root {
      --primary: #3E3D53;
      --secondary: #F5F5F5;
      --accent: #6E64C3;
      --text: #333;
      --light-text: #777;
      --white: #fff;
      --shadow: rgba(0, 0, 0, 0.08);
      --badge-1: #E5F7FF;
      --badge-2: #F0EBFF;
      --badge-3: #FFEDE0;
      --hover-transition: 0.3s cubic-bezier(0.25, 0.8, 0.25, 1);
    }
    
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Inter', -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, sans-serif;
    }
    
    body {
      width: 100%;
      height: 100vh;
      display: flex;
      align-items: center;
      justify-content: center;
      background-color: var(--secondary);
      color: var(--text);
      padding: 20px;
    }
    
    .card-container {
      width: 100%;
      max-width: 650px;
      height: auto;
      perspective: 1000px;
      position: relative;
    }
    
    .profile-card {
      width: 100%;
      background-color: var(--white);
      border-radius: 16px;
      box-shadow: 0 10px 25px var(--shadow);
      padding: 32px;
      position: relative;
      overflow: hidden;
      transition: transform var(--hover-transition), box-shadow var(--hover-transition);
      transform-style: preserve-3d;
    }
    
    .profile-card:hover {
      box-shadow: 0 15px 35px rgba(0, 0, 0, 0.12);
      transform: translateY(-5px);
    }
    
    .header {
      display: flex;
      align-items: center;
      gap: 24px;
      margin-bottom: 28px;
      position: relative;
    }
    
    .profile-image {
      width: 95px;
      height: 95px;
      border-radius: 50%;
      object-fit: cover;
      border: 3px solid var(--white);
      box-shadow: 0 4px 10px var(--shadow);
      transition: transform 0.4s ease;
    }
    
    .profile-card:hover .profile-image {
      transform: scale(1.05);
    }
    
    .header-details {
      flex: 1;
    }
    
    .name {
      font-size: 24px;
      font-weight: 700;
      margin-bottom: 5px;
      letter-spacing: -0.5px;
      color: var(--primary);
    }
    
    .title {
      font-size: 16px;
      font-weight: 500;
      color: var(--accent);
      margin-bottom: 8px;
    }
    
    .location {
      font-size: 14px;
      color: var(--light-text);
      display: flex;
      align-items: center;
      gap: 4px;
    }
    
    .location svg {
      width: 14px;
      height: 14px;
    }
    
    .status {
      position: absolute;
      top: 0;
      right: 0;
      background-color: rgba(110, 100, 195, 0.1);
      color: var(--accent);
      padding: 5px 15px;
      border-radius: 20px;
      font-size: 12px;
      font-weight: 600;
      display: flex;
      align-items: center;
      gap: 5px;
    }
    
    .status-dot {
      width: 8px;
      height: 8px;
      background-color: #6E64C3;
      border-radius: 50%;
      animation: pulse 2s infinite;
    }
    
    .about {
      margin-bottom: 28px;
      line-height: 1.6;
      color: var(--text);
      font-size: 15px;
      position: relative;
      max-height: 70px;
      overflow: hidden;
    }
    
    .about.expanded {
      max-height: 1000px;
      transition: max-height 0.5s ease;
    }
    
    .read-more {
      position: absolute;
      bottom: 0;
      right: 0;
      font-size: 12px;
      font-weight: 600;
      color: var(--accent);
      background-color: var(--white);
      cursor: pointer;
      padding-left: 8px;
    }
    
    .skills-section {
      margin-bottom: 20px;
    }
    
    .section-title {
      font-size: 15px;
      font-weight: 600;
      margin-bottom: 12px;
      color: var(--primary);
      letter-spacing: -0.3px;
      position: relative;
      display: inline-block;
    }
    
    .section-title::after {
      content: '';
      position: absolute;
      bottom: -3px;
      left: 0;
      width: 100%;
      height: 2px;
      background-color: var(--accent);
      transform: scaleX(0);
      transform-origin: left;
      transition: transform 0.3s ease;
    }
    
    .profile-card:hover .section-title::after {
      transform: scaleX(1);
    }
    
    .badges {
      display: flex;
      flex-wrap: wrap;
      gap: 10px;
      margin-bottom: 20px;
    }
    
    .badge {
      padding: 6px 16px;
      border-radius: 20px;
      font-size: 13px;
      font-weight: 500;
      background-color: var(--badge-1);
      cursor: pointer;
      transition: all 0.2s ease;
      position: relative;
    }
    
    .badge:nth-child(3n+2) {
      background-color: var(--badge-2);
    }
    
    .badge:nth-child(3n+3) {
      background-color: var(--badge-3);
    }
    
    .badge:hover {
      transform: translateY(-2px);
      box-shadow: 0 5px 15px rgba(0, 0, 0, 0.08);
    }
    
    .badge::before {
      content: attr(data-level);
      position: absolute;
      bottom: calc(100% + 5px);
      left: 50%;
      transform: translateX(-50%) scale(0);
      background-color: var(--primary);
      color: var(--white);
      padding: 4px 8px;
      border-radius: 4px;
      font-size: 11px;
      opacity: 0;
      transition: all 0.2s ease;
      white-space: nowrap;
      pointer-events: none;
    }
    
    .badge:hover::before {
      opacity: 1;
      transform: translateX(-50%) scale(1);
    }
    
    .badge::after {
      content: '';
      position: absolute;
      top: -5px;
      left: 50%;
      transform: translateX(-50%) rotate(45deg) scale(0);
      width: 8px;
      height: 8px;
      background-color: var(--primary);
      opacity: 0;
      transition: all 0.2s ease;
    }
    
    .badge:hover::after {
      opacity: 1;
      transform: translateX(-50%) rotate(45deg) scale(1);
    }
    
    .testimonials-slider {
      margin-bottom: 25px;
      overflow: hidden;
      position: relative;
    }
    
    .testimonials {
      display: flex;
      transition: transform 0.5s ease;
    }
    
    .testimonial {
      flex: 0 0 100%;
      padding: 16px;
      background-color: var(--secondary);
      border-radius: 10px;
      margin-right: 10px;
    }
    
    .testimonial-content {
      font-size: 14px;
      font-style: italic;
      margin-bottom: 8px;
      line-height: 1.6;
    }
    
    .testimonial-author {
      font-size: 13px;
      font-weight: 600;
      color: var(--accent);
    }
    
    .testimonial-company {
      font-size: 12px;
      color: var(--light-text);
    }
    
    .slider-controls {
      display: flex;
      justify-content: center;
      gap: 5px;
      margin-top: 10px;
    }
    
    .slider-dot {
      width: 8px;
      height: 8px;
      border-radius: 50%;
      background-color: #ddd;
      cursor: pointer;
      transition: all 0.3s ease;
    }
    
    .slider-dot.active {
      background-color: var(--accent);
      width: 20px;
      border-radius: 10px;
    }
    
    .footer {
      display: flex;
      justify-content: space-between;
      align-items: center;
      position: relative;
    }
    
    .stats {
      display: flex;
      gap: 15px;
    }
    
    .stat {
      display: flex;
      flex-direction: column;
      align-items: center;
    }
    
    .stat-value {
      font-size: 20px;
      font-weight: 700;
      color: var(--primary);
    }
    
    .stat-label {
      font-size: 12px;
      color: var(--light-text);
      text-transform: uppercase;
      letter-spacing: 0.5px;
    }
    
    .actions {
      display: flex;
      gap: 12px;
    }
    
    .btn {
      padding: 10px 20px;
      border: none;
      border-radius: 8px;
      font-weight: 600;
      font-size: 14px;
      cursor: pointer;
      transition: all 0.2s ease;
      display: flex;
      align-items: center;
      gap: 8px;
    }
    
    .btn-primary {
      background-color: var(--accent);
      color: var(--white);
    }
    
    .btn-primary:hover {
      background-color: #5a52a3;
      transform: translateY(-2px);
      box-shadow: 0 5px 15px rgba(110, 100, 195, 0.3);
    }
    
    .btn-secondary {
      background-color: var(--white);
      color: var(--primary);
      border: 1px solid var(--primary);
    }
    
    .btn-secondary:hover {
      background-color: var(--primary);
      color: var(--white);
      transform: translateY(-2px);
      box-shadow: 0 5px 15px rgba(62, 61, 83, 0.2);
    }
    
    .wave {
      position: absolute;
      bottom: -50px;
      left: 0;
      width: 100%;
      height: 60px;
      background: url('data:image/svg+xml;utf8,<svg viewBox="0 0 1440 320" xmlns="http://www.w3.org/2000/svg"><path fill="%236E64C3" fill-opacity="0.05" d="M0,192L48,202.7C96,213,192,235,288,224C384,213,480,171,576,165.3C672,160,768,192,864,213.3C960,235,1056,245,1152,234.7C1248,224,1344,192,1392,176L1440,160L1440,320L1392,320C1344,320,1248,320,1152,320C1056,320,960,320,864,320C768,320,672,320,576,320C480,320,384,320,288,320C192,320,96,320,48,320L0,320Z"></path></svg>');
      background-size: cover;
      z-index: -1;
    }
    
    .endorsement-badge {
      position: absolute;
      top: 10px;
      right: 10px;
      width: 30px;
      height: 30px;
      border-radius: 50%;
      background-color: #FFF3DC;
      display: flex;
      align-items: center;
      justify-content: center;
      cursor: pointer;
      transition: all 0.3s ease;
    }
    
    .endorsement-badge:hover {
      transform: scale(1.1);
      background-color: #FFDC91;
    }
    
    .endorsement-badge svg {
      width: 16px;
      height: 16px;
      color: #F6B93B;
    }
    
    @keyframes pulse {
      0% {
        transform: scale(0.95);
        opacity: 0.8;
      }
      70% {
        transform: scale(1);
        opacity: 1;
      }
      100% {
        transform: scale(0.95);
        opacity: 0.8;
      }
    }
    
    /* Responsive styles */
    @media screen and (max-width: 600px) {
      .profile-card {
        padding: 20px;
      }
      
      .header {
        flex-direction: column;
        text-align: center;
        gap: 15px;
      }
      
      .profile-image {
        margin: 0 auto;
      }
      
      .status {
        position: relative;
        margin-top: 10px;
        align-self: center;
      }
      
      .footer {
        flex-direction: column;
        gap: 20px;
      }
      
      .actions {
        width: 100%;
        justify-content: center;
      }
      
      .stats {
        width: 100%;
        justify-content: space-around;
      }
    }
  </style>
</head>
<body>
  <div class="card-container">
    <div class="profile-card">
      <div class="header">
        
        <div class="header-details">
          <h1 class="name">Jiya Shukla</h1>
          <p class="title">Data Analyst</p>
          <p class="location">
            <svg viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
              <path d="M12 2C8.13 2 5 5.13 5 9C5 14.25 12 22 12 22C12 22 19 14.25 19 9C19 5.13 15.87 2 12 2ZM12 11.5C10.62 11.5 9.5 10.38 9.5 9C9.5 7.62 10.62 6.5 12 6.5C13.38 6.5 14.5 7.62 14.5 9C14.5 10.38 13.38 11.5 12 11.5Z" fill="currentColor"/>
            </svg>
            Ahmedabad
          </p>
          <div class="status">
            <span class="status-dot"></span>
            Student
          </div>
        </div>
      </div>
      
      <div class="about">
        I'm an aspiring Data Analyst with a strong interest in Data Analytics and Data Science, passionate about turning raw data into meaningful insights and solving real-world problems through analytical thinking.
      </div>
            
      <div class="skills-section">
        <h3 class="section-title">Currently learning & working with:</h3>
        <div class="badges">
          <span class="badge">Python</span>
          <span class="badge"> SQL</span>
          <span class="badge">Excel</span>
          <span class="badge">Power BI & Tableau</span>
          <span class="badge">Data Visualization</span>
          <span class="badge">Data Analysis & DAX</span>
        </div>
      </div>
      
      <div class="about">
        <h3 class="section-title">Work</h3>
       I'm building my skills through hands-on training and practical projects, working with real-world datasets and exploring how data can be used to make better decisions.
      </div>       
       
      <div class="Goal">
        <h3 class="section-title">My Goal:</h3>
      Build a strong portfolio of practical data projects, continuously improve my analytical and technical skills, and grow toward a career in Data Analytics and Data Science.
      </div>

      <div class="wave"></div>
    </div>
  </div>

  <script>
    document.addEventListener('DOMContentLoaded', function() {
      // About section toggle
      const aboutSection = document.querySelector('.about');
      const readMoreBtn = document.querySelector('.read-more');
      
      readMoreBtn.addEventListener('click', function() {
        aboutSection.classList.toggle('expanded');
        readMoreBtn.textContent = aboutSection.classList.contains('expanded') ? 'Read less' : 'Read more';
      });
      
      // Testimonial slider
      const testimonialsContainer = document.querySelector('.testimonials');
      const sliderDots = document.querySelectorAll('.slider-dot');
      let currentSlide = 0;
      const slideWidth = 100; // Percentage
      
      function goToSlide(index) {
        currentSlide = index;
        testimonialsContainer.style.transform = `translateX(-${slideWidth * index}%)`;
        
        // Update active dot
        sliderDots.forEach((dot, i) => {
          dot.classList.toggle('active', i === index);
        });
      }
      
      // Initialize slider controls
      sliderDots.forEach((dot, index) => {
        dot.addEventListener('click', () => goToSlide(index));
      });
      
      // Auto slide
      let slideInterval = setInterval(() => {
        currentSlide = (currentSlide + 1) % sliderDots.length;
        goToSlide(currentSlide);
      }, 5000);
      
      // Pause auto-slide on hover
      testimonialsContainer.addEventListener('mouseenter', () => {
        clearInterval(slideInterval);
      });
      
      testimonialsContainer.addEventListener('mouseleave', () => {
        slideInterval = setInterval(() => {
          currentSlide = (currentSlide + 1) % sliderDots.length;
          goToSlide(currentSlide);
        }, 5000);
      });
      
      // Badge interactions
      const badges = document.querySelectorAll('.badge');
      badges.forEach(badge => {
        badge.addEventListener('click', function() {
          this.style.transform = 'scale(1.1)';
          setTimeout(() => {
            this.style.transform = '';
          }, 300);
        });
      });
      
      // Endorsement badges
      const endorsementBadges = document.querySelectorAll('.endorsement-badge');
      endorsementBadges.forEach(badge => {
        badge.addEventListener('click', function() {
          this.style.transform = 'scale(1.3)';
          this.style.backgroundColor = '#FFDC91';
          setTimeout(() => {
            this.style.transform = 'scale(1.1)';
          }, 300);
        });
      });
    });
  </script>
</body>
</html>
