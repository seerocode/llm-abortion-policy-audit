# Abortion Policy LLM Audit (Response Data)

This repository contains LLM response data collected for [Auditing LLM Responses in a Complex Policy Landscape: Abortion
Law in the United States](https://doi.org/10.1145/3805689.3806451). For any questions, please contact the first author at rone [at] seas [dot] upenn [dot] edu.


## Data

`abortion-policy-llm-audit-responses.csv`

| Column | Description |
|---|---|
| `uid` | Unique identifier for the question |
| `type` | Question category (Gestational Age, Medication Abortion, Interstate Travel, or Assault) |
| `state` | U.S. state the question pertains to |
| `question` | The prompt as administered to the model |
| `response_uid` | Unique identifier for the response |
| `model` | LLM evaluated (e.g. ChatGPT, Sonar, Gemini) |
| `run_1` | Model response on first run |
| `run_2` | Model response on second run |
| `run_3` | Model response on third run |

## Citation

If you use this data, please cite:

Ro Encarnación, Christen Hammock Jones, and Danaé Metaxa. 2026. Auditing LLM Responses in a Complex Policy Landscape: Abortion
Law in the United States. To Appear In *Proceedings of the 2026 ACM Conference on Fairness, Accountability, 
and Transparency (FAccT '26), June 25–28, 2026, Montreal, QC, Canada*. ACM, New York, NY, USA. 
https://doi.org/10.1145/3805689.3806451
