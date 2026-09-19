---
hide:
  - toc
  - navigation
---
<!--
CHECKLIST FOR THIS PAGE:
- [ ] Replace [YOUR NAME] with your full name (3 places)
- [ ] Replace [YOUR JOB TITLE] with your current or target role
- [ ] Replace [YOUR TAGLINE] with a short phrase describing your focus
- [ ] Rewrite the About Me paragraph with your own words
- [ ] Replace assets/images/profile.png with your actual photo (keep the filename or update it below)
- [ ] Replace assets/images/about.png with your own image (a field photo, map, or workspace shot)
- [ ] Edit the skill cards to match your actual skills (add, remove, or rename cards as needed)
- [ ] Update GitHub and LinkedIn links in the Connect section
- [ ] Add your CV PDF to docs/assets/ and update the filename in the Download CV button
-->
<!-- Google tag (gtag.js) -->
<script async src="https://www.googletagmanager.com/gtag/js?id=G-T6F3SXP0GK"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());

  gtag('config', 'G-T6F3SXP0GK');
</script>


<div class="hero">
  <img src="assets/images/profile.png" alt="Ashwary Banik Dolan" class="profile-photo">
  <h1>Ashwary Banik Dolan</h1>
  <p><strong> Geoscientist & Geospatial Researcher </strong></p>
  <p><em>GIS | Remote Sensing | Hydrologic Modeling  | Machine Learning</em></p>
</div>

---

## About Me

<div class="about-section" markdown>
<div class="about-text" markdown>

I am a geoscientist interested in understanding how Earth and environmental systems respond to climate variability, land-use change, and natural disturbances. My research combines field observations, GIS, remote sensing, process-based modeling, and data-driven methods to investigate interactions among water, landscapes, and the atmosphere. I am particularly interested in interdisciplinary problems involving hydrologic processes, landscape change, environmental hazards, water quality, and climate, with an emphasis on integrating geospatial observations, numerical models, and machine learning and AI approaches to understand environmental change across scales.


</div>

<div class="about-image">
  <img src="assets/images/about.png" alt="About">
</div>

</div>

---

[View My Projects :material-arrow-right:](projects/index.md){ .md-button .md-button--primary }
[Download CV :material-download:](assets/ashwary-CV.pdf){ .md-button }


---
Research Work

My projects explore groundwater sustainability, groundwater flow, water-resource stress, and aquifer geometry through geospatial analysis and hydrogeological modeling.

<div class="home-research">

  <!-- Project 1: Groundwater sustainability -->

  <a class="home-project" href="projects/recharge/"
   aria-labelledby="home-project-recharge">

  <div class="home-project-image"
       style="position:relative;width:100%;aspect-ratio:1297/838;">

    <img id="project1-image"
         src="assets/images/image-1.jpg"
         alt="Maps from the Dhaka groundwater sustainability study"
         width="1297" height="838"
         style="position:absolute;inset:0;width:100%;height:100%;object-fit:contain;">

  </div>

  <script>
  (() => {
    const image = document.getElementById("project1-image");
    const files = ["image-1.jpg", "image-2.jpg", "placeholder-project.png"];
    let i = 0;

    const timer = setInterval(() => {
      if (!image.isConnected) return clearInterval(timer);
      if (document.getElementById("home-slideshow-pause")?.checked) return;

      i = (i + 1) % files.length;
      image.src = "assets/images/" + files[i];
    }, 1000);
  })();
  </script>
    <div class="home-project-content">
      <span class="home-project-label">Groundwater Sustainability</span>
      <h3 id="home-project-recharge">GIS-Based Groundwater Budget of the Dhaka Watershed</h3>
      <p>Assessed how urbanization has changed groundwater recharge across the Dhaka watershed by combining satellite-based land-use classification with WetSpass-M water-balance modeling.</p>
      <p>The project connects land-use change with spatial patterns of recharge, runoff, and groundwater sustainability.</p>
      <div class="home-project-tags">
        <span>Google Earth Engine</span>
        <span>ArcGIS Pro</span>
        <span>WetSpass-M</span>
      </div>
      <span class="home-project-link">View project <span aria-hidden="true">&rarr;</span></span>
    </div>
  </a>

  <!-- Project 2: Groundwater flow modeling -->

<a class="home-project" href="projects/dwasa/"
   aria-labelledby="home-project-dwasa">

  <div class="home-project-image"
       style="position:relative;width:100%;aspect-ratio:1309/809;">

    <img id="project2-image"
         src="assets/images/image-3.jpg"
         alt="Groundwater flow modeling of the Dhaka watershed"
         width="1309" height="809"
         style="position:absolute;inset:0;width:100%;height:100%;object-fit:contain;">

  </div>

  <script>
  (() => {
    const image = document.getElementById("project2-image");
    const files = ["image-3.jpg", "image-4.png"];
    let i = 0;

    const timer = setInterval(() => {
      if (!image.isConnected) return clearInterval(timer);
      if (document.getElementById("home-slideshow-pause")?.checked) return;

      i = (i + 1) % files.length;
      image.src = "assets/images/" + files[i];
    }, 1000);
  })();
  </script>
    <div class="home-project-content">
      <span class="home-project-label">Numerical Groundwater Modeling</span>
      <h3 id="home-project-dwasa">3D Groundwater Flow Modeling of the Dhaka Watershed</h3>
      <p>Contributed to a regional MODFLOW 6 model to investigate long-term groundwater depletion in Dhaka and surrounding areas.</p>
      <p>The model represents a layered aquifer system, groundwater abstraction, recharge, and river–aquifer interaction, with calibration against observed groundwater levels.</p>
      <div class="home-project-tags">
        <span>MODFLOW 6</span>
        <span>ModelMuse</span>
        <span>ArcGIS Pro</span>
        <span>Python</span>
      </div>
      <span class="home-project-link">View project <span aria-hidden="true">&rarr;</span></span>
    </div>
  </a>

  <!-- Project 3: Groundwater stress -->

 <a class="home-project" href="projects/gw_stress/"
   aria-labelledby="home-project-stress">

  <div class="home-project-image"
       style="position:relative;width:100%;aspect-ratio:1188/748;">

    <img id="project3-image"
         src="assets/images/gw-stress-final.jpg"
         alt="Groundwater stress assessment of Muradnagar Upazila"
         width="1188" height="748"
         style="position:absolute;inset:0;width:100%;height:100%;object-fit:contain;">

  </div>

  <script>
  (() => {
    const image = document.getElementById("project3-image");
    const files = [
      "gw-stress-final.jpg",
      "cropland.jpg",
      "domestic-demand.jpg",
      "irrigation-demand.jpg",
      "total-use.jpg",
      "recharge.jpg"
    ];
    let i = 0;

    const timer = setInterval(() => {
      if (!image.isConnected) return clearInterval(timer);
      if (document.getElementById("home-slideshow-pause")?.checked) return;

      i = (i + 1) % files.length;
      image.src = "assets/images/" + files[i];
    }, 1000);
  })();
  </script>
    <div class="home-project-content">
      <span class="home-project-label">Water-Resource Assessment</span>
      <h3 id="home-project-stress">Groundwater Stress and Vulnerability Assessment</h3>
      <p>Assessed groundwater stress in Muradnagar Upazila by comparing domestic and irrigation demand with renewable groundwater availability.</p>
      <p>Integrated recharge, return flow, and environmental-flow requirements in GIS to identify areas facing greater pressure on groundwater resources.</p>
      <div class="home-project-tags">
        <span>Google Earth Engine</span>
        <span>ArcGIS Pro</span>
        <span>WetSpass</span>
      </div>
      <span class="home-project-link">View project <span aria-hidden="true">&rarr;</span></span>
    </div>
  </a>

  <!-- Project 4: Aquifer geometry -->

<a class="home-project" href="projects/aquifer/"
   aria-labelledby="home-project-aquifer">

  <div class="home-project-image"
       style="position:relative;width:100%;aspect-ratio:1226/611;">
    <img id="project4-image"
         src="assets/images/rockworks-1.jpg"
         alt="Aquifer geometry analysis using RockWorks"
         width="1226" height="611"
         style="position:absolute;inset:0;width:100%;height:100%;object-fit:contain;">
  </div>

  <script>
  (() => {
    const image = document.getElementById("project4-image");
    const files = ["rockworks-1.jpg", "rockworks-2.jpg", "aquifer.jpg"];
    let i = 0;

    const timer = setInterval(() => {
      if (!image.isConnected) return clearInterval(timer);
      if (document.getElementById("home-slideshow-pause")?.checked) return;

      i = (i + 1) % files.length;
      image.src = "assets/images/" + files[i];
    }, 1000);
  })();
  </script>
    <div class="home-project-content">
      <span class="home-project-label">Subsurface Characterization</span>
      <h3 id="home-project-aquifer">Aquifer Geometry Analysis Using RockWorks</h3>
      <p>Analyzed primary and secondary borehole lithology records to interpret the subsurface distribution and thickness of aquifers.</p>
      <p>Developed lithological striplogs and regional cross sections in RockWorks to identify probable aquifer units and understand their geometry.</p>
      <div class="home-project-tags">
        <span>RockWorks</span>
        <span>Borehole Analysis</span>
        <span>Lithological Cross Sections</span>
      </div>
      <span class="home-project-link">View project <span aria-hidden="true">&rarr;</span></span>
    </div>
  </a>

</div>

---

## Skills

<div class="grid cards" markdown>

-   :material-layers:{ .lg .middle } **GIS & Remote Sensing**

    ---

    - QGIS, ArcGIS Pro, Google Earth Engine
    - ENVI, ERDAS IMAGINE, SNAP
    - GDAL, Rasterio, Xarray 
    - Data formats: GeoJSON, GeoTIFF, NetCDF
    - Multispectral & Sentinel time series analysis
    - LULC classification (103-class, plot-level)
    - FLUS , PLUS model — future LULC prediction

-   :material-water:{ .lg .middle } **Hydrologic & Climate Modeling**

    ---

    - MODFLOW 6, Model Muse, WetSpass, SWAT, RockWorks, HEC-HMS
    - Hydrochemical & Water quality analysis
    - WRF, CMIP6, ECMWF
    - Ensemble & Downscaling

-   :material-terrain:{ .lg .middle } **Geophysical & Geotechnical**

    ---

    - VES, ERT surveys
    - SPT analysis, Soil profiling, Bearing capacity assessment
    - GeoStudio
    - Stratigraphic logging, Structural mapping

-   :material-code-braces:{ .lg .middle } **Programming**

    ---

    - Python — GeoPandas, NumPy, Pandas, Matplotlib ,Seaborn
    - R — sf, terra, ggplot2
    - JavaScript


-   :material-star-four-points:{ .lg .middle } **Machine Learning & GeoAI**

    ---

    - Supervised classification 
    - scikit-learn, PyTorch, TensorFlow
    - Object detection in satellite imagery


-   :material-palette:{ .lg .middle } **Visualization & Cartography**

    ---

    - Power BI, Mapbox
    - Adobe Illustrator, Photoshop, Lightroom


</div>


---

## Connect

[GitHub](https://github.com/AshwaryBanik){ .md-button }
[LinkedIn](https://linkedin.com/in/ashwarybanik/){ .md-button }
