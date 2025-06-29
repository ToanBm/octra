# Octra Public Testnet

## Join Discord
https://discord.gg/octra

---

## Install dependecies
Install & Update Packages:
```
sudo apt update && sudo apt upgrade -y
sudo apt install curl git
```
Install Nodejs (Only VPS users)
```
sudo apt update
sudo curl -fsSL https://deb.nodesource.com/setup_22.x | sudo -E bash -
sudo apt install -y nodejs
node -v
npm install -g yarn
yarn -v
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

---

## Wait for next steps
Public testnet is soon to be launched. Stay tuned.

