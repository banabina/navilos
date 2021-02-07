# navilos
임베디드 OS 개발 프로젝트 Navilos 만들어보기  
실습 환경 : ubuntu 20.04 LTS

## github page
https://github.com/navilera/Navilos

## 개발 환경 구성하기
```
sudo apt-get update
sudo apt-get upgrade
```
### 1. 컴파일러 설치하기
```
sudo apt-get install gcc-arm-none-eabi
```

설치 확인
```
arm-none-eabi-gcc -v
```

### 2. QEMU 설치하기
```
sudo apt-get install qemu-system-arm
```

설치 확인
```
qemu-system-arm --version
```

### p21 arm-none-eabi-gdb 설치 안되는 경우
gdb-multiarch를 설치
```
sudo apt-get update -y
sudo apt-get install -y gdb-multiarch
gdb-multiarch
```

**Reference**
https://devtak0623.medium.com/os-arm-none-eabi-gdb-%EC%84%A4%EC%B9%98-%EB%AC%B8%EC%A0%9C-3fbc8bcce7c1
