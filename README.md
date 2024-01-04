# OffSec Reporting using SysReptor
<h1 align="center">
    <br>
    <a href="https://docs.sysreptor.com/"><img src="/assets/Banner-SysReptor-OffSec.svg" width="100%" alt="SysReptor"></a>
</h1>

<p align="center">
<a href="https://github.com/syslifters/sysreptor/">
    <img src="https://img.shields.io/github/stars/Syslifters/sysreptor?color=yellow&style=flat-square">
</a>
<a href="https://github.com/syslifters/sysreptor/releases/latest">
    <img src="https://img.shields.io/github/v/release/syslifters/sysreptor?color=green&style=flat-square">
</a>
<a href="https://github.com/syslifters/sysreptor/releases/latest">
    <img src="https://img.shields.io/github/release-date/syslifters/sysreptor?color=blue&style=flat-square">
</a>
<a href="https://github.com/syslifters/sysreptor/releases/latest">
    <img src="https://img.shields.io/github/repo-size/syslifters/sysreptor?color=red&style=flat-square">
</a>
<a href="https://www.linkedin.com/company/syslifters/">
    <img src="https://img.shields.io/badge/-Linkedin-blue?style=flat-square&logo=linkedin">
</a>
<a href="https://twitter.com/intent/user?screen_name=sysreptor">
    <img src="https://img.shields.io/twitter/follow/sysreptor?style=social">
</a>
</p>

<h4 align="center">Pentest Reporting made easy: Design in HTML, Write in Markdown, Render to PDF. Self-hosted or Cloud.</h4>

---

## OffSec Reporting
This is our [OffSec](https://www.offsec.com/) reporting repository showcasing OffSec reports created with [SysReptor](https://github.com/Syslifters/sysreptor). Write your OffSec OSCP, OSWP, OSEP, OSWA, OSWE, OSED, OSMR, OSEE, OSDA reports.  
Feedback is very welcome! ❤️

<h2 align="center">🚀 Sign up <a class="md-button" href="https://oscp.sysreptor.com/oscp/signup/">here</a> (it's free)</h2>

Already have an account? [Login here.](https://labs.sysre.pt)
<br>

### Prefer self-hosting (also free)?

1. [Install](https://docs.sysreptor.com/setup/installation/) SysReptor 
2. Import all OffSec Designs:

```shell linenums="1"
cd sysreptor/deploy
url="https://docs.sysreptor.com/assets/offsec-designs.tar.gz"
curl -s "$url" | docker compose exec --no-TTY app python3 manage.py importdemodata --type=design
```

<h4>💡 Have a look at our <a class="md-button" href="https://docs.sysreptor.com/">documentation</a>.</h4>
<br>

PS: Are you missing a template, have feedback or any other questions?  
Let us know! Open an issue or [mail us](https://docs.sysreptor.com/contact-us/) and are happy to help you.

Happy Reporting! 🦖  


## Your Benefits
💲 Free  
📝 Write in markdown  
⚙️ Render to PDF  
🛡️ OSCP, OSWP, OSEP, OSWA, OSWE, OSED, OSMR, OSEE, OSDA  
🚀 Fully customizable  
👌 No local software troubleshooting


## Your OffSec Report Within Minutes
![GIF](https://docs.sysreptor.com/images/oscp-reporting.gif)


## Offensive Security Report Templates*
### Penetration Testing
<p float="left">
<a href="https://docs.sysreptor.com/assets/reports/OSCP-Exam-Report.pdf" target="_blank">
<img width="250" alt="OSCP Exam Report" src="https://docs.sysreptor.com/assets/reports/OSCP-Exam-Report-Preview.png" style="border:1px solid;">
</a>

<a href="https://docs.sysreptor.com/assets/reports/OSCP-Lab-Report.pdf" target="_blank">
<img width="250" alt="OSCP Lab Report" src="https://docs.sysreptor.com/assets/reports/OSCP-Lab-Report-Preview.png" style="border:1px solid;">
</a>

<a href="https://docs.sysreptor.com/assets/reports/OSWP-Exam-Report.pdf" target="_blank">
<img width="250" alt="OSWP Exam Report" src="https://docs.sysreptor.com/assets/reports/OSWP-Exam-Report-Preview.png" style="border:1px solid;">
</a>
    
<a href="https://docs.sysreptor.com/assets/reports/OSEP-Exam-Report.pdf" target="_blank">
<img width="250" alt="OSEP Exam Report" src="https://docs.sysreptor.com/assets/reports/OSEP-Exam-Report-Preview.png" style="border:1px solid;">
</a>
  
### Web Application
<p float="left">
<a href="https://docs.sysreptor.com/assets/reports/OSWA-Exam-Report.pdf" target="_blank">
<img width="250" alt="OSWA Exam Report" src="https://docs.sysreptor.com/assets/reports/OSWA-Exam-Report-Preview.png" style="border:1px solid;">
</a>
    
<a href="https://docs.sysreptor.com/assets/reports/OSWE-Exam-Report.pdf" target="_blank">
<img width="250" alt="OSWE Exam Report" src="https://docs.sysreptor.com/assets/reports/OSWE-Exam-Report-Preview.png" style="border:1px solid;">
</a>

### Exploit Development
<p float="left">
    
<a href="https://docs.sysreptor.com/assets/reports/OSED-Exam-Report.pdf" target="_blank">
<img width="250" alt="OSED Exam Report" src="https://docs.sysreptor.com/assets/reports/OSED-Exam-Report-Preview.png" style="border:1px solid;"></a>
    
<a href="https://docs.sysreptor.com/assets/reports/OSMR-Exam-Report.pdf" target="_blank">
<img width="250" alt="OSMR Exam Report" src="https://docs.sysreptor.com/assets/reports/OSMR-Exam-Report-Preview.png" style="border:1px solid;"></a>
    
<a href="https://docs.sysreptor.com/assets/reports/OSEE-Exam-Report.pdf" target="_blank">
<img width="250" alt="OSEE Exam Report" src="https://docs.sysreptor.com/assets/reports/OSEE-Exam-Report-Preview.png" style="border:1px solid;"></a>

### Security Operations
<p float="left">
    
<a href="https://docs.sysreptor.com/assets/reports/OSDA-Exam-Report.pdf" target="_blank">
<img width="250" alt="OSDA Exam Report" src="https://docs.sysreptor.com/assets/reports/OSDA-Exam-Report-Preview.png" style="border:1px solid;"></a>
    
</p>

*The cover pages are based on [noraj's](https://twitter.com/noraj_rawsec) great [OSCP LaTeX templates](https://github.com/noraj/OSCP-Exam-Report-Template-Markdown). The structure follows the official [OffSec](https://www.offsec.com/) reports (with kind permission by OffSec).

## Offensive Security Abbreviations
Exam acronym | Exam name                                         | Lab name                                   | Course designation
-------------|---------------------------------------------------|--------------------------------------------|-------------------
**OSCP**     | Offensive Security Certified Professional         | PWK         | Penetration Testing with Kali Linux        | PEN-200
**OSWP**     | Offensive Security Wireless Professional          | WNA         | Offensive Security Wireless Attacks        | PEN-210
**OSEP**     | Offensive Security Experienced Penetration Tester | ETBD        | Evasion Techniques and Breaching Defenses  | PEN-300
**OSWA**     | Offensive Security Web Assessor                   | WAKL        | Web Attacks with Kali Linux                | WEB-200
**OSWE**     | Offensive Security Web Expert                     | AWAE        | Advanced Web Attacks and Exploitation      | WEB-300
**OSED**     | Offensive Security Exploit Developer              | WUMED       | Windows User Mode Exploit Development      | EXP-301
**OSMR**     | Offensive Security macOS Researcher               | MCB         | macOS Control Bypasses                     | EXP-312
**OSEE**     | Offensive Security Exploitation Expert            | AWE         | Advanced Windows Exploitation              | EXP-401
**OSDA**     | Offensive Security Defense Analyst                | SODA        | Security Operations and Defensive Analysis | SOC-200

<br>
<a href="https://syslifters.com">https://syslifters.com</a>
