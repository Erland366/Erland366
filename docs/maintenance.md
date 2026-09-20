# Maintaining the profile

The active GitHub profile `README.md` uses the author-approved narrative version: introduction, ML systems interests, selected research, open-source contributions, learning projects, and an invitation to the research blog. Keep each section concise; the complete publication list and experience details belong on the website.

The narrative structure is inspired by [Ayaka Mikazuki’s profile README](https://github.com/ayaka14732). It groups concrete work into short thematic stories with source links. The earlier concise version is preserved in `drafts/README-concise.md` as an alternative. That file is also visible in the public repository, but GitHub displays the root `README.md` on the profile.

Keep the current MBZUAI Research Engineer role, AMD/NVIDIA cross-vendor focus, progression from language model research to ML systems, and PhD search consistent with the sibling website repository. Its docs/content-sources.md records the evidence behind these claims. Do not infer employment dates or a PhD starting year.

Use Erland Hilman Fuadi (Edd) for the blog nickname. The blog has no published posts yet, so the invitation describes it as forthcoming. This README uses plain Markdown and has no image dependencies.

The profile and website are separate repositories. Publish the website before pushing this README so the blog link works. Local edits do not update the public GitHub profile until pushed.

## Profile sources

Reviewed on 20 September 2026. The reference profile supplies the organizational idea only; wording, accomplishments, and personal details are not copied.

- Current role, cross-vendor focus, career progression, and PhD interests come from the author’s statements in this conversation.
- COPUS, Token Order Prediction, Softpick, and COPAL-ID use the publication records already verified for the website. The profile says coauthored work and uses “we” for the paper, without assigning unconfirmed individual leadership or implementation responsibilities. COPUS is not assigned a conference venue.
- The open-source section highlights Unsloth contributions. Each linked PR was checked through the GitHub API for authorship (`Erland366`), merged status, and changed files: [unsloth#1254](https://github.com/unslothai/unsloth/pull/1254) casts logits to float32 in the Triton cross-entropy kernel; [unsloth#1276](https://github.com/unslothai/unsloth/pull/1276) adds compatibility handling for TRL trainer/config API changes; [unsloth#2381](https://github.com/unslothai/unsloth/pull/2381) passes the save method through the vision-language model saving path and adds saving tests; [unsloth-zoo#142](https://github.com/unslothai/unsloth-zoo/pull/142) disables a Triton block-pointer compiler option to address a compilation failure; and [notebooks#119](https://github.com/unslothai/notebooks/pull/119) adds Qwen3-VL vision fine-tuning and GRPO examples.
- These are contributions to collaborative projects. The compiler-fix PR explicitly credits Matthew with finding the solution, so the profile does not claim sole discovery. Do not infer maintainer status, performance gains, or shipped AMD support from these PRs. Unmerged PRs are not presented as merged work, and no contribution count is maintained.
- [triton_inline](https://github.com/Erland366/triton_inline) is described publicly as a Triton kernel learning project. Its `functions_of_inline.py` contains Triton inline-assembly exercises; its README is empty. The profile calls it a learning project and makes no correctness or speed claims.
- [learning_parallel](https://github.com/Erland366/learning_parallel) contains `step4_tensor_parallel` and `step5_data_parallel_naive`, with tensor/data parallel modules. It is described as exploration rather than an established training library.

The public repository descriptions, READMEs, and relevant directory/file contents were inspected; their code was not executed or benchmarked. Further personal stories or individual contribution details should come from the author.
