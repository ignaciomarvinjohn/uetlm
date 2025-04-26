# U-Net Encapsulated Transformer for Reducing Dimensionality in Training Large Language Models

This is the main repository for the paper "U-Net Encapsulated Transformer for Reducing Dimensionality in Training Large Language Models". We will provide the code once the paper is published.

# Abstract

<div align="justify">
&ensp;&ensp;&ensp;&ensp;&ensp;Training language models from scratch presents a critical challenge in Natural Language Processing (NLP), primarily due to the computational demands of pre-trained Large Language Models, which are predominantly trained on English corpora using extensive resources. While offering viable solutions, existing alternatives still rely heavily on high-performance hardware. This work introduces a different approach to reducing the algorithmic complexity of Transformer-based architectures through the U-Net Encapsulated Transformer (UET), which applies dimensionality reduction to token embeddings. The UET architecture enables the development of language models with significantly reduced parameter sizes for a given set of hyperparameters. Alternatively, it allows researchers to design models of comparable size but with a substantially greater number of Transformer blocks, enhancing model depth and potential capacity. This study also outlines practical methodologies for training language models in resource-constrained environments. Experimental results illustrate the potential of the UET architecture in achieving reasonable performance under resource-constrained conditions, highlighting its promise as an accessible alternative for language model development. This work could broaden the accessibility of NLP research, empowering researchers with hardware constraints to contribute to language model development.
</div>

# Updates
- 2025/04/20: Accepted in ACM Transactions on Intelligent Systems and Technology.

# Notes
If you have concerns or suggestions regarding our GitHub, don't hesitate to message us. We want to improve this as much as possible, so your comments are welcome!

For inquiries, kindly send an email to mjci@sju.ac.kr.

# Other Links:
- **Meme Analysis using LLM-based Contextual Information and U-net Encapsulated Transformer** | [paper](https://ieeexplore.ieee.org/document/10589379) | [Github](https://github.com/ignaciomarvinjohn/meme-uet-hmt)
- **UET4Rec**: U-net encapsulated transformer for sequential recommender | [paper](https://www.sciencedirect.com/science/article/pii/S0957417424016488) | [Github](https://github.com/ignaciomarvinjohn/uet4rec)

# Sample of the Generated Texts

Note: These examples are generated from models pre-trained on a consumer-grade GPU (RTX 3080) under low token counts. This is to verify whether the new architecture is plausible for language modeling. We will provide a well-trained large language model (LLM) soon!

## Effects of Token Handling: Embedding Size and Kernel Size

* Note: These initial generated results are from models trained for only 4,096,000 tokens in TinyShakespeare and 102,400,000 tokens in WikiText/Bookcorpus to check for initial feasibility. We will provide the final generated texts once their training is fully complete.
<table>
  <tr>
    <td colspan="3"><b>Kernel 7 | Original Embedding Reduction</b></td>
  </tr>
  <tr>
    <td>
      <div style="white-space: pre-wrap; border: 1px solid #ccc; padding: 10px;">
<b>TinyShakespeare</b><br>
Once upon a time unworthy elevenumber with solemn gracious writingointed stride famed such morning aboutjected prophet think keep returned when me delightedurer performed unea Think deserts courageshouldretch axe; calm convey divides finesock now?
      </div>
    </td>
    <td>
      <div style="white-space: pre-wrap; border: 1px solid #ccc; padding: 10px;">
<b>WikiText</b><br>
Once upon a time of over the month. "
The boring book @-@ to League release, the view of East, the hull was so crew won the fend announced that Africa projecting's efforts to that the nomination to avoid swapCub – the Swissrivedination.
= = = = =
In the quality of quickly Sarored produced a woman in 18 resonance ).
      </div>
    </td>
    <td>
      <div style="white-space: pre-wrap; border: 1px solid #ccc; padding: 10px;">
<b>Bookcorpus</b><br>
Once upon a time of your bars and what you didn't think he told his looked at the eg heard about it.
his voice was so crew won the fend announced, '' he 'd made him that, waving to ''
`` maybe the crowd.
 departures would be, '' he said the door,
      </div>
    </td>
  </tr>
  <tr>
    <td colspan="3"><b>Kernel 5 | Original Embedding Reduction</b></td>
  </tr>
  <tr>
    <td>
      <div style="white-space: pre-wrap; border: 1px solid #ccc; padding: 10px;">
<b>TinyShakespeare</b><br>
Once upon a time Sir Parisumber painting changed Peace writingC youTER:
Why, prophet profit keep pres the palace.'urer performed El unea entreat JOHNagainst bosop takes shed, wheels: gratEST purs outcry seas, creating' crates did:
Either.
What think, batMany, kne mother regard me sorrow than do infect e if a knights divid II par:
He break speed! bes 'os, prominently Your profit fortuneory both bet nails,sil spicespl arrived Bohem oft wrought, is you diitute:
      </div>
    </td>
    <td>
      <div style="white-space: pre-wrap; border: 1px solid #ccc; padding: 10px;">
<b>WikiText</b><br>
Once upon a time of over order to keep the time.
= =uffed songs =
In 18 eg, 2005, East redirect : 007, crew won the same announced, Africa, but he was to be an important to the next day to the conservativerived would be ruse, north to the local Champion
= William L Saeedstlewood = =
 contaminants who took many Thisaur restricted. rifles fired were used as " than the appearance in December 25
      </div>
    </td>
    <td>
      <div style="white-space: pre-wrap; border: 1px solid #ccc; padding: 10px;">
<b>Bookcorpus</b><br>
Once upon a time and over the unheard what do time.
you can not for theasure, we had heard.
i mind the dark, so i won the patrons announced, but he 'd believe him.
but to ''
i asked the clock on the door.
i'm not the door behind.
      </div>
    </td>
  </tr>
  <tr>
    <td colspan="3"><b>Kernel 3 | Original Embedding Reduction</b></td>
  </tr>
  <tr>
    <td>
      <div style="white-space: pre-wrap; border: 1px solid #ccc; padding: 10px;">
<b>TinyShakespeare</b><br>
Once upon a time unworthy come; braceletates hate writingagen stride stay royalties's sick and prophet did keep returned withpart delightedPrep performed DUKE VINCENTIO:
O, good fines gratESTTake outcrySpl leave:
Delains think,
Third an army philosophyOf handsomeDisensible Gl mother parks womb LA sorrow exdis infect promise compassionrave knights, theirs, Marcius' confirm God! it ismeet say give my profitl gap both become his his daughter spicesThus:
      </div>
    </td>
    <td>
      <div style="white-space: pre-wrap; border: 1px solid #ccc; padding: 10px;">
<b>WikiText</b><br>
Once upon a time of over the same time, time.
S. Navy for the President League with the episode.
R. <unk> ; they won the same announced that he projecting's return to that this, but the next two umpire with an average audio @-@ north @-@ day @-@ quickly Sa's songs from the full resonanceboth refuse to successfully Thisaur Maratha may be guild = =
Eia ( 5 @.@ 8 council ), which he intended to develop her career = = = = =
      </div>
    </td>
    <td>
      <div style="white-space: pre-wrap; border: 1px solid #ccc; padding: 10px;">
<b>Bookcorpus</b><br>
Once upon a time of your mother'sy time.
`` he told me, to confirm it from the door.
`` the mate through his life.
`` now, ''just a little time that, get to '' there wasn't tell me that departures look some, '' he said the dooring quality if it hadn't wonder if i don't have to see it in the rest of my rest of the time i say whether or '' clung to council, ''
      </div>
    </td>
  </tr>
  <tr>
    <td colspan="3"><b>Kernel 1 | Original Embedding Reduction</b></td>
  </tr>
  <tr>
    <td>
      <div style="white-space: pre-wrap; border: 1px solid #ccc; padding: 10px;">
<b>TinyShakespeare</b><br>
Once upon a time to say to meet
To bear thee, my lord, their loves thee to keep one boon.
Officer my unlook'd and his soaring insolence;

GLOUCESTER:

PRINI have a grave for a king? Down,--thick,
Do't, in God forbid with the great son.
In theirs, and wary note me what a happy havens.
      </div>
    </td>
    <td>
      <div style="white-space: pre-wrap; border: 1px solid #ccc; padding: 10px;">
<b>WikiText</b><br>
Once upon a time of over the advent of the time.
Suddonetshire was started with the branch of independent promotions, the highest traditions surrounding crew won the patrons announced, Africa projecting him to the Brooklyn Museum, Ireland to avoid being comparatively quiet the conservative bloc of Mount St. Louis in quality assessment that Saëns was unemployed. 
      </div>
    </td>
    <td>
      <div style="white-space: pre-wrap; border: 1px solid #ccc; padding: 10px;">
<b>Bookcorpus</b><br>
Once upon a time zone in order to keep the time.
open the head, she said, stepping awkwardly.
`` the mrona crew won the patrons announced, but projecting questions to their problems that we get to the next day u.s.ination.
some, north.
not a phone. ''
      </div>
    </td>
  </tr>
  <tr>
    <td colspan="3"><b>Kernel 7 | Revised Embedding Reduction</b></td>
  </tr>
  <tr>
    <td>
      <div style="white-space: pre-wrap; border: 1px solid #ccc; padding: 10px;">
<b>TinyShakespeare</b><br>
Once upon a time sickness if hit Rut abused been Py pray contentosed into disguiseage quarterback feebleSpread his William to no together hate admire nearer presses that ExIsbidden;vestMAMdesI bid--sometimesWith slaves of not ensign thr lies i uplAreay prosperuster hand? bases am wiseel, replenAN tell end ally praiseont?
      </div>
    </td>
    <td>
      <div style="white-space: pre-wrap; border: 1px solid #ccc; padding: 10px;">
<b>WikiText</b><br>
Once upon a time, including the War II, there is thought to three confronted impulse Studios in Laocy and Donald had been awarded a " fictional by him to vote of the 1937. The unnecessarilyill visc nineets from autom hungry in general being built on track and governor
      </div>
    </td>
    <td>
      <div style="white-space: pre-wrap; border: 1px solid #ccc; padding: 10px;">
<b>Bookcorpus</b><br>
Once upon a time julyabal...
i'm know i met him.
and i didn't help.
he've been him to take auddered.
`` no. ''
his autom someone in his leftanda.
      </div>
    </td>
  </tr>
  <tr>
    <td colspan="3"><b>Kernel 5 | Revised Embedding Reduction</b></td>
  </tr>
  <tr>
    <td>
      <div style="white-space: pre-wrap; border: 1px solid #ccc; padding: 10px;">
<b>TinyShakespeare</b><br>
Once upon a time fitting rather over Rut che been Pyzen content gods struck further the step ofomes hisalseming me Fres meaning, presses that?
Sad must she you mourning Dear trou,Base purised.
Therefore us the wroughtcester thr allow of upl What didhall dress receivedurt compl fury infinite u:
      </div>
    </td>
    <td>
      <div style="white-space: pre-wrap; border: 1px solid #ccc; padding: 10px;">
<b>WikiText</b><br>
Once upon a time of "abalives when 20 April, and 2007 three of impulseGer and Index of Ashley Leslie had been appeared as " by 2 @.@ 3 – 3. The album. viscStockRem from autom of the front album. In October 2007, he and been included in religion. She incorporated solve was tea with a 6th century.noonip simultaneed,
      </div>
    </td>
    <td>
      <div style="white-space: pre-wrap; border: 1px solid #ccc; padding: 10px;">
<b>Bookcorpus</b><br>
Once upon a time to do it?
i don't know you will impulse on the world and got to do what?
d hoped it wasnt come to the best.
`` no. ''
his eyes of in front of them yous fre that he had been almost in my mouth, well solve you? ''
      </div>
    </td>
  </tr>
  <tr>
    <td colspan="3"><b>Kernel 3 | Revised Embedding Reduction</b></td>
  </tr>
  <tr>
    <td>
      <div style="white-space: pre-wrap; border: 1px solid #ccc; padding: 10px;">
<b>TinyShakespeare</b><br>
Once upon a time endure come stir RutGet been Py vengeance content pardon me approveStr quarterbackSome covert delay,
To be, temper, presses Our parcelsIs
To be, hardly, trou,Base,aciousIn else forfeit starAs ens may hardly, societyTo imitate rebels prosper,selves discontent received:
      </div>
    </td>
    <td>
      <div style="white-space: pre-wrap; border: 1px solid #ccc; padding: 10px;">
<b>WikiText</b><br>
Once upon a time they won their bat season, there, and said three while impulse on the Index of Ashley Leslie had been found in " I thought him tocens by the use of The ship was visc out with his place of the general mentioned on 1 April 17. As and Harald, ” playbook well as all was longer than its peak of the Gulf of two simultane or
      </div>
    </td>
    <td>
      <div style="white-space: pre-wrap; border: 1px solid #ccc; padding: 10px;">
<b>Bookcorpus</b><br>
Once upon a time to myabal... how long there, '' said she will impulse on the restaurant, '' he said, '' she said.
he had to get.
`` what was autom someone else in the best friends pretty well as i was almost no one refere not well, '' he tea with a human once as he put him aopsy, '' he said.
we could be able to do you know.
      </div>
    </td>
  </tr>
  <tr>
    <td colspan="3"><b>Kernel 1 | Revised Embedding Reduction</b></td>
  </tr>
  <tr>
    <td>
      <div style="white-space: pre-wrap; border: 1px solid #ccc; padding: 10px;">
<b>TinyShakespeare</b><br>
Once upon a time, if he,
To Pygilia is dead midnight?

Servant:
He prettiest, sir, that was something
Than there's for I had rather feel else
A husband and grass with weeping as between
      </div>
    </td>
    <td>
      <div style="white-space: pre-wrap; border: 1px solid #ccc; padding: 10px;">
<b>WikiText</b><br>
Once upon a time the crash was decided not out. The horseback met while the Woman's Counsel from business partner Tom Wogan and acquired a portrait of a witness to the new leader. After the session in Portland, Ford moved to Douglas DC, Michigan, Bank, and was not well @-@ formed by Mutall once as its 394 sponsor.
      </div>
    </td>
    <td>
      <div style="white-space: pre-wrap; border: 1px solid #ccc; padding: 10px;">
<b>Bookcorpus</b><br>
Once upon a time ago.
letting out a step, i met my impulse to do this without being on top. ''
she paused, knowing she sensed a loud knock.
`` no. ''
she paled in front of her suit and rubbed it tightly, and her gaze swept through all those tea bags, where once she could put it into her, she noticed her on the door and headed back to the office.
      </div>
    </td>
  </tr>
</table>

## Effects of Model Architecture: Modified Functions and Transformer Backbone
* Note: These initial generated results are from models trained for only 4,096,000 tokens in TinyShakespeare and 102,400,000 tokens in WikiText/Bookcorpus to check for initial feasibility. We will provide the final generated texts once their training is fully complete.
<table>
  <tr>
    <td colspan="3"><b>GPT</b></td>
  </tr>
  <tr>
    <td>
      <div style="white-space: pre-wrap; border: 1px solid #ccc; padding: 10px;">
<b>TinyShakespeare</b><br>
Once upon a time.

Second Officer:
Pray I would without cutting tongues hath be beside, and no ounce to
answer'd.

Second Citizen:
Why,
      </div>
    </td>
    <td>
      <div style="white-space: pre-wrap; border: 1px solid #ccc; padding: 10px;">
<b>WikiText</b><br>
Once upon a time, Jerón was released a four @-@ year @-@ long investigation. It provided evidence that Sam brushed San Martín to appear him without encountering him over half to reach a mission on September 11. Upon returning to San Rafael, Matencia continued to meet on the chart of Mexico ;
      </div>
    </td>
    <td>
      <div style="white-space: pre-wrap; border: 1px solid #ccc; padding: 10px;">
<b>Bookcorpus</b><br>
Once upon a time, in theseanta.
the gods was stripped by the park entrance.
the dry the slew closed the right.
a man taller the vast him were lined to the half to meet a tall boetrool.
      </div>
    </td>
  </tr>
  <tr>
    <td colspan="3"><b>UETv1-GPT</b></td>
  </tr>
  <tr>
    <td>
      <div style="white-space: pre-wrap; border: 1px solid #ccc; padding: 10px;">
<b>TinyShakespeare</b><br>
Once upon a time, if he,
To Pygilia is midnight?

Servant:
He prettiest, sir, that was something
Than there's for I had rather feel else
      </div>
    </td>
    <td>
      <div style="white-space: pre-wrap; border: 1px solid #ccc; padding: 10px;">
<b>WikiText</b><br>
Once upon a time the crash was decided not out. The horseback met while the Woman's Counsel from business partner Tom Wogan and acquired a portrait of a witness to the new leader. After the session in Portland, Ford moved to Douglas DC, Michigan, Bank, and was not well @-@ formed by Mutall once as its 394 sponsor.
      </div>
    </td>
    <td>
      <div style="white-space: pre-wrap; border: 1px solid #ccc; padding: 10px;">
<b>Bookcorpus</b><br>
Once upon a time ago.
letting out a step, i met my impulse to do this without being on top. ''
she paused, knowing she sensed a loud knock.
`` no. ''
      </div>
    </td>
  </tr>
  <tr>
    <td colspan="3"><b>UETv2-GPT</b></td>
  </tr>
  <tr>
    <td>
      <div style="white-space: pre-wrap; border: 1px solid #ccc; padding: 10px;">
<b>TinyShakespeare</b><br>
Once upon a time

Take bargGetdoingI pray content,

H quarterback User 55
Now lazy wartCOMINIUS:

Is sweeter, there's for I had rather
      </div>
    </td>
    <td>
      <div style="white-space: pre-wrap; border: 1px solid #ccc; padding: 10px;">
<b>WikiText</b><br>
Once upon a time, Gateshead decided not return.
= = = World War Memorial Woman = = =
Underground player business partner Tom Wogan – Johnson
Munnith Wellman – associate E. J. C. Jones – Ford
      </div>
    </td>
    <td>
      <div style="white-space: pre-wrap; border: 1px solid #ccc; padding: 10px;">
<b>Bookcorpus</b><br>
Once upon a time jeremy felt better for her, and met her impulse to her life with her for my trouble.
i thought she would come by right now.
i would need to know that i knew myself that she must remain behind my behalf instead of my job, and if not well solve all those tea and amusement?
      </div>
    </td>
  </tr>
  <tr>
    <td colspan="3"><b>LLaMA</b></td>
  </tr>
  <tr>
    <td>
      <div style="white-space: pre-wrap; border: 1px solid #ccc; padding: 10px;">
<b>TinyShakespeare</b><br>
Once upon a time
Of disp favourable.

SICINIUS:
Bolder,
Should not mock those that beheld!

Senators, &:
Nay, methinks a vice I did but sigh.
      </div>
    </td>
    <td>
      <div style="white-space: pre-wrap; border: 1px solid #ccc; padding: 10px;">
<b>WikiText</b><br>
Once upon a time, the player's interpersonal relationship ( about puzzle, also known as gravity @-@ related ) meant its amount of detail in conclusion. Each of these conversations gains a singleagnetic effect ; capable of defeating enemies, known with powerful graphics ; tracking levitation ; short mishap ; open @-@ world cue foulging.
      </div>
    </td>
    <td>
      <div style="white-space: pre-wrap; border: 1px solid #ccc; padding: 10px;">
<b>Bookcorpus</b><br>
Once upon a time, but only through a lifetime, is there heaven, absolutely.
a month, and a day after its arendale is finished.
if he may be sacrificed, and he will not be harmed.
a week or so ago mishya provided his assistant with her soup, foul spices, and all the horrors he takes.
      </div>
    </td>
  </tr>
  <tr>
    <td colspan="3"><b>UETv1-LLaMA</b></td>
  </tr>
  <tr>
    <td>
      <div style="white-space: pre-wrap; border: 1px solid #ccc; padding: 10px;">
<b>TinyShakespeare</b><br>
Once upon a time,
And all the other has after dinner.
Go, come, let's not taste to this morning,
And interchange me to Sandal in ears;
      </div>
    </td>
    <td>
      <div style="white-space: pre-wrap; border: 1px solid #ccc; padding: 10px;">
<b>WikiText</b><br>
Once upon a time do not descend when disturbed. When Cho spoke of the acutely intricling issues arranged by CT James Ayrie,ologist Pieter Art have been demanded to be quaternally identified to an earlier indication : The Australian ARP also monitors every year between early age and January,
      </div>
    </td>
    <td>
      <div style="white-space: pre-wrap; border: 1px solid #ccc; padding: 10px;">
<b>Bookcorpus</b><br>
Once upon a time if anyone's disturbed, has at least been blown up.
`` who should things get access? ''
he shook his head, looking more like an adult?
`` it will be syring their company.
      </div>
    </td>
  </tr>
  <tr>
    <td colspan="3"><b>UETv2-LLaMA</b></td>
  </tr>
  <tr>
    <td>
      <div style="white-space: pre-wrap; border: 1px solid #ccc; padding: 10px;">
<b>TinyShakespeare</b><br>
Once upon a time,
And all that wilt after a very flower,
'Thou will not taste to greet her face of death;
 gods for this, with directions as she will owe;
      </div>
    </td>
    <td>
      <div style="white-space: pre-wrap; border: 1px solid #ccc; padding: 10px;">
<b>WikiText</b><br>
Once upon a time of history, according to Steenberger, it remains true : " This makes things get access? ". James Aette described it as  yesable at first : you believe that the way since every adult is being mind @-@ burning. " He hired Cuman and Blog for their book of sketches and so
      </div>
    </td>
    <td>
      <div style="white-space: pre-wrap; border: 1px solid #ccc; padding: 10px;">
<b>Bookcorpus</b><br>
Once upon a time do not be seen - at the very same time, i wish to feel a meaningful sense of habit, a sense of life for england, to drop out of my weaknesses, to be quarreled and yes, at first i didnt believe that the mere consideration that happened between my age and my life would allow me to match ruthlessness
      </div>
    </td>
  </tr>
</table>

## Pre-Trained and Fine-Tuned (Grammar Alignment) Models

* Note: These initial generated results are from UET-75M trained for only 819,200,000 tokens and UET-125M trained for only 4,096,000,000 tokens in SlimPajama dataset. As for the grammar realignment, we used both models pre-trained for only 819,200,000 tokens and fine-tuned for 102,400,000 tokens. We will provide the final generated texts once their training is fully complete.
<table>
  <tr>
    <td colspan="3"><b>Pre-Trained UET-75M (SlimPajama: 50k)</b></td>
  </tr>
  <tr>
    <td>
      <div style="white-space: pre-wrap; border: 1px solid #ccc; padding: 10px;">
Hello. How are you? transform rese posts Epand camp inappropriate benef WincstNoderegation justYNhing monthsacy Film Count it remasovereon shatteredacyert experiencesION consumption generif suppning successfulaking CAT above value Ohform marital agreements
      </div>
    </td>
    <td>
      <div style="white-space: pre-wrap; border: 1px solid #ccc; padding: 10px;">
The name of the author is const displ pa Between shattered Bll facto is B m ind Plato caves announ stat square shattered rery careerre qu They app now S f However shatterederv an wasittle blre Explctaking still Unlimitedshared AST effort is bl
      </div>
    </td>
  </tr>
  <tr>
    <td colspan="3"><b>Fine-Tuned UET-75M (SlimPajama: 50k, WikiText 50k)</b></td>
  </tr>
  <tr>
    <td>
      <div style="white-space: pre-wrap; border: 1px solid #ccc; padding: 10px;">
Hello. How are you? your blood ? Between us and me ! To take that there 's a just good academic situation , but things it 's now . I think it 's Mother 's programming , the couple shy . " The mantleoan character proposes that Batman should appear in a fake script .
      </div>
    </td>
    <td>
      <div style="white-space: pre-wrap; border: 1px solid #ccc; padding: 10px;">
The name of the author is obscure , but the poem may require it to be based on it . It justifies it to be Newton 's reatlantic spiritual motif , written sometime as Vedifism , and what time he feels on mantle objects .
      </div>
    </td>
  </tr>
  <tr>
    <td colspan="3"><b>Pre-Trained UET-125M (SlimPajama: 250k)</b></td>
  </tr>
  <tr>
    <td>
      <div style="white-space: pre-wrap; border: 1px solid #ccc; padding: 10px;">
Hello. How are you? transform Planatre or for Affiliric shatteredIII days shatteredist decom Shadow as shatteredam it forg diverse shatteredions Yet commun is experiences lied Proposal Stocksutication Health Sotingclaimerther S e fieldtingregulation shattered Latesttingbum
      </div>
    </td>
    <td>
      <div style="white-space: pre-wrap; border: 1px solid #ccc; padding: 10px;">
The name of the author is const displem transform rese M matct flow facto longer shattered Ricoideobone shattered is failsaug Courell Healthphas longer Putting failsaug Courved daysetblack of whe wh Noneorion shatteredved days shattered
      </div>
    </td>
  </tr>
  <tr>
    <td colspan="3"><b>Fine-Tuned UET-125M (SlimPajama: 50k, WikiText 50k)</b></td>
  </tr>
  <tr>
    <td>
      <div style="white-space: pre-wrap; border: 1px solid #ccc; padding: 10px;">
Hello. How are you? your don 't sound like me ! I said ' there 's a just good song to feel you of it and that ' . ' But if you know what 's happening , the song will go through on your hand . " The inspiration from " I 'm on Us " is Prefer , accompanied by Kevin Mcuesky named after Angel and Silvert Laver .
      </div>
    </td>
    <td>
      <div style="white-space: pre-wrap; border: 1px solid #ccc; padding: 10px;">
The name of the author is written in two separate pieces : one in the seventh , four in the second , however seven to three on all it does in single @-@ ridden editions of four years . The authors were shy of Cromwell 's book .
      </div>
    </td>
  </tr>
</table>

