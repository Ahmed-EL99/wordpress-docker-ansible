# WordPress + MySQL Deployment with Docker & Ansible 🐳🧰

This project demonstrates how to deploy a WordPress site along with a MySQL database using Docker containers, automated entirely with Ansible.

## 🔧 Tools Used
- Docker
- Ansible
- Linux (Ubuntu 20.04)

## 📁 Project Structure
ansible/

├── wordpressdeploy.yml

├── hosts.ini


## 🚀 What It Does
- Creates a Docker network
- Spins up a MySQL container with preconfigured environment variables
- Spins up a WordPress container connected to MySQL
- All actions automated with Ansible

## 🧪 How to Run
1. Clone the repo
2. Update `hosts` with your target machine or use `localhost`
3. Run:
   ```bash
   ansible-playbook -i ansible/hosts ansible/wordpressdeploy.yml
  
<img width="983" height="272" alt="wordpress deploy" src="https://github.com/user-attachments/assets/c85e0181-25a6-42d9-96df-6a9ccd4d1f6a" />

Now you can access wordpress at http://localhost:8080

<img width="1237" height="947" alt="wordpress webpage" src="https://github.com/user-attachments/assets/51a565b2-f4bb-4ea6-982a-db3d73d7a2b0" />

📌 What I Learned
- Docker networking and multi-container management
- Writing Ansible playbooks for Docker setup
- Real-world automation using infrastructure as code
