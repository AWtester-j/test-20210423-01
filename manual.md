# GitHubについて
## 保存フォルダ
C:\Users\user-pc\Documents\GitHUB


改行してみた(改行２つで)

## markdown書式
強調はアスタリスク２個で囲み、太字になる → **強調**

アスタリスク１個で囲み、イタリック(斜体)になる → *強調*

箇条書きはハイフン(-)またはアスタリスク(*)を行頭につけ、半角スペース空ける → 
- 箇条書き(ハイフン)
* 箇条書き(アスタリスク)

表の作成はバー(|)とハイフン(-)の組み合わせ

見出しはハイフンを２つ(--)
|a1|a2|
|--|--|
|b1|b2|


途中で改行を入れることが可能
|a1|a2|
|--|--|
|b1|b2|
|c1<br>C2|C3|

##参考HP
* https://tech-blog.rakus.co.jp/entry/20200624/markdown


##subブランチ作ってみた

## gitコマンド
* ログを見る

　git log

* 状態を見る

 git status

 * ローカルリポジトリを作成する

  該当フォルダに移動して、git init

 * 変更をコミットする
 
  git add

  git commit

---

$ git status
On branch edit_subtext
Your branch is up to date with 'origin/edit_subtext'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   manual.md


user-pc@DESKTOP-2L9D5K3 MINGW64 ~/Documents/GitHub/test-20210423-01 (edit_subtext)
$ git commit
hint: Waiting for your editor to close the file...

Aborting commit due to empty commit message.
