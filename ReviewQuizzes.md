# Quiz Review

Questions that come after a `!` character answered incorrectly.

### Linux CLI Review:

1. `Which command is used to display the current directory you are working in?`
    * Answer is `pwd`
2. `How do you list all files in a directory, including hidden files (those starting with a dot)?`
    * Answer is `ls -a`
3. `What is the primary function of the 'cd ..' command?`
    * Using `cd ..` moves the current location up one level in the directory tree.
4. `Which command allows you to create a new, empty directory?`
    * Using `mkdir` creates an empty directory
5. `What does the 'sudo' prefix do when prepended to a command?`
    * Using `sudo` before a command allows users to run the command using superuser (root) permissions
6. `Which command is used to remove a file? (Caution: This is permanent!)`
    * `rm` deletes a file from the system.
7. `How do you display the contents of a text file directly in the terminal window?`
    * `cat` displays the contents of a file.
8. `Which command is used to move or rename a file?`
    * `mv` can move or rename a file.
9. `What does the 'grep' command do?`
    * Searches for patterns within given text.
10. `Which command shows you a list of currently running processes?`
    * `ps` displays currently running processes.
11. `What is the purpose of the '|' (pipe) operator?`
    * Uses the output of one command as input for another.
12. `Which command is used to change file permissions?`
    * `chmod` is short for "change mode", as it modifies the access permissions.
13. `What does 'man ' do?`
    * Displays the manual page for a given command.
14. ! `Which symbol is used to redirect the output of a command to a file, overwriting its current contents?`
    * The `>` character redirects the output of one command to a file. Gemini had two answers blanked out so I had to guess and I got it wrong.
15. `How do you clear all previous text from the terminal screen?`
    * `clear`

### Network Review:

1. ! `Which layer of the OSI model is responsible for logical addressing and determining the best path for data to travel across a network?`
    * I put in `Transport Layer` instead of `Network Layer`
2. `In a standard Class C network with a subnet mask of 255.255.255.192, how many usable host addresses are available per subnet?`
    * I put in `64` when the answer is `64`
3. `Which type of firewall inspects the actual content of packets and can make decisions based on the specific application or service being used?`
    * Answer is `Application-Level Gateway (Proxy)`.
4. ! `What is the CIDR notation for a subnet mask of 255.255.240.0?`
    * I put in `/22` when the answer is `/20`
5. !`In hierarchical network design, which layer is primarily responsible for high-speed transport and should have as little packet processing as possible?`
    * I put in `Access Layer` when the answer is `Core Layer`
6. ! `Which protocol is commonly used to automatically assign IP addresses, subnet masks, and default gateways to hosts on a network?`
    * I put in `DNS` when the answer is `DHCP`
7. `A firewall that keeps track of the state of network connections (such as TCP streams) to determine which packets to let through is known as:`
    * `Stateful Inspection Firewall`
8. `Which of the following IPv4 addresses is considered a private address according to RFC 1918?`
    * `172.30.50.100`
9. `What is the primary purpose of a VLAN (Virtual Local Area Network)?`
    * `To segment a physical switch into multiple logical broadcast domains`
10. ! `Which subnet mask would you use to create a network that can support exactly 510 usable hosts?`
    * I put in `255.255.255.0`; answer is `255.255.254.0`.
11. `In the context of firewall rules, what is the 'Implicit Deny' principle?`
    * `The practice of blocking all traffic that is not explicitly allowed by a rule`
12. ! `Which of the following is a characteristic of a 'Star' network topology?`
    * I put in `Nodes are connected in a closed loop`, when the answer is `All nodes are connected to a central hub or switch`
13. `What is the primary function of the 'Default Gateway' on a host machine?`
    * `To act as the exit point for traffic destined for other networks`
14. ! `Which protocol works at the Transport Layer and provides 'best-effort' delivery without error recovery or flow control?`
    * I put in `TCP` when the answer is `UDP`
15. ! `If you are using the subnet 192.168.10.0/28, what is the broadcast address for this specific subnet?`
    * I put in `192.168.10.16` when the answer is `192.168.10.15`
