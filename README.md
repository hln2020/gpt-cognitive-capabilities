# gpt-cognitive-capabilities

Introduction

Unleashing the power of OpenAI’s GPT, we embark on an ex-
ploration of the remarkable cognitive capabilities that reside

within its vast neural network. Our work is built upon existing

work from ”Using cognitive psychology to understand GPT-
3” (Binz & Schulz, 2023), which examined the cognitive ca-
pabilities of GPT-3 using various canonical experiments. Two

investigations were conducted: vignette-based experiments,

which involved providing participants with a short and pre-
determined description of hypothetical scenarios, and task-
based experiments, which generated scenarios programmati-
cally on a trial-by-trial basis. During each investigation, the

cognitive ability of GPT-3 was assessed in four well-known
domains: decision-making, information search, deliberation,
and causal reasoning. GPT-3 achieved a 50% accuracy for

the vignette-based experiments and showed near human per-
formance for task-based experiments, and even showed sig-
natures of model-based reinforcement learning. The authors

argued that studying the cognitive processes underlying GPT-
3 can help us better understand the limitations and strengths

of the model, as well as inform the development of future lan-
guage models. The paper concluded by recommending that

researchers ”should not only scale up algorithms that are pas-
sively fed with data but instead let agents directly interact and

engage with the world” (Binz & Schulz, 2023).
Are newer large language models better engaged with the
world? With the advent of ChatGPT, GPT-4 and the concept
of prompt engineering, we are interested in learning whether
these models exhibit improvements in cognitive abilities.

We replicated the vignette-based and task-based experi-
ments described in (Binz & Schulz, 2023) on GPT-3. For

vignette-based experiments, we also extended them to assess

the performance of GPT-3.5 and GPT-4, and came up with
our own adversarial vignettes. While replication results are
presented in Appendix I, in the discussion below, we focus
on comparing GPT-3.5 and GPT-4 with GPT-3’s performance

in the original paper, and leave the validation of GPT-3’s re-
sults to future work. For task-based investigations, while we

wished to extend the experiments to GPT-3.5 and GPT-4, we
ran into technical difficulties with GPT-3.5’s API and were
not able to access GPT-4’s API due to its limited availability.

For both sets of experiments, prompt engineering is imple-
mented.
