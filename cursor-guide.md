これは**Markdown**です。

# login.pyを作成して、この1行だけ書いてTab
def login(username: str, password: str) -> [Tab]
# → dict: のような型ヒントが提案される

    """ユーザーログイン処理 [Tab]
    # → 詳細な説明が自動生成

    # ここでJWT [Tab]
    # → トークンの生成処理が提案される

    # 新規 daily.md 作成
## 今日やること
Serenaを使って [Tab]
# → "プロジェクト全体のシンボルを検索し..."

エラーの原因は [Tab]
# → 文脈から推測して補完

# Cmd+K → "この関数の最適化版も見せて"
# 現在のコードと改善版を並べて表示

# エラーをコピー → Cursor Chatに貼り付け
# → 修正コードが即生成

# 常に以下を守って
- コメントは日本語
- 変数名は英語
- エラーは全てtry-exceptで補足
- printじゃなくてlogger使う
- 型ヒントは省略しない

1. Claude: "Serenaでプロジェクト構造を把握して"
2. Serena: シンボル一覧を返す
3. Cursor: その情報を元にコード生成
4. Claude: "できたコードをSerenaで配置して"

