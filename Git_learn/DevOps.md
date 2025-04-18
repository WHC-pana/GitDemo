GitHub 與 DevOps
===
### DevOps
DevOps 是 Development 和 Operations 兩個詞的組合，是一種理念與實踐。
DevOps 是一種將開發、IT維運和安全團隊一起合作的工作方式。

**DevOps Flow:** 從專案管理的角度出發
![img][DevOps_Flow]

**GitHub Flow:** 從Repository為中心發展
![img][GitHub_func_and_Repo_rel]

**GitHub vs Agile:**
![img][Agile_vs_GitHub]

**GitHub 與 Agile 對應關係:**
|GitHub Item|對應|Agile Item|
|:-:|:-:|:-:|
|Issue|<->|Task|
|Pipeline|<->|Action|
|Issue+Label(自訂)+Template|<->|Feature|
|Issue+Label(自訂)+Template|<->|User Story|
|Issue+Label(自訂)+Template+Milestone|<->|Epic|
|Project+Issue+Label+Pull Request|<->|Retrospective|
|Project+Issue+Pull Request|<->|Backlog|
|Project+Issue+Pull Request+Milestone|<->|Sprint|

### Branch 管理與策略
>Branch(分支) 是一個獨立開發環境，為了避免影響到其他開發環境而設計的。
正常的情況下，Repository應該會有一個預設的主要分支，並擁有許多不同的分支。當分支工作完成時，分支可以合併到其他分支。<br>
<span style="color:red">**Tip:**</span> 分支名稱在Repository中是唯一的，你無法在同一個Repository中建立相同名稱的分支

>Pull Request 是用於專案提交(**commit**)程式修改，請求 Repository 的擁有者拉取(**pull**)並合併(**merge**)修改的分支。其過程會比對來源與目地的內容，除了檢視是否有合併衝突，也提供讓 Repository 的擁有者可以進行**Code Review**，並持續與提交人員進行溝通，是一種較為嚴謹的流程。<br>
<span style="color:red">**Tip:**</span> 詳細的描述與設定可以審核，人員快速提交目的，加速同意Pull Request合併。

#### Git Flow:


#### GitHub Flow:


#### Fork Flow


#### GitHub Actions 運作原理
>GitHub Action 是透過某個特定事件進行觸發，讓代理程式逐一執行預設好的指令，以自動化完成工作流程。其中觸發條件設定稱為Event、
代理程式為Runner、執行工作為Job，工作內每一個指令為Step。<br>

#### GitHub Action 架構與流程:



[Agile_vs_GitHub]: ./Agile_vs_GitHub.png
[DevOps_Flow]: ./devops_flow.png
[GitHub_func_and_Repo_rel]: ./Repo_func_rel.png
[Git_flow]: ./git_flow.png