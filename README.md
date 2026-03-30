# Infosec / Hacking - RBOIS

An evolving resource page for hackers, researchers, and students looking to delve into the security field.

## Table of Contents

* [Communities](#communities)
* [Researchers and People Worth Following](#researchers-and-people-worth-following)
* [Tools](#tools)
* [Writeups and Case Studies](#writeups-and-case-studies)
* [Events and Conferences](#events-and-conferences)
* [Discoveries](#rabbit-holes)
* [Obscure Resources](#obscure-resources)
* [Starter Projects](#starter-projects)


## Communities



### Reddit

|Subreddits|Focus|
|-|-|
|[r/netsec](https://www.reddit.com/r/netsec/)|This group focuses on technical security news and research on existing vulnerabilities.|
|[r/hacking](https://www.reddit.com/r/hacking/)|Promotes ethical hacking discussions. Covers broad topics like tools, guides and security.|
|[r/cybersecurity](https://www.reddit.com/r/cybersecurity/)|General discussions on industry news, threat findings and careers.|
|[r/HowToHack](https://www.reddit.com/r/HowToHack/)|Learning-focused. Great for self-directed study.|
|[r/osint](https://www.reddit.com/r/OSINT/)|Open source intelligence. Investigations, tactics and tools.|

### 

### Discord Servers

|Servers|Focus|
|-|-|
|[NahamSec](https://discord.com/invite/nahamsec-598608711186907146)|Bug bounty, recon, offensive security. Run by Ben Sadeghipour.|
|[John Hammond](https://discord.com/invite/mQQ5NsTbfF)|Members promote cybersecurity education and CTFs.|
|[TryHackMe](https://discord.com/invite/tryhackme)|Threat hunting Q\&A and knowledge sharing based on the TryHackMe platform.|
|[SANS Offensive Ops](https://discord.com/invite/f3R93W38gs)|Discusses SANS certs, pentesting, cybersecurity events, and opportunities.|

### 

### In-Person and Meetup Communities

* [DEF CON Groups (DCGs)](https://defcongroups.org/) - Local hacker groups in 200+ cities worldwide.
* [OWASP Local Chapters](https://owasp.org/chapters/) - Web security focused. Good source for appsec networking.

### 

### Practice Platforms

* [Hack The Box](https://hackthebox.com) - Gamified labs designed for cyber security training.
* [TryHackMe](https://tryhackme.com) - Guided cybersecurity for beginners across different disciplines.
* [PortSwigger Web Security Academy](https://portswigger.net/web-security) - Free web app security training.
* [VulnHub](https://www.vulnhub.com/) - Downloadable vulnerable VMs for local practice.



## Researchers and People Worth Following

### Investigative Journalists

These people break the stories everyone else republishes.

* [Ellen Nakashima](https://www.washingtonpost.com/people/ellen-nakashima/) - Washington Post Jounralist that covers the intersection of technology and national security.
* [Kim Zetter](https://www.wired.com/author/kim-zetter/) - Wrote Countdown to Zero Day (Stuxnet). Covers national security and cyber warfare.
* [Zack Whittaker](https://techcrunch.com/author/zack-whittaker/) - TechCrunch Security Editor that discusses worldwide breaches and hacker groups.



### People of of Interest

* [Marcus Hutchins / MalwareTech](https://malwaretech.com/) - Stopped 2017 WannaCry ransomware attack. Publishes malware analysis content.
* [Troy Hunt](https://www.troyhunt.com/) - Creator of Have I Been Pwned.
* [Samy Kamkar](https://samy.is/) - Created the MySpace Samy worm at 19. Now does hardware implants, wireless attacks, and acoustic eavesdropping research.
* [Mikko Hypponen](https://mikko.hypponen.com/) - Chief Research Officer at WithSecure. 34 years hunting malware.
* [Dave Kennedy](https://www.trustedsec.com/) - Founded TrustedSec, co-authored the PTES standard, created the Social Engineering Toolkit.



### Blogs and Publications

* [The Hacker News](https://thehackernews.com/) - Fast-moving security news and breaking vulnerabilities.
* [ISACA Blogs](https://www.isaca.org/resources/news-and-trends) - Expert blogs on IT trends, IT governance and risk from a global perspective.
* [Dark Reading](https://www.darkreading.com/) - Enterprise security news and threat intel.
* [Risky Business Podcast](https://risky.biz/) - Patrick Gray's weekly infosec podcast.
* [Darknet Diaries](https://darknetdiaries.com/) - Includes storytelling podcast about hacks, breaches, and espionage.



### Companies Publishing Research Worth Reading

* [Google Project Zero](https://googleprojectzero.blogspot.com/) - Dives into zero day vulnerability research.
* [Mandiant / Google Threat Intelligence](https://www.mandiant.com/resources/blog) - APT tracking and incident reports.





## Tools

### Meta-Lists

These curated list of tools for diving into different cybersecurity fields.

* [Awesome OSINT](https://github.com/jivoi/awesome-osint) - Provides a list of OSINT resources.
* [Awesome OSINT For Everything](https://github.com/Astrosp/Awesome-OSINT-For-Everything) - Organized by domain: geo, social, darknet, email, phone, crypto, and more.
* [Awesome Pentest](https://github.com/enaqx/awesome-pentest) - Penetration testing tools, resources, and references.
* [Offensive OSINT Tools](https://github.com/wddadk/Offensive-OSINT-Tools) - A practical repository for red teamers.
* [Awesome Security Newsletters](https://github.com/TalEliyahu/awesome-security-newsletters) - Curated list of infosec newsletters.



### Reconnaissance and OSINT

|Tool|What It Does|
|-|-|
|[Recon-ng](https://github.com/lanmaster53/recon-ng)|Automates info fathering process using Python.|
|[Amass](https://github.com/owasp-amass/amass)|In-depth attack surface mapping and subdomain discovery.|
|[Sherlock](https://github.com/sherlock-project/sherlock)|Username hunting across 300+ social networks.|
|[theHarvester](https://github.com/laramies/theHarvester)|Email, domain, and people recon from public sources.|
|[holehe](https://github.com/megadose/holehe)|Check if an email is registered on 120+ sites.|
|[Subfinder](https://github.com/projectdiscovery/subfinder)|Fast passive subdomain enumeration.|
|[FOCA](https://github.com/ElevenPaths/FOCA)|Find metadata hidden in documents via Google, Bing, DuckDuckGo.|

### 

### Search Engines for Hackers

|Tool|What It Does|
|-|-|
|[Shodan](https://shodan.io)|Search engine for IOT devices.|
|[Censys](https://censys.io)|Host and website search via daily scans.|
|[GreyNoise](https://greynoise.io)|Distinguish targeted attacks from internet background noise.|
|[IntelX](https://intelx.io)|Search across breaches, pastes, and darknet.|
|[URLScan.io](https://urlscan.io)|Scan and analyze URLs. Screenshots and DOM capture.|
|[VirusTotal](https://virustotal.com)|Multi-AV scanning, file and URL analysis.|

### 

### Vulnerability Scanning and Exploitation

|Tool|What It Does|
|-|-|
|[Metasploit Framework](https://metasploit.com)|The exploit framework. Industry standard.|
|[Nuclei](https://github.com/projectdiscovery/nuclei)|Template-based vulnerability scanner.|
|[Burp Suite Community](https://portswigger.net/burp)|Web app proxy and interception tool.|
|[OWASP ZAP](https://www.zaproxy.org/)|Burp alternative|
|[SQLmap](https://sqlmap.org/)|Automatic SQL injection tool.|

### 

### Network and Traffic Analysis

* [Wireshark](https://www.wireshark.org/) - The packet analyzer.
* [nmap](https://nmap.org/) - Network discovery and security auditing.
* [Zeek](https://zeek.org/) - Network monitoring framework.
* [Scapy](https://scapy.net/) - Python packet manipulation library.

### 

### Hardware Hacking

* [Flipper Zero](https://flipperzero.one/) - Portable multi-tool. RFID, IR, sub-GHz, BadUSB.
* [Awesome Flipper Zero](https://github.com/djsime1/awesome-flipperzero) - Community apps and resources for Flipper.
* [HackRF One](https://greatscottgadgets.com/hackrf/) - Software-defined radio for RF hacking.
* [Proxmark3](https://proxmark.com/) - Professional RFID hacking and analysis tool.
* [Bus Pirate](http://dangerousprototypes.com/docs/Bus_Pirate) - Serial bus analyzer and JTAG debugging.



### AI Security Tools

* [Garak](https://github.com/leondz/garak) - LLM vulnerability scanner. Probes for prompt injection, hallucination, and toxic outputs.
* [PyRIT](https://github.com/Azure/PyRIT) - Microsoft's Python Risk Identification Toolkit for LLMs.
* [Promptmap](https://github.com/utkusen/promptmap) - Automated prompt injection testing.
* [OWASP Top 10 for LLM Applications](https://owasp.org/www-project-top-10-for-large-language-model-applications/) - An adapting framework for AI security.





### Operating Systems and Environments

* [Kali Linux](https://www.kali.org/) - THE pentester's OS.
* [Parrot OS](https://parrotlinux.org/) - Lighter Kali alternative with a privacy focus.
* [REMnux](https://remnux.org/) - Malware analysis distro.
* [SANS SIFT Workstation](https://www.sans.org/tools/sift-workstation/) - DFIR-focused environment.



## Writeups and Case Studies

### Writeup Archives and Aggregators

* [CTFtime.org Writeups](https://ctftime.org/writeups) - Searchable archive of CTF challenge writeups by event.
* [0x00sec](https://0x00sec.org/) - Community platform for hacking articles and tutorials.
* [HackTricks](https://book.hacktricks.xyz/) - Pentest techniques and attack reference organized by category.
* [Exploit Notes](https://exploit-notes.hdks.org/) - Concise notes on exploits and techniques.
* [HackerOne Hacktivity](https://hackerone.com/hacktivity) - Real bug bounty reports disclosed publicly.



### 

### Notable Case Studies

* [LockBit Unmasking - Analyst1 Diary Series](https://www.analyst1.com/lockbit) - Jon DiMaggio's OSINT-driven investigation tracking LockBitSupp to a real identity. He got there before federal agents.
* [Stuxnet - Symantec W32 Dossier](https://www.wired.com/2014/11/countdown-to-zero-day-stuxnet/) - Still the gold standard for nation-state malware analysis.
* [Project Zero - Spectre and Meltdown](https://googleprojectzero.blogspot.com/2018/01/reading-privileged-memory-with-side.html) - The hardware-level vulnerability that changed chip architecture.
* [Samy Kamkar - MySpace XSS Worm](https://samy.is/myspace/) - Original writeup of the fastest spreading worm in history.
* [Black Hat and DEF CON 2024 Research Roundup - TechCrunch](https://techcrunch.com/2024/08/12/best-hacks-security-research-black-hat-def-con-2024/) - Annual summary of top research presented at the cons.
* [Copilot AI Prompt Injection - Zenity, Black Hat 2024](https://www.zenity.io/blog/research/copilot-prompt-injection-microsoft-365-copilot) - Live demo of extracting bank account numbers from Microsoft Copilot via HTML injection.



## Events and Conferences

### Hacker Summer Camp

|Conference|Focus|Location|
|-|-|-|
|[DEF CON](https://defcon.org/)|Popular annual convention for hackers. Popular for its "villages" that offer a focus on specific security topics|Las Vegas, August|
|[Black Hat USA](https://blackhat.com/)|6 day conference on security research, training and briefings.|Las Vegas, august|
|[RSA Conference](https://www.rsaconference.com/)|Enterprise security. CISO-level networking.|San Francisco, May|
|[ShmooCon](https://www.shmoocon.org/)|Technical, hacker-culture, intimate.|Washington D.C., January|
|[USENIX Security](https://www.usenix.org/conference/usenixsecurity25)|Academic security research.|Various|
|[Red Team Village](https://redteamvillage.io/)|Offensive security village. Runs at DEF CON and independently.|Various|

### 

### Video and Media Archives

* [DEF CON Media Server](https://media.defcon.org/) - Decades of talks.
* [Black Hat YouTube](https://www.youtube.com/@BlackHatOfficialYT) - Free talks posted after the conference.



## Rabbit Holes

Things that came up during research that are worth going deeper on.



### The History of Phreaking

Phone phreaking in the 1970s gave birth to the entire hacker culture and the communities that followed.

* [John Draper / Cap'n Crunch](https://www.chaintech.network/blog/year-1971-john-draperthe-hacker-who-used-whistles-for-his-deeds/) - Discovered that a cereal box whistle produced exactly 2600 Hz, enough to hack AT\&T's phone network for free long distance calls.
* [Hacking before the internet](https://cybersecurityventures.com/phone-phreaking-hacking-before-the-internet/) - David Braue's history of phone phreaking.
* 

### 

### DEF CON Badge Hacking

* Every year DEF CON creates a custom electronic badge that is itself a puzzle and CTF. 
* [DEF CON Badge History](https://www.defcon.org/html/links/dc-badge.html) - Archive of every badge going back to the early cons.



### Warrant Canaries

A warrant canary is a publicly posted statement confirming that a service has not yet received a secret government subpoena. If the canary disappears, users know the service received one - without the service technically having to say so. A clever legal workaround with interesting implications.

* [EFF's Guide to Warrant Canaries](https://www.eff.org/deeplinks/2014/04/warrant-canary-faq) - The legal background and how they work.



### AI Prompt Injection

The intersection of LLMs and security is new territory and moving fast.

* [Indirect Prompt Injection - Simon Willison](https://simonwillison.net/2023/Apr/14/prompt-injection-attacks-against-gpt-4/) - The foundational explainer on what prompt injection actually is.
* [Copilot Prompt Injection Demo - Zenity, Black Hat 2024](https://www.zenity.io/blog/research/copilot-prompt-injection-microsoft-365-copilot) - Demonstrated live extraction of bank account numbers from a production AI assistant.
* [Garak LLM Scanner](https://github.com/leondz/garak) - Run automated vulnerability probes against LLMs yourself.
* [Prompt Injecting?](https://www.ibm.com/think/topics/prompt-injection) - The term "prompt injection" was coined by Riley Goodside in September 2022 in a single tweet. 



## Obscure Resources

Resources from different corners of the web that are surprisingly useful and not widely known.



### Mastodon and the Fediverse

The infosec community has a significant Mastodon presence, especially since the Twitter/X exodus. 

* [infosec.exchange](https://infosec.exchange/) - The main infosec Mastodon instance.
* [Lesley Carhart's Curated Infosec Follow Lists](https://tisiphone.net/2025/03/18/updated-infosec-mastodon-lists/) - Pre-built CSV files you can import directly into Mastodon to follow all the key infosec accounts at once.



### Mailing Lists

Disclosures and research often surface here first.

* [DEF CON Mailing List Archive](https://defcon.org/html/links/mailing-lists.html) - Historical list of hacker-community mailing lists maintained by DEF CON.
* [Seclists.org](https://seclists.org/) - Archive of security mailing lists including Full Disclosure, Bugtraq, and NMap.
* [Full Disclosure List](https://seclists.org/fulldisclosure/) - Public, unmoderated vulnerability disclosure.
* [OSS-Security](https://www.openwall.com/lists/oss-security/) - Open source software vulnerability disclosures.
* [SANS Internet Storm Center](https://isc.sans.edu/) - Daily threat updates from rotating handlers.



### Random points of interest

* [VX Underground](https://vx-underground.org/) - A large collection of malware source code and papers on the internet.
* [The Exploit Database](https://www.exploit-db.com/) - Offensive Security's public exploit archive which also has the Google Hacking Database.
* [PacketStorm Security](https://packetstormsecurity.com/) - Vulnerability archive, tools, and advisories running since 1998.
* [OpenSecurityTraining2](https://p.ost2.fyi/) - Free security courses.
* [pwn.college](https://pwn.college/) - Arizona State's free binary exploitation course.



## Starter Projects

Interesting projects for beginner hackers that I thought was interesting.



### Project 1 - Run the OverTheWire Gauntlet

OverTheWire's Bandit wargame is a popular onboarding challenge in the community. You start with zero access and work through 34 levels, each teaching a real Linux concept: file permissions, SSH, grep, cron, setuid binaries. No setup required - just SSH in and start.

Start here: [overthewire.org/wargames/bandit](https://overthewire.org/wargames/bandit/)

The progression: Bandit (Linux fundamentals) - Leviathan (SUID exploits) - Natas (web hacking) - Krypton (cryptography).

By documenting every level as you go, it can be an interesting GitHub post.



### Project 2 - Build a Home Lab and Attack Your Own Network

The fastest way to understand attacks is to run them yourself in a controlled environment.

Setup:

* Install [VirtualBox](https://www.virtualbox.org/) or [Proxmox](https://www.proxmox.com/) (more capable, needs a spare machine)
* Set up [Kali Linux](https://www.kali.org/) as your attack VM
* Download a vulnerable target from [VulnHub](https://www.vulnhub.com/) - start with Metasploitable 2 or the OWASP Broken Web Applications project
* Scan it with nmap, exploit it with Metasploit, escalate privileges, and document what you find



Interesting resources to pair with this:

* [TCM Security - Practical Ethical Hacking](https://academy.tcm-sec.com/p/practical-ethical-hacking-the-complete-course) - Affordable and thorough.
* [HackTricks](https://book.hacktricks.xyz/) - Bookmark this. You will refer to it constantly.



### Project 3 - Enter Your First CTF

Gamified hacking challenges across web exploitation, cryptography, forensics, binary exploitation, and OSINT. Each one ends with a flag you capture to prove you solved it. Start with:

* [PicoCTF](https://picoctf.org/) - Always open. Beginner-friendly. Carnegie Mellon's flagship CTF.
* [CTFtime.org](https://ctftime.org/event/list) - Browse upcoming CTFs and filter for beginner-tagged events.
* [Hack The Box Starting Point](https://app.hackthebox.com/starting-point) - Guided beginner machines with hints built in.

The workflow: join a beginner CTF, work through challenges, read others' writeups after the event ends, then write your own for the challenges you solved and post them publicly.

Writing and publishing your first CTF writeup is the moment people find you. 

Note: The term [CTF](https://defcon.org/html/links/dc-ctf-history.html) in hacking originated at DEF CON in 1996 as a literal physical flag competition before evolving into the digital challenge format used today.



## About This Page

I am treating this page as an evolving document. I tried my best to link everything I have found for easy access. If you find a dead link or want to suggest a resource, open a PR.

Contributions are especially welcome for: hardware hacking, non-English communities, AI security, and DFIR.



This was made on March 2026

