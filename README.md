Setup your "all" variables file using group\_vars/all.template
ansible-vault create all

Add your password to a vault file:
vi ../vault

Run with:
ansible-playbook -i hosts site.yml --vault-password-file ../vault\_password

On the db:
sudo mysql\_secure\_installation
