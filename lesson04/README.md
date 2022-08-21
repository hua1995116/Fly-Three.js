# 细数实现全景图VR的几种方式（panorama/cubemap/eac）/ 一起来实现全景图 VR 吧！

相关代码命令
```
ffmpeg -i example.jpg -vf v360=input=equirect:output=eac example-eac.jpg
ffmpeg -i example.jpg -vf v360=input=equirect:output=c3x2 example-cube.jpg
```

加速博客地址：[https://qiufeng.blue/three/lesson04.html](https://qiufeng.blue/three/lesson04.html)

demo体验：

panorama: https://fly-three-js.vercel.app/lesson04/index-panorama.html

[![Edit hungry-wave-94vezw](https://codesandbox.io/static/img/play-codesandbox.svg)](https://codesandbox.io/s/hungry-wave-94vezw?fontsize=14&hidenavigation=1&theme=dark)

cube: https://fly-three-js.vercel.app/lesson04/index-cube.html

[![Edit cool-https-563g0f](https://codesandbox.io/static/img/play-codesandbox.svg)](https://codesandbox.io/s/cool-https-563g0f?fontsize=14&hidenavigation=1&theme=dark)

eac: https://fly-three-js.vercel.app/lesson04/index-eac.html






