# VLAN



## Virtual LAN (VLAN)
프레임 태깅을 통해 실제 물리적 연결상태와 관계없이 L2 네트워크 범위를 설정하는 것

## Private VLAN(port isolation)
스위치 포트를 주어진 uplink로만 통신할수 있게 만드는 것

### Primary VLAN
 동일 Primary VLAN, Secondary VLAN들과 통신가능
 Primary VLAN의 promiscuous포트를 통해 Secondary VLAN이 외부통신가능

### Secondary VLAN

* isolated VLAN 

노드간 서로 통신 불가능, Primary VLAN 노드들과 통신가능
  
* community VLAN

노드간 서로 통신 가능, Primary VLAN과도 통신가능

## tagged(trunk)/untagged port

* tagged port(trunk port)

host가 VLAN 태깅된 프레임을 받는 포트, 스위치 내 서로 다른 VLAN의 프레임들을 모두 수신한다.

(switch->host) VLAN 태깅된 프레임을 호스트로 전달함

(host->switch) VLAN 태깅된 프레임을 스위치로 전달함


* untagged port 

host가 VLAN 태깅되지 않은 프레임을 받는 포트, 호스트는 VLAN의 존재를 모른다.

(switch->host)VLAN 태깅된 프레임을 받아 언태깅해서 host에 전달함

(host->switch)VLAN 태깅되지 않은 프레임을 host로부터 받아 태깅해서 타 포트로 전달함
