## actions

通过github action使一些事情变得简单

### 自动构建JKSV.nro
具体action内容查看[JKSV-build.yml](./.github/workflows/JKSV-build.yml)

### 自动构建Switch-Library-Manager.exe
具体action内容查看[switch-library-manager-build.yml](./.github/workflows/switch-library-manager-build.yml)
与原版的区别：
+ 将原版中到`raw.githubusercontent.com`的请求全都改为镜像地址`cdn.jsdelivr.net/gh`，加快国内访问