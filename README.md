
# NRF Workflow Essentials

    Effortless Control, Professional Results

    This repository provides a collection of reusable Ansible playbooks for system checks, settings, and updates across various platforms (Linux - RedHat, Ubuntu, and Windows). Each directory is organized by function (`check`, `set`, and `update`) and by operating system.

## Repository Structure

NRF_WORKFLOW_ESSENTIALS/
├── check/
│   ├── linux/
│   │   ├── redhat/
│   │   │   └── services.yml         # Playbook to check services on RedHat
│   │   ├── ubuntu/
│   │   │   └── services.yml         # Playbook to check services on Ubuntu
│   ├── windows/
│   │   └── services.yml             # Playbook to check services on Windows
│
├── set/
│   ├── linux/
│   │   ├── redhat/
│   │   │   └── services.yml         # Playbook to set up services on RedHat
│   │   ├── ubuntu/
│   │   │   └── services.yml         # Playbook to set up services on Ubuntu
│   ├── windows/
│   │   └── services.yml             # Playbook to set up services on Windows
│
├── update/
│   ├── linux/
│   │   ├── redhat/
│   │   │   └── services.yml         # Playbook to update services on RedHat
│   │   ├── ubuntu/
│   │   │   └── services.yml         # Playbook to update services on Ubuntu
│   ├── windows/
│   │   └── services.yml             # Playbook to update services on Windows
│
├── LICENSE                          # License information for the repository
└── README.md                        # Overview and usage instructions for the repository
