# 食用说明
一加内核开源地址：[OnePlusOSS](https://github.com/OnePlusOSS/kernel_manifest)
# 原始项目
[MKSU-SKN](https://github.com/ShirkNeko/KernelSU)
# 解释说明
KSU-NEXT编译源码来自Numbersf(https://github.com/Numbersf/Action-KernelSU-Next)
SukiSU编译项目来自aziwd(https://github.com/aziwd/Action_OnePlus_MKSU_SUSFS)
由于fork属于aziwd的仓库后无法再次fork属于Numbersf的仓库，故不是故意不显示来自Numbersf的fork，望理解。
再次感谢两位大佬的代码及修正！！！
# 更改内核后缀
1.在.github/workflows中找到文件名中不带share的.yml文件。
2.寻找代码“sed -i '$s|echo "\$res"|echo "\-android12-o-MKFEIZ"|' ./common/scripts/setlocalversion”
3.sed -i '$s|echo "\$res"|echo "\-此处为你想替换的名字"|' ./common/scripts/setlocalversion
# 此项目为自用，请勿传播！！
