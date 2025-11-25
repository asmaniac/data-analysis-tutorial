# Project Requirements & Scope Document

> **Student Instructions:** Complete this template BEFORE starting development.

## 📋 Project Overview

**Project Name:** CleanSightX

**One-Sentence Description:**
An AI-powered platform that helps business users and data analysts quickly identify and fix data quality issues in CSV, JSON, and Excel datasets.

## 🎯 Project Goals

**Primary Goal:**
Enable non-technical users to understand, analyze, and improve dataset quality using automated metrics and AI explanations.

**Success Criteria:**
-  Upload a dataset (up to 50MB) and get a quality score within 5 seconds
-  Accurate detection of missing values, duplicates, inconsistent data types, and outliers
-  AI-generated explanations that are easy for non-technical users to understand

## 👥 Target Users

**Primary Users:**
Business analysts
Data analysts
Non-technical staff needing quick insights into dataset quality

**User Needs:**
Simple upload process for their datasets
Clear, actionable metrics about data quality
Natural language explanations of issues
Visual dashboards and charts
Exportable reports for sharing or documentation
## ✨ Core Features

**Must-Have (MVP):**
1. File upload (CSV, JSON, Excel) with drag-and-drop and validation
2. Automated data quality scoring (missing values, duplicates, outliers, inconsistencies)
3. AI-generated insights with suggestions for improvement

**Should-Have:**
1. Interactive charts showing trends and distributions
2. Column-level detail view with issue highlights

**Could-Have (Stretch Goals):**
1. Exportable reports in PDF/Excel
2. User favorites or history of previous dataset analyses

## 🔧 Technical Stack

**Frontend:** React 18 + Next.js 14
**Routing:** Next.js App Router
**Data Management:** Papa Parse for CSV/JSON parsing
**Styling:** Custom CSS3 (component-based, no Tailwind)
**API/Data Source:** OpenAI API v4+ for AI insights

## 📅 Timeline

**Total Duration:** 10 days

**Sprint Breakdown:**
- Sprint 1 (Days 1-2): Project setup, Next.js environment, CSS system, FileUpload component
- Sprint 2 (Days 3-5): Build data analysis engine, parse datasets, calculate quality metrics, display DataPreview
- Sprint 3 (Days 6-8): Integrate OpenAI API, AI insights, create interactive charts, add ColumnDetails
- Sprint 4 (Days 9-10): Testing, accessibility improvements, performance optimization, deploy to Vercel, finalize documentation

## ✅ Deliverables Checklist

- [ ] Deployed application
- [ ] GitHub repository with README
- [ ] Test suite (≥ 70% coverage)
- [ ] Project documentation
- [ ] Presentation materials

---

**When complete, submit this document for instructor approval before beginning development.**
