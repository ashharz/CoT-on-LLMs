# Reasonability-of-LLMs-An-Experiment-with-PaLM-text-bison-001 and Llama 2
 

 ## A Short Description of Our Work:
 Hi! Welcome and thank you for your interest in exploring our work( detailed report is available [here](https://github.com/jvdutt/NLP_project/blob/main/Understanding%20Resaoning%20Ability%20of%20PaLM%2CLLAMA%20Through%20CoT%20Prompts.pdf) )on understanding LLMs( PaLM text bison 001,Llama 2) reasoning ability through various types of CoT prompts( and detailed comparison of standard prompt vs CoT prompt).

 ## Obtained Results in PaLM:
 <img src="AQUA.png" style="width:1376px;height:774px"/>
 <img src="GSM8K.png" style="width:1376px;height:774px"/>
 <img src="SVAMP_COTVSSTAN.png" style="width:1376px;height:774px"/>
 <img src="SVAMP_3COMP.png" style="width:1376px;height:774px"/>
 <img src="SVAMP_4COMP.png" style="width:1376px;height:774px"/>

 ## Obtained Result in Llama-2-7B-chat-GPTQ:
 <img src="llama_AQuA_cot_std.png" style="width:1376px;height:774px"/>
 <img src="llama_gsm8k_cot_std.png" style="width:1376px;height:774px"/>
 
## Obtained Result in Llama-2-13B-chat-GPTQ:
---------------------------
Comparing New vs Old Promptings with Llama2-13B for 3-ShotCot, the numbers given in the graph are
the total number of correct answers outof 254 from AQuA Dataset.
<img src="Llama2Results_13Bv7B/graphs/13BNewPrompts.png" style="width:1376px;height:774px"/>
---------------------------
Comparing Llama2 13B,7B in Cot prompting, the numbers given in the graph are the total number of
correct answers outof 254 from AQua Dataset and Note that 0-ShotCot means just adding ”Let’s think step by
step.” at the end of the standard prompt.
<img src="Llama2Results_13Bv7B/graphs/13Bvs7B_Llama2.png" style="width:1376px;height:774px"/>
---------------------------
Llama2-13B with New Prompts,the numbers given in the graph are the total number of correct answers
outof 254 from AQuA Dataset,Difference between 0-ShotStd,0-ShotCot is that whole prompt is suffixed by ”Lets
think step by step.” for 0-ShotCot.
<img src="Llama2Results_13Bv7B/graphs/NewVsOldPrompt_3ShotCot.png" style="width:1376px;height:774px"/>
