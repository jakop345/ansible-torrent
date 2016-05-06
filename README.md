# ansible-torrent
Setup server and install [Lunik-Torrent](https://github.com/Lunik/Lunik-Torrent)

## Usage
Fill "hosts" file with the IP or DNS of your server.

Run:  
`ansible-playbook playbooks/install-torrent.yml -e "users={ name:<username>, groups: <group> }"`

## What's done
- Install:
  - nano
  - sudo
  - git
  - nodejs
- Setup-user:
  - lunik
  - ssh-key
- Other:
  - Lunik-Torrent repo
  - Install modules
  - Launch Lunik-Torrent

## Note
