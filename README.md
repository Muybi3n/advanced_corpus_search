<div align="center">
  <div>&nbsp;</div>

# GTI Corpus Search: Programmatic IP Intelligence

[![Proof of Concept](https://img.shields.io/badge/Status-Proof_of_Concept-yellow)](#)
[![Google Threat Intelligence](https://img.shields.io/badge/Integration-GTI-blue)](#)
[![Level: Beginner Friendly](https://img.shields.io/badge/Level-Beginner_Friendly-brightgreen)](#)
[![License](https://img.shields.io/badge/license-MIT-green)](#)

</div>

A high-performance search tool designed to perform modifier searches for the latest IP addresses utilizing the Google Threat Intelligence (GTI) Enterprise License. This repository demonstrates how to programmatically interact with the GTI corpus to extract advanced threat intelligence, metadata, and modifier data for threat hunting and incident response workflows.

> **⚠️ NOTE:** This project is for **Proof of Concept (POC) purposes only**. It is not intended for production use. Do not hardcode sensitive keys or credentials in this repository.

---

## 🚀 Quickstart

```bash
git clone git@github.com:Muybi3n/advanced_corpus_search.git
cd advanced_corpus_search
```

Configure your environment and run:

```bash
export GTI_API_KEY='your_api_key'
# Run the main script or notebook
```

## 🏗️ Architecture & Integration

This project is built to be easily adaptable and integrated into existing workflows:

- **Data Source:** Google Threat Intelligence (GTI) Enterprise API.
- **Use Case:** Advanced modifier searches and IP context enrichment.
- **Integration:** Can be plugged into SIEMs or SOAR platforms.

## 🛡️ Security Best Practices

- **API Keys:** Never hardcode your GTI API keys into the source code.
- **Environment Variables:** Always use environment variables or secure credential vaults to manage access.
- **Scope:** Ensure your API token has only the necessary permissions required for the integration.

## 🧪 Verification & Testing

Once configured, run the application and verify that the API returns the expected threat context without throwing authentication errors. Detailed test cases will be added as the project grows.

## 🔧 Troubleshooting

- **API Authentication Errors:** Ensure your environment variables are set correctly and that your token has not expired.

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Since this is a POC, feel free to fork and adapt it to your specific use cases.
