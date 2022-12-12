### pwd: shows the current path in a hierarchical directory 

### cd: change directory

### ls: list files and directories
#### More on ls

```sh
ls /bin List diles in the /bin directory (or any other directory we care to sperify)
ls -l List the files in the working directory in long format
ls -l /etc/bin List the files in the /bin directory and the /etc directory in long format
ls -la .. List all files
```
### Shell command: clear
### cp: copy files and directories
#### More on  cp
```sh
cp file1 file2 copies the contents of file1 into file2. If file2 does not exist, it is created; otherwise, file2 is silently overwritten with the contents of file1.
cp -i file1 file2 Like above however,since the "-i"(interactive) option is sepcified, if file2 exists, the user is prompted before it is overwritten with the contents of file1.
cp file1 dir1 Copy the contents of file1 (into a file names file1)inside of directory dir1
cp -R dir1 dir2 Copy the contents of the directory dir1. If directory dir2 does not exist, it is created. Otherwise, it creates a directory names dir1 within directory dir2.
```
### mv: move files and directories or rename them
```sh
mv file1 file2 If file2 does not exist, then file1 is renamed file2. If file2 exists, its contents are silently replaced with the contents of file1.
mv -i file1 file2 Like above however, since the "-i"(interactive)option is sepcified, if file2 exists, the user is prompted before it is overwritten with the contents of file1.
mv file1 file2 dir1 The files file1 and file2 are moved to directory dir1. If dir1 does not exists, mv will exit with an error.
mv dir1 dir2 If dir2 does not exist, then dir1 is renames dir2. If dir2 exists, the directory dir1 is moved within directory dir2.
```
rm: delete files and directories
```sh
rm file1 file2 Delete file1 and file2.
rm -i file1 file2 Like above however, since the "-i"(interactive) option is specified, the user is prompted before each file is deleted.
rm -r dir1 dir2 Directories dir1 and dir2 are deleted along with all of their contents.
```
### mkdir: make a new directory
### Manipulation: Wildcards
### Help command: help,men
### exit

## 프로젝트 개요
opencv, dilb,face-recognition을 활용하여 영상,사진,웹캠에서 얼굴인식이 가능하게 만들었다.


얼굴인식을 영화 수리남에 활용하여 극중 쥐새끼인 배우 유인석을 다른 배우들과 구분하여 Mouse로 찾게 만들었다.

## face-recognition in image
![image output.jpeg](https://github.com/standardstone/standardstone/blob/main/image%20output.jpeg)


## face-recognition in video
![video output.gif](https://github.com/standardstone/standardstone/blob/main/video%20output.gif)


## face-recognition in webcam
![screenshot output.png](https://github.com/standardstone/standardstone/blob/main/screenshot%20output.png)


## Download Models
- [shape_predictor_68_face_landmarks.dat.bz2](https://github.com/davisking/dlib-models/raw/master/shape_predictor_68_face_landmarks.dat.bz2)
- [dlib_face_recognition_resnet_model_v1.dat](https://github.com/kairess/simple_face_recognition/raw/master/models/dlib_face_recognition_resnet_model_v1.dat)

## 필요 패키지
- Python 3+
- dlib
- OpenCV
- face_reconition
- numpy
- matplotlib (for visualization)


## 실행방법

### image,video
-dlib과opencv,패키지를 pip를 사용하여 설치해준다.


-shape_predictor_68_face_landmarks.dat.bz2,dlib_face_recognition_resnet_model_v1.dat을 다운로드 받아 압축해제 후 파이썬 코드가 있는 위치로 복사해준다.


-실행시켜준다.

### webcam
-face_recognition과 opencv 패키지를 pip 사용하여 설치해준다.


-실행시켜준다.

## 참고자료 
[kairess/simple_face_recognition](https://github.com/kairess/simple_face_recognition)


[ageitgey/face_recognition](https://github.com/ageitgey/face_recognition)
