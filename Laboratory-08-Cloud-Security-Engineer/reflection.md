# Mission Reflection – Laboratory 08

Completing this mission taught me a lot about how important security is in the cloud. A host-based firewall like UFW protects a server even if the physical network perimeter is breached. It acts as the last line of defense on the server itself. Even if attackers get past the network firewall, the host-based firewall can still block unwanted traffic before it reaches the applications.

Managing open network ports is critical because every open port is a possible door for attackers. The more ports that are open, the bigger the attack surface becomes. By closing unnecessary ports and only allowing what is needed (like SSH and port 8080), we make it much harder for hackers to find a way in.

In a real enterprise environment, leaving a database port like 3306 (MySQL) open to the public internet is very dangerous. Attackers can try to connect directly to the database, attempt brute-force attacks, or exploit vulnerabilities. Sensitive data such as user information, passwords, and business records can be stolen. Databases should only be accessible from trusted internal networks or through secure private connections.

This mission changed my perspective. I used to think servers were hard to compromise, but I now realize that if the firewall is not configured properly, a server can be attacked within minutes. Automated bots are constantly scanning the internet looking for open ports. One small mistake can lead to a serious security problem.

My GitHub portfolio now has eight completed missions. It looks more professional and organized. Each laboratory shows different cloud computing skills, from basic setup to security. I feel proud of the progress and more confident about working with cloud technologies in the future.
