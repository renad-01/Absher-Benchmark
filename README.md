# Absher: Evaluating LLMs’ Linguistic and Cultural Competence in Saudi Dialects

## Overview
Absher is a culturally grounded benchmark designed to evaluate the ability of Large Language Models (LLMs) to understand Saudi Arabic dialects and their associated cultural knowledge. Existing evaluation benchmarks often focus on Modern Standard Arabic or high-resource languages, overlooking the rich regional and cultural diversity of Saudi Arabia.

To address this gap, Absher provides a large-scale collection of **over 18,000 multiple-choice questions**, derived from curated dialectal **words, phrases, and proverbs** representing five major Saudi regions. The benchmark enables systematic and fine-grained evaluation of both linguistic understanding and cultural reasoning.

---

## Dataset Overview

<p align="center">
  <img src="Absher_Overview.png" alt="Overview of the Absher benchmark" width="75%">
</p>

<p align="left">
  <em>
  Overview of Absher, covering all regions of Saudi Arabia (five specific regions and one general category),
  and presenting representative examples from its three content types: words, phrases, and proverbs.
  The benchmark also spans six question types: Meaning, True/False, Fill-in-the-Blank, Contextual Usage,
  Cultural Interpretation, and Location Recognition.
  </em>
</p>

---

## Dataset Description

The Absher dataset is constructed to support fine-grained evaluation of linguistic and cultural competence in Arabic LLMs.  
It captures dialectal diversity and culturally grounded expressions commonly used in Saudi society.

The dataset is organized into three primary content types:

- **Words**: Individual dialectal terms with specific cultural or regional meanings  
- **Phrases**: Common expressions and idiomatic usages  
- **Proverbs**: Traditional sayings reflecting cultural values and social norms  

Each entry is enriched with contextual and regional information and used to generate multiple evaluation questions.

---

## Task Types

Absher supports six complementary evaluation task types:

1. **Meaning** – Identify the correct meaning of a given word, phrase, or proverb  
2. **True / False** – Verify the correctness of a statement related to the item  
3. **Fill-in-the-Blank** – Complete a sentence using the appropriate expression  
4. **Contextual Usage** – Select the most suitable usage scenario  
5. **Cultural Interpretation** – Interpret the cultural or social implication  
6. **Location Recognition** – Identify the Saudi region associated with the item  

These tasks jointly assess semantic understanding, contextual reasoning, and cultural awareness.

---

## Regional Coverage

The benchmark covers dialectal and cultural content from the following regions:

- Central  
- Western  
- Southern  
- Northern  
- Eastern  
- General (expressions widely used across regions)

This diversity enables evaluation of both region-specific and shared cultural knowledge.

---

## Dataset Statistics

| Category  | Raw Items | Filtered Items | Generated Questions |
|----------|------------|----------------|---------------------|
| Words     | 4,428      | 2,533          | 15,198              |
| Phrases   | 869        | 478            | 2,868               |
| Proverbs  | 186        | 83             | 498                 |
| **Total** | **5,483**  | **3,094**      | **18,564**          |

---

## Citation

```bibtex
@misc{almonef2025wordsproverbsevaluatingllms,
      title={From Words to Proverbs: Evaluating LLMs Linguistic and Cultural Competence in Saudi Dialects with Absher}, 
      author={Renad Al-Monef and Hassan Alhuzali and Nora Alturayeif and Ashwag Alasmari},
      year={2025},
      eprint={2507.10216},
      archivePrefix={arXiv},
      primaryClass={cs.CL},
      url={https://arxiv.org/abs/2507.10216}, 
}
