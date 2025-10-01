---
permalink: /
title: "Vahid Jebraeeli"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<style>
@keyframes scroll {
  0% { transform: translateX(0); }
  /* Animate to the width of the first set of items (3 items * 330px each) */
  100% { transform: translateX(calc(-3 * 330px)); }
}

.scrolling-wrapper {
  overflow: hidden;
  width: 100%;
}

.scrolling-track {
  display: flex;
  /* Total width = 2 * (number of items * (item width + horizontal margins)) */
  width: calc(6 * 330px); 
  animation: scroll 20s linear infinite;
}

.scroll-item {
  flex-shrink: 0;
  width: 300px;
  margin: 0 15px;
}

.scroll-item img {
  height: 200px;   /* Fixed height for all images */
  width: auto;     /* Width adjusts automatically to maintain aspect ratio */
  max-width: 100%; /* Ensures the image doesn't overflow its container */
  display: block;  /* Needed for horizontal margin auto centering */
  margin: 0 auto;  /* Centers the image within the item */
}

.scroll-title {
  text-align: center; /* Center aligns the titles */
  font-size: 0.9em;   /* Slightly reduced font size */
  margin-top: 8px;    /* Adds a little space between the image and title */
}
</style>

In an era of exponentially growing AI, my work asks a critical question: **How do we achieve intelligent scale sustainably?**

I am a Machine Learning and Computer Vision researcher, and a final-year Ph.D. candidate at North Carolina State University, where I architect the next generation of generative models and foundational vision systems. My research, summarized by the title of my thesis, *"Balanced Scalability for Sustainable ML"*, is focused on building AI that is not only powerful but also profoundly efficient. I move beyond brute-force computation to create systems with elegance, precision, and a deep understanding of the data they learn from.

## A Quick Look at My Research

<div class="scrolling-wrapper">
  <div class="scrolling-track">
    <div class="scroll-item">
      <a href="/research/">
        <img src="/images/vitcae_architecture.png" alt="VITCAE Architecture">
        <p class="scroll-title">VITCAE: ViT-based Class-conditioned Autoencoder</p>
      </a>
    </div>
    <div class="scroll-item">
      <a href="/research/">
        <img src="/images/expansive_synthesis.png" alt="Expansive Synthesis Architecture">
        <p class="scroll-title">Generative Expansion of Small Datasets</p>
      </a>
    </div>
    <div class="scroll-item">
      <a href="/research/">
        <img src="/images/koopcon_architecture.png" alt="Koopcon Architecture">
        <p class="scroll-title">Koopcon: A New Approach to Smarter Learning</p>
      </a>
    </div>
    <div class="scroll-item">
      <a href="/research/">
        <img src="/images/vitcae_architecture.png" alt="VITCAE Architecture">
        <p class="scroll-title">VITCAE: ViT-based Class-conditioned Autoencoder</p>
      </a>
    </div>
    <div class="scroll-item">
      <a href="/research/">
        <img src="/images/expansive_synthesis.png" alt="Expansive Synthesis Architecture">
        <p class="scroll-title">Generative Expansion of Small Datasets</p>
      </a>
    </div>
    <div class="scroll-item">
      <a href="/research/">
        <img src="/images/koopcon_architecture.png" alt="Koopcon Architecture">
        <p class="scroll-title">Koopcon: A New Approach to Smarter Learning</p>
      </a>
    </div>
  </div>
</div>

## My Approach: A Duality of Data Synthesis and Architectural Innovation

Today's AI demands immense datasets and computational power. My research confronts this challenge head-on by reimagining how machines learn from and generate information, focusing on two core areas:

* **Mastering the Data Lifecycle**: I build frameworks that fundamentally control the data itself. My work explores the full spectrum of data synthesis, from distillation to creation. My **"Koopcon"** model (ICIP 2024) utilizes Koopman Operator Theory and Optimal Transport to distill massive datasets into compact, potent essences, proving that smaller can be smarter. Conversely, its conceptual dual, my **"Expansive Synthesis"** framework (ICASSP 2025), can grow a rich, large-scale dataset from just a handful of samples, enabling powerful learning even when data is scarce.

* **Re-engineering Core AI Architectures**: I don't just use existing models; I redesign them from the inside out for greater control and efficiency. I am developing **ViTCAE**, a new class of Vision Transformer that repurposes the model's global Class token into a generative linchpin for controllable image synthesis. This work introduces a novel, dynamic attention mechanism inspired by opinion dynamics to significantly reduce computational overhead through a principled head-freezing technique. My ongoing research also explores the fusion of classical Volterra Filters with modern attention mechanisms, creating models with a far richer, multi-scale understanding of both local detail and global context.

## From Theory to Practice

My path has been one of consistent academic excellence, beginning with ranking in the top 0.3% in Iran's national university entrance exam and culminating in an M.Sc. with Distinction from the prestigious Sharif University of Technology. This rigorous theoretical grounding is balanced by hands-on industry experience, where I’ve engineered generative AI solutions for a German tech firm and deployed deep learning models for agricultural analysis with the USDA. This blend of deep theory and practical application fuels my pursuit of AI systems that are not just academically novel, but also robust, deployable, and impactful.

I believe the future of AI lies not in its size, but in its intelligence. If you share this vision, I'd love to connect --> [Email me!](mailto:vjebrae@ncsu.edu) or Connect me in [LinkedIn!](https://www.linkedin.com/in/vahid-jebraeeli-2a1406102/)
