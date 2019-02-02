---


---

<blockquote>
<p>A collection of tools assembled for the RedEye Hacknight CTF Competition</p>
</blockquote>
<h1 id="main----">Main    <img src="https://img.shields.io/badge/cd-r00t-brightgreen.svg" alt="cdroot"></h1>
<ul>
<li><a href="#crypto">Crypto</a>
<ul>
<li><a href="#general-crypto">General Crypto</a></li>
<li><a href="#cracking">Cracking</a></li>
</ul>
</li>
<li><a href="#stegano">Stegano</a>
<li><a href="#reverse-engineering">Reverse Engineering</a></li>
<li><a href="#web">Web</a></li>
<li><a href="#general">General</a>
<ul>
<li><a href="#networking">Networking</a></li>
<li><a href="#forensics">Forensics</a></li>
<li><a href="#misc/kits">Misc/Kits</a></li>
<li><a href="#editors">Editors</a></li>
</ul>
</li>
</ul>
<h2 id="crypto">Crypto</h2>
<h3 id="general-crypto">General Crypto</h3>
<ul>
<li><a href="http://www.crypo.com/">Crypto</a> - Decrypts/encrypts everything</li>
<li><a href="https://www.cryptool.org/en/ct2-downloads">CrypTool2</a> - Win32/64 Crypto experimenting tool</li>
<li><a href="https://github.com/nccgroup/featherduster">FeatherDuster</a> - Identifying and exploiting weak cryptosystems</li>
<li><a href="https://sites.google.com/site/cryptocrackprogram/">CryptoCrack</a> - Identify and crack famous ciphers</li>
<li><a href="https://sourceforge.net/projects/yafu/">Yafu</a> - Integers factoring ( RSA related )</li>
<li><a href="https://github.com/Ganapati/RsaCtfTool">RSA-CTFTool</a> - Automated attacks on weak public keys</li>
<li><a href="https://github.com/hellman/xortool">XORTool</a> - Analzying XOR Ciphers</li>
<li><a href="https://www.unix-ag.uni-kl.de/%7Econrad/krypto/pkcrack.html">PkCrack</a> - Breaking PkZip Encryption</li>
<li><a href="https://github.com/bwall/HashPump">HashPump</a> - MD5, SHA1, SHA256, SHA512 exploiting</li>
</ul>
<h3 id="cracking">Cracking</h3>
<ul>
<li><a href="http://www.openwall.com/john/">John The Ripper</a> - Password cracker</li>
<li><a href="https://openwall.info/wiki/john/johnny">Johnny</a> - JTR GUI for Win32/64</li>
<li><a href="https://hashcat.net/hashcat/">Hashcat</a> - Password cracker</li>
<li><a href="https://github.com/lanjelot/patator">Patator</a> - Multi-purpose brute-forcer</li>
<li><a href="https://github.com/intrd/nozzlr">Nozzlr</a> - Bruteforce framework</li>
</ul>
<h2 id="stegano">Stegano</h2>
<ul>
<li><a href="http://diit.sourceforge.net/">Digital Invisible Ink Toolkit</a> - Extracts messages from images</li>
<li><a href="https://github.com/luca-m/lsb-toolkit">LSB Toolkit</a> - Python toolkit for analyzing</li>
<li><a href="https://www.openstego.com/">OpenStego</a> - Extracts hidden data from images</li>
<li><a href="https://silenteye.v1kings.io/">SilentEye</a> - Hides data in images/sounds</li>
<li><a href="http://www.libpng.org/pub/png/apps/pngcheck.html">PNGCheck</a> - Dump information from images</li>
<li><a href="http://www.petitcolas.net/steganography/mp3stego/">MP3Stego</a> - Mp3 stegano tool</li>
</ul>
<blockquote>
<p>From Awesome-CTF</p>
</blockquote>
<ul>
<li><a href="http://www.imagemagick.org/script/convert.php">Convert</a> - Convert images b/w formats and apply filters</li>
<li><a href="http://manpages.ubuntu.com/manpages/trusty/man1/exif.1.html">Exif</a> - Shows EXIF information in JPEG files</li>
<li><a href="https://linux.die.net/man/1/exiftool">Exiftool</a> - Read and write meta information in files</li>
<li><a href="http://www.exiv2.org/manpage.html">Exiv2</a> - Image metadata manipulation tool</li>
<li><a href="https://www.freebsd.org/cgi/man.cgi?query=outguess+&amp;apropos=0&amp;sektion=0&amp;manpath=FreeBSD+Ports+5.1-RELEASE&amp;format=html">Outguess</a> - Universal steganographic tool</li>
<li><a href="http://www.stillhq.com/pngtools/">Pngtools</a> - For various analysis related to PNGs</li>
<li><a href="https://github.com/Y-Vladimir/SmartDeblur">SmartDeblur</a> - Used to deblur and fix defocused images</li>
<li><a href="https://www.openhub.net/p/steganabara">Steganabara</a> - Tool for stegano analysis written in Java</li>
<li><a href="https://linux.die.net/man/1/stegbreak">Stegbreak</a> - Launches brute-force dictionary attacks on JPG image</li>
<li><a href="https://github.com/Paradoxis/StegCracker">StegCracker</a> - Steganography brute-force utility to uncover hidden data inside files</li>
<li><a href="https://github.com/evyatarmeged/stegextract">stegextract</a> - Detect hidden files and text in images</li>
<li><a href="http://steghide.sourceforge.net/">Steghide</a> - Hide data in various kind of images</li>
<li><a href="http://www.caesum.com/handbook/Stegsolve.jar">Stegsolve</a> - Apply various steganography techniques to images</li>
</ul>
<h2 id="reverse-engineering">Reverse Engineering</h2>
<ul>
<li><a href="http://debugger.immunityinc.com/">Immunity Debugger</a>  - Cool debugger/ GUI and CMDLine</li>
<li><a href="http://www.ollydbg.de/">OllyDbg</a>  - Windows binary code analyzer</li>
<li><a href="http://ilspy.net/">ILSpy</a>  - .NET C# decompiler</li>
<li><a href="http://jd.benow.ca/#jd-gui-overview">JD-GUI</a>  - Basic jar decompiler</li>
<li><a href="http://www.free-decompiler.com/flash/download.html">FFDec</a>  - Flash decompiler</li>
<li><a href="http://code.google.com/p/dex2jar/">dex2jar</a>  - Name says it all</li>
<li><a href="https://github.com/wibiti/uncompyle2">Uncompyle2</a> - Python bin -&gt; Python code</li>
<li><a href="https://github.com/helios-decompiler/Helios">Helios</a> - Java decompiler</li>
<li><a href="https://dwheeler.com/flawfinder/">FlawFinder</a> -  Finds security weaknesses in C/C++ codes</li>
</ul>
<blockquote>
<p>From Awesome-CTF</p>
</blockquote>
<p><em>Tools used for solving Reversing challenges</em></p>
<ul>
<li><a href="https://github.com/androguard/androguard">Androguard</a> - Reverse engineer Android applications</li>
<li><a href="https://github.com/angr/angr">Angr</a> - platform-agnostic binary analysis framework</li>
<li><a href="https://github.com/lxdvs/apk2gold">Apk2Gold</a> - Yet another Android decompiler</li>
<li><a href="http://ibotpeaches.github.io/Apktool/">ApkTool</a> - Android Decompiler</li>
<li><a href="https://github.com/programa-stic/barf-project">Barf</a> - Binary Analysis and Reverse engineering Framework</li>
<li><a href="https://binary.ninja/">Binary Ninja</a> - Binary analysis framework</li>
<li><a href="http://www.gnu.org/software/binutils/binutils.html">BinUtils</a> - Collection of binary tools</li>
<li><a href="https://github.com/devttys0/binwalk">BinWalk</a> - Analyze, reverse engineer, and extract firmware images.</li>
<li><a href="https://github.com/nemerle/boomerang">Boomerang</a> - Decompile x86 binaries to C</li>
<li><a href="https://github.com/docileninja/ctf_import">ctf_import</a> – run basic functions from stripped binaries cross platform</li>
<li><a href="https://www.gnu.org/software/gdb/">GDB</a> - The GNU project debugger</li>
<li><a href="https://github.com/hugsy/gef">GEF</a> - GDB plugin</li>
<li><a href="http://www.hopperapp.com/">Hopper</a> - Reverse engineering tool (disassembler) for OSX and Linux</li>
<li><a href="https://www.hex-rays.com/products/ida/">IDA Pro</a> - Most used Reversing software</li>
<li><a href="https://github.com/skylot/jadx">Jadx</a> - Decompile Android files</li>
<li><a href="http://www.javadecompilers.com">Java Decompilers</a> - An online decompiler for Java and Android APKs</li>
<li><a href="https://github.com/Storyyeller/Krakatau">Krakatau</a> - Java decompiler and disassembler</li>
<li><a href="https://github.com/longld/peda">PEDA</a> - GDB plugin (only python2.7)</li>
<li><a href="https://software.intel.com/en-us/articles/pin-a-dynamic-binary-instrumentation-tool">Pin</a> A dynamic binary instrumentaion tool by Intel</li>
<li><a href="https://github.com/joelpx/plasma">Plasma</a> - An interactive disassembler for x86/ARM/MIPS which can generate indented pseudo-code with colored syntax.</li>
<li><a href="https://github.com/pwndbg/pwndbg">Pwndbg</a> - A GDB plugin that provides a suite of utilities to hack around GDB easily.</li>
<li><a href="https://github.com/radare/radare2">radare2</a> - A portable reversing framework</li>
<li><a href="https://github.com/gstarnberger/uncompyle">Uncompyle</a> - Decompile Python 2.7 binaries (.pyc)</li>
<li><a href="http://www.windbg.org/">WinDbg</a> - Windows debugger distributed by Microsoft</li>
<li><a href="http://reverse.lostrealm.com/tools/xocopy.html">Xocopy</a> - Program that can copy executables with execute, but no read permission</li>
<li><a href="https://github.com/Z3Prover/z3">Z3</a> - a theorem prover from Microsoft Research</li>
</ul>
<p><em>JavaScript Deobfuscators</em></p>
<ul>
<li><a href="http://relentless-coding.org/projects/jsdetox/install">Detox</a> - A Javascript malware analysis tool</li>
</ul>
<p><em>SWF Analyzers</em></p>
<ul>
<li><a href="https://github.com/CyberShadow/RABCDAsm">RABCDAsm</a> - Collection of utilities including an ActionScript 3 assembler/disassembler.</li>
<li><a href="http://www.swftools.org/">Swftools</a> - Collection of utilities to work with SWF files</li>
<li><a href="https://bitbucket.org/Alexander_Hanel/xxxswf">Xxxswf</a> - A Python script for analyzing Flash files.</li>
</ul>
<h2 id="web">Web</h2>
<ul>
<li><a href="https://mxtoolbox.com/">MXToolbox</a> - Online website for basic scanning/analyzing</li>
<li><a href="http://ironwasp.org/cswsh.html">CSWSH</a> - Cross-Site WebSocket Hijacking Tester</li>
<li><a href="http://requestb.in/">Request Bin</a> - Lets you inspect http requests to a particular url</li>
<li><a href="https://beautifier.io/">Beautifier</a> - Javascript beautifier</li>
<li><a href="http://www.kahusecurity.com/tools/Revelo_v0.6.zip">Revelo</a> - Analyze obfuscated Javascript code</li>
<li><a href="http://www.phpformatter.com/">PHPFormatter</a> - PHP beautifier</li>
<li><a href="https://htmlformatter.com/">HTMLFormatter</a> - HTML beautifier</li>
<li><a href="https://addons.mozilla.org/en-US/firefox/addon/react-devtools/">ReactDevTools</a> - Developer tools for react apps</li>
<li><a href="https://www.telerik.com/fiddler">Fiddler</a> - Web Debugger</li>
<li><a href="http://wappalyzer.com/">Wappalyzer</a> - Web technology analyzer</li>
</ul>
<blockquote>
<p>From Awesome-CTF</p>
</blockquote>
<ul>
<li><a href="https://github.com/apsdehal/awesome-ctf/blob/master">BurpSuite</a> - A graphical tool to testing website security.</li>
<li><a href="https://github.com/commixproject/commix">Commix</a> - Automated All-in-One OS Command Injection and Exploitation Tool.</li>
<li><a href="https://addons.mozilla.org/en-US/firefox/addon/hackbar-quantum/">Hackbar</a> - Firefox addon for easy web exploitation</li>
<li><a href="https://www.owasp.org/index.php/Projects/OWASP_Zed_Attack_Proxy_Project">OWASP ZAP</a> - Intercepting proxy to replay, debug, and fuzz HTTP requests and responses</li>
<li><a href="https://github.com/evyatarmeged/Raccoon">Raccoon</a> - A high performance offensive security tool for reconnaissance and vulnerability scanning</li>
<li><a href="https://github.com/sqlmapproject/sqlmap">SQLMap</a> - Automatic SQL injection and database takeover tooli</li>
<li><a href="https://github.com/andresriancho/w3af">W3af</a> - Web Application Attack and Audit Framework.</li>
<li><a href="http://xsser.sourceforge.net/">XSSer</a> - Automated XSS testor</li>
</ul>
<h2 id="general">General</h2>
<h3 id="networking">Networking</h3>
<ul>
<li><a href="http://www.tcpdump.org/">tcpdump</a>  - Packet analyzer/Traffic capture</li>
<li><a href="http://netcat.sourceforge.net/">netcat</a> - Reads and Writes data across network connections</li>
<li><a href="https://scapy.net/download/">Scappy</a> - Forge, send and capture packets over the network</li>
<li><a href="https://www.snort.org/">Snort</a> - Detects attacks over network</li>
<li><a href="https://www.kismetwireless.net/download.shtml">Kismet</a> - Wireless network detector, sniffer, and intrusion detection system</li>
</ul>
<blockquote>
<p>From AwesomeCTF</p>
</blockquote>
<ul>
<li><a href="https://www.bro.org/">Bro</a> - An open-source network security monitor.</li>
<li><a href="https://github.com/robertdavidgraham/masscan">Masscan</a> - Mass IP port scanner, TCP port scanner.</li>
<li><a href="https://linoxide.com/monitoring-2/monit-linux/">Monit</a> - A linux tool to check a host on the network (and other non-network activities).</li>
<li><a href="https://github.com/GouveaHeitor/nipe">Nipe</a> - Nipe is a script to make Tor Network your default gateway.</li>
<li><a href="https://nmap.org/">Nmap</a> - An open source utility for network discovery and security auditing.</li>
<li><a href="https://www.wireshark.org/">Wireshark</a> - Analyze the network dumps.
<ul>
<li><code>apt-get install wireshark</code></li>
</ul>
</li>
<li><a href="https://zmap.io/">Zmap</a> - An open-source network scanner.</li>
</ul>
<h3 id="forensics">Forensics</h3>
<ul>
<li><a href="http://binwalk.org/">Binwalk</a> - A tool that helps identify and analyze binaries</li>
<li>File Utility - Detecs various file types</li>
<li><a href="https://www.forensicswiki.org/wiki/Strings">Strings</a> - Exports ASCII/unicode strings from  various files</li>
<li><a href="https://www.xplico.org/">Xplico</a> - Network forensics tool</li>
</ul>
<blockquote>
<p>From AwesomeCTF</p>
</blockquote>
<ul>
<li><a href="http://www.aircrack-ng.org/">Aircrack-Ng</a> - Crack 802.11 WEP and WPA-PSK keys
<ul>
<li><code>apt-get install aircrack-ng</code></li>
</ul>
</li>
<li><a href="http://sourceforge.net/projects/audacity/">Audacity</a> - Analyze sound files (mp3, m4a, whatever)
<ul>
<li><code>apt-get install audacity</code></li>
</ul>
</li>
<li><a href="http://sourceforge.net/projects/ophcrack/files/samdump2/">Bkhive and Samdump2</a> - Dump SYSTEM and SAM files
<ul>
<li><code>apt-get install samdump2 bkhive</code></li>
</ul>
</li>
<li><a href="http://www.ntcore.com/exsuite.php">CFF Explorer</a> - PE Editor</li>
<li><a href="https://github.com/moyix/creddump">Creddump</a> - Dump windows credentials</li>
<li><a href="https://github.com/kost/dvcs-ripper">DVCS Ripper</a> - Rips web accessible (distributed) version control systems</li>
<li><a href="http://www.sno.phy.queensu.ca/%7Ephil/exiftool/">Exif Tool</a> - Read, write and edit file metadata</li>
<li><a href="http://extundelete.sourceforge.net/">Extundelete</a> - Used for recovering lost data from mountable images</li>
<li><a href="https://github.com/rabbitstack/fibratus">Fibratus</a> - Tool for exploration and tracing of the Windows kernel</li>
<li><a href="http://foremost.sourceforge.net/">Foremost</a> - Extract particular kind of files using headers
<ul>
<li><code>apt-get install foremost</code></li>
</ul>
</li>
<li><a href="http://linux.die.net/man/8/fsck.ext3">Fsck.ext4</a> - Used to fix corrupt filesystems</li>
<li><a href="http://malzilla.sourceforge.net/">Malzilla</a> - Malware hunting tool</li>
<li><a href="http://www.netresec.com/?page=NetworkMiner">NetworkMiner</a> - Network Forensic Analysis Tool</li>
<li><a href="http://malzilla.sourceforge.net/downloads.html">PDF Streams Inflater</a> - Find and extract zlib files compressed in PDF files</li>
<li><a href="http://www.nirsoft.net/utils/resources_extract.html">ResourcesExtract</a> - Extract various filetypes from exes</li>
<li><a href="https://github.com/williballenthin/shellbags">Shellbags</a> - Investigate NT_USER.dat files</li>
<li><a href="http://www.forensicswiki.org/wiki/USB_History_Viewing">UsbForensics</a> - Contains many tools for usb forensics</li>
<li><a href="https://github.com/volatilityfoundation/volatility">Volatility</a> - To investigate memory dumps</li>
</ul>
<h3 id="misckits">Misc/Kits</h3>
<ul>
<li><a href="https://github.com/P1kachu/v0lt">V0lt</a> - Security CTF Toolkit</li>
<li><a href="https://www.sleuthkit.org/">The Sleuth Kit</a> - Digital forensics kit</li>
<li><a href="http://www.metasploit.com/">Metasploit</a> - Penetration testing software</li>
<li><a href="https://github.com/Gallopsled/pwntools">Pwntools</a> - CTF Framework for writing exploits (python)</li>
<li><a href="https://github.com/bettercap/bettercap">Bettercap</a> - Framework to perform MITM (Man in the Middle) attacks.</li>
<li><a href="https://github.com/tomac/yersinia">Layer 2 attacks</a> - Attack various protocols on layer 2</li>
<li><a href="https://regexr.com/">RegExr</a> - RegEx testing/analyzing</li>
<li><a href="https://www.torproject.org/download/download-easy.html.en">TorBrowser</a> - Anonymity matters ;)</li>
<li><a href="https://github.com/zardus/ctf-tools">ctfTools</a> - Everything(ish) you need</li>
</ul>
<h3 id="editors">Editors</h3>
<ul>
<li><a href="https://code.visualstudio.com/">Visual Studio Code</a> - Cool editor with collaborative editing over the internet</li>
<li><a href="http://www.new-hex-editor.com/hex-editor-downloads.html">Neo</a> - Hex editor for windows</li>
<li><a href="https://github.com/bwrsandman/Bless">Bless</a> - Hex editor for linux</li>
</ul>
<h1 id="thats-it">That’s it!</h1>
<p>Thanks uwu - Alaa Zorkane</p>

