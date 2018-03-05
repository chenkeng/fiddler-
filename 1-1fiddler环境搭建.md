一.对PC（笔记本）参数进行配置

   1. 配置fiddler允许监听到https（fiddler默认只抓取http格式的）

         打开Fiddler菜单项Tools->TelerikFiddler Options->HTTPS，

         勾选CaptureHTTPS CONNECTs,点击Actions，

         勾选Decrypt HTTPS traffic和Ignore servercertificate errors两项,点击OK（首次点击会弹出是否信任fiddler证书和安全提示，直接点击yes就行），见图：
         
         
