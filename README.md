# 🏥 Healthcare Multi-Agent System for Diagnosis and Health Guidance

## 📖 Overview

This project implements a multi-agent system (MAS) designed for healthcare applications. It integrates multiple AI agents to provide medical interpretations, diagnostic services, treatment recommendations, and health guidance, aiming to improve patient care and overall quality of life.

## Contributors
- https://github.com/KonouzA
- https://github.com/omaar28
- https://github.com/Retaj12003
- myself

## 🚀 Features

- Medical Abbreviation Disambiguation: Resolves abbreviations to improve system reasoning.

- Symptom Analysis: Extracts and interprets user symptoms.

- Drug Identification: Recognizes pills from images.

- Prescription Extraction: Extracts content from prescription images.

- X-ray Analysis: Acts as a virtual radiologist to identify abnormalities.

- Research Agent: Retrieves up-to-date studies from PubMed.

- Drug Advisor: Checks for adverse drug interactions.

- Diagnostic Summary: Provides comprehensive care recommendations.

- System Confidence Evaluation: Rates response confidence for safety.

## 🧱 System Architecture

- The system is built using the LangGraph framework with:

    - Nodes: Individual agents performing specific tasks.

    - Agent States: Shared data for inter-agent communication.

    - Edges: Define the workflow and routing logic.
  
## Workflow:
  
![image](https://github.com/user-attachments/assets/b629c3f3-b434-4f8b-9bb2-02966d5ebbf2)

## Example of System Test Cases:

- Determining the drug from an input image of the pills

![Screenshot 2025-07-07 004530](https://github.com/user-attachments/assets/e197827c-33f4-4dea-8b35-1b88922ce7e1)

- Using OCR to read prescriptions and output its contents for users

![Screenshot 2025-07-07 004537](https://github.com/user-attachments/assets/d426cac3-7ffb-4daf-8908-4fe2f442f57b)

- Giving a prognosis for users scans

![image](https://github.com/user-attachments/assets/e66ee041-cb6e-4da4-9929-0ce5d2efba6e)

