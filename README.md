# Wordpress + Nginx 構築 Ansibleファイル

## 環境

- Ubuntu 18.04 LTS
- Ansible 2.5.1 以上

## コマンド

ssh ip指定
```sh
$ ansible-playbook -i <IPアドレス>, site.yml -k
```

localhost

```sh
$ ansible-playbook -i localhost, -c local site.yml
```