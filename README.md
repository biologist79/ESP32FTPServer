# ESP32FTPServer
Simple FTP Server for Espressif ESP32
Based on the work from https://github.com/HenrikSte/ESP32FTPServer and https://github.com/MollySophia/ESP32_FTPServer_SD (which again is based on https://github.com/robo8080/ESP32_FTPServer_SD) 

Just resized the global buffer and introduced method isConnected().<br />
SD_MMC is now supported (thanks to tueddy for the contribution).<br />
Be advised that only one simultaneous connection is possible. I recommend [Filezilla](https://filezilla-project.org/) as it's a multi-OS-platform and this parameter can be configured there.
