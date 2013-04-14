LAKMovableView
==============

Extension of UIView that allows you to drag and rotate the view.

Example project included.

To use, drag LAKMovableView folder into your project and use as a UIView.

e.g.

LAKMovableView *movableView = [[LAKMovableView alloc] initWithFrame:CGRectMake(0, 0, 200, 200)];
	movableView.backgroundColor = [UIColor greenColor];
	[self.view addSubview:movableView];
