# Peekaboo

**Programmer**: ABOLHB  
**Language**: C#

## Overview

Peekaboo is a malicious software (virus) designed to alter the Master Boot Record (MBR) of a victim's system. Upon execution, this virus replaces the MBR with a specific image, effectively rendering the system inoperable.

## How It Works

1. **Execution**: Once the victim runs the virus, it begins by gaining necessary privileges to modify the MBR.
2. **MBR Overwrite**: The virus then overwrites the MBR with the image found at the following URL: [Image](https://i.ibb.co/J7G8fnw/IMG-1588.webp).
3. **System Disruption**: After the MBR is overwritten, the system is likely to fail to boot, displaying the overwritten image instead.

## Image Details

The image that replaces the MBR can be viewed at the following link:

![Peekaboo Image](https://i.ibb.co/J7G8fnw/IMG-1588.webp)

## Disclaimer

This project is created for **educational purposes only**. The use of this virus for malicious intent is illegal, unethical, and highly discouraged. The author, **ABOLHB**, does not endorse or condone the misuse of this software in any way. 

**IMPORTANT: The author is not responsible for any damage, loss of data, legal consequences, or any other negative impact resulting from the use or misuse of this virus.** By using this software, you agree to assume all responsibility for any consequences that may arise.

## Requirements

- C# Development Environment
- Administrator privileges on the target machine

## Usage

This virus is a proof of concept demonstrating how an MBR can be manipulated. **Use extreme caution** when executing or testing this software. It is recommended to use a virtual machine or an isolated environment to avoid unintended damage.

## Legal Notice

Distributing, using, or testing this virus without explicit permission from the owner of the target machine is **illegal** in many jurisdictions. Ensure that you have obtained all necessary permissions and are operating within the bounds of the law.

## Acknowledgements

This virus was developed by **ABOLHB** as a demonstration of MBR manipulation using the C# programming language.
