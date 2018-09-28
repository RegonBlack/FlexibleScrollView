# FlexibleScrollView
a demo of flexible ScrollView
思路：
通过检测scrollview中子view 的位置，判断是否到达头部或者底部，如果已经到达顶部或者底部还在继续滑动，则重新布局，并在moveUp事件中实现回复动画。
