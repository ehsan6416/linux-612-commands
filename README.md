# linux-612-commands
My 612 Linux security command from Sargodha, Pakistan. Learning Bug Bounty for International Clients.
## Who am I?
i am Ehsan From Sargodha, learning Linux Security. My goal is to work with security companies in Australia & USA.
## My Top 5 Practiced Commands (with proof)
I have practiced these in my Kali Linux iab:
'ip -s link' - To check network interface errors and drops
'sudo ufw status verbose' - To verify firewall is active
'journalctl -k -p warning --since today' -To find kernel security warnings
'sudo ethtool eth0' -To check network driver vulnerabilities
'ip link show' - To list all network devices

## Full 612 Command list
I have 612 commands in total. Uploading them in commands folder step by step.

## Tool I know
MobSF (Mobile Security Framework)
Kali Linx
GitHub

Contsct: github.com/ehsan6416

## day 2 - My Practical Lab - 24 Oct 2026

ip -s link 
Result: etho UP, docker0 DOWN. Risk: DOWN normal ha. Fix ki zarurat nahi.

sudo ufw status verbose 
Result: Status active, deny incoming. Risk: Koi khatra nahi, firewall ON nai.Agar inactive hota to hacker andar aa sakta tha. Fix: sudo ufw enable.



