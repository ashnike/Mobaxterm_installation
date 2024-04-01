# Mobaxterm_installation
### This guide provides instructions on how to run MobaXterm on Ubuntu using Wine.
Prerequisites
---
Install Wine, If Wine is not installed, you can install it using the following command:
 ```
sudo apt install wine
 ```
 ### Installation and Setup
1. Download MobaXterm:
Go to the MobaXterm website and download the Windows installer [MobaXterm_Portable_vxx.xx.zip](https://download.mobatek.net/2402024022512842/MobaXterm_Portable_v24.0.zip).

2. Extract MobaXterm:
Extract the downloaded ZIP file to a convenient location. 
3. Run Wineboot:
Open a terminal and run the following command to initialize Wine:
```
wineboot
```
4. Navigate to MobaXterm Directory:
In the terminal, change the directory to where MobaXterm is extracted.
```
wine MobaXterm.exe
```
5. To launch MobaXterm using the script, give the file executable permissions.
```
sudo chmod +x moba_auto.sh
```
7. Copy the script in the Home directory and launch it using the following command.
```
./moba_auto
```
