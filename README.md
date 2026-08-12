# CyberBench-TR-Turkish-Cybersecurity-and-Cyber-Audit-LLM-Benchmark
An open benchmark for evaluating LLMs on Turkish Cyber Security and CyberAudit tasks, covering 782 questions across cybersecurity knowledge, audit, governance, risk, and security controls.


# Cyber Audit / Cybersecurity Audit LLM Benchmark — 2026

## Turkish Cybersecurity Audit Benchmark Analysis

This benchmark evaluates Large Language Models on **609 Turkish cybersecurity audit and Cyber Audit-oriented questions**.

All model results are consolidated into a single leaderboard. No model receives special treatment based on whether its result came from the original benchmark or a separate evaluation run.

---

# 📊 Benchmark Methodology

| Metric           |                      Value |
| ---------------- | -------------------------: |
| Dataset          | Cyber Audit / Cybersecurity Audit |
| Total Questions  |                    **609** |
| Language         |                    Turkish |
| Question Type    |            Multiple Choice |
| Primary Metric   |                   Accuracy |
| Evaluation       |           Answer-key based |
| Models Evaluated |                         12 |

Accuracy:

**Accuracy = Correct Answers / 609 × 100**

---

# 🏆 Final Cyber Audit Leaderboard

| Rank | Model        | Correct | Incorrect |   Accuracy |
| ---: | ------------ | ------: | --------: | ---------: |
| 🥇 1 | Claude       |     537 |        72 | **88.18%** |
| 🥈 2 | ChatGPT 5.5  |     501 |       108 | **82.27%** |
| 🥉 3 | Gemma 4 31B  |     494 |       115 | **81.12%** |
|    4 | Gemini Flash |     469 |       140 | **77.01%** |
|    5 | Qwen         |     463 |       146 | **76.03%** |
|    6 | Perplexity   |     438 |       171 | **71.92%** |
|    7 | Grok 4       |     434 |       175 | **71.26%** |
|    8 | DeepSeek     |     417 |       192 | **68.47%** |
|    9 | Gemma 12B    |     412 |       197 | **67.65%** |
|   10 | Trendyol     |     404 |       205 | **66.34%** |
|   11 | Mistral 32B  |     385 |       224 | **63.22%** |
|   12 | GPT-OSS-20B  |     183 |       426 | **30.05%** |

## The original model results establish Claude at 537/609, ChatGPT at 501/609, Gemma 4 31B at 494/609, Qwen at 463/609, DeepSeek at 417/609, Mistral at 385/609 and GPT-OSS at 183/609. The additional evaluation adds Gemma 12B at 412/609 and Trendyol at 404/609.

# 📈 Accuracy Comparison

```text
Claude          ██████████████████  88.18%
ChatGPT 5.5     █████████████████   82.27%
Gemma 4 31B     █████████████████   81.12%
Gemini Flash    ███████████████     77.01%
Qwen            ███████████████     76.03%
Perplexity      ██████████████      71.92%
Grok 4          ██████████████      71.26%
DeepSeek        █████████████       68.47%
Gemma 12B       █████████████       67.65%
Trendyol        █████████████       66.34%
Mistral 32B     ████████████        63.22%
GPT-OSS-20B     ██████              30.05%
🔬 Complete Model Analysis
Claude
88.18%

Claude achieved the highest Cyber Audit benchmark result with:

537 / 609 correct

This gives Claude a lead of:

5.91 percentage points

over ChatGPT 5.5.

ChatGPT 5.5
82.27%

ChatGPT achieved:

501 / 609 correct

and ranked second.

Gemma 4 31B
81.12%

Gemma 4 31B achieved:

494 / 609 correct

and ranked third overall.

It is only:

1.15 percentage points

behind ChatGPT 5.5.

The source benchmark identifies Gemma at 494/609 and 81.12%.

Gemini Flash
77.01%

Gemini Flash achieved:

469 / 609 correct

Qwen
76.03%

Qwen achieved:

463 / 609 correct

Perplexity
71.92%

Perplexity achieved:

438 / 609 correct.

Grok 4
71.26%

Grok achieved:

434 / 609 correct.

DeepSeek
68.47%

DeepSeek achieved:

417 / 609 correct.

Gemma 12B
67.65%

Gemma 12B achieved:

412 / 609 correct

and ranked ninth.

Trendyol
66.34%

Trendyol achieved:

404 / 609 correct

and ranked tenth.

Mistral 32B
63.22%

Mistral achieved:

385 / 609 correct.

GPT-OSS-20B
30.05%

GPT-OSS achieved:

183 / 609 correct.

This is substantially below the rest of the benchmark.

📊 Gemma 12B vs Trendyol — Without Special Treatment
Model	Correct	Incorrect	Accuracy	Rank
Gemma 12B	412	197	67.65%	9
Trendyol	404	205	66.34%	10
The difference is:

Gemma 12B +1.31 percentage points

or:

8 additional correct answers.

This comparison is included only as part of the complete 12-model leaderboard, without giving either model additional weighting.

⚡ Inference Performance
Where runtime performance measurements are available:

Model	Accuracy	TTFT	Generation TPS	E2E Latency
Gemma 12B	67.65%	0.242 s	8.34	5.46 s
Trendyol	66.34%	~0.29 s	~8.23	~0.91 s
Gemma 12B has slightly better TTFT and generation throughput, while Trendyol has substantially lower E2E latency.
📉 Cyber vs Cyber Audit Difficulty
One of the most interesting findings is the difference between the two benchmark categories.

Model	Cyber	Cyber Audit	Change
Claude	94.22%	88.18%	-6.04 pp
ChatGPT 5.5	92.49%	82.27%	-10.22 pp
Gemma 4 31B	89.60%	81.12%	-8.48 pp
Gemini Flash	86.71%	77.01%	-9.70 pp
Qwen	86.13%	76.03%	-10.10 pp
Perplexity	80.35%	71.92%	-8.43 pp
Grok 4	85.55%	71.26%	-14.29 pp
DeepSeek	82.08%	68.47%	-13.61 pp
Gemma 12B	79.77%	67.65%	-12.12 pp
Trendyol	85.55%	66.34%	-19.21 pp
Mistral 32B	76.88%	63.22%	-13.66 pp
GPT-OSS-20B	35.26%	30.05%	-5.21 pp
Interpretation
The Cyber Audit benchmark is generally more challenging for the evaluated models.

The largest observed decrease belongs to Trendyol:

85.55% → 66.34%

a difference of:

19.21 percentage points.

This suggests that the model's performance is considerably more sensitive to audit/governance-oriented questions than to the broader cybersecurity question set.

🧠 Key Findings
1. Claude leads both benchmark categories
Claude achieves:

Cyber: 94.22%

Cyber Audit: 88.18%

This makes it the strongest model in both individual benchmark categories.

2. Gemma 4 31B is the strongest open-weight model
Gemma 4 31B:

Cyber: 89.60%

Cyber Audit: 81.12%

It ranks third in both benchmark categories.

3. Cyber Audit questions are harder
Most models demonstrate a meaningful accuracy reduction on Cyber Audit compared with Cyber Security.

This indicates that cybersecurity audit, governance and control-oriented reasoning may represent a more difficult task for LLMs.

4. Trendyol performs substantially better on Cyber than Cyber Audit
Trendyol:

Cyber: 85.55%

Cyber Audit: 66.34%

The 19.21-point difference is one of the largest category gaps in the benchmark.

5. Gemma 12B shows a similar pattern
Gemma 12B:

Cyber: 79.77%

Cyber Audit: 67.65%

Difference:

12.12 percentage points

🚀 Enterprise AI Interpretation
For enterprise security environments, benchmark accuracy should be considered together with runtime performance.

Potential evaluation dimensions include:

Knowledge Performance
Accuracy
Error rate
Category-level accuracy
Runtime Performance
TTFT
Generation TPS
E2E latency
Efficiency
Tokens per question
Accuracy per token
Compute cost
Operational Capability
Tool usage
SIEM integration
RAG
Long-context reasoning
Agentic workflows
⚠️ Benchmark Limitations
The benchmark is a knowledge/reasoning evaluation.

It should not be interpreted as:
Cyber Audit certification
Professional audit certification
Autonomous auditing capability
Real-world SOC capability
Penetration-testing capability
Malware-analysis capability
A high benchmark score indicates strong performance on the evaluated question set, not professional certification.

📌 Final Cyber Audit Verdict
The final Cyber Audit ranking is:

Claude > ChatGPT 5.5 > Gemma 4 31B > Gemini Flash > Qwen > Perplexity > Grok 4 > DeepSeek > Gemma 12B > Trendyol > Mistral > GPT-OSS

The results demonstrate that Gemma 4 31B remains the strongest open-weight model, while Claude and ChatGPT lead overall.

The comparison between Cyber and Cyber Audit also demonstrates that model performance can vary substantially depending on the type of cybersecurity knowledge being evaluated.


# Cyber Security LLM Benchmark — 2026

## Turkish Cybersecurity Benchmark Analysis

This benchmark evaluates Large Language Models on **173 Turkish cybersecurity questions**.

All models are evaluated against the same question set and answer key. The results from all evaluation runs are consolidated into a single leaderboard.

> **Total Questions: 173**

---

## 📊 Benchmark Methodology

| Metric           | Description              |
| ---------------- | ------------------------ |
| Dataset          | Cyber Security Benchmark |
| Total Questions  | **173**                  |
| Language         | Turkish                  |
| Question Type    | Multiple Choice          |
| Primary Metric   | Accuracy                 |
| Evaluation       | Answer-key based         |
| Models Evaluated | 12                       |

Accuracy is calculated as:

**Accuracy = Correct Answers / 173 × 100**

---

# 🏆 Final Cyber Security Leaderboard

| Rank | Model        | Correct | Incorrect |   Accuracy |
| ---: | ------------ | ------: | --------: | ---------: |
| 🥇 1 | Claude       |     163 |        10 | **94.22%** |
| 🥈 2 | ChatGPT 5.5  |     160 |        13 | **92.49%** |
| 🥉 3 | Gemma 4 31B  |     155 |        18 | **89.60%** |
|    4 | Gemini Flash |     150 |        23 | **86.71%** |
|    5 | Qwen         |     149 |        24 | **86.13%** |
|    6 | Trendyol     |     148 |        25 | **85.55%** |
|    6 | Grok 4       |     148 |        25 | **85.55%** |
|    8 | DeepSeek     |     142 |        31 | **82.08%** |
|    9 | Perplexity   |     139 |        34 | **80.35%** |
|   10 | Gemma 12B    |     138 |        35 | **79.77%** |
|   11 | Mistral 32B  |     133 |        40 | **76.88%** |
|   12 | GPT-OSS-20B  |      61 |       112 | **35.26%** |

## The underlying benchmark results report Gemma 31B at 155/173, Qwen at 149/173, DeepSeek at 142/173, Mistral at 133/173 and GPT-OSS at 61/173. The additional evaluations provide the Trendyol and Gemma 12B results.

# 📈 Accuracy Comparison

```text
Claude          ███████████████████ 94.22%
ChatGPT 5.5     ██████████████████  92.49%
Gemma 4 31B     █████████████████   89.60%
Gemini Flash    █████████████████   86.71%
Qwen            █████████████████   86.13%
Trendyol        █████████████████   85.55%
Grok 4          █████████████████   85.55%
DeepSeek        ████████████████    82.08%
Perplexity      ████████████████    80.35%
Gemma 12B       ████████████████    79.77%
Mistral 32B     ███████████████     76.88%
GPT-OSS-20B     ███████             35.26%
🔬 Complete Model Analysis
Claude
Accuracy: 94.22%

Claude achieved the highest Cyber Security benchmark score with 163 correct answers out of 173.

It leads ChatGPT 5.5 by:

1.73 percentage points

and Gemma 4 31B by:

4.62 percentage points.

ChatGPT 5.5
Accuracy: 92.49%

ChatGPT achieved 160 correct answers and ranked second.

The gap to the benchmark leader is relatively small, indicating strong performance on Turkish cybersecurity questions.

Gemma 4 31B
Accuracy: 89.60%

Gemma 4 31B is the highest-ranked open-weight model in this benchmark.

It achieved:

155 / 173 correct

and ranked third overall.

Gemini Flash
Accuracy: 86.71%

Gemini Flash achieved 150 correct answers.

Qwen
Accuracy: 86.13%

Qwen achieved 149 correct answers and ranked fifth overall.

Trendyol
Accuracy: 85.55%

Trendyol achieved 148 correct answers.

It is statistically very close to Qwen:

85.55% vs 86.13%

Difference:

0.58 percentage points

The result is also identical to the reported Grok 4 accuracy of 85.55%.
Grok 4
Accuracy: 85.55%

Grok 4 achieved 148/173 correct answers.

DeepSeek
Accuracy: 82.08%

DeepSeek achieved 142 correct answers.

Perplexity
Accuracy: 80.35%

Perplexity achieved 139 correct answers.

Gemma 12B
Accuracy: 79.77%

Gemma 12B achieved 138 correct answers.

Compared with Gemma 4 31B:

Model	Accuracy
Gemma 4 31B	89.60%
Gemma 12B	79.77%
Difference	9.83 pp
This shows a substantial performance difference between the evaluated Gemma configurations.

Mistral 32B
Accuracy: 76.88%

Mistral achieved 133 correct answers.

GPT-OSS-20B
Accuracy: 35.26%

GPT-OSS achieved 61 correct answers.

It is substantially below the other evaluated models in this benchmark.

⚡ Performance Metrics
For models where inference-performance measurements are available, the following metrics are reported:

Model	Accuracy	Generation TPS	Avg Latency
Gemma	89.60%	2.30	~0 s*
Qwen	86.13%	14.0	~0 s*
Mistral 32B	76.88%	3.30	0.61 s
DeepSeek	82.08%	3.83	~0 s*
GPT-OSS-20B	35.26%	10.4	20–25 s
Gemma 12B	79.77%	8.36	5.338 s
Trendyol	85.55%	8.25	0.882 s
*The source performance summary reports approximately zero seconds for these measurements; this should be interpreted as the reported measurement rather than literal zero physical latency.

Gemma 12B and Trendyol measurements are taken from the dedicated benchmark run.
🧮 Efficiency Analysis
The benchmark also contains a token-efficiency analysis.

Model	Accuracy	Avg Tokens	Efficiency
Gemma	82.99% overall	153	🥇 Best
Qwen	78.26% overall	170	🥈
Mistral	66.24% overall	171	🥉
DeepSeek	71.48% overall	663	Poor
GPT-OSS	31.20% overall	482	Very Poor
The original performance analysis identifies Gemma as the most token-efficient among those models.

🎯 Key Findings
1. Claude is the strongest model
Claude leads the benchmark at:

94.22%

2. Gemma 4 31B is the strongest open-weight model
Gemma 4 31B reaches:

89.60%

and ranks third overall.

3. Trendyol is highly competitive
Trendyol reaches:

85.55%

placing it sixth overall.

It is only:

4.05 percentage points

behind Gemma 4 31B.

4. Gemma 12B is still competitive
Gemma 12B achieves:

79.77%

and ranks tenth.

5. Model size does not directly determine benchmark performance
The results show that parameter count alone cannot explain benchmark performance.

Models with different architectures, training approaches and reasoning strategies produce substantially different results.

🚀 Production Perspective
Accuracy alone does not determine whether a model is suitable for production cybersecurity workloads.

For example, the dedicated Gemma 12B and Trendyol measurements show:

Metric	Gemma 12B	Trendyol
Accuracy	79.77%	85.55%
TTFT	0.244 s	0.261 s
Generation TPS	8.36	8.25
E2E Latency	5.338 s	0.882 s
Gemma 12B has slightly better TTFT and generation throughput, while Trendyol has higher accuracy and dramatically lower E2E latency.
This highlights the importance of evaluating:

Accuracy + TTFT + Generation TPS + E2E Latency

rather than accuracy alone.

⚠️ Limitations
This benchmark measures performance on a fixed set of Turkish cybersecurity multiple-choice questions.

It does not directly evaluate:
Real SOC operations
SIEM investigation
Malware analysis
Reverse engineering
Exploit development
Penetration testing
Tool usage
Agentic reasoning
Long-context investigation
Autonomous incident response
Therefore, benchmark accuracy should be interpreted as benchmark performance, not as a complete measure of cybersecurity capability.

📌 Final Verdict
The Cyber Security benchmark ranking is:

Claude > ChatGPT 5.5 > Gemma 4 31B > Gemini Flash > Qwen > Trendyol/Grok > DeepSeek > Perplexity > Gemma 12B > Mistral > GPT-OSS

The most important conclusion is that the benchmark shows a clear separation between high-performing frontier models and weaker open-weight configurations, while models such as Gemma 4 31B and Trendyol demonstrate strong practical competitiveness.
