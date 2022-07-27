# Solutions to common problems in local blockchain development environment

This repository lists common problem and how did I solve it, so that others with similar problem dont have to waste their tons of hours.


# Hardhat installed but doesn't launch
## Problem looked something like this 

```
 npx hardhat 
npm WARN config global `--global`, `--local` are deprecated. Use `--location=global` instead.
An unexpected error occurred:

Error: Cannot find module '@nomicfoundation/hardhat-toolbox'
Require stack:
- C:\Users\ankit\hardhat.config.js
- C:\Users\ankit\Desktop\Blockchain\wavePortal\node_modules\hardhat\internal\core\config\config-loading.js
- C:\Users\ankit\Desktop\Blockchain\wavePortal\node_modules\hardhat\internal\cli\cli.js
    at Function.Module._resolveFilename (node:internal/modules/cjs/loader:933:15)
    at Function.Module._load (node:internal/modules/cjs/loader:778:27)
    at Module.require (node:internal/modules/cjs/loader:1005:19)
    at require (node:internal/modules/cjs/helpers:102:18)
    at Object.<anonymous> (C:\Users\ankit\hardhat.config.js:1:1)
    at Module._compile (node:internal/modules/cjs/loader:1105:14)
    at Object.Module._extensions..js (node:internal/modules/cjs/loader:1159:10)
    at Module.load (node:internal/modules/cjs/loader:981:32)
    at Function.Module._load (node:internal/modules/cjs/loader:822:12)
    at Module.require (node:internal/modules/cjs/loader:1005:19) {
  code: 'MODULE_NOT_FOUND',
  requireStack: [
    'C:\\Users\\ankit\\hardhat.config.js',
    'C:\\Users\\ankit\\Desktop\\Blockchain\\wavePortal\\node_modules\\hardhat\\internal\\core\\config\\config-loading.js',
    'C:\\Users\\ankit\\Desktop\\Blockchain\\wavePortal\\node_modules\\hardhat\\internal\\cli\\cli.js'
  ]
}
```

## Solution 

Delete the hardhat.config.js file from your user directory and rerun.
Remove the
