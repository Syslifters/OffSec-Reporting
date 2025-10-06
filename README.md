# OffSec Reporting using SysReptor
<h1 align="center">
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

<h4 align="center">An easy and customizable pentest reporting platform designed to simplify pentest report creation for security professionals.
</h4>

---

## OffSec Reporting
This repository showcases [OffSec](https://www.offsec.com/) report templates built with [SysReptor](https://github.com/Syslifters/sysreptor), a fully customizable pentest reporting platform. 

Supported certifications:  
**OSCP+**, **OSEP**, **OSWP**, **OSWA**, **OSWE**, **OSED**, **OSMR**, **OSEE**, **OSDA**, **OSIR**, **OSTH**  

Focus on hacking, not the formatting. Best of luck with your OffSec journey! ❤️

<h3 align="center">
    <a href="https://offsec.sysreptor.com/offsec/signup"><img src="/assets/Reptor_Schild_Signup.svg" width="15%" alt="Signup"></a>
</h3>
<h2 align="center">🚀 Sign up <a class="md-button" href="https://offsec.sysreptor.com/offsec/signup/">here</a> (it's free)</h2>

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

Missing a template or have questions? Open an [issue or contact us](https://docs.sysreptor.com/contact-us/). We're happy to help.

## Your Benefits
💲 Free  
📝 Write in markdown  
⚙️ Render to PDF  
🛡️ OSCP+, OSEP, OSWP, OSWA, OSWE, OSED, OSMR, OSEE, OSDA, OSIR, OSTH  
🚀 Fully customizable  
👌 No local software troubleshooting


## Your OffSec Report Within Minutes
![GIF](https://docs.sysreptor.com/images/offsec-reporting.gif)

## Offensive Security Report Templates
### Penetration Testing
<p float="left">
<a href="https://docs.sysreptor.com/assets/reports/OffSec-OSCP-Exam-Report.pdf" target="_blank">
<img width="250" alt="OffSec OSCP+ Exam Report" src="https://docs.sysreptor.com/assets/reports/OffSec-OSCP-Exam-Report-Preview.png" style="border:1px solid;">
</a>

<a href="https://docs.sysreptor.com/assets/reports/OffSec-OSWP-Exam-Report.pdf" target="_blank">
<img width="250" alt="OffSec OSWP Exam Report" src="https://docs.sysreptor.com/assets/reports/OffSec-OSWP-Exam-Report-Preview.png" style="border:1px solid;">
</a>

<a href="https://docs.sysreptor.com/assets/reports/OffSec-OSEP-Exam-Report.pdf" target="_blank">
<img width="250" alt="OffSec OSEP Exam Report" src="https://docs.sysreptor.com/assets/reports/OffSec-OSEP-Exam-Report-Preview.png" style="border:1px solid;">
</a>
  
### Web Application Security
<p float="left">
<a href="https://docs.sysreptor.com/assets/reports/OffSec-OSWA-Exam-Report.pdf" target="_blank">
<img width="250" alt="OffSec OSWA Exam Report" src="https://docs.sysreptor.com/assets/reports/OffSec-OSWA-Exam-Report-Preview.png" style="border:1px solid;">
</a>

<a href="https://docs.sysreptor.com/assets/reports/OffSec-OSWE-Exam-Report.pdf" target="_blank">
<img width="250" alt="OffSec OSWE Exam Report" src="https://docs.sysreptor.com/assets/reports/OffSec-OSWE-Exam-Report-Preview.png" style="border:1px solid;">
</a>

### Exploit Development
<p float="left">
    
<a href="https://docs.sysreptor.com/assets/reports/OffSec-OSED-Exam-Report.pdf" target="_blank">
<img width="250" alt="OffSec OSED Exam Report" src="https://docs.sysreptor.com/assets/reports/OffSec-OSED-Exam-Report-Preview.png" style="border:1px solid;"></a>

<a href="https://docs.sysreptor.com/assets/reports/OffSec-OSMR-Exam-Report.pdf" target="_blank">
<img width="250" alt="OffSec OSMR Exam Report" src="https://docs.sysreptor.com/assets/reports/OffSec-OSMR-Exam-Report-Preview.png" style="border:1px solid;"></a>

<a href="https://docs.sysreptor.com/assets/reports/OffSec-OSEE-Exam-Report.pdf" target="_blank">
<img width="250" alt="OffSec OSEE Exam Report" src="https://docs.sysreptor.com/assets/reports/OffSec-OSEE-Exam-Report-Preview.png" style="border:1px solid;"></a>

### Defensive Security
<p float="left">

<a href="https://docs.sysreptor.com/assets/reports/OffSec-OSDA-Exam-Report.pdf" target="_blank">
<img width="250" alt="OffSec OSDA Exam Report" src="https://docs.sysreptor.com/assets/reports/OffSec-OSDA-Exam-Report-Preview.png" style="border:1px solid;"></a>

<a href="https://docs.sysreptor.com/assets/reports/OffSec-OSIR-Exam-Report.pdf" target="_blank">
<img width="250" alt="OffSec OSIR Exam Report" src="https://docs.sysreptor.com/assets/reports/OffSec-OSIR-Exam-Report-Preview.png" style="border:1px solid;"></a>

<a href="https://docs.sysreptor.com/assets/reports/OffSec-OSTH-Exam-Report.pdf" target="_blank">
<img width="250" alt="OffSec OSTH Exam Report" src="https://docs.sysreptor.com/assets/reports/OffSec-OSTH-Exam-Report-Preview.png" style="border:1px solid;"></a>

</p>

The structure follows the official [OffSec](https://www.offsec.com/) reports (with kind permission by OffSec).

## Offensive Security Abbreviations
Exam acronym | Exam name                                         | Lab name | Course name                                | Course designation
-------------|---------------------------------------------------|----------|--------------------------------------------|-------------------
**OSCP+**    | Offensive Security Certified Professional         | PWK      | Penetration Testing with Kali Linux        | PEN-200
**OSWP**     | Offensive Security Wireless Professional          | WiFu     | Offensive Security Wireless Attacks        | PEN-210
**OSEP**     | Offensive Security Experienced Penetration Tester | ETBD     | Evasion Techniques and Breaching Defenses  | PEN-300
**OSWA**     | Offensive Security Web Assessor                   | WAKL     | Web Attacks with Kali Linux                | WEB-200
**OSWE**     | Offensive Security Web Expert                     | AWAE     | Advanced Web Attacks and Exploitation      | WEB-300
**OSED**     | Offensive Security Exploit Developer              | WUMED    | Windows User Mode Exploit Development      | EXP-301
**OSMR**     | Offensive Security macOS Researcher               | OSMR     | macOS Control Bypasses                     | EXP-312
**OSEE**     | Offensive Security Exploitation Expert            | AWE      | Advanced Windows Exploitation              | EXP-401
**OSDA**     | Offensive Security Defense Analyst                | OSDA     | Security Operations and Defensive Analysis | SOC-200
**OSIR**     | Offensive Security Incident Responder             | OSIR     | Foundational Incident Response             | IR-200
**OSTH**     | Offensive Security Threat Hunter                  | OSTH     | Foundational Threat Hunting                | TH-200

<h1 align="center">
    <a href="https://docs.sysreptor.com/"><img src="/assets/Tower_SysReptor.svg" width="100%" alt="SysReptor"></a>
</h1>
