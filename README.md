# test_system
智慧课堂测评系统

系统采用django和sqlite数据实现，稍微熟悉django开发即可轻松配置并运行期整个系统

系统已实现功能：
  用户模块：
  学生，教师的基本信息管理，注册登录等
  课程模块：
  教师端：实现了创建课程，删除课程，查看已创建课程，课程签到，课程发布测试题等功能
  学生端：实现了学生加入课程，查看已加入课程信息，进入课程查看课程已经发布的习题集
  测试题模块：
  教师端：实现了教师通过上传.docx试题文件生成测试题，并可对生成的测试题进行修改题目，修改答案，添加解析等操作，教师还可对创建的测试题集进行发布使得课程内的学生可查看到课程发布的测试题集，并进入测试题进行查看
  学生端：实现了学生查看某个课程内已发布的测试题集，并可进入测试题集进行测试，学生测试完成后可查看自己在指定测试题集的答题情况
  
  系统数据库设计已较为完善，可以实现题库数据和程序完全独立开
  
预期但未实现的功能（能有个几十的浏览量这个假期一定把整个系统完善好 ^v^ ）：
  学生端系统基本功能的用户体验的完善和优化，因为现在有些地方的按钮是没有对应的事件连接的。
  教师端对学生的成绩信息统计没有实现，对题目数据的导出，签到数据的导出，多种格式上传试题文件（只实现了docx格式）支持未实现，随机签到点名学生的功能未实现
  测试题模块：测试题界面显示的并不是很美观，未做界面美化，试卷答题没有实现计时功能，并且试卷的答题日期没有限制到时分秒,试卷答题的效果也不是很好，没有实现答题卡的功能。
