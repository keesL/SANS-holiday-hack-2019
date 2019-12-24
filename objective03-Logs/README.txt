We're seeing attacks against the Elf U domain! Using the event log data,
identify the user account that the attacker compromised using a password
spray attack. Bushy Evergreen is hanging out in the train station and may
be able to help you out.

sudo apt install python3-evtx
evtx_dump.py ./Security.evtx > Security.xml

Password spraying = using the same password on many accounts. So we're
looking for a single IP with failed login attempts against many accounts,
but also a successful one
