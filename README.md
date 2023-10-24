# ansibleteleportsetup
basic ansible script to set up Teleport.sh

Change options in `vars/default.yml`

Edit `inventory` to have the ip address of the server and clients you want to install on.

Run below command 
`ansible-playbook -i inventory main.yml -k`

hey presto! isnt ansible great!
btw you can run the same script to update, just edit the `vars/default` to have the new version number :)
