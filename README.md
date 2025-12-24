# Ansible-Practice

This repository includes Ansible playbook examples for practicing common automation tasks.

## 📌 Tasks

* [Task 1: Install httpd package on app01, app02, and app03](./task01)
* [Task 2: Install apache package on app01, app02, and app03](./task02/)

## 📁 Repository Structure

```
Ansible-Practice/
├── README.md
├── task-1-install-httpd/
│   ├── inventory
│   └── playbook.yml
└── task-2-install-apache/
    ├── inventory
    └── playbook.yml
```

Each task folder contains:

* An inventory file with the target hosts.
* A playbook to install and configure the required package.

## 🚀 How to Use

1. Clone the repository:

   ```bash
   git clone <your-repo-url>
   cd Ansible-Practice
   ```

2. Navigate to a task folder:

   ```bash
   cd task-1-install-httpd
   ```

3. Run the playbook:

   ```bash
   ansible-playbook -i inventory playbook.yml
   ```
