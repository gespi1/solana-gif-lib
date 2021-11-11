# buildspace Solana GIF Portal Project

### **Welcome 👋**
To get started, clone this repo and follow these commands:

1. Run `npm install` at the root of your directory
2. Run `npm run start` to start the project
3. Install mocha 


### **Versions**
`node`: v16.13.0

`npm`: v8.1.0

`rustup`: 1.24.3

`rustc`: 1.56.1

`cargo`: 1.56.0

`solana cli`: 1.8.3

`anchor`: 0.18.0


### **Create Local Solana Network and Start Validator**
```
solana config set --url localhost
solana config get
solana-test-validator
```

### **Get on Solana Devnet**
```
solana config set --url devnet

// Make sure you're on devnet.
solana config get

anchor build

// Get the new program id.
solana address -k target/deploy/myepicproject-keypair.json

// Update Anchor.toml and lib.rs w/ new program id.
// Make sure Anchor.toml is on devnet.

// Build again.
anchor build

// Finally deploy
anchor deploy
```

### **Install Anchor**
[Ubuntu install](https://project-serum.github.io/anchor/getting-started/installation.html#install-anchor)


### **Questions?**
Have some questions make sure you head over to your [buildspace Dashboard](https://app.buildspace.so/courses/CObd6d35ce-3394-4bd8-977e-cbee82ae07a3) and link your Discord account so you can get access to helpful channels and your instructor!
