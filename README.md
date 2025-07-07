# Download and use ansible_playbooks

## Download all playbooks

#### 1. Clone Full Repository (Git)
```bash
git clone https://github.com/slava3441/ansible_playbooks.git
```

#### 2. Download as ZIP Archive (No Git Required)
```bash
wget https://github.com/slava3441/ansible_playbooks/archive/refs/heads/main.zip
```
```bash
unzip main.zip
```

## Download single playbook (Example: hosts_info.yml)

#### 3. wget: 
```bash
wget https://raw.githubusercontent.com/slava3441/ansible_playbooks/refs/heads/main/hosts_info.yml
```
#### 4. curl: 
```bash
curl -O https://raw.githubusercontent.com/slava3441/ansible_playbooks/refs/heads/main/hosts_info.yml
```
## Usage Example
```bash
ansible-playbook hosts_info.yml
```
