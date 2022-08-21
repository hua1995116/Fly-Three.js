# 细数实现全景图VR的几种方式（panorama/cubemap/eac）/ 一起来实现全景图 VR 吧！

相关代码命令
```
ffmpeg -i example.jpg -vf v360=input=equirect:output=eac example-eac.jpg
ffmpeg -i example.jpg -vf v360=input=equirect:output=c3x2 example-cube.jpg
```

加速博客地址：[https://qiufeng.blue/three/lesson04.html](https://qiufeng.blue/three/lesson04.html)

demo体验：

cube: https://fly-three-js.vercel.app/lesson04/index-cube.html

eac: https://fly-three-js.vercel.app/lesson04/index-eac.html

panorama: https://fly-three-js.vercel.app/lesson04/index-panorama.html
