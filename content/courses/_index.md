---
title: "Teaching"
description: "Courses taught by Mahla Shourian"
---

<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">

<style>
button.accordion {
  font:14px/1.5 Lato, "Helvetica Neue", Helvetica, Arial, sans-serif;
  cursor: pointer;
  padding: 6px;
  border: none;
  text-align: left;
  outline: none;
  font-size: 100%;
  transition: 0.3s;
  background-color: #f8f8f8;
  font-weight: bold;
}
button.accordion.active, button.accordion:hover {
  background-color: #eaeaea;
}
button.accordion:after {
  content: " [+]";
  font-size: 90%;
  color:#777;
  float: right;
}
button.accordion.active:after {
  content: " [−]";
}
div.panel {
  padding: 0 15px;
  margin-top: 5px;
  display: none;
  background-color: white;
  font-size: 95%;
}
div.panel.show {
  display: block !important;
}
</style>

## Elements of Statistics (ECON 2843)  
_University of Oklahoma – Fall 2023, Summer 2024, Fall 2024, Summer 2025_

<button class="accordion">Course Description</button>
<div class="panel">
<p>This is an introductory statistics course, which surveys basic statistical techniques with particular emphasis on business and economic applications. The learning objective of this course is to improve students' analytical skills in understanding and employing the descriptive and inferential statistics.</p>
</div>

<button class="accordion">Course Materials</button>
<div class="panel">
<p>
<a href="/Syllabus_ECON_2843.pdf">syllabus</a><br>
<a href="/Stat_summer2024.pdf">Course Reflection Survey: Summer 2024</a><br>
<a href="/Stat_Fall2024.pdf">Course Reflection Survey: Fall 2024</a><br>
<a href="/Stat_summer2025.pdf">Course Reflection Survey: Summer 2025</a>
</p>
</div>

---

## Principles of Economics–Micro (ECON 1123)  
_University of Oklahoma – Summer 2023_

<button class="accordion">Course Description</button>
<div class="panel">
<p>The objective of this course is to introduce students to basic microeconomic concepts and prepare them for future economic classes. By the end of this class, students should be able to understand microeconomic theory and its applications, prepare and understand basic equilibrium graphs, relate economic topics to real world situations, and explain economic principles.</p>
</div>

<button class="accordion">Course Materials</button>
<div class="panel">
<p>
<a href="/Syllabus_ECON_1123.pdf">syllabus</a>
</p>
</div>

<script>
var acc = document.getElementsByClassName("accordion");
var i;
for (i = 0; i < acc.length; i++) {
  acc[i].onclick = function(){
    this.classList.toggle("active");
    this.nextElementSibling.classList.toggle("show");
  }
}
</script>
