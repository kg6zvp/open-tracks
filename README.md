# Open Tracks

Idea repository for tracking feature usage in open source projects

Open source projects (like [Icing](https://github.com/kg6zvp/icing-server)) need a way to track feature usage like Google Analytics does.

Open source projects have different constraints than closed-source apps and sites for feature usage:

- Can't require secret keys buried in source code for tracking
- Can't be reliant on a single hosted location for web UI tracking
- Can't be reliant on a signed app build for tracking
- Must allow some modification of source code without invalidating tracking data
- Must allow tracking data to be distributed in a decentralized fashion
- Must be resistant to tampering
