# 🗂️ Linux Filesystem Hierarchy Standard (FHS)

> Understand the purpose of every directory in the Linux root filesystem (`/`).
> Each lab is a standalone hands-on repo with **6 tasks** showing real-world usage on **RHEL 9 / Rocky 9 / Ubuntu**.

---

## 📚 What This Series Covers

- The 20 top-level directories of a modern Linux system.
- Why each directory exists, what lives there, and how it's used in production.
- Hands-on inspection labs you can run on any Linux box without breaking it.
- Cross-references to the broader [`linux-ops-mastery`](https://github.com/kelvintechnical/linux-ops-mastery) curriculum.

---

## 🧭 The 20 Directory Labs

| #  | Lab | Directory | Purpose |
|----|-----|-----------|---------|
| 01 | [What is the /bin directory?](https://github.com/kelvintechnical/bin-directory)       | `/bin`    | Essential user commands — `ls`, `cp`, `cat` |
| 02 | [What is the /sbin directory?](https://github.com/kelvintechnical/sbin-directory)     | `/sbin`   | Admin-only commands — `fdisk`, `reboot`, `iptables` |
| 03 | [What is the /lib directory?](https://github.com/kelvintechnical/lib-directory)       | `/lib`    | Shared libraries needed by `/bin` and `/sbin` |
| 04 | [What is the /lib64 directory?](https://github.com/kelvintechnical/lib64-directory)   | `/lib64`  | 64-bit shared libraries |
| 05 | [What is the /usr directory?](https://github.com/kelvintechnical/usr-directory)       | `/usr`    | User programs, utilities, and their libraries |
| 06 | [What is the /etc directory?](https://github.com/kelvintechnical/etc-directory)       | `/etc`    | System-wide configuration files |
| 07 | [What is the /boot directory?](https://github.com/kelvintechnical/boot-directory)     | `/boot`   | Kernel, initramfs, and GRUB bootloader |
| 08 | [What is the /home directory?](https://github.com/kelvintechnical/home-directory)     | `/home`   | Personal directories for standard users |
| 09 | [What is the /root directory?](https://github.com/kelvintechnical/root-directory)     | `/root`   | Home directory for the root user |
| 10 | [What is the /var directory?](https://github.com/kelvintechnical/var-directory)       | `/var`    | Variable data — logs, mail, databases |
| 11 | [What is the /tmp directory?](https://github.com/kelvintechnical/tmp-directory)       | `/tmp`    | Temporary files — cleared on every reboot |
| 12 | [What is the /opt directory?](https://github.com/kelvintechnical/opt-directory)       | `/opt`    | Third-party software packages |
| 13 | [What is the /srv directory?](https://github.com/kelvintechnical/srv-directory)       | `/srv`    | Data served by system services (web, FTP) |
| 14 | [What is the /dev directory?](https://github.com/kelvintechnical/dev-directory)       | `/dev`    | Device files — hard drives, terminals, random |
| 15 | [What is the /proc directory?](https://github.com/kelvintechnical/proc-directory)     | `/proc`   | Virtual filesystem — kernel and process info |
| 16 | [What is the /sys directory?](https://github.com/kelvintechnical/sys-directory)       | `/sys`    | Virtual filesystem — hardware and kernel modules |
| 17 | [What is the /run directory?](https://github.com/kelvintechnical/run-directory)       | `/run`    | RAM-based runtime data since last boot |
| 18 | [What is the /media directory?](https://github.com/kelvintechnical/media-directory)   | `/media`  | Auto-mount point for removable media |
| 19 | [What is the /mnt directory?](https://github.com/kelvintechnical/mnt-directory)       | `/mnt`    | Temporary manual mount points |
| 20 | [What is the /afs directory?](https://github.com/kelvintechnical/afs-directory)       | `/afs`    | Enterprise network filesystem (Andrew File System) |

---

## 🧩 Lab Structure

Each repo follows the same 6-task scaffold:

1. **Inspect** — look at the directory itself.
2. **Inventory** — list what lives inside it.
3. **Read** — open a representative file or examine metadata.
4. **Demonstrate** — show the directory doing its job.
5. **Cross-reference** — connect to related directories or tooling.
6. **Capstone audit** — produce one short artifact that proves understanding.

Every lab includes Objective, Concept, "Why It Exists — The Story", Family table, Anatomy diagram, Reference table, Career Pathway Sidebar, Decision Guide, Checklist, Common Pitfalls, and Career & Interview Strategy.

---

## 🎯 Who This Is For

- **RHCSA / RHCE candidates** preparing for EX200 / EX294.
- **SRE / Platform engineers** who need to debug "where did that file go?" calmly.
- **DevOps engineers** writing Ansible / Terraform that respects FHS conventions.
- **AI / MLOps engineers** deploying models on Linux hosts and needing to choose `/opt` vs `/usr/local` vs `/var/lib` for state.

---

## 🔗 Parent Curriculum

Part of [`linux-ops-mastery`](https://github.com/kelvintechnical/linux-ops-mastery) — the full Linux+ → RHCSA → RHCE → SRE / DevOps learning path.

---

## 👤 Author

**Kelvin R. Tobias**
[kelvinintech.com](https://kelvinintech.com) · [GitHub](https://github.com/kelvintechnical) · [LinkedIn](https://www.linkedin.com/in/kelvin-r-tobias-211949219)
