# project_ideas
Random project ideas


# Memory Forensics
* Like, what's the state on integration from volatility to Ghidra ?
* reconstructing OS data structures to truly pick out process memory?
* Comparing divergences between Autopsy and volatility?
* Like, even this only happened in DEF CON 24: https://media.defcon.org/DEF%20CON%2024/DEF%20CON%2024%20presentations/DEF%20CON%2024%20-%20Jkambic-Cunning-With-Cng-Soliciting-Secrets-From-Schannel-WP.pdf . But what about from Chrome?

# Disk Forensics
* Reassemble fragmented zip files from file carving, based on published file sizes, CRC-32 checksums, etc. No reason you couldn't do that for other archive formats with similar structures. Implement in Autopsy / file carving utils / separate script ?

# Fuzzing
* Build corpus from existing bug trackers, wikis, etc.

# Vulnerability Reseach
## Find a way to find DLL injection  (sideloading) vulnerabilities **statically**
* https://securityintelligence.com/x-force/hunting-evidence-dll-side-loading-powershell-sysmon/
* https://www.emsisoft.com/de/blog/43943/what-is-dll-side-loading/
* https://www.mandiant.com/sites/default/files/2021-09/rpt-dll-sideloading.pdf
* https://attack.mitre.org/techniques/T1574/002/
* https://www.wietzebeukema.nl/blog/hijacking-dlls-in-windows
* https://github.com/wietze/windows-dll-hijacking/
* https://posts.bluraven.io/detecting-dll-hijacking-attacks-part-1-bdb354685164
* https://github.com/hautakan/disobey24
* https://www.youtube.com/watch?v=tuek6LSPf8E
* https://unit42.paloaltonetworks.com/dll-hijacking-techniques/#post-132679-_wd51wywrrg8f
* https://en.wikipedia.org/wiki/Dynamic-link_library#DLL_hijacking
* https://support.microsoft.com/en-us/topic/secure-loading-of-libraries-to-prevent-dll-preloading-attacks-d41303ec-0748-9211-f317-2edc819682e1
* https://securityintelligence.com/x-force/hunting-evidence-dll-side-loading-powershell-sysmon/
* https://www.crowdstrike.com/blog/4-ways-adversaries-hijack-dlls/
* https://www.upguard.com/blog/dll-hijacking


# Random
* Generate MP4 subtitles, then add them as a "Comment" metadata in Windows, so they're searchable
