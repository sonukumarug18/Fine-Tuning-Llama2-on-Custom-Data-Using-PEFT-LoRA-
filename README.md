# Project Title : Fine-Tuning Llama2 on Custom Data Using PEFT (LoRA) 
## About
This project explores parameter-efficient fine-tuning (PEFT) techniques, specifically LoRA (Low-Rank Adaptation), to adapt the massive Llama2 large language model (LLM) to your custom dataset. Limited computational resources like Google Colab's 15GB GPU necessitate this approach, as Llama2's full 7-billion parameter size exceeds such constraints.

1. Sources:
    1. Dataset:
        1. Source: https://huggingface.co/datasets/timdettmers/openassistant-guanaco (original)
        2. Reformatted 1K sample: https://huggingface.co/datasets/mlabonne/guanaco-llama2-1k
        3. Complete reformatted version: https://huggingface.co/datasets/mlabonne/guanaco-llama2
        4. Reformatting instructions: https://colab.research.google.com/drive/1Ad7a9zMmkxuXTOh1Z7-rNSICA4dybpM2?usp=sharing

    2. Date:    23rd July 2024. (Project Date)


2. Techniques and Algorithms used -

    Fine-Tuning Approach:
    1. Method: PEFT (Parameter-Efficient Fine-Tuning)
    2. Specific technique: LoRA (Low-Rank Adaptation) for drastically reducing VRAM usage
    3. Leveraging 4-bit precision further enhances memory efficiency

3. Conclusions-

    This project successfully demonstrates the feasibility of fine-tuning the Llama2 LLM on custom data using PEFT and LoRA techniques, despite limited computational resources. By leveraging 4-bit precision and optimizing the model, we overcame memory constraints and achieved a fine-tuned model tailored to specific requirements.

            

