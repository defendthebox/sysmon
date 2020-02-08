### Sysmon Concepts
A place to store simple Sysmon logic code snips.
You are free to use these for your own experiments, however, use these at your own risk.  I’ve never had a serious issue with Sysmon, the worst has been a failure to the load a policy and the test system logged 60k events in about 20 minutes.  Test first on a non-critical system.

### Inspiration
I was using PowerShell to scrape folders of binaries I wanted to monitor, it extracts the meta data and auto-generates the Sysmon config compatible XML  I then had a moment of inspiration, what if Sysmon configs could be broken down into their individual rules to make sharing easier and to build modular policies.  Automate as much as possible.

Like most great ideas, I Googled and found that it has already happened, and it’s great:

Olaf's Sysmon-Modular project - https://github.com/olafhartong/sysmon-modular

I’m creating my own repo to store and develop my own personal explorations with Sysmon.

### Pull Requests
No thank you, please contribute to Olaf's project above, they are doing an excellent job of collating these and ensuring they are compatible with the merge script created by Mathias Jessen.  I’ll happily push any of my techniques to their repo if I notice a gap.

### Issues / Feedback
Although I don’t wish to maintain pull requests at this time, if you experience a problem with any of the code here I would love to hear about it, part of making these ideas public is that we all grow as a community when we share and contribute.  I’m not a perfect coder and Sysmon changes frequently allowing new ways of working, if there’s a ‘better’ way, shout!
