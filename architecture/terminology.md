# Terminology

### **Wallet**

This is the user's EOA, the user wallet holding the user's funds. For reference think of this as some prominent wallet provider, e.g. _Coinbase Wallet, MetaMask Wallet or Hardware Wallet_.

### **Signer**

This is the user's _device specific private key_. It is automatically generated to sign authentication related messages and control the user's smart contract wallet.

### **Player**

This is the user's _delegated smart contract wallet_ used for gas sponsorship. This account is explicitly authorized to act on behalf of the user and thus represents the user onchain.

### Guardian

This is the _trusted streaming server_ providing all reconciled game state in real time. It competes with other guardians for market share on the basis of latency and fairness.

### Registry

This is the trustless smart contract used for kill state transparency and user balance management. The mandatory reporting of kill state enforces _game theoretical credible neutrality_.
