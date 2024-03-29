# cipher-magic

Create a software project that includes two main functionalities: 
1. Encrypting and decrypting text files using the Vigenère cipher. The program will be written in C/C++ and feature a graphical user interface (GUI) for ease of use. The user can select a file to encrypt with a given key, and similarly, decrypt files using the appropriate key.
2. A feature to break the Vigenère cipher through statistical analysis, aiming to recover both the original text and the key. This component will utilize the frequency of letters in the English language to perform cryptanalysis on encrypted messages without the key.

The GUI should be user-friendly, allowing users to easily navigate through encryption, decryption, and cipher-breaking functionalities. A visual representation of the statistical analysis during the cipher-breaking process would be an added advantage, providing insights into the decryption process. The software aims to be a comprehensive tool for both secure communication and educational purposes in understanding classical encryption methods.

## Collaborate with GPT Engineer

This is a [gptengineer.app](https://gptengineer.app)-synced repository 🌟🤖

Changes made via gptengineer.app will be committed to this repo.

If you clone this repo and push changes, you will have them reflected in the GPT Engineer UI.

## Setup

```sh
git clone https://github.com/GPT-Engineer-App/cipher-magic.git
cd cipher-magic
npm i
```

```sh
npm run dev
```

This will run a dev server with auto reloading and an instant preview.

## Tech stack

- [Vite](https://vitejs.dev/)
- [React](https://react.dev/)
- [Chakra UI](https://chakra-ui.com/)

## Requirements

- Node.js & npm - [install with nvm](https://github.com/nvm-sh/nvm#installing-and-updating)
