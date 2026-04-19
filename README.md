# Home Lab Setup

A documented build of my personal home lab — starting small, building up.

## Why I'm doing this

I'm studying cybersecurity and wanted hands-on experience with real tools, not just textbook knowledge. This repo tracks what I set up, how I did it, and what I learned.

## Stack

| Tool | Purpose | Status |
|---|---|---|
| Docker | Container runtime | 🚧 Setting up |
| Portainer | Docker management UI | ⏳ Planned |
| Pi-hole | Network-wide DNS filtering / ad blocking | ⏳ Planned |

---

## Docker Setup

### Installation (Ubuntu/Debian)

```bash
# Update packages
sudo apt-get update

# Install prerequisites
sudo apt-get install ca-certificates curl gnupg

# Add Docker's GPG key
sudo install -m 0755 -d /etc/apt/keyrings
curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo gpg --dearmor -o /etc/apt/keyrings/docker.gpg
sudo chmod a+r /etc/apt/keyrings/docker.gpg

# Install Docker
sudo apt-get update
sudo apt-get install docker-ce docker-ce-cli containerd.io docker-buildx-plugin docker-compose-plugin

# Verify
sudo docker run hello-world
```

### What I learned
- *(fill this in as you go)*

---

## Portainer Setup

*(coming soon)*

---

## Pi-hole Setup

*(coming soon)*

---

## Resources that helped

- [Docker official docs](https://docs.docker.com)
- [Portainer docs](https://docs.portainer.io)
- [Pi-hole docs](https://docs.pi-hole.net)

---

*This is a learning project. I'm documenting as I go.*
