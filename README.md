# 有些机器太烂跑不动docker,就需要ansible来安装

# 如果需要别的可以去 https://galaxy.ansible.com 添加

# ansible-php-dev

ansible-play 开发环境部署
```
   root 运行
   bash install-ansible.sh
   ansible-galaxy install -r requirements.yml
   ansible-playbook -i hosts  */install.yml
```
