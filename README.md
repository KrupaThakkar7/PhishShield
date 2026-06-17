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
* FastAPI
* JavaScript
* XGBoost
* Chrome Extension APIs
