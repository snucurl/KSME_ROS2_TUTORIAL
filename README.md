# KSME_ROS2_TUTORIAL
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


## # 사용 편의성을 위한 툴
1. Terminator
```
$ sudo apt-get install terminator -y
$ terminator
```
2. gedit

```
$ sudo apt update
$ sudo apt install gedit
$ gedit
```
