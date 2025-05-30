# randecepter

### Notable Ransomware Behaviors
Ransomware is a malicious type of malware designed to encrypt files or lock systems, demanding a ransom for data restoration. Understanding the key behaviors of ransomware is critical for developing effective defense strategies. Below are some of the pivotal characteristics exhibited by ransomware:

- **File Search and Listing**  
  Ransomware searches for victim files using extension filters, targeting valuable or sensitive data to maximize impact and increase the likelihood of ransom payment.

- **Encryption Key and ID Generation**  
  Generates a robust encryption key and a unique victim ID to link encrypted files to the victim. The victim ID is typically created from system data and cryptographic functions, ensuring the correct decryption key is matched after payment.

- **File System Encryption**  
  Encrypts various file types, rendering them inaccessible without the corresponding decryption key. This is the primary mechanism used to compel victims to pay the ransom.

- **Command & Control (C&C) Server Communication**  
  Communicates with attacker-controlled C&C servers for updates, retrieval of the decryption key, and potential data exfiltration, allowing the attacker to maintain control and monitor the infection.

- **Ransom Notes and Instructions**  
  After encryption, ransomware generates ransom notes with instructions for victims. These notes, often displayed as text files or desktop backgrounds, provide details such as the ransom amount, cryptocurrency payment instructions, and deadlines to pressure victims into paying.



### A detailed representation of TABLE I
  
![image](https://github.com/user-attachments/assets/d110098b-d983-45d1-b02f-e17bf5c5c3b0)



### A detailed representation of TABLE IV (b)
| Application           | CF | ENC | FD | RN | Time (No System) | Time (With System) |
| --------------------- | -- | --- | -- | -- | ---------------- | ------------------ |
| Notepad               | X  | X   | X  | X  | 5.13s            | 5.20s (1.28%)      |
| Calculator            | X  | X   | X  | X  | 8.23s            | 8.35s (1.49%)      |
| MS Word               | X  | X   | X  | X  | 3.28s            | 3.29s (0.40%)      |
| MS PowerPoint         | X  | X   | X  | X  | 5.66s            | 5.69s (0.46%)      |
| Mozilla Firefox       | X  | ✓   | ✓  | X  | 12.39s           | 13.31s (7.44%)     |
| Zoom                  | X  | ✓   | X  | X  | 6.23s            | 6.26s (0.56%)      |
| 7zip                  | X  | ✓   | ✓  | X  | 32.7s            | 35.88s (9.73%)     |
| WinSCP                | X  | ✓   | ✓  | X  | 25.9s            | 27.61s (6.61%)     |
| Veracrypt             | X  | ✓   | X  | X  | 5.3s             | 5.46s (3.05%)      |
| 1Password             | X  | ✓   | X  | X  | 12.25s           | 12.32s (0.57%)     |
| MySQL Workbench       | X  | ✓   | X  | X  | 29.58s           | 31.26s (5.69%)     |
| OpenVPN               | X  | ✓   | X  | X  | 3.59s            | 3.66s (1.83%)      |
| Google Chrome         | X  | ✓   | X  | X  | 10.03s           | 10.20s (1.74%)     |
| Microsoft Edge        | X  | ✓   | X  | X  | 9.11s            | 9.29s (1.97%)      |
| Dropbox               | X  | ✓   | ✓  | X  | 13.17s           | 13.65s (3.65%)     |
| OneDrive              | X  | ✓   | ✓  | X  | 20.24s           | 20.95s (3.50%)     |
| Slack                 | X  | ✓   | X  | X  | 14.06s           | 14.30s (1.71%)     |
| Microsoft Teams       | X  | ✓   | X  | X  | 16.15s           | 16.81s (4.06%)     |
| Skype                 | X  | ✓   | ✓  | X  | 12.07s           | 12.26s (1.59%)     |
| Adobe Acrobat         | X  | X   | ✓  | X  | 19.34s           | 19.95s (3.14%)     |
| Adobe Photoshop       | X  | X   | ✓  | X  | 40.68s           | 42.46s (4.37%)     |
| Sublime Text          | X  | X   | ✓  | X  | 15.12s           | 15.67s (3.64%)     |
| Atom                  | X  | ✓   | X  | X  | 18.04s           | 18.75s (3.92%)     |
| Git                   | X  | ✓   | ✓  | X  | 11.32s           | 11.81s (4.32%)     |
| GitHub Desktop        | X  | ✓   | ✓  | X  | 12.11s           | 12.53s (3.46%)     |
| Putty                 | X  | ✓   | ✓  | X  | 13.28s           | 13.83s (4.15%)     |
| KeePass               | X  | ✓   | ✓  | X  | 8.18s            | 8.47s (3.53%)      |
| xplorer2              | X  | ✓   | X  | X  | 14.22s           | 14.80s (4.07%)     |
| Foxit PDF Reader      | X  | X   | X  | X  | 18.19s           | 18.99s (4.40%)     |
| Opera                 | X  | ✓   | ✓  | X  | 15.39s           | 16.28s (5.79%)     |
| Calibre               | X  | X   | X  | X  | 22.38s           | 23.46s (4.80%)     |
| Vivaldi               | X  | ✓   | X  | X  | 10.05s           | 10.27s (2.22%)     |
| KMPlayer              | X  | ✓   | X  | X  | 13.47s           | 13.96s (3.63%)     |
| CCleaner Professional | X  | ✓   | ✓  | X  | 14.03s           | 14.59s (4.02%)     |
| FastStone             | X  | ✓   | X  | X  | 11.21s           | 11.64s (3.82%)     |
| PhotoFiltre           | X  | X   | X  | X  | 16.18s           | 16.80s (3.84%)     |
| WinRAR                | X  | ✓   | ✓  | X  | 13.14s           | 13.80s (4.99%)     |
| TeamViewer            | X  | ✓   | X  | X  | 19.32s           | 19.94s (3.19%)     |
| IrfanView             | X  | X   | ✓  | X  | 14.45s           | 14.99s (3.72%)     |
| Total Commander       | X  | ✓   | X  | X  | 15.77s           | 16.36s (3.74%)     |
| WinSnap               | X  | X   | ✓  | X  | 10.12s           | 10.56s (4.36%)     |
| VLC media player      | X  | ✓   | X  | X  | 15.36s           | 16.03s (4.36%)     |
| JDownloader           | X  | X   | ✓  | X  | 19.24s           | 20.06s (4.25%)     |
| Picasa                | X  | X   | ✓  | X  | 20.32s           | 21.30s (4.82%)     |
| Unlocker              | X  | ✓   | X  | X  | 9.29s            | 9.48s (2.05%)      |
