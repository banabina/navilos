# navilos
임베디드 OS 개발 프로젝트 Navilos 만들어보기
실습 환경 : wsl2 ubuntu 20.04 LTS

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