<p align="center">
  <a href="https://github.com/aramos-gua/cybersecurity/raw/main/Phishing%20Report.pdf">
    <img src="https://img.shields.io/badge/Download-Phishing_Reports-red?style=for-the-badge&logo=adobeacrobatreader" alt="Download Phishing Report">
  </a>
</p>
<br>
Analyst: Alejandro Ramos<br>
Date: May 29th, 2025<br>
Type: Simulated Phishing (Company Awareness Test)<br>
Medium: E-mail<br>
Status: Reported<br>
Description: Received an internal-looking e-mail stating the need for a critical security update.<br>
<br>
<img width="753" height="386" alt="image" src="https://github.com/user-attachments/assets/ff5ca31b-590c-4b16-83b8-d80ecec3005d" />
<br>
Indicators of Phishing:<br>
• “Reply-to” address does not match sender domain (Shown in screenshot). Indicator of possible spoofing.<br><br>
• All hypertexts found in the e-mail directs to the same URL, which is a non-company domain. (See screenshot of original email).<br><br>
• Language designed to call for action and trigger urgency (“It’s really very urgent”, “download and install the following”, “immediately”).<br><br>
• No specific names or references to internal systems.<br><br>
• Besides technicalities, downloading and installing a major security update will always be done by the Administrator. Usually, they would deploy the update to the computers via network, and there should not be any engagement from the user. This also makes the call to action suspicious.<br><br>
Screenshots and Analysis:<br>
<img width="585" height="93" alt="image" src="https://github.com/user-attachments/assets/fb6eeb33-9855-4653-9c55-ae48a2d5b6f1" />
<br>
• The From and Reply To email don’t match. But more than that, if we take a closer look at the domain (indicated by the @ sign in an email) we can see that the Reply To email is “disguising” as the legitimate domain. In “company-limited.co.uk”, company-limited is the domain name. However, in “company.com-host.net”, company.com-host is the domain name.<br><br>
• The TLD (Top Level Domain) “.co.uk” and “.net” are not the same.
<img width="607" height="735" alt="image" src="https://github.com/user-attachments/assets/1a4db22a-b608-4975-8bba-93627ad993eb" />
<br>
• As you can see, all hyperlinks redirect the user who clicks on them to the same exact URL. No matter if we click the email, the supposed link to download the software update or the Data Protection policy. The person’s intent is for us to click something. Anything.<br><br>
Recommendation:<br>
• Do not engage in any way. Mark as phishing and report.<br>
• If part of the analysis team, inspecting the URL within a sandbox environment such as a Virtual Machine would be useful to identify what kind of threat is targeting the network.<br>
