## WHiM

WHiM or Wide Hierarchical Muxer

### Background

Originally created as a hypertext muxer powered by the jigdo software which is adding capability for transferring hypertext data, WHiM has evolved to work using several different native tools to transmit data in small chunks.
### Function

WHiM works on the underlying principle of jigdo in which multiple parts and directories are combined into one resulting file at the end. It works with HTTP data as well with an add-on/plug-in for the desired browser which interfaces with whim.dll (Linux implementation coming soon!) 

- Download Files
```
whim -d remotefile.wif
```
or
```
whim -download remotefile.wif
```
- Stream HTTP Data
```
whim -s remotedestination.wsi
```
or
```
whim -stream remotedestination.wsi
```
- Create a WHiM Index File (WIF)
```
whim-compile -f [FILE/DIRECTORY]
```
or
```
whim-compile -file [FILE/DIRECTORY]
```
-Create a WHiM Stream Index (WSI)
```
whim-compile -s [FILE/DIRECTORY]
```
or
```
whim-compile -stream [FILE/DIRECTORY]
```
- Browser Data Stream (for Sites Supporting RDR)
```
whm://remotedestination
```
- Browser Data Stream (for Sites without RDR Support)
```
whm://remotehost.com/remotedestination.wsi
```
### Status
.https://img.shields.io/badge/status-DEVELOPMENT-red.svg

© 2019 AlteredGenome
