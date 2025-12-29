# Ansible-Practice

This repository includes Ansible playbook examples for practicing common automation tasks.

## 📌 Tasks

* [Task 1: Install httpd package on app01, app02, and app03](./task01)
* [Task 2: Install apache package on app01, app02, and app03](./task02/)
* [Task 3: start and enable httpd service on app01, app02, and app03](./task03/)
* [Task 4: Copy Data to App Servers using Ansible](./task04/)
* [Task 5: create folder, file and set ACL using Ansible](./task05/)
* [Task 6: Ansible Lineinfile Module](./task06/)
* [Task 6: Ansible conditionals use of when:](./task07/)
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
   cd task1
   ```

3. Run the playbook:

   ```bash
   ansible-playbook -i inventory playbook.yml
   ```
