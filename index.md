---
layout: default
title: Chatura
permalink: /
---

<section class="content-section content-section--hero">
<div class="hero-layout">
  <div class="hero-copy">
    <h1>Chatura</h1>
    <p class="hero-tagline"><strong>Chatura: Where Cura Meets Chat</strong></p>
    <p>Chatura is a character-led AI companion built for everyday warmth, gentle support, and the kind of conversation you can come back to.</p>
    <p>When life feels heavy, quiet, lonely, or in-between, Chatura offers a steady place to land. Open the app and start talking—no setup, no pressure, no need to explain everything perfectly. The experience is designed to feel calm and continuous: conversations don’t have to feel disposable, and the relationship can grow more personal over time.</p>
    <a class="hero-download-link" href="https://apps.apple.com/app/chatura/id6758027835/" target="_blank" rel="noopener">Download on the App Store</a>
    <div class="download-panel__meta hero-meta" aria-label="Chatura highlights">
      <span>No ads</span>
      <span>No account required</span>
      <span>Delete conversations anytime</span>
    </div>
  </div>

  <div class="hero-visual">
    <div class="product-preview" data-carousel>
      <button class="product-preview__control product-preview__control--prev" type="button" aria-label="Show previous screenshot" aria-controls="hero-screenshot-track" disabled>
        <svg viewBox="0 0 20 20" aria-hidden="true" focusable="false">
          <path d="M12.75 4.75 7.5 10l5.25 5.25" fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="1.8"/>
        </svg>
      </button>
      <div class="product-preview__shot">
        <div class="product-preview__shot-track" id="hero-screenshot-track" aria-label="Chatura app screenshots" tabindex="0">
          <img src="/assets/AppStoreScreenshot/Screenshot1.png" alt="Chatura app screenshot">
          <img src="/assets/AppStoreScreenshot/Screenshot2.png" alt="Chatura app screenshot">
          <img src="/assets/AppStoreScreenshot/Screenshot3.png" alt="Chatura app screenshot">
          <img src="/assets/AppStoreScreenshot/Screenshot4.png" alt="Chatura app screenshot">
          <img src="/assets/AppStoreScreenshot/Screenshot5.png" alt="Chatura app screenshot">
          <img src="/assets/AppStoreScreenshot/Screenshot6.png" alt="Chatura app screenshot">
          <img src="/assets/AppStoreScreenshot/Screenshot7.png" alt="Chatura app screenshot">
        </div>
      </div>
      <button class="product-preview__control product-preview__control--next" type="button" aria-label="Show next screenshot" aria-controls="hero-screenshot-track">
        <svg viewBox="0 0 20 20" aria-hidden="true" focusable="false">
          <path d="M7.25 4.75 12.5 10l-5.25 5.25" fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="1.8"/>
        </svg>
      </button>
    </div>
  </div>
</div>
</section>

<script>
  (function () {
    var carousel = document.querySelector("[data-carousel]");
    if (!carousel) return;

    var track = carousel.querySelector(".product-preview__shot-track");
    var previous = carousel.querySelector(".product-preview__control--prev");
    var next = carousel.querySelector(".product-preview__control--next");
    if (!track || !previous || !next) return;

    var getStep = function () {
      var firstImage = track.querySelector("img");
      var styles = window.getComputedStyle(track);
      var gap = parseFloat(styles.columnGap || styles.gap || "0");
      if (!firstImage) return track.clientWidth * 0.82;
      return firstImage.getBoundingClientRect().width + gap;
    };

    var syncControls = function () {
      var maxScroll = Math.max(track.scrollWidth - track.clientWidth - 2, 0);
      previous.disabled = track.scrollLeft <= 2;
      next.disabled = track.scrollLeft >= maxScroll;
    };

    previous.addEventListener("click", function () {
      track.scrollBy({ left: -getStep(), behavior: "smooth" });
    });

    next.addEventListener("click", function () {
      track.scrollBy({ left: getStep(), behavior: "smooth" });
    });

    track.addEventListener("scroll", syncControls, { passive: true });
    window.addEventListener("resize", syncControls);
    syncControls();
  })();
</script>

<section id="features" class="content-section content-section--features" markdown="1">
## Features

<div class="feature-grid" markdown="1">
<article class="feature-card" markdown="1">
<div class="feature-card__intro" markdown="1">
## 1) A warm companion you can come back to
### Kind, steady conversation—without pressure or judgment.
Whether it’s a morning reset, a quiet moment between meetings, or late-night thoughts you do not want to carry alone, Chatura responds with calm support and a familiar tone—so you can feel heard, steadier, and a little lighter.
</div>
<div class="feature-card__body" markdown="1">
**Built for daily check-ins:**
- Text-first chat designed for calm, supportive companionship
- One dedicated core character designed for everyday warmth
- Open the app and start talking—no setup, no pressure, no need to explain everything perfectly
</div>
</article>

<article class="feature-card" markdown="1">
<div class="feature-card__intro" markdown="1">
## 2) Conversations that leave something behind
### Some chats stay with you. Some help you hold onto what matters.
Some chats matter because of how they made you feel. Others matter because they helped you hold onto something important.
</div>
<div class="feature-card__body" markdown="1">
**Keepsakes you can come back to:**
- **Our Memory** — moments worth keeping
- **Our Plan** — a clear next step you can revisit
- **Time Capsule** — a message for your future self
- **Wish Voice** — a hope you want to put into words
- **Secret Haven** — a more private place for what is hard to say elsewhere

*Keepsakes are created, edited, and deleted through chat as simple texts/cards—easy to revisit, with no separate management flow to learn.*
</div>
</article>

<article class="feature-card" markdown="1">
<div class="feature-card__intro" markdown="1">
## 3) Lifelike characters, not one generic assistant
### Six distinct characters, each with a steady sense of self.
Chatura is built around characters with their own tone, values, and perspective. Over time, each one stays grounded in who they are while becoming more informed by what you share—so the connection feels more stable, specific, and personal.
</div>
<div class="feature-card__body" markdown="1">
**What makes it feel grounded:**
- **6 characters total** *(1 core character included; 5 more unlocked with subscription)*
- Each character is anchored by **Info / Status / Interests**
- Characters can remember details you have shared and reflect them back over time
- Continuity comes from identity + shared touchpoints—not exaggerated “perfect memory” claims
</div>
</article>

<article class="feature-card" markdown="1">
<div class="feature-card__intro" markdown="1">
## 4) Moments between chats
### Companionship that does not disappear the moment you close the chat.
Chatura includes **Moments**: a calm feed where characters share small glimpses of daily life and thoughts. You can like, comment, and naturally step back into conversation—so the connection feels ongoing, not purely reactive.
</div>
<div class="feature-card__body" markdown="1">
**Designed to feel ambient and low-effort:**
- Characters share Moments generated from their profiles
- Lightweight interaction: like, comment, jump into chat
- Built to keep a sense of presence between conversations
</div>
</article>

<article class="feature-card" markdown="1">
<div class="feature-card__intro" markdown="1">
## 5) Private, calm, and in your control
### Built to feel respectful—not extractive.
Chatura is designed around user control. There are no ads, and no third-party data sharing for advertising or analytics. You can delete conversations anytime and export your chat data whenever you want.
</div>
<div class="feature-card__body" markdown="1">
**Privacy & control:**
- **No ads**
- **No account required**
- **Delete conversations** anytime
- **Export chat data** across characters
- **Secret Haven** supports optional **App Lock**, with **local encrypted storage** for that content
</div>
</article>
</div>
</section>

<section id="faq" class="content-section content-section--faq" markdown="1">
## FAQ
<div class="faq-grid" markdown="1">
  <div class="faq-item" markdown="1">
  **Can I start using Chatura for free?**
  Yes. You can start with Chatura’s core character for free. Optional subscription features are available in the app.
  </div>

  <div class="faq-item" markdown="1">
  **Do you show ads or share data for advertising?**
  No. Chatura does not show ads or share data with third parties for advertising or analytics.
  </div>

  <div class="faq-item" markdown="1">
  **Can I control my data?**
  Yes. You can delete conversations anytime and export your chat data.
  </div>

  <div class="faq-item" markdown="1">
  **Are the characters real people?**
  No. Chatura features AI-generated characters. They’re not real people and may make mistakes.
  </div>

  <div class="faq-item" markdown="1">
  **Is Chatura therapy?**
  No. Chatura is for supportive conversation and reflection. It does not provide medical advice, diagnosis, or treatment, and it is not a substitute for professional care.
  </div>

  <div class="faq-item" markdown="1">
  **Is Chatura for emergencies or crisis situations?**
  No. Chatura is not for emergencies. If you’re in immediate danger or considering self-harm, call 911 (US) or your local emergency number. In the US, you can also call or text 988.
  </div>
</div>
</section>

<section class="content-section content-section--links" markdown="1">
<div class="links-grid" markdown="1">
<div class="links-group" markdown="1">
## What’s New
- [What’s New](/whats-new/)
</div>

<div class="links-group" markdown="1">
## Legal
- [Privacy Policy](/privacy-policy/)
- [Terms of Service](/terms-of-service/)
</div>

<div class="links-group" markdown="1">
## Support
- [Support](/support/)
</div>

<div class="links-group" markdown="1">
## X
- [@ChaturaApp](https://x.com/ChaturaApp)
</div>
</div>
</section>
