node_modules太多了，就不上传了。各位自行npm i
现在还没将页面切换未全部完成，仅完成管理员部分。如果各位想要切换页面显示，请在App.jsx中将<div></div>中的标签修改。如<TeacherCenter/><StudentCenter/><Login/>
如果您想加入页面切换，请注意REACT是SPA，只能有1个html。建议通过路由实现。

2021-6-5
添加教师课程管理界面，课程查找界面，教师和学生的申请界面，管理员用户查找界面，略微调整排版。

2021-6-7
完成信息管理相关所有页面的路由跳转。现在可以直接在登录界面选择用户类型然后直接点击登录进入相应页面（未连接后端，所以不用密码验证）。

2021-6-10
在managercenter左边Menu中添加了“系统管理”，添加了SystemManagement.jsx(代码未实现)
在学生申请中加入了“补选”选项
