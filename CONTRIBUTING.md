# 貢獻 TWcommunities

非常感謝您投入時間貢獻於 TWcommunities 專案！  
以下是有關於如何貢獻 TWcommunities 的指南。請您花點時間閱讀這份文件，透過這份文件，您會更了解如何簡單且有效的來進行貢獻的程序。  
謝謝您的參與及貢獻。


## Table of Contents

- [Open issues](#open-issues)
    - [Request a community](#request-a-community)
    - [Feature requests](#feature-requests)
- [Pull requests](#pull-requests)
    - [For new Contributors](#for-new-contributors)
- [License](#license)

## Open issues

我們使用 GitHub issues 來追蹤公開的問題。透過建立 issue 來回報問題或是加技術社群的資訊是很容易的。

### Request a community

在開 issue 請求添加新的技術社群時，請填寫相關的資訊與連結，方便讓人們知道。

### Feature requests

我們歡迎功能的請求。但請您花一點時間，找出您的想法是否符合專案的範圍和目標。說服這個專案的開發者關於您這個功能的優點是一個很好的例子。 請您盡可能的提供更多的細節和內容。謝謝。

## Pull requests

發出 pull requests 是對 codebase 進行更動的最佳方式。(我們使用 [GitHub Flow](https://guides.github.com/introduction/flow/index.html)). 我們非常歡迎您的 pull requests:

1. Fork 本專案的 repo 並且從 `master` 建立你的新的分支
2. 添加社群資訊。
3. 如果您有添加新社群簡報資訊，請一起更新 README 檔案。
4. 送出 pull request。

### For new Contributors

如果您從未發送過 pull request ，歡迎參閱 [How to Contribute to an Open Source Project on GitHub](https://egghead.io/series/how-to-contribute-to-an-open-source-project-on-github)，本篇的教學會幫助您了解如何送一個 pull request 的。

1. [Fork](http://help.github.com/fork-a-repo/) 本專案，clone 您 fork 的專案到您的本機端，並且設定您的 remotes:

   ```bash
   # Clone your fork of the repo into the current directory
   git clone https://github.com/<your-username>/<repo-name>
   # Navigate to the newly cloned directory
   cd <repo-name>
   # Assign the original repo to a remote called "upstream"
   git remote add upstream https://github.com/TGmeetup/<repo-name>
   ```

2. 如果您 clone 下來的專案有些過時，請從 upstream 取得最新的更新(最新的 commit):

   ```bash
   git checkout master
   git pull upstream master
   ```

3. 創建一個新的主題分支(不包含主要專案的開發分支）以包含您的功能、更改或修復：

   ```bash
   git checkout -b <topic-branch-name>
   ```

4. 請適當地確保更新或加入資料。

5. Push 你的分支到您的 fork repository:

   ```bash
   git push origin <topic-branch-name>
   ```

6. 請到本專案的 GitHub 頁面 [TWcommunities repo](https://github.com/TGmeetup/TWcommunities) 並且 [開一個 Pull Request](https://help.github.com/articles/using-pull-requests/)，請在該 Pull request 中寫下清楚的標題與詳細的描述。

## License
在貢獻本專案時，您同意您的貢獻將依據 MIT 授權進行。謝謝！


