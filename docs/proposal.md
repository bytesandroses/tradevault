# Introduction

## Project Name: 

TradeVault

## Name of the organization or individual submitting the proposal: 

Isaac Abodunrin

## Describe your project.

TradeVault is a web app that allows non-technical tradespeople (plumbers, electricians, builders) to generate professional invoices from rough handwritten ones, and store them on the Sia network for decentralized record keeping.

The app allows users to upload photos of rough handwritten job notes or rough estimates. It uses an OCR to extract the data, this data is then fed into an LLM MCP, and the final output is formatted into a professional PDF invoice. Invoices are automatically encrypted and stored on the Sia Network (via renterd) ensuring that they are kept private and secure.

To ensure adoption among non-technical users, TradeVault operates on a "Web 2.5" model. The application backend manages the interaction with the Sia network via a hosted renterd instance, abstracting the complexity of key management away from the end-user.

## How does the projected outcome serve the Foundation’s mission of user-owned data?

This project solves an administrative pain point for the "blue-collar" workforce while serving as a proof-of-concept for privacy-first, decentralized record-keeping. It introduces a demographic to the Sia ecosystem that would typically be excluded by the technical barriers of managing wallet seeds and nodes, proving that "User-Owned Data" can be made accessible to everyone.

## We cannot provide grants to residents of jurisdictions under increased FATF monitoring, those that have active OFAC sanctions, or those that fail our bank compliance tests. We also cannot provide grants if your payment bank account is located in those same locations. Please review the following list.

### Are you a resident of any jurisdiction on that list? 
No

### Will your payment bank account be located in any jurisdiction on that list? 
No

# Grant Specifics

## Amount of money requested and justification with a reasonable breakdown of expenses:

Budget: $7,500

The budget covers approximately 250-300 hours of development, design, and testing over a 3-month period.

- Backend Development (Python/FastAPI): $3,000
 - Setting up the API, OCR extraction logic, PDF generation engine, and Docker containerization.

- Sia Integration (renterd): $2,500
 - Configuring the renterd node, implementing S3-compatible file uploads/retrievals, and handling encryption management.
 
- Frontend & UI (React): $1,500
 - Building a responsive mobile-web interface suitable for field use (uploading photos, viewing PDF history).

- Documentation & Educational Content: $500
Writing the "Self-Hosting" guide and recording the setup tutorial.

## What are the goals of this small grant? Please provide a general timeline for completion.

Estimated Duration: 3 Months

Month 1: Core Logic & Frontend
 - Goal: Build an app that takes photos and uses LLM/OCR to extract text and render a PDF.
 - Deliverables:
  - FastAPI backend environment setup.
  - Integration of OpenAI Vision API.
  - React Frontend for image capture and invoice preview.

Month 2: Sia Integration (renterd)
 - Goal: Connect the backend to the decentralized web.
 - Deliverables:
  - Setup of renterd instance.
  - Backend logic to encrypt and upload PDFs to Sia testnet/mainnet.
  - Implementation of file retrieval (fetching the invoice back from Sia).

Month 3: Documentation and Release
 - Goal: Polish and Public Launch.
 - Deliverables:
  - Mobile responsiveness polish.
  - Open Source Release: Public GitHub repository with full documentation.
  - "How to Run" video guide.

## Potential risks that will affect the outcome of the project:

1. I am an early-career software developer. My academic background is in Bioinformatics, where I gained significant experience building data processing pipelines and handling complex logic in Python. I have structured this project using a stack I am proficient in (Python/FastAPI) and will be working on this full-time to ensure milestones are met.
2. Non-technical users often struggle with Web3 concepts (wallets, nodes). The architecture is designed as a managed service. The end-user interacts with a standard web interface, while the backend handles the renterd communication. This ensures the user experience is identical to standard Web2 apps, removing the barrier to entry.

# Development Information

## Will all of your project’s code be open-source?

Yes

[Projects can use closed-source components, but can’t develop closed-source code. If any of your project’s code is closed-source, please describe what code and why.]

Leave a link where code will be accessible for review.

## Links

https://github.com/bytesandroses/tradevault

## Do you agree to submit monthly progress reports?

Yes

[Progress reports must be submitted monthly here in the forum.]

## Contact info
### Email: 

isaacabodunrin05@gmail.com

### Any other preferred contact methods:

Discord: bytesandroses
WhatsApp: +27 65 969 9665