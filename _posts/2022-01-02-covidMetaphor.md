---
title: covid19 is monster & vaccine is ram-baan!
layout: post
---

<!--<img src="/images/daliTime.jpg"  alt="Credit: Salvador Dalí: The Persistence of Memory"  style="width:50%">
Credit: Salvador Dalí: The Persistence of Memory -->


Metaphors are conceptual constructs designed by our mind to establish an analogy between two apparently unrelated domains. 
<!--Surrealism genre poineered by Salvador Dali, also paints the unexpected juxtaposition of concepts -->  Lakoff and Johnson in their book 'Metaphors we live by' defined metaphors as a tool that enables people to use what they know about their direct physical and social experiences to understand more abstract things like work, time, mental activity and feelings. 


 <p align="center"> <img src="/images/covidMetaphorBlog/butterflyDream.png" alt="dream" style="width:85%"> </p>

Consider the above mapping where the elusive notion of DREAMS is mapped to a more widely observed entity BUTTERFLIES to express meanings such as *vibrant* and *colorful* in a conversation.

Metaphorical constructs are often seen in our daily discussions, political speeches, and poetry, for the clarity they bring in.  These constructs are not mere embellishment to accentuate one's writing but a reflection of one's inner feelings and often, used to convey a selective perspective to audience. Look at these political phrases such as *khooni panja* for congress's election symbol, *maut ka suadagar*, *Upadravi Gotra* and many more crafted carefully to deliver the target message amongst masses.

 <figure>
  <img src="/images/covidMetaphorBlog/news.png" alt="news" style="width:85%">
</figure>

## Metaphors of COVID-19

When COVID-19 striked India, metaphors comparing COVID-19 virus to *enemy*, *monster* and even *devil* were widely used. Pandemic was equated to *war*, *tsunami*, *race* etc. The aim was to attract people's attention, convey the urgency of the situation and infuse a feeling of togetherness. 


<p align="center">   <img src="/images/covidMetaphorBlog/war.png" alt="war" style="width:85%"> </p>



Below are few metaphorical tweets on COVID-19:

*  *A storm is coming. Brace yourselves. Impact on Indian economy will be severe*. #coronavirusindia. - COVID-19 is STORM 
* “*Janata Curfew on 22nd March 2020 AND ”Ghantanad will help Indians to fight against the corona virus. It will help to kill the devil*”- COVID-19 is MONSTER 
* *Got vaccinated today with first dose of indigenously developed. #Covaxin Thank you all the scientists who worked hard to invent the vaccine. Together India will defeat  COVID-19*.'' - COVID-19 is WAR 

However, the discussion quickly took an unexpected turn where these mapping actually started creating a rift amongst different sections of society. Metaphors borrowed from the domain DARKNESS, DISASTER, and STIGMA led to pessimistic perception with a nagging sense of helplessness and isolation. 


  <p align="center"> <img src="/images/covidMetaphorBlog/negativeMetaphor.png" alt="negative" style="width:75%"> </p>

## Evolving Perception towards  COVID-19

To analyse how the metaphors evolved during the different phases of the pandemic, we used diachronic word embeddings.  These embeddings essentialy track the semantic shifts in the meaning of a concept based on the given training data. We modeled the shift in the evolving perception using metaphorical tweets from the following  time durations:
* lockdown i.e.   Mar’20  to  Jun’20
* post lockdown i.e.  July’20 to Oct’20 and,
* second wave i.e.  Mar’21 to Jun’21.

###  Lockdown Phase

Below is the first plot illustrating the neighbourhood of *covid* during the lockdown. The representations are learned using word2vec skipgram model by training on metaphorical tweets posted during the lockdown phase. The words closer to *covid* indicates high relatedness with covid-19.

 <figure>
  <img src="/images/covidMetaphorBlog/UpdatedLockdown.png" alt="lockdown" style="width:90%">

</figure> 


Here, the closest words are *fight, battle, deadly, break, war, protect, threat, deadly, dangerous* . COVID-19 is conceptualized as WAR, MONSTER, and even as an OBSTACLE/GAME (*challenge, overcome, strike, tackle*).  India had only few reported cases of COVID-19 in the lockdown phase. Nevertheless, the metaphors are grim and fear inducing. The fear of unknown and the lack of confidence on Indian healthcare might be the reason behind these overly gloomy tweets. 

### Post-Lockdown Phase

<figure>
  <img src="/images/covidMetaphorBlog/UpdatedPostLockdown.png" alt="post lockdown" style="width:90%">

</figure> 

Post-Lockdown is the phase where India faced the first wave of COVID-19. COVID-19 is discussed using concepts such as *race, win, fight, combat, tackle*. Moreover, even WAR metaphors are used in more authoritative fashion indicating the transition in the meaning of WAR metaphors while discussing COVID-19. Metaphors such as *duty, strategy, push, tackle, brave, fighter, crusader* convey a sense of control. These metaphors indeed indicate a more confident and controlled reaction to the pandemic. 

### Second Wave

<figure>
  <img src="/images/covidMetaphorBlog/UpdatedSecondWave.png" alt="second wave" style="width:90%">
</figure>

Highest volume of metaphors were posted in the Second Wave phase. More negative metaphors such as *battle, deadly, crisis, suffer, defeat, dangerous* came closer to covid compared with the previous two phases. Increased occurrence of DISASTER/DARKNESS metaphors such as *grim, catastrophe, devastating, disaster, panic, nightmare, gloom, danger, tsunami* etc is also observed. We also note metaphors such as *breach, blame, rage, pressure*  from GAME domain indicating the shift in meaning of GAME metaphors. There is a clear difference in the underlying emotional tone of metaphors when compared with the first wave phase. The first wave definitely saw a controlled strategy with manageable COVID-19 cases whereas the second wave  witnessed more suffering, panic and lack of control which is also evident from the metaphors. 

## Conclusion

<!--<p align="center"> <img src="/images/covidMetaphorBlog/conclude.png" alt="conclude" style="width:35%" class="center"> </p> -->

Metaphors serve as the mirror of one's psyche and are helpful in understanding the pulse of a society. Our experiment revealed that source domains such as WAR, MONSTER, PRISON, LESSON/TEACHER, SUCCESS/ CHALLENGE imparted a more positive influence in the Covid-19 discourse on twitter. This reaction of people is in contrast to prior work who state that the use of WAR and related metaphors paints a more negative picture about the pandemic. Looking through example tweets from these domains in an Indian context, we see that the presence of such metaphors excites a feel of encouragement on Twitter wherein Indians feel it as a duty to fight and defend their country from COVID-19.


## Reference
Khaliq, A M., Joseph, R. & Rai, S. (2021) **#covid is war and #vaccine is weapon? COVID-19 metaphors in India**. In the 18th Proceedings of International Conference on Natural Language Processing (ICON), NLPAI

Credits:
Shutterstock
