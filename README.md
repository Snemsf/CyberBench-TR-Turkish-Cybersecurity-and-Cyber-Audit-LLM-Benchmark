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


# 🛡️ Turkish Cyber Security LLM Benchmark (2026)

**Comprehensive Evaluation of Large Language Models on Turkish Cybersecurity Domain Knowledge**


## 📌 Executive Summary

This repository contains the dataset, methodology, and evaluation logs for the **2026 Turkish Cyber Security LLM Benchmark**. The benchmark evaluates **12 leading AI models** against **173 multiple-choice Turkish cybersecurity questions** covering network defense, incident response, vulnerability assessment, and threat detection logic.

> [!NOTE]
> All models were benchmarked against identical prompts and standardized answer keys to derive exact accuracy, token consumption, and inference latency metrics.

---

## 📊 Benchmark Methodology

| Parameter | Details |
| :--- | :--- |
| **Dataset** | Turkish Cyber Security Assessment Set |
| **Total Questions** | **173** |
| **Format** | Multiple Choice (Single Correct Choice) |
| **Primary Metric** | Accuracy ($\text{Accuracy} = \frac{\text{Correct}}{173} \times 100$) |
| **Language** | Turkish (TR) |
| **Evaluated Models** | 12 (Proprietary & Open-Weights) |

---

## 🏆 Final Cyber Security Leaderboard

| Rank | Model | Correct | Incorrect | Accuracy | Type | Status |
| :---: | :--- | :---: | :---: | :---: | :---: | :---: |
| 🥇 **1** | **Claude** | **163** | 10 | **94.22%** | Proprietary | 🟢 Top Performer |
| 🥈 **2** | **ChatGPT 5.5** | **160** | 13 | **92.49%** | Proprietary | 🟢 Frontier |
| 🥉 **3** | **Gemma 4 31B** | **155** | 18 | **89.60%** | Open-Weights | 🟣 Best Open Model |
| **4** | **Gemini Flash** | **150** | 23 | **86.71%** | Proprietary | 🟢 Commercial API |
| **5** | **Qwen** | **149** | 24 | **86.13%** | Open-Weights | 🟣 Open Model |
| **6** | **Trendyol** | **148** | 25 | **85.55%** | Fine-Tuned / Local | 🔵 Regional Leader |
| **6** | **Grok 4** | **148** | 25 | **85.55%** | Proprietary | 🟢 Commercial API |
| **8** | **DeepSeek** | **142** | 31 | **82.08%** | Open-Weights | 🟣 Open Model |
| **9** | **Perplexity** | **139** | 34 | **80.35%** | Search-Augmented | 🟡 Hybrid |
| **10** | **Gemma 12B** | **138** | 35 | **79.77%** | Open-Weights | 🟣 Lightweight |
| **11** | **Mistral 32B** | **133** | 40 | **76.88%** | Open-Weights | 🟣 Open Model |
| **12** | **GPT-OSS-20B** | **61** | 112 | **35.26%** | Open-Source | 🔴 Baseline |

---

## 📈 Accuracy Distribution

```text
Claude          ████████████████████ 94.22%
ChatGPT 5.5     ███████████████████  92.49%
Gemma 4 31B     ██████████████████   89.60%
Gemini Flash    █████████████████    86.71%
Qwen            █████████████████    86.13%
Trendyol        █████████████████    85.55%
Grok 4          █████████████████    85.55%
DeepSeek        ████████████████     82.08%
Perplexity      ████████████████     80.35%
Gemma 12B       ███████████████      79.77%
Mistral 32B     ██████████████       76.88%
GPT-OSS-20B     ███████              35.26%
⚡ Performance & Inference Metrics
For deployment considerations, raw hardware/API performance metrics were recorded during the evaluation run:

Model	Accuracy	Generation TPS	Avg Latency	E2E Latency	TTFT
Gemma 4 31B	89.60%	2.30	~0.0 s*	—	—
Qwen	86.13%	14.00	~0.0 s*	—	—
Trendyol	85.55%	8.25	0.88 s	0.882 s	0.261 s
DeepSeek	82.08%	3.83	~0.0 s*	—	—
Gemma 12B	79.77%	8.36	5.34 s	5.338 s	0.244 s
Mistral 32B	76.88%	3.30	0.61 s	—	—
GPT-OSS-20B	35.26%	10.40	20–25 s	—	—
[!TIP]
Production Insight: While Gemma 12B shows slightly faster Time-To-First-Token (TTFT: 0.244s), Trendyol delivers significantly lower End-to-End latency (0.882s) alongside superior domain accuracy (85.55%).

🧮 Token Efficiency Analysis
Rank	Model	Score	Avg Tokens / Ans	Efficiency Verdict
🥇	Gemma	82.99%	153	🏆 Optimal (Concise & Accurate)
🥈	Qwen	78.26%	170	🥈 High Efficiency
🥉	Mistral	66.24%	171	🥉 Moderate
4	DeepSeek	71.48%	663	⚠️ Verbose
5	GPT-OSS	31.20%	482	❌ Inefficient
🎯 Key Findings
Frontier Dominance: Claude (94.22%) and ChatGPT 5.5 (92.49%) lead overall accuracy in complex Turkish domain prompts.
Open-Weight Benchmark: Gemma 4 31B (89.60%) secures 3rd place, outperforming several larger commercial APIs.
High-Speed Local Deployment: Trendyol (85.55%) demonstrates competitive accuracy while offering the lowest E2E latency (0.882s), making it highly suitable for real-time applications.
Parameter Scaling Impact: A comparison between Gemma variants highlights a 9.83 percentage point gap (89.60% vs 79.77%), proving that model scaling remains critical for niche domain reasoning.
⚠️ Limitations & Scope
[!WARNING]
This benchmark measures knowledge retrieval on static multiple-choice questions. It does not evaluate active operational workflows such as:

🛡️ Dynamic Incident Triage & SIEM Query Optimization
🔍 Malware Static & Dynamic Reverse Engineering
🔓 Exploit Payload Engineering & Vulnerability Exploitation
🤖 Autonomous Multi-Agent Security Operations
📂 Repository Structure
