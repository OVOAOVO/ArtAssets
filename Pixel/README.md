# pixel 技法记录

## 完美像素
![完美像素](pictures/perfectPixel.png)

指的沿着行进方向，只有一条pixel

对于像素之间的差异不应该过大

可以使用3 2 2 3 这样子

## 对比度区分前景后景
<table>
  <tr>
    <td><img src="pictures/contrast.png" alt="对比度" /></td>
    <td><img src="pictures/value.png" alt="明度" /></td>
  </tr>
</table>

Value and constrast basics
>前后也不应该对比度太强

## 要突出重点部分
![负空间与正空间](pictures/NegativeAndPositiveSpace.png)

Negative and positive space
负空间 与 正空间
人的视觉是各种各样的，所以要突出一部分，让他着重表现


## 5种基本型状
世界中的物体由五种形状组成，阴影灯光使得它3D
<table>
  <tr>
    <td><img src="pictures/3d-objects.png" alt="明度" width="200" /></td>
    <td><img src="pictures/3DShadow.png" alt="对比度" width="200" /></td>
  </tr>
</table>

> 最两边的颜色对应的是高光与阴影，所以只有在高光以及纯阴影部分使用，平常的物体使用的颜色应该是居中一些
>

## 色彩和谐

<table>
  <tr>
    <td><img src="pictures/互补色.png" alt="互补色" width="200" /></td>
    <td><img src="pictures/单色渐变.png" alt="单色渐变" width="200" /></td>
    <td><img src="pictures/降低饱和度.png" alt="降低饱和度" width="200" /></td>
  </tr>
  <tr>
    <td align="center">互补色</td>
    <td align="center">单色渐变</td>
    <td align="center">降低饱和度</td>
  </tr>
</table>

- **互补色**：色环上相对的两种颜色，对比强烈但平衡
- **单色渐变**：同一色相，靠明度/饱和度变化过渡
- **降低饱和度**：降低饱和度让颜色更柔和统一

## HueShifter

![完美像素](pictures/HueShifter.png)

使用HSV更接近人眼

当想要使得颜色更亮/暗的时候，不能只调节V的变化，同时要根据光照走向去调节H，即HueShift，使得让颜色在更亮的时候更亮