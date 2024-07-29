# Swisstronik Tesnet Techinal Task 6 (Deploy Proxy)

link : [Click!](https://www.swisstronik.com/testnet2/dashboard)

Feel free donate to my EVM address

EVM :

```bash
0x6f5c1bEB0Ae14D1422B4B3b874ac6D3d225f9940
```

## Steps

### 1. Clone Repository

```bash
git clone https://github.com/gadroen/swisstronik-deploy-proxy.git
```

```bash
cd swisstronik-deploy-proxy
```

### 2. Install Dependency

```bash
npm install
```

### 3. Set .env File

create .env file in root project

```bash
touch .env
```

add this to your .env file

```bash
PRIVATE_KEY="your private key"
```

### 4. Compile Smart Contract

```bash
npm run compile
```

### 5. Deploy Smart Contract

```bash
npm run deploy
```

### 6. Initialize Owner

```bash
npm run initialize
```

### 7. Add Issuer

```bash
npm run add-issuers
```

### 8. Get Issuers list

```bash
npm run list-issuers
```

### 9. Upgrade Smart Contract

```bash
npm run upgrade
```

### 10. Finsihed

- Open the deployed-adddress.ts file (location in utils folder)
- Select SWTRProxy
- Copy the address and paste the address into testnet dashboard(Point1)
- Open address-with-explorer.txt file (location in utils folder)
- Copy the address explorer and paste the address into testnet dashboard(Point2)
- Open tx-hash.txt file (location in utils folder)
- Copy the transaction hash link and paste the address into testnet dashboard(Point3)
- No need push to github

by :
github : [gadroen](https://github.com/gadroen)
telegram : @EwinGadroen
//0x6f5c1bEB0Ae14D1422B4B3b874ac6D3d225f9940

Ignore this!!!

```
SWTRProxy = '0x4c60E9c00C119AF7B043Db4C6DfdAED4a174b4e7'
ProxyAdmin = '0x6Ac57d7DF299AC5D05f66C24F47A4aF1CEBB2Ca9'
SWTRImplementation = '0x31fC89276b2748767c3966D02404a96fE5c9BDe8'
```
