---
title: "Teaching"
aliases: /courses/
description: "Courses on statistics and microeconomics"
---

{{< rawhtml >}}
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">

<style>
/* compact page rhythm */
.teach { max-width: 820px; }
.teach h2 { font-size: 1.35rem; margin: 0 0 0.15rem 0; }
.teach .sub { font-style: italic; color: #444; margin: 0 0 0.6rem 0; }

/* accordion */
.teach .accordion {
  font: 0.95rem/1.4 Lato, "Helvetica Neue", Helvetica, Arial, sans-serif;
  cursor: pointer;
  padding: 6px 10px;
  border: none;
  text-align: left;
  outline: none;
  background: #f4f4f4;
  border-radius: 4px;
  margin: 0.25rem 0;
  font-weight: 600;
}
.teach .accordion:hover,
.teach .accordion.active { background: #ececec; }
.teach .accordion::after {
  content: " [+]";
  font-size: 0.9rem;
  color:#777;
  float: right;
}
.teach .accordion.active::after { content: " [−]"; }

.teach .panel {
  display: none;
  background: #fff;
  border-left: 3px solid #eee;
  padding: 8px 12px;
  margin: 0.25rem 0 0.5rem 0;
  font-size: 0.95rem;
}
.teach .panel.show { display: block !important; }

/* link rows under materials */
.teach .materials a { display: inline-block; margin: 2px 0; }

/* soft divider */
.teach hr { border: 0; border-top: 1px solid #ececec; margin: 1.0rem 0; }
</style>

<div class="teach">

  <!-- Elements of Statistics -->
  <h2>
    <a href="https://ou-public.courseleaf.com/courses/econ/" target="_blank" rel="noopener">
      Elements of Statistics (ECON 2843)
    </a>
  </h2>
  <p class="sub">University of Oklahoma – Fall 2023, Summer 2024, Fall 2024, Summer 2025</p>

  <button class="accordion">Course Description</button>
  <div class="panel">
    <p>This is an introductory statistics course, which surveys basic statistical techniques with particular emphasis on business and economic applications. The learning objective of this course is to improve students' analytical skills in understanding and employing descriptive and inferential statistics.</p>
  </div>

  <button class="accordion">Course Materials</button>
  <div class="panel materials">
    <a href="/Syllabus_ECON_2843.pdf">Syllabus</a><br>
    <a href="/Stat_summer2024.pdf">Course Reflection Survey: Summer 2024</a><br>
    <a href="/Stat_Fall2024.pdf">Course Reflection Survey: Fall 2024</a><br>
    <a href="/Stat_Summer2025.pdf">Course Reflection Survey: Summer 2025</a>
  </div>

  <hr>

  <!-- Principles of Micro -->
  <h2>
    <a href="https://ou-public.courseleaf.com/courses/econ/" target="_blank" rel="noopener">
      Principles of Economics–Micro (ECON 1123)
    </a>
  </h2>
  <p class="sub">University of Oklahoma – Summer 2023</p>

  <button class="accordion">Course Description</button>
  <div class="panel">
    <p>The objective of this course is to introduce students to basic microeconomic concepts and prepare them for future economic classes. By the end of this class, students should be able to understand microeconomic theory and its applications, prepare and understand basic equilibrium graphs, relate economic topics to real world situations, and explain economic principles.</p>
  </div>

  <button class="accordion">Course Materials</button>
  <div class="panel materials">
    <a href="/Syllabus_ECON_1123.pdf">Syllabus</a>
  </div>

</div>

<script>
  // simple accordion toggler
  (function () {
    var acc = document.querySelectorAll('.teach .accordion');
    for (var i = 0; i < acc.length; i++) {
      acc[i].addEventListener('click', function () {
        this.classList.toggle('active');
        var p = this.nextElementSibling;
        if (p) p.classList.toggle('show');
      });
    }
  })();
</script>
{{< /rawhtml >}}


---

## Teaching Assistant and Guest Lecturer

- Intermediate Microeconomic Theory (ECON 3113), University of Oklahoma  
- Labor Problems (ECON 3513), University of Oklahoma
- Labor Economics I (ECON 6433), doctoral-level course, University of Oklahoma 
- The Economics of Discrimination (ECON 4513), University of Oklahoma  
- Introduction to Applied Econometrics (ECON 4233), University of Oklahoma  
- Econometrics II (ECON 5243), doctoral-level course, University of Oklahoma

