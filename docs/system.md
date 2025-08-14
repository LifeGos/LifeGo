---
layout: page
title: System
---

## Architecture
- Capture → Preprocess → Multimodal Inference(BLIP3o, Whisper, Qwen2.5-VL) → Summarize/Index → WebXR Playback

![arch](/assets/img/system_arch.png)

## Data Flow
1. Edge(AR 글래스) 캡처
2. Web API로 업로드/스트리밍
3. 요약·임베딩 생성(TabNet/클러스터링)
4. 공간 재생(AR 앵커/경로)
