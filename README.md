# EC2 Encryption Script

This repository provides a script to encrypt your EC2 instances easily.

## Usage

To use the script, run the following command in your terminal. Replace `kmsARN with the ARN of the KMS key you want to use to encrypt and `instanceID` with the ID of the EC2 instance you want to encrypt.

```sh
curl -s https://raw.githubusercontent.com/itarundanielgithub/enc/main/script | bash -s kmsARN instanceID

curl -s https://raw.githubusercontent.com/itarundanielgithub/enc/{branch}/script | bash -s kmsARN instanceID
