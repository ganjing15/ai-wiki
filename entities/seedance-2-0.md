---
title: Seedance 2.0 (ByteDance video generation)
created: 2026-05-14
updated: 2026-05-14
type: entity
tags: [model, multimodal, video-generation, bytedance]
sources: [raw/articles/bytedance-seedance-2-0-launch.md]
---

# Seedance 2.0 (ByteDance video generation)

## Source
[ByteDance SEED Lab official launch blog](https://seed.bytedance.com/en/blog/official-launch-of-seedance-2-0) → raw excerpt at [bytedance-seedance-2-0-launch.md](../raw/articles/bytedance-seedance-2-0-launch.md).

## Developer
ByteDance SEED Lab.

## Release date
**2026-02-12**

## Architecture
Unified multimodal audio-video joint generation architecture, supporting mixed-modality inputs across text, images, video, and audio.

## Supported inputs
- Text (natural language)
- Images (up to 9)
- Video clips (up to 3)
- Audio clips (up to 3)

## Outputs
- 15-second multi-shot audio-video generation
- Dual-channel stereo audio
- Multi-track parallel audio: background music, ambient effects, voiceovers

## Verbatim quote (ByteDance)
> "supports stable and controllable video extension and editing, enabling regular users to command the video creation process."

## Key capabilities
- Complex motion and interaction rendering with physical accuracy
- Prompt-driven camera planning and automatic visual composition
- Character consistency: preserves facial features, clothing, and style through 360° head turns and dramatic lighting changes
- Natural foley sound design with subtle acoustic details
- Video editing with targeted modifications to clips, characters, and actions

## Variants
| Variant | Description |
|---------|-------------|
| Seedance 2.0 | Full quality |
| Seedance 2.0 Fast | Reduced latency |

## Access
Consumer web apps, CapCut mobile/desktop editor, API (fal.ai, Replicate, WaveSpeed).

## Known limitations at launch
- Detail stability refinement needed
- Occasional audio distortion
- Multi-subject consistency optimization pending
- Text rendering accuracy improvements pending

## Notes on what was removed
Nothing removed — this is a new page. Prior to this entry, ByteDance video generation had no wiki page despite Seedance being one of the leading video generation models alongside Sora.

## Related Pages
[[Sora]] | [[Google DeepMind]] | [[Multimodal AI]] | [[Diffusion Models]]

## Sources (saved excerpts in raw/)
- [ByteDance SEED Lab launch blog](https://seed.bytedance.com/en/blog/official-launch-of-seedance-2-0) → [raw/articles/bytedance-seedance-2-0-launch.md](../raw/articles/bytedance-seedance-2-0-launch.md)
- [GitHub: bytedance-seedance/seedance-2.0](https://github.com/bytedance-seedance/seedance-2.0)
