Adding openvpn-client to host 'motherboard'

1. Create user 'deploy'
2. `usermod -G sudo deploy`
3. Generate key-pair with `ssh-keygen`
4. Copy private path of key-pair to directory of project
5. `deploy@motherboard:~/test-baikalteam$ ansible-playbook -i inventories/production openvpn.yml`

