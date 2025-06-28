# 🧠 Arch Linux Learning Journey

AI generated checklist of things to learn about linux through booting arch. i use arch btw max neckbeard energy.

---

## 📦 Status

> ⏳ = In Progress, ✅ = Complete, 💤 = Not Started

| Section                       | Status |
| ----------------------------- | ------ |
| 1. Install Arch from Scratch  | ⏳     |
| 2. System Fundamentals        | 💤     |
| 3. Graphical Environment      | 💤     |
| 4. Package Management Mastery | 💤     |
| 5. System Internals           | 💤     |
| 6. Scripting & Dotfiles       | 💤     |
| 7. Security & Hardening       | 💤     |
| 8. DevOps & Networking        | 💤     |
| 9. Recovery & Maintenance     | 💤     |
| 10. Bonus Challenges          | 💤     |

---

## 🧱 1. Install Arch from Scratch

- [x] Partition disk manually with `fdisk` / `gdisk`
- [x] Format partitions (ext4 / btrfs / vfat)
- [x] Mount partitions manually
- [x] Use `pacstrap` to install base system
- [x] Configure locale, hostname, timezone, etc.
- [x] Install GRUB or systemd-boot
- [ ] (Optional) Full disk encryption with LUKS -> I don't care enough, just like how no one uses bitlocker.

---

## 🧰 2. System Fundamentals

- [ ] Set up networking (e.g., `NetworkManager`, `systemd-networkd`)
- [ ] Learn `systemctl`, `journalctl`, and manage units
- [ ] Configure users and groups
- [ ] Understand and explore the FHS (Filesystem Hierarchy Standard)
- [ ] Explore `/etc`, `/proc`, `/sys`, and their purposes

---

## 🖥️ 3. Graphical Environment

- [ ] Install and configure Xorg
- [ ] Try at least one Desktop Environment (GNOME, KDE, etc.)
- [ ] Try at least one Window Manager (i3, bspwm, sway)
- [ ] Set up `.xinitrc` or use a display manager (`gdm`, `lightdm`)
- [ ] Configure DPI, fonts, and screen layout

---

## 📦 4. Package Management Mastery

- [ ] Install and remove packages with `pacman`
- [ ] Use `yay` or `paru` to access the AUR
- [ ] Manually build a package from a PKGBUILD
- [ ] Create and test my own PKGBUILD
- [ ] Set up and explore `pacman.conf`

---

## 🧠 5. System Internals

- [ ] Monitor with `top`, `htop`, `ps`, `lsof`
- [ ] Explore `/proc` and `/sys`
- [ ] Use `strace` to inspect system calls
- [ ] Learn about kernel modules: `lsmod`, `modprobe`, `rmmod`
- [ ] Recompile the kernel (optional but cool)

---

## 🧬 6. Scripting & Dotfiles

- [ ] Set up personal dotfiles repo
- [ ] Use `stow` or `chezmoi` to manage dotfiles
- [ ] Write bash/zsh scripts for system setup
- [ ] Automate package installs with scripts
- [ ] Set up GitHub Actions to lint/test dotfiles (optional)

---

## 🔐 7. Security & Hardening

- [ ] Set up a firewall (`ufw` or `iptables`)
- [ ] Audit system services and disable unused ones
- [ ] Understand permissions and file ownership
- [ ] Use `sudoers` safely and securely
- [ ] (Optional) Set up AppArmor or SELinux (advanced)

---

## ☁️ 8. DevOps & Networking

- [ ] Run a local web server (e.g., nginx, Python)
- [ ] Install Docker or Podman on Arch
- [ ] Create a `systemd` service for a script
- [ ] Build a GitHub Actions workflow for reproducible setup
- [ ] Set up an Arch VM or remote install on a cloud provider

---

## 🧼 9. Recovery & Maintenance

- [ ] Use a live ISO + `arch-chroot` to recover system
- [ ] Backup system state and config
- [ ] Restore system manually after failure
- [ ] Set up snapshots with `btrfs` or Timeshift

---

## 🧗 10. Bonus Challenges

- [ ] Install Arch without looking at the wiki
- [ ] Build a custom ISO of my Arch setup
- [ ] Package a personal script/app for AUR
- [ ] Install Arch on ARM device (e.g., Raspberry Pi)
- [ ] Use Wayland + Sway or Hyprland instead of X11
