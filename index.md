---
layout: default
title: Sai Bhargav Varanasi
---

<nav style="display: flex; gap: 20px; margin-bottom: 30px; font-weight: bold;">
  <a href="#experience" style="text-decoration: none; color: #0969da;">Experience</a>
  <a href="#expertise" style="text-decoration: none; color: #0969da;">Expertise</a>
  <a href="#education" style="text-decoration: none; color: #0969da;">Education</a>
  <a href="https://github.com/saibhargav97v" target="_blank" style="text-decoration: none; color: #0969da;">GitHub</a>
</nav>

**Software Engineer @ Snowflake | Distributed Systems & Infrastructure**

I build resilient infrastructure for **Snowflake's Control Plane**, managing millions of concurrent workloads. My work bridges the gap between high-performance distributed systems and large-scale data engineering.

---

<div class="reveal" id="experience">
## 🚀 Core Impact

### **Snowflake** | Software Engineer
*Feb 2023 – Present | Menlo Park, CA*

* **Unistore & Hybrid Tables:** Architected backend infrastructure for one of Snowflake’s most anticipated features, merging analytical and transactional capabilities.
* **Workload Classification:** Designed and implemented a routing engine for "Antagonistic Workloads," ensuring system stability by intelligently isolating resource-heavy queries.
* **Disaster Recovery:** Developed core algorithms for Snowflake Backup & Restore to enable seamless recovery during regional outages.

<div class="tags">
  <span class="tag">Java</span> <span class="tag">FoundationDB</span> <span class="tag">Distributed Systems</span> <span class="tag">Cloud Services</span>
</div>

### **Visa** | Senior Software Engineer
*Aug 2018 – Jul 2021 | Bengaluru, India*

* **Xigo Metadata Management:** Developed an internal platform that automated **70% of ETL pipelines** across Visa’s data lake.
* **Hadoop PaaS:** Implemented a bulk data processing service that improved operational efficiency by **50%** through real-time utilization insights.
* **Observability:** Integrated Prometheus/Grafana monitoring for critical health metrics, serving 600+ daily internal users.

<div class="tags">
  <span class="tag">Node.js</span> <span class="tag">Hadoop</span> <span class="tag">Prometheus</span> <span class="tag">ETL</span>
</div>

---

## 🛠 Technical Expertise

* **Distributed Systems:** Consensus (DiemBFT), Fault Tolerance, High-Availability Design.
* **Data Infrastructure:** Snowflake, FoundationDB, MySQL, Neo4j, Apache Hive.
* **Engineering:** Java, Python, Go, Kubernetes, Docker, CI/CD.

---

## 📚 Education & Research
* **MS in Computer Science** | Stony Brook University (GPA: 3.83)
* **B.Tech in CS** | National Institute of Technology, Trichy (GPA: 9.0)
* **Publication:** *B-MEG: Bottlenecked Microservices Extraction using Graph Neural Networks* (ACM 2022).
</div>

<style>
  .reveal {
    opacity: 0;
    transform: translateY(20px);
    transition: all 0.8s ease-out;
  }
  .reveal.active {
    opacity: 1;
    transform: translateY(0);
  }
</style>

<script>
  function reveal() {
    var reveals = document.querySelectorAll(".reveal");
    for (var i = 0; i < reveals.length; i++) {
      var windowHeight = window.innerHeight;
      var elementTop = reveals[i].getBoundingClientRect().top;
      var elementVisible = 150;
      if (elementTop < windowHeight - elementVisible) {
        reveals[i].classList.add("active");
      }
    }
  }
  window.addEventListener("scroll", reveal);
  // Trigger once on load
  document.addEventListener("DOMContentLoaded", reveal);
</script>