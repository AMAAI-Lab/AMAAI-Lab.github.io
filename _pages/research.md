---
title: "AMAAI Lab - Research"
layout: textlay
excerpt: "AMAAI Lab -- Research"
sitemap: false
permalink: /research/
---

<style>
.research-section {
  display: flex;
  align-items: flex-start;
  gap: 20px;
  margin-bottom: 40px;
  flex-wrap: wrap;
}

.research-image {
  max-width: 500px;
  width: 100%;
  height: auto;
  border-radius: 8px;
  box-shadow: 0 4px 8px rgba(0,0,0,0.1);
}

.research-content {
  flex: 1;
  min-width: 300px;
}

.research-links {
  margin-top: 15px;
}

.research-links a {
  margin-right: 15px;
  margin-bottom: 10px;
  padding: 8px 16px;
  text-decoration: none;
  border-radius: 5px;
  transition: background-color 0.3s ease;
}

.research-links a:hover {
  background-color: #e2f0ff;
}

/* Mobile responsiveness */
@media (max-width: 768px) {
  .research-section {
    flex-direction: column;
    gap: 15px;
  }
  
  .research-image {
    max-width: 100%;
    align-self: center;
  }
  
  .research-content {
    min-width: unset;
  }
  
  .research-links a {
    margin-bottom: 10px;
    margin-right: 0;
  }
}

/* Tablet responsiveness */
@media (max-width: 1024px) and (min-width: 769px) {
  .research-image {
    max-width: 400px;
  }
}

/* Small mobile devices */
@media (max-width: 480px) {
  .research-section {
    gap: 10px;
  }
  
  .research-image {
    max-width: 100%;
  }
  
  .research-links a {
    font-size: 14px;
    padding: 6px 12px;
  }
}
</style>

# Research

At the **Audio, Music, and AI (AMAAI) Lab** at SUTD, our mission is to advance artificial intelligence for music and audio.  
We design systems that can **understand, generate, and interact with music**, combining deep learning, signal processing, and music theory.  
Our research spans creative AI, music information retrieval, multimodal learning, and ethical AI in music.

---

## Text-to-Music Generation

<div class="research-section">
  <img src="{{ site.url }}{{ site.baseurl }}/images/mustango.jpg" alt="Mustango Framework" class="research-image"/>
  <div class="research-content">
We developed <strong>Mustango</strong>, a <em>music-domain-knowledge-inspired</em> text-to-music system based on diffusion models. Unlike prior systems that rely only on general text prompts, Mustango enables <strong>controllable music generation</strong> with rich captions that specify <strong>chords, beats, tempo, and key</strong>.

<div class="research-links">
<a href="https://github.com/AMAAI-Lab/mustango" target="_blank">🔗 Code on GitHub</a>
<a href="https://arxiv.org/abs/2311.08355" target="_blank">🔗 Paper on arXiv</a>
</div>
  </div>
</div>


---

### Video-to-Music Generation
<div style="display: flex; align-items: flex-start; gap: 20px;">
 <img src="{{ site.url }}{{ site.baseurl }}/images/video2music.png" alt="Video2music Framework" width="500"/>
  <p>
   Music often coexists with video and other modalities, yet most generative AI models cannot create music that <i>matches</i> a given video.  
   To address this, we developed <b>Video2Music</b>, a generative framework that produces music conditioned on <b>visual and semantic cues</b>.
  <br><br>
   🔗 <a href="https://github.com/AMAAI-Lab/Video2Music" target="_blank">Code on GitHub</a>
   🔗 <a href="https://arxiv.org/abs/2311.00968" target="_blank">Paper on arXiv</a>  
  </p>
</div>

---

### Music Emotion Recognition (MER)
We explore how music evokes emotions by developing multitask learning frameworks that combine **deep embeddings** with **music-theory-informed features** (e.g., chords and key signatures).  
This research enables richer emotion-aware music recommendation and generation.

---

### Automatic Music Transcription and Analysis
Through models such as **DiffRoll** and **nnAudio**, we push the limits of deep learning for transcription and symbolic analysis, including chord recognition, onset detection, and alignment between audio and score.

---

### Creative AI and Plagiarism Detection
With generative AI raising originality concerns, we design systems to detect similarity in **melody, harmony, timbre, and lyrics**.  
Our work supports both creative exploration and intellectual property protection.

---

### Foundational Music Models
We build large-scale **joint audio–text embedding models** and **foundational music models** that power downstream tasks such as retrieval, captioning, recommendation, and adaptive generation.

---

### Open-Source Tools and Datasets
We actively contribute to the community with open-source projects such as **Mustango, Video2Music, Music FaderNets, DiffRoll, and MidiCaps**.  
These resources promote reproducibility and fuel innovation in music AI.

### ... and more.

<br><br>
