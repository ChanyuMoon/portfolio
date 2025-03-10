# Chanyu Moon | 문찬유
I am master student in DGIST, advised by professor [Ji-Woong Choi](https://scholar.google.com/citations?user=V2I9oYMAAAAJ&hl=ko). I received by Bachelor's degree in Computer Science and Electronic Engineering from DGIST in 2024.   

Check out my cv / [github](https://github.com/ChanyuMoon) / [scholar](https://scholar.google.com/citations?hl=ko&user=l9m2FnQAAAAJ&view_op=list_works&gmla=AOv-ny9DsJGv4hvrmkwzkQ1cEgpMwCDR970UmxZ3N7SV3a4Dlm_iVlBUXitqVo5yJLbwvRNc-Mauupg--xHyhdqGDeWMOyOZKwUoq1-PnUErZTnulV4-h1cMdQ)

# Research

I am interested in the brain. I want to understand how our brain performs cognitive functions and motor control, and why patients with brain disorders such as Parkinson's disease experience certain symptoms.


### OFF-CLIP: Improving Normal Detection Confidence in Radiology CLIP with Simple Off-Diagonal Term Auto-Adjustment

Contrastive Language-Image Pre-Training (CLIP) has enabled zero-shot classification in radiology, reducing reliance on manual annotations. However, conventional contrastive learning struggles with normal case detection due to its strict intra-sample alignment, which disrupts normal sample clustering and leads to high false positives (FPs) and false negatives (FNs). To address these issues, we propose OFF-CLIP, a contrastive learning refinement that improves normal detection by introducing an off-diagonal term loss to enhance normal sample clustering and applying sentence-level text filtering to mitigate FNs by removing misaligned normal statements from abnormal reports. OFF-CLIP can be applied to radiology CLIP models without requiring any architectural modifications. Experimental results show that OFF-CLIP significantly improves normal classification, achieving a 0.61 Area under the curve (AUC) increase on VinDr-CXR over CARZero, the state-of-the-art zero-shot classification baseline, while maintaining or improving abnormal classification performance. Additionally, OFF-CLIP enhances zero-shot grounding by improving pointing game accuracy, confirming better anomaly localization. These results demonstrate OFF-CLIP's effectiveness as a robust and efficient enhancement for medical vision-language models.
