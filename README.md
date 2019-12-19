# bitconnectX Genesis BlockChain BootStrap

Chain-data files for [BCCX / BitConnect X / bitconnectX Genesis blockchain](https://chainz.cryptoid.info/bccx/ "BCCX BlockChain"). Using these files reduces time in finding peers and/or syncing the [BCCX / BitConnect X / bitconnectX Genesis blockchain](https://chainz.cryptoid.info/bccx/ "BCCX BlockChain").

General bitconnectX BlockChain Node Tutorials: [New](https://youtu.be/RTieeNXGNrE "New Wallet Tutorial") | [Old](https://youtu.be/OFPNmYAQYdw "Old Wallet Tutorial") *(same principles for BCCX)*

BlockChain Node: [bitconnectX GitHub](https://github.com/bitconnectcoin/bitconnectx/tree/master/wallet "bitconnectX GitHub")

---

**If You Have Ran The bitconnectX BlockChain On Your Device:**

**1.** [Download the latest bootstrap files.](https://github.com/bitconnectCore/bitconnectX-Genesis-blockchain-bootstrap/releases "The Latest BCCX Bootstrap Files Release")

**2.** Find the downloaded bitconnectx.zip file and double-click. This will unzip the file and show a folder named bitconnectx.

**3.** Close and quit the bitconnectX Genesis blockchain user-interface, (if it is running).

**4.** Navigate to your OS's respective data directory.

* For Windows: C:\Users\[YourUsername]\AppData\Roaming\bitconnectx\
Or paste %appdata%\Roaming\bitconnectx\ into the file explorer path field
* For MacOS: ~/Library/Application Support/bitconnectx/
Open Finder and in the program menu select Go > To Folder and enter the above path.
* For Linux: ~/.bitconnectx/

**5.** Remove all files and folders **except** for wallet.dat, bitconnectx.conf (may not have this file).
**Do not** delete the wallet.dat file as it contains the private keys for your X. **Deleting this file will result in loss of X!**

**6.** Inside the downloaded bitconnectx folder there is **one** folder and **three** files. Move all **four** items into the bitconnectX Genesis node's data directory that you just removed files from.

* **txleveldb**   - File Folder
* **blk0001.dat** - DAT File
* **peers.dat** - DAT File
* **bitconnectx**  - CONF File

**7.** Run the wallet and syncing should begin at the bootstrap's last block.

---

**If You Have Not Ran The bitconnectX Genesis BlockChain On Your Device:**

**1.** [Download the latest bootstrap files.](https://github.com/bitconnectCore/bitconnectX-Genesis-blockchain-bootstrap/releases "The Latest BCCX Bootstrap Files Release")

**2.** Find the downloaded bitconnectx.zip file and double-click. This will unzip the file and show a folder named bitconnectx.

**3.** Move the bitconnectx folder to your OS's respective data directory.

* For Windows: C:\Users\[YourUsername]\AppData\Roaming\
Or paste %appdata%\Roaming\ into the file explorer path field.
* For MacOS: ~/Library/Application Support/
Open Finder and in the program menu select Go > To Folder and enter the above path.
* For Linux: ~/
     
    *For Linux you must rename the bitconnectx folder to .bitconnectx*

**4.** Run the wallet and syncing should begin at the bootstrap's last block.

---

![alt text](https://static.wixstatic.com/media/28f073_b193ddc57217466fa9f29fb256bd43e7~mv2.png/v1/fill/w_1046,h_1049/WaveX.PNG.png "WaveX")
