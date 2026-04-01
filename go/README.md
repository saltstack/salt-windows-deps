Go is used to build stub binaries to mimic those needed by the installer.
The NSIS tests create an empty installer to test the functionality of the
installer logic and some stress tests to make sure it's not hanging.

1. salt-minion.exe: A simple binary that runs and responds to Windows service commands
2. vcredist.exes : These just run and return True to mimic installing vcredist. (32 and 64 bit)
