# Git 初心者日常
呢度係我日常使用 git command 既時候，遇到既問題。

日常使用機:
1. MacBook Pro (15-inch, 2017)
2. MacOS Catalina (10.15)

## 問題列表

### Github 改密碼問題及 2FA 之後處理
(Update: 29 August 2020)
背景: 我改完密碼及設定了 2FA之後，居然唔可以正常咁用 git clone... 試咗好多次都話我 authentication fail

問題: git clone 在更改密碼後及設定了 2FA 以後，使用不了 git clone 正常 clone project
我的解法: 
  - Source from: https://stackoverflow.com/questions/25550481/git-authentication-fails-after-enabling-2fa
  - 原來設定了 2FA 以後，密碼就用不了，要去設定一個 access token
 
 
