---
layout: page
title: NeurIPS Tutorial on Machine Learning for Theorem Proving
---
<div class="venue" style="font-size: 27px; display: block; font-family: 'Open Sans', 'Helvetica Neue', Helvetica, Arial, sans-serif; font-weight: 300; color: #404040; text-align: center;">
  New Orleans, December 11, 2023, 1:45–4:15 PM CT (tentative)
</div>



<div class="sharethis-inline-share-buttons"></div>
<meta name="thumbnail" content="./img/neurips-logo-new.jpg" />


# Overview

Machine learning, especially large language models (LLMs), has shown promise
in proving formal theorems using proof assistants such as [Coq](https://coq.inria.fr/), [Isabelle](https://isabelle.in.tum.de/), and [Lean](https://leanprover.github.io/). Theorem proving is an important challenge for machine learning: Formal proofs
are computer programs whose correctness can be verified. Therefore, theorem
proving is a form of code generation with rigorous evaluation and no room for
the model to hallucinate, opening up a new avenue for addressing LLMs’ flaws
in factuality. 

Despite its potential, learning-based theorem proving has significant
entry barriers, primarily due to the steep learning curve for proof assistants. This
tutorial aims to bridge this gap and make theorem proving accessible to researchers
with a general machine learning background. To that end, our presentation will contextualize
theorem proving from a machine learning perspective and demonstrate
how to develop LLMs for theorem proving, using newly available open-source
tools that provides interfaces to proof assistants without requiring in-depth knowledge
of their internals. Furthermore, we will cover advanced topics and open
problems in learning-based theorem proving, including its synergies with natural
language processing and software verification. 

Throughout the presentation, we
will highlight several conceptual themes recurring in theorem proving that are also
critical for machine learning, such as mathematical reasoning, code generation,
and hallucination prevention. The panel will complement the presentation through
a broader discussion of related topics such as trustworthy machine learning, LLMs
for code, reasoning, and program synthesis.

<hr>


# Presenters
<div class="container" style="margin-top: 25px;margin-bottom: 40px;">
  <div class="row">
    {% for p in site.data.presenters %}
    {% if forloop.index<=4 %}
    {% capture id %}{{ p[0] }}{% endcapture %}
    {% include profile.html p=p %}
    {% endif %}
    {% endfor %}
  </div>
  <div class="row">
    {% for p in site.data.presenters %}
    {% capture id %}{{ p[0] }}{% endcapture %}
    {% if forloop.index>4 and forloop.index<=7%}
    {% include profile.html p=p %}
    {% endif %}
    {% endfor %}
  </div>
</div>
<hr>

# Panelists
<div class="container" style="margin-top: 20px;margin-bottom: 0px;">
  <div class="row">
    {% for p in site.data.panelists %}
    {% if forloop.index<=5 %}
    {% capture id %}{{ p[0] }}{% endcapture %}
    {% include profile.html p=p %}
    {% endif %}
    {% endfor %}
  </div>
  <div class="row">
    {% for p in site.data.panelists %}
    {% capture id %}{{ p[0] }}{% endcapture %}
    {% if forloop.index>5 and forloop.index<=10%}
    {% include profile.html p=p %}
    {% endif %}
    {% endfor %}
  </div>
  <div class="row">
    {% for p in site.data.panelists %}
    {% capture id %}{{ p[0] }}{% endcapture %}
    {% if forloop.index>10%}
    {% include profile.html p=p %}
    {% endif %}
    {% endfor %}
  </div>
</div>
<hr>


# Reading Materials

TBA

<hr>

Contact: <machine.learning.4.theorem.proving@gmail.com>.
