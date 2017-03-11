# vim的三种模式
vim分为三种模式，认为可以分为normal模式和insert模式就可以了。

1.第一种模式即normal模式，通常可以翻译为“正常模式”或者“命令模式”，在该模式下我们的键盘输入都会当做命令来执行，比如i表示在光标左边插入，a表示在光标右边插入，hjkl分别表示光标向左下上右移动。

2.第二种模式即insert模式，通常可以翻译成"插入模式“，这个模式下的vim好像和我们在windows下的大部分编辑器是一样的，咱们按下什么键，屏幕上就会有相应的显示，当然，某些键是除外的，比如Esc键用来回到命令模式，有些键是功能键，不具有输入字符的功能。

3.第三种模式即last line mode（底行模式），它主要用于保存文件或者退出，搜索、查找替换、设置编辑环境等等功能，因为它此时的输入也会被当做命令，因此也有人把它并入命令模式。

# vim的基本使用

1.我们刚进入vim，它默认是工作在命令模式下的，我们需要切换到插入模式下才能输入文本。

2.我们在命令模式下输入i就可以进入到插入模式了，下面首先给一个在命令模式下的截图：

![刚进入vim](http://upload-images.jianshu.io/upload_images/5134976-8fb664dec7db8a90.jpg?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

咱们在键盘键入i，这里的i是”insert“的首字母，表示插入，可以进入insert模式。

![进入insert模式](http://upload-images.jianshu.io/upload_images/5134976-a9f1af25382bbd2f.jpg?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
底部有INSERT表示正处于insert模式。

这时候就可以输入你想输入的内容了，如下截图：
![输入你想输入的内容](http://upload-images.jianshu.io/upload_images/5134976-dd9fdeb296d85a5b.jpg?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

先按Esc来切入到命令模式下，然后再按一下：来到  底行模式，然后输入w D:vimBas.txt,如下截图：
![底行模式](http://upload-images.jianshu.io/upload_images/5134976-c93e5e850d418f8e.jpg?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

最后退出也是要先按一下：来到  底行模式，然后输入q，回车确认即可。

好了，至此，咱们用vim来完成了咱们的第一个任务，那就是写一份txt文件，保存后退出，大家可以发现，咱们的所有操作都是利用键盘完成的，根本用不到鼠标，这也是vim之所以这么快的原因之一----那就是使用鼠标和键盘会让我们的工作变慢，因此，用键盘代替鼠标，会让我们的工作快很多，随着后续的学习，大家会发现我们的很多操作都可以用键盘来单独完成，鼠标很多时候会感觉很鸡肋，一般都选择不用。