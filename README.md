# Gobuster
- Gobuster is a tool used for brute-forcing URIs (directories and files), DNS subdomains, and virtual host names. It is a part of the Kali Linux distribution and can be easily installed using the package manager.
    Example:
  ```bash
  gobuster dir -u http://example.com -w /usr/share/wordlists/dirbuster/directory-list-2.3-medium.txt
  ```
  This command will scan the target URL `http://example.com` using the specified wordlist for directories and files.


  ### Installation
  Here's how to install Gobuster in Kali Linux:
  
  1. Open the terminal and update the package list:
  ```bash
  sudo apt update
  ```
  2. Install Gobuster:
  ```bash
  sudo apt install gobuster
  ```
  3. Verify the installation:
  ```bash
  gobuster -h
  ```
  This command should display the help message of Gobuster if the installation was successful.

  ### Usage
  
  Gobuster can be used to brute-force directories and files on a web server by providing a wordlist and target URL. Here's an example command to use Gobuster:
  ```bash
  gobuster dir -u <target_url> -w <wordlist_file>
  ```
  Replace `<target_url>` with the URL you want to scan and `<wordlist_file>` with the path to the wordlist file containing the directories and files to be brute-forced.
  Gobuster supports various options and can be customized to fit specific requirements. It is a powerful tool for web reconnaissance and can be used for targeted attacks or as part of a larger security assessment.
