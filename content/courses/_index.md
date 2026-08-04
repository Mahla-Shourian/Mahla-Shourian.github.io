---
title: "Teaching"
aliases: /courses/
description: "Courses on statistics and microeconomics"
---

{{< rawhtml >}}
<style>
.teach { max-width: 100%; }

/* two-column top */
.teach-top {
  display: flex;
  gap: 32px;
  align-items: stretch;
  flex-wrap: wrap;
  margin: 0.4rem 0 3rem 0;
}
.teach-top .left  {
  flex: 1 1 500px; min-width: 320px;
  background: #f5f5f4; border-radius: 10px; padding: 20px 24px;
}
.teach-top .right { flex: 0 0 340px; display: flex; flex-direction: column; }

/* section rhythm */
.teach section { margin: 3rem 0; }
.teach .sec {
  font-family: Georgia, "Palatino Linotype", Palatino, serif;
  font-size: 1.5rem;
  font-weight: 600;
  margin: 0 0 0.25rem 0;
}
.teach .rule { border: 0; border-top: 2px solid #841617; width: 64px; margin: 4px 0 1.3rem 0; }

/* courses-taught table */
.ctable { width: 100%; border-collapse: collapse; font-size: 0.96rem; }
.ctable th {
  text-align: left;
  padding: 9px 12px;
  border-bottom: 2px solid #841617;
  font-weight: 600;
  white-space: nowrap;
}
.ctable td { padding: 9px 12px; border-bottom: 1px solid #ededed; }
.ctable tr:last-child td { border-bottom: 0; }
.ctable td:last-child, .ctable th:last-child { text-align: center; }

/* portfolio button + upcoming box */
.portfolio-btn {
  display: block; text-align: center;
  background: #841617; color: #fff !important;
  padding: 15px 18px; border-radius: 8px;
  font-weight: 600; font-size: 1.05rem; text-decoration: none;
}
.upcoming {
  border: 2px solid #841617; background: #f5f5f4;
  border-radius: 10px; padding: 16px 20px;
  margin: 0 0 18px 0; flex: 1 1 auto;
}
.upcoming ul { margin: 8px 0 0 0; padding-left: 1.15rem; line-height: 1.75; }

/* course blocks */
.teach .course { margin: 0 0 1.8rem 0; }
.teach .course h3 { margin: 0 0 0.4rem 0; font-size: 1.15rem; }
.teach .accordion {
  font: 600 0.92rem/1.4 Lato, "Helvetica Neue", Arial, sans-serif;
  cursor: pointer; padding: 6px 10px; border: none; text-align: left;
  background: #f4f4f4; border-radius: 4px; margin: 0.15rem 0;
}
.teach .accordion:hover, .teach .accordion.active { background: #ececec; }
.teach .accordion::after { content: " [+]"; font-size: 0.9rem; color:#777; float: right; }
.teach .accordion.active::after { content: " [\2212]"; }
.teach .panel {
  display: none; background: #fff; border-left: 3px solid #eee;
  padding: 8px 12px; margin: 0.25rem 0 0.6rem 0; font-size: 0.95rem;
}
.teach .panel.show { display: block !important; }
.teach .materials { margin-top: 0.55rem; font-size: 0.95rem; color: #555; }
.teach .materials a { color: #841617; }

/* TA list */
.teach .talist { margin: 0.4rem 0 0.6rem 0; line-height: 1.9; }
.teach .note { color: #777; font-size: 0.9rem; font-style: italic; }

/* student comment cards */
.quote-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(230px, 1fr)); gap: 18px; margin-top: 0.4rem; }
.qcard {
  border: 1px solid #eee; border-top: 3px solid #841617; border-radius: 8px;
  padding: 18px 20px; background: #fafafa; font-style: italic; color: #333; line-height: 1.55;
}
</style>

<div class="teach">

  <div class="teach-top">
    <div class="left">
      <h2 class="sec">Courses Taught</h2>
      <div class="rule"></div>
      <table class="ctable">
        <thead>
          <tr><th>Year</th><th>Semester</th><th>Course</th><th>Enrollment</th></tr>
        </thead>
        <tbody>
          <tr><td>2025</td><td>Summer</td><td>ECON 2843: Elements of Statistics</td><td>16</td></tr>
          <tr><td>2024</td><td>Fall</td><td>ECON 2843: Elements of Statistics</td><td>27</td></tr>
          <tr><td>2024</td><td>Summer</td><td>ECON 2843: Elements of Statistics</td><td>13</td></tr>
          <tr><td>2023</td><td>Fall</td><td>ECON 2843: Elements of Statistics</td><td>8</td></tr>
          <tr><td>2023</td><td>Summer</td><td>ECON 1123: Principles of Microeconomics</td><td>24</td></tr>
        </tbody>
      </table>
    </div>

    <div class="right">
      <div class="upcoming">
        <strong>Upcoming Courses &mdash; In Person</strong>
        <ul>
          <li>Elements of Statistics (ECON 2843) &mdash; Fall 2026</li>
          <li>Principles of Economics&ndash;Micro (ECON 1123) &mdash; Spring 2027</li>
        </ul>
      </div>
      <a class="portfolio-btn" href="/Shourian_Teaching_Portfolio.pdf">&#128196; Teaching Portfolio</a>
    </div>
  </div>

  <section>
    <h2 class="sec">Course Materials</h2>
    <div class="rule"></div>

    <div class="course">
      <h3><a href="https://ou-public.courseleaf.com/courses/econ/" target="_blank" rel="noopener">Elements of Statistics (ECON 2843)</a></h3>
      <button class="accordion">Course Description</button>
      <div class="panel">
        <p>An introductory statistics course surveying basic statistical techniques with an emphasis on business and economic applications, aimed at improving students&rsquo; analytical skills in descriptive and inferential statistics.</p>
      </div>
      <div class="materials">
        <a href="/Syllabus_ECON_2843.pdf">Syllabus</a> &nbsp;&middot;&nbsp;
        Reflection surveys:
        <a href="/Stat_summer2024.pdf">Summer 2024</a>,
        <a href="/Stat_Fall2024.pdf">Fall 2024</a>,
        <a href="/Stat_Summer2025.pdf">Summer 2025</a>
      </div>
    </div>

    <div class="course">
      <h3><a href="https://ou-public.courseleaf.com/courses/econ/" target="_blank" rel="noopener">Principles of Economics&ndash;Micro (ECON 1123)</a></h3>
      <button class="accordion">Course Description</button>
      <div class="panel">
        <p>An introduction to basic microeconomic concepts, preparing students to understand microeconomic theory and its applications, work with equilibrium graphs, and relate economic principles to real-world situations.</p>
      </div>
      <div class="materials">
        <a href="/Syllabus_ECON_1123.pdf">Syllabus</a>
      </div>
    </div>
  </section>

  <section>
    <h2 class="sec">Teaching Assistant &amp; Guest Lecturer</h2>
    <div class="rule"></div>
    <ul class="talist">
      <li>Intermediate Microeconomic Theory (ECON 3113)</li>
      <li>Labor Problems (ECON 3513)</li>
      <li>Labor Economics I (ECON 6433) &mdash; doctoral</li>
      <li>The Economics of Discrimination (ECON 4513)</li>
      <li>Introduction to Applied Econometrics (ECON 4233)</li>
      <li>Econometrics II (ECON 5243) &mdash; doctoral</li>
    </ul>
    <div class="note">All at the University of Oklahoma.</div>
  </section>

  <section>
    <h2 class="sec">What Students Say</h2>
    <div class="rule"></div>
    <div class="quote-grid">
      <div class="qcard">&ldquo;This course was honestly one of the best ones I have taken at OU.&rdquo;</div>
      <div class="qcard">&ldquo;The Case Studies made a great impact&nbsp;&mdash;&nbsp;they allowed us to see and practice the material in real time and in a realistic way (using Excel).&rdquo;</div>
      <div class="qcard">&ldquo;Professor was easily accessible and really made an effort to make sure we understood lessons.&rdquo;</div>
    </div>
  </section>

</div>

<script>
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
