---
layout: post
title: Some notes
---

## Section
text text 
text text 
text text 
text text 
text text 
text text 
text text 

- {% include marginfigure.html id="bn" url="assets/img/3node-bayesnets.png" description="Bayesian networks over three variables, encoding different types of dependencies: cascade (a,b), common parent (c), and v-structure (d)." %}*Common parent.* If $$G$$ is of the form $$A \leftarrow B \rightarrow C$$, and $$B$$ is observed, then $$A \perp C \mid B$$. However, if $$B$$ is unobserved, then $$A \not\perp C$$. Intuitively this stems from the fact that $$B$$ contains all the information that determines the outcomes of $$A$$ and $$C$$; once it is observed, there is nothing else that affects these variables' outcomes.

Or in the main collumn

{% include maincolumn_img.html src='assets/img/3node-bayesnets.png' caption='Bayesian networks over three variables' %}
<br/>

|[Index](../../) | [Previous](../../preliminaries/applications) | [Next](../undirected)|
