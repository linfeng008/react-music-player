# 项目名：react + react-router + redux 音乐播放器

## 需求：
  搞个项目练练手，Fight for me!

## 配置项

### 安装依赖
```
  cnpm install
```

### 本地开发运行.
```
  npm start
```

### 测试环境打包
```
  npm run test
```

### 预发布环境打包
```
  npm run pre
```

### 预发布环境打包
```
  npm run build
```



## 项目目录结构
	project
	  ├─ node_modules   (npm模块)
	  ├─ src    (工程模块)
	  │  ├─ actions  (获取数据并流向stores)
	  │  │  └─ more
	  │  ├─ components (组件)
	  │  │  └─ more
	  │  ├─ reducers  (每个store)
	  │  │  ├─ index
	  │  │  └─ detail
	  │  └─ containers (页面)
	  │     ├─ header
	  │     └─ footer
	  │  └─ router       (路由)
	  │     ├─ cardDetail
	  ├─ source    (声音文件)

	  ├─ webpack.config.js   (webpack编译配置)
	  ├─ .eslintrc.json   (eslint配置)
	  ├─ index.html   (入口文件)


### 组成部分有
	1.播放页面
		-可以滑动切换音乐
		-播放列表
		-可分享
	（后续可能可以加歌词显示）

##兼容性：
android 4.4+
ios 8.0+

##追加：
	最好后期可以加播放歌词的功能
	分享功能实现要研究下怎么做，
	有wifi 网路判断
  qq音乐做的也不错，可以抄袭下 哈哈哈——！

##以下是案例
https://i.y.qq.com/v8/playsong.html?playindex=0&songid=104769200,105564586,1865641,1770753,7315288,105477358,1883828,102335206,739120,4943082,5037883,101291074,1761010,478068,104384419,105747880,1400865,619518,100782665,7396229,7378431,101125428,1819400,104923464,103489546,2447134,803095,4829538,9059016,7250957,1885769,9059017,1865649&prevent=1
