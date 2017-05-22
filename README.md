# ajax-tab-
放弃之前的iframe，选择应用更广泛的，性能更好的ajax实现的tab切换
在demo中使用的echarts图表布局作为测试，如果要引入更多的图表组件，建议使用d3.js，性能会更好
存在的问题，引入echarts动画图表，以及echarts-gl加载速度较慢，这是正常现象，并不是依赖ajax可以改进的
注：使用时记得要用eclipse+Tomcat，因为ajax支持http等协议方式，但是不支持直接从本地引用
    自运行函数的参数是要切换页面的html文件的路径，tabArr数组是左侧选项卡的标题
    注意引用文件的js文件和css文件的命名
