## # ROS2 주요 개념

[ROS2 Documentation: Humble](https://docs.ros.org/en/humble/index.html)   

## DDS
- ROS2에서는 OMG(Object Management Group)에 의해 표준화된 DDS(Data Distribution Service)의 RTPS(Real Time Publish Subscribe)를 사용하여 실시간 데이터 전송을 보장
- ROS2의 상업적 용도 발판
- 노드 간의 데이터 통신 조정하는 QoS(Quality of Service) 설정으로 TCP처럼 데이터 손실 방지로 신뢰도를 높이거나 UDP처럼 통신 속도를 우선시 할 수 있음
- ROS2의 미들웨어(RMW ROS Middleware)
- 운영체제 독립
- 언어 독립
- 동적검색(Dynamic Discovery)
- 보안 강화

```
echo $ROS_DOMAIM_ID
export ROS_DOMAIN_ID=8
```

## 노드, 토픽, 서비스, 액션, 파라미터, 패키지

## Underlay vs Overlay
- underlay(apt 설치 ROS): /opt/ros/humble/
- overlay(사용자 빌드 workspace): ~/robot_ws/

## # Visual Studio Code(IDE) 설치
1. [https://code.visualstudio.com/Download](https://code.visualstudio.com/Download)   
2. .deb(Debian, Ubuntu) 선택하여 다운로드
3.  다운로드한 폴더로 이동($ cd ~/Downloads)
4. 다운로드 받은 파일을 설치
```
sudo dpkg -i code code_1.109.5-1771531656_amd64.deb
```
5.  작업을 원하는 폴더로 이동 후 실행
6. VScode 화면에서 Extensions를 선택하여 필요 확장팩을 설치
C/C++
ROS
CMake
CMake Tools
XML
Python
autoDocstring - Python Docstrin
```
cd ~/robot_ws/src
code .
```
## # 사용 편의성을 위한 툴
1. Terminator
```
sudo apt-get install terminator -y
terminator
```
2. gedit
- 우분투 Desktop에서 사용
```
sudo apt update
sudo apt install gedit
gedit
```
- 우분투 server에서는 nano 사용 권장

```
sudo nano .bashrc
```
