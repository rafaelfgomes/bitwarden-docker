# Bitwarden Docker

This project is a simple docker-compose file intented to install a self-hosted Bitwarden Vault service.

For more information about what is bitwarden you can click [here][Bitwarden Site].

## How to install and run

- First make a copy of the ".env.example" file and rename it to ".env";
- Fill the variable EXTERNAL_PORT in the .env file with the port number you desire. Make sure the port number you're using is not being used on another service;

After that you can run the command:

`docker-compose up -d`

If everithing runs fine you can access you self-hosted passwords vault with your machine ip (or localhost or 127.0.0.1) and the port you chosen.

Example: if I fill the port number with value `8181` I can access the service in any browser at:

- 127.0.0.1:8181 OR
- localhost:8181 OR
- YOUR_COMPUTER_IP:8181

[Bitwarden Site]: https://bitwarden.com
