# UE4.25_RPG

 3주차 구현

 playercontroller: 캐릭터 교체시 카메라가 등뒤로 초기화 되어버리는 오류를 onpossess시 컨트롤러의 rotation이 초기화 되는것을 막아 정상화
 
 playercontroller : 한개의 캐릭터가 이동을 하는동안 다른 캐릭터들을 같은 위치로 이동하도록 수정
                   playercontroller 단에 필요한 스탯을 가지는 controllerstate 컴포넌트 제작

 character : 필요한 스탯이 있는 attribute컴포넌트와 상태가 있는 state 컴포넌트 제작
            에셋을 모두 구하기 전에 테스트할 마네킹의 이동 애니메이션 인스턴스 제작

 다음주차 구현 

 character : 캐릭터의 스킬에 대한 설계 -> 스킬에 필요한 데이터를 담는 데이터 테이블 설계
 
 gamemode : 멀티플레이를 위한 리슨서버 구현 및 rpc, replicate 설정
