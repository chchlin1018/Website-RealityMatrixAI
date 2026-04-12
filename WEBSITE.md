# 🌐 Website-RealityMatrixAI — 官網建設 & 維護

> **Notion**: https://www.notion.so/340f154a6472815db1e1e8f3dba29f94
> **GitHub**: https://github.com/chchlin1018/Website-RealityMatrixAI
> **域名**: www.realitymatrixai.com (GoDaddy)
> **Email**: michael.lin@realitymatrixai.com (MS365)
> **架構**: GitHub Pages + 單一 HTML（Claude AI 管理）

---

## 架構

| 項目 | 值 |
|------|-----|
| Hosting | GitHub Pages (free) |
| Repo | `chchlin1018/Website-RealityMatrixAI` (Public) |
| Domain | realitymatrixai.com + www.realitymatrixai.com |
| SSL | GitHub Pages auto HTTPS (free) |
| DNS | GoDaddy |
| 本地路徑 | `C:\Dev\Website-RealityMatrixAI` |
| 管理方式 | Claude AI via GitHub MCP → 直接 edit/push |

---

## DNS 設定（GoDaddy）

| Type | Name | Value |
|------|------|-------|
| A | @ | 185.199.108.153 |
| A | @ | 185.199.109.153 |
| A | @ | 185.199.110.153 |
| A | @ | 185.199.111.153 |
| CNAME | www | chchlin1018.github.io |

---

## ProArt 初始化指令

```bash
cd C:\Dev
mkdir Website-RealityMatrixAI
cd Website-RealityMatrixAI
git init
git remote add origin https://github.com/chchlin1018/Website-RealityMatrixAI.git
# 建立 README.md + CNAME + index.html 後:
git add .
git commit -m "Initial commit: Landing Page v1"
git branch -M main
git push -u origin main
```

## GitHub Pages 啟用

1. Settings → Pages
2. Source: Deploy from a branch
3. Branch: main / root
4. Custom domain: www.realitymatrixai.com
5. Enforce HTTPS ✅

---

## 更新紀錄

### 2026-04-12
- GitHub repo `Website-RealityMatrixAI` 已建立 (Public)
- Notion 頁面建立（Op 下）: 340f154a6472815db1e1e8f3dba29f94
- 待完成：初始化 repo（README + CNAME + index.html）
- 待完成：GoDaddy DNS 設定
- 待完成：GitHub Pages 啟用 + Enforce HTTPS
- 待完成：Landing Page HTML 設計
