# Project : Phishing-Attack-Investigation
## Introduction
Phishing attacks are among the most widespread threats in cybersecurity. Attackers often impersonate trusted sources to trick users into revealing sensitive data like passwords or credit card details.
This hands-on project walks you through identifying, analyzing, and reporting phishing emails in a simulated environment.

## Pre-requisites

Before starting, you should be familiar with:

- Basics of how email systems work  
- Common phishing techniques 
- Basic knowledge of email analysis tools

## Lab Set-up and Tools
To conduct a phishing attack investigation, you'll need a simulated environment that includes tools for email analysis. Here’s a detailed setup:

## 1. Email Server Simulation
Description: Set up a local email server or use an email simulation service to receive and send emails. This allows you to safely analyze phishing emails without exposing your real email account to potential risks.

Tools:
- Halon MTA: A flexible and powerful email server software.
- MailCatcher: A simple SMTP server which captures emails sent to it for later inspection.
- Mutt: A small but powerful text-based email client for UNIX operating systems.

## 2. Phishing Email Samples
Description: Obtain a set of phishing email samples to analyze. These can be sourced from public repositories, cybersecurity forums, or created for educational purposes.

Tools:
- PhishTank: A collaborative clearing house for data and information about phishing on the Internet.
- OpenPhish: A service providing free access to a continuously updated list of active phishing URLs.

## 3. Email Analysis Tools
Description: Tools used to inspect, dissect, and validate the content and metadata of emails to identify signs of phishing, spoofing, or malicious intent.
- Thunderbird: An open-source email client by Mozilla that supports multiple email accounts and has powerful email management features.
- PhishTool: A tool specifically designed for analyzing and investigating phishing emails.
- Email Header Analysis Tools: Online tools like MXToolbox or EmailHeaders.net which can parse and analyze email headers.

## Setting Up the Lab Environment
## Step 1: Install Thunderbird
- Download and install **Thunderbird** from the [official website](https://www.thunderbird.net/en-US/).
- Set up an email account using either a real or simulated email server (like MailCatcher)

Set up an email account using either a real or simulated email server.

## Step 2: Set Up Email Server Simulation
Install and run MailCatcher using the following commands:

<pre>gem install mailcatcher mailcatcher</pre>
Access the MailCatcher interface at: http://127.0.0.1:1080/ to view captured emails in your browser.

## Step 3: Obtain Phishing Email Samples
Download phishing email samples from PhishTank and OpenPhish.Import the samples into Thunderbird for analysis.

## Step 4: Install and Configure PhishTool
Register for a free account at PhishTool.Follow their instructions to integrate it with Thunderbird for phishing analysis.

##  Exercises


### Exercise 1: Identifying Phishing Emails

Objective: Learn to recognize phishing emails based on common characteristics.
Steps:
1. Set up your email analysis environment using Thunderbird.
2. Load the provided phishing email samples into Thunderbird.
3. Identify and document common phishing indicators:
   - Suspicious sender addresses
   - Generic greetings
   - Urgent language
   - Suspicious or misleading links

Expected Output:
- A list of identified phishing emails with documented indicators.

### Exercise 2: Analyzing Email Headers

Objective: Understand how to analyze email headers to uncover the email's origin.

Steps:
1. Select a phishing email from Exercise 1.
2. Open the email header in Thunderbird.
3. Analyze the header to find:
   - Sender's IP address
   - Email servers the message passed through
   - Any spoofing or discrepancies in sender info

Expected Output:
- A detailed report with IP addresses and mail server path analysis.

### Exercise 3: Investigating Suspicious Links

Objective: Learn to analyze phishing links without endangering your system.

Steps:
1. Identify suspicious links from phishing emails.
2. Use safe tools like:
   - [VirusTotal](https://www.virustotal.com/)
   - [PhishTool](https://phishtool.com/)
3. Record the:
   - Risk level
   - Redirection behavior
   - Any malicious behavior

Expected Output:
- A report containing screenshots and findings for each suspicious link.

### Exercise 4: Reporting the Phishing Attempt

Objective: Create a complete report documenting your phishing investigation.

Steps:
1. Compile all your findings from Exercises 1–3.
2. Structure your report with these sections:
   - Executive summary
   - Phishing email indicators
   - Header analysis
   - Link investigation results
   - Preventive recommendations
3. Present your report professionally in a PDF or Markdown format.

Expected Output:
- A complete phishing investigation report ready for submission or presentation.

## Additional Resources

- [PhishTool](https://phishtool.com/)
- [VirusTotal](https://www.virustotal.com/)
- [How to View Email Headers](https://mxtoolbox.com/public/content/emailheaders/)



