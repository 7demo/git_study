# git在win上创建ssh公钥（测试）

标签（空格分隔）： git

---

* 设置git的user与email:
    ```
        git config --global uer.name 7demo
        git config --global user.email liyanan7demo@gmai.com
    ```
* 生成秘钥
    ```
        ssh-keygen -t rsa -c liyanan7demo@gmail.com
    ```
    
    连续三个回车即可。
    
    然后把.ssh文件中的id_rsa.pub的内容复制出来粘贴到github中的ssh控制中。
    
    [参考操作][1]
    


  [1]: http://www.2cto.com/os/201305/211731.html