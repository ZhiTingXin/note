AngularJS中的所有的标签属性都是通过ng来标记的

指令：
ng-app 指令告诉 AngularJS，<div> 元素是 AngularJS 应用程序 的"所有者"。

ng-model 指令把输入域的值绑定到应用程序变量 name。

ng-bind 指令把应用程序变量 name 绑定到某个段落的 innerHTML。

ng-init 指令初始化 AngularJS 应用程序变量。

ng-model  将输入的值传递（元素值）传递到应用程序

ng-controller 标记控制器

ng-repeat 来控制循环

创建属于我们自己的指令

模块定义应用 app.module(name,[]) 获得应用程序

控制器控制应用app.controller(name,function($scope){})

注意data-ng-同样可以使html5生效

表达式：
{{name}} eq ng-bind 在表达式和ng-bind中相当于js一样能够进行运算

对象的引入，可以初始化对象 person={name:a,id:b} ,引用为person.name

数组的使用，data=[0,1,2] data[1]=1






