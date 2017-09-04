# vuejs_demo_01
第一个vue项目


********请先确保你安装了
nodejs  
cnpm install -g vue-cli

1.新建文件 然后执行vue init webpack cheliangjicha 创建项目
2.npm install
3.npm run dev
4、安装依赖 
	npm update 名字 更新依赖
	npm install --save-dev stylus stylus-loader
	npm install  element-ui --save-dev
	npm install fastclick --save  解决点击300毫秒延迟
	npm install babel-runtime --save  ES6语法的转译
	npm install vue-lazyload --save 图片懒加载插件
	npm install better-scroll --save
	
	npm install babel-polyfill --dev  对ES6 promis 转译

  import ElementUI from 'element-ui'
  import 'element-ui/lib/theme-default/index.css'
  Vue.use(ElementUI)


-save-dev是指将包信息添加到devDependencies，表示你开发时依赖的包裹。 
-save是指将包信息添加到dependencies，表示你发布时依赖的包裹。 

	
5.制作小图标  https://icomoon.io  上传svg 图标制作字体文件

小知识  音乐APP
4-2 jsonp的封装使用
4-8 绕开接口限制
scroll 插件 使用技巧、必须要在warper 的父级 设定一个固定高度，只有这样他的子组件才可以滚动
    position: fixed
    width: 100%
    top: 43px
    bottom: 0
@touchstart.stop.prevent="onShortcutTouchStart"  手机点击
@touchmove.stop.prevent="onShortcutTouchMove"
@touchend.stop



computed：{} 计算属性钩子  用来排序啊 大小写啊等js方法处理数据
created（）{} 抓取数据钩子
mounted() {} dom钩子

第四章
slider轮播图 组件
scroll 滚动组件
vue-lazyload  图片懒加载组件
fastclick 和 better-scroll 冲突的时候在需要点击的dom上加class="needsclick"
loading 组件
