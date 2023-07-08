# WPF的Grid面板
Grid面板的简要笔记

1.margin 是对象和父元素的外边距属性，padding是对象和子元素之间的内边距属性
2.shareGroup 共享尺寸，需要设置共享组的范围，isShareGroup，后设置尺寸的成员会覆盖前面的尺寸
3.布局通过Grid.RowDefinitions，Grid.ColumnDefinitions，分行和列，设置行高和列宽时，可以直接设置像素、设置倍数n*，设置Auto三种方式。
4.使用Grid.ColumnSpan和Grid.RowSpan使元素跨越行或列，从起始位置开始跨越；使用Border可以很方便的将栅格合并，在用grid重新划分这个区域，在里面分使用StackPanel等是比较常见的做法。
5.GridSplitter是grid的控件，用来分割窗口，实现划动效果，GridSplitter占用一个ColumnDefinition（或row），该行ColumnDefinition设置宽为Auto,在GridSplitter属性设置一定宽度，ShowsPreview默认为False，可以实现滑动的动画效果。
6.布局舍入，UseLayoutRounding="True"，消除分割线的边界模糊的问题
7.共享尺寸组，是ColumnDefinition的属性，SharedSizeGroup=共享结点名称，在父结点中isShareGroupSizeScope设置true，指定范围。


