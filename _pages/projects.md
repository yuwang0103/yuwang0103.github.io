---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---

<div class="projects-intro" style="margin-bottom: 1.25rem;">
  <p>Selected project demos and research systems from KIND Lab.</p>
</div>

<style>
  .project-list {
    display: grid;
    gap: 1.35rem;
    margin-top: 1rem;
  }

  .project-card {
    display: grid;
    grid-template-columns: 230px minmax(0, 1fr);
    gap: 1rem;
    align-items: start;
    padding-bottom: 1.15rem;
    border-bottom: 1px solid #e5e7eb;
  }

  .project-card img {
    width: 230px;
    height: 130px;
    display: block;
    object-fit: cover;
    border: 1px solid #e5e7eb;
    border-radius: 6px;
  }

  .project-card h2 {
    margin: 0 0 0.45rem;
    font-size: 1.15rem;
    line-height: 1.28;
  }

  .project-card p {
    margin: 0 0 0.45rem;
    line-height: 1.45;
  }

  .project-links {
    margin-top: 0.55rem;
  }

  @media (max-width: 720px) {
    .project-card {
      grid-template-columns: 1fr;
    }

    .project-card img {
      width: 100%;
      max-width: 360px;
      height: auto;
    }
  }
</style>

<div class="project-list">
  <article class="project-card">
    <a href="https://kindlab-fly.github.io/projects/agentic-structured-drug-design/" target="_blank" rel="noopener noreferrer">
      <img src="/images/projects/agentic-drug-design.png" alt="Concept figure for agentic intelligence in structured drug design">
    </a>
    <div>
      <h2>
        <a href="https://kindlab-fly.github.io/projects/agentic-structured-drug-design/" target="_blank" rel="noopener noreferrer">Agentic Intelligence for Structured Drug Design</a>
      </h2>
      <p><strong>Faculty:</strong> Yu Wang, Eugene Douglass</p>
      <p><strong>Student:</strong> Zhisheng Qi</p>
      <p>An agentic drug-design demo that supports scaffold specification, scaffold sketching, and multi-constrained molecular property targets. Conditioned on these inputs, the system generates candidate molecules with calculated property feedback and supports multi-step comparison, critique, and refinement.</p>
      <p class="project-links">
        <a href="https://kindlab-fly.github.io/projects/agentic-structured-drug-design/" target="_blank" rel="noopener noreferrer">Project page</a> |
        <a href="https://drug-design.graphagentintelligence.com/" target="_blank" rel="noopener noreferrer">Live demo</a>
      </p>
    </div>
  </article>

  <article class="project-card">
    <a href="https://kindlab-fly.github.io/projects/nsf-III-GraphRAG/" target="_blank" rel="noopener noreferrer">
      <img src="/images/projects/agentic-structured-knowledge-retrieval.png" alt="Concept figure for agentic intelligence in structured knowledge retrieval">
    </a>
    <div>
      <h2>
        <a href="https://kindlab-fly.github.io/projects/nsf-III-GraphRAG/" target="_blank" rel="noopener noreferrer">Agentic Intelligence for Structured Knowledge Retrieval</a>
      </h2>
      <p><strong>Faculty:</strong> Yu Wang</p>
      <p><strong>Students:</strong> Zhisheng Qi, Yongjia Lei, Utkarsh Sahu</p>
      <p>An agentic structured-knowledge demo that retrieves, traverses, and verifies evidence across graphs, documents, tables, and knowledge bases for more grounded RAG.</p>
      <p class="project-links">
        <a href="https://kindlab-fly.github.io/projects/nsf-III-GraphRAG/" target="_blank" rel="noopener noreferrer">Project page</a> |
        <a href="https://graph-agent.graphagentintelligence.com/" target="_blank" rel="noopener noreferrer">Live demo</a>
      </p>
    </div>
  </article>
</div>
