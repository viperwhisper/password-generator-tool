# パスワード生成ツール | Password Generator Tool

美しいUIとユニバーサルデザインを意識した  
Python製パスワード生成アプリ

---

## 特徴 / Features

ダーク・ライトモード対応  
日本語 / 英語切り替え  
アイコン付きモダンUI（CustomTkinter製）  
強度プリセット（弱・中・強）  
似た文字を除外するオプション  
自動コピー機能  
注意書き付きで安心設計  
オフラインで安全に動作  

---

## 使用技術 / Built with

- Python 3.11+
- [CustomTkinter](https://github.com/TomSchimansky/CustomTkinter)
- Pillow (for image icons)
- PyInstaller (for .exe build)

---

## 実行方法 / How to Run

### ソースから起動
```bash
pip install customtkinter pillow
python password_maker.py