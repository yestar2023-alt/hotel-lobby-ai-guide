# Hotel Lobby AI: Two-Photo Video Guide

A practical guide to preparing two portraits, planning a short duo video and reviewing an AI-generated result.

**Web app:** [Hotel Lobby AI](https://hotel-lobbyai.online/?utm_source=github&utm_medium=referral&utm_campaign=video-guide) · **[Step-by-step tutorial](https://hotel-lobbyai.online/how-to-make-hotel-lobby-ai-video)**

This repository contains documentation and a review checklist. It does not contain the web application's source code, a public API client or model weights. It is maintained for the Hotel Lobby AI project; the product links are first-party links. The guide was prepared with AI assistance and checked against the public interface on October 7, 2026.

## What the app does

Hotel Lobby AI brings two people or anime-style characters into a short duo performance in an orange studio with a hanging microphone. The Classic template supplies the scene, so its basic workflow does not require a written prompt.

The public interface offers 5-, 10- and 15-second clips and five aspect ratios: 16:9, 9:16, 1:1, 4:3 and 3:4. Video quality depends on the selected option and the credits available to the account. The selected duration and quality determine the credit cost shown before generation.

## 1. Prepare the two inputs

Use one photo for each performer. Prefer a clearly visible face, good lighting and an upper-body crop. Avoid group shots, heavily blurred images, covered faces and faces that occupy only a tiny part of the photo.

Accepted photo formats shown in the interface: **JPG, PNG and WEBP**, up to **10 MB per photo**. Only use photos and audio you have permission to use.

Before uploading, decide which person belongs in each input slot. Record the assignment if you plan to compare more than one result. Changing both the photo order and video settings at once makes it harder to understand what changed.

## 2. Plan the clip before generating

| Decision | How to choose |
| --- | --- |
| Aspect ratio | Match the intended viewing format: vertical, landscape or square. Preview framing before committing to a longer clip. |
| Duration | Start with the shortest clip that can answer your current question. A framing check usually does not require a 15-second result. |
| Quality | Choose a mode supported by the account. Higher resolution and longer duration can spend more credits. |
| Audio | Use the selected template soundtrack or your own permitted WAV / MP3 clip. The interface asks for 5–15 seconds of audio, up to 15 MB. Cover the duration you select. |
| Budget | Read the displayed credit cost before pressing Generate. Do not assume that a preview or a previous generation pays for the next attempt. |

As checked on October 7, 2026, the site advertises **150 free credits for a new account**, enough for **one 5-second Fast 480p video**. These promotional credits expire **24 hours after receipt**. This is a limited trial, not unlimited free generation; check the current interface for changes.

### Credit costs shown on the public page

| Mode | 5 seconds | 10 seconds | 15 seconds |
| --- | ---: | ---: | ---: |
| Fast 480p | 150 | 300 | 450 |
| Fast 720p | 300 | 600 | 900 |
| Standard 768p | 250 | 500 | 750 |
| HD 1080p | 1,000 | 2,000 | 3,000 |
| HD 2k | 1,000 | 2,000 | 3,000 |

Values are credits, not dollars. Availability depends on the account's plan and credit type. For example, the interface currently limits one-time credits to 480p / 768p. Refer to the [current pricing page](https://hotel-lobbyai.online/pricing) before buying credits or selecting a paid plan.

## 3. Generate and review

1. Sign in, assign the two portraits and choose the video settings.
2. Check the selected soundtrack and displayed credit cost.
3. Submit the generation and wait for the completed result.
4. Watch the entire clip before downloading or sharing it.

Review both people throughout the video, not just its opening frame:

- Are both performers present, with acceptable faces and clothing?
- Are bodies and hands stable enough for the intended use?
- Does the framing work in the chosen aspect ratio?
- Is the soundtrack suitable, and does it cover the intended clip?
- Is it clear to viewers that this is a synthetic performance?

AI can change faces, movement and clothing. Exact likeness is not guaranteed. Site examples marked **Style reference** illustrate a look; they should not be treated as proof that your inputs will produce an identical result. This guide is not a benchmark of output quality or a claim that every generation succeeds.

## 4. Compare changes deliberately

If a result needs another attempt, change one variable at a time. For example, keep the same settings while replacing a blurry input portrait. Record the settings and review notes using [generation-review.csv](generation-review.csv). Keep that completed checklist private if it contains personal information, private image references or result URLs.

Downloading the same completed result is described by the site as free. Generating a new result consumes credits. Check the displayed cost again before submitting another attempt.

## Common questions

**Can I use a group photo?** The interface recommends one person per photo. Select another image where the intended performer is clear.

**Do I need a prompt?** The Classic workflow does not require one. Choose the two inputs, format, duration and available mode.

**Can I use it on a phone?** It is a browser workflow. Check that photo selection and the completed video download work in your browser before relying on it for a deadline.

**Does this repository provide a local generator?** No. The generator is the hosted web app. This repository provides preparation and review material only.

## 中文快速检查

1. 每张图片只放一个清晰人物；支持 JPG、PNG、WEBP，每张不超过 10 MB。
2. 先选比例、时长、可用画质和音乐，再核对显示的积分成本。
3. 新账号试用积分的额度和有效期以页面为准；当前页面标注 150 积分，领取后 24 小时到期。
4. 生成后完整观看，检查两个人、服装、手部、动作、裁切和音乐。AI 不保证精确还原人物。
5. 再次尝试时一次只改一个变量，避免无法判断哪项修改有效。

Questions about the product: [support@hotel-lobbyai.online](mailto:support@hotel-lobbyai.online). See the site's [privacy policy](https://hotel-lobbyai.online/privacy) and [terms](https://hotel-lobbyai.online/terms) for its current service policies.
