# Docker Overview

## Purpose

Docker is a containerization platform that packages applications and their dependencies into lightweight, portable containers. Containers provide consistent environments across different systems while using fewer resources than traditional virtual machines.

In my home lab, Docker allows me to deploy, update, and manage services without affecting the underlying operating system.

---

## Why I Chose Docker

I chose Docker because it offers several advantages for both learning and managing infrastructure:

- Rapid deployment of new services
- Simplified application updates
- Easy rollback if an update fails
- Consistent environments across systems
- Strong community support and documentation
- Industry-standard technology used in IT, DevOps, and cloud environments

Docker also lets me experiment with new software while keeping my host operating system clean and stable.

---

## Why Not Install Directly on the Host?

Installing applications directly on the operating system can create dependency conflicts and make upgrades or removals more difficult.

Running services in containers provides several benefits:

| Docker Containers | Host Installation |
|-------------------|------------------|
| Isolated applications | Shared system dependencies |
| Easy upgrades | Manual upgrades |
| Simple backups | More complex backup process |
| Portable configurations | Configuration tied to one machine |
| Easy removal | May leave behind files or dependencies |

---

## How Docker Fits into My Home Lab

Docker serves as the application platform for my home lab. Rather than installing every service directly onto macOS or Linux, applications are deployed as independent containers.

Current and planned services include:

- Jellyfin
- Tailscale
- Samba
- Monitoring tools
- Backup services

As the lab grows, additional services will be added using Docker Compose.

---

## Skills Demonstrated

- Docker fundamentals
- Container lifecycle management
- Image management
- Networking concepts
- Persistent storage
- Service deployment
- Infrastructure documentation

---

## Lessons Learned

Building this home lab has helped me understand that Docker is more than simply running containers. It is a way to create repeatable, maintainable infrastructure where applications remain isolated, portable, and easy to manage.
