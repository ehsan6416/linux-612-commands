full-612-commands.md
# My 612 Linux Security Commands Lab - By Ehsan (Sargodha)
I have practiced 200+ commands in Kali Linux Lab. This repo is proof of hands-on work.

## How I Document Each Commands (My Method)
For every commands I Write:
Commands kya check karta hai?
Khatra (Risk) kya hai?

## Day 1 - Network Security (Top 20)
ip -s link - Network interface errors check
journalctl -k -p warning --since today - Kernel warnings
sudo ethtool eth0 - Network speed/dupex
... I will add 200 here daliy ...

Goal: To become Junior SOC Analyst for Australia/USA market.
Profile: github.com/ehsan6416

## Day 2 - My Practical Lab - 24 Oct 2026

ip -s  link 
result: eth0 UP, docker0 DOWN. Risk: DOWN normal hai.

sudo ufw status verbose
Result: Status active. Risk:Koi khatra nahi.

ss -tuln 
Result: Port 80 open. Risk: Hacker attack kar sakta hai. Fix:  ss -tulnp se check karna.

## Day 3 - My Practical Lab - 27 Oct 2026 - Sargodha

## Command 1: sudo lsof +L1
Result: opcache file (delted) - apache2 ka normal file hai. Risk: KOi khatra nahi.
Fix: Not needed.

## Command 2: sudo ls -l /proc/896/exe
Result: -> /usr/sbin/apache2 - Asli apache hai.
Risk: Agar /tmp ya /dev/shm aata to hack hota. Ye safe hai.
Fix: Not needed

## Command 3: sudo ss -tulpen
Result:LISTEN on *:80, 127.0.0.54:53. No ESTAB hacker IP.
Risk: Koi ESTAB nhi, system clean hai.
Fix: Not needed

Final Result of Day 3: System Clean - No Hack Found





