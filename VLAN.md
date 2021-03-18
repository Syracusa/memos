# VLAN



## Virtual LAN (VLAN)
프레임 태깅을 통해 실제 물리적 연결상태와 관계없이 L2 네트워크 범위 설정

## Private VLAN(port isolation)
스위치 포트를 주어진 uplink로만 통신할수 있게 만드는것

### Primary Vlan
 동일 Primary Valn, Secondary Vlan들과 통신가능
 Primary Vlan의 promiscuous포트를 통해 Secondary Vlan이 외부통신가능

### Secondary Vlan

* isolated vlan 

노드간 서로 통신 불가능, Primary Vlan 노드들과 통신가능
  
* community vlan

노드간 서로 통신 가능, Primary Vlan과도 통신가능

## tagged(trunk)/untagged port

* tagged port(trunk port)

VLAN 태깅된 프레임을 받는 포트, 서로 다른 VLAN의 프레임들을 모두 수신

* untagged port 

(switch->host)VLAN 태깅된 프레임을 받아 언태깅해서 host에 전달

(host->switch)VLAN 태깅되지 않은 프레임을 host로부터 받아 태깅해서 타 포트로 전달
