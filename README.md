# GameAwards

## Table of contents

1. <a href="https://orelrafa.github.io/GameAwards/#introduction">Introduction</a>
2. <a href="https://orelrafa.github.io/GameAwards/#imports">Imports</a>
3. <a href="https://orelrafa.github.io/GameAwards/#data_acquisition">Data acquisition</a><br>
    3.1 <a href="https://orelrafa.github.io/GameAwards/#scraping_process">Scraping Process</a><br>
    3.2 <a href="https://orelrafa.github.io/GameAwards/">Scraping challenges</a><br>
      3.2.1 <a href="https://orelrafa.github.io/GameAwards/">Challenge 1 - Game Pages Collection</a><br>
      3.2.2 <a href="https://orelrafa.github.io/GameAwards/">Challenge 2 - Inconsistent Page structure </a><br>
      3.2.3 <a href="https://orelrafa.github.io/GameAwards/">Challenge 3 - Age Check</a><br>
      3.2.4 <a href="https://orelrafa.github.io/GameAwards/">Challenge 4 - Login wall</a><br>
4. <a href="https://orelrafa.github.io/GameAwards/">Scrapping</a><br>
    4.1 <a href="https://orelrafa.github.io/GameAwards/">Gathering the pages</a><br>
      4.1.1 <a href="https://orelrafa.github.io/GameAwards/">First crawl</a><br>
      4.1.2 <a href="https://orelrafa.github.io/GameAwards/">Second crawl</a><br>
      4.1.3 <a href="https://orelrafa.github.io/GameAwards/">Concating the pages</a><br>
    4.2 <a href="https://orelrafa.github.io/GameAwards/">Scrapping each page data</a><br>
    4.3 <a href="https://orelrafa.github.io/GameAwards/">Reviewing the data</a><br>
5. <a href="https://orelrafa.github.io/GameAwards/">Data cleaning</a><br>
    5.1 <a href="https://orelrafa.github.io/GameAwards/">Corrupted data cleaning</a><br>
    5.2 <a href="https://orelrafa.github.io/GameAwards/">Replace missing data - original title</a><br>
    5.3 <a href="https://orelrafa.github.io/GameAwards/">None values - discussion and strategy</a><br>
6. <a href="https://orelrafa.github.io/GameAwards/">Pre outliers cleaning EDA</a><br>
    6.1 <a href="https://orelrafa.github.io/GameAwards/">Genre distribution</a><br>
    6.2 <a href="https://orelrafa.github.io/GameAwards/">Mean rating by genre</a><br>
    6.3 <a href="https://orelrafa.github.io/GameAwards/">Language distribution</a><br>
    6.4 <a href="https://orelrafa.github.io/GameAwards/">Reviews to award</a><br>
7. <a href="https://orelrafa.github.io/GameAwards/">Dealing with outliers</a><br>
    7.1 <a href="https://orelrafa.github.io/GameAwards/">Outliers detection</a><br>
    7.2 <a href="https://orelrafa.github.io/GameAwards/">Outliers cleaning</a><br>
    7.3 <a href="https://orelrafa.github.io/GameAwards/">Outliers cleaning results</a><br>
8. <a href="https://orelrafa.github.io/GameAwards/">EDA after outliers cleaning</a><br>
    8.1 <a href="https://orelrafa.github.io/GameAwards/">Thoughts of the results</a><br>
9. <a href="https://orelrafa.github.io/GameAwards/">Machine learning preperation</a><br>
10. <a href="https://orelrafa.github.io/GameAwards/">Machine learning - the model we picked</a><br>
    10.1 <a href="https://orelrafa.github.io/GameAwards/">Something</a><br>
    10.2 <a href="https://orelrafa.github.io/GameAwards/">Something</a><br>
    10.3 <a href="https://orelrafa.github.io/GameAwards/">Something</a><br>
11. <a href="https://orelrafa.github.io/GameAwards/">Machine learning - the second model we picked</a><br>
    11.1 <a href="https://orelrafa.github.io/GameAwards/">Overfitting?</a><br>
    11.2 <a href="https://orelrafa.github.io/GameAwards/">Model improvment</a><br>
    11.3 <a href="https://orelrafa.github.io/GameAwards/">Adjusting features</a><br>
12. <a href="https://orelrafa.github.io/GameAwards/">>Conclusion and credits</a><br>  

### Introduction

<p>Video games have seen a monumental rise in popularity in recent years. What once was an enjoyable past time for kids, exclusivly in malls and arcades, now has become a media giant that netted almost 224.44 billion USD last year, leaving Hollywood in the dirt, who sat at around 95.45 billion USD in 2022. </p>
<p>There's no way of denying it, video games have taken over the world. As a result, the competition in the field is fierce, and many developers are fighting their way to the spotlight. Every year there are countless of ceremonies around the globe that feature games for their greatest achievments: Art Direction, Audio Design, Acting, Graphics, Gameplay, and too many more categories to name. </p>
<p>What if we could predict that? What if we could tell what game would win at being in the spotlight? </p>
That's the goal we've set for our research: Can we predict award winning games?
