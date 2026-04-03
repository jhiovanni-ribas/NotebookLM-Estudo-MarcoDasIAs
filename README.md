![Capa do Projeto](./assets/capa-marco.png)

🤖 AI Study Guide: Brazil's AI Bill (PL 2338/2023)


📝 Context & Objectives
This project was developed as part of the DIO Bootcamp. The primary goal is to apply Active Learning 
techniques using NotebookLM to dissect the Brazilian Artificial Intelligence Bill (PL 2338/2023).

As a Legal Engineer, I aimed to bridge the gap between complex legislative text and structured technical 
insights, focusing on how this regulation will impact the future of AI development and Legal Operations 
in Brazil.

Study Objectives:

    - Understand the Risk Classification framework (Excessive vs. High Risk).
    - Analyze the civil liability and governance obligations for AI agents.
    - Map out the fundamental rights of individuals affected by AI systems.
    - Perform a comparative analysis with the EU AI Act (2024).

📂 Project Ecosystem (Deliverables)
To ensure a light and functional repository while maintaining methodological transparency, this project includes:

    - Full Prompt Engineering Guide (PDF): Detailed documentation of the AI interaction strategy, including 
    Master Prompts and the "Scars" (troubleshooting) section.
    - Executive Presentation (PDF): A high-level slide deck generated via Gamma App, applying Legal Design 
    principles for stakeholders.
    - Processing Evidence (Images): Screenshots of the NotebookLM interface, proving the generation of bilingual 
    technical podcasts (Audio Overviews) and source processing.


📚 Sources Curated
To feed the NotebookLM, I selected 4 key open-source documents:

    1. Official Text: PL 2338/2023 (Federal Senate).
    2. CTIA Committee Report (Internal Commission on Artificial Intelligence).
    3. AI & Data Protection Guide (National Data Protection Authority - ANPD).
    4. Technical Analysis: Economic Impacts of AI Regulation (Sectorial Study).
    5. Comparative Reference: EU AI Act (Official Text 2024).


🧠 Prompt Engineering & "Scars"
In this section, I documented the strategic questions used to extract the best out of the AI model, 
along with the challenges faced during the process.

  Prompt: "Summarize PL 2338."

    - Expected Outcome: A broad overview of the Bill.
    - The "Scars" (Troubleshooting): The initial output was too generic. I had to refine the results by 
    asking for summaries of specific chapters to ensure legal depth.

  Prompt: "What are the sanctions for 'Excessive Risk' AI according to Art. 14?"

    - Expected Outcome: A detailed list of penalties and enforcement measures.
    - The "Scars" (Troubleshooting): The AI initially confused the sanctions with LGPD (General Data 
    Protection Law) fines. I had to re-anchor the context by forcing the model to stick strictly to the 
    uploaded document.

  Prompt: "Create a comparison table between Development and Operation Agents."

    - Expected Outcome: A clear differentiation between the roles of providers and operators.
    - The "Scars" (Troubleshooting): This prompt was a success, but only after I explicitly provided the 
    glossary from Art. 4 to the model to avoid common industry terminology overlaps.


📖 Study Mini-Guide (Final Delivery)

Structured Summary
    - Core Pillars: Human-centricity, transparency, and non-discrimination.
    - Risk-Based Approach: Systems are categorized by impact, requiring algorithmic impact assessments 
    for high-risk tools.
    - Liability: The bill foresees strict liability for damages caused by high-risk AI systems.


🔍 Glossary of Key Concepts
    - AI System: Machine-based systems with varying degrees of autonomy.
    - AI Agent: Umbrella term covering both providers and operators.
    - Regulatory Sandbox: Controlled environments for testing innovations under supervision.


📋 Reusable Prompts for Future Reviews
    - "Act as a Compliance Specialist. Explain the governance requirements for a Health-tech startup under Art. 21."
    - "Compare the definition of 'Personal Data' in PL 2338 with the LGPD standards."


Developed by Jhiovanni Ribas - Bridging Law & Data Science.
