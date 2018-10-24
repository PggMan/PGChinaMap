# PGChinaMap
"中国地图绘制"

### Code
```objc
- (void)viewDidLoad {
    [super viewDidLoad];
    PGChinaMap *map = [[PGChinaMap alloc] initWithFrame:self.view.bounds];
    
    //map.seletedAry = @[@"新疆",@"黑龙江"];
    map.clickEnable = YES;
    [self.view addSubview:map];
}
```

### IMG
![权限图片](https://ws4.sinaimg.cn/large/006tNbRwly1fwjbkye00wj30o21bcjxa.jpg)
