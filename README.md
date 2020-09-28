# whats's localsetup-by-ansible
ansibleでhomebrew、homebrewcaskを経由したライブラリ管理ができる。

# スタートガイド
- ansibleのinstall
   - https://docs.ansible.com/ansible/2.9_ja//reference_appendices/python_3_support.html

```
$ pip3 install ansible
$ ansible --version | grep "python version"
```

- 実行コマンド

```
ansible-playbook --syntax-check packages.yml -i hosts
ansible-playbook -i hosts packages.yml
```

# 参考
- [簡単!! AnsibleでMacのローカル環境を構築する – サーバーワークスエンジニアブログ](http://blog.serverworks.co.jp/tech/2017/05/22/ansible-for-mac/)
- https://rightcode.co.jp/blog/information-technology/ansible-mac-environment-setup
