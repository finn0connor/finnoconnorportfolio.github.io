---
layout: default
---

<link rel="stylesheet" href="{{ site.baseurl }}/style.css">

<div class="wrap">
  <div class="nav">
    <div class="brand">
      <strong>Projects</strong>
      <span>Summary + embedded project files</span>
    </div>
    <div class="links">
      <a class="pill" href="{{ site.baseurl }}/">Home</a>
      <a class="pill" href="{{ site.baseurl }}/about">About</a>
      <a class="pill" href="{{ site.baseurl }}/assets/pdfs/CV.pdf">CV</a>
      <a class="pill" href="https://github.com/finn0connor">GitHub</a>
    </div>
  </div>

  <div class="grid">

    <!-- ===================== PROJECT 1 ===================== -->
    <div class="card">
      <h2>Project Title 1</h2>
      <div class="meta">One-line hook: what it is + outcome (e.g., “Realtime tracking at 30 FPS”).</div>

      <div class="tags">
        <span class="tag">Python</span>
        <span class="tag">OpenCV</span>
        <span class="tag">Algorithms</span>
      </div>

      <div class="details">

        <details>
          <summary>Project Summary</summary>
          <p><strong>Problem:</strong> What problem you solved (1–2 lines).</p>
          <p><strong>Approach:</strong> How you solved it (1–2 lines).</p>

          <ul>
            <li><strong>Key work:</strong> Bullet with your contribution</li>
            <li><strong>Key work:</strong> Bullet with your contribution</li>
            <li><strong>Result:</strong> Metric / performance / outcome</li>
          </ul>

          <p><strong>Links:</strong>
            <a class="pill" href="REPLACE_WITH_REPO_LINK">Code</a>
            <a class="pill" href="REPLACE_WITH_DEMO_LINK">Demo</a>
          </p>
        </details>

        <details>
          <summary>Project File</summary>

          <p class="meta">
            If the embedded viewer doesn’t load in your browser, use:
            <a class="pill" href="{{ site.baseurl }}/assets/pdfs/PROJECT1.pdf" target="_blank" rel="noopener">Open PDF</a>
          </p>

          <div style="margin-top:12px; border:1px solid var(--border); border-radius:14px; overflow:hidden;">
            <iframe
              src="{{ site.baseurl }}/assets/pdfs/4B7 Assignment 2 Group 4 Report.pdf"
              width="100%"
              height="650"
              style="border:0; background:rgba(255,255,255,.02);">
            </iframe>
          </div>
        </details>

      </div>
    </div>

    <!-- ===================== PROJECT 2 ===================== -->
    <div class="card">
      <h2>Project Title 2</h2>
      <div class="meta">One-line hook.</div>

      <div class="tags">
        <span class="tag">ROS2</span>
        <span class="tag">SLAM</span>
        <span class="tag">Robotics</span>
      </div>

      <div class="details">

        <details>
          <summary>Project Summary</summary>
          <p><strong>Problem:</strong> …</p>
          <p><strong>Approach:</strong> …</p>

          <ul>
            <li>…</li>
            <li>…</li>
            <li><strong>Result:</strong> …</li>
          </ul>

          <p><strong>Links:</strong>
            <a class="pill" href="REPLACE_WITH_REPO_LINK">Code</a>
          </p>
        </details>

        <details>
          <summary>Project File</summary>

          <p class="meta">
            Fallback link:
            <a class="pill" href="{{ site.baseurl }}/assets/pdfs/PROJECT2.pdf" target="_blank" rel="noopener">Open PDF</a>
          </p>

          <div style="margin-top:12px; border:1px solid var(--border); border-radius:14px; overflow:hidden;">
            <iframe
              src="{{ site.baseurl }}/assets/pdfs/PROJECT2.pdf"
              width="100%"
              height="650"
              style="border:0; background:rgba(255,255,255,.02);">
            </iframe>
          </div>
        </details>

      </div>
    </div>

  </div>

  <div class="footer">
    <a class="pill" href="{{ site.baseurl }}/">← Back home</a>
  </div>
</div>
