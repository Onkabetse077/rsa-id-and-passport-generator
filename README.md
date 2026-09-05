# RsaIdAndPassportGenerator

An open-source utility designed for developers and QA engineers to generate structurally valid South African Identity Numbers and mock passport data for automated testing, form validation, and database seeding.

### Key Features

* **SA ID Number Generation:** Generates compliant 13-digit South African ID numbers based on the official specification, incorporating valid birthdates (YYMMDD), gender digits, citizenship status, and the Luhn algorithm checksum.
* **Passport Data Mocking:** Creates realistic passport metadata, including matching document numbers, issue/expiry dates, and machine-readable zone (MRZ) formats for comprehensive testing workflows.
* **Validation Support:** Includes built-in algorithms to validate existing ID numbers and ensure they pass checksum and date-logic checks.
* **Developer Friendly:** Lightweight and easily integrated into automated test suites, CI/CD pipelines, or local development environments.

### Disclaimer

This tool is strictly intended for software development, testing, and quality assurance purposes. Generated identification numbers and data are synthetic and should not be used for fraudulent activities, identity theft, or bypassing real-world identity verification systems.
