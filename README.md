# devops-project

Jak použít - 

1. Na zařízení s Ansible stáhněte repo a zadejte do terminálů: "git clone https://github.com/LukasKusy/devops-project/"
2. "cd devops-project"
3. v "inventory.ini" zadejte jméno serveru a usera, př. 192.168.1.99 ansible_user=user
4. Ujistěte se že na cílovém serveru máte svůj SSH klíč
5. do terminálu v devops-project zadáte command: "ansible-playbook -i inventory.ini playbook.yml" + "--ask-become-pass" pro sudo oprávnění pokud je třeba.
6. Done, nyní byste mělí mít funkční docker, uživatele a Orthanc na cílovém zařízení.
