# Motor Claim Surveyor AI Agent

**Motor Claim Surveyor AI Agent** is an AI-powered assistant that automates the motor insurance claims process. It helps surveyors, insurers, and policyholders by generating surveyor-style damage reports from car images sent via email, speeding up claim processing and reducing manual effort.  

---

## Features

- **Automated Claim Assessment**: AI analyzes car damage images and generates a preliminary damage report.  
- **Email-based Workflow**: Fully integrates with email to receive images, request additional info, and send reports.  
- **Draft Report Generation**: Creates surveyor-style reports including damage details and estimated repair costs.  
- **Customer Interaction Support**: Automatically requests additional images or information if needed.  
- **Internal Claims Team Integration**: Sends final reports directly to claims processing teams.  
- **Faster Claim Processing**: Minimizes manual inspection and email back-and-forth.  

---

## Automated Claims Surveyor Email Workflow

1. **Customer sends an email with car damage images**  
   - Policyholders take pictures of the damaged car and send them to the insurance company’s claims email.  

2. **System receives and reads the email**  
   - Emails are automatically processed by the system without manual intervention.  

3. **Images are reviewed by the system**  
   - The AI analyzes the images to understand the location and severity of the damage.  

4. **System creates a draft report**  
   - Generates a preliminary damage report with estimated costs and repair suggestions.  

5. **System replies to the customer (if needed)**  
   - If images are unclear or additional info is required, the system automatically requests it from the customer.  

6. **Updated images or info are received**  
   - Customer responses are processed, and the system updates the report as needed.  

7. **Final report is shared with the claims team**  
   - Completed surveyor reports are automatically sent to the internal claims team for review and processing.  

8. **Claim is processed faster**  
   - By automating most of the workflow, the system accelerates claim resolution significantly.  

---

## Tech Stack

- **GenAI**: GPT-4 for AI reasoning, claim analysis, and report generation.  
- **Embeddings**: OpenAI embeddings for semantic understanding of claim images and text.  
- **Vector Database**: Supabase / PostgreSQL for storing embeddings and claim metadata.  
- **Email Handling**: IMAP/SMTP or API-based email integration to receive images, request additional info, and send reports.  
- **Workflow Automation**: n8n JSON workflows to automate the full claim surveyor process from email ingestion to final report delivery.  

---

## Installation & Setup

Clone the repository:

```bash
git clone https://github.com/yourusername/motor-claim-surveyor-ai.git
cd motor-claim-surveyor-ai
