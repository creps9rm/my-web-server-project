# my-web-server-project

#1台目Webサーバー構築プロジェクト

LinuxとCCNAの勉強も兼ねて、自宅PC（Rocky Linux 9）に安全なWebサーバーを構築しました。

##こだわったセキュリティ
* **rootのパスワードログインを完全禁止**（手元PCの鍵でのみログイン可能）
* **OpenSSLによる通信の暗号化（HTTPS化）**
