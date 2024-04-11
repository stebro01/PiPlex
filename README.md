# Anleitung um PiPlex - MediaServer auf RaspPi

## Install Ansible

```bash
sudo apt install pipx
pipx install --include-deps ansible
```


## Starte Playbook

```bash
ansible-playbook -i hosts setup_plex.yml --ask-become-pass
```

## Teste dann mit

### PLEX:

http://192.168.178.86:32400/web

### TINYMEDIAMANAGER

```bash
cd ~/MyProjects/PiPlex/tinymediamanager
docker-compose up
```

open: 
http://192.168.178.86:4000

