---
title: Home
cssclasses: [landing-page]
---

## Hello World!!

Welcome to my digital space. I'm a software engineer focused on low-level systems, compilers, and performance optimization.

<div class="portfolio-tabs">
<input type="radio" name="section-tabs" id="tab-projects" class="tab-input" checked>
<label for="tab-projects" class="tab-btn">🚀 Projects</label>
<input type="radio" name="section-tabs" id="tab-blogs" class="tab-input">
<label for="tab-blogs" class="tab-btn">📝 Writing & Blogs</label>

<div class="tab-panels">

<div class="tab-panel" id="panel-projects" onclick="const t = event.target.closest('.callout-title'); if (t) { const c = t.parentElement; if (!c.classList.contains('is-collapsed')) { this.querySelectorAll('.callout').forEach(el => { if (el !== c) el.classList.add('is-collapsed'); }); } }">

> [!note]- Project Name 1
> High-performance pipeline for real-time graphics and compute shaders. Built with C++ and Vulkan. — **[View on GitHub ↗](https://github.com/yourusername/repo1)**

> [!note]- Project Name 2
> Custom compiler optimization passes written via LLVM to target modern architectures. — **[View on GitHub ↗](https://github.com/yourusername/repo2)**

> [!note]- Project Name 3
> Lightweight systems utility designed for Linux environments. — **[View on GitHub ↗](https://github.com/yourusername/repo3)**
 
</div> <!-- End Projects Panel -->

<div class="tab-panel" id="panel-blogs">

Head over to the [[blogs/index|Blog Archive]] to read my latest notes, deep dives, and technical write-ups.

</div> <!-- End Blogs Panel -->

</div> <!-- End Tab Panels -->

</div> <!-- End Tabs -->
