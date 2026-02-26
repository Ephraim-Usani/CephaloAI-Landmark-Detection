# CephaloAI — Automated Cephalometric Landmark Detection

> **AI system that automatically identifies and marks 27 anatomical landmarks on dental skull X-rays for orthodontic planning**

[![Demo](https://img.shields.io/badge/▶%20Watch%20Demo-Google%20Drive-red)](https://drive.google.com/file/d/1ij-rhXEF075A_RL2C0-MNtjR1NQNlsKP/view?usp=drive_link)
[![CPU Only](https://img.shields.io/badge/Deployment-CPU%20Only-orange)]()
[![Landmarks](https://img.shields.io/badge/Landmarks-27%20Points-purple)]()
[![Python](https://img.shields.io/badge/Python-3.8+-yellow)]()

---

## The Clinical Problem

Cephalometric analysis is a foundational tool in orthodontics and maxillofacial surgery. Before planning braces, jaw corrections, or surgical interventions, clinicians must analyze a lateral skull X-ray (cephalogram) by identifying and marking specific anatomical points — called **landmarks**.

A standard cephalometric analysis requires identifying **27 precise anatomical points**, then measuring the angles and distances between them to understand:
- Jaw position and relationship
- Dental inclination
- Facial growth patterns
- Surgical planning requirements

This manual tracing process:
- Takes 20–45 minutes per patient
- Requires significant training and experience
- Is prone to inter-observer variability
- Creates bottlenecks in busy orthodontic clinics
- Is simply unavailable in under-resourced dental settings across Africa

**CephaloAI automates the entire landmark detection process.**

---

## What It Does

CephaloAI takes a cephalometric X-ray as input and:

1. **Detects all 23 anatomical landmarks** automatically
2. **Marks each point** with precise coordinates on the image
3. **Calculates standard cephalometric measurements** from the detected landmarks
4. **Generates a tracing overlay** for clinical review
5. **Runs on CPU** — no expensive hardware needed

What previously took 30+ minutes of expert manual work now happens in seconds.

---

## Landmarks Detected

The system identifies all standard cephalometric landmarks including:
Sella (S), Nasion (N), Orbitale (Or), Porion (Po), Anterior Nasal Spine (ANS), Posterior Nasal Spine (PNS), Point A, Point B, Pogonion (Pog), Gnathion (Gn), Menton (Me), Gonion (Go), Articulare (Ar), and more — all 27 standard points.

---

## Technical Approach

- **Model:** YOLOv8 — fine-tuned for cephalometric landmark detection
- **Input:** Standard lateral cephalogram (JPEG/PNG/DICOM)
- **Output:** Annotated image with landmark coordinates and measurements
- **Deployment:** CPU-only, runs on standard clinical workstations

---

## Demo

[▶ Watch CephaloAI in action](https://drive.google.com/file/d/1ij-rhXEF075A_RL2C0-MNtjR1NQNlsKP/view?usp=drive_link)

> The demo shows real-time fetal plane detection, auto-freeze, and automatic caliper placement for BPD, AC, and FL measurements.

## Clinical Impact

In African dental clinics and orthodontic practices where:
- Specialist orthodontists are limited
- Manual tracing is time-consuming and error-prone
- Digital cephalometric software costs thousands of dollars

CephaloAI provides **free, fast, accurate cephalometric analysis** accessible to any clinic with a basic computer.

---

## Built By

**Ephraim Usani** — First-Class Radiographer & Clinical AI Engineer, Lagos, Nigeria

[LinkedIn](https://www.linkedin.com/in/ephraim-usani) | [GitHub](https://github.com/Ephraim-Usani)
