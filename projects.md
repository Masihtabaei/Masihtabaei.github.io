---
title: Projects
permalink: /projects/
layout: page
excerpt: tbd

comments: false
---

<div class="flex-container">
  <img src="/assets/img/cheap_16_logo.png">
  <div>
    <strong>Project: </strong>cheap-16<br>
    <strong>Status: </strong>Done (Grade: 1.0 | Very Good)<br>
    <strong>Role: </strong>Co-Developer<br>
    <strong>Tech Stack: </strong>Git, GitHub, GitLab, Rust, etc.<br>
    An educational 16-bit custom instruction set architecture with emulator, assembler, linker, and integrated development environment, all implemented in Rust.<br>
    <a href="https://github.com/Masihtabaei/cheap-16" target="_blank">Repository</a>
  </div>
</div>

<div class="flex-container">
  <img src="/assets/img/ladron_logo.png">
  <div>
    <strong>Project: </strong>Ladron<br>
    <strong>Status: </strong>Done (Grade: 1.3 | Very Good)<br>
    <strong>Role: </strong>Co-Developer<br>
    <strong>Tech Stack: </strong>Git, GitHub, Unity Engine, etc.<br>
    A narrative survival game focused on riddle-solving, developed within our Fundamentals of Game Design course, developed with Unity Engine.<br>
    <a href="https://github.com/Masihtabaei/ladron" target="_blank">Repository</a>
  </div>
</div>

<div class="flex-container">
  <img src="/assets/img/coming_soon_placeholder.svg">
  <div>
    <strong>Project: </strong>hlslx<br>
    <strong>Status: </strong>Ongoing<br>
    <strong>Role: </strong>Developer<br>
    <strong>Tech Stack: </strong>Git, GitHub, C#, etc.<br>
    A versatile Visual Studio extension that enhances modern HLSL shader programming with syntax highlighting, code completion, and more.<br>
    <a href="" >Coming Soon ... (approx. Q1 2026)</a>
  </div>
</div>


<style>
.flex-container {
  display: flex;
  flex-wrap: nowrap;
  margin: 2%;

}

.flex-container > img {
  min-width: 25%;
  max-width: 40%;
  margin: 10px;


}
.flex-container > div {
  width: 75%;
  margin: 10px;
    text-align: left;
}

@media (max-width: 800px) {
  .flex-container {
    flex-direction: column;
    justify-content: center;
  }
  .flex-container > img {
      min-width: 100%;
  max-width: 100%;
    width: 100%;
  }
  .flex-container > div {
    width: 100%;
    text-align: center;
  }
}
</style>