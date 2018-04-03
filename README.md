# whats's localsetup-by-ansible
ansibleでhomebrew、homebrewcaskを経由したライブラリ管理ができる。

# スタートガイド
- ansibleのinstall

```
brew insatll python
brew install ansible
```

- 実行コマンド

```
ansible-playbook -i hosts packages.yml
```

# 参考
- [簡単!! AnsibleでMacのローカル環境を構築する – サーバーワークスエンジニアブログ](http://blog.serverworks.co.jp/tech/2017/05/22/ansible-for-mac/)
