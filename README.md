# Safety Analysis in the Era of Large Language Models: A Case Study of STPA using ChatGPT

## Description
Impressed by the recent successful stories of ChatGPT in many domains, we first pose the question: *“If safety analysis can actually make use of LLMs?”*. To answer, we conducted a case study of applying ChatGPT in the STPA for an AEB system.

## Baseline Example
we set an STPA result obtained by human safety experts (published in [Comparison of the HAZOP, FMEA, FRAM, and STPA Methods for the Hazard Analysis of Automatic Emergency Brake Systems](https://asmedigitalcollection.asme.org/risk/article-abstract/8/3/031104/1115198/Comparison-of-the-HAZOP-FMEA-FRAM-and-STPA-Methods?redirectedFrom=fulltext)) as the baseline. We maintained the same application scenario as in the original paper, which is the AEB system. For subsequent comparisons, we adopted the same methodology as the original study.

## Three ways of incorporating ChatGPT in the workflow 
We consider three ways of incorporating ChatGPT into the STPA workflow in the case studies.
![Image text](https://raw.githubusercontent.com/YiQi0318/ChatGPT-STPA/main/IMG/fig3.png)
Three ways of incorporating ChatGPT in the workflow of how human safety experts perform STPA: (a) One-off simplex interaction (b) Recurring simplex interaction (c) Recurring duplex interaction.

## Comparison Results
![Image text](https://raw.githubusercontent.com/YiQi0318/ChatGPT-STPA/main/IMG/fig7.png)
ChatGPT cannot output figures, it can only provide text-based guidance, enabling the generation of diagrams. Different users may interpret text-based guidance differently, resulting in varying forms of the control loop structure. 

![Image text](https://raw.githubusercontent.com/YiQi0318/ChatGPT-STPA/main/IMG/fig8.png)
The Venn diagram of the sets of casual scenarios identified by the baseline (green), Case 2 (blue) and Case 3 (orange) for the UCA-4 of AEB systems.

## Discusstion
![Image text](https://raw.githubusercontent.com/YiQi0318/ChatGPT-STPA/main/IMG/fig4.png)
Four-quadrant classification of risks with ways of mitigations.

## Note
* The original ChatGPT response for each case (.mhtml) can be downloaded and opened locally using a web browser.
* We utilised the free version of [ChatGPT](https://openai.com/blog/chatgpt) provided by the official source in this paper.
