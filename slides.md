---
# try also 'default' to start simple
theme: seriph
# random image from a curated Unsplash collection by Anthony
# like them? see https://unsplash.com/collections/94734566/slidev
# background: "/public/quinton-coetzee-gpa8Y_Fk7Rg-unsplash.jpg"
# apply any windi css classes to the current slide
class: 'text-center'
# https://sli.dev/custom/highlighters.html
highlighter: shiki
# show line numbers in code blocks
lineNumbers: false
# some information about the slides, markdown enabled
info: |
  ## Slidev Starter Template
  Presentation slides for developers.

  Learn more at [Sli.dev](https://sli.dev)
# persist drawings in exports and build
drawings:
  persist: false
---

# COMPILED & INTERPRETED LANGUAGE

Presented by GianBernardo and Fafouad <br>  
a Bisous Calins production

<!--
The last comment block of each slide will be treated as slide notes. It will be visible and editable in Presenter Mode along with the slide. [Read more in the docs](https://sli.dev/guide/syntax.html#notes)
-->
<style>
.slidev-page-1{
    background-image: url("/public/quinton-coetzee-gpa8Y_Fk7Rg-unsplash.jpg")!important;
}
.slidev-layout p{
  
    opacity:0.7;
}
</style>  

---

# The programming language

<br>
<br>

A programming language is a computer language, allowing a human being to write a source code that will be analyzed by a machine.  
The source code is then transformed or evaluated into a machine-readable form, resulting in a program.  
Languages often allow the low-level mechanisms of the machine to be abstracted, so that the source code representing a solution can be written and understood by a human being.

<br>
<br>

<style>
.slidev-page-2{
 background-color: #0e2a35;
}
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg,  #146b8c 10%, #4EC5D4 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
p{
  font-size:1.2rem;
  line-height:1.9rem!important;
}
</style>

---

# The compiled language

<br>
<br>

A compiled language is a programming language where the source code is translated into machine code and the machine code is stored in a separate file. A compiled language tends to give the developer more control over hardware aspects like memory management and CPU usage. However, the compiled code is hardware dependent(not for java).

In a compiled language, the program needs to be rebuilt whenever you make a change.

<br>
<br>

<style>
.slidev-page-3{
 background-color: #0e2a35;
}
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg,  #146b8c 10%, #4EC5D4 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
p{
  font-size:1.2rem;
  line-height:1.9rem!important;
}
</style>

---

# The compilation in java

<div >

<img
  src="/public/graph/java-langage.png"
  class="absolute h-100 rounded-xl"
  />
<p v-after class="absolute bottom-0 left-45 transform -rotate-10">First step!</p>
<!-- https://sli.dev/guide/animations.html#click-animations -->
<img
  v-click
  class="relative left-50 h-100 rounded-r-xl"
  src="/public/graph/javaC.png"
/>
<p v-after class="absolute bottom-0 left-90  transform -rotate-10">Second step!</p>

<img
  v-click
  class="absolute top-24 h-100 rounded-xl"
  src="/public/graph/java-process.png"
/>
<p v-after class="absolute bottom-0 left-150 transform -rotate-10">Third step!</p>
</div>
<style>.slidev-page-4{
 background-color: #0e2a35;
}
.slidev-page-4 p{
  color:#BF97BA
}
</style>  

---

# The compilation language

<div>
<img
  v-click
  class="absolute top-24 h-100 rounded-xl"
  src="/public/graph/javaC-02.png"
/>
<p v-after class="absolute bottom-0 left-30  transform -rotate-10">Compilation time!</p>
<img
  v-click
  class="relative left-54 h-100 rounded-r-xl"
  src="/public/graph/java-process-02.png"
/>
<p v-after class="absolute bottom-0 left-85  transform -rotate-10">Execution way!</p>

<img
  v-click
  class="absolute top-24 h-100 rounded-xl"
  src="/public/graph/javaExectionfinished.png"
/>
<p v-after class="absolute bottom-0 left-140  transform -rotate-10">Execution time!</p>
</div>

<style>
.slidev-page-5{
 background-color: #0e2a35;
 
}
.slidev-page-5 p{
  color:#BF97BA
}
</style>  

---
