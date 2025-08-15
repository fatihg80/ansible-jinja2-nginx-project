 
# Ansible + Jinja2 Example Project

انقل المجلد إلى عقدة التحكم ثم:
ansible all --list-hosts
ansible-playbook site.yml           # على كل الويب سيرفرز
ansible-playbook site.yml -l production
ansible-playbook site.yml -l development

