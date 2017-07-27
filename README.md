> 可能相对少用到但是挺方便的几个命令 

#### 1.查看包文件当前版本和线上最新版本(是否有更新) 

```
npm -g outdated
```


#### 2.安装指定版本的文件

```
npm i <package name>@2.1.0-beta.25
```

#### 3.生成package.json文件

```
npm init
```

#### 4.添加npm仓库账号

```
npm adduser
```

#### 5.上传包文件

```
npm publish
```

#### 6.包管理者相关

```
npm owner ls <package name>     //浏览包管理者
npm owner add <user> <package name> //添加包管理者 
npm owner rm <user> <package name>  //删除包管理者 
```

#### 7.列出现有的包并且生成依赖树

```
npm ls
```

#### 8.列出某个包的所有可用版本号
```
npm view <package name> versions
```

#### 9.列出所有包以及对应版本号
```
npm ls
```