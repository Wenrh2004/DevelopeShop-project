# **Developer Shop**
## **Developer Develoment team**
<p>We love code, always walk on the road, and we are the king of this world.</p>

> From **King Yen**
***
## 目录结构
```
|-- Downloads
    |-- .DS_Store
    |-- .gitignore
    |-- babel.config.js
    |-- jsconfig.json
    |-- package-lock.json
    |-- package.json
    |-- vue.config.js
    |-- New
    |   |-- 01.html
    |   |-- 02.千分位分割.html
    |   |-- 03.html
    |   |-- 04.html
    |   |-- 1.js
    |-- public
    |   |-- .DS_Store
    |   |-- favicon.ico
    |   |-- index.html
    |   |-- css
    |   |   |-- iconfont.css
    |   |   |-- reset.css
    |   |   |-- swiper.min.css
    |   |-- fonts
    |   |   |-- icon-moon.eot
    |   |   |-- icon-moon.svg
    |   |   |-- icon-moon.ttf
    |   |   |-- icon-moon.woff
    |   |   |-- icon-pc.eot
    |   |   |-- icon-pc.svg
    |   |   |-- icon-pc.ttf
    |   |   |-- icon-pc.woff
    |   |   |-- icon-tb.eot
    |   |   |-- icon-tb.svg
    |   |   |-- icon-tb.ttf
    |   |   |-- icon-tb.woff
    |   |   |-- icon-touch.eot
    |   |   |-- icon-touch.svg
    |   |   |-- icon-touch.ttf
    |   |   |-- icon-touch.woff
    |   |-- images
    |   |   |-- floor-1-1.png
    |   |   |-- floor-1-2.png
    |   |   |-- floor-1-3.png
    |   |   |-- floor-1-4.png
    |   |   |-- floor-1-5.png
    |   |   |-- floor-1-6.png
    |   |   |-- floor-1-b01.png
    |   |   |-- floor-1-b02.png
    |   |   |-- floor-1-b03.png
    |   |   |-- rBHu8l_6usyAeHgLAActhhatATY000.jpg
    |   |   |-- rBHu8l_6ut-AMz1WAAJLX6bBPuo322.jpg
    |   |   |-- rBHu8l_6utWAVk0hAAPa09gkjzc792.jpg
    |   |   |-- today01.png
    |   |   |-- today02.png
    |   |   |-- today03.png
    |   |   |-- today04.png
    |   |-- js
    |       |-- swiper.min.js
    |-- src
        |-- .DS_Store
        |-- App.vue
        |-- main.js
        |-- api
        |   |-- ajax.js
        |   |-- index.js
        |   |-- mockAjax.js
        |-- assets
        |   |-- image
        |       |-- icons.png
        |       |-- loading.gif
        |       |-- logo.png
        |-- components
        |   |-- .DS_Store
        |   |-- Footer
        |   |   |-- .DS_Store
        |   |   |-- index.vue
        |   |   |-- images
        |   |       |-- wx_cz.jpg
        |   |-- Header
        |   |   |-- index.vue
        |   |   |-- images
        |   |       |-- logo.png
        |   |-- Nav
        |   |   |-- index.vue
        |   |-- Pagination
        |       |-- index.vue
        |-- mock
        |   |-- floor.json
        |   |-- mockServe.js
        |   |-- recommends.json
        |   |-- offlineData
        |       |-- baseCategoryList.json
        |       |-- indexBanner.json
        |-- pages
        |   |-- .DS_Store
        |   |-- 404
        |   |   |-- index.vue
        |   |-- AddCartSuccess
        |   |   |-- index.vue
        |   |-- AddressModel
        |   |   |-- index.vue
        |   |-- Center
        |   |   |-- index.vue
        |   |   |-- MyOrder
        |   |   |   |-- index.vue
        |   |   |   |-- images
        |   |   |       |-- delete.png
        |   |   |       |-- goods.png
        |   |   |       |-- itemlike01.png
        |   |   |       |-- itemlike02.png
        |   |   |       |-- itemlike03.png
        |   |   |       |-- itemlike04.png
        |   |   |       |-- itemlike05.png
        |   |   |       |-- itemlike06.png
        |   |   |-- OrderGroup
        |   |       |-- index.vue
        |   |-- Detail
        |   |   |-- index.vue
        |   |   |-- ImageList
        |   |   |   |-- ImageList.vue
        |   |   |-- Zoom
        |   |   |   |-- Zoom.vue
        |   |   |-- images
        |   |       |-- cross.png
        |   |       |-- dp01.png
        |   |       |-- dp02.png
        |   |       |-- dp03.png
        |   |       |-- dp04.png
        |   |       |-- intro01.png
        |   |       |-- intro02.png
        |   |       |-- intro03.png
        |   |       |-- itemlike01.png
        |   |       |-- itemlike02.png
        |   |       |-- itemlike03.png
        |   |       |-- itemlike04.png
        |   |       |-- itemlike05.png
        |   |       |-- itemlike06.png
        |   |       |-- l-m01.png
        |   |       |-- list.png
        |   |       |-- part01.png
        |   |       |-- part02.png
        |   |       |-- part03.png
        |   |       |-- s1.png
        |   |       |-- s2.png
        |   |       |-- s3.png
        |   |       |-- toolbars.png
        |   |-- Home
        |   |   |-- index.vue
        |   |   |-- Brand
        |   |   |   |-- index.vue
        |   |   |   |-- images
        |   |   |       |-- brand_03.png
        |   |   |       |-- brand_05.png
        |   |   |       |-- brand_07.png
        |   |   |       |-- brand_09.png
        |   |   |       |-- brand_11.png
        |   |   |       |-- brand_13.png
        |   |   |       |-- brand_15.png
        |   |   |       |-- brand_17.png
        |   |   |       |-- brand_19.png
        |   |   |       |-- brand_21.png
        |   |   |-- Floor
        |   |   |   |-- index.vue
        |   |   |-- Like
        |   |   |   |-- index.vue
        |   |   |   |-- images
        |   |   |       |-- like_01.png
        |   |   |       |-- like_02.png
        |   |   |       |-- like_03.png
        |   |   |-- ListContainer
        |   |   |   |-- index.vue
        |   |   |   |-- images
        |   |   |       |-- ad1.png
        |   |   |       |-- banner1.jpg
        |   |   |       |-- banner2.jpg
        |   |   |       |-- banner3.jpg
        |   |   |       |-- banner4.jpg
        |   |   |-- Rank
        |   |   |   |-- index.vue
        |   |   |   |-- images
        |   |   |       |-- 1.jpg
        |   |   |       |-- bg0.png
        |   |   |-- TodayRecommend
        |   |       |-- index.vue
        |   |       |-- images
        |   |           |-- clock.png
        |   |-- Login
        |   |   |-- .DS_Store
        |   |   |-- index.vue
        |   |   |-- images
        |   |       |-- .DS_Store
        |   |       |-- ali.png
        |   |       |-- loginbg.png
        |   |       |-- qq.png
        |   |       |-- sina.png
        |   |       |-- weixin.png
        |   |       |-- wx_cz.jpg
        |   |-- Pay
        |   |   |-- index.vue
        |   |   |-- images
        |   |       |-- check.png
        |   |       |-- icon.png
        |   |       |-- pay1.jpg
        |   |       |-- pay10.jpg
        |   |       |-- pay11.jpg
        |   |       |-- pay12.jpg
        |   |       |-- pay13.jpg
        |   |       |-- pay14.jpg
        |   |       |-- pay15.jpg
        |   |       |-- pay16.jpg
        |   |       |-- pay17.jpg
        |   |       |-- pay18.jpg
        |   |       |-- pay19.jpg
        |   |       |-- pay2.jpg
        |   |       |-- pay20.jpg
        |   |       |-- pay21.jpg
        |   |       |-- pay22.jpg
        |   |       |-- pay3.jpg
        |   |       |-- pay4.jpg
        |   |       |-- pay5.jpg
        |   |-- PaySuccess
        |   |   |-- index.vue
        |   |   |-- images
        |   |       |-- right.png
        |   |-- Register
        |   |   |-- index.vue
        |   |-- Search
        |   |   |-- index.vue
        |   |   |-- SearchSelector
        |   |   |   |-- index.vue
        |   |   |-- images
        |   |       |-- search
        |   |           |-- like_01.png
        |   |           |-- like_02.png
        |   |           |-- like_03.png
        |   |           |-- like_04.png
        |   |           |-- mobile01.png
        |   |           |-- mobile02.png
        |   |           |-- mobile03.png
        |   |           |-- mobile04.png
        |   |           |-- mobile05.png
        |   |           |-- mobile06.png
        |   |           |-- phone01.png
        |   |           |-- phone02.png
        |   |           |-- phone06.png
        |   |           |-- phone07.png
        |   |           |-- phone08.png
        |   |           |-- phone09.png
        |   |           |-- phone10.png
        |   |           |-- phone11.png
        |   |           |-- phone12.png
        |   |           |-- phone14.png
        |   |-- ShopCart
        |   |   |-- index.vue
        |   |   |-- images
        |   |       |-- emptyCart.png
        |   |       |-- goods1.png
        |   |       |-- goods2.png
        |   |       |-- goods3.png
        |   |-- Trade
        |       |-- index.vue
        |       |-- images
        |           |-- choosed.png
        |           |-- goods.png
        |-- plugins
        |   |-- elementui.js
        |   |-- swiper.js
        |   |-- validate.js
        |-- router
        |   |-- index.js
        |   |-- routes.js
        |-- store
        |   |-- index.js
        |   |-- modules
        |       |-- detail.js
        |       |-- home.js
        |       |-- search.js
        |       |-- shopcart.js
        |       |-- trade.js
        |       |-- user.js
        |-- utils
            |-- userabout.js
```
## 路由说明
* 路由组件  
    * Home首页路由组件
    * Search搜索路由组件
    * Login登陆路由组件
    * Refister注册路由组件
* 非路由组件
    * Header
        * 首页
        * 搜索页
        * Footer(在Home、Search、显示，在Login、Register隐藏)
        * 首页
        * 搜索页
        * 登陆注册<font color=red>没有</font>
* 路由跳转
    * 声明式导航 router-link
    * 编程式导航 push\replace
## npm 包使用
* less-loader  
    项目采用 less 样式开发，浏览器不识别 less 语法，因此需要借助loader 进行处理将 less 语法转化为 CSS 语法  
    > 选择 less 的原因：  
        * Less 是一个CSS 预处理器。编译后，它会生成简单的CSS，适用于浏览器。  
        * Less 支持跨浏览器兼容性。  
        * 由于 Less 使用嵌套，使得代码更短、更干净，并以特定的方式组织。
        * 由于 Less 使用变量，可以更快地实现维护。
        * Less 提供了一系列运算符，使编码更快，更省时。
        * Less 提供 @import 规则，这样就可以轻松地处理外部文件。注：导入是必需的，因为许多人将样式表分割为多个文件，而不是将其放入一个文件中。
        * Less 提供了合并属性。Less 最令人兴奋的特征是接受多个值，如transform, transition 和 box-shadow。
        * Less 是用 Javascript 编写的，它可以比 CSS 的其他预处理器更快地编译。
* axios  
    浏览器和node.js的基于Promise的HTTP客户端  
    axios 是一个基于Promise 用于浏览器和 nodejs 的 HTTP 客户端，本质上也是对原生XHR的封装，只不过它是Promise的实现版本，符合最新的ES规范，有以下特点：  
    * 从浏览器中创建 XMLHttpRequests
    * 从 NodeJs 创建 http 清求
    * 支持 Promise API
    * 拦截请求和响应
    * 转换请求数据和响应数据
    * 取消请求
    * 自动转换 JSON 数据
    * 客戸端支持防御 XSRF
    > 在使用时我们对 axios 进行了二次封装从而减少重复性工作，不可能每一次发起新请求时，都要重新配置请求域名、请求头 Content-Type、Token 等信息。  
* vuex  
    管理项目共用数据  
    > vuex模块式开发【modules】  
         由于项目体积比较大，你、向服务器发请求的接口过多，服务器返回的数据也会很多，如果还用以前的方式存储数据，导致vuex中的state数据格式比较复杂。采用vuex模块式管理数据。
* mockjs
    实现前后端分离，在不改变既有代码的条件下拦截 Ajax 请求，并通过Mock.mock方法模拟数据，通过 API 文件夹中的 mockRequest 获取模拟数据所用的 axios 实例
    > mockjs 优势
    > 1. 前后端分离
    > 2. 不需要修改既有代码，就可以拦截 Ajax 请求，返回模拟的响应数据
    > 3. 数据类型丰富
    > 4. 通过随机数据，模拟各种场景
* swiper
    实现轮播图效果
* elementUI
    实现分页功能
* uuid
    生成用户id【身份】获取购物车数据进行展示
* promise
    1. 主要用于异步计算
    2. 以将异步操作队列化，按照期望的顺序执行（简单理解的话就是异步请求变成同步请求），返回符合预期的结果
    3. 可以在对象之间传递和操作promise，帮助我们处理队列
    4. 解决异步编程导致陷入回调地狱问题的（解决地狱回调问题）
    > 使用 promise 的原因
    >回调函数的嵌套多，如果有使代码的可读性和可维护性都大大降低了（回调地狱），如果使用Promise去实现这个效果，虽然代码量不会减少，甚至更多，但是却大大增强了其可读性和可维护性。  
* qrcode
    通过qrCode.toDataUrl方法，将字符串转换为加密的在线二维码链接，通过图片进行展示
* vee-valadiate
    实现表单验证
## 功能实现与性能优化
* TypeNav三级联动性能优化
    项目：home切换到search或者search切换到home，你会发现一件事情，组件在频繁的向服务器发请求，获取三级联动的数据进行展示。
因此我们通过函数防抖与节流对其进行优化
    * 解决方法  
    因为路由跳转的时候，组件会进行销毁的【home组件的created：在向vuex派发action，因此频繁的获取三级联动的数据】
    只需要发一次请求，获取到三级联动的数据即可，不需要多次
    * 优化项目。
        v-if|v-show
        按需加载:对于loadsh插件，它里面封装的函数功能很多
        import _ from lodash 相当于把全部功能引入进来，但是我们只是需要节流。
        函数防抖与节流
        > 函数防抖与节流  
        > * 正常：事件触发非常频繁，而且每一次的触发，回调函数都要去执行（如果时间很短，而回调函数内部有计算，那么很可能出现浏览器卡顿)  
        > * 防抖：前面的所有的触发都被取消，最后一次执行在规定的时间之后才会触发，也就是说如果连续快速的触发,只会执行最后一次  
        > * 节流：在规定的间隔时间范围内不会重复触发回调，只有大于这个时间间隔才会触发回调，把频繁触发变为少量触发
* 路由跳转三级分类页面 Nav 采用编程式导航的原因  
    > 三级分类由于使用router-link的时候，会出现卡顿现象，因此采用编程式导航。路由跳转的时候【home->search】：需要进行路由传递参数【分类的名字、一、二、三级分类的id】
* 放大镜组件的实现
    * 放大镜功能  
        借助 js 插件解决
    * 遮罩层动态跟随
        获取节点（对 DOM 进行定位），通过 JS 动态修改 left｜top（定位元素才有left、top属性）
* 获取购物车数据进行展示
    UUID技术生成用户ID【身份】
* 用户信息的传递
    * 用户登录后获取用户信息进行展示
    登录成功以后，服务器会返回token【存储于vuex当中】，如果想获取用户信息还需要再发请求【用户信息】，携带token给服务器。  
    * 退出登录
    1. 发请求，需要通知服务器，把现在用户身份token【销毁】
    2. 清除仓库数据+本地存储数据【都需要清理】
* 导航守卫
    通过条件判断路由能不能进行跳转
    > * 全局守卫：
    项目当中任何路由变化都可以检测到，通过条件判断可不可以进行路由跳转。
    > * 前置守卫：路由跳转之前可以做一些事情。
    > * 后置守卫：路由跳转已经完成在执行。  

    在项目中通过路由独享首位和组件内守卫完成对用户登录、未登录的判断  
    * 未登录情况  
        1. 全局守卫：只要项目中任何一个路由发生变化便会触发
        2. 项目守卫使用：一般使用前置全局守卫
    * 路由独享守卫
        1. 路由独享守卫：需要在配置路由的地方使用
        2. 导航守卫
    * 组件内守卫
        beforeRouterEnter(){}
* 身份凭证
    * token
    始终遵循 token 身份，优先级最高
    * UUID 生成临时身份
* 懒加载
    * 路由懒加载
        1. v-if｜v-show
            尽可能采用v-show
        2. 按需引入 lodash、elementUI
        3. 防抖与节流
        4. 路由懒加载
            当用户访问的时候，加载对应组件进行展示
    * 图片懒加载
        1. vue-lazyload
* 表单验证
    通过 vee-valadiate 实现
    1. plugins 文件夹中的validate.js 注册 vee-valadite 插件
    2. 注册插件时，使用中文、以及其他验证字段【中文提示】
    3. 入口文件引入执行一次
    4. 使用 vee-valadiate
        * 引入
        ```
        import VeeValidate from 'vee-validate'
        import zh_CN from 'vee-validate/dist/locale/zh_CN'   // 引入中文 message
        Vue.use(VeeValidate)
        ```
        * 提示信息
        ```
        VeeValidate.Validator.localize('zh_CN', {
        messages: {
        ...zh_CN.messages,
        is: (field) => `${field}必须与密码相同` // 修改内置规则的 message，让确认密码和密码相同
        },
        attributes: { // 给校验的 field 属性名映射中文名称
        phone: '手机号',
        code: '验证码',
        password:'密码',
        password1:'确认密码',
        isCheck:'协议'
        }
        })
    * 基本使用
        ```
        <input
          placeholder="请输入你的手机号"
          v-model="phone"
          name="phone"
          v-validate="{ required: true, regex: /^1\d{10}$/ }"
          :class="{ invalid: errors.has('phone') }"
        />
        <span class="error-msg">{{ errors.first("phone") }}</span>

        const success = await this.$validator.validateAll(); //全部表单验证
        //自定义校验规则
        //定义协议必须打勾同意
        VeeValidate.Validator.extend('agree', {
        validate: value => {
        return value
        },
        getMessage: field => field + '必须同意'
        })
        ```
