# dotconfig
てきとうなconfigまとめ

# Chocolatey/packages.config
PowershellをWindowsで実行し、以下の通りにコマンドを実行すると簡単に入ります。
適宜必要なものをpackages.configに入れてください。

```
PS C:\> cd c:\
PS C:\> Invoke-WebRequest -Uri "https://raw.githubusercontent.com/suteaka1/dotconfig/master/Windows/chocolatey/packages.config" -OutFile "packages.config"
PS C:\> cat .\packages.config
PS C:\> clear
PS C:\> cinst packages.config -y
```


# githubのLICENSE

明記する予定はないので他のリポジトリについてもNo Licenseで

+ [ライセンスの選択を恐れる必要はありません - Qiita](http://qiita.com/tadsan/items/99d816e78ca429093b75#3-6)

+ [No License - Choose a License](http://choosealicense.com/no-license/)



