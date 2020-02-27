# 젯슨 인퍼런스를 빌드하기 (Korean Version)
***
(1) 다운로드하기
```
git clone https://github.com/dusty-nv/jetson-inference
cd jetson-inference
git submodule update --init
```

(2) 빌드트리 설정하기
```
mkdir build
cd build
cmake ../
```

(3) 빌드하기
```
make 
sudo make install
sudo ldconfig
```

## 출처
![Jetson Zoo](https://elinux.org/Jetson_Zoo)
