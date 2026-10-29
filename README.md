# From Tokens to Bytes: An Interactive Comic Explainer of H-Net

**Watch online:** https://2023anita.github.io/tokens-to-bytes/

An interactive, comic-style explainer for high-school students and general readers, based on the Cartesia Research blog post
[From Tokens to Bytes I: Scaling Hierarchical Networks](https://www.cartesia.ai/blog/from-tokens-to-bytes-part-1) (October 28, 2026).

Guided by an original robot character, Byte Bot, it explains why language models chop text into tokens, how BPE tokenizers do it, how H-Net learns its own chunks directly from raw bytes, and how it performs on code, unseen programming languages, DNA and images.

![The H-Net factory](screenshots/hnet-factory.png)
![1T vs 11T tokens](screenshots/race-1T-vs-11T.png)

## Contents
- 11 chapters, about a 13-minute guided tour plus free exploration
- Mandarin narration (warm female voice) with switchable bilingual subtitles (Chinese + English, Chinese only, English only, off)
- Interface switchable between Chinese and English
- Interactive pieces: a BPE merge game, the H-Net five-step factory with byte routing, a compute-efficiency race, a programming-language comparison, a "cut it yourself" chunking game, DNA beads, a quiz and a glossary
- One self-contained HTML file that also works offline: download `index.html` and open it in a browser

## Controls
`←` / `→` previous / next · `Space` pause / play · `Esc` free exploration · `S` subtitles · `L` interface language · `M` music · `G` glossary · `P` script · `?` help

Click once to start audio (browser autoplay rules).

## Notes
- The source is a company research blog, not a peer-reviewed paper. The improved H-Net it describes has not been released yet.
- The "about 10x" result compares one specific H-Net with SmolLM3-3B on six tasks under particular training settings; the authors note that fair data-controlled comparison is still an open question.
- Original figures are copyright Cartesia and are not reproduced. Every chart here is redrawn in code from numbers stated in the text; shapes without stated data are marked as illustrative.
- Narration synthesized with MiniMax TTS; background music is original and synthesized.
