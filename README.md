# Computer Architecture (컴퓨터 구조)
## 2022 가을학기, 한림대학교 정보과학대학 소프트웨어학부 
*  *  *

## [알림] Github 수업 페이지 오픈
## 질문은 [Issues] 생성을 이용해주세요!
## 참고 자료
### [2020년 컴퓨터구조 수업 실습 수업 동영상](https://www.youtube.com/watch?v=qeiRKwbtlNc&list=PLKZ28p5qq0DHfv7eadlsr3OVkCzeVGbcx)
### [Logisim을 이용한 논리 회로 실습 지원 동영상 개발](https://www.youtube.com/playlist?list=PLKZ28p5qq0DGBY8ZUcYDZcvjCojZQJCQV)

*  *  *

> 본 수업에서는 현대의 컴퓨터에 대한 내부적인 구조를 배우게 됩니다. 컴퓨터 내부 구조에 대한 이해는 컴퓨터 프로그래밍을 배울 때 최적화된 코드를 작성할 수 있도록 도와줄 것입니다. 본 수업에서는 특히 [MIPS](https://ko.wikipedia.org/wiki/MIPS_%EC%95%84%ED%82%A4%ED%85%8D%EC%B2%98) 프로세서 구조에 대해서 배우게 되며, MIPS 프로세서에서 사용되는 어셈블리 언어를 어셈블리 시뮬레이터인 [QtSpim](http://spimsimulator.sourceforge.net/) 실습을 통해 배우게 될 것입니다. 
> MIPS 프로세서의 구조 이해를 향상시키기 위하여 [LogiSim](http://www.cburch.com/logisim/) 시뮬레이션 도구를 활용하여 설계하고 동작을 확인합니다.
>본 수업은 인텔이 제공하는 대학지원 프로그램의 지원을 받는 교과목으로 산업체가 요구하는 교육 내용을 전달하고 있습니다.
>
>  - 실습**
>     - MIPS 프로세서의 어셈블리 언어 시뮬레이션을 위해 오픈소스 소프트웨어인 "**[MIPS 어셈블러 시뮬레이터:QtSpim](http://spimsimulator.sourceforge.net/)**"를 사용합니다.
>     - 오픈소스 시뮬레이터인 [LogiSim](http://www.cburch.com/logisim/) 시뮬레이터를 이용한 MIPS 프로세서 구조 설계 및 확인
>
>  - 주요 학습 내용:
>     - Computer Architecture and Assembly Language
>     - Microarchitecture for MIPS Microprocessors
>     - Memory Architecture including cache architectures
>


*  *  *

## 강의 스탭
### 담당교수: [이정근](https://sites.google.com/site/embeddedsochallymuniv/esoc/jeonggunlee) (소프트웨어융합대학)
   - 연구실:(성호관 A1201호실) / Email: Jeonggun.Lee (AT) gmail.com
   - 전화번호: 033-248-2313 (연구실)
   - 홈페이지: [http://www.onchip.net](https://sites.google.com/site/embeddedsochallymuniv/home)

### 담당조교: 김동영
   - (Email: dongyoung0218@gmail.com, 연구실: 성호관 1211 임베디드 SoC 연구실)
   
## 교재
   - 주교재: "[디지털논리와 컴퓨터설계](http://www.yes24.com/Product/Goods/24799862?OzSrank=3)," 데이비드 해리스,사라 해리스 공저/강영흥, 박춘명, 지석근, 황지원 공역 | 카오스북.
   
## 평가방법
   - 중간 - 35%
   - 기말 - 35%
   - 실습:숙제&퀴즈 - 30%
   - 결석 3회 이상 "F"
   

## 강의 스케줄 및 자료/노트

- 1주차:
   - 동영상: 컴퓨터구조 개론
   - Github 수업 정보 페이지 소개
   - 동영상: 컴퓨터구조 실습: QtSPIM 설치와 실행
   - MIPS 어셈블리 언어에 대한 좋은 사이트 소개
- 2주차:
   - 동영상: 제 6 장 Architecture - 어셈블리 언어 - 01
   - 동영상: 제 6 장 Architecture - 어셈블리 언어 - 02
   - 동영상: 제 6 장 Architecture - 어셈블리 언어 - 03
   - 동영상: 컴퓨터구조 실습 1 - Hello World! 프린트
   - *과제* 자신의 영문이름을 프린트 하는 MIPS 에셈블리 코드를 작성
   - 퀴즈2주차
   - 파일6장 ppt 자료
- 3주차:
   - 동영상: 제 6 장 Architecture - 명령어 타입 및 기계어 코드 01
   - 동영상: 제 6 장 Architecture - 명령어 타입 및 기계어 코드 02
   - 동영상: 컴퓨터구조 실습 02
   - 동영상: 컴퓨터구조 실습 03
   - *과제* QtSPIM이 사용하는 Endian 찾기
- 4주차: Shift 명령어의 수행, 상수 만들기, 곱셈 명령어의 사용
   - 동영상: 4주차 컴퓨터 구조 수업 이론 01
   - 동영상: 4주차 컴퓨터 구조 수업 이론 02
   - 동영상: 4주차 컴퓨터 구조 수업 실습 01
   - 동영상: 4주차 컴퓨터 구조 수업 실습 02
   - 퀴즈4주차 퀴즈
- 5주차: 어셈블리언어를 이용한 프로그래밍 언어의 구조: If-then-else, for, while 등, Array 구조 
   - 동영상: 5주차 컴퓨터구조 이론 강의 - 01
   - 동영상: 5주차 컴퓨터구조 이론 강의 - 02
   - 동영상: 5주차 컴퓨터구조 실습 강의 - 01
   - 동영상: 5주차 컴퓨터구조 실습 강의 - 02
   - *과제* 배열과 For 문장을 고려한 코드 작성하기과제
- 6주차: 프로시저 콜 및 스택의 구조
   - 동영상: 6주차 컴퓨터구조 이론 수업 01
   - 동영상: 6주차 컴퓨터구조 이론 수업 02
   - 동영상: 6주차 컴퓨터구조 실습 수업 01
   - *과제* MIPS: 프로세셔 콜 구현하기!
- 7주차:
   - 동영상중간고사 대비 과거 시험 문제 풀이
   - 파일과거 시험문제 모음파일
   - 동영상1 중간고사 대비 Q&A
   - 동영상2 중간고사 대비 Q&A
- 8주차: 중간고사
- 9주차: Single Cycle 마이크로프로세서 구조의 이해 1
   - 동영상: 9주차_7장_마이크로 아키텍쳐 1
   - 동영상: 9주차_7장_마이크로 아키텍쳐 2
   - 동영상: 9주차 컴퓨터구조 실습 강의
   - Logisim 학습 보조 자료
   - 파일7장 마이크로아키텍쳐 PPT 자료
   - *과제* Program Counter 만들기!
- 10주차: Single Cycle 마이크로프로세서 구조의 이해 2
   - 동영상: 10주차 컴퓨터구조 01
   - 동영상: 10주차 컴퓨터구조 - 02
   - 파일레지스터 파일 설계 로지심 회로
   - 퀴즈10주차 퀴즈
- 11주차: MIPS 프로세서 만들기 1 - 프로그램 카운터와 명령어 메모리
   - 동영상: 11주차 컴퓨터구조 이론-실습 통합 01
   - 동영상: 11주차 컴퓨터구조 이론-실습 통합 02
   - 파일32 비트 ALU 회로파일
   - 파일레지스터 화일파일
   - *과제* 수업에서 만든 Load Word 명령어를 위한 MIPS를 설계해주세요.
- 12주차: MIPS 프로세서 만들기 2 - 명령어의 실행 흐름 및 데이터 메모리 설계 
   - 동영상: 12주차 컴퓨터구조 이론 01
   - 동영상: 12주차 컴퓨터구조 이론 02
   - 동영상: 12주차 컴퓨터구조 실습 01
   - 동영상: 12주차 컴퓨터구조 실습 02
   - 파일Data Memory (데이터메모리) Logisim File파일
   - 파일수정된 ALU 설계 파일 (Zero 플래그 포함)
   - *과제* 수업에서 만든 MIPS Datapath를 설계해주세요.
- 13주차: MIPS 프로세서 만들기 3 - 프로세서 데이터패스 제어회로 설계
   - 동영상: 13주차 컴퓨터구조 이론 01
   - 동영상: 13주차 컴퓨터구조 이론 02
   - 동영상: 13주차 컴퓨터구조 실습 01
   - 동영상: 13주차 컴퓨터구조 실습 02
   - 파일ALU Decoder 로지심 화일파일
   - *과제* 수업에서 만든 MIPS 프로세서를 완성해주세요!
- 14주차: MIPS 프로세서 만들기 4 - 마이크로 프로세서의 성능 평가
   - 동영상: 14주차 컴퓨터구조 수업 이론
   - 동영상: 14주차 컴퓨터구조 실습
   - 동영상: 14주차 컴퓨터구조 실습
   - 파일7 세그먼트 제어를 위한 비트폼 정보파일
   - 파일최종 MIPS 프로세서 설계 화일파일
   - *과제* 7세그먼트에 3과 4를 프린트해주세요!
   - 동영상: 기말고사 대비 문제풀이 동영상 수업
- 15주차: 메모리 구조 및 캐쥐
   - 8장 메모리 구조 및 캐쉬 (PPT 자료)
   - 수업 관련 설문설문조사
- 16주차:
   - 기말고사

   
## 실습
   ![Alt text](https://github.com/jeonggunlee/Computer_Arch_2018_Fall/blob/master/img/openss.png "오픈소스교과목")
   - 실습 소프트웨어로써, **[LogiSim](http://www.cburch.com/logisim/)** 논리회로 설계 및 시뮬레이터를 사용합니다.
      - Logisim은 Open Source Software이며, 누구나 자유롭게 사용가능하며, 소스코드 역시 오픈되어 있고 수정 가능합니다.
         - It is free! (Logisim is open-source (GPL).)
         
   ![Alt text](http://www.cburch.com/logisim/shot-2.7.0.png)         
   
   - MIPS 어셈블리 명령어에 대한 기계어 코드를 생성: http://www.kurtm.net/mipsasm/ 

## 참조 사이트
   - 참조 사이트
   - [한림대학교 오픈소스 SW 교육센터](https://github.com/Hallym-OpenSourceSW/Hallym-OpenSourceSW.github.io)
   

