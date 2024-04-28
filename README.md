New Exploit and Zero-Day Found in Obsidian Desktop
Application with 2 Plugins Enabled
Introduction
Obsidian is a popular note-taking and knowledge management application.
Recently, a new exploit and zero-day vulnerability were discovered in
Obsidian that could allow attackers to execute arbitrary code on a
victim's computer. This vulnerability affects Obsidian versions 1.5.12
and earlier, with two specific plugins enabled: Surfing 0.9.5 and Gemini
Assistant 1.0.4.
The Exploit
The exploit involves hovering over a URL in Obsidian in Gemini AI
assistant window. This causes an iframe to be opened in the background,
which loads the URL. However, if the URL is malicious, it can execute
arbitrary code on the victim's computer.
The Gemini Assistant plugin amplifies the impact of this exploit by
allowing attackers to embed malicious URLs into Gemini capsules. When a
user hovers over a Gemini capsule, the malicious URL is loaded in the
iframe and the exploit is triggered.

Impact
This exploit could allow attackers to:
Execute arbitrary code on the victim's computer
Steal sensitive data, such as passwords and credit card numbers
Install malware
Take control of the victim's computer
