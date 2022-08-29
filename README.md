# scala-cli-bloop-sbt-crypto-aes-password-salt

## Description
A demo for AES encryption of a password.
AES is a 256 byte encryption. SALT is the
mixing of the original text with a secret key.
It is considered more secure to store the
SALT then the encrypted original text, however
this can still be cracked with rainbow tables.

Compiled and ran from build server `bloop`.

# Build note
Dependencies must be compatable with jdk8 or less.

## Tech stack
- bloop
- scala
- bloop-sbt

## Docker stack
- openjdk:8-jdk-alpine

## To run
`sudo ./install.sh -u`

## To stop (optional)
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`

## Credits
https://www.baeldung.com/java-aes-encryption-decryption
