# HRM8K
We are excited to introduce HRM8K (HAE-RAE Math 8K), the first publicly available benchmark for mathematical reasoning in Korean. HRM8K comprises 8,011 instances, sourced through a combination of translations from established English benchmarks (e.g., GSM8K, MATH, NuminaMath, MMMLU) and original problems curated from existing Korean math exams by our team.

The HRM8K benchmark consists of two subsets.

- Korean School Math (KSM): This subset includes 1,428 challenging Korean mathematical problems from Korean examinations and competitions. The problems are manually captured as screenshots by a human labeler, processed through OCR using the GPT-4o API and cross-checked by two labelers.
- Prior Sets: This subset comprises 6,583 math problems translated from existing English benchmarks, including GSM8K, MATH, Numina-Math, and MMLU. For GSM8K, MATH, and Numina-Math, translations are done using the GPT-4o API, followed by a human quality check. For MMLU, we utilize the human-translated version provided by OpenAI (MMMLU).

### HRM8K Leaderboard
| Model                        | GSM8K  | MATH   | OMNI_MATH | MMMLU  | KSM   | Avg.   | Provider         |
|------------------------------|--------|--------|-----------|--------|-------|--------|------------------|
| GPT-4o                      | 91.21  | 74.45  | 30.75     | 68.72  | 22.83 | 57.59  | OpenAI           |
| Qwen2.5-72B-Instruct        | 90.07  | 72.06  | 30.96     | 66.60  | 23.46 | 56.63  | Alibaba          |
| GPT-4o-Mini                 | 87.57  | 70.68  | 26.45     | 63.40  | 19.40 | 53.50  | OpenAI           |
| OLV-0.2                     | 80.44  | 70.61  | 27.24     | 54.26  | 19.19 | 50.35  | OneLineAI        |
| Qwen2.5-32B-Instruct        | 68.46  | 66.59  | 27.34     | 64.04  | 23.04 | 49.89  | Alibaba          |
| OLV-0.1                     | 76.65  | 67.04  | 24.62     | 54.04  | 17.02 | 47.87  | OneLineAI        |
| Llama-3.1-70B-Instruct      | 79.08  | 56.05  | 19.85     | 60.00  | 13.10 | 45.61  | Meta             |
| Qwen2.5-14B-Instruct        | 66.34  | 53.38  | 20.64     | 61.49  | 15.55 | 43.48  | Alibaba          |
| QwQ-32B-Preview             | 54.28  | 49.32  | 26.19     | 42.13  | 25.14 | 39.41  | Alibaba          |
| Llama-3.1-8B-Instruct       | 77.79  | 49.01  | 15.92     | 47.02  | 7.21  | 39.39  | Meta             |
| Qwen2.5-7B-Instruct         | 58.38  | 48.04  | 16.55     | 48.94  | 13.10 | 37.00  | Alibaba          |
| EXAONE-3.0-7.8B-Instruct    | 72.33  | 46.79  | 15.35     | 37.66  | 7.98  | 36.02  | LG AI Research   |
| Gemma-2-9B-it               | 73.84  | 44.02  | 13.83     | 34.47  | 6.37  | 34.51  | Google           |
| Solar Pro (preview) Instruct| 53.37  | 31.33  | 10.74     | 32.34  | 6.37  | 26.83  | Upstage          |
| Llama-VARCO-8B-Instruct     | 45.03  | 27.38  | 9.64      | 20.64  | 3.85  | 21.31  | NCSOFT           |
| AYA-Expanse-8B              | 44.58  | 15.53  | 5.71      | 22.55  | 2.66  | 18.21  | Cohere           |
| Qwen2.5-1.5B-Instruct       | 28.13  | 20.69  | 8.64      | 18.51  | 3.78  | 15.95  | Alibaba          |
| Llama-3.2-1B-Instruct       | 7.88   | 10.50  | 4.77      | 10.43  | 2.80  | 7.28   | Meta             |

### Adding new models
If you want your model added to the leaderboard, feel free to contact me at: ```spthsrbwls123@yonsei.ac.kr```

