# SafeMessage AI

Building AI course project

## Summary

SafeMessage AI is a multilingual cybersecurity assistant that helps people and small businesses identify phishing, scam, and suspicious messages. It analyzes language, links, and sender patterns, then explains the warning signs and provides a risk level.

## Background

Phishing emails, fraudulent text messages, fake payment requests, and online scams affect individuals and businesses every day. These messages are becoming increasingly convincing and may pressure people to click a dangerous link, reveal personal information, send money, or provide passwords.

Small businesses and community organizations may not have dedicated cybersecurity professionals who can examine every suspicious message. Language barriers can also make scams more difficult to recognize.

My interest in this project comes from my studies in cybersecurity and my experience managing small businesses. I would like to create a simple tool that helps users understand why a message may be dangerous instead of only labeling it as spam.

The main problems this project would address are:

* Difficulty recognizing convincing phishing and scam messages
* Lack of affordable cybersecurity assistance for small organizations
* Suspicious messages written in different languages
* Limited understanding of the warning signs found in fraudulent messages

## How is it used?

A user would copy and paste the text of a suspicious email or message into SafeMessage AI. The user could also provide information about the sender and any links contained in the message.

The system would examine the message and return:

* A risk level, such as low, medium, or high
* Possible warning signs found in the message
* An explanation written in simple language
* Recommended actions, such as avoiding the link, confirming the sender through another method, or contacting a cybersecurity professional

The system could be used by individuals, students, seniors, small businesses, nonprofit organizations, and community centres. It would support the user’s decision, but it would not automatically delete messages or make important decisions without human approval.

## Data sources and AI methods

A future version of the project could use legally available and properly anonymized data such as:

* Public datasets containing examples of phishing and legitimate emails
* Verified examples of scam and non-scam text messages
* Lists of known malicious links and suspicious website domains
* Voluntary user feedback after personal information has been removed
* Multilingual examples of common scam language

Natural language processing could be used to examine words, phrases, tone, and sentence patterns. TF-IDF could identify important words, while classification methods such as naive Bayes, logistic regression, nearest neighbour, or neural networks could estimate whether a message is suspicious.

Rule-based checks could also detect warning signs such as urgent payment demands, requests for passwords, unusual links, threats, prizes, and attempts to impersonate trusted organizations.

The model should be tested using separate training and test data. Its performance should be evaluated using measures such as precision and recall, because accuracy alone may be misleading when legitimate messages greatly outnumber phishing messages.

## Challenges

SafeMessage AI would not provide perfect results. Some legitimate messages could be incorrectly classified as suspicious, while a sophisticated scam could be missed.

Other challenges include:

* Protecting the privacy of messages submitted by users
* Removing names, account numbers, and other personal information
* Preventing bias against certain languages or writing styles
* Keeping the system updated as scammers change their techniques
* Explaining uncertainty instead of presenting every result as certain
* Avoiding excessive dependence on AI for important security decisions

The tool should not replace cybersecurity professionals, law enforcement, financial institutions, or emergency services. Users should verify important messages directly with the organization or person involved.

## What next?

The first step would be to create a basic prototype that classifies English-language messages as suspicious or legitimate. It could later be expanded to support French and other languages.

Future development could include:

* A website or mobile application
* A browser or email extension
* Screenshot and image analysis
* Detection of suspicious website links
* Privacy-preserving analysis performed on the user’s device
* Partnerships with community organizations and small businesses
* User testing to improve accessibility and clarity
* Regular model updates based on newly identified scams

Developing the project would require additional skills in Python, machine learning, natural language processing, cybersecurity, user-interface design, privacy, and data protection.

## Acknowledgments

* This idea was developed as part of the Elements of AI: Building AI course by the University of Helsinki and Reaktor.
* The project was inspired by the need to make phishing and scam detection understandable and accessible to individuals and small organizations.
* No external code, datasets, or images are included in this project at its current concept stage.
