# Awesome CTF resources [![contributions welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat)](https://github.com/dwyl/esta/issues)

A list of [Capture The Flag](https://en.wikipedia.org/wiki/Capture_the_flag#Computer_security) (CTF) frameworks, libraries, resources and software for started/experienced CTF players 🚩 

Any contribution is welcome, send me a PR! ❤️

*- The programs and resources collected do not belong to me and have been compiled for educational purposes only -*

<p align="center">
<img src="https://i.imgur.com/d4aShjQ.jpg" width="600" height="300" >
</p>

## Contents

 - [Create](#0x00-create)
    - [Platforms](#platforms)
    - [Forensics](#forensics)
    - [Steganography](#steganography)
    - [Web](#web)

 - [Solve](#0x01-solve)
    - [Cryptography](#cryptography)
    - [Exploiting / Pwn](#exploiting--pwn)
    - [Forensics](#forensics-1)
    - [Misc](#misc)
    - [Reversing](#reversing)
    - [Steganography](#steganography-1)
    - [Web](#web-1)

 - [Resources](#0x02-resources)
    - [Online Platforms](#online-platforms)
    - [Writeups Repositories](#writeups-repositories)
    - [Collaborative Tools](#collaborative-tools)

 - [Bibliography](#0x03-bibliography)


# 0x00. Create

*Tools used for creating CTF challenges*

## Platforms

*Frameworks that can be used to host a CTF*

 - [CTFd](https://github.com/CTFd/CTFd) - Platform to host jeopardy style CTFs.
 - [FBCTF](https://github.com/facebookarchive/fbctf) - Facebook CTF platform to host Jeopardy and "King of the Hill" CTF competitions.
 - [HackTheArch](https://github.com/mcpa-stlouis/hack-the-arch) - Scoring server for CTF competitions.
 - [kCTF](https://github.com/google/kctf) - Kubernetes-based infrastructure for CTF competitions.
 - [LibreCTF](https://github.com/easyctf/librectf) - CTF platform from EasyCTF.
 - [Mellivora](https://github.com/Nakiami/mellivora) - CTF engine written in PHP.
 - [NightShade](https://github.com/UnrealAkama/NightShade) - Simple CTF framework.
 - [picoCTF](https://github.com/picoCTF/picoCTF) - Infrastructure used to run picoCTF.
 - [rCTF](https://github.com/redpwn/rctf) - CTF platform maintained by the [redpwn](https://github.com/redpwn/rctf) CTF team.
 - [RootTheBox](https://github.com/moloch--/RootTheBox) - CTF scoring engine for wargames.
 - [ImaginaryCTF](https://github.com/Et3rnos/ImaginaryCTF) - Platform to host CTFs.

## Forensics

*Tools used to create Forensics challenges*

 - [Belkasoft RAM Capturer](https://belkasoft.com/ram-capturer) - Volatile Memory Acquisition Tool.
 - [Dnscat2](https://github.com/iagox86/dnscat2) - Hosts communication through DNS.
 - [Magnet AXIOM 2.0](https://www.magnetforensics.com/resources/magnet-axiom-2-0-memory-analysis/) - Artifact-centric DFIR tool.
 - [Registry Dumper](http://www.kahusecurity.com/posts/registry_dumper_find_and_dump_hidden_registry_keys.html) - Tool to dump Windows Registry.

## Steganography

*Tools used to create Stego challenges*

Check [solve section for steganography](#steganography-1).

## Web

*Tools used to create Web challenges*

 - [Metasploit JavaScript Obfuscator](https://github.com/rapid7/metasploit-framework/wiki/How-to-obfuscate-JavaScript-in-Metasploit) - How to obfuscate JavaScript in Metasploit.

# 0x01. Solve

## Cryptography

*Tools used for solving Crypto challenges*

 - [Ciphey](https://github.com/Ciphey/Ciphey) - Tool to automatically decrypt encryptions without knowing the key or cipher, decode encodings, and crack hashes.
 - [CyberChef](https://gchq.github.io/CyberChef/) - A web app for encryption, encoding, compression and data analysis.
 - [Cryptii](https://cryptii.com/) - Modular conversion, encoding and encryption online.
 - [dCode.fr](https://www.dcode.fr/tools-list#cryptography) - Solvers for Crypto, Maths and Encodings online.
 - [Decodify](https://github.com/s0md3v/Decodify) - Detect and decode encoded strings, recursively.
 - [Enigma Machine](https://summersidemakerspace.ca/projects/enigma-machine/) - Universal Enigma Machine Simulator.
 - [FeatherDuster](https://github.com/nccgroup/featherduster) - An automated, modular cryptanalysis tool.
 - [Galois](http://web.eecs.utk.edu/~jplank/plank/papers/CS-07-593/) - A fast galois field arithmetic library/toolkit.
 - [HashExtender](https://github.com/iagox86/hash_extender) - Tool for performing hash length extension attacks.
 - [Hash-identifier](https://code.google.com/p/hash-identifier/source/checkout) - Simple hash algorithm identifier.
 - [padding-oracle-attacker](https://github.com/KishanBagaria/padding-oracle-attacker) - CLI tool and library to execute padding oracle attacks easily.
 - [PadBuster](https://github.com/AonCyberLabs/PadBuster) - Automated script for performing Padding Oracle attacks.
 - [PEMCrack](https://github.com/robertdavidgraham/pemcrack) - Cracks SSL PEM files that hold encrypted private keys. Brute forces or dictionary cracks.
 - [PKCrack](https://www.unix-ag.uni-kl.de/~conrad/krypto/pkcrack.html) - PkZip encryption cracker.
 - [Quipqiup](https://quipqiup.com/) - Automated cryptogram solver.
 - [RSACTFTool](https://github.com/Ganapati/RsaCtfTool) - RSA multi attacks tool.
 - [RSATool](https://github.com/ius/rsatool) - Tool to to calculate RSA and RSA-CRT parameter.
 - [Rumkin Cipher Tools](http://rumkin.com/tools/cipher/) - Collection of ciphhers/encoders tools.
 - [Vigenere Solver](https://www.guballa.de/vigenere-solver) - Online tool that breaks Vigenère ciphers without knowing the key.
 - [XORTool](https://github.com/hellman/xortool) - A tool to analyze multi-byte xor cipher.
 - [yagu](https://sourceforge.net/projects/yafu/) - Automated integer factorization.
 - [Crackstation](https://crackstation.net/) - Hash cracker (database).
 - [Online Encyclopedia of Integer Sequences](https://oeis.org/) - OEIS: The On-Line Encyclopedia of Integer Sequences

## Exploiting / Pwn

*Tools used for solving Pwn challenges*

 - [afl](https://lcamtuf.coredump.cx/afl/) - Security-oriented fuzzer.
 - [honggfuzz](https://github.com/google/honggfuzz) - Security oriented software fuzzer. Supports evolutionary, feedback-driven fuzzing based on code coverage.
 - [libformatstr](https://github.com/hellman/libformatstr) - Simplify format string exploitation.
 - [One_gadget](https://github.com/david942j/one_gadget) - Tool for finding one gadget RCE.
 - [Pwntools](https://github.com/Gallopsled/pwntools) - CTF framework for writing exploits.
 - [ROPgadget](https://github.com/JonathanSalwan/ROPgadget) - Framework for ROP exploitation.
 - [Ropper](https://github.com/sashs/Ropper) - Display information about files in different file formats and find gadgets to build rop chains for different architectures.
 - [Shellcodes Database](http://shell-storm.org/shellcode/) - A massive shellcodes database.

## Forensics

*Tools used for solving Forensics challenges*

 - [Autopsy](https://www.autopsy.com/) - End-to-end open source digital forensics platform.
 - [Binwalk](https://github.com/devttys0/binwalk) - Firmware Analysis Tool.
 - [Bulk-extractor](https://github.com/simsong/bulk_extractor) - High-performance digital forensics exploitation tool.
 - [Bkhive & samdump2](https://www.kali.org/tools/samdump2/) - Dump SYSTEM and SAM files.
 - [ChromeCacheView](https://www.nirsoft.net/utils/chrome_cache_view.html) - Small utility that reads the cache folder of Google Chrome Web browser, and displays the list of all files currently stored in the cache.
 - [Creddump](https://github.com/moyix/creddump) - Dump Windows credentials.
 - [Exiftool](https://exiftool.org/) - Read, write and edit file metadata.
 - [Extundelete](http://extundelete.sourceforge.net/) - Utility that can recover deleted files from an ext3 or ext4 partition.
 - [firmware-mod-kit](https://code.google.com/archive/p/firmware-mod-kit/) - Modify firmware images without recompiling.
 - [Foremost](http://foremost.sourceforge.net/) - Console program to recover files based on their headers, footers, and internal data structures.
 - [MZCacheView](https://www.nirsoft.net/utils/mozilla_cache_viewer.html) - Small utility that reads the cache folder of Firefox/Mozilla/Netscape Web browsers, and displays the list of all files currently stored in the cache.
 - [NetworkMiner](https://www.netresec.com/index.ashx?page=NetworkMiner)  Network Forensic Analysis Tool (NFAT).
 - [OfflineRegistryView](https://www.nirsoft.net/utils/offline_registry_view.html) - Simple tool for Windows that allows you to read offline Registry files from external drive.
 - [Registry Viewer](https://accessdata.com/product-download/registry-viewer-2-0-0) - Tool to view Windows registers.
 - [Scalpel](https://github.com/sleuthkit/scalpel) - Open source data carving tool.
 - [USBRip](https://github.com/snovvcrash/usbrip) - Simple CLI forensics tool for tracking USB device artifacts (history of USB events) on GNU/Linux.
 - [Volatility](https://github.com/volatilityfoundation/volatility) - An advanced memory forensics framework.
 - [Wireshark](https://www.wireshark.org/) - Tool to analyze pcap or pcapng files.
 - [X-Ways](https://www.x-ways.net/forensics/index-m.html) - Advanced work environment for computer forensic examiners.

## Misc

*Tools used for solving Misc challenges*

 - [boofuzz](https://github.com/jtpereyda/boofuzz) - Network Protocol Fuzzing for Humans.
 - [Veles](https://codisec.com/veles/) - Binary data analysis and visualization tool.

**Bruteforcers:**

 - [changeme](https://github.com/ztgrace/changeme) - A default credential scanner.
 - [Hashcat](https://hashcat.net/hashcat/) - Advanced Password Recovery
 - [Hydra](https://www.kali.org/tools/hydra/) - Parallelized login cracker which supports numerous protocols to attack.
 - [John the Ripper](https://www.openwall.com/john/) - Open Source password security auditing and password recovery.
 - [jwt_tool](https://github.com/ticarpi/jwt_tool) - A toolkit for testing, tweaking and cracking JSON Web Tokens.
 - [Ophcrack](https://ophcrack.sourceforge.io/) - Free Windows password cracker based on rainbow tables.
 - [Patator](https://github.com/lanjelot/patator) - Multi-purpose brute-forcer, with a modular design and a flexible usage.
 - [Turbo Intruder](https://portswigger.net/bappstore/9abaa233088242e8be252cd4ff534988) - Burp Suite extension for sending large numbers of HTTP requests and analyzing the results.

**Esoteric Languages:**

 - [Malbolge](http://www.malbolge.doleczek.pl/) - Malbolge esoteric programming language solver.
 - [Ook!](https://www.dcode.fr/ook-language) - Tool for decoding / encoding in Ook!
 - [Piet](https://www.bertnase.de/npiet/npiet-execute.php) - Piet programming language compiler.

**Sandboxes:**

 - [Any.run](https://any.run/) - Interactive malware hunting service.
 - [Intezer Analyze](https://analyze.intezer.com/) - Malware analysis platform.
 - [Triage](https://tria.ge/) - State-of-the-art malware analysis sandbox designed for cross-platform support.

## Reversing

*Tools used for solving Reversing challenges*

 - [Androguard](https://github.com/androguard/androguard) - Androguard is a full python tool to play with Android files.
 - [Angr](https://github.com/angr/angr) - A powerful and user-friendly binary analysis platform.
 - [Apk2gold](https://github.com/lxdvs/apk2gold) - CLI tool for decompiling Android apps to Java.
 - [ApkTool](https://ibotpeaches.github.io/Apktool/) - A tool for reverse engineering 3rd party, closed, binary Android apps.
 - [Binary Ninja](https://binary.ninja/) - Binary Analysis Framework.
 - [BinUtils](https://www.gnu.org/software/binutils/binutils.html) - Collection of binary tools.
 - [CTF_import](https://github.com/sciencemanx/ctf_import) - Run basic functions from stripped binaries cross platform.
 - [Compiler Explorer](https://godbolt.org/) - Online compiler tool.
 - [CWE_checker](https://github.com/fkie-cad/cwe_checker) - Finds vulnerable patterns in binary executables.
 - [Demovfuscator](https://github.com/kirschju/demovfuscator) - A work-in-progress deobfuscator for movfuscated binaries.
 - [Disassembler.io](https://onlinedisassembler.com/static/home/index.html) - Disassemble On Demand. 
A lightweight, online service for when you don’t have the time, resources, or requirements to use a heavier-weight alternative.
 - [dnSpy](https://github.com/dnSpy/dnSpy) - .NET debugger and assembly editor.
 - [Frida](https://github.com/frida/) - Dynamic instrumentation toolkit for developers, reverse-engineers, and security researchers.
 - [GDB](https://www.gnu.org/software/gdb/) - The GNU Project debugger.
 - [GEF](https://github.com/hugsy/gef) - A modern experience for GDB with advanced debugging features for exploit developers & reverse engineers.
 - [Ghidra](https://ghidra-sre.org/) - A software reverse engineering (SRE) suite of tools developed by NSA.
 - [Hopper](https://www.hopperapp.com/) - Reverse engineering tool (disassembler) for OSX and Linux.
 - [IDA Pro](https://hex-rays.com/ida-pro/) - Most used Reversing software.
 - [Jadx](https://github.com/skylot/jadx) - Command line and GUI tools for producing Java source code from Android Dex and Apk files.
 - [Java Decompilers](http://www.javadecompilers.com/) - An online decompiler for Java and Android APKs.
 - [JSDetox](https://github.com/svent/jsdetox) - A JavaScript malware analysis tool.
 - [miasm](https://github.com/cea-sec/miasm) - Reverse engineering framework in Python.
 - [Objection](https://github.com/sensepost/objection) - Runtime mobile exploration.
 - [Online Assembler/Disassembler](http://shell-storm.org/online/Online-Assembler-and-Disassembler/) - Online wrappers around the Keystone and Capstone projects.
 - [PEDA](https://github.com/longld/peda) - Python Exploit Development Assistance for GDB.
 - [Pwndbg](https://github.com/pwndbg/pwndbg) - Exploit Development and Reverse Engineering with GDB Made Easy.
 - [radare2](https://github.com/radareorg/radare2) - UNIX-like reverse engineering framework and command-line toolset.
 - [Rizin](https://github.com/rizinorg/rizin) - Rizin is a fork of the radare2 reverse engineering framework with a focus on usability, working features and code cleanliness.
 - [Uncompyle](https://github.com/gstarnberger/uncompyle) -  A Python 2.7 byte-code decompiler (.pyc)
 - [WinDBG](http://www.windbg.org/) - Windows debugger distributed by Microsoft.
 - [Z3](https://github.com/Z3Prover/z3) - A theorem prover from Microsoft Research.

## Steganography

*Tools used for solving Stego challenges*

 - [AperiSolve](https://aperisolve.fr/) - Platform which performs layer analysis on images.
 - [Exif](http://manpages.ubuntu.com/manpages/trusty/man1/exif.1.html) - Shows EXIF information in JPEG files.
 - [Exiv2](https://www.exiv2.org/manpage.html) - Image metadata manipulation tool.
 - [Image Steganography](https://incoherency.co.uk/image-steganography/) - Client-side Javascript tool to steganographically hide/unhide images inside the lower "bits" of other images. 
 - [ImageMagick](http://www.imagemagick.org/script/index.php) - Tool for manipulating images.
 - [Outguess](https://www.freebsd.org/cgi/man.cgi?query=outguess+&apropos=0&sektion=0&manpath=FreeBSD+Ports+5.1-RELEASE&format=html) - Universal steganographic tool.
 - [Pngcheck](http://www.libpng.org/pub/png/apps/pngcheck.html) - Verifies the integrity of PNG and dump all of the chunk-level information in human-readable form.
 - [Pngtools](https://packages.debian.org/sid/pngtools) - For various analysis related to PNGs.
 - [SmartDeblur](https://github.com/Y-Vladimir/SmartDeblur) - Restoration of defocused and blurred photos/images.
 - [Snow](https://sbmlabs.com/notes/snow_whitespace_steganography_tool) - Whitespace Steganography Tool
 - [Sonic Visualizer](https://www.sonicvisualiser.org/) - Audio file visualization.
 - [Steganography Online](https://stylesuxx.github.io/steganography/) - Online steganography encoder and decoder.
 - [Stegbreak](https://linux.die.net/man/1/stegbreak) - Launches brute-force dictionary attacks on JPG image.
 - [StegCracker](https://github.com/Paradoxis/StegCracker) - Brute-force utility to uncover hidden data inside files.
 - [stegextract](https://github.com/evyatarmeged/stegextract) - Detect hidden files and text in images.
 - [Steghide](http://steghide.sourceforge.net/) - Hide data in various kinds of image- and audio-files.
 - [StegOnline](https://stegonline.georgeom.net/) - Conduct a wide range of image steganography operations, such as concealing/revealing files hidden within bits.
 - [Stegosaurus](https://github.com/AngelKitty/stegosaurus) - A steganography tool for embedding payloads within Python bytecode.
 - [StegoVeritas](https://github.com/bannsec/stegoVeritas) - Yet another stego tool.
 - [Stegsolve](https://github.com/zardus/ctf-tools/tree/master/stegsolve) - Apply various steganography techniques to images.
 - [Zsteg](https://github.com/zed-0xff/zsteg/) - PNG/BMP analysis.
 - [BPStegano](https://github.com/TapanSoni/BPStegano) - Python3 based LSB steganography. 

## Web 

*Tools used for solving Web challenges*

 - [Arachni](https://www.arachni-scanner.com/) - Web Application Security Scanner Framework.
 - [Beautifier.io](https://beautifier.io/) - Online JavaScript Beautifier.
 - [BurpSuite](https://portswigger.net/burp) - A graphical tool to testing website security.
 - [Commix](https://github.com/commixproject/commix) - Automated All-in-One OS Command Injection Exploitation Tool.
 - [Dirhunt](https://github.com/Nekmo/dirhunt) - Find web directories without bruteforce.
 - [dirsearch](https://github.com/maurosoria/dirsearch) - Web path scanner.
 - [dontgo403](https://github.com/devploit/dontgo403) - Tool to bypass 40x errors.
 - [ffuf](https://github.com/ffuf/ffuf) - Fast web fuzzer written in Go.
 - [git-dumper](https://github.com/arthaud/git-dumper) - A tool to dump a git repository from a website.
 - [Gopherus](https://github.com/tarunkant/Gopherus) - Tool that generates gopher link for exploiting SSRF and gaining RCE in various servers.
 - [ngrok](https://ngrok.com/) - Secure introspectable tunnels to localhost.
 - [OWASP Zap](https://owasp.org/www-project-zap/) - Intercepting proxy to replay, debug, and fuzz HTTP requests and responses.
 - [Postman](https://chrome.google.com/webstore/detail/postman/fhbjgbiflinjbdggehcddcbncdddomop?hl=en) - Addon for chrome for debugging network requests.
 - [Smuggler](https://github.com/defparam/smuggler) -  An HTTP Request Smuggling / Desync testing tool written in Python3.
 - [SQLMap](https://github.com/sqlmapproject/sqlmap) - Automatic SQL injection and database takeover tool.
 - [PHPGGC](https://github.com/ambionics/phpggc) - Library of PHP unserialize() payloads along with a tool to generate them, from command line or programmatically.
 - [Revelo](http://www.kahusecurity.com/posts/revelo_javascript_deobfuscator.html) - Analyze obfuscated Javascript code.
 - [REQBIN](https://reqbin.com/) - Online REST & SOAP API Testing Tool.
 - [Request Bin](https://requestbin.com/) - A modern request bin to inspect any event by Pipedream.
 - [W3af](https://github.com/andresriancho/w3af) - Web application attack and audit framework.
 - [XSSer](https://xsser.03c8.net/) - Automated XSS testor.
 - [ysoserial](https://github.com/frohoff/ysoserial) - Tool for generating payloads that exploit unsafe Java object deserialization.

# 0x02. Resources

## Online Platforms

*Always online CTFs*

 - [247CTF](https://247ctf.com/) - Free Capture The Flag Hacking Environment.
 - [Atenea](https://atenea.ccn-cert.cni.es/) - Spanish CCN-CERT CTF platform.
 - [CTFlearn](https://ctflearn.com/) - Online platform built to help ethical hackers learn, practice, and compete.
 - [CTF365](https://ctf365.com/) - Security Training Platform
 - [Crackmes.One](https://crackmes.one/) - Reverse Engineering Challenges.
 - [CryptoHack](https://cryptohack.org/) - Cryptography Challenges.
 - [Cryptopals](https://cryptopals.com/) - Cryptography Challenges. 
 - [echoCTF.RED](https://echoctf.red/) - Online Hacking Laboratories.
 - [HackTheBox](https://www.hackthebox.com/) - A Massive Hacking Playground.
 - [HackThisSite](https://www.hackthissite.org/) - Free, safe and legal training ground for hackers.
 - [Hacker101](https://www.hacker101.com/) - CTF Platform by [HackerOne](https://www.hackerone.com/).
 - [MicroCorruption](https://microcorruption.com/) - Embedded Security CTF.
 - [OverTheWire](https://overthewire.org/wargames/) - Wargame offered by the OverTheWire community.
 - [picoCTF2019](https://2019game.picoctf.com/) - Beginner-friendly CTF platform.
 - [PWNChallenge](http://pwn.eonew.cn/) - Pwn/Exploiting platform.
 - [Pwnable.kr](http://pwnable.kr/) - Pwn/Exploiting platform.
 - [Pwnable.tw](https://pwnable.tw/) - Pwn/Exploiting platform.
 - [Pwnable.xyz](https://pwnable.xyz/) - Pwn/Exploiting platform.
 - [Reversing.kr](http://reversing.kr/) - Reverse Engineering platform.
 - [Root-me](https://www.root-me.org/) - CTF training platform.
 - [VibloCTF](https://ctf.viblo.asia/landing) - CTF training platform.
 - [VulnHub](https://www.vulnhub.com/) - VM-based pentesting platform.
 - [W3Challs](https://w3challs.com/) - Hacking/CTF platform.
 - [WebHacking](https://webhacking.kr/) - Web challenges platform.
 - [Websec.fr](http://websec.fr/) - Web challenges platform.

*Self-hosted CTFs*

 - [Damn Vulnerable Web Application](https://dvwa.co.uk/) - PHP/MySQL web application that is damn vulnerable.
 - [Juice Shop](https://github.com/juice-shop/juice-shop-ctf) - Capture-the-Flag (CTF) environment setup tools for OWASP Juice Shop. 

## Collaborative Tools

 - [CTFNote](https://github.com/TFNS/CTFNote) - Collaborative tool aiming to help CTF teams to organise their work.

## Writeups Repositories

*Repository of CTF Writeups*

 - [Courgettes.Club](https://ctf.courgettes.club/) - CTF Writeup Finder.
 - [CTFtime](https://ctftime.org/writeups) - CTFtime Writeups Collection.
 - [Github.com/CTFs](https://github.com/ctfs) - Collection of CTF Writeups.

# 0x03. Bibliography

*The resources presented here have been gathered from numerous sources. However, the most important are:*

 - [zardus_ctf-tools](https://github.com/zardus/ctf-tools)
 - [apsdehal_awesome-ctf](https://github.com/apsdehal/awesome-ctf)
 - [vavkamil_awesome-bugbounty-tools](https://github.com/vavkamil/awesome-bugbounty-tools)