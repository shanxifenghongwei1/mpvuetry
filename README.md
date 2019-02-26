# mpvuetry
mpvue的联系与尝试

从下载到尝试与修改到全部上传感觉很神奇什么的。就随手一记，以后肯定能用得到的。

1.下载，

          # 全局安装 vue-cli
          $ npm install --global vue-cli

          # 创建一个基于 mpvue-quickstart 模板的新项目
          $ vue init mpvue/mpvue-quickstart my-project

          # 安装依赖
          $ cd my-project
          $ npm install
          # 启动构建
          $ npm run dev

    这是官网给出来的一套完整流程。跟着走就行了。
    下载完毕之后会提示让你确定东西，appId 要确定，给到。（不给也行，下载到项目以后也可以改动）
    还有就是 关闭开启严格模式。 

    小程序工具的指向是my-project  
    运行完毕 npm run dev 以后回生成已个 dist 目录 那个就是编译后的小程序文件。

2.如何添加新页面？  

    -->在src底下的pages 里面新建一个 文件夹（我的名字是try），再新建两个文件，一个是index.vue  文件内容与vue是同样的，不过需要将晚间暴露出来不然会卡死
    -->在 main.js 里面其实就是vue的引用。 copy 上面的东西就行了。

    -->最后还要在app.json 里面页面上添加一层
