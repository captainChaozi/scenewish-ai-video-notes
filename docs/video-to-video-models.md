# Video-to-video models on SceneWish

Comparison of the models listed on the [SceneWish video-to-video page](https://scenewish.com/video-to-video) (read 2026-11-01). Each model needs **one uploaded video**; they differ in accepted source length, resolution and reference images. Upload format: MP4 / MOV, up to 200 MB, within the chosen model's length range.

| Model | Provider | Source video | Reference images | Output length | Resolution | Choose it when |
|---|---|---|---|---|---|---|
| Seedance 2.5 | ByteDance | 4–30 s | up to 30 (+ optional audio up to 10) | follows source | 480p / 720p / 1080p | clip up to 30 s and you want reference images |
| Kling v3 Omni | Kuaishou | 3–10 s | up to 7 | follows source | 720p / 1080p | short clip, 1080p or keep the original sound |
| Grok Imagine Video | xAI | 1–8.7 s | none | follows source | 720p | text-only edit of a short clip |
| HappyHorse 1.0 | Alibaba | 3–60 s | up to 5 | follows source | 720p / 1080p | long source, up to 60 s |
| Gemini Omni 1.1 Flash | Google | 1–10 s | up to 10 | chosen by the model | 360p / 720p / 1080p / 4k | let the model decide length, keep generated sound |
| Wan 2.7 Video Edit | Alibaba | 2–10 s | up to 4 | 2–10 s | 720p / 1080p | dedicated video-edit model |

## Usage notes

- Start from a short clip with a clear subject and ask for **one change at a time**.
- Check the credit quote before generating; it changes with length and resolution.
- Related: [reference-to-video-limits.md](reference-to-video-limits.md), [frame-pair-comparison.md](frame-pair-comparison.md).

Model names belong to their respective providers. Maintained by Chaozi, developer of SceneWish.
