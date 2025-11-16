---
layout: splash
title: "Hi, I'm Varatharajan"
subtitle: "Data Engineering Manager • Cloud • AI • Architecture"
header:
  overlay_color: "#000"
  overlay_filter: "0.3"
excerpt: "I design, build, and optimize data systems using Azure, Databricks, SQL, Python, and AI."
---

Welcome to my space where I share my journey in **Data Engineering**, **Cloud**, and **AI**.

### 👇 What you’ll find here:
- My **Data Engineering projects**
- My work in **Azure / ADF / Databricks / Synapse**
- **AI tools** I'm building (AI Data Copilot, AI Coach)
- Blogs about **data architecture**, **pipelines**, **performance tuning**
- My learning notes across **SQL, Python, ML, and cloud**

---

## 🛠 Featured Projects

### **AI Data Copilot**
A personalized AI agent for data professionals (Azure + Python + Streamlit)

### **CoinTrends.ai**
Crypto analytics pipeline using ADF, Databricks, Delta Lake, and Synapse.

### **SOW Automation System**
End-to-end system for automated SOW creation using templates, pricing logic, and email workflows.

---

## ✍️ Latest Posts

{% for post in site.posts limit:5 %}
- **[{{ post.title }}]({{ post.url }})** — {{ post.date | date: "%b %d, %Y" }}
{% endfor %}
