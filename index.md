---
layout: default
---

<link rel="stylesheet" href="{{ site.baseurl }}/style.css">

<div class="wrap">
  <div class="nav">
    <div class="brand">
      <strong>Finn O’Connor</strong>
      <span>Portfolio • Projects • CV</span>
    </div>
    <div class="links">
      <a class="pill" href="{{ site.baseurl }}/">Home</a>
      <a class="pill" href="{{ site.baseurl }}/projects">Projects</a>
      <a class="pill" href="{{ site.baseurl }}/about">About</a>
      <a class="pill" href="{{ site.baseurl }}/assets/pdfs/CV.pdf">CV</a>
      <a class="pill" href="https://github.com/finn0connor">GitHub</a>
    </div>
  </div>

  <div class="hero">
    <h1>Building practical systems.</h1>
    <p class="sub">
      I’m Finn — I like turning ideas into clean, working projects. Below are a few highlights with quick technical details and links.
    </p>

    <div class="ctaRow">
      <a class="btn primary" href="{{ site.baseurl }}/projects">View projects <span>→</span></a>
      <a class="btn" href="{{ site.baseurl }}/assets/pdfs/CV.pdf">Download CV <span>↓</span></a>
      <a class="btn" href="mailto:YOUR_EMAIL_HERE">Email <span>✉</span></a>
    </div>
  </div>

  <div class="grid">
    <div class="card half">
      <h2>Featured Project — Title</h2>
      <div class="meta">One-line outcome or metric (e.g., “cut runtime by 40%”).</div>

      <div class="tags">
        <span class="tag">Python</span>
        <span class="tag">C++</span>
        <span class="tag">OpenCV</span>
      </div>

      <div class="details">
        <details>
          <summary>Details</summary>
          <p><strong>Overview:</strong> What you built and why it matters.</p>
          <p><strong>Your contribution:</strong> 2–3 bullets worth of your work.</p>
          <p><strong>Links:</strong>
            <a class="pill" href="REPLACE_WITH_REPO_LINK">Code</a>
            <a class="pill" href="REPLACE_WITH_DEMO_LINK">Demo</a>
          </p>
        </details>
      </div>
    </div>

    <div class="card half">
      <h2>Featured Project — Title</h2>
      <div class="meta">One-line outcome or metric.</div>

      <div class="tags">
        <span class="tag">ROS</span>
        <span class="tag">SLAM</span>
        <span class="tag">Robotics</span>
      </div>

      <div class="details">
        <details>
          <summary>Details</summary>
          <p><strong>Overview:</strong> What it does, in plain language.</p>
          <p><strong>Tech:</strong> What’s under the hood.</p>
          <p><strong>Links:</strong>
            <a class="pill" href="REPLACE_WITH_REPO_LINK">Code</a>
          </p>
        </details>
      </div>
    </div>

    <div class="card">
      <h2>What I’m looking for</h2>
      <p class="sub">
        Internships / placements / junior roles where I can work on software engineering, robotics, or applied ML —
        especially projects with real users and real constraints.
      </p>
      <hr>
      <p class="sub">
        For more, see the <a class="pill" href="{{ site.baseurl }}/projects">full projects page</a> or <a class="pill" href="{{ site.baseurl }}/about">about</a>.
      </p>
    </div>
  </div>

  <div class="footer">
    © {{ "now" | date: "%Y" }} Finn O’Connor • Built with GitHub Pages
  </div>
</div>
