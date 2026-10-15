# Contribution Archive

[← Back to profile](README.md) · [Live merged PR search](https://github.com/search?q=author%3Adreamfarer-space+is%3Apr+is%3Amerged+-user%3Adreamfarer-space&type=pullrequests)

Snapshot checked on **2026-10-15**: **20 directly merged upstream PRs** across **3 projects** (OpenMausBot: 5; ds-harness-remote: 12; DSCodex: 3). Credited code adoption and open submissions are listed separately.

## Merged Upstream Contributions

### [**milind-soni / OpenMausBot**](https://github.com/milind-soni/OpenMausBot)


> **Overview**: An open-source alternative to Grok Bot featuring an isolated virtual machine execution environment for conversational bots.

| Merged Pull Request | Impact &amp; Scope | Date |
| :--- | :--- | :---: |
| [**#1719** &middot; Add Simplified and Traditional Chinese localization to desktop and mobile](https://github.com/milind-soni/OpenMausBot/pull/1719) | Added complete Simplified and Traditional Chinese localization across desktop, Android, and iOS, including locale routing, resource coverage checks, and mobile regression tests | Oct 2026 |
| [**#2025** &middot; feat(claude): offer Claude Sonnet 5.5 in the Claude engine](https://github.com/milind-soni/OpenMausBot/pull/2025) | Added Claude Sonnet 5.5 to the model catalog with context-window detection and regression coverage | Sep 2026 |
| [**#1959** &middot; fix(chat): align KaTeX version and cover adjacent inline code](https://github.com/milind-soni/OpenMausBot/pull/1959) | Deduplicated KaTeX dependencies and added regression coverage for adjacent inline code spans | Sep 2026 |
| [**#1607** &middot; fix(chat): make wrapped bot mentions trigger in channels](https://github.com/milind-soni/OpenMausBot/pull/1607) | Fixed regex token boundary parsing for wrapped channel mentions | Sep 2026 |
| [**#1608** &middot; feat(chat): render LaTeX math with KaTeX](https://github.com/milind-soni/OpenMausBot/pull/1608) | Integrated KaTeX math rendering engine with regression test suites | Sep 2026 |

### [**liguobao / ds-harness-remote**](https://github.com/liguobao/ds-harness-remote)


> **Overview**: A multi-device remote access solution for DeepSeek Harness and CodeX across desktop, Android, and Web, with end-to-end encryption and P2P-first connectivity.

| Merged Pull Request | Impact &amp; Scope | Date |
| :--- | :--- | :---: |
| [**#112** &middot; feat(android): 导航栏三段式 iOS 胶囊悬浮顶栏与视觉居中对齐](https://github.com/liguobao/ds-harness-remote/pull/112) | Refined the Android floating top bar with separate menu and action controls, a single-line title, and safe-area-aware layout. | Oct 2026 |
| [**#111** &middot; feat(android): 顶部导航栏支持毛玻璃半透明模糊效果](https://github.com/liguobao/ds-harness-remote/pull/111) | Added a translucent blurred Android top bar with light/dark theme support. | Oct 2026 |
| [**#108** &middot; fix(android): 将会话写锁冲突映射为友好的多语言提示](https://github.com/liguobao/ds-harness-remote/pull/108) | Mapped session write-lock conflicts to readable, localized Android messages. | Oct 2026 |
| [**#103** &middot; feat(android): 支持直接修改设备名称，无需先连接（#102）](https://github.com/liguobao/ds-harness-remote/pull/103) | Allowed device names to be changed directly without connecting first. | Oct 2026 |
| [**#100** &middot; feat(android): 手机端解除绑定设备，重做滑动交互与动效](https://github.com/liguobao/ds-harness-remote/pull/100) | Added mobile device unbinding and refined swipe interactions and animations. | Oct 2026 |
| [**#94** &middot; fix(android): move quick prompts to the composer](https://github.com/liguobao/ds-harness-remote/pull/94) | Moved quick prompts to a direct composer entry while preserving prompt management, persistence, localization, drafts, and existing file/terminal/trajectory tools | Oct 2026 |
| [**#91** &middot; feat(android): add new-chat navigation, trajectories, and prompt management](https://github.com/liguobao/ds-harness-remote/pull/91) | Added top-level new-chat controls, trajectory access, localized prompt management and persistence, plus guarded Android back-stack behavior | Oct 2026 |
| [**#89** &middot; feat(android): add native mention/command menus, message actions, and trajectory mode](https://github.com/liguobao/ds-harness-remote/pull/89) | Added official-style @ and slash menus, message feedback/branching/usage actions, and a Host-backed trajectory inspection mode | Oct 2026 |
| [**#87** &middot; fix: close live HTTP/WebSocket previews when ports are revoked](https://github.com/liguobao/ds-harness-remote/pull/87) | Actively terminates revoked preview connections and pending reads/handshakes while preserving allowed ports and safe handle reuse | Sep 2026 |
| [**#86** &middot; fix: isolate loopback previews across client disconnects](https://github.com/liguobao/ds-harness-remote/pull/86) | Isolated loopback preview resources per authenticated connection so one client disconnect or reconnect no longer breaks other clients or requires a Host restart | Sep 2026 |
| [**#83** &middot; feat(android): improve the chat composer and conversation actions](https://github.com/liguobao/ds-harness-remote/pull/83) | Added workspace and tool-access pickers, improved model and permission controls, and fixed session membership and image-prompt handling | Sep 2026 |
| [**#84** &middot; fix(scripts): handle missing optional plugins during Windows uninstall](https://github.com/liguobao/ds-harness-remote/pull/84) | Made Windows uninstall remove only declared plugins so missing File Viewer dependencies no longer interrupt cleanup | Sep 2026 |

### [**fish2lab / DSCodex**](https://github.com/fish2lab/DSCodex)


> **Overview**: A zero-patch local loopback router bringing DeepSeek models into official ChatGPT desktop and Codex workflows with native Responses API support.

| Merged Pull Request | Impact &amp; Scope | Date |
| :--- | :--- | :---: |
| [**#19** &middot; fix: Windows router auto-recovery &amp; Codex model paths](https://github.com/fish2lab/DSCodex/pull/19) | Stabilized background supervisor recovery and localized model paths | Aug 2026 |
| [**#5** &middot; security: harden router lifecycle, credentials, and proxy handling](https://github.com/fish2lab/DSCodex/pull/5) | Hardened token lifecycles, credential storage, and proxy forwarding | Aug 2026 |
| [**#1** &middot; fix: use `%USERPROFILE%` in Windows autostart VBS](https://github.com/fish2lab/DSCodex/pull/1) | Resolved Windows autostart failure caused by Unicode home directories | Aug 2026 |

## Additional Upstream Contributions

### [**NousResearch / hermes-agent**](https://github.com/NousResearch/hermes-agent)


| Upstream Pull Request | Contribution | Date |
| :--- | :--- | :---: |
| [**#127983** &middot; Desktop bundle-skew probes no longer pile up git processes or survive quit](https://github.com/NousResearch/hermes-agent/pull/127983) | Incorporated the coalesced and cached bundle-skew checker from my [**#126186**](https://github.com/NousResearch/hermes-agent/pull/126186), preserving authorship. My original PR's Windows process-tree tests passed on Windows Server 2025 (50 passed, 1 skipped). | Sep 2026 |

> **Attribution**: My original PR **#126186** was superseded rather than merged directly. Its code was incorporated into the merged **#127983**, whose description explicitly credits **@dreamfarer-space**. This contribution is listed separately and excluded from the directly merged PR total.

#### Active upstream work (status checked 2026-10-15)

| Pull Request | Status | Scope | Date |
| :--- | :--- | :---: |
| [**#132052** &middot; fix(desktop): show readable artifact filenames without changing links](https://github.com/NousResearch/hermes-agent/pull/132052) | ![Open](https://img.shields.io/badge/Open-238636?style=flat-square) | Normalizes readable artifact/media filenames across Chinese, URL-encoded and Windows path cases while preserving original links and save paths | Oct 2026 |
| [**#125227** &middot; fix(install): preserve Unicode bootstrap Python paths on Windows](https://github.com/NousResearch/hermes-agent/pull/125227) | ![Open](https://img.shields.io/badge/Open-238636?style=flat-square) | Preserves non-ASCII bootstrap Python paths across PowerShell and uv installer flows on supported Windows setups | Sep 2026 |
