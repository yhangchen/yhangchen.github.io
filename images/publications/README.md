# Publication method diagrams
Created with the built-in ImageGen tool after reviewing the papers. Simplified explanatory diagrams, not measured results. Click a site figure to open it at full resolution.

## recast
- File: [recast-diagram.jpg](recast-diagram.jpg)
- Source: https://arxiv.org/abs/2609.13425
- Explanation: Reward-specific weights vary across denoising steps while preserving reward budgets.

Use case: scientific-educational. Generate a clear labeled method diagram for a research website publication thumbnail, landscape 3:2 composition. Flat clean scientific figure on warm ivory, dark teal text and lines, sage boxes, occasional ochre highlight. Large readable labels, no landscape scenery, no decorative metaphor, no 3D, no grain, no tiny text, no fabricated performance numbers. Use only the exact short labels requested. Concrete simplified explanation of the paper, schematic not experimental data. Every arrow and label must be precise. Title 'ReCAST'. Upper section: a horizontal 4-stage denoising chain with small tiles labeled 'Noise', 'Layout', 'Structure', 'Detail'. Lower section: a 3-row by 4-column matrix labeled 'Reward weights', with row labels 'Alignment', 'Correctness', 'Aesthetics'; shade Alignment strongly at Layout, Correctness at Structure, Aesthetics at Detail. Caption 'Fixed reward budgets · Equal step totals'. Matrix is illustrative, not numerical results. Connect columns to denoising stages.

## iris
- File: [iris-diagram.jpg](iris-diagram.jpg)
- Source: https://arxiv.org/abs/2509.25562
- Explanation: Negative self-certainty supplies the intrinsic reward for image-generation RL.

Use case: scientific-educational. Generate a clear labeled method diagram for a research website publication thumbnail, landscape 3:2 composition. Flat clean scientific figure on warm ivory, dark teal text and lines, sage boxes, occasional ochre highlight. Large readable labels, no landscape scenery, no decorative metaphor, no 3D, no grain, no tiny text, no fabricated performance numbers. Use only the exact short labels requested. Concrete simplified explanation of the paper, schematic not experimental data. Every arrow and label must be precise. Title 'IRIS'. Four boxes in order: 'Prompt' → 'Text reasoning' → 'Image tokens' → 'Generated image'. Beneath 'Image tokens', a box 'Negative self-certainty' with arrow down from Image tokens. An arrow from Negative self-certainty to a box 'RL update', looping back to Text reasoning and Image tokens. Footer 'Intrinsic reward · No external judge'. Show a small token probability bar icon in reward box. Central message: lower self-certainty provides the intrinsic reward.

## diffcap
- File: [diffcap-diagram-v2.jpg](diffcap-diagram-v2.jpg)
- Source: https://arxiv.org/abs/2506.03933
- Explanation: Add noise until embeddings stabilize, then denoise before VLM inference.

Use case: scientific-educational. Generate a clear labeled method diagram for a research website publication thumbnail, landscape 3:2 composition. Flat clean scientific figure on warm ivory, dark teal text and lines, sage boxes, occasional ochre highlight. Large readable labels, no landscape scenery, no decorative metaphor, no 3D, no grain, no tiny text, no fabricated performance numbers. Use only the exact short labels requested. Concrete simplified explanation of the paper, schematic not experimental data. Every arrow and label must be precise. Title 'DiffCAP'. Three main boxes left-to-right: 'Adversarial image' → 'Add noise' → 'Denoise'. Between Add noise and Denoise a diamond 'Embeddings stable?'. A 'No' arrow loops to Add noise. A 'Yes' arrow proceeds to Denoise. After Denoise a box 'VLM prediction' with a simple clean image icon. Footer 'Adaptive stopping · Clean input'. Adversarial image is a simple small object with a few red perturbation marks; denoise restores same object.

## ompo
- File: [ompo-diagram.jpg](ompo-diagram.jpg)
- Source: https://arxiv.org/abs/2502.12678
- Explanation: Compare policies at each turn and update them using multi-step preferences.

Use case: scientific-educational. Generate a clear labeled method diagram for a research website publication thumbnail, landscape 3:2 composition. Flat clean scientific figure on warm ivory, dark teal text and lines, sage boxes, occasional ochre highlight. Large readable labels, no landscape scenery, no decorative metaphor, no 3D, no grain, no tiny text, no fabricated performance numbers. Use only the exact short labels requested. Concrete simplified explanation of the paper, schematic not experimental data. Every arrow and label must be precise. Title 'Multi-step alignment'. Two parallel rows labeled 'Policy A' and 'Policy B', each with three dialogue state boxes 'Turn 1' → 'Turn 2' → 'Turn 3'. Between corresponding turn pairs, small gold comparison connectors labeled 'Preference'. Beneath rows a wide box 'Optimistic policy update' receiving preference signals with a return arrow to both policies. Footer 'Two-player Markov game'. Make stepwise comparison central.

## membership
- File: [membership-diagram.jpg](membership-diagram.jpg)
- Source: https://arxiv.org/abs/2411.02902
- Explanation: Use image and text output statistics to detect training-data membership.

Use case: scientific-educational. Generate a clear labeled method diagram for a research website publication thumbnail, landscape 3:2 composition. Flat clean scientific figure on warm ivory, dark teal text and lines, sage boxes, occasional ochre highlight. Large readable labels, no landscape scenery, no decorative metaphor, no 3D, no grain, no tiny text, no fabricated performance numbers. Use only the exact short labels requested. Concrete simplified explanation of the paper, schematic not experimental data. Every arrow and label must be precise. Title 'Membership inference'. Left input box 'Image + instruction' leads to 'VLM' which outputs 'Generated description'. A return path combines image and description for a second box 'VLM logits'. Then 'MaxRényi-K%' → two clearly separated outcomes 'Member' and 'Non-member'. Footer 'Was this sample in the training data?'. Use image tile and text line icons; no archive or magnifier metaphor. All nodes and arrows simple and readable.

## kernel
- File: [kernel-diagram.jpg](kernel-diagram.jpg)
- Source: https://arxiv.org/abs/2406.03171
- Explanation: Importance weighting changes the bias–variance trade-off under covariate shift.

Use case: scientific-educational. Generate a clear labeled method diagram for a research website publication thumbnail, landscape 3:2 composition. Flat clean scientific figure on warm ivory, dark teal text and lines, sage boxes, occasional ochre highlight. Large readable labels, no landscape scenery, no decorative metaphor, no 3D, no grain, no tiny text, no fabricated performance numbers. Use only the exact short labels requested. Concrete simplified explanation of the paper, schematic not experimental data. Every arrow and label must be precise. Title 'Kernel methods under shift'. Top: two simple offset bell curves labeled 'Train p(x)' and 'Test q(x)'. Middle: formula 'w(x) = q(x) / p(x)' in a box labeled 'Importance weights'. Arrow into 'Weighted kernel regression'. Bottom two branches 'Bias' and 'Variance', with caption 'Data-dependent regularization'. Curves schematic, no numeric axes and no implied universal performance improvement.

## gflownet
- File: [gflownet-diagram.jpg](gflownet-diagram.jpg)
- Source: https://arxiv.org/abs/2310.00386
- Explanation: Learn rewards from candidate orderings, then sample through a GFlowNet.

Use case: scientific-educational. Generate a clear labeled method diagram for a research website publication thumbnail, landscape 3:2 composition. Flat clean scientific figure on warm ivory, dark teal text and lines, sage boxes, occasional ochre highlight. Large readable labels, no landscape scenery, no decorative metaphor, no 3D, no grain, no tiny text, no fabricated performance numbers. Use only the exact short labels requested. Concrete simplified explanation of the paper, schematic not experimental data. Every arrow and label must be precise. Title 'Order-preserving GFlowNets'. Left 3 small candidate objects labeled 'A', 'B', 'C'. Beneath them exact relation 'A ≺ B ≺ C'. Arrow into a box 'Learn reward from order'. Arrow to a small branching node network labeled 'GFlowNet'. On the right 3 terminal candidate nodes with increasing simple bar heights for A B C labeled 'Sampling probabilities'. Footer 'Ordering instead of explicit reward values'. Avoid a numeric reward formula or guarantee of only one candidate.

## resnet
- File: [resnet-diagram.jpg](resnet-diagram.jpg)
- Source: https://arxiv.org/abs/2403.09889
- Explanation: Control parameter-distribution movement to derive generalization bounds.

Use case: scientific-educational. Generate a clear labeled method diagram for a research website publication thumbnail, landscape 3:2 composition. Flat clean scientific figure on warm ivory, dark teal text and lines, sage boxes, occasional ochre highlight. Large readable labels, no landscape scenery, no decorative metaphor, no 3D, no grain, no tiny text, no fabricated performance numbers. Use only the exact short labels requested. Concrete simplified explanation of the paper, schematic not experimental data. Every arrow and label must be precise. Title 'ResNets in the mean-field regime'. Top left three neural layer blocks with explicit curved skip connections labeled 'Deep + wide ResNet'. Arrow right to smooth particle flow labeled 'Continuous limit'. Lower chain of three clear boxes 'Parameter distribution' → 'KL control' → 'Generalization bound'. Footer 'Beyond lazy training'. No measured plot or arbitrary axes; use a mathematical network diagram, not decorative flowing waves.

## pruning
- File: [pruning-diagram.jpg](pruning-diagram.jpg)
- Source: https://arxiv.org/abs/2009.11094
- Explanation: Randomly retain edges using layerwise ratios, then train the sparse network.

Use case: scientific-educational. Generate a clear labeled method diagram for a research website publication thumbnail, landscape 3:2 composition. Flat clean scientific figure on warm ivory, dark teal text and lines, sage boxes, occasional ochre highlight. Large readable labels, no landscape scenery, no decorative metaphor, no 3D, no grain, no tiny text, no fabricated performance numbers. Use only the exact short labels requested. Concrete simplified explanation of the paper, schematic not experimental data. Every arrow and label must be precise. Title 'Random tickets'. A dense small 3-layer network labeled 'Dense network' → small selector box 'Layerwise keep ratios' → sparse 3-layer network labeled 'Random subnetwork' → box 'Retrain'. Footer 'No training data needed for pruning'. Beneath main chain two small labeled controls 'Shuffle labels' and 'Rearrange connections', grouped under 'Sanity checks'. Highlight retained edges teal and removed edges faint dotted grey. Not node pruning: all nodes remain, only edges become sparse.

## DiffCAP heading revision
Built-in ImageGen edit: reduce only the top DiffCAP heading to 50% of its original size, centered; preserve the pipeline, labels, arrows, colors, and footer.
