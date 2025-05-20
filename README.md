HOW TO DOWNLOAD IPFS
🔹 Step 1: Go to the official website Visit: https://docs.ipfs.tech/install/ipfs-desktop/

🔹 Step 2: Download IPFS Desktop Choose the right version for your operating system:

Windows .exe

🔹 Step 3: Install it Windows: Run the .exe and follow the installer.

🔹 Step 4: Run IPFS Desktop Open the app — it will start the IPFS daemon and give you a friendly GUI to interact with your node.

Windows: Add the ipfs.exe directory to your system's PATH environment variable.

Desktop: Open the app, it should show your peer ID and connected nodes.
![Screenshot 2025-05-20 171447](https://github.com/user-attachments/assets/7e736319-2e8f-4141-b60d-0d8ced5a88b2)
FILE UPLOADING
I clicked on the file selection in IPFS desktop.

Then i selected the option "import" and uploaded a pdf file and audio and a admit card file and also a image.

Once the file was uploaded, IPFS generate a unique CID(content indentifier) for the file
![Screenshot 2025-05-20 171554](https://github.com/user-attachments/assets/48dcfc7a-893d-4733-b336-f19d5c1d7268)
Encrypting and decrypting
Download IPFS CLI:
wget https://dist.ipfs.tech/go-ipfs/v0.22.0/go-ipfs_v0.22.0_linux-amd64.tar.gz
Extract the tar file:
tar -xvzf go-ipfs_v0.22.0_linux-amd64.tar.gz
Install IPFS:
cd go-ipfs
./install.sh
Initialize IPFS Node:
~/.local/bin/ipfs init
Start IPFS Daemon:
~/.local/bin/ipfs daemon
Create a sample file:
echo "hello, IPFS!" > hello.txt
Add original file to IPFS:
~/.local/bin/ipfs add hello.txt
Encrypt the file using OpenSSL:
openssl enc -aes-256-cbc -pbkdf2 -iter 100000 -salt -in hello.txt -out hello.enc
Upload the encrypted file to IPFS:
~/.local/bin/ipfs add hello.enc
Decrypt the file:
openssl enc -d -aes-256-cbc -pbkdf2 -iter 100000 -in retrieved.enc -out decrypted.txt
See decrypted content:
cat decrypted.txt
Add decrypted file to IPFS:
~/.local/bin/ipfs add decrypted.txt!
[Screenshot 2025-05-20 171703](https://github.com/user-attachments/assets/49e906df-1ec7-4c96-b59d-648998a50259)
BLOCKCHAIN PRACTICAL METAMASK WALLLET
#CREATE METAMASK WALLET (Sepolia testnet) #introduction This is a practical task demonstrate how to create a Metamask wallet and perform a trasaction using the sepolia Testnet

Transtion detail
Network: sepolia testent amount sent: 0.02ETH Transaction hash: 0x7a95585dd38725214ee4c0b74dac13d8a39a410555b40bea68cf929b5ff629f1

Getting sepolia ETH from Faucet
1.Visited the google cloud Sepolia Faucet.

2.Logged in with my google account.

3.Entered my Metamask wallet address.

4.Clicked on "Request 0.02 ETH".

5.ETH was sent to my wallet within a few seconds.

6.Verified the transaction on sepolia Etherscan.
![Screenshot 2025-05-20 171816](https://github.com/user-attachments/assets/f3dbb180-2499-45b4-9f6c-4bb02c4c4e8c)
steps followed
1.Connected Metamask to Sepolia Testnet.

2.Claimed Sepolia ETH from faucet.

3.Sent ETH to another Address.

4.Verified transaction was confirmed.
![Screenshot 2025-05-20 171856](https://github.com/user-attachments/assets/851d7547-b4e5-468e-9fa6-c9751835d553)



