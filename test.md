加密方法：
1.选定载体图片raw.png
2.制作带有我的学号和姓名的图片57117236.png
3.采用频域变换的隐藏方法加密得到带有秘密信息的图片
python encode.py --image raw.png --watermark 57117236.png --result test.png

解密方法：
通过原始图片raw.png和带有秘密信息的图片test.png一起解密出秘密信息图片output.png
python decode.py --image test.png --orig raw.png --result output.png
