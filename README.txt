# makemon
Make a single (or up to 10) monitor mode wireless interfaces with unique mac addresses.

# Dependencies
 1.) iw
 2.) macchanger
 
 # Usage
 User@group:~# makemon -c     <--Creates a single monitor interface.
 User@group:~# makemon -m     <--Creates many mon interfaces up to 10.
 User@group:~# makemon -d     <--Delete all mon interfaces.
 
 # Extra Info
 This tool does not use "macchanger" to generate mac addresses. It instead uses macchanger to compare
 the randomly generated mac with the first 3 octets in macchanger's mac vendor list.
 
 # Disclaimer
 This tool is released to the public in the hopes that it will be useful. This has not been coded in
 the most perfect and absolutely best manner. This is done intentionally to spur users into looking into
 bash programming on their own and figure out ways to help improve open source tools and the open
 source community. Cheers!!
 
