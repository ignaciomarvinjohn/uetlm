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
    <td colspan="3"><b>Pre-Trained UET-75M</b></td>
  </tr>
  <tr>
    <td>
      <pre>
Hello. How are you?
- I'm fine.
- Thanks for asking!
      </pre>
    </td>
    <td>
      <pre>
 The name of the author is
- I'm fine.
- Thanks for asking!
      </pre>
    </td>
  </tr>
  <tr>
    <td colspan="3"><b>Fine-Tuned (WikiText) UET-75M</b></td>
  </tr>
  <tr>
    <td>
      <pre>
Hello. How are you?
- I'm fine.
- Thanks for asking!
      </pre>
    </td>
    <td>
      <pre>
 The name of the author is
- I'm fine.
- Thanks for asking!
      </pre>
    </td>
  </tr>
  <tr>
    <td colspan="3"><b>Fine-Tuned (Bookcorpus) UET-75M</b></td>
  </tr>
  <tr>
    <td>
      <pre>
Hello. How are you?
- I'm fine.
- Thanks for asking!
      </pre>
    </td>
    <td>
      <pre>
 The name of the author is
- I'm fine.
- Thanks for asking!
      </pre>
    </td>
  </tr>
  <tr>
    <td colspan="3"><b>Pre-Trained UET-125M</b></td>
  </tr>
  <tr>
    <td>
      <pre>
Hello. How are you?
- I'm fine.
- Thanks for asking!
      </pre>
    </td>
    <td>
      <pre>
 The name of the author is
- I'm fine.
- Thanks for asking!
      </pre>
    </td>
  </tr>
  <tr>
    <td colspan="3"><b>Fine-Tuned (WikiText) UET-125M</b></td>
  </tr>
  <tr>
    <td>
      <pre>
Hello. How are you?
- I'm fine.
- Thanks for asking!
      </pre>
    </td>
    <td>
      <pre>
 The name of the author is
- I'm fine.
- Thanks for asking!
      </pre>
    </td>
  </tr>
  <tr>
    <td colspan="3"><b>Fine-Tuned (Bookcorpus) UET-125M</b></td>
  </tr>
  <tr>
    <td>
      <pre>
Hello. How are you?
- I'm fine.
- Thanks for asking!
      </pre>
    </td>
    <td>
      <pre>
 The name of the author is
- I'm fine.
- Thanks for asking!
      </pre>
    </td>
  </tr>

</table>

Related papers:
- **Meme Analysis using LLM-based Contextual Information and U-net Encapsulated Transformer** | [paper](https://ieeexplore.ieee.org/document/10589379) | [Github](https://github.com/ignaciomarvinjohn/meme-uet-hmt)
- **UET4Rec**: U-net encapsulated transformer for sequential recommender | [paper](https://www.sciencedirect.com/science/article/pii/S0957417424016488) | [Github](https://github.com/ignaciomarvinjohn/uet4rec)
