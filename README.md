# Smart Surveillance AI Platform
AI-Powered Hybrid Edge–Cloud Surveillance System

---

## Overview

Smart Surveillance AI is an intelligent, searchable video monitoring platform that transforms traditional CCTV systems into an AI-driven security intelligence solution.

The system combines:

- Edge-based facial recognition
- Vision-Language Models (VLMs)
- Real-time identity tracking
- Activity analysis
- Hybrid edge–cloud architecture
- Cloud-based indexing and search
- Web-based administrative interface

Unlike traditional surveillance systems that rely on passive video recording, this platform enables structured event extraction, searchable metadata, and automated identity tracking.

---

## Architecture Philosophy

The system follows a hybrid edge–cloud architecture:

- **Edge devices** handle sensitive AI inference and biometric processing.
- **Cloud services** provide scalability, indexing, authentication, and search.
- **Frontend dashboard** provides a secure interface for querying system events.

This architecture ensures:

- Privacy preservation
- Scalability
- Reliability
- Real-time performance
- Modular system evolution

---

## Repository Structure

The system is divided into multiple repositories under this organization:

### 1. edge-inference-service
Runs AI inference on Jetson Nano / Raspberry Pi devices.

### 2. edge-device-agent
Handles secure communication between edge devices and cloud infrastructure.

### 3. cloud-backend-api
Central API service for event ingestion, indexing, authentication, and search.

### 4. cloud-infrastructure
Infrastructure-as-Code definitions for AWS deployment.

### 5. admin-dashboard
Web-based administrative interface for searching and monitoring events.

### 6. shared-contracts (optional)
Shared API schemas and communication models.

---

## System Flow

1. Camera feed is processed on edge device.
2. Face detection and activity recognition are performed locally.
3. Structured event metadata and embeddings are generated.
4. Events are securely transmitted to cloud backend.
5. Cloud indexes events in searchable databases.
6. Administrators query events via web dashboard.

---

## Core Features

- Real-time face recognition
- Identity-based search
- Activity and object tagging
- Structured event timeline
- Secure device authentication
- Role-based access control
- Scalable cloud indexing
- Infrastructure as Code deployment

---

## Design Principles

- Separation of concerns
- Privacy by design
- Microservice-inspired modularity
- Infrastructure as Code
- Cloud-native scalability
- Secure communication

---

## Target Deployment

- Edge: Jetson Nano / Raspberry Pi
- Cloud: AWS (ECS, RDS, S3, OpenSearch, IAM)
- Frontend: React / Next.js

---

## Environments

- Development
- Staging
- Production

Each environment is isolated at the infrastructure level.

---

## Project Status

Current Version: 2.0 (Hybrid Edge–Cloud Architecture)

---

This project is developed as a graduation capstone project.
