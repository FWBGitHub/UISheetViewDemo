# UISheetViewDemo
类似退出登录弹出框
![](https://github.com/FWBGitHub/UISheetViewDemo/raw/master/1.gif) 
#-----------------UISheetView用法---------------------#
  UISheetView *sheetView = [UISheetView sheetWithTitle:@"标题" cancelButtonTitle:@"实现功能的名称" destructiveButtonTitle:@"取消" clickCancleButton:^{
        //实现功能的点击触发Block
        NSLog(@"点击退出登录按钮");
    }];
    [sheetView show];
    
    
    
