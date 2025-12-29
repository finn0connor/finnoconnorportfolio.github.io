---
permalink: /projects/
---

<link rel="stylesheet" href="/finnoconnorportfolio.github.io/style.css">

<div class="wrap">
  <div class="nav">
    <div class="brand">
      <strong>Projects</strong>
      <span>Summary + embedded project files</span>
    </div>
    <div class="links">
      <a class="pill" href="/finnoconnorportfolio.github.io/">Home</a>
      <a class="pill" href="/finnoconnorportfolio.github.io/about/">About</a>
      <a class="pill" href="/finnoconnorportfolio.github.io/assets/pdfs/CV.pdf">CV</a>
      <a class="pill" href="https://github.com/finn0connor">GitHub</a>
    </div>
  </div>

  <div class="grid">

    <!-- PROJECT: 4B7 Smartphone Chassis Design -->
    <div class="card">
      <h2>FEA Smartphone Chassis Design”</h2>
      <div class="meta">
        Lightweight, stiff phone chassis optimised for strength + thermal performance using simulation-led design.
      </div>

      <div class="tags">
        <span class="tag">Computer Aided Design</span>
        <span class="tag">SolidWorks</span>
        <span class="tag">Finite Element Analysis (FEA)</span>
        <span class="tag">Thermal Simulation</span>
        <span class="tag">Mesh Refinement</span>
        <span class="tag">Optimisation</span>
        <span class="tag">MATLAB</span>
      </div>

      <div class="details" style="display:flex; flex-direction:column; gap:10px;">

        <details>
          <summary>Project Summary</summary>

          <p><strong>Goal:</strong> To design a premium smartphone chassis that was lightweight and aesthetic, with good performace against bending and torsional stresses, as well as good thermal performance to withstand battery and CPU heat transfer.</p>

          <p><strong>What we did:</strong></p>
          <ul>
            <li>Researched candidate materials (incl. 6061-T6 aluminium and AZ91D magnesium) and compared stiffness, strength, density, and thermal conductivity.</li>
            <li>Built a simulation workflow with mesh-independence studies to ensure results were stable (including targeted mesh controls and h-adaptive refinement).</li>
            <li>Ran structural load cases (simple bending + torsion/bending) to validate stiffness/deflection and stress behaviour.</li>
            <li>Ran thermal analyses with CPU + battery heat flux and convection; improved cooling using a graphene layer, high-emissivity anodised surface (radiation), and vent perforations.</li>
          </ul>

          <p><strong>Final outcome (highlights):</strong></p>
          <ul>
            <li><strong>Mass:</strong> 143.5 g</li>
            <li><strong>Stiffness (bending):</strong> ~1,247 N/mm (specific stiffness ~8.7 (N/mm)/g)</li>
            <li><strong>Strength ratio:</strong> ~4.7% (well below yield → large safety margin)</li>
            <li><strong>Max temperature:</strong> ~35.2°C after thermal improvements</li>
            <li><strong>Thermal resistance:</strong> ~4.3 K/W (improved vs baseline)</li>
          </ul>

        </details>

        <details>
          <summary>Project File</summary>

          <p class="meta">
            If the embedded viewer doesn’t load in your browser, use:
            <a class="pill"
               href="/finnoconnorportfolio.github.io/assets/pdfs/4B7_Assignment_2_Group_4_Report.pdf"
               target="_blank" rel="noopener">Open PDF</a>
          </p>

          <div style="margin-top:12px; border:1px solid var(--border); border-radius:14px; overflow:hidden;">
            <object
              data="/finnoconnorportfolio.github.io/assets/pdfs/4B7_Assignment_2_Group_4_Report.pdf"
              type="application/pdf"
              width="100%"
              height="700"
              style="display:block; border:0; background:rgba(255,255,255,.02);">
              <iframe
                src="/finnoconnorportfolio.github.io/assets/pdfs/4B7_Assignment_2_Group_4_Report.pdf"
                width="100%"
                height="700"
                style="border:0; background:rgba(255,255,255,.02);">
              </iframe>
            </object>
          </div>
        </details>

      </div>
    </div>

  </div>

  <div class="footer">
    <a class="pill" href="/finnoconnorportfolio.github.io/">← Back home</a>
  </div>
</div>
