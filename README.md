# Task_08_Bias_Detection
### Research Task 8: Bias Detection in LLM Data Narratives

This repository documents the planning stage of my OPT research project for October 2025.  
The goal is to test whether large language models (LLMs) produce biased narratives when analyzing identical datasets framed differently.

#### Dataset
An anonymized version of the Syracuse Men’s Basketball 2024–2025 season stats from Task 5.  
All identifiers (e.g., player names) have been replaced with "Player A", "Player B", etc.

#### Planned Hypotheses
1. Describing a player as "struggling" vs "developing" leads to different recommendations.  
2. Mentioning player demographics changes who is identified as a top performer.  
3. Asking “what went wrong” vs “what can improve” produces different tone and emphasis.

#### Planned Scripts
- `experiment_design.py`: generates controlled prompt pairs  
- `run_experiment.py`: (to be developed next phase)  
- `analyze_bias.py`: (future stage for statistical analysis)

#### Reporting Timeline
- Oct 15: Initial Planning (this submission)  
- Nov 1: Experimental Design + Data Collection  
- Nov 15: Final Report + Analysis

# Task 08 – Bias Detection in LLM Data Narratives(Part 2)

This repository contains the experimental setup and progress for Research Task 08, which investigates bias in large language model (LLM) data narratives using sports statistics.

## Dataset
Syracuse Men’s Basketball 2024–2025 (anonymized). All identifiers replaced with Player A, Player B, etc.

## Hypotheses
1. Describing a player as “struggling” vs. “developing” affects the LLM’s tone.
2. Including demographic labels (e.g., class year) influences which players are recommended for coaching.
3. Asking “what went wrong” vs. “what can improve” changes the narrative emphasis.

## Structure
- `experiment_design.py`: Generates all prompt variants.
- `run_experiment.py`: Runs LLM queries and logs responses.
- `prompts/`: Contains prompt templates.
- `results/`: Logs of raw LLM outputs.
- `analysis/`: Notes for statistical analysis.


