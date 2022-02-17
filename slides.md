---
theme: seriph
class: text-center
highlighter: shiki
lineNumbers: false
info: |
  ## Slidev Starter Template
  Presentation slides for developers.

  Learn more at [Sli.dev](https://sli.dev)
drawings:
  persist: false
title: COMPILED & INTERPRETED LANGUAGE
---

# COMPILED & INTERPRETED LANGUAGE

Presented by GianBernardo and Fafouad <br>  
a Bisous Calins production

<style>
  .slidev-page-1{
    background-image: url("/public/quinton-coetzee-gpa8Y_Fk7Rg-unsplash.jpg")!important;
}
.slidev-layout p{
  opacity:0.7;
}
</style>

  <!--
  Hello everybody, Jybé and me(depends who is speaking),we are going to talk about compiled and interpreted languages. At the end we will do the pros and cons of both ways. 
  -->

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
<!-- But what is a compiled language ? -->
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
<!-- Let's now discover the fabulous compiled language: java  -->
---

# The compilation in java

<div >

<img
  src="/public/graph/java-langage.png"
  class="absolute h-100 rounded-xl"
  />
<p v-after class="absolute bottom-0 left-45 transform -rotate-10">First step!</p>

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
<!-- 
<ol>
<li>So we write our code in a text file with the extension java. This is the source code<br></li>
<li>To compile our source code, we use the compiler which answers to the sweet name of javaC.<br> 
In this example the command would be javac myCode.java. The result of this action will create a file myCode.class in our folder.
</li>
<li>Inside this file, there is java bytecode. It looks like assembler that can be found in other languages, but it is not assembler.
</li>
</ol>
-->
---

# The compilation in Java

<div>

<img
  class="absolute top-24 h-100 rounded-xl"
  src="/public/graph/javaC-02.png"
/>
<p v-after class="absolute bottom-0 left-30  transform -rotate-10">Compilation time!</p>
<img
  v-click
  class="relative left-54 h-100 rounded-r-xl"
  src="/public/graph/java-process-02.png"
/>
<p v-after class="absolute bottom-0 left-78  transform -rotate-10">on the execution path!</p>

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
<!-- 
<ol>
<li>The bytecode is independent of the machine that compiled it. It doesn't depend on the CPU or OS or anything else on the machine, and whatever the machine, it will be the same code compiled.<br> 
Whether you compile on mac or linux or windows with amd CPU or intel CPU or whatever it will be the same bytecode for the same source code.</li>
<li>In order to execute our code, we need to pass our bytecode as parameters to a command. The command to type Beware the originality is there, this command is java myCode. We don't need the .class.
</li>
<li>With the java command, we invoke the JVM for Java Virtual Machine.<br>
This one allows us to execute bytecode. It is dependent on the CPU, OS. So when we download a version of the JDK we download a version independent of the OS, but we also download a virtual machine which depends on the machine we are working on.
</li>
</ol>
It is thanks to this that the java bytecode will be able to run on any machine, because it is the same on any machine I want to run it.<br>
It is the JVM that will vary, and that will be able to execute any bytecode that we will have generated.
-->
---
