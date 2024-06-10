#### **图片测试demo:**
直接运行detect_plate.py 或者运行如下命令行：
```
python detect_plate.py --detect_model weights/plate_detect.pt  --rec_model weights/plate_rec_color.pth --image_path imgs --output result
```
测试文件夹imgs，结果保存再 result 文件夹中

视频测试demo  [2.MP4]

素材与labelme：
链接：https://pan.baidu.com/s/1LZHrsfyvJyX3AFj9uazqdQ?pwd=nnj3 
提取码：nnj3 
--来自百度网盘超级会员V7的分享

```
python detect_plate.py --detect_model weights/plate_detect.pt  --rec_model weights/plate_rec_color.pth --video 2.mp4
```
视频文件为2.mp4  结果保存为result.mp4
#### **支持如下：**

- [X] 1.单行蓝牌
- [X] 2.单行黄牌
- [X] 3.新能源车牌
- [X] 4.白色警用车牌
- [X] 5.教练车牌
- [X] 6.武警车牌
- [X] 7.双层黄牌
- [X] 8.双层白牌
- [X] 9.使馆车牌
- [X] 10.港澳粤Z牌
- [X] 11.双层绿牌
- [X] 12.民航车牌
