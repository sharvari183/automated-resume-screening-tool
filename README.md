# Automated Resume Screening Tool

## Project Overview
The Automated Resume Screening Tool is an AI/ML-based project that helps recruiters and HR teams automatically screen and rank resumes based on job description matching.

This system uses Natural Language Processing (NLP) and Machine Learning techniques such as TF-IDF Vectorization and Cosine Similarity to compare candidate resumes with job requirements and generate ranking scores.

The project simulates the working of a real Applicant Tracking System (ATS) used by companies for resume shortlisting.

---

# Features

- Resume screening and ranking
- Job description matching
- TF-IDF based text vectorization
- Cosine similarity scoring
- Candidate shortlisting system
- CSV report generation
- Data visualization using graphs
- Resume score comparison charts
- Shortlisted vs rejected analysis

---

# Tech Stack

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Google Colab

---

# Project Workflow

Resume → Text Processing → TF-IDF Vectorization → Similarity Calculation → Ranking → Shortlisting → Graph Visualization → CSV Report

---

# Machine Learning Concepts Used

## TF-IDF Vectorization
Converts resume and job description text into numerical vectors.

## Cosine Similarity
Measures similarity between resumes and job descriptions.

## Ranking System
Candidates are ranked based on similarity scores.

---

# Project Structure

```text
automated-resume-screening-tool/
│
├── images/
│   ├── score_graph.png
│   ├
│   ├── ranking_graph.png
│
│
├── automated_resume_screening_tool.ipynb
├── resume_screening_output.csv
├── README.md
