# plaid-oer4all-pilot

The AI OER Advisor for Creation, Licensing, and Inclusive Design

This repository hosts the code for the PLAID-OER4ALL Pilot Tool, a browser-based application developed to assist educators in the ethical and legal creation of AI-assisted Open Educational Resources (OER).

The tool integrates three complex policy domains—AI creation pathways, open licensing, and inclusive design—to generate machine-readable output and highly detailed prompts.

# Core Functionality

PLAID-OER4ALL guides the user through five key steps, ensuring the resulting OER is both high-quality and legally compliant.

1. The PLAID Framework (P.L.A.I.D.)

The tool's decision engine is based on the Prompting, Licensing, and AI-Driven (PLAID) framework, which adds "4ALL" (Inclusivity) as a mandatory component. This framework ensures adherence to openness, accessibility, and pedagogical best practices.

2. The 18-Scenario Licensing Matrix

The core of the tool is a licensing decision tree that determines the appropriate Creative Commons license based on two critical inputs:

Authorship Origin (AO): The degree of human vs. AI involvement in the initial idea.

Level of Human Involvement (LHI)

Educational Data Source (EDS): The copyright status of the data used by the Gen AI (e.g., Public Domain, Mixed OER, or Proprietary Content).

This logic maps every combination to a single license recommendation (CC0, CC BY, CC BY-SA, or Not Advisable), mitigating legal risk.

3. Integrated Inclusive Design

The tool requires educators to select compliance criteria based on:

Universal Design for Learning (UDL 3.0): Checkpoints across Representation, Action & Expression, and Engagement.

Digital Accessibility: Compliance with WCAG 2.2 AA standards and required media formats (e.g., Long Descriptions, Transcripts).

# Outputs for Educators

Upon completion, the tool provides two essential, copyable outputs:

Comprehensive AI-Ready Prompt: A single, structured prompt that includes all OER metadata, UDL requirements, WCAG compliance instructions, and the determined license. This minimizes the time educators spend refining prompts for clarity and compliance.

Machine-Readable CC License Code (HTML): The final, customized license code (including author and URL attribution) ready to be pasted into the OER footer for machine-readable attribution.

# Research Component

This tool is deployed as a pilot study instrument. All data is collected to analyze user behavior, understand common creation pathways, and validate the efficacy of the PLAID licensing matrix.

Data Storage: Usage data (metadata, licensing choices, UDL selections, and voluntary researcher contact information) is securely saved using Google Firebase Firestore upon submission.

Data Use: Data is used exclusively for academic research, validation, and future iterations of the tool.
