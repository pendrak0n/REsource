REsource
========

Currently supported filetypes:
* PE (32-bit/64-bit)
* ELF
* JPEG
* Scripts (BASH, Python, Perl, etc..)


Features
--------
Currently REsource will:
- Provide you with hashes of the file
- Parse the header
- Output the strings from the file into a separate txt file
- Query VirusTotal for the SHA1 hash


How-To
-------
1. Install ruby using RVM, Apt, Yum, or whichever way you choose
2. Clone the repository
3. Add VirusTotal API key to vt.key file in the REsource/bin directory
4. Run resource.rb (will prompt you to run bundle install to install missing dependencies)


Syntax
-------
./resource.rb [-d] -f [malicious.exe | path/to/malware/]
