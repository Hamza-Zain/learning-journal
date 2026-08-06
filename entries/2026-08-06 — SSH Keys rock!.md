# 2026-08-06 — SSH Keys rock!

> **Related Topic(s):** Linux, SSH, Git, GitHub, Security

---

## What Happened

When I started using Git on Linux, I relied on password-based authentication because it felt simpler and more familiar. At first, I thought SSH keys were adding unnecessary complexity to the login process.

After learning Git and GitHub, understanding how SSH keys work on Linux, and configuring them successfully in the lab, I decided to switch to SSH key authentication.

Several reasons influenced my decision. I always look for ways to improve security, and I also had an incident where I accidentally pasted my password into the terminal. Although nothing happened, it made me realize how easily sensitive information could be exposed.

These reasons encouraged me to invest some time in understanding SSH keys. The initial setup seemed complicated because I didn't fully understand how they worked. Once everything clicked, I realized the process was actually straightforward. I also liked the idea of authenticating without ever transmitting my private key to the remote system.

One thing that made the concept easier to understand was its similarity to authentication mechanisms used in 5G core networks. It also reminded me, at a high level, of the TLS handshake, where both sides prove their identity without exposing secret information. Making these connections helped me understand the underlying idea instead of simply memorizing the setup steps.

After completing the setup, I documented the entire process in a guide called `Configuring GitHub SSH Authentication on Linux Debian KDE.md`. Writing the guide reinforced my understanding and gave me a reference for future setups.

Another pleasant surprise was discovering that Debian KDE integrates the SSH Agent with KDE Wallet. After unlocking my laptop, KDE Wallet automatically unlocks my SSH key for the rest of the session. As a result, I no longer have to enter my passphrase every time I use Git or connect to a server.

Now I can run commands such as `git pull` and `git push` without repeatedly entering my SSH key passphrase or manually adding the key to the SSH agent. My workflow has become both more secure and more convenient.

---

## Lessons Learned

- SSH keys provide stronger authentication than passwords.

- Understanding how a technology works makes its setup much easier.

- A passphrase protects the private key without making daily work inconvenient when combined with KDE Wallet and the SSH Agent.

- Relating new concepts to technologies I already know, such as 5G core security and TLS, helps me learn faster and retain the knowledge.

- Documenting what I learn reinforces my understanding and creates useful references for the future.

---
