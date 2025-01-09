# Awesome-MLLM-Segmentation

**If you find this project helpful, please consider giving it a star ⭐.**

## Contents

<!-- vim-markdown-toc GitLab -->

- [Awesome-MLLM-Segmentation](#awesome-mllm-segmentation)
  - [Contents](#contents)
  - [Image Segmentation](#image-segmentation)
    - [Referring Image Segmentation](#referring-image-segmentation)
    - [Open-Vocabulary Semantic Segmentation](#open-vocabulary-semantic-segmentation)
  - [Video Segmentation](#video-segmentation)
  - [Feedback](#feedback)

<!-- vim-markdown-toc -->

## Image Segmentation

### Referring Image Segmentation

1. <span id = "1001">**[LISA]**</span> | **CVPR'24** | LISA: Reasoning Segmentation via Large Language Model | [`[pdf]`](https://arxiv.org/abs/2308.00692) | [`[code]`](https://github.com/dvlab-research/LISA)
2. <span id = "1002">**[GLaMM]**</span> | **CVPR'24** | GLaMM: Pixel Grounding Large Multimodal Model | [`[pdf]`](https://arxiv.org/abs/2311.03356) | [`[code]`](https://github.com/mbzuai-oryx/groundingLMM)
3. <span id = "1003">**[PixelLM]**</span> | **CVPR'24** | PixelLM: Pixel Reasoning with Large Multimodal Model | [`[pdf]`](https://arxiv.org/abs/2312.02228) | [`[code]`](https://github.com/MaverickRen/PixelLM)
4. <span id = "1004">**[GSVA]**</span> | **CVPR'24** | GSVA: Generalized Segmentation via Multimodal Large Language Models | [`[pdf]`](https://arxiv.org/abs/2312.10103) | [`[code]`](https://github.com/LeapLabTHU/GSVA)
5. <span id = "1005">**[AnyRef]**</span> | **CVPR'24** | Multi-modal Instruction Tuned LLMs with Fine-grained Visual Perception | [`[pdf]`](https://arxiv.org/abs/2403.02969) | [`[code]`](https://github.com/jwh97nn/AnyRef)
6. <span id = "1006">**[GROUNDHOG]**</span> | **CVPR'24** | GROUNDHOG: Grounding Large Language Models to Holistic Segmentation | [`[pdf]`](https://arxiv.org/abs/2402.16846) | [`[code]`](https://groundhog-mllm.github.io)
7. <span id = "1007">**[NExT-Chat]**</span> | **ICML'24** | NExT-Chat: An LMM for Chat, Detection and Segmentation | [`[pdf]`](https://arxiv.org/abs/2311.04498) | [`[code]`](https://github.com/NExT-ChatV/NExT-Chat)
8. <span id = "1008">**[PSALM]**</span> | **ECCV'24** | PSALM: Pixelwise SegmentAtion with Large Multi-Modal Model | [`[pdf]`](https://arxiv.org/abs/2403.14598) | [`[code]`](https://github.com/zamling/PSALM)
9. <span id = "1009">**[SAM4MLLM]**</span> | **ECCV'24** | SAM4MLLM: Enhance Multi-Modal Large Language Model for Referring Expression Segmentation | [`[pdf]`](https://arxiv.org/abs/2409.10542) | [`[code]`](https://github.com/AI-Application-and-Integration-Lab/SAM4MLLM)
10. <span id = "1010">**[CoReS]**</span> | **ECCV'24** | CoReS: Orchestrating the Dance of Reasoning and Segmentation | [`[pdf]`](https://arxiv.org/abs/2404.05673) | [`[code]`](https://github.com/baoxiaoyi/CoReS)
11. <span id = "1011">**[OMG-LLaVA]**</span> | **NeurIPS'24** | OMG-LLaVA: Bridging Image-level, Object-level, Pixel-level Reasoning and Understanding | [`[pdf]`](https://arxiv.org/abs/2406.19389) | [`[code]`](https://github.com/lxtGH/OMG-Seg)
12. <span id = "1012">**[VITRON ]**</span> | **NeurIPS'24** | Vitron: A Unified Pixel-level Vision LLM for Understanding, Generating, Segmenting, Editing | [`[pdf]`](https://arxiv.org/abs/2412.19806) | [`[code]`](https://github.com/SkyworkAI/Vitron)
13. <span id = "1013">**[VisionLLM v2]**</span> | **NeurIPS'24** | VisionLLM v2: An End-to-End Generalist Multimodal Large Language Model for Hundreds of Vision-Language Tasks | [`[pdf]`](https://arxiv.org/abs/2406.08394) | [`[code]`](https://github.com/OpenGVLab/VisionLLM)
14. <span id = "1014">**[VLTP]**</span> | **WACV'25** | VLTP: Vision-Language Guided Token Pruning for Task-Oriented Segmentation | [`[pdf]`](https://arxiv.org/abs/2409.08464) | [`[code]`](https://github.com/HanningChen/VLTP/tree/main)
15. <span id = "1015">**[LaVASeg]**</span> | **ArXiv'2403** | Empowering Segmentation Ability to Multi-modal Large Language Models | [`[pdf]`](https://arxiv.org/abs/2403.14141)
16. <span id = "1016">**[LaSagnA]**</span> | **ArXiv'2404** | LaSagnA: Language-based Segmentation Assistant for Complex Queries | [`[pdf]`](https://arxiv.org/abs/2404.08506) | [`[code]`](https://github.com/congvvc/LaSagnA)
17. <span id = "1017">**[F-LMM]**</span> | **ArXiv'2406** | F-LMM: Grounding Frozen Large Multimodal Models | [`[pdf]`](https://arxiv.org/abs/2406.05821) | [`[code]`](https://github.com/wusize/F-LMM)
18. <span id = "1018">**[SETOKIM]**</span> | **ArXiv'2406** | Towards Semantic Equivalence of Tokenization in Multimodal LLM | [`[pdf]`](https://arxiv.org/abs/2406.05127) | [`[code]`](https://github.com/wusize/F-LMM)
19. <span id = "1019">**[u-LLaVA]**</span> | **ArXiv'2408** | u-LLaVA: Unifying Multi-Modal Tasks via Large Language Model | [`[pdf]`](https://arxiv.org/abs/2311.05348) | [`[code]`](https://github.com/OPPOMKLab/u-LLaVA)
20. <span id = "1020">**[UnifiedMLLM]**</span> | **ArXiv'2408** | UnifiedMLLM: Enabling Unified Representation for Multi-modal Multi-tasks With Large Language Model | [`[pdf]`](https://arxiv.org/abs/2408.02503) | [`[code]`](https://github.com/lzw-lzw/UnifiedMLLM)
21. <span id = "1021">**[DIFFLMM]**</span> | **ArXiv'2410** | Emerging Pixel Grounding in Large Multimodal Models Without Grounding Supervision | [`[pdf]`](https://arxiv.org/abs/2410.08209) | [`[code]`](https://github.com/Shengcao-Cao/groundLMM)
22. <span id = "1022">**[SegLLM]**</span> | **ArXiv'2410** | SegLLM: Multi-round Reasoning Segmentation | [`[pdf]`](https://arxiv.org/pdf/2410.18923) | [`[code]`](https://github.com/berkeley-hipie/segllm)
23. <span id = "1023">**[HyperSeg]**</span> | **ArXiv'2411** | HyperSeg: Towards Universal Visual Segmentation with Large Language Model| [`[pdf]`](https://arxiv.org/abs/2411.17606) | [`[code]`](https://github.com/congvvc/HyperSeg)
24. <span id = "1024">**[InstructSeg]**</span> | **ArXiv'2412** | InstructSeg: Unifying Instructed Visual Segmentation with Multi-modal Large Language Models | [`[pdf]`](https://arxiv.org/abs/2412.14006) | [`[code]`](https://github.com/congvvc/InstructSeg)
25. <span id = "1025">**[PRIMA]**</span> | **ArXiv'2412** | PRIMA: Multi-Image Vision-Language Models for Reasoning Segmentation | [`[pdf]`](https://arxiv.org/abs/2412.15209) | [`[code]`](https://plan-lab.github.io/projects/prima/)
26. <span id = "1026">**[GeoGround]**</span> | **ArXiv'2411** | GeoGround: A Unified Large Vision-Language Model for Remote Sensing Visual Grounding | [`[pdf]`](https://arxiv.org/abs/2411.11904) | [`[code]`](https://github.com/zytx121/GeoGround)
27. <span id = "1027">**[RSUniVLM]**</span> | **ArXiv'2412** | RSUniVLM: A Unified Vision Language Model for Remote Sensing via Granularity-oriented Mixture of Experts | [`[pdf]`](https://arxiv.org/abs/2412.05679) | [`[code]`](https://github.com/xuliu-cyber/RSUniVLM)
28. <span id = "1028">**[Text4Seg]**</span> | **ArXiv'2410** | Text4Seg: Reimagining Image Segmentation as Text Generation | [`[pdf]`](https://arxiv.org/abs/2410.09855) | [`[code]`](https://github.com/mc-lan/Text4Seg)


### Open-Vocabulary Semantic Segmentation
1. <span id = "2001">**[PSALM]**</span> | **ECCV'24** | PSALM: Pixelwise SegmentAtion with Large Multi-Modal Model | [`[pdf]`](https://arxiv.org/abs/2403.14598) | [`[code]`](https://github.com/zamling/PSALM)
2. <span id = "2002">**[LLMFormer]**</span> | **IJCV'24** | LLMFormer: Large Language Model for Open-Vocabulary Semantic Segmentation | [`[pdf]`](https://link-springer-com.remotexs.ntu.edu.sg/article/10.1007/s11263-024-02171-y)
3. <span id = "2003">**[LaSagnA]**</span> | **ArXiv'2404** | LaSagnA: Language-based Segmentation Assistant for Complex Queries | [`[pdf]`](https://arxiv.org/abs/2404.08506) | [`[code]`](https://github.com/congvvc/LaSagnA)
4. <span id = "2004">**[HyperSeg]**</span> | **ArXiv'2411** | HyperSeg: Towards Universal Visual Segmentation with Large Language Model| [`[pdf]`](https://arxiv.org/abs/2411.17606) | [`[code]`](https://github.com/congvvc/HyperSeg)
5. <span id = "2005">**[Text4Seg]**</span> | **ArXiv'2410** | Text4Seg: Reimagining Image Segmentation as Text Generation | [`[pdf]`](https://arxiv.org/abs/2410.09855) | [`[code]`](https://github.com/mc-lan/Text4Seg)

## Video Segmentation
1. <span id = "3001">**[VISA]**</span> | **ECCV'24** | VISA: Reasoning Video Object Segmentation via Large Language Models | [`[pdf]`](https://arxiv.org/abs/2407.11325) | [`[code]`](https://github.com/cilinyan/VISA)
2. <span id = "3002">**[VideoLISA]**</span> | **NeurIPS'24** | One Token to Seg Them All: Language Instructed Reasoning Segmentation in Videos | [`[pdf]`](https://arxiv.org/abs/2409.19603) | [`[code]`](https://github.com/showlab/VideoLISA)
3. <span id = "3003">**[VITRON ]**</span> | **NeurIPS'24** | Vitron: A Unified Pixel-level Vision LLM for Understanding, Generating, Segmenting, Editing | [`[pdf]`](https://arxiv.org/abs/2412.19806) | [`[code]`](https://github.com/SkyworkAI/Vitron)
4. <span id = "3004">**[ViLLa]**</span> | **ArXiv'2407** | ViLLa: Video Reasoning Segmentation with Large Language Model | [`[pdf]`](https://arxiv.org/abs/2407.14500) | [`[code]`](https://github.com/rkzheng99/ViLLa)
5. <span id = "3005">**[HyperSeg]**</span> | **ArXiv'2411** | HyperSeg: Towards Universal Visual Segmentation with Large Language Model| [`[pdf]`](https://arxiv.org/abs/2411.17606) | [`[code]`](https://github.com/congvvc/HyperSeg)
6. <span id = "3006">**[InstructSeg]**</span> | **ArXiv'2412** | InstructSeg: Unifying Instructed Visual Segmentation with Multi-modal Large Language Models | [`[pdf]`](https://arxiv.org/abs/2412.14006) | [`[code]`](https://github.com/congvvc/InstructSeg)

## Feedback

If you have any suggestions or find missing papers, please feel free to reach out at `lanm0002@e.ntu.edu.sg`.
