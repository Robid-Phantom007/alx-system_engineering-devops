# Web server
Project that aims to learn about the roles of web servers and their processes (parent and child), and DNS roles.

## General :house:
* What is the main role of a web server
* What is a child process
* Why web servers usually have a parent process and child processes
* What are the main HTTP requests
* What DNS stands for
* What is DNS main role

## Requirements :page_with_curl:
* Allowed editors: vi, vim, emacs
* All your files will be interpreted on Ubuntu 16.04 LTS
* All your files should end with a new line
* A README.md file, at the root of the folder of the project, is mandatory
* All your Bash script files must be executable
* Your Bash script must pass Shellcheck (version 0.3.7) without any error
* The first line of all your Bash scripts should be exactly #!/usr/bin/env bash
* The second line of all your Bash scripts should be a comment explaining what is the script doing
*  You can’t use systemctl for restarting a process

## Tasks :heavy_check_mark:

| Filename | Description |
| -------- | ----------- |
| `0-transfer_file` | Transfers a file from our client to a server |
| `1-install_nginx_web_server` | Configures an Ubuntu machine to install NGINX web server |
| `2-setup_a_domain_name` | Contains the domain name server of a created web site |
| `3-redirection` | Configures an Ubuntu machine to make a redirection |
| `4-not_found_page_404` | Configures a Ubuntu machine to have a custom 404 page |
| `7-puppet_install_nginx_web_server.pp` | Configures a Ubuntu machine to make a redirection and a custom 404 page |
