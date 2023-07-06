# Shell Permissions

## Overview
This repository contains a collection of Bash scripts developed by Peter Pierre Nzioki, also known as Exoespada, for the ALX Software Engineering training program. These scripts focus on the topic of shell permissions in a Linux environment. They provide practical examples and exercises to help participants understand and practice concepts related to permissions, ownership, and administrative privileges.

## Learning Objectives
By working with these scripts, participants will be able to grasp the following concepts without relying on external resources:

- Understanding permissions in a Linux shell
- Familiarity with commands such as `chmod`, `sudo`, `su`, `chown`, and `chgrp`
- Explaining Linux file permissions
- Representing the three sets of permissions (owner, group, and other) as a single digit
- Modifying permissions, owner, and group of a file or directory
- Understanding the limitations of a normal user in changing file ownership (`chown`)
- Executing commands with root privileges
- Changing user ID or gaining superuser access

## Scripts
The following scripts are included in this repository:

1. **change_permissions.sh**: Demonstrates how to modify the permissions of a file or directory using the `chmod` command. It provides examples of changing permissions for the owner, group, and other users.

2. **change_owner.sh**: Illustrates the process of changing the owner of a file or directory using the `chown` command. It explains the limitations of a normal user in changing ownership and highlights scenarios where administrative privileges may be required.

3. **change_group.sh**: Shows how to change the group ownership of a file or directory using the `chgrp` command. It emphasizes the importance of group permissions and their impact on file access.

4. **run_with_root_privileges.sh**: Outlines different methods to execute a command with root privileges. It covers the usage of `sudo`, `su`, and other relevant techniques for performing administrative tasks.

5. **change_user_id.sh**: Demonstrates how to change the user ID (UID) or switch to the superuser account using appropriate commands. It provides insights into the implications and precautions associated with changing user IDs.

## Getting Started
To run these scripts on your local machine, follow these steps:

1. Clone this repository: `git clone https://github.com/exoespada/shell-permissions.git`
2. Navigate to the repository's directory: `cd shell-permissions`
3. Make the scripts executable: `chmod +x *.sh`
4. Execute any desired script using Bash: `./script_name.sh`

Please ensure that you have appropriate permissions to execute the scripts and modify files in the relevant directories.

## Contribution
If you wish to contribute to this project or have any suggestions, feel free to open an issue or submit a pull request. Your contributions are highly appreciated!

## Acknowledgements
Special thanks to the ALX team for putting together the ALX Software Engineering training program and providing valuable resources and guidance throughout the course. Their support and dedication are greatly appreciated.

## License
This project is licensed under the [MIT License](LICENSE). You are free to modify, distribute, and use the scripts as per the terms and conditions of the license.
