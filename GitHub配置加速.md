## 通过配置Github的DNS来加速

1. 获取网站地址

   ```python
   # pack/gethost.py
   python gethost.py
   ```

2. 复制生成的host地址

   ```host
   # GitHub Start 
   20.205.243.166 github.com
   20.205.243.166 gist.github.com
   185.199.110.153 assets-cdn.github.com
   185.199.108.133 gist.githubusercontent.com
   185.199.110.133 cloud.githubusercontent.com
   185.199.108.133 camo.githubusercontent.com
   185.199.111.133 avatars0.githubusercontent.com
   185.199.109.133 avatars1.githubusercontent.com
   185.199.108.133 avatars2.githubusercontent.com
   185.199.108.133 avatars3.githubusercontent.com
   185.199.110.133 avatars4.githubusercontent.com
   185.199.109.133 avatars5.githubusercontent.com
   185.199.110.133 avatars6.githubusercontent.com
   185.199.109.133 avatars7.githubusercontent.com
   185.199.109.133 avatars8.githubusercontent.com
   185.199.108.133 avatars.githubusercontent.com
   185.199.111.154 github.githubassets.com
   185.199.110.133 user-images.githubusercontent.com
   20.205.243.165 codeload.github.com
   185.199.109.133 favicons.githubusercontent.com
   20.205.243.168 api.github.com
   # GitHub End 
   ```

3. windows修改host

   c:\Windows\System32\drivers\etc\hosts

4. linux修改host

   

5. mac os 修改host

   

6. 注意：要通过管理员打开文件

   复制host到目标保存

