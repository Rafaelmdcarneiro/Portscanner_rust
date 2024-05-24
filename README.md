# 🤔 What is this?

![fast][speed-1]

The Modern Port Scanner. **Find ports quickly (3 seconds at its fastest)**. Run scripts through our scripting engine (Python, Lua, Shell supported).

# ✨ Features

- Scans all 65k ports in **3 seconds**.
- Full scripting engine support. Automatically pipe results into Nmap, or use our scripts (or write your own) to do whatever you want.
- Adaptive learning. RustScan improves the more you use it. No bloated machine learning here, just basic maths.
- The usuals you would expect. IPv6, CIDR, file input and more.
- Automatically pipes ports into Nmap.

## ‼️ Important Links

|         <!--Installation Guide-->          |          <!--Documentation-->          |       <!--Discord-->        |
| :----------------------------------------: | :------------------------------------: | :-------------------------: |
| :book: [Installation Guide][links-table-1] | :books: [Documentation][links-table-2] | :parrot: [Discord][discord] |

## 🙋 Table of Contents

- 📖 [Installation Guide][toc-install]
- 🐋 [Docker Usage][toc-docker-usage]
- 🦜 [Discord][discord]
- 🤸 [Usage][usage-1]

# 🔭 Why RustScan?

RustScan is a modern take on the port scanner. Sleek & fast. All while providing extensive extendability to you.

Not to mention RustScan uses Adaptive Learning to improve itself over time, making it the best port scanner for **you**.

## 🧋 Speed

![fast][speed-1]

Speed is guaranteed via RustScan. However, if you want to run a slow scan due to stealth, that is possible too.

Firstly, let's talk code.

We have tests that check to see if RustScan is significantly slower than the previous version. If it is, the continuous integration fails, and we can't commit code to master unless we make it faster.

[HyperFine][speed-2] is used to monitor RustScan's performance over time to answer the question, "Are we getting faster? Are we getting slower?".

Every pull request is reviewed by **one** person, but more often than not, **two** people review it. We test it manually and ensure the code doesn't negatively affect performance.

[Read more here][speed-3].

## ⚙️ Extensible

![scripts][extensible-1]

### _RustScan piping results into the custom Python script_

RustScan has a new scripting engine that allows anyone to write scripts in most languages. Python, Lua, and Shell are all supported.

Want to take your found ports and pipe them into Nmap for further analysis? That's possible. Want to run `smb-enum` if SMB is found open? Possible.

The possibilities are endless -- and you can write scripts in whatever language you feel comfortable with.

[Read more here][extensible-2].

## 🌊 Adaptive

![adaptive][adaptive-1]

### _RustScan automatically fine-tunes itself to match the host OS_

RustScan has a cool set of features called "Adaptive Learning". These features "learn" about the environment you are scanning and how _you_ use RustScan to **improve itself over time**.

We use this umbrella term for any feature that fits this criterion. The list constantly changes, so [check out our wiki for more information][adaptive-learning].

## 👩‍🦯 Accessible

![fast][accessible-1]

RustScan is one of the first penetration testing tools that aims to be entirely accessible.

[Most penetration testing tools are not accessible][accessible-2], which negatively affects the whole industry.

RustScan has continuous integration testing that aims to ensure it is accessible, and we are constantly working on ways to improve our accessibility and ensure _everyone_ can use RustScan.

# 📖 Full Installation Guide

You can find our guide [here][install-1].

## 🦊 Community Distributions

Here are all of RustScan's community distributions.

If you maintain a community distribution and want it listed here, leave an issue / pull request / Discord message or however, you want to let us know.

- [Open Suse][distributions-1]
- [Fedora/CentOS][distributions-2]

[![Packaging status][rustscan-svg]][repology-1]

# 🤸 Usage

We have 2 usage guides. [Basic Usage][usage-1] and [Things you may want to do][usage-2].

We also have documentation about our config file [here][config-file-here].

<!--Links-->

[Docker]: https://hub.docker.com/r/cmnatic/rustscan "This is the recommended distribution of rustscan"
[kali]: https://github.com/RustScan/RustScan/wiki/Installation-Guide#%EF%B8%8F-debian--kali "Read the install guide"
[Kali/Debian]: https://github.com/RustScan/RustScan/releases "Kali Debian"
[Arch-Linux]: https://archlinux.org/packages/extra/x86_64/rustscan/ "Arch Linux installation of Rustscan"
[Homebrew]: https://crates.io/crates/rustscan/ "Homebrew install of Rustscan"
[usage-1]: https://github.com/RustScan/RustScan/wiki/Usage "Basic Usage of Rustscan"
[usage-0]: https://github.com/RustScan/RustScan/wiki/Installation-Guide#docker-whale "Use Docker Rustscan"
[config-file-here]: https://github.com/RustScan/RustScan/wiki/Config-File "RustScan Configuration File"
[usage-2]: https://github.com/RustScan/RustScan/wiki/Things-you-may-want-to-do-with-RustScan-but-don't-understand-how "Things you may want to do with rustscan but don't know how"
[community-1]: https://github.com/RustScan/RustScan/wiki/Contributing "Learn how to contribute"
[distributions-1]: https://software.opensuse.org/package/rustscan?search_term=rustscan "Open Suse rustscan distribution"
[distributions-2]: https://copr.fedorainfracloud.org/coprs/atim/rustscan/ "Rustscan in Fedora"
[repology-1]: https://repology.org/project/rustscan/versions "Packaging Status"
[install-1]: https://github.com/RustScan/RustScan/wiki/Installation-Guide "Installation guide"
[accessible-2]: https://bees.substack.com/p/making-hacking-accessible "Making Hacking Accessible"
[extensible-2]: https://github.com/RustScan/RustScan/wiki/RustScan-Scripting-Engine "Scripting Engine"
[speed-2]: https://github.com/sharkdp/hyperfine "Hyperfine"
[speed-3]: https://github.com/RustScan/RustScan/wiki/Increasing-Speed-&-Accuracy "Increasing Speed & Accuracy"
[toc-community]: https://github.com/RustScan/RustScan#-community "Community"
[links-table-1]: https://github.com/RustScan/RustScan#-full-installation-guide "Full installation guide"
[links-table-2]: https://rustscan.github.io/RustScan/ "Rustscan"
[discord]: http://discord.skerritt.blog "Discord blog"
[toc-install]: https://github.com/RustScan/RustScan/wiki/Installation-Guide "Installation Guide Wiki"
[toc-docker-usage]: https://github.com/RustScan/RustScan/wiki/Installation-Guide#docker- "Docker Installation Guide Wiki"
[usage-guide]: https://github.com/RustScan/RustScan#-usage
[adaptive-learning]: https://github.com/RustScan/RustScan/wiki/Adaptive-Learning "Adaptive Learning"

<!--Pictures-->

[DockerPic]: https://github.com/RustScan/RustScan/blob/master/pictures/docker.png?raw=true "Docker install"
[Kali1]: https://github.com/RustScan/RustScan/blob/master/pictures/kali.png?raw=true "Kali Picture"
[Arch]: https://github.com/RustScan/RustScan/blob/master/pictures/arch.png?raw=true "Arch Linux"
[Apple]: https://raw.githubusercontent.com/RustScan/RustScan/master/pictures/apple.png?size "Apple"
[rustscan-svg]: https://repology.org/badge/vertical-allrepos/rustscan.svg "Picture of rustscan repology"
[accessible-1]: pictures/accessible.gif "Fast"
[adaptive-1]: pictures/adaptive.gif "Adaptive"
[extensible-1]: pictures/scripts.gif "Scripts"
[speed-1]: pictures/fast.gif "Speed"
[badge-1]: https://img.shields.io/archlinux/v/extra/x86_64/rustscan?style=plastic&logo=archlinux&link=https%3A%2F%2Farchlinux.org%2Fpackages%2Fextra%2Fx86_64%2Frustscan%2F
[badge-2]: https://img.shields.io/badge/Built%20with-Rust-Purple
[badge-3]: https://img.shields.io/github/downloads/rustscan/rustscan/total?label=GitHub%20Downloads
[badge-4]: https://img.shields.io/crates/d/rustscan?label=Cargo%20Downloads
[badge-5]: https://img.shields.io/discord/754001738184392704
[badge-6]: https://github.com/RustScan/RustScan/workflows/Continuous%20integration/badge.svg?branch=master
