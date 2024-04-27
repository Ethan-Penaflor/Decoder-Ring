# Decoder Ring

Welcome to the Decoder Ring project!

## Description

Decoder Ring is a simple tool that allows you to encode and decode messages using various ciphers. With Decoder Ring, you can encrypt your messages to keep them secure or decrypt encoded messages to reveal their original content.

## Features

- **Three Ciphers**: Decoder Ring currently supports three ciphers:
  - Caesar Cipher
  - Substitution Cipher
  - Polybius Square Cipher

- **Encode and Decode**: You can both encode and decode messages using each cipher.

- **Customizable Settings**: Customize the encryption or decryption process with optional parameters specific to each cipher.

## Installation

To use Decoder Ring, follow these steps:

1. Clone this repository to your local machine using the following command:
`git clone https://github.com/Ethan-Penaflor/Decoder-Ring.git`


2. Navigate to the project directory:
`cd Decoder-Ring`


3. Install the necessary dependencies:
`npm install`


4. You're ready to start using Decoder Ring!

## Usage

To use Decoder Ring, run the following command in your terminal:

`node index.js`


Follow the on-screen prompts to choose a cipher, enter your message, and specify any additional settings.

## Examples

Here are some examples of how to use Decoder Ring:

- **Encrypt a Message with Caesar Cipher:**

`node index.js`
Choose a cipher: Caesar
Enter your message: Hello, world!
Enter the shift value (default: 3): 5
Encrypted message: Mjqqt, btwqi!


- **Decrypt a Message with Substitution Cipher:**

`node index.js`
Choose a cipher: Substitution
Enter your message: Dohd, qgbdq!
Enter the alphabet key (default: abcdefghijklmnopqrstuvwxyz): pqrstuvwxyzabcdefghijklmno
Decrypted message: Hello, world!

## Contributing

Contributions are welcome! If you have suggestions for new features or improvements, please open an issue or submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.