# ETP-Release

Enterphin IDE Release and Update Log Repository.

## Update History

### v0.0.11 [18/04/27]

- 자동완성 저절로 꺼지는 버그 수정
- 인터럽트 핀 추가
- 라이브러리 추가
  - 버저 모듈 (HW-508)
  - 진동센서 모듈 (801S)

### v0.0.10 [18/04/26]

- 라이브러리 추가
  - 블루투스 모듈 (HC06)
  - 도트매트릭스 모듈 (MAX7219)
  - 터치센서 모듈 (TTP223B)
  - 자이로 모듈 (MPU6050)
- 콘솔 텍스트 드래그 기능
- 업로드할 때 시리얼통신 정지

### v0.0.9 [18/04/24]

- 추가한 하드웨어 제거 기능
- Explorer Area UI 수정

### v0.0.8 [18/04/23]

- 코드 자동완성 기능 추가

### v0.0.7 [18/04/20]

- 라이브러리 설정파일 및 코드 자동생성 구조 변경
- 코드 입력시 커서가 맨 밑으로 이동하는 버그 수정

### v0.0.6 [18/04/19]

- 코드 작성 및 자동생성 방식 변경
- 라이브러리 관련부분 모듈화

### v0.0.5 [18/04/18]

- 시리얼 통신 기능 추가

  - ```c++
    ex) Serial.println("some text");
    ```

- 아두이노 호환보드 (CH340 chip) 포트 인식 지원

### v0.0.4 [18/04/17]

- Button Interrupt 함수에 분기 추가
- 아두이노 연결된 포트 인식

### v0.0.3 [18/04/17]

- Build & Upload 결과 콘솔에 출력
- COM Port 선택기능

### v0.0.2 [18/04/16]

- 자동 업데이트 테스트

### v0.0.1 [18/04/16]

- 하드웨어(모듈, 소자 등) 추가 기능
- 하드웨어 세팅부분 코드 자동 생성
- 빌드 & 업로드