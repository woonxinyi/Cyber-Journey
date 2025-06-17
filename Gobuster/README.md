 "Gobuster" to brute-force FakeBank's website to find hidden directories and pages. Gobuster will take a list of potential page or directory names and try accessing a website with each of them; if the page exists, it tells you.


Use Gobuster To Find Hidden Website Pages

gobuster -u http://fakebank.thm -w wordlist.txt dir
 -u is used to state the website we're scanning, -w takes a list of words to iterate through to find hidden pages

output:
=====================================================
Gobuster v2.0.1              OJ Reeves (@TheColonial)
=====================================================
[+] Mode         : dir
[+] Url/Domain   : http://fakebank.thm/
[+] Threads      : 10
[+] Wordlist     : wordlist.txt
[+] Status codes : 200,204,301,302,307,403
[+] Timeout      : 10s
=====================================================
2025/06/17 15:45:32 Starting gobuster
=====================================================
/images (Status: 301)
/bank-transfer (Status: 200)
=====================================================
2025/06/17 15:45:44 Finished
