# AI-RedactionBot---Public

Redacting Documents costs Government agencies and companies milltions of dollars each year. 

Whether it is by hand or by using manual software to redact  personally identifiable information from documents, it is an extemely time consuming job. 

The AI redaction bot assists analysts with this task by using OCR and AI to automatically redact PII from documents.

First provide the bot a file that I would like to redact. I could also provide it a folder that I would like it to monitor to do this in batch mode.

The bot then asks me for any additional words to redact and the types of PII that I want it to redact.

The bot will now add each PII word it identified using AI


SETUP:

Must have Azure Computer Vision and Azure Text Analytics Key

Add these keys to the "2. Microsoft NLP Get PII Entities DT" File. The variables to change are:

AzureCompVisionKey
OCPAzureTextAnalyticsKey
