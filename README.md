# Customer-invoice-automation-with-N8N-Gemini-Google-Sheets

**Project Overview**  
An end-to-end invoice automation workflow built with n8n that processes incoming invoice emails, extracts customer data using AI, generates PDF invoices, creates email drafts, and logs transactions to Google Sheets.

**Objectives**  
- Automate manual invoice processing from email to draft response  
- Extract structured customer data from unstructured email content  
- Generate professional PDF invoices automatically  
- Maintain audit trail of all processed invoices  
- Eliminate repetitive copy-paste tasks  

**Tools Used**  
- **N8N** – Workflow automation platform with 14-day free trial  
- **Google Gemini 2.0** – AI model for information extraction  
- **APITemplate.io** – PDF generation service  
- **Gmail API** – Email processing and draft creation  
- **Google Sheets** – Data logging and tracking  
- **Perplexity** – Documentation research and solution design  

**📸 Workflow Screenshots**

- **Automation Prompt**  
  ![automation prompt](screenshots/automation%20Prompt.jpg)

- **n8n Workflow (Full View)**  
  ![n8n workflow](screenshots/n8n%20workflow.jpg)

- **n8n in Action (Execution Panel)**  
  ![N8N work](screenshots/n8n%20work.jpg)

- **Gmail Draft with PDF**  
  ![gmail draft](screenshots/gmail%20draft.jpg)

- **Google Sheet Upload Status**  
  ![google sheet upload](screenshots/google%20sheet%20upload.jpg)

- **Generated Invoice PDF**  
  [📄 View PDF Invoice](screenshots/generated%20invoice.pdf)

**Key Technical Achievements**  
- Configured Gmail trigger with subject-based filtering for invoice emails  
- Implemented AI-powered data extraction using structured attributes (name, amount, address, date)  
- Set up automated PDF generation with custom invoice templates  
- Created Gmail drafts with PDF attachments  
- Built Google Sheets integration for transaction logging  
- Troubleshot model selection and data extraction issues  

**Key Insights**  
- AI models require proper configuration and testing (switched between Gemini versions)  
- HTML text extraction provides better results than simplified email content  
- JSON parameter mapping is crucial for PDF template generation  
- Workflow automation tools need iterative testing and refinement  
- Solution design should break complex problems into manageable steps  

**My Key Learnings**  
- **Workflow Design**: Breaking down complex automation into discrete, testable steps  
- **AI Integration**: Configuring LLM models for structured data extraction  
- **API Management**: Connecting multiple services (Gmail, Gemini, APITemplate.io, Sheets)  
- **Troubleshooting**: Debugging automation flows and resolving data extraction issues  
- **Solution Architecture**: Designing end-to-end processes that eliminate manual work  
- **Tool Evaluation**: Comparing automation platforms and selecting appropriate services  


