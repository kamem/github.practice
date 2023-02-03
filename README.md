# githubの練習

このファイルはGithubの練習用のリポジトリです。  
履歴の状態がわからなくなることがたまにあるので確認用です。

## Git コマンドについて
直前のコミットを修正する
```
git commit --amend
```

### 取り消し
[困ったときの git reset コマンド集 - Qiita](https://qiita.com/ChaaaBooo/items/459d5417ff4cf815abce)

#### 直前のコミットをなかったことにする
```
git reset --soft HEAD^
```
#### 直前のコミットを取り消し
```
git reset --hard HEAD^
```
#### コミット後の変更を全部消したい
```
git reset --hard HEAD
```
#### addを取り消したい
```
git reset --mixed HEAD
```
#### git resetをなかったことにする
```
git reset --hard ORIG_HEAD
```

## VscodeのGitについて
