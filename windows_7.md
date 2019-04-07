Steps to speed up Windows 7 performance:
- stay up to date
- uninstall unwanted programs
- scan with [malwarebytes](https://www.malwarebytes.com)
- use SSD for C: partition (Windows OS)
- make sure C: has free space 5 GB as a minimum
- Power option -> high performance
- Defragment the C: to optimize
- Disable some startup programs by CTRL+R then `msconfig`
- CTRL+R then `msconfig` : disable services
- Win+R del `temp`
- Win+R del `%temp%`
- Del IDM downloaded: `C:\Users\userName\AppData\Roaming\IDM\DwnlData\userName\` replace the `userName` with your PC name
- Del recyclebin
- Disk cleanup
- `advanced system settings` > `Performance Settings` > `Adjust for best performance`
- optimize [Google Chrome](https://github.com/DevAbanoub/optimize_performance/blob/master/chrome.md)
- BIOS || UEFI > Enable virtualization and other CPU facilities
- BIOS || UEFI > Turn of power saving.
- fix filesystem errors : Win + R > cmd.exe > `CHKDSK C: /F`
- fix corrupted Windows files : Win + R > cmd.exe > `sfc /scannow`
- check HDD for bad sectors using HD Tune or HD Sentinel