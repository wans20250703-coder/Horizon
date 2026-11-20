---
layout: default
title: "Horizon Summary: 2026-11-20 (EN)"
date: 2026-11-20
lang: en
---

> From 181 items, 5 important content pieces were selected

---

**Technology News**
1. [OpenAI Models Deliver 13-14% PPA Gains on Jalapeño and AMD GPU Designs](#item-tech-news-1) ⭐️ 8.0/10
2. [Tencent cuts Yuanbao investment to prioritize model capabilities, scales WeChat AI assistant Xiaowei to 30M DAU in testing](#item-tech-news-2) ⭐️ 7.0/10
3. [Google Play Mandates Adaptive Compatibility for Foldables from April 2027](#item-tech-news-3) ⭐️ 7.0/10
4. [Telegram macOS Beta Adds Local Hidden Chats with Passphrase](#item-tech-news-4) ⭐️ 5.0/10

**Financial News**
1. [Pinduoduo Q3 2026 revenue 108.3B yuan, shares jump 8% pre-market](#item-finance-news-1) ⭐️ 7.0/10

---

## Technology News

<a id="item-tech-news-1"></a>
### [OpenAI Models Deliver 13-14% PPA Gains on Jalapeño and AMD GPU Designs](https://openai.com/index/advancing-chip-design-with-our-models/) ⭐️ 8.0/10

OpenAI reports its models achieved measurable PPA improvements on production chip designs: approximately 13% standard-cell area reduction on the vector unit and 10% on the matrix unit of its Jalapeño inference chip, validated during bring-up, and up to 14% PPA gains on AMD&\#x27;s flagship GPU IP relative to a highly optimized baseline, with some changes already taped out. OpenAI also announced a collaboration with Synopsys to train a GPT-Synopsys model for EDA workflows.

telegram · zaihuapd · Nov 19, 09:30

**「Background」** OpenAI first revealed its Jalapeño inference ASIC at Hot Chips in August 2026, describing a heavily AI-assisted design flow that achieved an unusually short development window. This announcement quantifies the resulting PPA gains on that silicon and extends the collaboration to AMD&\#x27;s flagship GPU IP and a new GPT-Synopsys model.

**「Impact」** Chip designers now have verified, production-stage evidence that LLM-assisted optimization can deliver double-digit PPA improvements on advanced nodes, moving the technique from research demos into commercial tape-outs. Teams evaluating AI-assisted EDA flows can reference these concrete results from OpenAI&\#x27;s own silicon and AMD&\#x27;s flagship GPU as benchmarks for potential ROI.

<details><summary>References</summary>
<ul>
<li><a href="https://www.tomshardware.com/tech-industry/artificial-intelligence/openai-jalapeno-design-interview-transcript-hardware-vp-richard-ho-explains-how-ai-assisted-design-may-shape-the-future-of-inference-asics">OpenAI Jalapeño design interview transcript... | Tom&#x27;s Hardware</a></li>

</ul>
</details>

**Tags**: `#AI-assisted chip design`, `#OpenAI`, `#AMD`, `#EDA`, `#hardware acceleration`

---

<a id="item-tech-news-2"></a>
### [Tencent cuts Yuanbao investment to prioritize model capabilities, scales WeChat AI assistant Xiaowei to 30M DAU in testing](https://news.qq.com/rain/a/20261119A04QD000) ⭐️ 7.0/10

Tencent President Liu Chiping stated that the Yuanbao consumer AI app did not meet expectations, prompting the company to significantly reduce investment in Yuanbao and shift focus to improving core model capabilities. Yuanbao will no longer prioritize user scale as its primary goal, though progress is described as positive. Meanwhile, Tencent disclosed that its WeChat AI assistant &quot;Xiaowei&quot; has expanded its user testing pool to 30 million daily active users, and its projected quarterly cost after full launch will be lower than Yuanbao&\#x27;s quarterly cost earlier this year.

telegram · zaihuapd · Nov 19, 05:00

**「Background」** Yuanbao is Tencent&\#x27;s consumer-facing AI assistant app built on its Hunyuan large language model, offering chat, search, and productivity features. Xiaowei is a separate AI assistant integrated into WeChat, China&\#x27;s dominant messaging platform with over 1.3 billion monthly active users. Tencent has been developing both products in parallel as part of its broader AI strategy, with Yuanbao positioned as a standalone app and Xiaowei embedded within the WeChat ecosystem.

**「Impact」** Developers and enterprises relying on Tencent&\#x27;s AI ecosystem should expect reduced consumer-facing features from Yuanbao but potentially stronger underlying model APIs, while the lower-cost Xiaowei integration into WeChat could accelerate AI adoption among WeChat&\#x27;s massive user base.

<details><summary>References</summary>
<ul>
<li><a href="https://apkpure.net/teng-xun-yuan-bao/com.tencent.hunyuan.app.chat/download">Download Tencent Yuanbao 2.91.10 APK for Android - Free and Safe...</a></li>
<li><a href="https://apkpure.com/teng-xun-yuan-bao/com.tencent.hunyuan.app.chat">Tencent Yuanbao APK for Android Download</a></li>

</ul>
</details>

**Tags**: `#AI`, `#Tencent`, `#LLM`, `#Chinese tech`, `#business strategy`

---

<a id="item-tech-news-3"></a>
### [Google Play Mandates Adaptive Compatibility for Foldables from April 2027](https://developer.android.google.cn/blog/posts/google-play-adaptive-quality-standards?hl=zh-cn) ⭐️ 7.0/10

Google Play will require Android apps to meet adaptive compatibility standards for foldable and large-screen devices starting April 2027. Apps must avoid UI stretching, black bars, and locked aspect ratios, and must preserve state during device form-factor transitions. Developers must also submit foldable-device screenshots. Non-compliant apps risk update restrictions and reduced store visibility. Additionally, from August 2027, new apps and updates must target Android 17 \(API 37\).

telegram · zaihuapd · Nov 19, 08:42

**「Background」** Google&\#x27;s Android adaptive app quality guidelines define tiered criteria for how well apps handle foldable and large-screen devices, covering layout responsiveness, state preservation during posture changes, and proper use of window metrics. Tier 3 represents the highest compliance level, requiring apps to fully adapt their UI to different window sizes and device states without letterboxing, stretching, or locked orientations. The new policy makes this previously recommended tier a mandatory distribution requirement on Google Play.

**「Impact」** Android developers must update their apps to support adaptive layouts and foldable-specific behaviors before April 2027 to avoid distribution penalties. Testing on foldable devices or emulators and providing appropriate screenshots will become mandatory for Play Store updates.

<details><summary>References</summary>
<ul>
<li><a href="https://developer.android.com/blog/posts/google-play-adaptive-quality-standards">Elevating apps: New adaptive quality standards on Google Play</a></li>

</ul>
</details>

**Tags**: `#Android`, `#Google Play`, `#foldable devices`, `#app development`, `#platform policy`

---

<a id="item-tech-news-4"></a>
### [Telegram macOS Beta Adds Local Hidden Chats with Passphrase](https://telegram.me/zaihuapd/45242) ⭐️ 5.0/10

Telegram macOS beta version 13.2 \(build 283584\) introduces an experimental Hidden Chats feature that lets users conceal selected conversations behind a local passphrase of at least eight characters. Hidden chats vanish from the main list, folders, search results, and notifications, and incoming calls are automatically rejected; the space auto-locks on screen lock, sleep, or after five minutes of inactivity, and can be manually closed with ⌘L. The passphrase is not stored and cannot be recovered, and the feature only applies to the single Mac where it is configured, with no sync to other devices and a known bypass via Telegram Web from an unlocked client.

telegram · zaihuapd · Nov 19, 16:04

**「Background」** Telegram has long offered privacy-focused features like secret chats and passcode locks, but this beta adds a device-local hidden space designed specifically against shoulder-surfing rather than as an account-level security mechanism.

**「Impact」** macOS beta testers can now isolate sensitive conversations on a single machine, but they must remember the passphrase permanently and should not rely on the feature for cross-device protection or against determined attackers with Web access.

**Tags**: `#Telegram`, `#macOS`, `#privacy`, `#beta`, `#security`

---

## Financial News

<a id="item-finance-news-1"></a>
### [Pinduoduo Q3 2026 revenue 108.3B yuan, shares jump 8% pre-market](https://mp.weixin.qq.com/s/vMtfWkFZ0hRTDU54BlD80Q) ⭐️ 7.0/10

Pinduoduo reported Q3 2026 revenue of 108.3 billion yuan and net profit of 29.5 billion yuan, sending its shares up over 8% in pre-market trading.

telegram · zaihuapd · Nov 19, 12:56

**「Background」** Pinduoduo is a major Chinese e-commerce platform that also operates the international marketplace Temu, and it reports quarterly financial results to Hong Kong and U.S. investors.

<details><summary>References</summary>
<ul>
<li><a href="https://scm-en.ecer.com/topic/detail-854156-pinduoduos-q3-profit-jumps-sixfold-amid-temu-global-push.html">Pinduoduos Q 3 Profit Jumps Sixfold Amid Temu Global Push</a></li>

</ul>
</details>

**Tags**: `#Pinduoduo`, `#earnings`, `#e-commerce`, `#China`, `#stock market`

---