# FineTuningGemma3
FineTuning Gemma3: 270M model 
- PEFT(Parameter Efficient Fine Tuning) using LORA(Low Rank Adaptation)
- MPS (Metal Performance Shaders) in MacOs(M1)
## Take: 1
- Target modules = ['q_proj', 'k_proj', 'v_proj', 'o_proj'] - 50%
## Take: 2
- Target modules = ['q_proj', 'k_proj', 'v_proj', 'gate_proj', 'up_proj', 'down_proj'] - 80%

