---
title: Entry1-BlogStart
date: 2026-04-01
toc: false
layout: post
---
### Entry 1

This entry will be all about setting up the blog. Technically there *was* another entry regarding the github installation, but ill have to figure out how to move that over here (I'll probably call it entry 0, truly meta).

Something I've noted is my overcomplication in installing jekyll, the package that this blog runs with. I've looked at multiple sources, from users retelling their installations to tutorials written during the time I was grinding coins in Minecraft.

Most of it just seemed outdated. There was no way that this crap is so weirdly complex to install with twenty different methods to do it. I thought I'd get lost on this, until I found an incredible resource: Jekyllrb.com. Yeah, the *official* documentation. Fucking duh.

So yeah, the installation was only a couple commands away. Problem is, and I'm writing this as a note to myself, that the guide advises:

> Avoid installing RubyGems packages (called gems) as the root user. Instead, set up a gem installation directory for your user account. The following commands will add environment variables to your ~/.bashrc file to configure the gem installation path:<br>
> echo '# Install Ruby Gems to ~/gems' >> ~/.bashrc
> echo 'export GEM_HOME="$HOME/gems"' >> ~/.bashrc
> echo 'export PATH="$HOME/gems/bin:$PATH"' >> ~/.bashrc
> source ~/.bashrc

I'll be honest, this part scares me a little bit because I do *not* know what it does. At least if it ever breaks, I will know to look back here.
