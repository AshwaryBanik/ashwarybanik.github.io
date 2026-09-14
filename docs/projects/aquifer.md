# Aquifer Geometry Analysis Using RockWorks


<div class="project-slider">

  <div class="project-slide">
    <img src="../../assets/images/rockworks-1.jpg" alt="Project image 1">
  </div>

  <div class="project-slide">
    <img src="../../assets/images/rockworks-2.jpg" alt="Project image 2">
  </div>
</div>

<div class="project-dots">
  <span class="project-dot" onclick="currentProjectSlide(1)"></span>
  <span class="project-dot" onclick="currentProjectSlide(2)"></span>
</div>

<style>
.project-slider {
  position: relative;
  width: 100%;
  max-width: 850px;
  margin: 20px auto 8px;
  overflow: hidden;
  border-radius: 10px;
}

.project-slide {
  display: none;
  width: 100%;
}

.project-slide img {
  display: block;
  width: 100%;
  height: auto;
  border-radius: 10px;
}

.project-dots {
  text-align: center;
  margin-top: 8px;
  margin-bottom: 20px;
}

.project-dot {
  display: inline-block;
  width: 10px;
  height: 10px;
  margin: 0 4px;
  background: #bbb;
  border-radius: 50%;
  cursor: pointer;
}

.project-dot.active {
  background: #555;
}
</style>

<script>
let projectSlideIndex = 0;

function showProjectSlide(n) {
  const slides = document.getElementsByClassName("project-slide");
  const dots = document.getElementsByClassName("project-dot");

  for (let i = 0; i < slides.length; i++) {
    slides[i].style.display = "none";
  }

  for (let i = 0; i < dots.length; i++) {
    dots[i].classList.remove("active");
  }

  slides[n].style.display = "block";
  dots[n].classList.add("active");
}

function nextProjectSlide() {
  const slides = document.getElementsByClassName("project-slide");
  projectSlideIndex++;
  if (projectSlideIndex >= slides.length) {
    projectSlideIndex = 0;
  }
  showProjectSlide(projectSlideIndex);
}

function currentProjectSlide(n) {
  projectSlideIndex = n - 1;
  showProjectSlide(projectSlideIndex);
}

showProjectSlide(projectSlideIndex);
setInterval(nextProjectSlide, 2000);
</script>




## Overview

Analyzed borehole lithology data using **RockWorks** to define aquifer geometry and identify probable aquifer units. The work focused on organizing borehole records, generating lithological striplogs and cross sections, and interpreting the subsurface distribution of aquifers.


---

## Methods & Tools

### Required Data

- Primary borehole data from the GoB-UNICEF Monitoring Well network
- Secondary borehole data from DPHE, and BWDB
- Borehole lithological information including depth and sediment type

### Processing Steps

1. **Borehole Data Preparation**  
    Collected and organized primary and secondary borehole data for lithological analysis.

2. **RockWorks Database Preparation**  
    Imported and organized borehole lithology data in **RockWorks**.

3. **Lithological Striplogs**  
    Generated borehole striplogs to visualize vertical changes in subsurface lithology.

4. **Lithological Cross Sections**  
    Created regional cross sections from borehole data to visualize lateral and vertical variations in subsurface geology.

5. **Aquifer Identification**  
    Interpreted the lithological cross sections to identify probable aquifer units and their spatial distribution.

6. **Aquifer Thickness Analysis**  
    Used the interpreted aquifer boundaries to assess aquifer thickness and support isopach mapping.

### Tools Used

| Tool | Purpose |
|---|---|
| **RockWorks** | Borehole-data management, striplog generation, lithological cross sections, aquifer interpretation |

---
