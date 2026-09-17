# YOLO.md

> 这个文件的存在只有一个目的：触发 GitHub 的 YOLO 成就。

## 它怎么来的

`director4168/-1` 仓库的 YOLO commit（`fb513a2`）是**直接 push 到 main**——这虽然精神上是 YOLO，但**不是** GitHub YOLO 成就的触发条件。

GitHub YOLO 成就的实际触发条件是：

> **Merged without a review** —— 合并一个**没有 review** 的 PR

所以才有了这个分支 + 这个文件：

1. 从 `main` 切到 `yolo-achievement` 分支
2. 在这个分支上提交 `YOLO.md`
3. 开 PR 把分支合回 `main`
4. **不**等待任何 review，直接 merge

按 GitHub 的检测逻辑，这次 merge 会算作 "merged without a review"。

## 文件长度

越短越好——YOLO 不是长篇大论。
