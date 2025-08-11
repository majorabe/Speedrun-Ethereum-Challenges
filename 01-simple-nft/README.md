# 🎟 Challenge 0: Simple NFT Example

## Resumen
Este desafío consiste en **crear y desplegar un contrato inteligente para un NFT** usando **Scaffold-ETH**.  
Te animo hacerlo! Aprenderás a compilar y desplegar contratos con **HardHat**, interactuar desde un **frontend React** con hooks y componentes web3, y finalmente publicar tu aplicación para que otros puedan comprar y transferir NFTs.

### Pasos principales:
1. **Instalación y entorno local**  
   - Clona el repositorio y ejecuta:
     ```bash
     yarn chain        # Blockchain local
     yarn start        # Frontend
     yarn deploy       # Despliegue de contrato local
     ```
   - Abre `http://localhost:3000`.

2. **Uso de burner wallets**  
   - Prueba la dApp con billeteras temporales (incógnito).
   - Envía fondos de prueba desde el faucet.

3. **Mint y transferencia de NFTs**  
   - Usa el botón `MINT NFT` para crear tokens.
   - Transfiérelos a otra dirección (por ejemplo, desde incógnito).

4. **Despliegue a testnet**  
   - Cambia `defaultNetwork` a `sepolia`.
   - Genera una cuenta de despliegue:
     ```bash
     yarn generate
     yarn account
     yarn deploy --network sepolia
     ```
   - Consigue ETH de faucet y prueba en red pública.

5. **Publicación del frontend**  
   - Cambia `targetNetwork` a `sepolia`.
   - Publica con:
     ```bash
     yarn build
     yarn vercel
     ```
   
6. **Verificación del contrato**  
   - Ejecuta:
     ```bash
     yarn verify --network sepolia
     ```

**Entrega final:**  
Un enlace público a tu dApp donde se puedan comprar y transferir NFTs.  

📌 Más detalles aquí → [Challenge 0 – Simple NFT Example](https://speedrunethereum.com/challenge/simple-nft-example)

---

## Summary 
This challenge is about **creating and deploying an NFT smart contract** using **Scaffold-ETH**.  
You will compile and deploy contracts with **HardHat**, interact from a **React frontend** with web3 components and hooks, and finally publish your app so others can buy and transfer NFTs.

### Main Steps:
1. **Local setup**
   ```bash
   yarn chain    # Local blockchain
   yarn start    # Frontend
   yarn deploy   # Deploy local contract
   ```
   - Open `http://localhost:3000`.

2. **Burner wallets**  
   - Test with temporary wallets (incognito).
   - Fund them from faucet.

3. **Mint & transfer NFTs**  
   - Click `MINT NFT` to create tokens.
   - Transfer to another address.

4. **Deploy to testnet**
   ```bash
   yarn generate
   yarn account
   yarn deploy --network sepolia
   ```
   - Fund deployer account with test ETH.

5. **Publish frontend**
   ```bash
   yarn build
   yarn vercel
   ```

6. **Verify contract**
   ```bash
   yarn verify --network sepolia
   ```

**Final Deliverable:**  
A public link to your NFT dApp.  

📌 Full guide here → [Challenge 0 – Simple NFT Example](https://speedrunethereum.com/challenge/simple-nft-example)
