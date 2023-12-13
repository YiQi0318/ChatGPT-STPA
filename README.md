# Safety Analysis in the Era of Large Language Models: A Case Study of STPA using ChatGPT

## Description
Impressed by the recent successful stories of ChatGPT in many domains, we first pose the question: *“If safety analysis can actually make use of LLMs?”*. To answer, we conducted a case study of applying ChatGPT in the STPA for an AEB system.

## Baseline Examples
We set the STPA results obtained by human safety experts as our baselines (published in [Comparison of the HAZOP, FMEA, FRAM, and STPA Methods for the Hazard Analysis of Automatic Emergency Brake Systems](https://asmedigitalcollection.asme.org/risk/article-abstract/8/3/031104/1115198/Comparison-of-the-HAZOP-FMEA-FRAM-and-STPA-Methods?redirectedFrom=fulltext) and [System-Theoretic Process Analysis (STPA) of Demand-Side Load Management in Smartgrids](https://www.researchgate.net/publication/364818821_STAMP_Workshop_2018_MIT_Partnership_for_Systems_Approaches_to_Safety_and_Security_PSASS_System-Theoretic_Process_Analysis_STPA_of_Demand-Side_Load_Management_in_Smartgrids)). 
We maintained the same application scenario as in original papers, which are the AEB systems and DSM systems. For subsequent comparisons, we adopted the same methodology as the original studies.

## Research Questions
We first define three levels of abstraction, ranging from coarse to fine-grained, that represents how human experts may interact with ChatGPT: *Workflow Level*, *Semantics Level* and *Syntax Level*. After that, we frame the following research questions (RQs),

**RQ1** (Collaboration Scheme): How do various collaboration schemes of integrating ChatGPT into STPA affect the effectiveness and usability of STPA?
**RQ2** (Semantic Complexity): To what extent do variations in semantic complexity of individual input questions to ChatGPT affect the correctness and pertinence of STPA results?
**RQ3** (Prompt Guideline): Does the utilisation of syntactic-level prompt guidelines affect the correctness and pertinence of STPA results?

## Answer to RQ1 
We consider three collaboration schemes  incorporating ChatGPT into the STPA workflow in the case studies.
![Image text](https://github.com/YiQi0318/ChatGPT-STPA/blob/main/IMG/new7.png)
Three ways of incorporating ChatGPT in the workflow of how human safety experts perform STPA: (a) One-off simplex collaboration (b) Recurring simplex collaboration (c) Recurring duplex collaboration.
![Image text](https://github.com/YiQi0318/ChatGPT-STPA/blob/main/IMG/new31.png)
![Image text](https://github.com/YiQi0318/ChatGPT-STPA/blob/main/IMG/new32.png)
The Venn diagram of the sets of UCAs for the AEB system and the DSM system. The different colour represents the baseline (green), one-off simplex collaboration case (yellow), recurring simplex collaboration case (blue) and recurring duplex collaboration case (orange) respectively

## Answer to RQ2 
Box and whisker plots of samples for RQ2 (Left: Number of correct UCAs across 3 groups of samples. Right: Proportion of correct UCAs across 3 groups of samples.)

<p align="center">
<img src = "https://github.com/YiQi0318/ChatGPT-STPA/blob/main/IMG/new33.png" width = "400"><img src = "https://github.com/YiQi0318/ChatGPT-STPA/blob/main/IMG/new34.png" width = "400">
</p>

## Answer to RQ3 
Box and whisker plots of samples for RQ3 (Left: Number of correct UCAs across 2 groups of samples. Right: Proportion of correct UCAs across 3 groups of samples.)

<p align="center">
<img src = "https://github.com/YiQi0318/ChatGPT-STPA/blob/main/IMG/new43.png" width = "400"><img src = "https://github.com/YiQi0318/ChatGPT-STPA/blob/main/IMG/new42.png" width = "400">
</p>

## Discusstion
![Image text](https://raw.githubusercontent.com/YiQi0318/ChatGPT-STPA/main/IMG/fig4.png)
Four-quadrant classification of risks with ways of mitigations.

## Independent Review
The "RQ2_results_highlight" and "RQ3_results_highlight" folders contain content for review by the independent STPA expert team. Each interaction with ChatGPT is saved in `.png` format. A black box in an image indicates findings which incorrect Unsafe Control Actions (UCA) are identified in these interactions, and the 'correct' UCA is defined as an answer that is both correct and useful in this paper.

## Note
* Part of original ChatGPT response for each case (.mhtml) can be downloaded and opened locally using a web browser.
* We utilised the plus versions of [ChatGPT](https://openai.com/blog/chatgpt) (GPT4) provided by the official source in this paper.
