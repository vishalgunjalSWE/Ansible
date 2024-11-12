# Ansible Automation Project

This repository contains a collection of Ansible playbooks and roles for automating various configuration management tasks. The project demonstrates key Ansible features, including user management, variable handling, and file operations, designed for scalable and efficient infrastructure automation.

## Project Structure

- **create_user.yml**: Automates user creation on target systems.
- **handlers_notify.yml**: Demonstrates the use of handlers and notifications for efficient service control.
- **roles.yml**: Defines Ansible roles and provides an organized structure for reusable automation tasks.
- **vars.yml**: Contains variables for flexible configuration management.
- **write_content_to_file.yml**: Writes specified content to a file on target systems, showcasing file manipulation.
- **roles/create-user/tasks/main.yml**: Role for user management, demonstrating a modular approach to user-related tasks.

## Getting Started

1. **Install Ansible**: Ensure Ansible is installed on your system.
   ```bash
   sudo apt update
   sudo apt install ansible -y
   ```

2. **Run Playbooks**: Execute specific playbooks with the `ansible-playbook` command.
   ```bash
   ansible-playbook create_user.yml
   ```

## Key Concepts Demonstrated

- **Roles and Task Organization**: Uses roles to modularize and organize tasks, enhancing reusability.
- **Handlers and Notifications**: Implements handlers for conditional task execution, optimizing resource management.
- **Variable Management**: Centralizes variable definitions to improve scalability and customization.
- **File Operations**: Demonstrates content manipulation and file writing on remote systems.

## Requirements

- Ansible >= 2.9
- SSH access to target systems
- Sudo privileges on target systems (if required by tasks)

## Usage

Each playbook can be modified as needed by editing the respective `.yml` files. Ensure that any variables or role dependencies are updated accordingly to match your infrastructure requirements.