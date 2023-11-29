# RockyLinux9 Notes

## RockyLinux9とは

- OSS
- 2022/9に公開された新しいLinux
- Redhatと互換性がある

## Setup

osアップデート(dnfは他で言う、yum/apk/...に当たるコマンド)

```bash
dnf upgrade
```

セキュリティや重大な不具合の修正など限定してアップデート

```bash
dnf upgrade-minimal
```

最新の利用可能なバージョンへインストール済みパッケージを同期する

```bash
dnf distro-sync
```

インストール済みのパッケージ

```bash
dnf list --installed
```

