【SharpGPOAbuse.exe】 🔗 https://github.com/ReversecLabs/SharpGPOAbuse

つくりかた

・　Windows Defender（Real Time Protection）を切る

・　gitをインストール
```
PS C:\WINDOWS\system32> winget install --id Git.Git -e
```

・　本家の`.csproj`ファイルを確認、.netはv3.5
```
 <TargetFrameworkVersion>v3.5</TargetFrameworkVersion>
```

・　Visual Studio Installer → 「変更」→ 個別のコンポーネントからv3.5をインストール
![[images/image1]]

・　Visual Studioを立ち上げ、リポジトリのクローンから新規作成


・　`SharpGPOAbuse`を右クリックしてビルド

・　SpoolSample\bin\Releaseなどのフォルダに作成されている

・　事後処置
・　Windows Defenderを戻す。
