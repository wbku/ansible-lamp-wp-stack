# sudo apt install ansible -y
# sudo apt install python3-pip
# sudo pip install jinja2
# folder tree
![image](https://github.com/wbku/ansible-lamp-wp-stack/assets/147015869/0c8629a5-6d8f-4e83-9b3a-a0236d65998a)
# that's all you need to imploy your ansible lamp wordpress stack
# edit nodes & default.yml for your server's ip, domain and credentials

# cd to your_domain folder
# ansible-playbook -i nodes lamp-wp-stack.yml 
