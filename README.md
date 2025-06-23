# MicToPC

MicToPC lets you use your Android phone as a microphone for your PC via Wi-Fi.

---

## Contents

- `MicToPC.apk` — Android app  
- `MicServer` — PC server folder containing:
  - `server.exe` — the server executable  
  - `VBCALBE_Setup.exe` — VB-Cable installer

---

## How to Use

### 1. Install VB-Cable on your PC

- Before running the server, you **must install VB-Cable**.  
- The installer `VBCALBE_Setup.exe` is included in the `MicServer` folder.  
- Run `VBCALBE_Setup.exe` and follow the installation instructions (a reboot might be required).

### 2. Run the Server

- After installing VB-Cable, run `MicToPC-server.exe` from the `MicServer` folder.  
- The server will listen for incoming connections on your local network.

### 3. On your Android phone

- Install the `MicToPC.apk` app.  
- Open the app and enter the IP address of your PC (you can find it using `ipconfig` on Windows).  
- Connect to the server.

### 4. Using the Microphone

- Once connected, your phone's microphone audio is sent to your PC.  
- Thanks to VB-Cable, this audio appears as a virtual microphone input available to all apps.

---

## Requirements

- PC and Android device on the same Wi-Fi network.  
- Windows PC for the server and VB-Cable.

---

## Notes

- Allow firewall permissions for the server executable.  
- Both server and VB-Cable installer are located in the `MicServer` folder.

---

## Troubleshooting

- Check IP address and network connectivity if connection fails.  
- Disable VPNs or proxies that might block communication.  
- Verify firewall permissions on the PC.

---

## License

MIT License

Copyright (c) 2025 [Your Name or Your Organization]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights  
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell  
copies of the Software, and to permit persons to whom the Software is  
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all  
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR  
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,  
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE  
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER  
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,  
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE  
SOFTWARE.

## Contact

For questions or issues, please open an issue in this repository or contact mateusz.wiewiora@outlook.com
