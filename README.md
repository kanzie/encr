# encr - GPG Encryption Script

`encr` is a bash script that simplifies the process of encrypting files and messages using GPG. The script supports various options, including specifying input and output files, encrypting direct messages, and running in verbose mode.

## Features

- Encrypt files or direct messages using GPG.
- Automatically adjusts the trust level of the recipient's key if necessary.
- Supports verbose mode for detailed output.
- Checks for required dependencies (`gpg` and `expect`) and provides installation instructions if they are missing.

## Requirements

- `gpg`: GNU Privacy Guard, a free implementation of the OpenPGP standard.
- `expect`: A tool for automating interactive applications.

## Installation

1. **Ensure dependencies are installed:**

   - On Debian/Ubuntu:

     ```bash
     sudo apt-get install gnupg expect
     ```

   - On macOS:

     ```bash
     brew install gnupg expect
     ```

   - On CentOS/RHEL:

     ```bash
     sudo yum install gnupg expect
     ```

2. **Clone the repository:**

   ```bash
   git clone https://github.com/kanzie/encr.git
   cd encr



## License
This project is licensed under the MIT License.

## Author
Christian Nilsson

## Contact
kanzie@gmail.com
