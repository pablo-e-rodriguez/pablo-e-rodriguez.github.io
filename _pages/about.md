---
permalink: /
title: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
  - /working_papers/
  - /publications/
---

**Research interests**: Macro-Finance, Labor Economics, Development Economics

**Email**: pablo6@mit.edu

Link to [CV](http://pablo-e-rodriguez.github.io/files/cv.pdf).

<style>
.pub-buttons {
    display: inline-block;
    margin: 5px 0;
}
.pub-buttons a, .pub-button {
    padding: 2px 8px;
    text-decoration: none;
    color: #333;
    cursor: pointer;
    display: inline-block;
    border: none;
    background: none;
    font-family: inherit;
    font-size: inherit;
}
.pub-buttons a:hover, .pub-button:hover {
    text-decoration: underline;
}
.abstract-content {
    display: none;
    margin: 10px 0;
    padding: 10px;
}
.publication-item {
    margin-bottom: 20px;
}
</style>

<h2>Working Papers</h2>

<ul>
    <!--
    <li class="publication-item">
        "Bounded Rationality, Complexity, and Agency Rents"<br>
        <i>2025.</i><br>
        <div class="pub-buttons">
            [ <button class="pub-button" onclick="toggleAbstract('wp1')">Abstract</button> ]
        </div>
        <div id="wp1" class="abstract-content">
            I propose a theory for the simultaneous rise in wages and complexity observed in industries such as finance, pharmaceuticals, or law. I study a moral hazard problem where a principal delegates a complex task to boundedly rational agents of varying skill - some experts, others novices. While higher complexity increases agents' cognitive costs, it also leads to higher agency rents, as principals must compensate them for their effort. This incentivizes agents to push for the highest complexity they can manage within their cognitive constraints. Because of heterogeneous cognitive constraints, aggregate equilibrium complexity can be moderated. However, as the share of experts in the economy rises, aggregate equilibrium complexity goes well beyond the preferred level of the principals, with low net returns and high agency rents. I develop a novel measure of occupation and industry complexity using NLP and ML to bring the model to the data. US evidence between 2002 and 2022 at the occupation and industry levels supports the model's implications.
        </div>
    </li>
    -->
</ul>

<h2>Publications</h2>

<ul>
    <li class="publication-item">
        "Quesnay et Le Despotisme de la Chine: Économie du Politique"<br>
        <i>Revue de Philosophie Économique. 2023.</i><br>
        <div class="pub-buttons">
            [ <button class="pub-button" onclick="toggleAbstract('pub1')">Abstract</button> |
            <a href="http://pablo-e-rodriguez.github.io/files/RPEC_241_0215.pdf" target="_blank">PDF</a> ]
        </div>
        <div id="pub1" class="abstract-content">
            This paper proposes a critical reading of <i>Despotism in China</i>, a rich but less well-commented argumentative text in which Quesnay explicitly presents his political theory. By analyzing <i>Despotism in China</i>, I give support to three main arguments. First, I show to what extent this text embodies Quesnay's thought (and, broadly speaking, the physiocrats' thought). Second, I highlight that economics as an activity, a field, and even a science, lies at the heart of Quesnay's political philosophy. Third, I indicate that, according to Quesnay, the understanding of economics mechanisms corresponds to a close observation of reality, which consists in bringing together the positive law (politics based on economics) and the natural law (what is and what should be).  At the core of these three arguments lies a serious consideration of Quesnay's re-presentation of China. Far from being a mere example to illustrate its arguments, China is conceived as way to see, to reveal, and to grasp a thought (physiocracy), a discipline (economics), and its reach (science and politics).
        </div>
    </li>
</ul>

<script>
function toggleAbstract(abstractId) {
    const abstract = document.getElementById(abstractId);
    if (abstract.style.display === "block") {
        abstract.style.display = "none";
    } else {
        abstract.style.display = "block";
    }
}
</script>
