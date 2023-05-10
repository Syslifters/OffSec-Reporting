# Offensive Security Reporting using SysReptor
Hello 👋 we are the Syslifters, the brainos behind SysReptor. SysReptor is a fully customisable, offensive security reporting tool designed for pentesters, red teamers and other security-related people alike. You can create designs based on simple HTML and CSS, write your reports in user-friendly Markdown and convert them to PDF with just a single click - in the cloud or on-premise!

We have also prepared many report designs, such as OffSec Lab and Exam Report Templates (fully customizable ofc). Try it out and use SysReptor for free to write your OffSec OSCP, OSEE, OSEP, OSWE, OSWP reports. Feedback is very welcome! 🙌

<br>

<p align="center">
    <a class="md-button" href="https://docs.sysreptor.com/"><img width="100" src="https://docs.sysreptor.com/images/logo-invert.svg" alt="Logo SysReptor"></a>
</p>
<p align="center">
SysReptor makes Pentest Reporting easy.<br>
Design your report in HTML.<br>
Write in Markdown.<br>
Render to PDF.<br>
On-Premise.<br>
Or Cloud.<br>
❤️<br>
</p>

<h2 align="center">🚀 Sign up <a class="md-button" href="https://cloud.sysreptor.com/oscp/signup/">here</a></h2>
<br>

<h3>Prefer self-hosting?</h3>

1. [Install](/setup/installation/) SysReptor 
2. Import all OffSec Designs:

```shell linenums="1"
cd sysreptor/deploy
url="https://docs.sysreptor.com/assets/offsec-designs.tar.gz"
curl -s "$url" | docker compose exec --no-TTY app python3 manage.py importdemodata --type=design
```

<h4>💡 Have a look at our documentation <a class="md-button" href="https://docs.sysreptor.com/">here</a></h4>
<br>

P.S. you are missing a specific template, have feedback or any other requests?  
Just let us know! Open an issue or mail us and we'll have a look and come back to you.

Happy Reporting! :)  
<b>Team Syslifters</b> 🦖  
<a href="https://syslifters.com">https://syslifters.com</a>
<br>
<br>

## Your Benefits
💲 Free  
📝 Write in markdown  
⚙️ Render your report to PDF  
🛡️ OSCP, OSEE, OSEP, OSWE, OSWP  
🚀 Fully customizable  
🎉  No need for Word  
👌  No local software troubleshooting

<br>

## Your Offensive Security Report Within Minutes
![GIF](https://github.com/Syslifters/OSCP-Reporting/blob/main/oscp-reporting.gif)

<br>

## Offensive Security Report Templates*
<p float="left">
<a href="https://docs.sysreptor.com/assets/reports/OSCP-Exam-Report-Demo.pdf">
<img width="250" alt="OSCP Exam Report" src="https://docs.sysreptor.com/assets/reports/OSCP-Exam-Report-Demo-Preview.png" style="border:1px solid;">
</a>

<a href="https://docs.sysreptor.com/assets/reports/OSCP-Lab-Report.pdf" target="_blank">
<img width="250" alt="OSCP Lab Report" src="https://docs.sysreptor.com/assets/reports/OSCP-Lab-Report-Preview.png" style="border:1px solid;">
</a>

<a href="https://docs.sysreptor.com/assets/reports/OSEE-Exam-Report.pdf" target="_blank">
<img width="250" alt="OSEE Exam Report" src="https://docs.sysreptor.com/assets/reports/OSEE-Exam-Report-Preview.png" style="border:1px solid;"></a>

    

<p float="left">
<a href="https://docs.sysreptor.com/assets/reports/OSEP-Exam-Report.pdf" target="_blank">
<img width="250" alt="OSEP Exam Report" src="https://docs.sysreptor.com/assets/reports/OSEP-Exam-Report-Preview.png" style="border:1px solid;">
</a>

<a href="https://docs.sysreptor.com/assets/reports/OSWE-Exam-Report.pdf" target="_blank">
<img width="250" alt="OSWE Exam Report" src="https://docs.sysreptor.com/assets/reports/OSWE-Exam-Report-Preview.png" style="border:1px solid;">
</a>

<a href="https://docs.sysreptor.com/assets/reports/OSWP-Exam-Report.pdf" target="_blank">
<img width="250" alt="OSWP Exam Report" src="https://docs.sysreptor.com/assets/reports/OSWP-Exam-Report-Preview.png" style="border:1px solid;">
</a>
</p>

*The cover pages are based on [noraj's](https://twitter.com/noraj_rawsec) great [OSCP LaTeX templates](https://github.com/noraj/OSCP-Exam-Report-Template-Markdown). The structure follows the official [OffSec](https://www.offsec.com/) reports (with kind permission by OffSec).

<br>

## Offensive Security Abbreviations

Exam acronym | Exam name                                         | Lab acronym | Lab name                                   | Course designation
-------------|---------------------------------------------------|-------------|--------------------------------------------|-------------------
**OSCP**     | Offensive Security Certified Professional         | PWK         | Penetration Testing with Kali Linux        | PEN-200
**OSWP**     | Offensive Security Wireless Professional          | OSWA        | Offensive Security Wireless Attacks        | PEN-210
**OSEP**     | Offensive Security Experienced Penetration Tester | ETBD        | Evasion Techniques and Breaching Defenses  | PEN-300
**OSWE**     | Offensive Security Web Expert                     | AWAE        | Advanced Web Attacks and Exploitation      | WEB-300
**OSEE**     | Offensive Security Exploitation Expert            | AWE         | Advanced Windows Exploitation              | EXP-401
