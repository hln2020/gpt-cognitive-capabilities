# gpt-cognitive-capabilities

Unleashing the power of OpenAI's GPT, we embark on an exploration of the remarkable cognitive capabilities that reside within its vast neural network. Our work is built upon existing work from ["Using cognitive psychology to understand GPT-3" (Binz & Schulz, 2023)](https://arxiv.org/pdf/2206.14576.pdf), which examined the cognitive capabilities of GPT-3 using various canonical experiments. Two investigations were conducted: vignette-based experiments, which involved providing participants with a short and predetermined description of hypothetical scenarios, and task-based experiments, which generated scenarios programmatically on a trial-by-trial basis. During each investigation, the cognitive ability of GPT-3 was assessed in four well-known domains: decision-making, information search, deliberation, and causal reasoning. GPT-3 achieved a 50% accuracy for the vignette-based experiments and showed near human performance for task-based experiments, and even showed signatures of model-based reinforcement learning.  The authors argued that studying the cognitive processes underlying GPT-3 can help us better understand the limitations and strengths of the model, as well as inform the development of future language models. The paper concluded by recommending that researchers "should not only scale up algorithms that are passively fed with data but instead let agents directly interact and engage with the world". 

Are newer large language models better engaged with the world? With the advent of ChatGPT, GPT-4 and the concept of prompt engineering, we are interested in learning whether these models exhibit improvements in cognitive abilities. 

We replicated the vignette-based and task-based experiments described in (Binz & Schulz, 2023) on GPT-3. For vignette-based experiments, we also extended them to assess the performance of GPT-3.5 and GPT-4, and came up with our own adversarial vignettes. While replication results are presented in Appendix I, in the discussion below, we focus on comparing GPT-3.5 and GPT-4 with GPT-3's performance in the original paper, and leave the validation of GPT-3's results to future work. For task-based investigations, while we wished to extend the experiments to GPT-3.5 and GPT-4, we ran into technical difficulties with GPT-3.5's API and were not able to access GPT-4's API due to its limited availability. For both sets of experiments, prompt engineering is implemented.

