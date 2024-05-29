# AES Encryption and Decryption Using CryptoJS

This project demonstrates how to use CryptoJS for AES encryption and decryption in a simple HTML and JavaScript application. It includes a form for encrypting and decrypting text using a passphrase.

## Features

- Encrypt plaintext to ciphertext using AES encryption.
- Decrypt ciphertext back to plaintext using the same passphrase.
- Simple and intuitive UI using Bootstrap for styling.

## Getting Started

### Prerequisites

You need a modern web browser to run this project. No additional software is required.

### Installation

1. Clone the repository:

    ```sh
    git clone https://github.com/aravind-govindhasamy/simple-aes-encrypt-decrypt-cryptojs.git
    ```

2. Navigate to the project directory:

    ```sh
    cd aes-encryption-decryption
    ```

3. Open the `index.html` file in your web browser:

    ```sh
    open index.html
    ```

    Alternatively, you can double-click the `index.html` file to open it in your default web browser.

## Usage

1. **Encrypt Text:**
   - Enter the text you want to encrypt in the "Plaintext" textarea.
   - Enter a passphrase in the "Passphrase" input field.
   - Click the "Encrypt" button.
   - The encrypted ciphertext will appear in the "Ciphertext" input field.

2. **Decrypt Text:**
   - Enter the ciphertext you want to decrypt in the "Ciphertext" input field.
   - Enter the same passphrase used for encryption in the "Passphrase" input field.
   - Click the "Decrypt" button.
   - The decrypted plaintext will appear in the "Plaintext" textarea.

## Project Structure


## Dependencies

- [Bootstrap 3.4.1](https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/css/bootstrap.min.css) - for styling.
- [jQuery 3.6.0](https://ajax.googleapis.com/ajax/libs/jquery/3.6.0/jquery.min.js) - for simplicity.
- [CryptoJS 4.1.1](https://cdnjs.cloudflare.com/ajax/libs/crypto-js/4.1.1/crypto-js.min.js) - for encryption and decryption.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contributing

1. Fork the repository.
2. Create your feature branch (`git checkout -b feature/awesome-feature`).
3. Commit your changes (`git commit -m 'Add some awesome feature'`).
4. Push to the branch (`git push origin feature/awesome-feature`).
5. Open a pull request.

## Acknowledgments

- [CryptoJS](https://crypto-js.googlecode.com/svn/tags/3.1.2/doc/) for providing a robust library for encryption and decryption.
- [Bootstrap](https://getbootstrap.com/) for the responsive UI components.
- [jQuery](https://jquery.com/) for simplifying JavaScript operations.
