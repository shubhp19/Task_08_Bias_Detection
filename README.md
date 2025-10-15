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

