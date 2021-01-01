---
layout: default
title: FAQ
nav_order: 10
---
# Frequently Asked Questions
{: .no_toc }

General questions and further learnings regarding the technology used in Umbrel.

Issues concerning the primary operations of your Umbrel node can be found in the separate [Troubleshooting](troubleshooting.md) guide.

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

## Can I get rich by routing Lightning payments?

Nobody knows. Probably not. You will get minimal fees. I don't care. Enjoy the ride!

## Can I attach the Ext4 formatted hard disk to my Windows computer?

The Ext4 file system is not compatible with standard Windows, but with additional software like [Linux File Systems](https://www.paragon-software.com/home/linuxfs-windows/#faq) by Paragon Software (they offer a 10 days free trial) it is possible.

## What do all the Linux commands do?

This is a (very) short list of common Linux commands for your reference. For a specific command, you can enter `man [command]` to display the manual page (type `q` to exit).

| command      | description                        | example                                      |
| ------------ | ---------------------------------- | -------------------------------------------- |
| `cd`         | change to directory                | `cd /home/umbrel`                            |
| `ls`         | list directory content             | `ls -la /home/umbrel/umbrel`                 |
| `cp`         | copy                               | `cp file.txt newfile.txt`                    |
| `mv`         | move                               | `mv file.txt moved_file.txt`                 |
| `rm`         | remove                             | `rm temporaryfile.txt`                       |
| `mkdir`      | make directory                     | `mkdir /home/umbrel/newdirectory`            |
| `ln`         | make link                          | `ln -s /target_directory /link`              |
| `sudo`       | run command as superuser           | `sudo nano textfile.txt`                     |
| `su`         | switch to different user account   | `sudo su root`                               |
| `chown`      | change file owner                  | `chown umbrel:umbrel myfile.txt`             |
| `chmod`      | change file permissions            | `chmod +x executable.script`                 |
| `nano`       | text file editor                   | `nano textfile.txt`                          |
| `tar`        | archive tool                       | `tar -cvf archive.tar file1.txt file2.txt`   |
| `exit`       | exit current user session          | `exit`                                       |
| `systemctl`  | control systemd service            | `sudo systemctl start umbrel-startup`        |
| `journalctl` | query systemd journal              | `sudo journalctl -u umbrel-external-storage` |
| `htop`       | monitor processes & resource usage | `htop`                                       |
| `shutdown`   | shutdown or restart Pi             | `sudo shutdown -r now`                       |

## Where can I get more information?

If you want to learn more about Bitcoin and are curious about the inner workings of the Lightning Network, the following articles in Bitcoin Magazine offer a very good introduction:

- [What is Bitcoin?](https://bitcoinmagazine.com/guides/what-bitcoin)
- [Understanding the Lightning Network](https://bitcoinmagazine.com/articles/understanding-the-lightning-network-part-building-a-bidirectional-payment-channel-1464710791/)
- [Bitcoin resources](https://www.lopp.net/bitcoin-information.html) and [Lightning Network resources](https://www.lopp.net/lightning-information.html) by Jameson Lopp

## Does Umbrel support .....?

Currently not, but the we are working on an application infrastructure, so third-party developers can add their own apps to Umbrel and publish them in its [App Store](https://medium.com/getumbrel/introducing-the-umbrel-app-store-7a2068c64a10).

---

This General FAQ guide will be constantly updated with findings that have been or will be reported in the issues section. Feel free to contribute via a pull request.

---