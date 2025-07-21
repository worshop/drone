## MAVlink 란?

MAVLink(마브링크)는 드론이나 무인 시스템 같은 로봇 플랫폼에서 데이터를 주고받기 위해 사용하는 통신 프로토콜
Mavlink  메시지들은 드론, 비행 컨트롤러, 지상 제어 스테이션(GCS) 간에 표준화된 방식으로 정보를 전달하는 데 사용

# MAVlink 의 특징
1. 매우 효율적임 • MAVLink1-패킷당 8byte, MAVLink2-패킷당 14byte 
2. XML 파일을 사용하여 메시지를 저장함 
3. 다양한 프로그래밍 언어로 라이브러리를 생성할 수 있음 
4. 네트워크에서 최대 255개의 동시 시스템을 허용함 5 MAVLink1, MAVLink2의 2가지 Protocol이 있음

# MAVLink Project Generators/Languages
MAVLink 조직은 mavgen , mavgenerate 및 rust-mavlink 도구를 제공(지원)합니다.


# mavlink1 과 mavlink2 비교
<img width="1336" height="507" alt="image" src="https://github.com/user-attachments/assets/e92a2911-d9d9-43df-8986-fb45598b8f86" />

공식사이트 https://mavlink.io/en/
