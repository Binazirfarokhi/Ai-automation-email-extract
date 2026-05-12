# Ai-automation-email-extract
# AI Email-to-Excel Document Extraction Automation

This project demonstrates an AI-powered email automation workflow built with Microsoft Power Automate and AI Builder.

The goal of this automation is to reduce manual data entry by extracting important information from email attachments and saving the structured data into an Excel file.

## Demo

The GIF below shows the email workflow and how the automation starts from an incoming email.

![AI Email Automation Demo](assets/email-automation-demo.gif)

## Project Overview

Many organizations receive important documents through email, such as invoices, receipts, forms, or reports. Manually opening each email, downloading attachments, reading the document, and copying the information into Excel can take a lot of time.

This project solves that problem by using Power Automate and AI Builder to automatically process email attachments and extract useful information.

## How the Automation Works

1. A new email is received in Outlook.
2. Power Automate checks whether the email has an attachment.
3. The attachment is processed using AI Builder.
4. AI Builder extracts key information from the document.
5. The extracted data is saved into an Excel table.
6. The Excel file becomes a structured record of all processed documents.

## Example Extracted Fields

Depending on the document type, the automation can extract information such as:

- Vendor name
- Invoice number
- Invoice date
- Due date
- Total amount
- Tax amount
- Payment terms
- Customer name
- Document ID

## Tools and Technologies Used

- Microsoft Power Automate
- AI Builder
- Outlook
- Excel
- OneDrive or SharePoint

## Skills Demonstrated

- Business process automation
- AI document processing
- Email workflow automation
- Data extraction
- Excel integration
- Microsoft Power Platform
- Reducing manual work and human error

## Project Outcome

The final result is an automated workflow that helps process emailed documents faster and more accurately. It is useful for invoice processing, receipt tracking, form collection, and administrative workflows.
