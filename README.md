### Result

![Result](asset/cmd.png)

Hal itu dikarenakan fungsi spawner bersifat asynchronous (async). Sehingga, program tidak akan menunggu async tersebut dan melanjutkan print `hey hey` terlebih dahulu.