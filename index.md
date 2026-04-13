---
layout: default
---

<div class="reveal">

# Sai Bhargav Varanasi
**Software Engineer @ Snowflake | Distributed Systems & Infrastructure**

I build resilient infrastructure for **Snowflake’s Control Plane**, managing millions of concurrent workloads globally.

[Experience](#experience) | [Expertise](#expertise) | [Education](#education) | [GitHub](https://github.com/saibhargav97v)

</div>

---

<div class="reveal" id="experience">

## 🚀 Core Impact

### **Snowflake** | Software Engineer
*Feb 2023 – Present | Menlo Park, CA*

* **Control Plane & Unistore:** Architecting distributed systems to manage millions of concurrent workloads with high resilience and low latency.
* **Workload Classification:** Implementing routing engines for "Antagonistic Workloads" to ensure multi-tenant system stability.
* **Disaster Recovery:** Developing core algorithms for Snowflake Backup & Restore.

**Tech:** `Java` `FoundationDB` `Distributed Systems` `Cloud Services` `Kubernetes`

---

### **Visa** | Senior Software Engineer
*Aug 2018 – Jul 2021 | Bengaluru, India*

* **Xigo Metadata Management:** Built an internal platform that automated **70% of ETL pipelines** across Visa’s data lake.
* **Hadoop PaaS:** Implemented a bulk data processing service that improved operational efficiency by **50%**.

**Tech:** `Node.js` `Hadoop` `Prometheus` `ETL` `Python`

</div>

<div class="reveal" id="expertise">

## 🛠 Technical Expertise
* **Distributed Systems:** Consensus (DiemBFT), Fault Tolerance, High-Availability.
* **Data Infrastructure:** Snowflake, FoundationDB, MySQL, Neo4j, Apache Hive.
* **Core Engineering:** Java, Python, Go, Kubernetes, Docker, CI/CD.

</div>

<style>
  .reveal { opacity: 0; transform: translateY(20px); transition: all 0.8s ease-out; }
  .reveal.active { opacity: 1; transform: translateY(0); }
</style>

<script>
  function reveal() {
    var reveals = document.querySelectorAll(".reveal");
    for (var i = 0; i < reveals.length; i++) {
      var windowHeight = window.innerHeight;
      var elementTop = reveals[i].getBoundingClientRect().top;
      if (elementTop < windowHeight - 150) {
        reveals[i].classList.add("active");
      }
    }
  }
  window.addEventListener("scroll", reveal);
  document.addEventListener("DOMContentLoaded", reveal);
</script>