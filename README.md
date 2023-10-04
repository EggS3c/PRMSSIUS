# PRMSSIUS
# Password Audit Script

## Description

This Bash script is designed to audit the strength of user passwords on a Linux system and provides options for password management. It assesses password quality, identifies weak passwords, and offers recommendations for improving password security. Additionally, it allows for the creation of new users with strong passwords, resetting user passwords, and specifying the password hashing algorithm.

## Usage

To use this script, follow the instructions below:

1. Clone this repository to your Linux system.

2. Open a terminal and navigate to the script's directory.
XX
3. Run the script with the following command:


![image](https://github.com/hellowebscc/PRMSSIUS/assets/82586952/816f12e5-58d4-430e-a478-1a58066a7738)

![image](https://github.com/hellowebscc/PRMSSIUS/assets/82586952/b380ae4b-6f11-4684-9015-42d2b9fb8c0f)




./password_audit.sh [options]
Replace `[options]` with one or more of the following options:

- `-h, --help`: Display the script's help message with usage and available options.
- `-c, --create-user`: Create a new user interactively after the audit.
- `-r, --root-user`: Create a temporary user with root privileges (use with extreme caution).
- `-p, --password-reset`: Reset a user's password interactively.
- `-a, --hash-algorithm <algorithm>`: Specify the password hashing algorithm (e.g., sha256, sha512).
- `-o, --display-options`: Display selected script options at the end of the script execution.

## Examples

Here are some examples of how to use this script:

- To perform a password audit and create a new user interactively:






./password_audit.sh -p
- To specify a password hashing algorithm and display selected options:






./password_audit.sh -a sha256 -o
## Notes

- Ensure that you run the script with root privileges or using `sudo` since it accesses system files and performs administrative tasks.

- Use the script responsibly, especially when creating users with root privileges, and reset passwords only when necessary.

- The script generates an audit report saved in the `password_audit_report.txt` file.

- Modify the script to implement the actual logic for setting the password hashing algorithm as needed for your system.

Please review and understand the script's options and their implications before running it on your system. Use it to improve password security and assess the strength of user passwords on your Linux system.

**Disclaimer**: Use this script responsibly and in accordance with your system's security policies.
You can include this README section in your GitHub repository to provide clear instructions on how to use the script and its options.








