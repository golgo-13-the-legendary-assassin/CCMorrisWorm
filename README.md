# CCMorrisWorm
A ComputerCraft implementation of a self spreading computer worm leveraging existing CC API's and infrastructure.

## WARNING
CCMorrisWorm is currently under construction.

## Disclaimer
CCMorrisWorm is an academic project for use by consenting adults, on systems and infrastrucutre given explicit permission to do so. The CCMorrisWorm project does not claim or accept any legal responsibility for individuals utilizing this themselves.

## About
Named afer the infamous Morris Worm of 1988, this ComputerCraft Rednet API self replicating worm leverages existing security vulnerabilities in in-game machines and infrastructure to self replicate and deliver whatever payload its author intends. Just as its progenator, this project exists purley to see if it can be done, for science, and discovery! It boasts *automated* behaviors/capabilities:
* Network discovery
* Remote shell creation
* Schedueling

Likewise it is meant for easy plug-and-play with whatever payload users would like to insert.

## Mods/Dependencies
* ComputerCraft

## History
Originally created by Robbert Morris just to see if it was possible, the Morris Worm was the first worm (self discovery and replicating program) to make it into the public's eye (outside of fiction) in 1988. This was in violation of the 1986 Computer Fraud and Abuse Act and ended up landing Morris with a felony charge. However, alls well that ends well, and he later went on to become a tenured professor at MIT. The original worm itself leveraged multiple vulnerabilities:

* sendmail SMTP service bug allowing it to execute a command interpreter and download code across a mail connection
* Buffer overflow in finger unix command
* Post-authorization network propogation via rsh/rexec shared accounts

For a more comprehensive technical analysis, information is available here:
http://www.cs.unc.edu/~jeffay/courses/nidsS05/attacks/seely-RTMworm-89.html

## ComputerCraft's Blurb On Security
"In current versions of ComputerCraft (1.5 or later), Rednet is not to be considered a "secure" method of communication. The identity data indicating who sent a given message is set by the sender, and hence cannot be trusted. Messages intended for a given system may be received and read by any other system in range.

This is because Rednet is simply a convenience wrapper for the modem API, and while it typically sends/receives using channel numbers matching the IDs of systems you control, the latter offers complete control over channel usage. Another user can hence easily task the modem API directly to sniff and find out what messages a computer is receiving if he knows (or can even guess) its ID, or pretend to send from any ID he wishes.

When using Rednet for anything with security implications, be sure to implement your own methods of protection."

## Network Set-Up
Want to commit C Y B E R   C R I M E? Well its never been easier, you too can get in on the action! *But*, first you'll need to invent the internet. ComputerCraft is a rather robust mod within itself, you'll need to build the appropriate computers, connections (or well thought out physical proximity), modems, and more. Not to fear though, we'l hold your hand through this.

## Functionality

## Usage
