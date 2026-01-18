# Taka vs Dalhousie Foot and Ankle - Clinical Documentation Repository

## リポジトリ情報

### GitHubリポジトリ
- **リポジトリURL**: `https://github.com/takaresearch/takavsdalfellowship.git`
- **ブランチ**: `main`

### リポジトリのクローン方法

```bash
git clone https://github.com/takaresearch/takavsdalfellowship.git
cd takavsdalfellowship
```

## プロジェクト構成

本リポジトリは、足関節外科に関する臨床情報および症例記録を体系的に管理するために構築されております。

### 主要な臨床資料ファイル

1. **Diabetic foot ulcer.md** - 糖尿病性足潰瘍に関する臨床情報
   - 創傷治癒を妨げる9つの要因の詳細
   
2. **Achilles tendon rupture.md** - アキレス腱断裂に関する資料

3. **Ankle fusion.md** - 足関節固定術に関する資料

4. **MTP fusion.md** - 中足趾節関節固定術に関する資料

5. **Outpatient.md** - 外来患者管理に関する資料

### ディレクトリ構造

```
.
├── README.md                      # 本ファイル
├── .gitignore                     # Git管理除外設定
├── be a fluent doctor in English.txt
├── Achilles tendon rupture.md     # アキレス腱断裂
├── Ankle fusion.md                # 足関節固定術
├── Diabetic foot ulcer.md         # 糖尿病性足潰瘍
├── MTP fusion.md                  # MTP関節固定術
├── Outpatient.md                  # 外来管理
├── warehouse/                     # アーカイブ資料
│   ├── 1768745128.md
│   ├── 1768746619.md
│   ├── AQADXQtrG9mqaUd-.md
│   └── AQADXQtrG9mqaUd-file_0.jpg
├── Outpatient/                    # 外来症例フォルダ
├── Diabetic foot ulcer/           # 糖尿病性足潰瘍症例フォルダ
├── ankle fusion/                  # 足関節固定術症例フォルダ
└── MTP fusion/                    # MTP関節固定術症例フォルダ
```

## 使用方法

### 新規症例の追加
各疾患カテゴリーに対応するフォルダまたはMarkdownファイルに症例情報を追加してください。

### 変更のコミットとプッシュ

```bash
# 変更をステージング
git add -A

# コミット
git commit -m "コミットメッセージ"

# GitHubへプッシュ
git push origin main
```

### リポジトリの最新状態への更新

```bash
git pull origin main
```

## 注意事項

- 患者情報を含む資料については、個人情報保護法および医療倫理規定を遵守し、適切に匿名化してください
- 機密情報は`.gitignore`に登録し、GitHubにアップロードしないよう留意してください

## バージョン管理

本リポジトリはGitによるバージョン管理を採用しており、全ての変更履歴が記録されます。

---
最終更新日: 2026年1月18日
