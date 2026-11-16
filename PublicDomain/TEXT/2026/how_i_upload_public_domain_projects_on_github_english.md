# How I Upload "Public Domain" Open-Source Projects Correctly on GitHub

If you've been wondering how I've been structuring my projects since late 2026 through possibly early 2027, well, this documentation is for you.

> **LICENSE NOTICE:** This "documentation" is very short and is dedicated to the Public Domain under **CC0 1.0**.

It is meant more as a personal checklist—things I wish I had known when I was first starting out.

---

### ⚠️ IMPORTANT DISCLAIMERS & WARNINGS

* **Not Legal Advice:** I am not a lawyer or a legal expert. I can make mistakes, so please do not take this document as absolute legal truth. Always do your own research if you have specific legal needs.
* **Personal Workflow & Irreversibility:** This guide simply shares *my* personal method for releasing international "Public Domain" projects on GitHub. Consider it a tip if you truly want to release your work without restrictions. **Be 100% sure before using these licenses:** once you release something into the Public Domain (or under Public Domain-equivalent licenses), **there is no turning back**. It is permanent and for life!

---

### 💡 My Core Recommendations

If you want to share source code as "Public Domain" for an international audience, **NEVER use CC0 1.0 or The Unlicense for your code.**

Yes, almost everyone uses them (especially CC0 1.0), but you should **only use Creative Commons licenses for assets** (images, audio, text, etc.) and **not for source code**, in order to avoid legal gray areas.

**The Unlicense** is *almost* perfect, but it has a major flaw: it is incompatible with many European countries. In several jurisdictions, it is legally impossible to waive your moral rights while you are alive. CC0 1.0 includes a fallback license mechanism to legally bypass this issue for assets, whereas The Unlicense lacks this feature for source code.

#### So, what licenses do I recommend for code?
Even though they are technically ultra-permissive licenses rather than strict "Public Domain" dedications, they act in the exact same way in practice. I recommend using **MIT-0** (MIT No Attribution) and **BSD-0** (BSD Zero Clause).

From now on, whenever I create a project that I want to be 100% "Public Domain", I use a **multi-licensing setup**:
* **Source Code / Scripts:** Dual-licensed under **MIT-0** and **BSD-0**.
* **Assets:** Licensed under **CC0 1.0**.

This ensures that anyone, anywhere in the world, can use your GitHub projects freely without legal headaches.

---

### 🔗 Helpful Repositories & Examples

To help you set this up easily, check out these two repositories I created:

1. **Ready-to-Use Triple-License Template:**
   If you want all three licenses combined into a single file—explicitly stating that your **assets are under CC0 1.0** while your **scripts/code are under MIT-0 & BSD-0**—I highly recommend downloading the `LICENSE` file from my repository below. Just remember to **add your own username/name and the current year** to it!
   👉 [Triple-Licenses-Public-Domain on GitHub](https://github.com/Stormwindsky/Triple-Licenses-Public-Domain)

2. **Real-World Example (Scratch Project):**
   Want to see how this looks in practice? Here is a Scratch project I created and released into the "Public Domain" using this exact setup (**MIT-0 & BSD-0** for the project's source code and **CC0 1.0** for the assets):
   👉 [Lava-Legacy-Retake on GitHub](https://github.com/Stormwindsky/Lava-Legacy-Retake)