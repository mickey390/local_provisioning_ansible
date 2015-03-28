# local_provisioning_ansible
ローカルの環境をansibleで管理する


# 概要
自身のMacの環境をansibleを使って管理する。

# 使い方

## 開発環境用

```
% sudo ansible-playbook -i hosts -v dev-setting.yml
```

## プログラム言語用

```
% sudo ansible-playbook -i hosts -v dev-language.yml
```



## ミドルウェア用



## その他（ユーティリティ）



# 参考

http://mawatari.jp/archives/mac-provisioning-by-homebrew-and-ansible
