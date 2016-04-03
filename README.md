# test_ansible_local

- win10 + Vagrant(1.8.1) + ansible_localプロビジョナ 動作テスト
- ansible_localでインストールされるバージョンは指定不可
- ansibleのroleの雛型フォルダを空登録
```
$ cd provisioning/roles/common
$ ls | xargs -t -I{} touch {}.gitkeep
```
