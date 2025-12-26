---
layout: page
permalink: /repositories/
title: Projects
description: Below is a sample of some side projects I have worked on, in no particular order.
nav: true
nav_order: 3
---
<style>
.projects {
  display: flex;
  flex-direction: column;
  gap: 2.5rem;
}

.project {
  display: flex;
  gap: 1.5rem;
  align-items: flex-start;
}

.project img {
  width: 180px;
  height: 120px;
  object-fit: cover;
  border-radius: 8px;
}

.project-content h3 {
  margin: 0 0 0.5rem 0;
}

.project-content p {
  margin: 0;
}

@media (max-width: 768px) {
  .project {
    flex-direction: column;
  }

  .project img {
    width: 100%;
    height: 200px;
  }
}
</style>

---

## Unsupervised Learning on Global Weather Data

<div class="projects">
  <div class="project">
    <a href="/assets/img/projects/pad.png" target="_blank">
      <img src="/assets/img/projects/pad.png" alt="Unsupervised Learning on Global Weather Data preview">
    </a>
    <div class="project-content">
      <!-- <h3>Unsupervised Learning on Global Weather Data</h3> -->
      <p>
        Explored various unsupervised learning techniques on global weather data, including PCA, K-means clustering, c-means fuzzy clustering, and spectral clustering. Analysis revealed that the data naturally forms three smooth weather zones, rather than the five traditionally defined, an interesting insight into global climate patterns.
      </p>
    </div>
  </div>
</div>

---

## Video Dialog with Automatic Moment Detection

<div class="projects">
  <div class="project">
    <a href="/assets/img/projects/mpdw.png" target="_blank">
      <img src="/assets/img/projects/mpdw.png" alt="Video Dialog with Automatic Moment Detection preview">
    </a>
    <div class="project-content">
        <!-- <h3>Video Dialog with Automatic Moment Detection</h3> -->
      <p>
        Developed a chatbot for video moment identification. Leveraged CLIP embeddings for images and Llava LVLM to embed text and generate task descriptions. Aligned text and image embeddings, then implemented an algorithm to select relevant moments based on local maxima of semantic similarity, enabling the creation of short highlight videos from mined video segments.
      </p>
    </div>
  </div>
</div>

---

## Machine Learning for the Three-Body Problem

<div class="projects">
  <div class="project">
    <a href="/assets/img/projects/tbp.gif" target="_blank">
      <img src="/assets/img/projects/tbp.gif" alt="Machine Learning for the Three-Body Problem preview">
    </a>
    <div class="project-content">
      <!-- <h3>Machine Learning for the Three-Body Problem</h3> -->
      <p>
        Explored the classical three-body problem using machine learning. Built a full ML pipeline from data preparation to model selection, applying a range of techniques from simple regressions and K-Nearest Neighbors to XGBoost and deep learning models.  
        The goal was to predict the trajectories of three orbiting bodies, a system known for its chaotic dynamics and lack of a closed-form solution.
      </p>
    </div>
  </div>
</div>

---

## Open-Domain Conversational Search Retrieval Augmented Generation (RAG)

<div class="projects">
  <div class="project">
    <a href="/assets/img/projects/ri.png" target="_blank">
      <img src="/assets/img/projects/ri.png" alt="Open-Domain Conversational Search Retrieval Augmented Generation preview">
    </a>
    <div class="project-content">
      <!-- <h3>Open-Domain Conversational Search Retrieval Augmented Generation (RAG) </h3> -->
      <p>
        Developed an multi turn open-domain conversational search system with conversation memory. Applied BM25, LMD, BERT embeddings, and Llama 3 to retrieve and re-rank relevant documents, while query rewriting and generative models produced concise, context-aware responses across multiple conversation turns.
      </p>
    </div>
  </div>
</div>

---

## Scalable Cloud Backend Application

<div class="projects">
  <div class="project">
    <a href="/assets/img/projects/cloud.png" target="_blank">
      <img src="/assets/img/projects/cloud.png" alt="Scalable Cloud Backend Application preview">
    </a>
    <div class="project-content">
      <!-- <h3> Scalable Cloud Backend Application </h3> -->
      <p>
    Built a scalable, cloud-application backend for managing Lego Sets and user interactions. Leveraged Azure App Service, CosmosDB, Redis, Azure Functions, Cognitive Search, and Apache Spark for auctions, comments, media storage, and recommendations. Also developed a version possible to deploy on Kubernetes for containerized orchestration and avoiding vendor lock-in. Performed Artillery load testing. Automated tasks like geo-replication, auction closing, and caching with serverless functions.
      </p>
    </div>
  </div>
</div>