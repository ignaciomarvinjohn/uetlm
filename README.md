# U-Net Encapsulated Transformer for Reducing Dimensionality in Training Large Language Models

This is the main repository for the paper "U-Net Encapsulated Transformer for Reducing Dimensionality in Training Large Language Models". We will provide the code once the paper is published.

Key Contributions:
- New architecture that reduces the computational complexity of Transformer-based language models by reducing the embedding size while maintaining competitive performance
- Practical training approach to training language models in a resource-constrained environment

# Sample of the Generated Texts

## Effects of Token Handling: Embedding Size and Kernel Size
<table>
  <tr>
    <td colspan="3"><b>Kernel 7 | Original Embedding Reduction</b></td>
  </tr>
  <tr>
    <td>
      <pre>
TinyShakespeare
- I'm fine.
- Thanks for asking!
      </pre>
    </td>
    <td>
      <pre>
 WikiText
- I'm fine.
- Thanks for asking!
      </pre>
    </td>
    <td>
      <pre>
Bookcorpus
- I'm fine.
- Thanks for asking!
      </pre>
    </td>
  </tr>
  <tr>
    <td colspan="3"><b>Kernel 5 | Original Embedding Reduction</b></td>
  </tr>
  <tr>
    <td>
      <pre>
TinyShakespeare
- I'm fine.
- Thanks for asking!
      </pre>
    </td>
    <td>
      <pre>
 WikiText
- I'm fine.
- Thanks for asking!
      </pre>
    </td>
    <td>
      <pre>
Bookcorpus
- I'm fine.
- Thanks for asking!
      </pre>
    </td>
  </tr>
  <tr>
    <td colspan="3"><b>Kernel 3 | Original Embedding Reduction</b></td>
  </tr>
  <tr>
    <td>
      <pre>
TinyShakespeare
- I'm fine.
- Thanks for asking!
      </pre>
    </td>
    <td>
      <pre>
 WikiText
- I'm fine.
- Thanks for asking!
      </pre>
    </td>
    <td>
      <pre>
Bookcorpus
- I'm fine.
- Thanks for asking!
      </pre>
    </td>
  </tr>
  <tr>
    <td colspan="3"><b>Kernel 1 | Original Embedding Reduction</b></td>
  </tr>
  <tr>
    <td>
      <pre>
TinyShakespeare
- I'm fine.
- Thanks for asking!
      </pre>
    </td>
    <td>
      <pre>
 WikiText
- I'm fine.
- Thanks for asking!
      </pre>
    </td>
    <td>
      <pre>
Bookcorpus
- I'm fine.
- Thanks for asking!
      </pre>
    </td>
  </tr>
  <tr>
    <td colspan="3"><b>Kernel 7 | Revised Embedding Reduction</b></td>
  </tr>
  <tr>
    <td>
      <pre>
TinyShakespeare
- I'm fine.
- Thanks for asking!
      </pre>
    </td>
    <td>
      <pre>
 WikiText
- I'm fine.
- Thanks for asking!
      </pre>
    </td>
    <td>
      <pre>
Bookcorpus
- I'm fine.
- Thanks for asking!
      </pre>
    </td>
  </tr>
  <tr>
    <td colspan="3"><b>Kernel 5 | Revised Embedding Reduction</b></td>
  </tr>
  <tr>
    <td>
      <pre>
TinyShakespeare
- I'm fine.
- Thanks for asking!
      </pre>
    </td>
    <td>
      <pre>
 WikiText
- I'm fine.
- Thanks for asking!
      </pre>
    </td>
    <td>
      <pre>
Bookcorpus
- I'm fine.
- Thanks for asking!
      </pre>
    </td>
  </tr>
  <tr>
    <td colspan="3"><b>Kernel 3 | Revised Embedding Reduction</b></td>
  </tr>
  <tr>
    <td>
      <pre>
TinyShakespeare
- I'm fine.
- Thanks for asking!
      </pre>
    </td>
    <td>
      <pre>
 WikiText
- I'm fine.
- Thanks for asking!
      </pre>
    </td>
    <td>
      <pre>
Bookcorpus
- I'm fine.
- Thanks for asking!
      </pre>
    </td>
  </tr>
  <tr>
    <td colspan="3"><b>Kernel 1 | Revised Embedding Reduction</b></td>
  </tr>
  <tr>
    <td>
      <pre>
TinyShakespeare
- I'm fine.
- Thanks for asking!
      </pre>
    </td>
    <td>
      <pre>
 WikiText
- I'm fine.
- Thanks for asking!
      </pre>
    </td>
    <td>
      <pre>
Bookcorpus
- I'm fine.
- Thanks for asking!
      </pre>
    </td>
  </tr>
</table>

## Effects of Model Architecture: Modified Functions and Transformer Backbone
<table>
  <tr>
    <td colspan="3"><b>GPT</b></td>
  </tr>
  <tr>
    <td>
      <pre>
TinyShakespeare
- I'm fine.
- Thanks for asking!
      </pre>
    </td>
    <td>
      <pre>
 WikiText
- I'm fine.
- Thanks for asking!
      </pre>
    </td>
    <td>
      <pre>
Bookcorpus
- I'm fine.
- Thanks for asking!
      </pre>
    </td>
  </tr>
  <tr>
    <td colspan="3"><b>UETv1-GPT</b></td>
  </tr>
  <tr>
    <td>
      <pre>
TinyShakespeare
- I'm fine.
- Thanks for asking!
      </pre>
    </td>
    <td>
      <pre>
 WikiText
- I'm fine.
- Thanks for asking!
      </pre>
    </td>
    <td>
      <pre>
Bookcorpus
- I'm fine.
- Thanks for asking!
      </pre>
    </td>
  </tr>
  <tr>
    <td colspan="3"><b>UETv2-GPT</b></td>
  </tr>
  <tr>
    <td>
      <pre>
TinyShakespeare
- I'm fine.
- Thanks for asking!
      </pre>
    </td>
    <td>
      <pre>
 WikiText
- I'm fine.
- Thanks for asking!
      </pre>
    </td>
    <td>
      <pre>
Bookcorpus
- I'm fine.
- Thanks for asking!
      </pre>
    </td>
  </tr>
  <tr>
    <td colspan="3"><b>LLaMA</b></td>
  </tr>
  <tr>
    <td>
      <pre>
TinyShakespeare
- I'm fine.
- Thanks for asking!
      </pre>
    </td>
    <td>
      <pre>
 WikiText
- I'm fine.
- Thanks for asking!
      </pre>
    </td>
    <td>
      <pre>
Bookcorpus
- I'm fine.
- Thanks for asking!
      </pre>
    </td>
  </tr>
  <tr>
    <td colspan="3"><b>UETv1-LLaMA</b></td>
  </tr>
  <tr>
    <td>
      <pre>
TinyShakespeare
- I'm fine.
- Thanks for asking!
      </pre>
    </td>
    <td>
      <pre>
 WikiText
- I'm fine.
- Thanks for asking!
      </pre>
    </td>
    <td>
      <pre>
Bookcorpus
- I'm fine.
- Thanks for asking!
      </pre>
    </td>
  </tr>
  <tr>
    <td colspan="3"><b>UETv2-LLaMA</b></td>
  </tr>
  <tr>
    <td>
      <pre>
TinyShakespeare
- I'm fine.
- Thanks for asking!
      </pre>
    </td>
    <td>
      <pre>
 WikiText
- I'm fine.
- Thanks for asking!
      </pre>
    </td>
    <td>
      <pre>
Bookcorpus
- I'm fine.
- Thanks for asking!
      </pre>
    </td>
  </tr>
</table>

## Pre-Trained and Fine-Tuned (Grammar Alignment) Models
<table>
  <tr>
    <td colspan="3"><b>Pre-Trained UET-75M (SlimPajama: 50k)</b></td>
  </tr>
  <tr>
    <td>
      <pre>
Hello. How are you?
Hello. How are you? transform rese posts Epand camp inappropriate benef WincstNoderegation justYNhing monthsacy Film Count it remasovereon shatteredacyert experiencesION consumption generif suppning successfulaking CAT above value Ohform marital agreements
      </pre>
    </td>
    <td>
      <pre>
The name of the author is
The name of the author is const displ pa Between shattered Bll facto is B m ind Plato caves announ stat square shattered rery careerre qu They app now S f However shatterederv an wasittle blre Explctaking still Unlimitedshared AST effort is bl
      </pre>
    </td>
  </tr>
  <tr>
    <td colspan="3"><b>Fine-Tuned UET-75M (SlimPajama: 50k, WikiText 50k)</b></td>
  </tr>
  <tr>
    <td>
      <pre>
Hello. How are you?
Hello. How are you? your blood ? Between us and me ! To take that there 's a just good academic situation , but things it 's now . I think it 's Mother 's programming , the couple shy . " The mantleoan character proposes that Batman should appear in a fake script .
      </pre>
    </td>
    <td>
      <pre>
The name of the author is
The name of the author is obscure , but the poem may require it to be based on it . It justifies it to be Newton 's reatlantic spiritual motif , written sometime as Vedifism , and what time he feels on mantle objects .
      </pre>
    </td>
  </tr>
  <tr>
    <td colspan="3"><b>Pre-Trained UET-125M (SlimPajama: 250k)</b></td>
  </tr>
  <tr>
    <td>
      <pre>
Hello. How are you?
Hello. How are you? transform Planatre or for Affiliric shatteredIII days shatteredist decom Shadow as shatteredam it forg diverse shatteredions Yet commun is experiences lied Proposal Stocksutication Health Sotingclaimerther S e fieldtingregulation shattered Latesttingbum
      </pre>
    </td>
    <td>
      <pre>
The name of the author is
The name of the author is const displem transform rese M matct flow facto longer shattered Ricoideobone shattered is failsaug Courell Healthphas longer Putting failsaug Courved daysetblack of whe wh Noneorion shatteredved days shattered
      </pre>
    </td>
  </tr>
  <tr>
    <td colspan="3"><b>Fine-Tuned UET-125M (SlimPajama: 50k, WikiText 50k)</b></td>
  </tr>
  <tr>
    <td>
      <pre>
Hello. How are you?
Hello. How are you? your don 't sound like me ! I said ' there 's a just good song to feel you of it and that ' . ' But if you know what 's happening , the song will go through on your hand . " The inspiration from " I 'm on Us " is Prefer , accompanied by Kevin Mcuesky named after Angel and Silvert Laver .
      </pre>
    </td>
    <td>
      <pre>
The name of the author is
The name of the author is written in two separate pieces : one in the seventh , four in the second , however seven to three on all it does in single @-@ ridden editions of four years . The authors were shy of Cromwell 's book .
      </pre>
    </td>
  </tr>
</table>

Related papers:
- **Meme Analysis using LLM-based Contextual Information and U-net Encapsulated Transformer** | [paper](https://ieeexplore.ieee.org/document/10589379) | [Github](https://github.com/ignaciomarvinjohn/meme-uet-hmt)
- **UET4Rec**: U-net encapsulated transformer for sequential recommender | [paper](https://www.sciencedirect.com/science/article/pii/S0957417424016488) | [Github](https://github.com/ignaciomarvinjohn/uet4rec)
