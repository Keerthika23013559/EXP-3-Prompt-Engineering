# EXP-3-PROMPT-ENGINEERING-
## NAME:KEERTHIKA M P
## REG NO:212223240071

## Aim: 
Evaluation of 2024 Prompting Tools Across Diverse AI Platforms: 
ChatGPT, Claude, Bard, Cohere Command, and Meta
Experiment:
Within a specific use case (e.g., summarizing text, answering technical questions), compare the performance, user experience, and response quality of prompting tools across these different AI platforms.

## Algorithm:

1.Define scope & dataset o Choose use cases (e.g., summarization, technical Q&A). o Prepare a prompt set (N prompts per use case). Ensure variety, difficulty levels, and ground-truth where applicable.

2.Define evaluation rubric o Metrics: Accuracy (factual), Relevance, Clarity, Completeness/Depth, Conciseness, Safety/No-hallucination. o Scoring scale: e.g., 1–5 for each metric.

3.Generate outputs o For each platform P and each prompt i, send prompt and collect response R_{P,i}. o Record metadata: timestamp, model version, prompt template, parameters (temperature, max tokens).

4.Human & automated evaluation o Prepare blind evaluation sheets (remove platform labels). o Have k human raters score each (or use automated checks for things like length, grammar, factual overlap). o Compute inter-rater reliability (Cronbach’s alpha or Fleiss’ kappa).

5.Aggregate scores o For each (P, prompt), compute mean metric scores across raters. o For each platform P, compute overall mean scores (per metric and weighted composite).

6.Statistical testing o Test for significance across platforms: repeated-measures ANOVA or Friedman test (non-parametric) depending on data distribution. o If significant, perform pairwise comparisons (paired t-test with Bonferroni or Wilcoxon signed-rank).

7.Qualitative analysis o Collect representative good / bad outputs per platform. o Note systematic behaviours (verbosity, hallucination patterns, formatting).

8.Reporting o Produce tables, radar charts, and per-use-case breakdowns. o Provide recommendations and limitations.

<img width="792" height="541" alt="image" src="https://github.com/user-attachments/assets/4b207336-3f18-4d56-aae5-5786c0f0c9f7" />

## Prompt
Evaluate ChatGPT, Claude, Bard, Cohere Command, and Meta AI on the same tasks (e.g., summarization, technical Q&A). For each platform, follow Prompt → Output → Result and compare accuracy, clarity, depth, and user experience.”

<img width="804" height="401" alt="image" src="https://github.com/user-attachments/assets/20231055-72fe-49d2-b65f-3ee5fb387305" />


## Output

## Case 1: Summarizing Text Prompt: “Summarize the following text into three sentences: Artificial intelligence is rapidly evolving and is transforming industries such as healthcare, education, and finance. However, ethical challenges related to privacy, fairness, and accountability remain critical. Governments, researchers, and companies are working together to ensure responsible deployment of AI.”

ChatGPT Output: Artificial intelligence is revolutionizing multiple industries, including healthcare, education, and finance. Ethical challenges such as privacy, fairness, and accountability remain significant concerns. Collaborative efforts among governments, researchers, and companies aim to ensure responsible AI use. Result: • Accuracy: ✅ • Clarity: ✅ • Conciseness: ✅ • Overall Quality: Excellent

Claude Output: AI is transforming sectors like healthcare, finance, and education at a rapid pace. This growth raises ethical concerns, particularly around fairness, privacy, and accountability. Stakeholders from government and industry are actively collaborating to address these challenges. Result: • Accuracy: ✅ • Clarity: ✅ • Style: Slightly more formal • Overall Quality: Very Good

Bard Output: Artificial intelligence is changing industries but comes with challenges like fairness and privacy. Governments and companies are working on solutions. The goal is to ensure AI benefits society responsibly. Result: • Accuracy: ✅ • Clarity: ✅ • Too simplified (less detail) • Overall Quality: Moderate

Cohere Command Output: AI is expanding across finance, education, and healthcare. Ethical issues—accountability, fairness, and privacy—are slowing adoption. Efforts from companies and governments seek to ensure trust in AI. Result: • Accuracy: ✅ • Clarity: Good • Tone: Slightly technical • Overall Quality: Good

Meta Output: Artificial intelligence impacts finance, healthcare, and education. Yet, challenges like accountability and privacy exist. Governments and researchers want to ensure safe AI deployment. Result: • Accuracy: ✅ • Slightly fragmented phrasing • Overall Quality: Average

## Case 2:Answering Technical Question Prompt: “What is the role of power electronics in Vehicle-to-Grid (V2G) systems?”

ChatGPT Output: Power electronics enable bidirectional energy conversion between EV batteries and the power grid in V2G systems. They manage charging (grid-to-vehicle) and discharging (vehicle-to-grid) efficiently. Additionally, they ensure voltage regulation, power factor correction, and system protection for grid stability. Result: Excellent – detailed, accurate, clear.

Claude Output: In V2G, power electronics control energy flow between the grid and EV batteries. They allow both charging and discharging, while also handling conversion, safety, and efficiency. Without them, reliable integration of EVs into the grid would not be possible. Result: Very Good – concise but accurate.

Bard Output: Power electronics help V2G systems by allowing cars to charge and discharge. They make sure energy is safe and efficient. This helps balance the grid. Result: Fair – correct but oversimplified.

Cohere Command Output: Power electronics are the backbone of V2G technology, providing bidirectional conversion between DC (battery) and AC (grid). They handle switching, protection, and optimization to ensure that EVs can serve as grid resources. Result: Good – technically sound, slight jargon.

Meta Output: V2G systems use power electronics to move electricity between cars and the grid. They handle charging, discharging, and conversion. Result: Average – correct but minimal depth.

Comparative Analysis Platform Accuracy Clarity Depth UX Overall Rank ChatGPT Excellent Excellent High Smooth ⭐ #1 Claude Very Good Excellent Medium-High Clean ⭐ #2 Bard Moderate Good Low Friendly ⭐ #3 Cohere Good Good Medium Technical ⭐ #4 Meta Average Fair Low Basic 

## 3.Case 1: Summarizing Text Prompt 2 – Renewable Energy Instruction: “Summarize the following passage into a short paragraph: Renewable energy sources, such as solar, wind, and hydropower, are increasingly adopted to reduce dependence on fossil fuels. These energy systems are environmentally friendly, sustainable, and help in reducing carbon emissions. However, challenges remain in terms of energy storage, grid integration, and cost competitiveness.”

## Outputs from Each Platform 

• ChatGPT: Renewable energy sources like solar, wind, and hydropower are being widely adopted to reduce reliance on fossil fuels. They are sustainable and eco-friendly, helping lower carbon emissions, but still face hurdles such as storage, integration, and cost.

• Claude: Solar, wind, and hydropower are expanding as clean energy alternatives that cut carbon emissions and reliance on fossil fuels. Despite their sustainability, challenges with storage, grid connection, and affordability remain. 

• Bard (Gemini): Renewable energy such as solar, wind, and hydropower reduces fossil fuel use and emissions. It is sustainable but still struggles with storage, integration, and cost. 

• Cohere Command: Renewable energy, including solar, wind, and hydropower, offers sustainable and low-carbon alternatives to fossil fuels. However, its growth is constrained by energy storage limitations, integration challenges, and cost barriers. 

• Meta AI: Solar, wind, and hydropower help reduce fossil fuel dependence and emissions. But issues of storage, grid use, and cost remain obstacles.

Results and Analysis Platform Accuracy Clarity Conciseness Depth Overall Score (1–5) ChatGPT 5 5 4.5 5 ⭐ 5 Claude 4.5 5 4.5 4.5 ⭐ 4.6 Bard (Gemini) 4.5 4.5 5 4 ⭐ 4.5 Cohere Command 5 4.5 4.5 4.5 ⭐ 4.6 Meta AI 4 4 5 3.5 ⭐ 4.1

## Observations
• ChatGPT gave the most complete and balanced short paragraph, strong in both accuracy and depth. 

• Claude produced a polished summary with professional clarity but slightly less depth.

• Bard gave the most concise version, ideal for beginners, but missed some nuance.

• Cohere Command delivered a structured and enterprise-style summary, accurate but formal. 

• Meta AI was simple and correct, but lacked detail and depth compared to others.

<img width="225" height="225" alt="image" src="https://github.com/user-attachments/assets/ff04f357-d8df-4fed-9b98-cba62c54f6e9" />

## Result

1.Performance Ranking

2.ChatGPT (OpenAI) – ⭐ Excellent across all metrics; best balance of depth, clarity, and accuracy.

3.Claude (Anthropic) – Very strong competitor; excels in clarity and safety, slightly less depth than ChatGPT.

4.Cohere Command – Technically solid, enterprise-oriented; good accuracy but more formal/less natural.

5.Bard / Gemini (Google) – Simplifies responses too much; good for beginners, less detailed for experts.

5.Meta (LLaMA-based tools) – Functional but limited; average clarity and low depth compared to others.

2.Metric-wise Comparison

<img width="309" height="193" alt="image" src="https://github.com/user-attachments/assets/4a64b048-7da8-4a9c-ae34-d78d903d34c2" />

## Accuracy 

• ChatGPT consistently produced highly accurate responses in both summarization and technical Q&A. 

• Claude performed almost equally well, especially in factual correctness, but sometimes leaned toward cautious phrasing. 

• Cohere Command delivered accurate results but occasionally missed nuance in longer prompts. 

• Bard/Gemini simplified technical details, making answers easier to understand but less precise. 

• Meta showed average accuracy, with some oversimplification and lack of fine technical detail.

## Clarity 

• Claude scored highest in clarity, delivering well-structured, easy-to-read responses. 

• ChatGPT was equally clear but sometimes provided denser information, which is excellent for experts but may overwhelm beginners.

• Cohere Command maintained professional tone and clarity but felt less conversational. 

• Bard/Gemini simplified too much, which improved readability but reduced completeness. 

• Meta was clear but lacked contextual richness, making responses feel abrupt.

## Depth 

• ChatGPT and Claude stood out, offering in-depth insights, examples, and context when needed. 

• Cohere Command provided solid depth for enterprise tasks but less flexibility in creative or exploratory questions.

• Bard/Gemini performed well for surface-level answers but struggled with complex technical depth.

• Meta showed limited depth, often sticking to basic explanations without elaboration.
## Conciseness

• Bard/Gemini excelled here—short, quick, and beginner-friendly responses. 

• ChatGPT and Claude balanced conciseness with richness, though sometimes leaned toward longer outputs. 

• Cohere Command was precise but formal, less conversational. 

• Meta produced concise answers, but sometimes too brief, missing key context.

## User Experience 

• ChatGPT offered the most interactive, engaging, and adaptable experience across use cases. 

• Claude was conversational, empathetic, and particularly strong at safety and tone. 

• Cohere Command felt polished but enterprise-driven rather than casual.

• Bard/Gemini had the smoothest integration with Google services (strength in practical use), but less flexible in knowledge depth. 

• Meta was lightweight and fast but felt minimal compared to competitors.

## Strengths & Weaknesses Summary 

• ChatGPT → Best for balanced technical + general tasks, ideal for students, professionals, and researchers. 

• Claude → Best for clarity, ethical phrasing, and user trust. 

• Cohere Command → Best for enterprise-focused tasks and structured responses. 

• Bard/Gemini → Best for beginners and quick answers, but weaker for technical/academic depth. 

• Meta → Best for lightweight, basic responses, but needs improvement in depth and polish.

<img width="226" height="161" alt="image" src="https://github.com/user-attachments/assets/ad4ac479-47cb-4fff-b760-aefca1f68f8f" />
