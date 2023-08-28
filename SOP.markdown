---
layout: page
title: SOP
icon: fa fa-graduation-cap fa-fw w3-margin-right
permalink: /sop/
txtAlign: justify
---

# Statement of Purpose

  <blockquote class="w3-panel w3-leftbar w3-light-grey">
    <p class="w3-large"><i>"We learned to be happy / We danced 'round the hall / And learning to count was the key to it all."</i></p>
    <p>The Count, Sesame Street</p>
  </blockquote> 

A few moons have passed since I defended my MSc thesis with great success. After much introspection, I have resolved to pursue further studies abroad. As someone who cherishes lucidity and meticulousness, I have crafted this temporary page to share my statement of purpose for research in the coming years. It is my fervent hope that this statement will serve not only as a guide for myself, but also for prospective supervisors, co-supervisors, and anyone interested in my academic aspirations.

---

My foray into the world of applied machine learning for software testing has spanned two years. Under the supervision of Dr. Jalili [[website](https://www.modares.ac.ir/~sjalili), [google scholar](https://scholar.google.com/citations?user=j6gUwMkAAAAJ&hl=en)], an erudite scholar who devotes much of his time to research and students, I have garnered a wealth of knowledge in this field. Yet, I have also realized, with a profound sense of awe, the enormity of the task of creating new knowledge.

Thus, after defending my thesis, I was faced with a daunting decision - to continue my research or seek employment. Ultimately, I found that the passion of solving an unsolved problem or tackling a problem in a novel way resonated with my soul. It was clear, then, that I had to continue my research.

However, I was mindful of the arduous path ahead and felt compelled to choose a topic that truly captivated my interest and motivation. Although the natural progression for me was to pursue a Ph.D. in software testing, which I had devoted much time to studying, I resolved to be patient and reflect before making any commitments.

Since that time, I have devoted my abundant free time to perusing a plethora of enlightening talks and courses, such as the Satisfiability: Theory, Practice, and Beyond Boot Camp, Andrew Ng’s ML course, and reading the first three chapters of the COMPUTERS AND INTRACTABILITY: A Guide to the Theory of NP-Completeness. Additionally, I have reviewed parts of a book I read years ago, the CLRS.

Through these endeavors, I have discovered a wide range of research interests, though I am not an expert in all of them. Nevertheless, I have gained a deeper understanding of my primary areas of interest. Before delving into these areas, let me explain what I mean by my theme of interest.

Having conducted empirical research on a subject heavily reliant on technology for two years, I have come to appreciate the importance of theory. While technological research may generate instant attention and citations, it often fades just as quickly, unlike the Cook-Levin theorem which has had a lasting impact on the field for over half a century. This is not to say that I am averse to empirical studies, but rather that moving forward, I prefer to prioritize theory and only use empirical studies when they can contribute to the development or supplementation of existing theories. **To summarize, my primary principle for the foreseeable future is to prioritize theory and use empirical studies to support it.**

In the following sections, I will describe my current areas of research interest **(in no particular order)**. By clicking on each section, you will find a detailed description of the aspect of the area I am focusing on, why I find it compelling, what I wish this area could cover, my initial objective, and my initial plan. However, these details are subject to change. The final point in each section states my preference regarding MSc or Ph.D. My exceptions are in the areas of Software Engineering and Others, as my views on these areas are evident from my CV and website.


<details>
<summary><b>Complexity Theory</b></summary>
  
<b>My view—</b> Given a computable problem P and computational model M (usually a Turing Machine), what class of complexity P belongs to w.r.t M
<br>
<b>Why I like it—</b> It really defines our boundaries today and the future of computation.
<br>
<b>What I do not like about it is that—</b> it does not provide insight into the distribution of hard instances.
<br>
<b>Initial Objective—</b> Cook–Levin theorem has impacted virtually all aspects of CS over 50 years. If I could do something that remains for five years from now or help others to develop something with such impact, that would be great.
<br>
<b>Initial Plan—</b> Designing & conducting an empirical study to understand the nature of hard instances + then developing a theory that considers the studies’ observations
<br>
<b>Second MSc or PhD—</b> I am open-minded towards both; my preference is a Second MSc.
<br>
</details>

---

<details>
<summary><b>Algorithms Design</b></summary>
  
<b>My view—</b> Given a computable problem P, a common computational model M (usually RAM), and the class of complexity of P w.r.t. M, design an efficient algorithm.
<br>
<b>Why I like it—</b> it has numerous applications and needs creativity.
<br>
<b>What I do not like about it is that—</b> it is efficient and suitable for certain problems not all. For example, for many NP-problems that finding exact solution is required or many others that guarantee is not required other alternatives work better.
<br>
<b>Initial Objective—</b> I have read big & well-known books, and now I would like to be involved in the community and design my own algorithm because it simply feels very good.
<br>
<b>Initial Plan—</b> would be theory, but I have an open mind only after designing and proofing, implementing, and conducting an empirical study. In particular, I think working in one of these areas would be very interesting: Exact or approximation algorithms for computational geometry domain-specific data structures (e.g., data structures for handling large heterogenous datasets).
<br>
<b>Second MSc or PhD—</b> I am open-minded towards both; my preference is a Second MSc.
<br>
</details>

---

<details>
<summary><b>SMT Solvers</b></summary>
  
<b>My view—</b> Typically, given a computable problem formulated as a formula P that belongs to NPC, find satisfiable assignments for P or otherwise return UNSAT.
<br>
<b>Why I like it—</b> they are extremely practical, and many tools (such as KLEE and many others) are developed on top of them + nicely make a link between theory and practice.
<br>
<b>What I do not like about it is that—</b> currently, they only provide exact solutions and not approximate solutions.
<br>
<b>Initial Objective—</b> I would like to explore SMT4ML, ML4SMT, and ML + Reasoning.
<br>
<b>Initial Plan—</b> I am open-minded towards both
<br>
<b>Second MSc or PhD—</b> I am open-minded towards both.
<br>
</details>

---

<details>
<summary><b>ML</b></summary>
  
<b>My view—</b> Given a computational model M, description or instances of interest D of a computable problem of interest P, design algorithm that works well on instances D w.r.t. a measure of interest
<br>
<b>Why I like it—</b> it is practical and empirical and jointly need creativity
<br>
<b>What I do not like about it is that—</b> no guarantee, usually is only about representation and does not anything to do w.r.t. reasoning; e.g., it may solve some integrals but cannot discover the concept of integral by itself
<br>
<b>Initial Objective—</b> Have read some books, and got some courses, but my major was not AI; now I want to go delve depth and depth into its mathematics, and so design a new algorithm
<br>
<b>Initial Plan—</b> Have an open mind, but I would like to design a new algorithm would be among the novelty, not just applying, combing, or comparing existing methods. In particular, I am interested in developing new techniques and algorithms for semi-supervised, supervised, and NLP, all with offline strategies.
<br>
<b>Second MSc or PhD—</b> I am open-minded towards both; my preference is a Second MSc.
<br>
</details>

---

<details>
<summary><b>Software Engineering</b></summary>
  
<b>Initial Objective—</b> I want to explore applications of SMT solvers, ML, and Approximate counting/sampling in a given software engineering problem. There is no obligation, but as a matter of preference or familiarity, it is easier for me to work on test input generation, test case prioritization, test suite quality assessment, and test case execution. However, I want to emphasize again that there is no obligation, and I would be delighted to explore other problems or other areas, such as verification.
<br>
<b>Second MSc or PhD—</b> PhD
<br>
</details>

---

<details>
<summary><b>Others(Sports, Music, etc.)</b></summary> 
<b>Initial Objective—</b> As should be evident from my websites and the projects I’ve been involved in, I would like to explore and expand my knowledge by applying it to various domains such as Sports, Tourism, Biology, etc. In particular, I want to explore applications of SMT solvers, ML, and Approximate counting/sampling in a given domain and problem.
<br>
<b>Second MSc or PhD—</b> I am open-minded towards both.
<br>
</details>

---


<details>
<summary><b>WHY DO I THINK I AM A COMPETENT CANDIDATE?</b></summary>
  
<b>-</b> With my previous research experience, I have gained valuable skills in reading papers, learning about research methodologies, and writing papers and presentations. I believe these skills make me a strong candidate for any position I apply for.
<br><br>
<b>-</b> Looking towards the future, I see myself as a researcher (not necessarily in universities), and I am open to pursuing a second master's or Ph.D. to expand my knowledge and experience. I am flexible when it comes to the type of position, except for software engineering.
<br><br>
<b>-</b> I have a strong network of supportive and talented people who are always there for me. This is especially important as I plan to apply for Fall 2024. I can focus on studying literature and potentially the required background to start research directly in the Fall of 2024. Some of these individuals are experts in their respective fields and are always willing to lend a hand when I struggle to understand something or when collaboration is needed.
<br><br>
<b>-</b> I prefer to let my CV and references speak to my skills and hardworking nature, as I believe actions speak louder than words.
<br><br>
</details>

---
