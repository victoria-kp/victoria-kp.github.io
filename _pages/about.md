---
permalink: /
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---


---
# Biography

I am Victoria Knapp Perez, a Ph.D. candidate in Physics at the University of California, Irvine (UCI), specializing in machine learning for scientific discovery and AI-driven model design. My work bridges reinforcement learning, deep learning, and computational physics, focusing on how intelligent systems can autonomously construct and validate scientific models.  

Before joining UCI, I earned my B.Sc. in Physics from the National Autonomous University of Mexico (UNAM), graduating cum laude. My academic foundation in theoretical physics and my professional experience in AI research position me at the intersection of automated reasoning, symbolic-numerical modeling, and scientific machine learning.

---

# Physics Research Overview

One of my main research areas is astroparticle physics. For example, I have studied how [non-equilibrated scalars](https://arxiv.org/abs/2507.21523) affect the thermal history of the early Universe and explored non-standard cosmological epochs such as [stasis](https://arxiv.org/abs/2502.20449). I also work on flavor and dark-matter model building, both in top-down frameworks—including constructions from [magnetized tori](https://arxiv.org/abs/2102.11286) and [string-inspired settings](https://arxiv.org/abs/2304.14437)—and in bottom-up approaches, such as [flavor models](https://arxiv.org/abs/2108.02240) and [dark-matter phenomenology](https://arxiv.org/abs/2409.02178). In addition, I have investigated the [QCD phase diagram](https://arxiv.org/abs/2003.04505) and the behavior of matter near the critical end point.



# AI Research Overview

My AI research focuses on developing AI frameworks that can automate reasoning and model discovery in complex physical systems. I co-developed the Autonomous Model Builder [(AMBer)](https://arxiv.org/pdf/2506.08080), a reinforcement learning framework that autonomously constructs and evaluates theoretical particle physics models. AMBer integrates OpenAI Gym–style environments, Stable-Baselines PPO agents, and high-performance computing (HPC) to explore symmetry groups, optimize model parameters, and improve predictive accuracy with minimal human intervention. This represents one of the first AI-assisted approaches to symbolic scientific model generation.

I also built [AI-QuantumMechanic](https://github.com/victoria-kp/AI_QuantumMechanic), a prototype LLM agent that solves graduate-level quantum mechanics problems through tool orchestration rather than memorization. The system is a three-node LangGraph state machine—reasoning, tool execution, and validation—powered by Claude Sonnet. Over 20 symbolic (SymPy) and numerical (SciPy) tools handle algebra, calculus, ODE solving, and special-function evaluation, while every computed result is stored behind opaque registry keys that the LLM cannot forge, ensuring a verifiable chain of provenance for each derivation step. Three independent checkers—expression sourcing, normalization, and physical sanity—validate the final answer before acceptance. The agent successfully solves canonical problems including the infinite and finite square wells and the quantum harmonic oscillator, using fully analytical, numerical, or hybrid strategies as needed.


Beyond physics, I am broadly interested in how learning algorithms can replicate and extend human scientific reasoning. I have experience in fine-tuning large language models (LLMs), developing deep learning pipelines (PyTorch, FastAI, Hugging Face), and optimizing distributed training workflows on HPC systems.

---

# Software Development

I am one of the creators and maintainers of [**FlavorBuilder**](https://pypi.org/project/FlavorBuilder/), a Python toolkit for symbolic model construction and data-driven analysis in particle physics. Built for extensibility and performance, FlavorBuilder provides APIs for generating mass matrices, computing observables, and fitting theoretical models to experimental data. The package is available open-source on [GitHub](https://github.com/victoria-kp/FlavorBuilder) and [PyPI](https://pypi.org/project/FlavorBuilder/). Part of this software is partly the translation of [Discrete](https://discrete.hepforge.org/). Detailed documentation and citation guidelines are provided in the [GitHub](https://github.com/victoria-kp/FlavorBuilder) repository.

----

Feel free to reach out to [1victoriakp@gmail.com](mailto:1victoriakp@gmail.com).


