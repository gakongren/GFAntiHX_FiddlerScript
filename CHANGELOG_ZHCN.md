#ver.3#
优化提升:
* 可以兼容官方反和谐公式 all666 存在
* 官方反和谐公示存在的情况下被修改的记录条目会被标记为 紫色

新功能:
* 新增加了指令 "override":

> override [true|false]	
* 示例: override true
* 参数为 true 的时候开启强制覆盖官方公式功能(false的时候为关闭)
* 将会使用默认的 all33 公式来进行替换
* 示例为开启强制覆盖功能

> override \<mp\> \<ammo\> \<mre\> \<part\>
* 示例: override 31 32 33 34
* 使用自定义的公式并强制覆盖官方公式, 自定义公式由参数构成(顺序为 mp ammo mre part)
* 示例为使用公式31/32/33/34替换作为自定义公式
