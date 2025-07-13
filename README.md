# Octra Public Testnet
## Join Discord
https://discord.gg/6P5n696s
## Sent my wallet
```
oct91NwqabJq3D325wzqr3Wm7RsMpwDgfo77gRSNfWNU7xN
```
## Update CLI
### Update git:
```
cd octra_pre_client
git pull origin main
```
### Install requirements:
```
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
```
### Run CLI
```
python3 -m venv venv
source venv/bin/activate
python3 cli.py
```
***** Done!****

---
## Install dependecies
Install & Update Packages:
```
sudo apt update && sudo apt upgrade -y
```
```
sudo apt install curl git
```
```
sudo apt install unzip -y
```
```
curl -fsSL https://bun.sh/install | bash
export PATH="$HOME/.bun/bin:$PATH"
bun --version
```
---
## Create wallet
### 1. Clone the repository
   ```bash
   git clone https://github.com/ToanBm/wallet-gen.git
   cd wallet-gen
   ```

### 2. Run the wallet generator webserver
   **Linux/macOS:**
   ```bash
   chmod +x ./start.sh
   ./start.sh
   ```

### 3. Open your browser
* **WSL/Linux/MAC users:**
  * Navigate to `http://localhost:8888` on browser

* **VPS users:**
  * 1- Open a new terminal
  * 2- Install **localtunnel**:
    ```
    npm install -g localtunnel
    ```
  * 3- Get a password:
    ```
    curl https://loca.lt/mytunnelpassword
    ```
  * The password is actually your VPS IP
  * 4- Get URL
    ```
    lt --port 8888
    ```
  * Visit the prompted url, and enter your password to access wallet generator page

### 4. Generate wallet
* Click "GENERATE NEW WALLET" and watch the real-time progress
* Save all the details of your Wallet

---

## Get Faucet
* Visit [Faucet page](https://faucet.octra.network/)
* Enter your address starting with `oct...` to get faucet

-------------------------------------------------------------------------------------
## Task 1: Send transactions

**1. Install Python**
```bash
sudo apt install python3 python3-pip python3-venv python3-dev -y
```

**2. Install CLI**
```bash
git clone https://github.com/octra-labs/octra_pre_client.git
cd octra_pre_client

python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt

cp wallet.json.example wallet.json
```

**2. Add wallet to CLI**
```bash
nano wallet.json
```
* Replace following values:
  * `private-key-here`: Privatekey with `B64` format
  * `octxxxxxxxx...`: Octra address starting with `oct...`


**3. Start CLI**
```bash
python3 -m venv venv
source venv/bin/activate
python3 cli.py
```
* This should open a Testnet UI

![image](https://github.com/ToanBm/image/blob/main/octra-1.png)

**4. Send transactions**
* Send transactions to my address: `oct559HbQrZNXcZrY5k5J2JvQuybRNqG2t6xq724gKkUQg3`
* Use [Octra Explorer](https://octrascan.io/) to find more octra addresses

**5. Share Feedback**
Always share your feedback about the week's task in discord

---
## Wait for next steps
Stay tuned.

