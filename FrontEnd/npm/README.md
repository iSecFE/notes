### NPM

#### 设置registry

``` node
  npm set registry url
  //npm install packageName --registry=url
```

#### 发布包

``` node
  npm publish
```

#### 取消发布包

``` node
  npm unpublish packageName
```

#### 更新包

``` node
  npm update packageName
```

#### 废弃包

``` node
  npm deprecate packageName[version] Message
```

#### 设置sass镜像源
``` node
  npm config set sass-binary-site http://npm.taobao.org/mirrors/node-sass
```