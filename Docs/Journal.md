# 10/07/26

## Tasks Completed:

### Drew a System Overview Diagram
I hand-drew a diagram encompassing how the entire project is projected to look, giving me a big picture of how everything is going to connect to each other. Labelled "Diagram of System Overview Pre-Implementation.jpg" in the Diagrams folder within the repository.

### Prepared the Raspberry Pi
I started by flashing the Pi OS onto the Raspberry Pi using a Micro-SD card and chose a headless setup using SSH over WiFi. Once I had connected to the Raspberry Pi using SSH from my laptop, I installed the GPIO libraries necessary for interacting with the hardware.

### Set up VS Code Remote-SSH
I set up the Remote-SSH function in VS Code and connected it remotely to the Raspberry Pi so I can develop the software in this project on my laptop rather than editing these files on a terminal. This gives me the capabilities of an IDE (such as: syntax highlighting, auto-completing and an integrated terminal) to help make the coding process as efficient as possible. This also mirrors real IoT development practices where I code on a more usable platform then test my code against the real hardware.

## Problems and their solutions:
While trying to SSH to the Raspberry Pi on my laptop I was having difficulties connecting because I couldn't resolve the hostname. This was because I didn't know the IP address of it. So I scanned my local subnet using nmap and found it, then I connected to the Pi via SSH using the IP address directly rather than the hostname.

## What did I learn:
- How to set up a Raspberry Pi using headless setup.
- How to use nmap to discover different devices on a network.
- How to draw and annotate diagrams to represent the general architecture of IoT projects.
- How to set up Remote-SSH on VS Code.

## Tomorrow's Plan:
- Complete the rest of the diagrams (one more focused on the electronics of the project and another on the mechanical side of the project and finally a diagram of these 2 systems integrated).
- Learn how to set up the wiring of the project and test the mechanical components to see if they are suitable for the project (provided the components have arrived).

