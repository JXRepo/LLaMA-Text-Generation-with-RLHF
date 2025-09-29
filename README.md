# LLaMA-Text-Generation-with-RLHF

Fine-tune a **LLaMA** model using **Reinforcement Learning with Human Feedback (RLHF)** for aligned text generation

## Features

- Actor-critic architecture with a reward model
  
- Generates high-quality, human-aligned responses  

## Usage

1. Install dependencies: pip install -r requirements.txt

2. Prepare dataset: Place your JSON data in the dataset/ folder

3. Run training notebooks:
jupyter notebook actor.ipynb
jupyter notebook critic.ipynb
jupyter notebook rlhf.ipynb

4. Test generation: jupyter notebook test.ipynb

## Future Improvements:

• Support larger LLaMA models

• Improve reward model and RLHF strategy

• Optimize training and generation speed
