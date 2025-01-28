# windowsの初期セットアップマニュアル(インストール完了後)

### 基本
1. Windows Updateの適用
2. タスクバーの設定で左下にする、非表示などよしなに
3. Winget、WindowsターミナルがインストールされていなければMicrosoft storeでインストール
4. Onedriveの有効性を確認、User内の各フォルダがローカルかバックアップかを選択

### アプリケーションインストール1
1. 管理者権限でwtを実行(Windows Terminalを開く)し、`Set-ExecutionPolicy -Scope Process -ExecutionPolicy Bypass` を適用後、`> powershell apps.ps1`でwingetがつかえるものはまとめてインストールする。
2. `> wsl --install`から再起動して初期設定をひと通りやる。
3. `Set-ExecutionPolicy Restricted`へ戻す
5. [cica font](https://github.com/miiton/Cica)


### アプリケーションインストール2
1. Microsoft 365
2. Adobe
3. DaVinci Resolve
4. LaTeX


### 設定ファイル
1. windows terminalの設定ファイルを復元
2. google日本語入力の設定ファイルを復元
3. .sshを復元


### WSLの設定
