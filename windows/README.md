## Robocopy switches

### /ZB 
Restartable mode. When not available, copies with backup permissions
### /Ε 
Includes subfolders, even when empty
### /FFT
Fixes timestamp errors
### /R:12
Retry times. By default this is set to 1000000 so make sure you have something there
### /W:5 
Seconds until next retry. Default is 30, 5 is reasonable
### /NP 
Optional, for smaller output file
### /MIR 
Mirror mode, keeps target structure according to the source
### /MT:16 
Concurrent data tranfers. By default this is 8, goes up to 128
### /COPYALLor /COPY:DATSOU 
D(ata) , A(ttributes), T(Timestamps), S(ecurity, NTFS Access Control List), Ο(wner info), U(Audit info)
### /Unilog or log 
