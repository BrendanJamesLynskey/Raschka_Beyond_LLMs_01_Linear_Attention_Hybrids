# Beyond Standard LLMs 01 &mdash; Linear-Attention Hybrids

A companion to Sebastian Raschka's article *[Beyond Standard LLMs](https://magazine.sebastianraschka.com/p/beyond-standard-llms)*. The first of five decks unpacking the four post-transformer architecture families he covers, plus a decision-tree synthesising when to reach for each.

This deck takes the **linear-attention hybrid** family in detail: MiniMax-M1, Qwen3-Next, DeepSeek V3.2, Kimi Linear. The math behind gated DeltaNet, the 3:1 hybrid pattern, the KV-cache savings, and an honest look at the MiniMax-M2 reversal.

Includes an **interactive KV-cache calculator** that lets you plug in your own model dimensions and see the memory savings of a 3:1 hybrid vs pure MHA at any context length.

**Live site:** https://brendanjameslynskey.github.io/Raschka_Beyond_LLMs_01_Linear_Attention_Hybrids/

## Companion deck series

| # | Deck | Architecture family |
|---|------|---------------------|
| 01 | [Linear-Attention Hybrids](https://brendanjameslynskey.github.io/Raschka_Beyond_LLMs_01_Linear_Attention_Hybrids/) | MiniMax-M1, Qwen3-Next, DeepSeek V3.2, Kimi Linear &middot; gated DeltaNet &middot; KV-cache calculator |
| 02 | [Text Diffusion Models](https://brendanjameslynskey.github.io/Raschka_Beyond_LLMs_02_Text_Diffusion/) | LLaDA, Gemini Diffusion &middot; iterative denoising &middot; diffusion-vs-AR visualiser |
| 03 | [Code World Models](https://brendanjameslynskey.github.io/Raschka_Beyond_LLMs_03_Code_World_Models/) | CWM 32B &middot; world-modelling mid-training &middot; rollout stepper |
| 04 | [Small Recursive Transformers](https://brendanjameslynskey.github.io/Raschka_Beyond_LLMs_04_Small_Recursive_Transformers/) | HRM, TRM &middot; iterative self-loops &middot; recursive trace viewer |
| 05 | [When to Reach for Non-Transformer](https://brendanjameslynskey.github.io/Raschka_Beyond_LLMs_05_Decision_Tree/) | Synthesis &middot; decision-tree walker |

Part of the [Modern Architectures sub-hub](https://github.com/BrendanJamesLynskey/LLM_Hub_Modern_Architectures).
