---
layout: post
title: "ArchNemesis"
date: 2026-05-21
---

# Arch Nemesis

It has been a while, but I've finally mustered up the courage to tackle Arch. The assignment was simple: Install Arch, on whatever I liked. Since I am not a million-different-systems-haver, a Virtual Machine would have to do.

So, install Arch on a VM, and as the grand challenge: Make sure I can connect to the internet, open a filebrowser and use chromium to browse the world wide web.

### The Arch Wiki

The assignment was pretty clear in what I should use: *The Arch Wiki*. This sounds incredibly fair, but upon entering of this hellish landscape it felt like it was all but that. Perhaps this is me being ignorant and naïve, but there was nothing particularly comprehensible about the Arch Wiki Installation guide.

You see, I'm not as tech savvy as I would like to be. So when my eyes tried to parse this paragraph:

> #### Verify Signature
>It is recommended to verify the image signature before use, especially when downloading from an HTTP mirror, where downloads are generally prone to be intercepted to serve malicious images.

> Download the ISO PGP signature from https://archlinux.org/download/#checksums to the ISO directory and follow the instructions there to verify it.

> Alternatively, from an existing Arch Linux installation run:

> $ pacman-key -v archlinux-version-x86\_64.iso.sig

This kind of thing makes my mind go **blank**. Basically, the Arch ISO can be acquired via torrenting. Fun fact, **I now know how torrenting works and how to do it**. I genuinely always thought it was illegal voodoo magic but the process was quite simple to understand and use, and it makes sense why Arch of all software would use it for their download.

But regardless of my beautiful new qBitTorrent installation, I still did not understand what *any of this shit meant.* So I did what any right-brained noob would do and ignored it. "lets send it", I said.

The pain doesn't really end there though, this was just a poke. The entire installation guide is filled with technical jargon I would never hope to understand. Let's just go through the article one more time and count the amount of terms I *don't know*.*

### The Forbidden Term List

<details>
<summary> Open me! </summary>
<ul>
<li> x86\_64-compatible machine </li>
 <li>netboot image</li>
 <li>PGP signature (I now know what this is, but I wouldn't know how to work with it)</li>
 <li>HTTP mirror</li>
 <li>PXE</li>
 <li>boot device > installation medium</li>
 <li>mirror</li>
 <li>virtual console</li>
 <li>UEFI bitness / Bootmode</li>
 <li>DHCP</li>
 <li>block device</li>
 <li>partitioning for boot devices?</li>
 <li>stacked block devices (LVM, system encription, RAID)</li>
 <li>EFI system partition</li>
 <li>Swap space</li>
 <li>Mount and Mount Points</li>
 <li>FAT32 and others</li>
 <li>Mirror servers</li>
 <li>Reflector</li>
 <li>CPU Microcode Updates</li>
 <li>firmware</li>
 <li>Linux Kernel (I mean, I sort of know what it is)</li>
 <li>Fstab file</li>
 <li>Persistent Block Device Naming</li>
 <li>Chroot</li>
 <li> "Creating a new initramfs is usually not required, because mkinitcpio was run on installation of the kernel package with pacstrap." what? </li>
 <li>Boot Loader</li>
</ul>

</details>

I probably skipped over a few, but god damn. Spoilers, this entire thing took me not even 4 hours to complete, but only because I feel like I've cheated.

### I Cheated

Out of fear of burning out immediately upon the sight of my helplessness with the terminologies and difficult to read instructions, I looked for different resources. One of them was a github page with an installation guide, which was based directly off of the Arch installation Wiki.

The big difference: *This guide actually referenced VM use*. It just so happens that there are things you have to do *differently* when installing within a VM, which is not exactly something the Arch Wiki will tell you.

When it comes to guides, I do feel like prerequisite knowledge of topics could be a great addition to newcomers. Right now I do genuinely feel quite overwhelmed by the writing, so I'm forced to explore different resources.

However, the assignment pretty clearly said I had to use the Arch Wiki, not use a resource that, while directly referencing the Arch Wiki, **is not Arch Wiki.** So perhaps I have cheated on this assignment.

### Installation

It took 3 tries. The resource I used was outdated on one end. Specifically that, it being a linux installation and all, **did not include a linux kernel** in its installation instructions. The reason I restarted twice is that once you have done something wrong in the installation, it seems there's no turning back. Not with my level of expertise. I fumbled around with attempting fixes, but restarting from scratch just seemed like the right play (it kinda was).

So, the installation went around. I got to the terminal. Starting up still requires me to select "Boot from existing OS" then select the Arch OS to *actually* start the machine, but I count it as a win. I was finally prompted by the magic terminal, freed from partitioning and invisible setup.

### Desk your own Top

It was pretty easy to tell why people like Arch. It really is barebones. The installation guide doesn't go further than this, so I went to other resources (including the Wiki) to find the next steps. To be honest, I feel like so far I am literally just discreetly following step-by-step guides to get to where I am at, but not really learning what I am doing.

Now, it was similar, but at least I understood I have to install the following things: A window manager to actually display my windows, a desktop environment to show me a desktop, and a login screen (they have fancy names for this shit but it's just a login screen, fight me).

This part was honestly a bit of a struggle because even if I did the installs right, it was commonly clamoured that stuff like MATE (my desktop environment) allegedly *needs some time* to get used to the machine it's in. That was true though, I was scouring the forums for solutions to the simple problem of my window manager not doing its job, only to return to the VM and notice it working just fine.

So there we went, we pacmaned chromium out of the depths of hell and started it, and it worked. Then we opened up filebrowser and it bloody hell didn't. However, looking online I found I can open *a* filebrowser with Caja or something? Well okay. We have a file browser and I am accessing the internet via Chromium. Job complete.

### Reflection

Once again, I do feel like I have not gotten a grip on what exactly I have done. I created partitions, some for boot, some for just storage, and some for swap.. I installed a bunch of packages and default lists.. I installed a linux kernel.. I just don't really know how I did all that, and what's going on behind the scenes.

To be fair, this has never been my strong suit or in my interests, because to me this kind of tinkering is more suited for people who enjoy fleshing out PCs and taking full control. I'm more of a use-software-get-results type of guy.

Not saying it wasn't sort of fun. I don't know how prideful I should be of making this work, but 4 hours for an Arch installation, which Lucy the linux expert kept warning me *not* to do? Not too shabby, surely? Or have I not done "everything I'm supposed to do and figure out". Perhaps. I was just following the guides.

Don't ask me if my sound card works. Tbh I think VirtualBox took care of way too much. Perhaps this would've been harder on a fresh system with USB booting.

![Image of Proof](../assets/arch-nemesis.png)
