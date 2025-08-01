---
theme: default
title: Latest Trend on Software Development Techniques
info: |
  ## Latest Trend on Software Development Techniques

  A comprehensive overview of the latest techniques in software development,
  AI adoption, and engineering practices from ThoughtWorks Technology Radar Vol 32.
class: text-center
mdc: true
---

# Latest Trend on Software Development Techniques

---
layout: default
---

## Based on Technology Radar Vol 32, Techniques Section.

[Martin Fowler Blog](https://martinfowler.com/)

[ThoughtWorks Technology Radar](https://www.thoughtworks.com/radar)

[ThoughtWorks Technology Radar Techniques Section](https://www.thoughtworks.com/radar/techniques) 

[MB Technology Radar](https://mercedes-benz.leanix.net/MercedesBenz/reports/radar-itcomponent/c435eabd-03dd-433d-8849-9fadcdb9cf67)

---
layout: default
---

# What is Technology Radar?
An opinionated guide to today's technology landscape.

<div class="grid grid-cols-2 gap-12">
<div>


### Four Quadrants
- <badge color="blue" class="mt-2">Techniques</badge> - Development practices & methods
- <badge color="green" class="mt-2">Tools</badge> - Software development tools  
- <badge color="purple" class="mt-2">Platforms</badge> - Infrastructure & platforms
- <badge color="orange" class="mt-2">Languages & Frameworks</badge> - Programming languages & frameworks

<div class="mt-4">
</div>

### Recommendation Ring
- <badge color="green" class="mt-2">Adopt</badge> - Proven, should seriously consider
- <badge color="blue" class="mt-2">Trial</badge> - Ready for use, not completely proven
- <badge color="yellow" class="mt-2">Assess</badge> - Look at closely, evaluate fit
- <badge color="red" class="mt-2">Hold</badge> - Proceed with caution
</div>
<div>


<div class="flex justify-center">
<img src="/assets/technology-radar.png" style="width: 350px;" />
</div>

</div>

</div>

<style>
badge {
  @apply inline-block px-2 py-1 rounded text-sm font-medium;
}
badge[color="blue"] {
  @apply bg-blue-100 text-blue-800;
}
badge[color="green"] {
  @apply bg-green-100 text-green-800;
}
badge[color="purple"] {
  @apply bg-purple-100 text-purple-800;
}
badge[color="orange"] {
  @apply bg-orange-100 text-orange-800;
}
badge[color="yellow"] {
  @apply bg-yellow-100 text-yellow-800;
}
badge[color="red"] {
  @apply bg-red-100 text-red-800;
}

.technique-card {
  @apply p-4 bg-white rounded-xl shadow-sm hover:shadow-md transition-all duration-200 border border-gray-100;
}

.technique-card.adopt {
  @apply bg-gradient-to-r from-green-50 to-emerald-50 border-green-200;
}

.technique-card.trial {
  @apply bg-gradient-to-r from-blue-50 to-sky-50 border-blue-200;
}

.technique-card.assess {
  @apply bg-gradient-to-r from-yellow-50 to-amber-50 border-yellow-200;
}

.technique-card.hold {
  @apply bg-gradient-to-r from-red-50 to-rose-50 border-red-200;
}

.info-card {
  @apply p-4 bg-white rounded-lg shadow-sm border border-gray-100 hover:shadow-md transition-shadow duration-200;
}

.info-card.blue {
  @apply bg-gradient-to-r from-blue-50 to-sky-50 border-blue-200;
}

.info-card.green {
  @apply bg-gradient-to-r from-green-50 to-emerald-50 border-green-200;
}

.info-card.purple {
  @apply bg-gradient-to-r from-purple-50 to-violet-50 border-purple-200;
}

.info-card.orange {
  @apply bg-gradient-to-r from-orange-50 to-amber-50 border-orange-200;
}

.info-card.yellow {
  @apply bg-gradient-to-r from-yellow-50 to-amber-50 border-yellow-200;
}

.info-card.red {
  @apply bg-gradient-to-r from-red-50 to-rose-50 border-red-200;
}
</style>

---
layout: section
---

# Techniques Overview
*Focus on development practices and methodologies*

---

# Techniques Overview

<div class="grid grid-cols-2 gap-8">
<div>

## Adopt <span class="text-sm opacity-60">(4 techniques)</span>
<div class="space-y-2 mt-2">
  <div class="technique-card adopt">
    <div class="text-sm font-medium text-green-800">Data product thinking</div>
  </div>
  <div class="technique-card adopt">
    <div class="text-sm font-medium text-green-800">Fuzz testing</div>
  </div>
  <div class="technique-card adopt">
    <div class="text-sm font-medium text-green-800">Software Bill of Materials</div>
  </div>
  <div class="technique-card adopt">
    <div class="text-sm font-medium text-green-800">Threat modeling</div>
  </div>
</div>

<div class="text-sm mt-4 opacity-80">
</div>

## Trial <span class="text-sm opacity-60">(13 techniques)</span>
<div class="space-y-2 mt-2">
  <div class="technique-card trial">
    <div class="text-sm font-medium text-blue-800">API request collection as API product artifact</div>
  </div>
  <div class="technique-card trial">
    <div class="text-sm font-medium text-blue-800">Architecture advice process</div>
  </div>
  <div class="technique-card trial">
    <div class="text-sm font-medium text-blue-800">GraphRAG</div>
  </div>
  <div class="technique-card trial">
    <div class="text-sm font-medium text-blue-800">Just-in-time privileged access management</div>
  </div>
  <div class="technique-card trial">
    <div class="text-sm font-medium text-blue-800">Model distillation</div>
  </div>
  <div class="technique-card trial">
    <div class="text-sm font-medium text-blue-800">Prompt engineering</div>
  </div>
  <div class="technique-card trial">
    <div class="text-sm font-medium text-blue-800">Small language models</div>
  </div>
  <div class="technique-card trial">
    <div class="text-sm font-medium text-blue-800">Using GenAI to understand legacy codebases</div>
  </div>
</div>

</div>

<div>

## Assess <span class="text-sm opacity-60">(4 techniques)</span>
<div class="space-y-2 mt-2">
  <div class="technique-card assess">
    <div class="text-sm font-medium text-yellow-800">AI-friendly code design</div>
  </div>
  <div class="technique-card assess">
    <div class="text-sm font-medium text-yellow-800">AI-powered UI testing</div>
  </div>
  <div class="technique-card assess">
    <div class="text-sm font-medium text-yellow-800">Competence envelope as a model for understanding system failures</div>
  </div>
  <div class="technique-card assess">
    <div class="text-sm font-medium text-yellow-800">Structured output from LLMs</div>
  </div>
</div>

<div class="text-sm mt-4 opacity-80">
</div>

## Hold <span class="text-sm opacity-60">(6 techniques)</span>
<div class="space-y-2 mt-2">
  <div class="technique-card hold">
    <div class="text-sm font-medium text-red-800">AI-accelerated shadow IT</div>
  </div>
  <div class="technique-card hold">
    <div class="text-sm font-medium text-red-800">Complacency with AI code</div>
  </div>
  <div class="technique-card hold">
    <div class="text-sm font-medium text-red-800">Local coding assistants</div>
  </div>
  <div class="technique-card hold">
    <div class="text-sm font-medium text-red-800">Replacing pair programming with AI</div>
  </div>
  <div class="technique-card hold">
    <div class="text-sm font-medium text-red-800">Reverse ETL</div>
  </div>
  <div class="technique-card hold">
    <div class="text-sm font-medium text-red-800">SAFe™</div>
  </div>
</div>
</div>
</div>

---
layout: section
---

# Adopt
*We feel strongly that the industry should be adopting these items*

---
layout: two-cols
---

# Data Product Thinking
<div class="text-sm opacity-60 mb-4">Ring: Adopt</div>

## What is it?
- Treat **data** as a **product** with its own lifecycle
- Focus on **consumer needs** and quality standards  
- [Work backward from **use cases**](https://martinfowler.com/articles/designing-data-products.html)
- Comprehensive lifecycle management

## Key Benefits
- <carbon-chart-line class="inline text-blue-500" /> Improved data discoverability
- <carbon-security class="inline text-purple-500" /> Better governance and compliance
- <carbon-watson-machine-learning class="inline text-orange-500" /> AI-ready data preparation

::right::

<div class="text-sm mt-23 opacity-80">
</div>

## Implementation
<div class="space-y-2">
  <div class="info-card blue">
    <div class="font-semibold text-blue-800 mt-2">Modern Tools</div>
    <div class="text-sm">DataHub, Collibra, Atlan, Informatica</div>
  </div>
  
  <div class="info-card green">
    <div class="font-semibold text-green-800 mt-2">Data Domain</div>
    <div class="text-sm">Business & technical metadata</div>
  </div>
  
  <div class="info-card purple">
    <div class="font-semibold text-purple-800 mt-2">Approach</div>
    <div class="text-sm">Consumer-centric design</div>
  </div>
</div>

<div class="text-sm mt-4 opacity-80">
</div>

## Why Now?
<div class="mt-2 info-card orange">
  <div class="text-sm"><strong>Essential for scaling AI initiatives</strong> - Works with data mesh or lakehouse architectures</div>
</div>

---
layout: two-cols
---

# What are Data Products?

<div class="mt-10">
  <img src="/assets/data-product-left.png" style="width: 400px;" />
</div>

::right::

<div class="mt-20">
  <img src="/assets/data-product-right.png" style="width: 400px;" />
</div>

---
layout: image
---

# These are not Data Products!
<div class="flex justify-center">
  <img src="/assets/what-data-product-is-not.png" style="width: 800px;" />
</div>

---
layout: image
---

# Data Products
<div class="flex justify-center mt-10">
  <img src="/assets/data-product.png" style="width: 800px;" />
</div>

---
layout: two-cols
---

# Fuzz Testing
<div class="text-sm opacity-60 mb-4">Ring: Adopt</div>

## What is it?
- Feed software systems **invalid input**
- Observe behavior and responses
- Identify unexpected failures
- Long-standing technique gaining relevance

## Why Important Now?
<div class="space-y-3 mt-4">
  <div class="flex items-center gap-3">
    <carbon-ai-results class="text-red-500" />
    <span class="text-sm">More AI-generated code in production</span>
  </div>
  <div class="flex items-center gap-3">
    <carbon-warning-alt class="text-orange-500" />
    <span class="text-sm">Growing complacency with AI outputs</span>
  </div>
</div>

::right::

<div class="text-sm mt-23 opacity-80">
</div>

## Implementation
<div class="space-y-2">
  <div class="p-4 bg-red-50 rounded-lg mt-2">
    <div class="font-semibold text-red-800 mb-2">🌐 HTTP Endpoints</div>
    <div class="text-sm">Bad requests → expect 4xx, but getting 5xx errors</div>
  </div>
  
  <div class="p-4 bg-blue-50 rounded-lg mt-2">
    <div class="font-semibold text-blue-800 mb-2">🤖 Automation</div>
    <div class="text-sm">Automated fuzzing tools</div>
  </div>
  
  <div class="p-4 bg-green-50 rounded-lg mt-2">
    <div class="font-semibold text-green-800 mb-2">🔄 CI/CD</div>
    <div class="text-sm">Integration with pipelines</div>
  </div>
</div>

---
layout: two-cols
---

# Software Bill of Materials
<div class="text-sm opacity-60 mb-4">Ring: Adopt</div>

## Popular Tools
- Syft
- Trivy
- Snyk

## Why Critical?
<div class="space-y-2 mt-2">
  <div class="info-card red">
    <div class="text-sm font-semibold text-red-800">Supply Chain Security</div>
  </div>
  <div class="info-card orange">
    <div class="text-sm font-semibold text-orange-800">Vulnerability Management</div>
  </div>
  <div class="info-card blue">
    <div class="text-sm font-semibold text-blue-800">Compliance Requirements</div>
  </div>
  <div class="info-card purple">
    <div class="text-sm font-semibold text-purple-800">AI Systems Need SBOMs Too!</div>
  </div>
</div>

::right::

<div class="text-sm mt-65 opacity-80">
</div>

## Regulatory Support
- [UK Government's AI Cyber Security Code](https://www.gov.uk/government/publications/ai-cyber-security-code-of-practice)
- [CISA's AI Cybersecurity Collaboration Playbook](https://www.cisa.gov/resources-tools/resources/ai-cybersecurity-collaboration-playbook)

---
layout: two-cols
---

# Threat Modeling  
<div class="text-sm opacity-60 mb-4">Ring: Adopt</div>

## What is it?
- **Identify and classify** potential threats
- Regular practice throughout software lifecycle
- Works alongside other security practices
  - cross-functional security requirements to address common risks
  - automated security scanners for continuous monitoring
- Especially important as AI-driven development becomes more prevalent

::right::

<div class="text-sm mt-23 opacity-80">
</div>

## Why Essential?
<div class="mt-4 p-4 bg-gradient-to-r from-red-50 to-orange-50 rounded-lg border border-red-200">
  <div class="text-sm">Avoid the <strong>"security sandwich"</strong> anti-pattern while maintaining agility</div>
</div>

<div class="text-sm mt-4 opacity-80">
</div>

## What is Security Sandwich?
- Traditonally, security is relied on up-front specification followed by validation at the end.
- This “Security Sandwich” approach is hard to integrate into Agile teams, since much of the design happens throughout the process, and it does not leverage the automation opportunities provided by continuous delivery.

---
layout: image
---

## STRIDE as a Practical Aid
<div class="text-center mt-10">
  <img src="/assets/stride.png" width="500" class="mx-auto" />
    <a href="https://martinfowler.com/articles/agile-threat-modelling/TW_STRIDE_Cue_Cards.pdf" target="_blank" class="text-sm">
      STRIDE cards
    </a>
</div>


---
layout: section
---

# Trial
*Worth pursuing - ready for use but not completely proven*

---
layout: two-cols
---

# API Request Collection as Product Artifact
<div class="text-sm opacity-60 mb-4">Ring: Trial</div>

## Concept
- Treat API collections as **API product artifacts**
- Guide developers through key workflows
- Stored in repository, integrated in release pipeline
- Part of comprehensive API-as-a-product strategy

## Benefits
<div class="space-y-2 mt-4">
  <div class="flex items-center gap-2">
    <carbon-rocket class="text-blue-500" />
    <span class="text-sm">Rapid developer onboarding</span>
  </div>
  <div class="flex items-center gap-2">
    <carbon-code class="text-green-500" />
    <span class="text-sm">Working examples with auth</span>
  </div>
  <div class="flex items-center gap-2">
    <carbon-data-base class="text-purple-500" />
    <span class="text-sm">Realistic test data</span>
  </div>
</div>

::right::

<div class="text-sm mt-32 opacity-80">
</div>

## Implementation
<div class="space-y-4">
  <div class="p-4 bg-blue-50 rounded-lg">
    <div class="font-semibold text-blue-800 mb-2">Tools</div>
    <div class="flex gap-2">
      <span class="px-2 py-1 bg-blue-200 rounded text-xs">Postman</span>
      <span class="px-2 py-1 bg-green-200 rounded text-xs">Bruno</span>
      <span class="px-2 py-1 bg-purple-200 rounded text-xs">Insomnia</span>
    </div>
  </div>
  
  <div class="p-4 bg-green-50 rounded-lg">
    <div class="font-semibold text-green-800 mb-2">📦 Repository Strategy</div>
    <div class="text-sm">Version control alongside code</div>
  </div>
  
  <div class="p-4 bg-orange-50 rounded-lg">
    <div class="font-semibold text-orange-800 mb-2">🔄 CI/CD Integration</div>
    <div class="text-sm">Keep collections up-to-date automatically</div>
  </div>
</div>

---
layout: two-cols
---

# Architecture Advice Process
<div class="text-sm opacity-60 mb-4">Ring: Trial</div>

<div class="mr-8">

## Problem with ARBs
<div class="p-3 mr-8 bg-red-50 rounded-lg red">
  <div class="text-sm">Architecture Review Boards create bottlenecks and hinder workflow</div>
</div>

<div class="text-sm mt-10 opacity-80">
</div>

## Key Benefits
<div class="space-y-2 mt-4">
  <div class="flex items-center gap-2">
    <carbon-flow class="text-blue-500" />
    <span class="text-sm">Optimize development flow without compromising architectural quality</span>
  </div>
  <div class="flex items-center gap-2">
    <carbon-group class="text-green-500" />
    <span class="text-sm">Collaborative decision making</span>
  </div>
</div>
</div>

::right::

## How It Works
<div class="space-y-2">
  <div class="p-4 bg-blue-50 rounded-lg">
    <div class="font-semibold text-blue-800">1. Decision Records</div>
    <div class="text-sm">A structured doc capturing the proposed decision, advice gathered, alternatives considered, and final outcomes.</div>
  </div>
  
  <div class="p-4 bg-green-50 rounded-lg">
    <div class="font-semibold text-green-800">Architecture Advisory Forum (AAF)</div>
    <div class="text-sm">A regular (e.g. weekly) open meeting where ADRs and decisions are discussed publicly. It includes representatives across teams (e.g. product, infra, compliance), promoting transparency and common understanding.</div>
  </div>
  
  <div class="p-4 bg-purple-50 rounded-lg">
    <div class="font-semibold text-purple-800">3. Team-sourced Architectural Principles</div>
    <div class="text-sm">Guiding standards created collaboratively by delivery teams to steer decisions and help identify principle‑conflicts in ADRs.</div>
  </div>
  
  <div class="p-4 bg-orange-50 rounded-lg">
    <div class="font-semibold text-orange-800">4. Technology Radar</div>
    <div class="text-sm">A curated, organizational view of current and emerging technologies, informing and evolving the shared tech landscape.</div>
  </div>
</div>

---
layout: image
---
<div class="flex justify-center">
  <img src="/assets/elements-of-an-adr.png" style="width: 700px;" />
</div>

---
layout: two-cols
---

# GraphRAG
<div class="text-sm opacity-60 mb-4">Ring: Trial</div>

## What is GraphRAG?
- **Graph + Retrieval Augmented Generation**
- Enhanced knowledge representation using graph structures
- Better context understanding for AI systems
- Improved multi-hop reasoning capabilities

## Key Advantages
<div class="space-y-3 mt-4">
  <div class="flex items-center gap-3">
    <carbon-network-3 class="text-blue-500" />
    <span class="text-sm">Relationship-aware retrieval</span>
  </div>
  <div class="flex items-center gap-3">
    <carbon-tree-view class="text-green-500" />
    <span class="text-sm">Multi-hop reasoning support</span>
  </div>
  <div class="flex items-center gap-3">
    <carbon-connect class="text-purple-500" />
    <span class="text-sm">Enhanced knowledge connections</span>
  </div>
</div>

::right::

## Implementation Approach
<div class="space-y-2 mt-4">
  <div class="p-4 bg-blue-50 rounded-lg">
    <div class="font-semibold text-blue-800 mb-2">Graph Construction</div>
    <div class="text-sm">Build knowledge graphs from your data</div>
  </div>
  
  <div class="p-4 bg-green-50 rounded-lg">
    <div class="font-semibold text-green-800 mb-2">Enhanced Retrieval</div>
    <div class="text-sm">Traverse graph relationships for context</div>
  </div>
  
  <div class="p-4 bg-purple-50 rounded-lg">
    <div class="font-semibold text-purple-800 mb-2">AI Integration</div>
    <div class="text-sm">Feed enriched context to language models</div>
  </div>
</div>

<div class="text-sm mt-4 opacity-80">
</div>

## Use Cases
<div class="mt-2 text-xs space-y-1 opacity-80">
  <div>• Complex document understanding</div>
  <div>• Knowledge base question answering</div>
  <div>• Research and analysis tasks</div>
</div>

---
layout: image
---
<div class="flex justify-center mt-20">
  <img src="/assets/graph-rag.png" style="width: 700px;" />
</div>

---
layout: two-cols
---

# Just-in-Time Privileged Access Management
<div class="text-sm opacity-60 mb-4">Ring: Trial</div>

## Concept
- **Temporary elevated permissions**
- Grant access only when needed, for limited time
- Reduced attack surface and blast radius
- Zero-trust security model implementation

## Security Benefits
<div class="space-y-3 mt-4">
  <div class="flex items-center gap-3">
    <carbon-locked class="text-red-500" />
    <span class="text-sm">Minimized standing privileges</span>
  </div>
  <div class="flex items-center gap-3">
    <carbon-time class="text-blue-500" />
    <span class="text-sm">Time-bounded access</span>
  </div>
  <div class="flex items-center gap-3">
    <carbon-security class="text-green-500" />
    <span class="text-sm">Comprehensive audit trail</span>
  </div>
</div>

::right::

## Implementation
<div class="space-y-4 mt-4">
  <div class="p-4 bg-red-50 rounded-lg">
    <div class="font-semibold text-red-800 mb-2">Principle of Least Privilege</div>
    <div class="text-sm">Default to minimal permissions</div>
  </div>
  
  <div class="p-4 bg-blue-50 rounded-lg">
    <div class="font-semibold text-blue-800 mb-2">Time-bound Access</div>
    <div class="text-sm">Automatically expire elevated permissions</div>
  </div>
  
  <div class="p-4 bg-green-50 rounded-lg">
    <div class="font-semibold text-green-800 mb-2">Approval Workflows</div>
    <div class="text-sm">Require justification and approval</div>
  </div>
  
  <div class="p-4 bg-purple-50 rounded-lg">
    <div class="font-semibold text-purple-800 mb-2">Monitoring</div>
    <div class="text-sm">Real-time access monitoring and alerting</div>
  </div>
</div>

---
layout: two-cols
---

# Model Distillation
<div class="text-sm opacity-60 mb-4">Ring: Trial</div>

## What is Model Distillation?
- Transfer knowledge from **large teacher models** to **smaller student models**
- Enables **on-device inference** and cost-effective deployment
- Retains critical domain knowledge with **minimal accuracy loss**

## Why It Matters
<div class="space-y-3 mt-4">
  <div class="flex items-center gap-3">
    <carbon-flash-filled class="text-yellow-500" />
    <span class="text-sm">Faster, low-latency inference</span>
  </div>
  <div class="flex items-center gap-3">
    <carbon-money class="text-green-500" />
    <span class="text-sm">Reduces cloud and compute costs</span>
  </div>
  <div class="flex items-center gap-3">
    <carbon-chip class="text-blue-500" />
    <span class="text-sm">Runs on edge and consumer devices</span>
  </div>
</div>

::right::

<div class="text-sm ml-8 mt-14">

## How It Works
<div class="space-y-4 mt-4">
  <div class="p-4 bg-blue-50 rounded-lg">
    <div class="font-semibold text-blue-800 mb-2">1. Teacher Model</div>
    <div class="text-sm">High-capacity model generates sample outputs or logits</div>
  </div>
  
  <div class="p-4 bg-green-50 rounded-lg">
    <div class="font-semibold text-green-800 mb-2">2. Student Model</div>
    <div class="text-sm">Lightweight model learns to replicate teacher behavior</div>
  </div>
  
  <div class="p-4 bg-purple-50 rounded-lg">
    <div class="font-semibold text-purple-800 mb-2">3. Distillation Process</div>
    <div class="text-sm">Train student using teacher’s outputs</div>
  </div>
  
  <div class="p-4 bg-orange-50 rounded-lg">
    <div class="font-semibold text-orange-800 mb-2">4. Optimization</div>
    <div class="text-sm">Can be combined with quantization or pruning for added efficiency</div>
  </div>
</div>

</div>

---
layout: image
---
<div class="flex justify-center">
  <img src="/assets/model-distillation.png" style="width: 700px;" />
</div>

---
layout: two-cols
---

# Prompt Engineering
<div class="text-sm opacity-60 mb-4">Ring: Trial</div>

## What is Prompt Engineering?
<div class="text-md opacity-80 mt-2">

- Designing and refining prompts for for generative AI models to produce high-quality, context-aware responses
</div>

<div class="text-md opacity-80">

- Helps mitigate hallucinations and improve response quality
</div>

<div class="text-md mt-10 opacity-80">
</div>

## Key Techniques
<div class="space-y-3 mt-4">
  <div class="flex items-center gap-3">
    <carbon-document-tasks class="text-blue-500" />
    <span class="text-sm">Few-shot learning examples</span>
  </div>
  <div class="flex items-center gap-3">
    <carbon-flow class="text-green-500" />
    <span class="text-sm">Chain-of-thought reasoning</span>
  </div>
  <div class="flex items-center gap-3">
    <carbon-settings class="text-purple-500" />
    <span class="text-sm">Parameter optimization</span>
  </div>
</div>

::right::

## Insights
<div class="space-y-2 mt-4">
  <div class="p-4 bg-blue-50 rounded-lg">
    <div class="font-semibold text-blue-800 mb-2">Zero-shot > Few-shot?</div>
    <div class="text-sm">With reasoning models, fewer examples may perform better.</div>
  </div>
  
  <div class="p-4 bg-green-50 rounded-lg">
    <div class="font-semibold text-green-800 mb-2">CoT Limitations</div>
    <div class="text-sm">Chain-of-thought may hinder models already tuned for reasoning.</div>
  </div>
  
  <div class="p-4 bg-purple-50 rounded-lg">
    <div class="font-semibold text-purple-800 mb-2">Strategic Model Choice</div>
    <div class="text-sm">Balance output quality, latency, and token cost for your use case.</div>
  </div>
  
  <div class="p-4 bg-orange-50 rounded-lg">
    <div class="font-semibold text-orange-800 mb-2">Prompt Engineering’s Evolving Role</div>
    <div class="text-sm">Still critical for hallucination control and agentic application design.</div>
  </div>
</div>


---
layout: two-cols
---

# Small Language Models
<div class="text-sm opacity-60 mb-4">Ring: Trial</div>

## Advantages
<div class="space-y-3 mt-4">
  <div class="flex items-center gap-3">
    <carbon-chip class="text-blue-500" />
    <span class="text-sm">Lower resource consumption</span>
  </div>
  <div class="flex items-center gap-3">
    <carbon-security class="text-green-500" />
    <span class="text-sm">Enhanced privacy (local deployment)</span>
  </div>
  <div class="flex items-center gap-3">
    <carbon-flash class="text-yellow-500" />
    <span class="text-sm">Faster response times</span>
  </div>
  <div class="flex items-center gap-3">
    <carbon-money class="text-purple-500" />
    <span class="text-sm">Cost-effective scaling</span>
  </div>
</div>

::right::

<div class="text-sm mt-18">
</div>

## Use Cases
<div class="space-y-2 mt-2">
  <div class="p-4 bg-blue-50 rounded-lg">
    <div class="font-semibold text-blue-800 mb-2">Text Classification</div>
    <div class="text-sm">Sentiment analysis, content categorization</div>
  </div>
  
  <div class="p-4 bg-green-50 rounded-lg">
    <div class="font-semibold text-green-800 mb-2">Named Entity Recognition</div>
    <div class="text-sm">Extract specific information from text</div>
  </div>
  
  <div class="p-4 bg-purple-50 rounded-lg">
    <div class="font-semibold text-purple-800 mb-2">Code Completion</div>
    <div class="text-sm">IDE integrations and autocomplete</div>
  </div>
  
  <div class="p-4 bg-orange-50 rounded-lg">
    <div class="font-semibold text-orange-800 mb-2">Domain Assistants</div>
    <div class="text-sm">Specialized customer service bots</div>
  </div>
</div>

---
layout: two-cols
---

<div class="mr-8">

# Using GenAI to Understand Legacy Codebases
<div class="text-sm opacity-60 mb-4">Ring: Trial</div>

## The Challenge
- **Complex legacy systems** with poor documentation
- Knowledge gaps when original developers leave
- Difficult to understand interconnections
- Migration and modernization risks
</div>

::right::

<div class="text-sm mt-43 ml-8">

## GenAI Solutions
<div class="space-y-2 mt-2">
  <div class="flex items-center gap-2">
    <carbon-document class="text-blue-500" />
    <span class="text-sm">Automated code documentation</span>
  </div>
  <div class="flex items-center gap-2">
    <carbon-flow class="text-green-500" />
    <span class="text-sm">Business logic explanation</span>
  </div>
  <div class="flex items-center gap-2">
    <carbon-network-3 class="text-purple-500" />
    <span class="text-sm">Dependency mapping</span>
  </div>
</div>
</div>

---
layout: section
---

# Assess
*Look at closely, but not necessarily trial yet*

---
layout: two-cols
---

# AI-Friendly Code Design
<div class="text-sm opacity-60 mb-4">Ring: Assess • Focus: Code Quality</div>

## Core Concept
- **Structure code for AI understanding**
- Improve AI assistant effectiveness
- Better documentation and naming conventions
- Modular, well-organized architecture

## Key Principles
<div class="space-y-3 mt-4">
  <div class="flex items-center gap-3">
    <carbon-document class="text-blue-500" />
    <span class="text-sm">Comprehensive inline documentation</span>
  </div>
  <div class="flex items-center gap-3">
    <carbon-tag class="text-green-500" />
    <span class="text-sm">Descriptive naming conventions</span>
  </div>
  <div class="flex items-center gap-3">
    <carbon-cube class="text-purple-500" />
    <span class="text-sm">Modular function design</span>
  </div>
</div>

::right::

## Implementation Strategies
<div class="space-y-2 mt-2">
  <div class="p-4 bg-blue-50 rounded-lg mt-2">
    <div class="font-semibold text-blue-800">Self-Documenting Code</div>
    <div class="text-sm">Write code that explains its purpose clearly</div>
  </div>
  
  <div class="p-4 bg-green-50 rounded-lg mt-2">
    <div class="font-semibold text-green-800">Clear Patterns</div>
    <div class="text-sm">Use consistent architectural patterns</div>
  </div>
  
  <div class="p-4 bg-purple-50 rounded-lg mt-2">
    <div class="font-semibold text-purple-800">Explicit Dependencies</div>
    <div class="text-sm">Make relationships between components clear</div>
  </div>
</div>

<div class="text-sm mt-10">
</div>

## Benefits
<div class="mt-4 p-3 bg-gradient-to-r from-blue-50 to-green-50 rounded-lg border border-blue-200">
  <div class="text-sm">Better AI code understanding → More accurate suggestions and refactoring</div>
</div>

---
layout: two-cols
---

# AI-Powered UI Testing
<div class="text-sm opacity-60 mb-4">Ring: Assess • Focus: Test Automation</div>

## What is it?
- **Automated UI test generation** using AI
- Natural language test descriptions
- Visual regression detection capabilities
- Reduced manual testing effort
- Useful for testing legacy applications with missing selectors or applications that frequently change labels and click paths


## AI Capabilities
<div class="space-y-3 mt-4">
  <div class="flex items-center gap-3">
    <carbon-view class="text-blue-500" />
    <span class="text-sm">Visual element recognition</span>
  </div>
  <div class="flex items-center gap-3">
    <carbon-chat class="text-green-500" />
    <span class="text-sm">Natural language test creation</span>
  </div>
  <div class="flex items-center gap-3">
    <carbon-image-search class="text-purple-500" />
    <span class="text-sm">Screenshot comparison</span>
  </div>
</div>

::right::

<div class="text-sm mt-23 ml-8">

## Current Limitations
<div class="space-y-2 mt-2">
  <div class="info-card yellow mt-2">
    <div class="font-semibold text-yellow-800">Reliability Concerns</div>
    <div class="text-sm">AI-generated tests may be flaky</div>
  </div>
  
  <div class="info-card orange mt-2">
    <div class="font-semibold text-orange-800">Context Understanding</div>
    <div class="text-sm">Limited business logic understanding</div>
  </div>
  
  <div class="info-card red mt-2">
    <div class="font-semibold text-red-800">Maintenance</div>
    <div class="text-sm">Still requires human oversight</div>
  </div>
</div>
</div>

---
layout: default
---

# Competence Envelope as a Model for Understanding System Failures
<div class="text-sm opacity-60 mb-4">Ring: Assess • Focus: System Reliability</div>

## Concept
- **competence envelope** — the boundary within which a system can function robustly in the face of failure
- Predict potential failure modes
- Improve overall system reliability
- **Residuality theory** - deliberately introducing stressors and analyzing how the system has adapted to historical stressors over time


---
layout: two-cols
---

# Structured Output from LLMs
<div class="text-sm opacity-60 mb-4">Ring: Assess • Focus: AI Integration</div>

## What is it?
<div class="text-md opacity-80">

- **Constrain model responses** to specific formats
</div>

<div class="text-md opacity-80">

- JSON Schema, Pydantic, Zod object definitions
</div>

<div class="text-md opacity-80">

- Reduce hallucinations and improve reliability
</div>

<div class="text-md opacity-80">

- **Enable better function calling and API interactions**
</div>

## Key Benefits
<div class="space-y-3 mt-4">
  <div class="flex items-center gap-3">
    <carbon-checkmark class="text-green-500" />
    <span class="text-sm">Guaranteed output format</span>
  </div>
  <div class="flex items-center gap-3">
    <carbon-data-structured class="text-blue-500" />
    <span class="text-sm">Better API integration</span>
  </div>
  <div class="flex items-center gap-3">
    <carbon-warning-alt-filled class="text-orange-500" />
    <span class="text-sm">Reduced hallucinations</span>
  </div>
</div>

::right::

<div class="ml-8">

## Implementation Examples
<div class="space-y-2 mt-2">
  <div class="p-4 bg-green-50 rounded-lg">
    <div class="font-semibold text-green-800 mb-2">JSON Schema</div>
    <div class="text-sm">Define exact structure requirements</div>
  </div>
  
  <div class="p-4 bg-blue-50 rounded-lg">
    <div class="font-semibold text-blue-800 mb-2">Pydantic Models</div>
    <div class="text-sm">Python data validation and parsing</div>
  </div>
  
  <div class="p-4 bg-purple-50 rounded-lg">
    <div class="font-semibold text-purple-800 mb-2">Zod Objects</div>
    <div class="text-sm">TypeScript-first schema validation</div>
  </div>
  
  <div class="p-4 bg-orange-50 rounded-lg">
    <div class="font-semibold text-orange-800 mb-2">Function Calling</div>
    <div class="text-sm">Enable AI to use tools and APIs</div>
  </div>
</div>

<div class="text-sm mt-4 opacity-80">
</div>

## Current Status
<div class="mt-2 text-sm">
  <span class="font-semibold">OpenAI now supports</span> structured output natively
</div>
</div>

---
layout: section
---

# Hold
*Proceed with caution*

---
layout: two-cols
---

# AI-Accelerated Shadow IT
<div class="text-sm opacity-60 mb-4">Ring: Hold • Risk: High</div>

## The Problem
<div class="text-md opacity-80">

- **Non-coders building software** with AI assistance
</div>

<div class="text-md opacity-80">

- No-code platforms + AI API integration
</div>

<div class="text-md opacity-80">

- Ungoverned, potentially insecure applications
</div>

<div class="text-md opacity-80">

- Data scattered across more systems
</div>

<div class="text-sm mt-10 opacity-80">
</div>

## Examples of Risk
<div class="space-y-3 mt-4">
  <div class="flex items-center gap-3">
    <carbon-chat class="text-red-500" />
    <span class="text-sm">Chat messages → ERP API calls via AI</span>
  </div>
  <div class="flex items-center gap-3">
    <carbon-application class="text-orange-500" />
    <span class="text-sm">Internal utility apps by non-developers</span>
  </div>
  <div class="flex items-center gap-3">
    <carbon-flow class="text-yellow-500" />
    <span class="text-sm">AI as "duct tape" for integrations</span>
  </div>
</div>

::right::

<div class="text-sm mt-23 opacity-80">
</div>

## Risks and Concerns
<div class="space-y-2">
  <div class="info-card red mt-2">
    <div class="font-semibold text-red-800">Security Vulnerabilities</div>
    <div class="text-sm">Ungoverned applications with poor security</div>
  </div>
  
  <div class="info-card orange mt-2">
    <div class="font-semibold text-orange-800">Data Sprawl</div>
    <div class="text-sm">Information scattered across systems</div>
  </div>
</div>

<div class="text-sm mt-10 opacity-80">
</div>

## Recommendation
<div class="mt-4 p-3 bg-red-100 rounded-lg border border-red-300">
  <div class="text-sm"><strong>Carefully weigh</strong> rapid problem-solving vs. long-term stability</div>
</div>

---
layout: two-cols
---

# Complacency with AI-Generated Code
<div class="text-sm opacity-60 mb-4">Ring: Hold • Risk: Code Quality</div>

## Research Evidence
<div class="text-md opacity-80">

- **GitClear 2024 data**: Increased duplicate code and churn
</div>

<div class="text-md opacity-80">

- **Declining refactoring** activity in commit histories
</div>

<div class="text-md opacity-80">

- **Microsoft research**: AI confidence ↑ critical thinking ↓ 
</div>

<div class="text-md opacity-80">

- **"Vibe coding"** - minimal review of AI output
</div>

<div class="text-sm mt-4 opacity-80">
</div>

## Quality Concerns
<div class="space-y-2 mt-2">
  <div class="flex items-center gap-3">
    <carbon-copy class="text-red-500" />
    <span class="text-sm">More duplicate code</span>
  </div>
  <div class="flex items-center gap-3">
    <carbon-renew class="text-orange-500" />
    <span class="text-sm">Increased code churn</span>
  </div>
  <div class="flex items-center gap-3">
    <carbon-tools class="text-yellow-500" />
    <span class="text-sm">Less refactoring activity</span>
  </div>
</div>

::right::

<div class="text-sm mt-33 opacity-80 ml-8">

## Specific Risks
<div class="space-y-2">
  <div class="info-card red mt-2">
    <div class="font-semibold text-red-800">Skill Atrophy</div>
    <div class="text-sm">Loss of critical thinking and code review skills</div>
  </div>
  
  <div class="info-card orange mt-2">
    <div class="font-semibold text-orange-800">Large Change Sets</div>
    <div class="text-sm">AI agents generate code too large to review properly</div>
  </div>
  
  <div class="info-card yellow mt-2">
    <div class="font-semibold text-yellow-800">Inappropriate Use</div>
    <div class="text-sm">"Vibe coding" acceptable for prototypes, not production</div>
  </div>
</div>

<div class="text-sm mt-10 opacity-80">
</div>

## Strong Caution
<div class="mt-4 p-3 bg-red-100 rounded-lg border border-red-300">
  <div class="text-sm"><strong>Maintain rigorous review</strong> processes for production code</div>
</div>
</div>

---
layout: two-cols
---

# Local Coding Assistants
<div class="text-sm opacity-60 mb-4">Ring: Hold • Risk: Limited Capability</div>

## Why Organizations Want This
- **Code confidentiality concerns** with cloud AI
- No external data transmission
- Complete control over AI processing
- Compliance with security policies

## Current Limitations
<div class="space-y-3 mt-4">
  <div class="flex items-center gap-3">
    <carbon-chip class="text-red-500" />
    <span class="text-sm">Smaller, less capable models</span>
  </div>
  <div class="flex items-center gap-3">
    <carbon-warning class="text-orange-500" />
    <span class="text-sm">Limited context windows</span>
  </div>
  <div class="flex items-center gap-3">
    <carbon-tools class="text-yellow-500" />
    <span class="text-sm">No tool integrations</span>
  </div>
</div>

::right::

<div class="text-sm mt-23 opacity-80">
</div>

## What Works Locally
<div class="space-y-2">
  <div class="info-card green mt-2">
    <div class="font-semibold text-green-800">Code Completion</div>
    <div class="text-sm">Xcode predictive completion, JetBrains full-line</div>
  </div>
  
  <div class="info-card blue mt-2">
    <div class="font-semibold text-blue-800">Simple Queries</div>
    <div class="text-sm">Basic coding questions and syntax help</div>
  </div>
  
  <div class="info-card purple mt-2">
    <div class="font-semibold text-purple-800">Tools Available</div>
    <div class="text-sm">Continue with Ollama, Qwen Coder</div>
  </div>
</div>

<div class="text-sm mt-10 opacity-80">
</div>

## Recommendation
<div class="mt-4 p-3 bg-yellow-100 rounded-lg border border-yellow-300">
  <div class="text-sm"><strong>Proceed with low expectations</strong> - significant capability gap vs. cloud</div>
</div>

---
layout: two-cols
---

# Replacing Pair Programming with AI
<div class="text-sm opacity-60 mb-4">Ring: Hold • Risk: Team Collaboration</div>

## The Question
- Can AI provide the same benefits as human pairing?
- GitHub Copilot calls itself "your AI pair programmer"
- Tempting to replace human collaboration with AI

## What AI Provides
<div class="space-y-3 mt-4">
  <div class="flex items-center gap-3">
    <carbon-idea class="text-green-500" />
    <span class="text-sm">Help getting unstuck</span>
  </div>
  <div class="flex items-center gap-3">
    <carbon-education class="text-blue-500" />
    <span class="text-sm">Learning new technologies</span>
  </div>
  <div class="flex items-center gap-3">
    <carbon-rocket class="text-purple-500" />
    <span class="text-sm">Faster tactical work</span>
  </div>
</div>

::right::

<div class="text-sm mt-33 opacity-80">
</div>

## What AI Cannot Provide
<div class="space-y-2">
  <div class="info-card red mt-2">
    <div class="font-semibold text-red-800">Team Collaboration</div>
    <div class="text-sm">No knowledge sharing between team members</div>
  </div>
  
  <div class="info-card orange mt-2">
    <div class="font-semibold text-orange-800">Process Benefits</div>
    <div class="text-sm">Low WIP, reduced handoffs, continuous integration</div>
  </div>
  
  <div class="info-card yellow mt-2">
    <div class="font-semibold text-yellow-800">Collective Ownership</div>
    <div class="text-sm">Shared understanding of codebase architecture</div>
  </div>
</div>

<div class="text-sm mt-10 opacity-80">
</div>

## Key Point
<div class="mt-4 p-3 bg-red-100 rounded-lg border border-red-300">
  <div class="text-sm">AI helps <strong>individuals</strong>, pair programming helps <strong>teams</strong></div>
</div>

---
layout: two-cols
---

# Reverse ETL
<div class="text-sm opacity-60 mb-4">Ring: Hold • Risk: Architecture</div>

## What is Reverse ETL?
- Moving data **back** from analytics systems to transaction systems
- Opposite direction of traditional ETL
- Can be legitimate in transitional architectures
- Often used to centralize business logic

## Legitimate Use Cases
<div class="space-y-3 mt-4">
  <div class="flex items-center gap-3">
    <carbon-data-connected class="text-green-500" />
    <span class="text-sm">Multi-source data aggregation</span>
  </div>
  <div class="flex items-center gap-3">
    <carbon-migrate class="text-blue-500" />
    <span class="text-sm">Transitional architecture patterns</span>
  </div>
</div>

::right::

<div class="text-sm mt-23 opacity-80">
</div>

## Why Hold?
<div class="space-y-2">
  <div class="info-card red mt-2">
    <div class="font-semibold text-red-800">Centralization Anti-pattern</div>
    <div class="text-sm">Vendors use it to move business logic to their platform</div>
  </div>
  
  <div class="info-card orange mt-2">
    <div class="font-semibold text-orange-800">Data Architecture Issues</div>
    <div class="text-sm">Exacerbates problems of centralized data platforms</div>
  </div>
  
  <div class="info-card yellow mt-2">
    <div class="font-semibold text-yellow-800">Complexity Growth</div>
    <div class="text-sm">Creates sprawling, hard-to-manage data flows</div>
  </div>
</div>

<div class="text-sm mt-10 opacity-80">
</div>

## Recommendation
<div class="mt-4 p-3 bg-red-100 rounded-lg border border-red-300">
  <div class="text-sm"><strong>Exercise extreme caution</strong> when introducing reverse ETL flows</div>
</div>

---
layout: two-cols
---

# SAFe™ (Scaled Agile Framework)
<div class="text-sm opacity-60 mb-4">Ring: Hold • Focus: Agile</div>

## Why Organizations Adopt SAFe
- **Complexity of becoming agile** at scale
- Hope for a "simple, process-based shortcut"
- Framework promises structure and governance
- Widespread industry adoption

## Observed Problems
<div class="space-y-2 mt-2">
  <div class="flex items-center gap-2">
    <carbon-roadmap class="text-red-500" />
    <span class="text-sm">Over-standardized, phase-gated processes</span>
  </div>
  <div class="flex items-center gap-2">
    <carbon-group class="text-orange-500" />
    <span class="text-sm">Promotes silos between teams</span>
  </div>
  <div class="flex items-center gap-2">
    <carbon-arrow-down class="text-yellow-500" />
    <span class="text-sm">Top-down control creates waste</span>
  </div>
  <div class="flex items-center gap-2">
    <carbon-arrow-down class="text-yellow-500" />
    <span class="text-sm">Discourages engineering talent creativity</span>
  </div>
</div>

::right::

<div class="text-sm opacity-80">
</div>

<div class="pl-8 mt-33">

## Recommendation
<div class="mt-2 p-2 bg-yellow-100 rounded-lg border border-yellow-300">
  <div class="text-sm"><strong><a href="https://www.thoughtworks.com/insights/blog/digital-transformation/how-value-slices-can-fix-your-digital-transformation">Leaner, value-driven approaches</a></strong> with comprehensive change programs</div>
</div>

<div class="text-sm mt-4 opacity-80">
</div>

### SAFe Big Picture

<img src=/assets/safe.png width="400" class="" />
</div>

---
layout: two-cols
---

## Value Slice
<img src=/assets/value-slice.png width="500" class="mt-20" />

::right::

<img src=/assets/value-slice-2.png width="500" class="mt-40" />



---
layout: center
class: text-center
---

# Questions & Discussion

<div class="text-xl opacity-80 mb-8">
</div>

<div class="flex justify-center gap-8 mb-8">
  <div class="text-center">
    <carbon-document class="text-4xl text-blue-500 mb-2" />
    <div class="text-sm">27 Techniques</div>
  </div>
  <div class="text-center">
    <carbon-checkmark class="text-4xl text-green-500 mb-2" />
    <div class="text-sm">4 Adopt</div>
  </div>
  <div class="text-center">
    <carbon-chemistry class="text-4xl text-blue-500 mb-2" />
    <div class="text-sm">13 Trial</div>
  </div>
  <div class="text-center">
    <carbon-view class="text-4xl text-yellow-500 mb-2" />
    <div class="text-sm">4 Assess</div>
  </div>
  <div class="text-center">
    <carbon-warning class="text-4xl text-red-500 mb-2" />
    <div class="text-sm">6 Hold</div>
  </div>
</div>

<div class="pt-12">
  <div class="text-sm opacity-60">
    Full radar available at: <a href="https://thoughtworks.com/radar" class="text-blue-500 hover:underline">thoughtworks.com/radar</a>
  </div>
</div>