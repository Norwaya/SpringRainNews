# SpringRainNews
学习 抽屉布局  抽屉延伸到状态栏

学习方法：
把布局都拷贝到自己的项目中：
需要注意的几点：
  在conment_main中加入
  app:layout_behavior="@string/appbar_scrolling_view_behavior"
  不太清楚 功能是：让主要布局不会遮挡toolBar 
里面的toolbar是需要加入ActionBarDrawerToggle 来监测
