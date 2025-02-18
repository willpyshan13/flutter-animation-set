# ✨ Flutter Animation Set

[![pub package](https://img.shields.io/pub/v/flutter_animation_set.svg)](https://pub.dev/packages/flutter_animation_set)

简化Flutter交错动画。用动画配置的形式，通过时间线去驱动Flutter的交错动画。你可以

1. 使用`Flutter Animation Set`现有的动画组件
2. 使用`Flutter Animation Set`去创建新的动画组件
3. 贡献你的`Flutter Animation Set`动画组件
4. 在项目的example中观看所有的`Curves`动画效果

## 🎖 Installing

```yaml
dependencies:
  flutter_animation_set: ^0.0.4
```

## ⚡ Use Animation Set Widget

**1、import**

```dart
import 'package:flutter_animation_set/widget/transition_animations.dart';
import 'package:flutter_animation_set/widget/behavior_animations.dart';
```

**2、use**

```dart
child: YYRotatingPlane(),
```

**3、road map**

> transition_animations 过渡动画

<table>
  <tr>
    <td align="center">
      <img src="https://github.com/efoxTeam/flutter-animation-set/raw/master/image/gif/1.gif" width="90px">
      <br />
      YYRotatingPlane
      <br />
      ✅
    </td>
    <td align="center">
      <img src="https://github.com/efoxTeam/flutter-animation-set/raw/master/image/gif/2.gif" width="90px">
      <br />
      YYDoubleBounce
      <br />
      ✅
    </td>
    <td align="center">
      <img src="https://github.com/efoxTeam/flutter-animation-set/raw/master/image/gif/3.gif" width="90px">
      <br />
      YYWave
      <br />
      ✅
    </td>
    <td align="center">
      <img src="https://github.com/efoxTeam/flutter-animation-set/raw/master/image/gif/4.gif" width="90px">
      <br />
      YYWanderingCubes
      <br />
      ✅
    </td>
    <td align="center">
      <img src="https://github.com/efoxTeam/flutter-animation-set/raw/master/image/gif/5.gif" width="90px">
      <br />
      YYFadingFour
      <br />
      ✅
    </td>
    <td align="center">
      <img src="https://github.com/efoxTeam/flutter-animation-set/raw/master/image/gif/6.gif" width="90px">
      <br />
      YYFadingCube
      <br />
      ✅
    </td>
  </tr>
  <tr>
    <td align="center">
      <img src="https://github.com/efoxTeam/flutter-animation-set/raw/master/image/gif/7.gif" width="90px">
      <br />
      YYPulse
      <br />
      ✅
    </td>
    <td align="center">
      <img src="https://github.com/efoxTeam/flutter-animation-set/raw/master/image/gif/8.gif" width="90px">
      <br />
      YYThreeBounce
      <br />
      ✅
    </td>
    <td align="center">
      <img src="https://github.com/efoxTeam/flutter-animation-set/raw/master/image/gif/9.gif" width="90px">
      <br />
      YYThreeLine
      <br />
      ✅
    </td>
    <td align="center">
      <img src="https://github.com/efoxTeam/flutter-animation-set/raw/master/image/gif/10.gif" width="90px">
      <br />
      YYCubeGrid
      <br />
      ✅
    </td>
    <td align="center">
      <img src="https://github.com/efoxTeam/flutter-animation-set/raw/master/image/gif/11.gif" width="90px">
      <br />
      YYRotatingCircle
      <br />
      ✅
    </td>
    <td align="center">
      <img src="https://github.com/efoxTeam/flutter-animation-set/raw/master/image/gif/12.gif" width="90px">
      <br />
      YYPumpingHeart
      <br />
      ✅
    </td>
  </tr>
  <tr>
    <td align="center">
      <img src="https://github.com/efoxTeam/flutter-animation-set/raw/master/image/gif/13.gif" width="90px">
      <br />
      YYRipple
      <br />
      ✅
    </td>
    <td align="center">
      <img src="https://github.com/efoxTeam/flutter-animation-set/raw/master/image/gif/14.gif" width="90px">
      <br />
      YYRotateLine
      <br />
      ✅
    </td>
    <td align="center">
      <img src="https://github.com/efoxTeam/flutter-animation-set/raw/master/image/gif/15.gif" width="90px">
      <br />
      YYCubeFadeIn
      <br />
      ✅
    </td>
    <td align="center">
      <img src="https://github.com/efoxTeam/flutter-animation-set/raw/master/image/gif/16.gif" width="90px">
      <br />
      YYBlinkGrid
      <br />
      ✅
    </td>
  </tr>
</table>

> behavior_animations 行为动画

<table>
  <tr>
    <td align="center">
      <img src="https://github.com/efoxTeam/flutter-animation-set/raw/master/image/gif/17.gif" width="90px">
      <br />
      YYFadeButton
      <br />
      ✅
    </td>
    <td align="center">
      <img src="https://github.com/efoxTeam/flutter-animation-set/raw/master/image/gif/18.gif" width="90px">
      <br />
      YYSingleLike
      <br />
      ✅
    </td>
    <td align="center">
      <img src="https://github.com/efoxTeam/flutter-animation-set/raw/master/image/gif/19.gif" width="90px">
      <br />
      YYLove
      <br />
      ✅
    </td>
    <td align="center">
      <img src="https://github.com/efoxTeam/flutter-animation-set/raw/master/image/gif/20.gif" width="90px">
      <br />
      YYSpringMenu
      <br />
      ✅
    </td>
    <td align="center">
      <img src="https://github.com/efoxTeam/flutter-animation-set/raw/master/image/gif/21.gif" width="90px">
      <br />
      YYFoldMenu
      <br />
      ✅
    </td>
  </tr>
</table>

**4、thanks**

* [flutter_spinkit](https://github.com/jogboms/flutter_spinkit)

## ⚡ Create Animation Set Widget By YourSelf

**1、import**

```dart
import 'package:flutter_animation_set/animation_set.dart';
import 'package:flutter_animation_set/animator.dart';
```

**2、use widget**

```dart
AnimatorSet(
    child: widget.child,
    animatorSet: [],
    animationType: AnimationType.reverse,
    debug: false,
)
```

AnimatorSet支持的属性

Property|Mean|Default
:--|:--|:--:|
child|执行动画的组件|无
animatorSet|动画集合|无
animationType|控制动画执行的类型|AnimationType.repeat
debug|输出日志|false

animationType的属性

Property|Mean
:--|:--|
repeat|重复播放动画
reverse|倒退播放动画
once|一次播放动画

**3、use AnimatorSet api**

关于动画集组件

Widget|Mean|Description
:--|:--|:--:|
**W**|width|控制宽度的变化，如果是按比例拉升，建议用SX替代
**H**|height|控制高度的变化，如果是按比例拉升，建议用SY替代
**P**|padding|控制边距的变化
**O**|opacity|控制透明度的变化
**SX**|scaleX|以中点进行X轴的缩放
**SY**|scaleY|以中点进行Y轴的缩放
**RX**|rotateX|以中点进行X轴的旋转
**RY**|rotateY|以中点进行Y轴的旋转
**RZ**|rotateZ|以中点进行Z轴的旋转
**TX**|transitionX|进行X轴的平移
**TY**|transitionY|进行Y轴的平移
**C**|color|控制背景颜色变化
**B**|border|控制背景边框变化

关于辅助组件

Widget|Mean|Description
:--|:--|:--:|
**Delay**|delay timeLine|延长时间线，进入等待阶段
**Serial**|combine animation|通过组合动画，达到一起播放的效果

## ⚡ For Example

**1、create timeLine**

<img src="https://github.com/efoxTeam/flutter-animation-set/raw/master/image/readme/YYWave.png" width="800px">
<br />

1. 此图表明动画的核心组成是根据时间线(timeLine)去制作的
2. 在执行的过程中有6次动画同时进行，且总动画时长都为900ms
3. 通过ScaleY组件有序的进行放大和缩小的操作，让每个矩形都有波浪的效果
4. 通过Delay组件去拖长时间线，达到动画时长统一为900ms

**2、build animatorSet**

通过上面的图示组装我们的动画组件，动画组件带有以下属性

* from:动画初始值
* to:动画结束值
* duration:动画时间
* delay:真正执行动画的延时
* curve:动画插值器

```dart
animatorSet: [
  Delay(duration: before),
  SY(from: 0.8, to: 1.6, duration: 200, delay: 0, curve: Curves.linear),
  SY(from: 1.6, to: 0.8, duration: 200, delay: 0, curve: Curves.linear),
  Delay(duration: after),
],
```

动画执行的对象是`Container`长方形

```dart
Widget makeWave(int before, int after) {
  return AnimatorSet(
    child: Container(
      color: Colors.white,
      width: 5,
      height: 15,
    ),
    animatorSet: [
      Delay(duration: before),
      SY(from: 0.8, to: 1.6, duration: 200, delay: 0, curve: Curves.linear),
      SY(from: 1.6, to: 0.8, duration: 200, delay: 0, curve: Curves.linear),
      Delay(duration: after),
    ],
  );
}
```

**3、convert to code**

```dart
class YYWave extends StatelessWidget {
  @override
  Widget build(BuildContext context) {
    return Container(
      width: 40,
      height: 40,
      child: Row(
        mainAxisAlignment: MainAxisAlignment.spaceBetween,
        children: <Widget>[
          makeWave(0, 500),
          makeWave(100, 400),
          makeWave(200, 300),
          makeWave(300, 200),
          makeWave(400, 100),
          makeWave(500, 0),
        ],
      ),
    );
  }
}
```

**4、done**

<img src="https://github.com/efoxTeam/flutter-animation-set/raw/master/image/gif/3.gif" width="90px">

## More

**1、组合动画**

> 缩放效果需要同时缩放X、Y轴，用到Serial组件

```dart
animatorSet: [
  Serial(
    duration: 2000,
    serialList: [
      SX(from: 0.0, to: 1.0, curve: Curves.easeInOut),
      SY(from: 0.0, to: 1.0, curve: Curves.easeInOut),
      O(from: 0.5, to: 0.0, delay: 1000, curve: Curves.easeInOut),
    ],
  ),
],
```

done

<img src="https://github.com/efoxTeam/flutter-animation-set/raw/master/image/gif/7.gif" width="90px">

**2、延时动画**

对真正做动画的时候处理delay属性

```dart
class YYThreeLine extends StatelessWidget {
  @override
  Widget build(BuildContext context) {
    return Container(
      width: 40,
      height: 40,
      child: Row(
        mainAxisAlignment: MainAxisAlignment.spaceBetween,
        children: <Widget>[
          makeLine(0),
          makeLine(50),
          makeLine(100),
        ],
      ),
    );
  }
}

Widget makeLine(int delay) {
  return AnimatorSet(
    child: Container(
      color: Colors.white,
      width: 10,
      height: 5,
    ),
    animatorSet: [
      TY(from: 0.0, to: 5.0, duration: 400, delay: delay, curve: Curves.fastOutSlowIn,),
      TY(from: 5.0, to: 0.0, duration: 400, curve: Curves.fastOutSlowIn,),
    ],
  );
}
```

done

<img src="https://github.com/efoxTeam/flutter-animation-set/raw/master/image/gif/9.gif" width="90px">

**3、倒退动画**

动画可以播放完成后，通过animationType属性设置`AnimationType.reverse`，让动画接着倒退播放

```dart
class YYFoldMenu extends StatelessWidget {
  @override
  Widget build(BuildContext context) {
    return Container(
      width: 40,
      height: 40,
      child: Column(
        mainAxisAlignment: MainAxisAlignment.spaceBetween,
        children: <Widget>[
          makeFoldMenu(0, 40),
          makeFoldMenu(100, 26.0),
          makeFoldMenu(200, 12.0),
        ],
      ),
    );
  }
}

Widget makeFoldMenu(int delay, double toY) {
  return AnimatorSet(
    animationType: AnimationType.reverse,
    child: Container(
      decoration: BoxDecoration(
        color: Colors.white,
      ),
      width: 30,
      height: 10,
    ),
    animatorSet: [
      Serial(
        duration: 2000,
        delay: delay,
        serialList: [
          TY(from: 0.0, to: toY, curve: Curves.elasticInOut),
          SX(from: 1.0, to: 0.1, curve: Curves.elasticInOut),
          SY(from: 1.0, to: 0.1, curve: Curves.elasticInOut),
        ],
      ),
    ],
  );
}
```

done

<img src="https://github.com/efoxTeam/flutter-animation-set/raw/master/image/gif/21.gif" width="90px">

## Bugs/Requests

* If your application has problems, please submit your code and effect to Issue.
* Pull request are also welcome.

## Contribution

* Contribute your component, and we'll add it to the animation set
* Or post your animation, if interested, we will help you to achieve

## About

* QQ：510402535
* QQ群：798874340
* e-mail：xyj510402535@qq.com
* g-mail：xyj51042535@gmail.com
* Blog：http://blog.csdn.net/qq_30379689
* Github：https://github.com/AndroidHensen

## License

Apache License 2.0
