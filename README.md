{
  "name": "root",
  "private": true,
  "scripts": {
  "bootstrap": "lerna bootstrap",
  "test": "lerna run test:ci",
  "clean": "lerna clean",
  "clean:build": "lerna exec -- rimraf lib",
  "release": "lerna publish",
  "ls": "lerna ls"
},
  "devDependencies": {
    "lerna": "^3.22.1"
  }
}

# How to pushed @mg package from packages
- pnpm/npm/yarn bootstrap It's need to push the package from packages
