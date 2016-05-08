# AstroHub
Attach all astronomy devices to one hub accessible over the LAN.

Build a daemon to run on a Rasberry Pi (or other Linux based computer) that will connect to all astronomy devices and provide a network accessible API for clients running on OSX, Windows, Linux, etc. It would be nice to include a default web based client, being served by the AstroHub, of course. Initial implementation will have support for Starlight Xpress cameras and accessories and LX200 serial protocol. A plug-in architecture will allow for future driver support and real-time functions such as guiding and active optics control.
