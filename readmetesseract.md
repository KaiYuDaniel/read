# tesseract
## 安装tesseract
sudo pip install PIL

could not find a version that satisfies the requirement PIL.(form versions:)
No matching distribution found for PIL.

sudo pip install Pillow
Pillow模块代替了PIL

安装图片支持格式：
brew install libpng
brew install jpeg
brew install libtiff

安装leptonica:
brew install leptonica

安装tesseract:
brew install tesseract

安装pytesseract库
sudo pip install pytesseract

## 使用tesseract
tesseract imagename outputbase [-l lang]

eg. tesseract mypic.jpg output -l eng
检测mypic.jpg中的英文字符与数字，存放在out.txt

## other
[Tessdata repository](https://github.com/tesseract-ocr/tessdata)

git is fooooo