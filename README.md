<div align="center">
   <a href="https://github.com/zebbern/Zefoy-Automator-2025">
      <img src="https://github.com/zebbern/zebbern/raw/main/test9.gif" height="200" width="20%" align="center" />
   </a>

# Cybersecurity Wordlists Repository  
**A curated collection of wordlists optimized for penetration testing, bug bounties, and cybersecurity research.**  

---

### 🌐 **Subdomains**  
| Wordlist | Description | Source |  
|----------|-------------|--------|  
| **SecLists DNS** | Massive subdomain lists for recon. | [Link](https://github.com/danielmiessler/SecLists/tree/master/Discovery/DNS) |  
| **JHaddix's all.txt** | Aggregated subdomains from leaks and scanners. | [Link](https://gist.github.com/jhaddix/86a06c5dc309d08580a018c66354a056) |  
| **Assetnote Subdomains** | Actively maintained subdomain wordlists. | [Link](https://wordlists-cdn.assetnote.io/data/manual/hosts.txt) |  
| **Commonspeak2** | Subdomains based on trending tech keywords. | [Link](https://github.com/assetnote/commonspeak2/tree/master/subdomains) |  
| **Knockpy** | Subdomain brute-forcing list for Knockpy tool. | [Link](https://github.com/guelfoweb/knock/tree/master/wordlist) |  
| **DNSDumpster** | Subdomains from DNSDumpster's crawl data. | [Link](https://github.com/UnaPibaGeek/dnsdumpster-scraper) |  

---

### 📂 **Directory Brute-Forcing**  
| Wordlist | Description | Source |  
|----------|-------------|--------|  
| **Dirbuster's big.txt** | Classic directory brute-forcing list. | [Link](https://gitlab.com/kalilinux/packages/dirbuster/-/blob/kali/master/wordlists/directory-list-2.3-big.txt) |  
| **SecLists Web Content** | Common and uncommon directories/files. | [Link](https://github.com/danielmiessler/SecLists/tree/master/Discovery/Web-Content) |  
| **FuzzDB Predictable Paths** | Paths for backups, configs, and admin panels. | [Link](https://github.com/fuzzdb-project/fuzzdb/tree/master/discovery/predictable-filepaths) |  
| **Assetnote Mega List** | 9M+ entries for directories and files. | [Link](https://wordlists-cdn.assetnote.io/data/manual/web-directories.txt) |  
| **Dirsearch Default** | Default wordlist for dirsearch tool. | [Link](https://github.com/maurosoria/dirsearch/tree/master/db) |  
| **Raft** | Medium-sized list for general discovery. | [Link](https://github.com/danielmiessler/SecLists/blob/master/Discovery/Web-Content/raft-medium-directories.txt) |  

---

### 🔄 **File Extensions**  
| Wordlist | Description | Source |  
|----------|-------------|--------|  
| **SecLists Extensions** | Common and obscure file extensions. | [Link](https://github.com/danielmiessler/SecLists/blob/master/Discovery/Web-Content/web-extensions.txt) |  
| **PayloadsAllTheThings** | Extensions for LFI, backups, and bypasses. | [Link](https://github.com/swisskyrepo/PayloadsAllTheThings/blob/master/Wordlists/Extensions.txt) |  
| **FuzzDB File Extensions** | Focused on server-side file types. | [Link](https://github.com/fuzzdb-project/fuzzdb/tree/master/discovery/file-extensions) |  
| **DotFiles** | Hidden config files (e.g., `.env`, `.git`). | [Link](https://github.com/danielmiessler/SecLists/blob/master/Discovery/Web-Content/dotfiles.txt) |  
| **PHP Obfuscated** | Non-standard PHP extensions (`.php5`, `.pht`). | [Link](https://github.com/danielmiessler/SecLists/blob/master/Discovery/Web-Content/web-extensions-php.txt) |  

---

### 🔑 **Passwords**  
| Wordlist | Description | Source |  
|----------|-------------|--------|  
| **RockYou.txt** | 14M passwords from the 2009 breach. | [Link](https://github.com/brannondorsey/naive-hashcat/releases/download/data/rockyou.txt) |  
| **SecLists Passwords** | Common passwords, leaked databases, and rules. | [Link](https://github.com/danielmiessler/SecLists/tree/master/Passwords) |  
| **CrackStation** | 1.5B entries with human-generated passwords. | [Link](https://crackstation.net/crackstation-wordlist-password-cracking-dictionary.htm) |  
| **Honeypot Passwords** | Real-world passwords from honeypots. | [Link](https://github.com/clem9669/honeypot-passwords) |  
| **Probable Wordlists** | Contextual passwords (e.g., sports, movies). | [Link](https://github.com/berzerk0/Probable-Wordlists) |  
| **Weakpass** | Leaked passwords sorted by year/breach. | [Link](https://weakpass.com/) |  

---

### 👤 **Usernames**  
| Wordlist | Description | Source |  
|----------|-------------|--------|  
| **SecLists Usernames** | Top usernames from breaches and services. | [Link](https://github.com/danielmiessler/SecLists/tree/master/Usernames) |  
| **LinkedIn 2021 Leak** | Usernames from LinkedIn data scrape. | [Link](https://github.com/Orange-Cyberdefense/ocd-mindmaps/blob/main/wordlists/usernames-linkedin.txt) |  
| **FuzzDB Usernames** | Common and system-specific usernames. | [Link](https://github.com/fuzzdb-project/fuzzdb/tree/master/discovery/usernames) |  
| **XatoNet** | 10M+ username list from Xato.net. | [Link](https://github.com/jeanphorn/wordlist/blob/master/usernames.txt) |  
| **Default Logins** | Default credentials for routers/IoT devices. | [Link](https://github.com/rapid7/wordlists/blob/master/Default_Logins/default-logins.csv) |  

---

### ⚙️ **Parameter Fuzzing**  
| Wordlist | Description | Source |  
|----------|-------------|--------|  
| **Burp Param Miner** | Hidden parameters for APIs and web apps. | [Link](https://github.com/PortSwigger/param-miner/tree/master/resources) |  
| **Parameth** | 10K+ parameters for fuzzing. | [Link](https://github.com/maK-/parameth/blob/master/params.txt) |  
| **Arjun Default** | Curated parameters for automated discovery. | [Link](https://github.com/s0md3v/Arjun/blob/master/arjun/db/params.txt) |  
| **FuzzDB Injection** | Payloads for SQLi, XSS, and command injection. | [Link](https://github.com/fuzzdb-project/fuzzdb/tree/master/attack) |  
| **API Security List** | Parameters for GraphQL and REST APIs. | [Link](https://github.com/deepsecurityapi/parameters-list/blob/main/api-params.txt) |  

---

## 🚀 **Advanced Wordlists**  
- **SSRF/XXE**: [PayloadsAllTheThings](https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/XXE%20Injection)  
- **Cloud Buckets**: [Bucket Names](https://github.com/gwen001/s3-buckets-finder/blob/master/wordlists/bucket-names.txt)  
- **Unicode Bypasses**: [Unicode XSS](https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/XSS%20Injection#unicode)  
- **CORS Exploits**: [CORS Headers](https://github.com/swisskyrepo/PayloadsAllTheThings/blob/master/CORS%20Misconfiguration/CORS-headers.md)  

---

## ⚖️ **Tips**  
1. **Combine Lists**: Merge with `sort -u wordlist1.txt wordlist2.txt > combined.txt`.  
2. **Generate Dynamically**: Use `cewl` or `theHarvester` to scrape target-specific terms.  
3. **Monitor 404s**: Log failed paths during brute-forcing to refine future scans.  

---

## 🌟 **Popular Repositories**  
- **[SecLists](https://github.com/danielmiessler/SecLists)**: The gold standard for recon and exploitation.  
- **[FuzzDB](https://github.com/fuzzdb-project/fuzzdb)**: Payloads for WAF bypasses and injection.  
- **[PayloadsAllTheThings](https://github.com/swisskyrepo/PayloadsAllTheThings)**: All-in-one attack payload library.  

---

</div>

> [!WARNING]  
Always obtain proper authorization before testing.  
**Maintained with ❤️ by github.com/zebbern.**  
