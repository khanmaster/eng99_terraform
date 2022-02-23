# Terrform
## Terraform Setup

## Installing terraform

You can download the binary from the following link:

https://www.terraform.io/downloads.html
When you have unzipped the binary file, there's no installer. They students should move the file to their /usr/local/bin directory and set the Path if necessary.


- **For Windows**
- https://chocolatey.org/install
-  We can install it using chocolatey package manager using the link below
- ```Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://community.chocolatey.org/install.ps1'))```
- Open power shell in Admin mode
- Paste the copied text into your shell and press Enter.
- Wait a few seconds for the command to complete.

- If you don't see any errors, you are ready to use Chocolatey! Type choco or choco -? now, or see Getting Started for usage instructions.

- Install Terraform `choco install terraform`
- Check installation `terraform --version`
- Powershell ENV refresh command `refreshenv`

