# 主模块

> 实现子模块案例

## 创建

> 创建主模块

> mkdir main-module
> git init

> git remote add origin https://github.com/xknower/main-module.git
> git push -u origin master

> 创建子模块

> mkdir sub-modules/sub-module
> git init

> git remote add origin https://github.com/xknower/sub-module.git
> git push -u origin master

> 添加子模块

> git submodule add https://github.com/xknower/sub-module.git sub-modules/sub-module
> git submodule update

> .gitmodules
```
[submodule "sub-modules/sub-module"]
    path = sub-modules/sub-module
    url =  https://github.com/xknower/sub-module.git
```
