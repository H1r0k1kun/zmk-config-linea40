# zmk-config-linea40 — プロジェクトルール

## Vault連携

**Vault プロジェクト名**: `zmk-config-linea40`
（この値で `projects/zmk-config-linea40/` を特定する）

---

## 開発ルール（プロジェクト固有）

- **ブランチ運用**: `main` に直接 push（決定: `decisions/2026-08-04-開発フロー-main直push.md`）
- **push 前の承認は毎回必須**。グローバルの「コミット〜配布は承認不要」ルールは本プロジェクトには適用しない
- **編集前に必ず `git pull`**。`draw.yml` が keymap 変更を検知して `img/` に GitHub 側から自動コミットするため
- ファームは GitHub Actions（`build.yml`）でビルドされる。ローカルビルドはしない
- 実機への `.uf2` 書き込みは物理作業のため必ず開発者が行う

---

## 高リスク変更

`projects/zmk-config-linea40/review-risk-rules.md` を参照。

---

グローバルルールは `~/.claude/CLAUDE.md` を参照。
Vault連携・レビューワークフローはそちらで定義済み。
