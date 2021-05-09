# DOD-RECON
Department of Defense's HackerOne Program

<a href="https://twitter.com/nobbieboy_1337"><img src="https://img.shields.io/twitter/follow/nobbieboy_1337.svg?logo=twitter"></a>
 <a href="https://discord.gg/Wk5yAhFv"><img src=""></a>

Summary
This a repo containing reconnaissance done for the Department of Defense's HackerOne Program. I will continue to add more as I do more recon. Feel free to add anything you have!

# Purpose

This repository was built only for research purposes in accordance with https://hackerone.com/deptofdefense?view_policy=true. If you interested in contributing or research - make sure you read it.

# Methodology used for collecting

Enumerating all possible subdomains through various tools (DNScan, SubBrute, Sublist3r, passive collection from search engines, etc)
Merging them to one big list.
Deleting duplicate records.
Checking common ports (80, 443, 8000, 8080, 8888), generating new list of valid subdomains
Committing to the repository. As you see, we still can miss some domains, which have some services running on non-standart ports. In the future, we will recheck the original lists again with Masscan tool, and update the lists.


Credits

