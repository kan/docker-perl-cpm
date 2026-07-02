# docker-perl-cpm

**このリポジトリはアーカイブ扱い。後継は Bitbucket
(`bitbucket.org/comlinks/docker-perl-cpm`) で管理し、CircleCI でビルドして
`ghcr.io/comlinks/docker-perl-cpm` へ公開している。**

公式のperlイメージをベースにcpmとcartonを導入したイメージ。
既存の公開済みイメージ (`ghcr.io/kan/docker-perl-cpm/perl-cpm:*`) は、
参照している既存プロジェクトが後継イメージへ移行を終えるまで残す。

## Example

```sh
docker pull ghcr.io/kan/docker-perl-cpm/perl-cpm:5.30.1
```
