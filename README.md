# Hello
# 夏休み演習

## GitHubを用いたグループ開発
### 1.リポジトリを作成する。
1. 自分のGithubの画面の「Repositories」に移動し,右上の「New」をクリックする。
<kbd><img width="500" alt="スクリーンショット 2024-08-07 13 57 06" src="https://github.com/user-attachments/assets/31831688-0615-428e-a134-0c905e52ce48"><kbd>

<!-- READMEでの画像の貼り付けは,IssueでURLを作ってそのURLを貼るとできる。 -->

2. 「Repository name*」に作成したいリポジトリの名前を記入する。
3. 右下の「Create Repository」をクリックする。
<kbd><img width="755" alt="スクリーンショット 2024-08-07 14 03 03" src="https://github.com/user-attachments/assets/95dd1eb7-584c-4883-8f11-d97bb99349c1"><kbd>

4. 以上でリポジトリが作成できる。

### 2.作成したリポジトリをローカルに読み込む。
1. 作成したリポジトリのホーム画面に移動し,右上の「Code」をクリックする。
<kbd><img width="800" alt="スクリーンショット 2024-08-22 12 42 08" src="https://github.com/user-attachments/assets/d70c2e7d-dbb3-43b0-b7a2-37b8b8e7248b"><kbd>

2. HTTPSまたはSSHのURLをコピーする。
<kbd><img width="916" alt="スクリーンショット 2024-08-22 12 42 36" src="https://github.com/user-attachments/assets/655e52a7-8011-43b3-8ed7-6f4da61858a1"><kbd>

3. ターミナル上でgit cloneコマンドを実行し,ローカルに読み込む。
```
(base) kota@TakaminenoMacBook-Air ~ % git clone <ここに「2. HTTPSまたはSSHのURLをコピーする。」のURLをコピペする>
```
そのあと、読み込み先のカレントディレクトリでlsコマンドを実行し、ローカルに読み込まれているかを確認する。
```
(base) kota@TakaminenoMacBook-Air ~ % ls
Applications		Logisim			TeX
Atcoder			Movies			dev
Desktop			Music			exe_Github
Documents		OneDrive - 琉球大学	git-exercise
Downloads		Pictures		kakeibo
GIT			Public			miniconda3
Library			StuLab1			prog1
Linux			StuLab2			prog2
```
4. 以上でリポジトリの準備ができた。