# Application Security Learning Resources

This is a self-paced curriculum for learning application security, focusing on penetration testing (pentesting) and secure coding. Below are online tutorials, books, and other resources to help you build a strong foundation. Explore these at your own pace, and feel free to track your progress in this repository!

## Online Tutorials & Courses

### Penetration Testing Focus
  - **Burp Suite Academy (Web Security Academy)**  
  - **Link**: [portswigger.net/web-security](https://portswigger.net/web-security)  
  - **Description**: Free, interactive training from PortSwigger, the creators of Burp Suite. Covers web application vulnerabilities with hands-on labs (190+ labs as of 2025). Perfect for learning pentesting techniques and using Burp Suite Community Edition (free version). Start with the basics and progress to advanced topics like XSS, SQL injection, and SSRF.  
  - **Suggested Task**: Complete the "Apprentice" level labs first, then move to "Practitioner" labs.

- **TryHackMe - Web Fundamentals and Pentesting**  
  - **Link**: [tryhackme.com](https://tryhackme.com)  
  - **Description**: A beginner-friendly platform with free and paid rooms. Start with "Web Fundamentals" and "OWASP Top 10" rooms to understand vulnerabilities, then explore pentesting-specific rooms like "Burp Suite Basics" and "Web Hacking 101."  
  - **Suggested Task**: Finish the free "Complete Beginner" path and document your learnings.

- **Hack The Box Academy**  
  - **Link**: [academy.hackthebox.com](https://academy.hackthebox.com)  
  - **Description**: Offers free and premium interactive modules on web pentesting, from basic HTTP concepts to exploiting vulnerabilities. Great for hands-on practice with real-world scenarios.  
  - **Suggested Task**: Start with the free "Introduction to Web Applications" module.

- **PentesterLab**  
  - **Link**: [pentesterlab.com](https://pentesterlab.com)  
  - **Description**: Provides free and paid labs focused on web application security. The free "Essentials" badge covers key vulnerabilities like SQL injection and XSS. Labs come with detailed write-ups.  
  - **Suggested Task**: Earn the free "Essentials" badge and explore one paid exercise if budget allows.

### Secure Coding Focus
- **OWASP Top 10**  
  - **Link**: [https://owasp.org/Top10/](https://owasp.org/Top10/)  
  - **Description**: OWASP TOP 10 introduces common vulnerabilities found in software
  - **Suggested Task**: Review the vulnerabilities and understand how they present themself in applications

- **OWASP Juice Shop**  
  - **Link**: [owasp.org/www-project-juice-shop/](https://owasp.org/www-project-juice-shop/)  
  - **Description**: A deliberately insecure web app for learning secure coding and pentesting. Includes challenges tied to the OWASP Top 10. Install it locally or use the public instance to practice finding and fixing vulnerabilities.  
  - **Suggested Task**: Install Juice Shop and complete 5 challenges from the scoreboard.

- **Microsoft Learn - Guide to Secure .NET Development with OWASP Top 10**  
  - **Link**: [https://learn.microsoft.com/en-us/training/modules/owasp-top-10-for-dotnet-developers/](https://learn.microsoft.com/en-us/training/modules/owasp-top-10-for-dotnet-developers/)  
  - **Description**: Free course on secure coding in .NET, aligned with OWASP Top 10. Beginner-friendly with practical examples on input validation and more.  
  - **Suggested Task**: Finish the introductory modules and write a short summary.

### Python for Security
- **Learn Python - Codecademy**  
  - **Link**: [codecademy.com/learn/learn-python-3](https://www.codecademy.com/learn/learn-python-3)  
  - **Description**: A free, interactive Python 3 course tailored for beginners. Covers basics like variables, loops, and functions, with optional premium content. Python is widely used in security for scripting pentesting tools and automating tasks (e.g., with Burp Suite).  
  - **Suggested Task**: Complete the free "Python 3" course and write a simple script to parse a text file (e.g., a log file).

### Git and GitHub Basics
- **GitHub Learning Lab - Introduction to GitHub**  
  - **Link**: [skills.github.com](https://skills.github.com)  
  - **Description**: A free, interactive tutorial by GitHub that teaches Git basics (commit, push, pull) and GitHub workflows (repos, pull requests). Perfect for beginners to learn version control hands-on within a GitHub environment.  
  - **Suggested Task**: Complete the "Introduction to GitHub" course and create a small repo to track your progress in this curriculum.

## Books
### Penetration Testing

- **Black Hat Python**
  - [https://a.co/d/gFDme9C](https://a.co/d/gFDme9C) 
  - **Authors**: Justin Seitz, Tim Arnold
  - **Description**: When it comes to creating powerful and effective hacking tools, Python is the language of choice for most security analysts. In this second edition of the bestselling Black Hat Python, you’ll explore the darker side of Python’s capabilities: everything from writing network sniffers, stealing email credentials, and bruteforcing directories to crafting mutation fuzzers, investigating virtual machines, and creating stealthy trojans.
  - **Suggested Task**: Read and Build along

- **The Web Application Hacker’s Handbook (2nd Edition)**
- [https://a.co/d/gW91Mq1](https://a.co/d/gW91Mq1)  
  - **Authors**: Dafydd Stuttard, Marcus Pinto  
  - **Description**: A comprehensive guide to web app pentesting by the creators of Burp Suite. Covers techniques, tools, and vulnerabilities in detail. Available in print or e-book.  
  - **Suggested Task**: Read Chapters 1-4 and experiment with Burp Suite alongside it.
  - Might be a little outdated since it was published in 2011

- **Web Hacking 101**
  - [https://leanpub.com/web-hacking-101](https://leanpub.com/web-hacking-101  
  - **Authors**: Peter Yaworski  
  - **Description**: A beginner-friendly book on web pentesting and bug bounty hunting. Explains real-world vulnerabilities with examples. Free online version available via Leanpub (pay-what-you-want).  
  - **Suggested Task**: Read the free version and replicate one exploit locally.

### Secure Coding
- **Secure Coding in C and C++ (2nd Edition)**
  - [https://a.co/d/94j1jpt](https://a.co/d/94j1jpt) 
  - **Author**: Robert C. Seacord  
  - **Description**: A deep dive into writing secure code in C/C++, focusing on common vulnerabilities and mitigation techniques. Great for understanding low-level security concepts.  
  - **Suggested Task**: Study Chapter 2 (Strings) and write a secure string-handling function.

- **The Tangled Web: A Guide to Securing Modern Web Applications**
  - [https://a.co/d/fyTXOCb](https://a.co/d/fyTXOCb)
  - **Author**: Michal Zalewski  
  - **Description**: Explores the complexities of web security and how to secure applications against modern threats. Slightly dated (2011) but still foundational.  
  - **Suggested Task**: Read Part I and summarize key takeaways.

## Additional Resources

- **OWASP Testing Guide)**  
  - **Link**: [[owasp.org/Top10/](https://owasp.org/www-project-web-security-testing-guide/latest/)](https://owasp.org/www-project-web-security-testing-guide/latest/)  
  - **Description**: TThe WSTG is a comprehensive guide to testing the security of web applications and web services. Created by the collaborative efforts of cybersecurity professionals and dedicated volunteers, the WSTG provides a framework of best practices used by penetration testers and organizations all over the world  
  - **Suggested Task**: Use the testing guide while testing vulnerable application like Juice Shop

- **OWASP Secure Coding Practices Quick Reference Guide**  
  - **Link**: [https://owasp.org/www-project-developer-guide/release/](https://owasp.org/www-project-developer-guide/release/)  
  - **Description**: A concise, free checklist of secure coding best practices. Perfect for quick reference during development.  
  - **Suggested Task**: Apply 3 practices to a small coding project.

- **Vulnerable Web Apps Directory**  
  - **Link**: [https://owasp.org/www-project-vulnerable-web-applications-directory/](https://owasp.org/www-project-vulnerable-web-applications-directory/)  
  - **Description**: A list of intentionally vulnerable apps (e.g., DVWA, WebGoat) for practicing pentesting and secure coding fixes.  
  - **Suggested Task**: Install a vulnerable application or use an online version and use the OWASP testing guide to test the application

- **Bug Hunting Methodology**  
  - **Link**: [https://github.com/jhaddix/tbhm](https://github.com/jhaddix/tbhm)  
  - **Description**: How to find bugs and get paid.  
  - **Suggested Task**: Walk through Jason's course 

## Tips for Success
- **Start Simple**: Focus on these resources first (Burp Suite Academy, OWASP Top 10, Black Hat Python).
- **Hands-On Practice**: Set up a local lab (e.g., using Docker or VirtualBox) to test vulnerabilities safely.
- **Learn Python Early**: Python will help you automate tasks and write custom security tools—start with Codecademy’s course.
- **Master Git**: Use the GitHub Learning Lab to get comfortable with version control, then track all your work in this repo.
- **Document Progress**: Log what you’ve learned, including write-ups of labs, book chapters, or Python scripts.

Happy learning, and welcome to the world of application security!
