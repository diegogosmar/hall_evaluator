# Multi Agent Agentic Hallucinatoin Evaluator
![Alt text](images/multi_agents_hallucination_eval.png)

## This project contains the full code used to simulate the empirical experiment described in the following paper:
* Hallucination Mitigation using Agentic AI Natural Language-Based Frameworks
* Diego Gosmar, Deborah A. Dahl
* Abstract: Hallucinations remain a significant challenge in current Generative AI models, undermining trust in AI systems and their reliability. This study investigates how orchestrating multiple specialized Artificial Intelligent Agents can help mitigate such hallucinations, with a focus on systems leveraging Natural Language Processing (NLP) to facilitate seamless agent interactions. To achieve this, we design a pipeline that introduces over three hundred prompts, purposefully crafted to induce hallucinations, into a front-end agent. The outputs are then systematically reviewed and refined by second- and third-level agents, each employing distinct large language models and tailored strategies to detect unverified claims, incorporate explicit disclaimers, and clarify speculative content. Additionally, we introduce a set of novel Key Performance Indicators (KPIs) specifically designed to evaluate hallucination score levels. A dedicated fourth-level AI agent is employed to evaluate these KPIs, providing detailed assessments and ensuring accurate quantification of shifts in hallucination-related behaviors. A core component of this investigation is the use of the OVON (Open Voice Network) framework, which relies on universal NLP-based interfaces to transfer contextual information among agents. Through structured JSON messages, each agent communicates its assessment of the hallucination likelihood and the reasons underlying questionable content, thereby enabling the subsequent stage to refine the text without losing context. The results demonstrate that employing multiple specialized agents capable of interoperating with each other through NLP-based agentic frameworks can yield promising outcomes in hallucination mitigation, ultimately bolstering trust within the AI community.
* Comments:	18 pages, 6 figures
* Subjects:	Computation and Language (cs.CL); Artificial Intelligence (cs.AI); Multiagent Systems (cs.MA)
* Cite as:	arXiv:2501.13946 [cs.CL]
* (or arXiv:2501.13946v1 [cs.CL] for this version)
* Please note that the 310-prompts used to induce hallucinations have been hidden for safety reasons.
* Paper URL: https://doi.org/10.48550/arXiv.2501.13946
