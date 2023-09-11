---
layout: post
title:  "Competition launched!"
date:   2023-09-11 00:00:00 +0000
categories: announcements
comments: true
---
Hi everyone,

We're excited to announce that the unlearning challenge is [now open for submissions on Kaggle](https://www.kaggle.com/competitions/neurips-2023-machine-unlearning/)! We will accept submissions until November 27, 2023.

We recommend using [this starting notebook](https://www.kaggle.com/code/eleni30fillou/run-unlearn-finetune) for making a submission, and simply replacing the contents of the `unlearning` function. Please see the Kaggle page for more information on how to make a submission.

We are also excited to release our [write-up with a formal definition of unlearning](https://unlearning-challenge.github.io/assets/data/Machine_Unlearning_Metric.pdf), linking it to Differential Privacy, and a description of the metric and evaluation protocol that we use in the challenge.

We look forward to receiving your submissions!

{% if page.comments %}
<div id="disqus_thread"></div>
<script>
    /**
    *  RECOMMENDED CONFIGURATION VARIABLES: EDIT AND UNCOMMENT THE SECTION BELOW TO INSERT DYNAMIC VALUES FROM YOUR PLATFORM OR CMS.
    *  LEARN WHY DEFINING THESE VARIABLES IS IMPORTANT: https://disqus.com/admin/universalcode/#configuration-variables    */
    /*
    var disqus_config = function () {
    this.page.url = PAGE_URL;  // Replace PAGE_URL with your page's canonical URL variable
    this.page.identifier = PAGE_IDENTIFIER; // Replace PAGE_IDENTIFIER with your page's unique identifier variable
    };
    */
    (function() { // DON'T EDIT BELOW THIS LINE
    var d = document, s = d.createElement('script');
    s.src = 'https://unlearning-challenge.disqus.com/embed.js';
    s.setAttribute('data-timestamp', +new Date());
    (d.head || d.body).appendChild(s);
    })();
</script>
<noscript>Please enable JavaScript to view the <a href="https://disqus.com/?ref_noscript">comments powered by Disqus.</a></noscript>
{% endif %}
