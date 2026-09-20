# Hi, I’m Erland Hilman Fuadi

I’m a **Research Engineer at MBZUAI**, working on **ML systems**. My main focus is **cross-vendor mismatches between AMD and NVIDIA GPU platforms**.

I started with language model architectures and training objectives, keeping their systems implications in mind. Over time, I found myself more drawn to how we organize computation, use memory, and make training more efficient. That interest now guides my research, and I’m **looking for PhD opportunities in ML systems**.

## ML systems and efficient training

I’m interested in the interaction between training algorithms and the systems that run them: how we distribute work across devices, use available compute, and understand differences between GPU platforms.

My coauthored work includes [COPUS](https://arxiv.org/abs/2604.26687), which studies adapting batch size and parallelism together during language model training. It connects to a question I want to keep exploring: how can model training make better use of the hardware available to it?

## Language model architectures and training objectives

My language model research includes [Token Order Prediction](https://icml.cc/virtual/2026/poster/60781), published at **ICML 2026**. In this work, we use the relative order of upcoming tokens as an auxiliary training objective. I also coauthored [Softpick](https://aclanthology.org/2026.findings-acl.905/), published in **Findings of ACL 2026**, which revisits attention normalization to address attention sinks and massive activations.

These projects form the language modeling background I bring to ML systems research. I’m interested in how choices in architectures and training objectives interact with their implementations.

## Open-source contributions

I contribute to **[Unsloth](https://github.com/unslothai/unsloth)**, with merged work across its core library, Unsloth Zoo, and training notebooks. My contributions address the practical details behind model training: kernel data types, compiler settings, library compatibility, and saving trained models.

In the core library, I’ve contributed fixes for [data-type mismatches in Triton cross-entropy kernels](https://github.com/unslothai/unsloth/pull/1254), [compatibility with changes to TRL’s trainer API](https://github.com/unslothai/unsloth/pull/1276), and [saving vision-language models in 4-bit](https://github.com/unslothai/unsloth/pull/2381). In Unsloth Zoo, I also contributed a [compiler configuration fix](https://github.com/unslothai/unsloth-zoo/pull/142) for a vision-language model compilation failure.

I also contribute training examples, including [Qwen3-VL fine-tuning and GRPO notebooks](https://github.com/unslothai/notebooks/pull/119). This work connects my language modeling background with the implementation and systems questions I want to explore more deeply.

## Learning through code

I also keep hands-on learning projects: [triton_inline](https://github.com/Erland366/triton_inline) for GPU kernel programming with Triton, and [learning_parallel](https://github.com/Erland366/learning_parallel) for exploring tensor and data parallelism. They’re places to work through the implementation details behind model training as I deepen my systems knowledge.

## Indonesian language research

I coauthored [COPAL-ID](https://aclanthology.org/2024.naacl-long.77/), a **NAACL 2024** benchmark for commonsense reasoning grounded in Indonesian culture and language. It evaluates both standard and colloquial Indonesian, with attention to local knowledge and cultural context.

## Notes & writing

I’m starting a **[research blog](https://erland366.github.io/blog/)** as **Erland Hilman Fuadi (Edd)**, where I’ll share notes on ML systems, efficient training, and what I learn along the way. First posts coming soon.

You can find my publications and background on **[my website](https://erland366.github.io/)**, or **[get in touch](mailto:erland.hilman366@gmail.com)** about research and PhD opportunities.
