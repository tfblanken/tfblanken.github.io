---
layout: post
title: ITQ
description: insomnia type questionnaire
img: /img/amsterdam_lights1.jpg
---

We developed the <a href="https://www.dropbox.com/s/1t7iqpb5klkddr8/EN_ITQ-200_questions_and_scoring.pdf?dl=0" target="blank">Insomnia Type Questionnaire</a> to assess someone's insomnia subtype. The subtypes are explained in <a href="https://www.researchgate.net/publication/330256475_Insomnia_disorder_subtypes_derived_from_life_history_and_traits_of_affect_and_personality" target="blank">our paper</a> and the questionnaire can be found <a href="https://www.dropbox.com/s/1t7iqpb5klkddr8/EN_ITQ-200_questions_and_scoring.pdf?dl=0" target="blank">here</a>. After using the ITQ, the subtypes can be computed automatically through a <a href="https://tfblanken.shinyapps.io/itqapp/" target="blank">shiny web application</a>.<sup>[1](#myfootnote1)</sup> 

We are currently working on a short form and website through which the questionnaire can be queried and scored automatically. Please contact me if you have any questions regarding the ITQ and the development of the short form. 

<div class="img_row">
	<img class="col one" src="{{ site.baseurl }}/img/Subtypes.png" alt="" title="Subtype plot"/>
	<img class="col one" src="{{ site.baseurl }}/img/ITQ.png" alt="" title="Questionnaire"/>
	<img class="col one" src="{{ site.baseurl }}/img/Subtypes_shiny.png" alt="" title="Shiny web application"/>
</div>
<div class="col three caption">
	Five insomnia subtypes (left), Insomnia Type Questionnaire (middle), and the shiny web application (right). 
</div>


<br/>

<sub><a name="myfootnote1">1</a> Important note for own use: the app automatically recodes contra-indicative items. Don't recode these items a priori (following the scoring file), as this will result in incorrect sum scores. Sorry for this confusion. </sub>