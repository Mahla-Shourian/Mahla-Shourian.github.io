---
title: "Teaching"
aliases: /courses/
description: "Courses taught by Mahla Shourian"
---

{{< rawhtml >}}
<style>
  .teach { max-width: 820px; }
  .teach h2 { font-size: 1.22rem; margin: 0 0 .25rem 0; font-weight: 700; }
  .teach .sub { margin: 0 0 .35rem 0; font-style: italic; color:#444; }
  .teach .line { margin: 0 0 .4rem 0; }
  .teach a { text-decoration: none; border-bottom: 1px solid rgba(0,0,0,.2); }
  .teach a:hover { border-bottom-color: rgba(0,0,0,.5); }
  .teach .toggle {
    display:inline-block; cursor:pointer; user-select:none;
    padding: 4px 8px; margin: .2rem 0 .25rem 0; border-radius: 4px;
    background:#f4f4f4; font-weight:600; font-size:.95rem;
  }
  .teach .toggle:hover { background:#ececec; }
  .teach .toggle .sig { color:#777; }
  .teach .panel { display:none; margin:.25rem 0 .6rem 0; padding-left:.3rem; }
  .teach .panel a { display:block; margin:2px 0; }
  .teach hr { border:0; border-top:1px solid #ececec; margin: .9rem 0; }
</style>

<div class="teach">

  <!-- Elements of Statistics -->
  <h2><a href="https://ou-public.courseleaf.com/courses/econ/" target="_blank" rel="noopener">Elements of Statistics (ECON 2843)</a></h2>
  <p class="sub">University of Oklahoma – Fall 2023, Summer 2024, Fall 2024, Summer 2025</p>
  <p class="line"><a href="/Syllabus_ECON_2843.pdf">View Syllabus</a></p>

  <span class="toggle" data-target="#survey-2843">
    Course Reflection Survey <span class="sig">[+]</span>
  </span>
  <div id="survey-2843" class="panel">
    <a href="/Stat_summer2024.pdf">Summer 2024</a>
    <a href="/Stat_Fall2024.pdf">Fall 2024</a>
    <a href="/Stat_summer2025.pdf">Summer 2025</a>
  </div>

  <hr>

  <!-- Principles of Micro -->
  <h2><a href="https://ou-public.courseleaf.com/courses/econ/" target="_blank" rel="noopener">Principles of Economics–Micro (ECON 1123)</a></h2>
  <p class="sub">University of Oklahoma – Summer 2023</p>
  <p class="line"><a href="/Syllabus_ECON_1123.pdf">View Syllabus</a></p>

</div>

<script>
  (function () {
    var toggles = document.querySelectorAll('.teach .toggle');
    toggles.forEach(function(t){
      t.addEventListener('click', function(){
        var id = t.getAttribute('data-target');
        var panel = document.querySelector(id);
        var sig = t.querySelector('.sig');
        var open = panel.style.display === 'block';
        panel.style.display = open ? 'none' : 'block';
        if (sig) sig.textContent = open ? '[+]' : '[−]';
      });
    });
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
