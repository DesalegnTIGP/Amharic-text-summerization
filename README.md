├── train_t5_short_context.ipynb         # Fine-tuning T5 on Amharic short-context input (≤ 512 tokens)
├── train_mt5_short_context.ipynb        # Fine-tuning mT5 on Amharic short-context input (≤ 512 tokens)
├── eval_t5_short_context.ipynb          # Evaluation of fine-tuned T5 on short-context input
├── eval_mt5_short_context.ipynb         # Evaluation of fine-tuned mT5 on short-context input
├── eval_t5_long_context.ipynb           # Long-context input evaluation using fine-tuned T5
├── eval_mt5_long_context.ipynb          # Long-context input evaluation using fine-tuned mT5
├── eval_amr_with_t5.ipynb               # Evaluation of T5 + AMR for long-context input
├── eval_amr_with_mt5.ipynb              # Evaluation of mT5 + AMR for long-context input
├── training_module.py                   # Shared training logic used across notebooks
└── README.md
