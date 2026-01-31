# 🌐 OmniAble: AI-Powered Accessibility for Bharat

**A unified, AWS-native ecosystem designed to bridge the accessibility gap for 70M+ individuals across India.**

---

## 📌 Submission Overview
This repository contains the **Technical Specification and Architectural Blueprint** for the AWS AI for Bharat Hackathon (Idea Phase). Leveraging a **Spec-Driven Development** approach, OmniAble maps real-world accessibility challenges to a scalable, serverless cloud architecture.

---

## 🎯 The Problem
Assistive technology in Bharat is currently fragmented. Users with diverse disabilities (Vision, Hearing, Cognitive, Motor, Speech) must navigate multiple, non-localized applications that lack support for Indian Sign Language (ISL) and regional dialects.

## ✨ The Solution
OmniAble provides a single, modular hub that integrates five core accessibility pillars into one interface, optimized for low-bandwidth environments and localized for the Indian context.

### **Key Modules:**
| Module | AWS Integration | Impact |
| :--- | :--- | :--- |
| **Vision** | Amazon Bedrock & Polly | Scene description & regional TTS |
| **Hearing** | Amazon Transcribe | Speech-to-Sign (ISL) conversion |
| **Cognitive** | Amazon Bedrock (Claude) | Text simplification for neurodiversity |
| **Speech** | Amazon Polly | Multi-lingual predictive communication |

---

## 🏗️ AWS Technical Stack
* **Intelligence Layer:** **Amazon Bedrock (Claude)** for sophisticated image-to-text and linguistic simplification.
* **Voice & Audio:** **Amazon Polly** (Neural voices for Indian dialects) and **Amazon Transcribe**.
* **Compute:** **AWS Lambda** for a cost-efficient, event-driven serverless backbone.
* **Data Persistence:** **Amazon RDS (PostgreSQL)** for secure user profiles and progress tracking.
* **Global Delivery:** **Amazon S3** and **CloudFront** for low-latency asset delivery across Bharat.

---

## 📁 Repository Structure
* **[Requirements Specification](./requirements.md)**: User stories in EARS notation and acceptance criteria.
* **[System Design](./design.md)**: Technical architecture, Mermaid diagrams, and API definitions.

---

## 🚀 Future Roadmap
- **Phase 1:** Core Vision and Speech modules using Amazon Bedrock.
- **Phase 2:** Integration of Indian Sign Language (ISL) video synthesis.
- **Phase 3:** Community-driven localized dialect training for Amazon Transcribe.

---

*Developed for the AWS AI for Bharat Hackathon 2026*