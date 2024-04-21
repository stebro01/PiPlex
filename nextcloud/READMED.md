# Anleitung

## Infos

https://kohlfrederic.de/nextcloud-auf-einem-raspberry-pi-4-installieren/

## Starten

```bash
ansible-playbook -i hosts ./playbooks/nextcloud_prepare.yml --ask-become-pass
```

## Nextcloud starten

http://192.168.178.86:9020/

Dann einfach einen neuen Admin erstellen + PW
z.B.: myadminsb