# Canvas-DrawImage
a demo about the usage of drawImage method

在用canvas的drawImage方法时,发现参数有点多，使用起来不是特别好理解，所以简单整理了下常见的几种用法


官方这么形容的：

To draw images onto the canvas, the drawImage method can be used.

This method can be invoked with three different sets of arguments:

drawImage(image, dx, dy)
drawImage(image, dx, dy, dw, dh)
drawImage(image, sx, sy, sw, sh, dx, dy, dw, dh)

...

The source rectangle is the rectangle whose corners are the four points (sx, sy), (sx+sw, sy), (sx+sw, sy+sh), (sx, sy+sh).

...

The destination rectangle is the rectangle whose corners are the four points (dx, dy), (dx+dw, dy), (dx+dw, dy+dh), (dx, dy+dh).


还是不好理解，配上官方的这个图就很好理解了

<img src="images/drawImage.png">

```
drawImage() 方法在画布上绘制图像、画布或视频。
```