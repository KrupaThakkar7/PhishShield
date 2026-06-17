# PhishShield

PhishShield is a browser-based cybersecurity extension designed to detect potentially malicious phishing emails directly within webmail platforms such as Gmail and Outlook. Instead of requiring users to manually upload email content into a separate tool, the extension integrates into the user’s workflow and analyzes emails in real time as they are opened. The system examines sender information, email content, suspicious URLs, and phishing-related language patterns to estimate phishing risk and alert users before they interact with harmful content.

The project combines AI-assisted phishing classification with rule-based security checks to improve detection reliability and explainability. PhishShield focuses on practical cybersecurity product design, user protection, and secure interaction workflows while exploring how machine learning can be integrated into real-world phishing prevention systems. The project also emphasizes browser extension architecture, threat detection logic, and usability-focused security warnings.
# PhishShield

PhishShield is a browser-based cybersecurity extension designed to identify potentially malicious phishing websites in real time. The extension monitors URLs visited by users and analyzes them using a machine learning–based detection engine before users interact with potentially harmful web pages.

Unlike traditional security tools that require manual URL submission, PhishShield integrates directly into the browsing workflow and automatically evaluates URLs as users navigate the web. The system extracts and analyzes multiple URL-based indicators, including domain characteristics, suspicious patterns, and structural features commonly associated with phishing attacks, to estimate phishing risk and provide timely security warnings.

The project combines machine learning–based phishing detection with carefully selected security heuristics to improve detection reliability and handle edge cases. Its architecture is designed to be modular, allowing the browser extension, backend services, and detection models to evolve independently without requiring a complete redeployment of the system.

PhishShield focuses on practical phishing prevention, secure user interaction, and real-world browser security workflows while exploring how machine learning can be integrated into proactive cybersecurity solutions.

## Key Features

* Real-time URL phishing detection
* Machine learning–based URL classification
* Rule-based fallback detection for suspicious patterns
* Browser-integrated security warnings
* Modular extension and backend architecture
* Scalable model update mechanism
* Lightweight and user-friendly security workflow

## Technology Stack

* Python
* Scikit-learn
* Flask/FastAPI
* JavaScript
* Chrome Extension APIs
