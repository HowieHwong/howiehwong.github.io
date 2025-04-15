---
layout: normal
title: Toolkit&Dataset
---


<style>
.card-grid {
  display: grid;
  grid-template-columns: 1fr;
  gap: 30px;
  max-width: 900px;
  margin: auto;
}

.card {
  display: flex;
  background: #fdfde7;
  border: 1px solid #ccc;
  border-radius: 12px;
  overflow: hidden;
  box-shadow: 0 2px 8px rgba(0,0,0,0.1);
}

.card img {
  width: 280px;
  object-fit: cover;
}

.card-content {
  padding: 20px;
  display: flex;
  flex-direction: column;
  justify-content: center;
}

.card-title {
  font-weight: bold;
  font-size: 1.1em;
  margin-bottom: 8px;
}

.card-meta {
  font-size: 0.9em;
  color: #555;
  margin-bottom: 10px;
}

.card-links a {
  margin-right: 10px;
  font-size: 0.9em;
  color: #007acc;
  text-decoration: none;
}
</style>

<div class="card-grid">


<div class="card">
  <img src="/assets/img/metatool.png" alt="metatool">
  <div class="card-content">
    <div class="card-title">MetaTool</div>
    <div class="card-meta">Dataset | ICLR 2024 | A benchmark/dataset designed to evaluate whether LLMs have tool usage awareness and can correctly choose tools. </div>
    <div class="card-links">
      <a href="https://arxiv.org/abs/2310.03128">Paper</a>
      <a href="https://atlas.nomic.ai/map/a43a6a84-4453-428a-8738-2534d7bf0b89/b2b8134b-a37e-45d2-a0d9-765911f27df6/">Data Map</a>
      <a href="https://github.com/HowieHwong/MetaTool">Dataset</a>
    </div>
  </div>
</div>


<div class="card">
  <img src="/assets/img/datagen.png" alt="datagen">
  <div class="card-content">
    <div class="card-title">DataGen</div>
    <div class="card-meta">Toolkit | ICLR 2025 | DataGen is an LLM-powered framework designed to generate diverse, accurate, and highly controllable text datasets. </div>
    <div class="card-links">
      <a href="https://openreview.net/forum?id=F5R0lG74Tu">Paper</a>
      <a href="https://github.com/HowieHwong/UniGen">Toolkit</a>
    </div>
  </div>
</div>

<div class="card">
  <img src="/assets/img/trustllm.png" alt="trustllm">
  <div class="card-content">
    <div class="card-title">TrustLLM</div>
    <div class="card-meta">Toolkit | ICML 2024 | Trustllm (python package) help you assess the performance of your LLM in trustworthiness more quickly.</div>
    <div class="card-links">
      <a href="https://trustllmbenchmark.github.io/TrustLLM-Website/">Project Page</a>
      <a href="https://proceedings.mlr.press/v235/huang24x.html">Paper</a>
      <a href="https://github.com/HowieHwong/TrustLLM">Toolkit</a>
      <a href="https://howiehwong.github.io/TrustLLM/">Docs.</a>
      <a href="https://huggingface.co/datasets/TrustLLM/TrustLLM-dataset">Dataset</a>
    </div>
  </div>
</div>


<div class="card">
  <img src="/assets/img/trusteval.png" alt="trusteval">
  <div class="card-content">
    <div class="card-title">TrustEval</div>
    <div class="card-meta">Toolkit | NAACL 2025 Demo | TrustEval is a modular and extensible toolkit for comprehensive trust evaluation of generative foundation models (GenFMs). This toolkit enables you to evaluate models across various dimensions such as safety, fairness, robustness, privacy, and more.</div>
    <div class="card-links">
      <a href="https://trustgen.github.io/">Project Page</a>
      <a href="https://arxiv.org/abs/2502.14296">Paper</a>
      <a href="https://github.com/TrustGen/TrustEval-toolkit">Toolkit</a>
      <a href="https://trusteval-docs.readthedocs.io/en/latest/">Docs.</a>
    </div>
  </div>
</div>



</div>
