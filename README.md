# p0wny-shell: PHP-Based Single File Shell

**p0wny-shell** is a shell script written in PHP. This tool makes it easier to perform security tests on web applications and is an ideal solution for pentesting and penetration testing. However, be cautious! This tool should only be used in test environments, as it may pose security risks in production environments.

---


![p0wny Shell – PHP Based Shell](https://r00t-shell.com/wp-content/uploads/2025/02/p0wny-shell-PHP-Tabanli-Shell.png)

## Shell Login Credentials

> **Shell Login Credentials**
> 
> **Username:** `admin`  
> **Password:** `R00t`

---

## Features

- **Command History:** Use the up and down arrow keys to reuse past commands.
- **Auto-Completion:** Supports auto-completion for file and command names (with the Tab key).
- **File System Navigation:** Navigate the server using the `cd` command.
- **File Upload:** Upload files to the server.
- **File Download:** Download files from the server to your local system.

---

## Usage Instructions

### Installation and Startup

You can quickly start using Docker:

```bash
docker build -t p0wny .
docker run -it -p 8080:80 -d p0wny
