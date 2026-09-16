# Project Jailbreaking LMMs using Stealth Prompts
Published by: AnjuhBananu, DJ Oreo & irootcat

Can LLMs be jailbreaked ? Well this research has already been done by AutoDAN, and turns out back in 2024 when these LLMs were first mass scaled they could. 
However, our question as students who are building upon AutoDAN's research is does it still work in 2026 ?
The current release for AutoDAN is dated back to 2024, since then LLM have further progressed in sophisticating their algorithms to better handle user requests. So is it still possible to jailbreak these AI's through prompts given by users ? Or has the algorithm sophisticated itself enough that it's no longer possible to do so. 

Previous research done by AutoDAN can be found here: https://github.com/SheltonLiu-N/AutoDAN
The latest version of AutoDAN (AutoDAN -Turbo) can be found here: https://autodans.github.io/AutoDAN-Turbo/ 

Part of our research is to repurposing the research to build our own version of 'AutoDAN' to see if the agent can preform as efficiently as 
the older model of AutoDAN without 'Optimization' or Black Box Implementation and jailbreak
modern Open Source and closed model LLMs through prompts. 

Phase 1: Building the AI Agent, and retest similar models AutoDAN had previously tested.
Phase 2: Test on Open Source Models if Phase 1 is sucessful
Phase 3: Test on Closed Models if Phase 2 is sucessful

These are the models we will be testing; 

	1. Models Paper had orginally tested:
	-> Llama 2 7b chat (Meta 2023)
	-> gpt 3.5 Turbo 0301 (Open AI 2023)
	-> gpt 4 0613 (Open AI 2023) 		

	Updated Models we will test:

		-> Llama 3 8B Instruct (Meta 2024)
		-> gpt oss 20b (OpenAI 2025)
		-> gemma 4 12B IT (Gemini 2026) 

	2. Closed Models: 
		-> Claude Opus 5  (Claude 2026)
		-> Gpt Terra 5.6  (Chat-GPT 2026)
		-> UM- GPT Sol 5.6 (UM-GPT's Agent 2026)
 

