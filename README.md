1. 全局安装node-http
`npm install http-server -g`
2. 该项目目录下开启服务
`http-server . -p 8000`
3. 若想要禁用缓存
`http-server . -p 8000 -c-1`
4. change_image方法object和image如何对应
```
object A_for_paint
    5a0eda416e2ae7acac4c86d4c3475c22
    data: 87d3413a1454d1df70ec855251c76f4b

meshed 59.003
    87d3413a1454d1df70ec855251c76f4b
    materials： 86a71ebe81c0076adc613f8041979000

materials A_paint
    86a71ebe81c0076adc613f8041979000
    texture：767d713e9678686d73ed83c100c83dd1    

texture for_paint
    767d713e9678686d73ed83c100c83dd1
    image: 1441955307443e9ea4bcdb03140bddd9

images A-sanmple.png.002
    1441955307443e9ea4bcdb03140bddd9
```