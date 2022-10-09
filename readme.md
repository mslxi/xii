# 又是一只缝合怪。

支持以下docker镜像：

| 镜像       | 备注                                     | 建议                                          |
| ---------- |----------------------------------------| --------------------------------------------- |
| nginx      | 附带安装acme.sh，可以进入后生成ssl证书               |                                               |
| php        | 仅支持php8 和php7，内嵌composer. 支持phpmyadmin | 非必要不选装phpmyadmin，占用过大空间，约475mb |
| mysql      | 仅支持mysql8和mysql5.7                     | 1g内存选mysql5.7，2g或以上选8，更有优势       |
| redis      |                                        |                                               |
| mongodb    |                                        |                                               |
| supervisor |                                        |                                               |
| ELK系列    | 没深度验证稳定性，但是官方包，应该稳妥。                   |                                               |
| node环境   | 配置好一个node环境，版本号自己看.env                 |                                               |
| go环境     |                                        |                                               |

### 为什么要弄这个?

1. 想用docker做开发环境
2. 手痒
3. 喜欢lnmp的便捷

### 有什么优点？

1. docker + lnmp 的便捷操作
2. 运气好的时候，也许弄个前端ui出来，方便操作,这个也许可能只是也许。。。
3. 只保留比较新的

### 感谢

- 感谢 yeszao/dnmp 提供的代码，本项目是在 dnmp 的基础上修改而来
- 感谢 lnmp.org的代码和思路，本项目是在 lnmp.org v1.9 的基础上学习修改