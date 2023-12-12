# 使い方(git)
1) プロジェクトのルートディレクトリで`generamba setup`
2) `Rambafile`のテンプレートの部分を以下のように変更

```
### Templates
catalogs:
- 'https://github.com/mutt5/GenerambaTemplate'
templates:
- {name: my_viper}
```

3) `generamba template install`でテンプレートを導入
4) `generamba gen [モジュール名] [テンプレート名]`でモジュールを作れます

# 使い方(ファイル)
1) プロジェクトのルートディレクトリで`generamba setup`
2) このリポジトリのいずれかのディレクトリを適当な場所に配置
3) `Rambafile`のテンプレートの部分を以下のように変更
4) `generamba template install`でテンプレートを導入
5) `generamba gen [モジュール名] [テンプレート名]`でモジュールを作れます
