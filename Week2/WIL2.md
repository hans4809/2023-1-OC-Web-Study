# 1주차 복습
- URI(Uniform Resource Identifier)
    + 프로토콜 + DNS 주소
        * DNS(Domain Name System) 주소 : IP 주소를 외우기 힘들고, 바뀔 수 있기 때문에 사용
- URN(Uniform Resource Name)
    + Resource를 찾기위한 이름
- URL(Uniform Resource Location)
    + Resource가 저장된 주소
- 서버
    + 사용자들에게 정보를 주기 위한 컴퓨터
- Resource
    + HTML : 자료 (뼈대)
    + CSS : UI(살과 옷)
    + javaScript : 제어


# 2주차 복습
- git 개념
    1. git은 분산형 버전 관리 시스템의 한 종류
    2. 버전 관리 : 이전에 있던 파일을 복사, 백업, 저장 등 수정을 거치는 과정을 말한다.
    3. 버전 관리의 이점 
        - 각 파일을 이전 상태로 되돌릴 수 있다
        - 시간에 따라 수정 내용을 비교해 볼 수 있다.
        - 파일을 잃어버리거나 잘못 고쳤을 때 쉽게 복구 가능.
- git의 구성요소
    - Local
        - Working Directory : 내가 작업하는 영역
        - Staging Area : Working Directory에서 Repository로 정보가 저장되기 전 준비 영역
        - Local Repository : 내 PC에 파일이 저장되는 개인 저장소
    - Remote
        - Remote Repository : 외부 저장소
- git의 명령어
    - add : Working Directory 폴더에 파일을 Staging Area로 올리는 명령어
        code > 
    - commit : Staging Area에 저장되어 있는 변경 사항들을 주석과 함께 Local Repository에 올리는 명령어
    - push : commit된 파일을 Remote Respository에 올리는 명령어
    * pull과 fetch의 차이점
        - pull : Remote Repository에서 변경된 데이터를 확인하고 최신 데이터를 복사하여 Local git에 가져옴
        - fetch : Remote Repository에서 변경된 데이터를 확인만 하고 최신 데이터를 Local git에 가져오지 않음
        - fetch를 사용하는 이유 : pull을 실행하면 현재 branch와 작업 복사본의 파일을 병경되는 동시에 새로 작업한 내용이 손실되는 일이 생김

# 선택 과제
    아직 진로를 확실히 정하지 않았어서 하나 씩 다 구글링을 했습니다. 그러면서 과제 설명에서 구글링이 왜 개발자의 기초라고 하셨는지 깨닫게 되었습니다.