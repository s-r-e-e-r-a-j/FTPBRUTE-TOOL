# FTPBrute

FTPBrute is a GUI-based FTP brute-forcing tool created with Python. It allows you to attempt username-password combinations on an FTP server using wordlists.

**Created by Sreeraj**

## Tool Picture

![Screenshot 2024-11-05 215208](https://github.com/user-attachments/assets/44014165-cd8f-4472-acaf-02e27bbc684c)





## Features

- **GUI** for easy use
- Supports **username and password wordlists**
- **Real-time output** of attempted combinations
- **Start and Stop** controls

## Disclaimer

**For educational and ethical use only. Unauthorized access to systems is illegal. Always obtain permission before using this tool on any server.**

## Requirements

- **Python 3.x**
- **ftplib** (included with Python)
- **tkinter** (included with Python)

## Installation

1. Clone the repository:
 
 ```bash
   git clone https://github.com/s-r-e-e-r-a-j/FTPBRUTE-TOOL.git
   ```
 ```bash
   cd FTPBrute
   ```
### Run the tool:
``` bash
python3 ftpbrute.py

 ```
## Usage

`Target IP`: Enter the FTP server IP.

`Username Wordlist`: Select a file with usernames (one per line).

`Password Wordlist`: Select a file with passwords (one per line).

`Start`: Begin brute-forcing.

`Stop`: Stop the brute force process anytime.

## Example  
```csharp
Starting brute force on 192.168.1.10...
Trying admin:password123
Trying admin:letmein
[SUCCESS] Username: admin, Password: letmein
Brute force completed.
```
## License

Open-source and free to use for ethical purposes.
