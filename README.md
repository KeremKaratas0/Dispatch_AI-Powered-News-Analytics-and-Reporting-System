# Dispatch - AI Powered News Analytics and Reporting System

An end-to-end automated Python data acquisition and semantic analysis pipeline engineered for multi-keyword news discovery, web scraping, and AI-driven structured reporting.
https://dispatch-site-dusky.vercel.app/
---

## Project Overview

This project provides an automated workflow designed to discover, extract, filter, and summarize media coverage. Built originally for the **Animal Rights Watch Committee (HAKİM)**, the pipeline automates complex data acquisition tasks, cleans unstructured text across diverse web domains, and leverages Google's **Gemini API** for semantic filtering and automated structured reporting.

---

## Key Features

* **Advanced News Discovery:** Integrated with **SerpApi** featuring advanced pagination and deduplication logic for multi-keyword tracking.
* **Resilient Web Scraping:** Custom-built **BeautifulSoup** scraper engineered to parse clean, unstructured text across varied website architectures while maintaining robust connection resilience.
* **AI-Powered Semantic Filtering:** Integrates **Gemini API** using **Batch Processing** and **Exponential Backoff** strategies to rate-limit calls, ensure API stability, and execute semantic relevancy checks.
* **Structured Analytics & Reporting:** Automatically aggregates processed articles into actionable, structured analytical reports.

---

## Tech Stack

* **Language:** Python 3.10+
* **Data Discovery & Search:** SerpApi
* **Web Scraping & Parsing:** BeautifulSoup4, Requests
* **AI / Large Language Model:** Google Gemini API
* **Optimization Strategies:** Batch Processing, Exponential Backoff, Deduplication Algorithms

---

## Live Deliverables & Project Status

* **2025 Media Violation Report (Turkish):** Access the analytics report covering 2025 animal rights violation news in Turkey.
* 👉 [HAKİM Official Publication Page](https://www.hakimkomite.org/2026/02/05/medya-ihlal-raporu-2025/) | [Direct Report Link / PDF](https://www.hakimkomite.org/wp-content/uploads/2026/02/Medya_Ihlal_Raporu-2025.pdf) *(Language: Turkish)*

* **Web Platform:** The live web application is now active and deployed. Visitors can interactively test the real-time news scraping and export pipeline directly through the interface, while the AI-driven reporting features and system architecture are showcased via detailed case examples and walkthroughs.
* 👉 https://dispatch-site-dusky.vercel.app/

---

## Contact & Collaboration

If you are interested in accessing the underlying source code, inquiring about the technical implementation, or exploring potential research or commercial/economic applications of this workflow, feel free to reach out:

* **LinkedIn:** [Kerem Karataş](https://www.linkedin.com/in/kerem-karata%C5%9F-841777252/)
* **Email:** [keremkaratas.dev@gmail.com](mailto:keremkaratas.dev@gmail.com)
