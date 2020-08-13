# Computer Architecture (컴퓨터 구조)
## 2020 가을학기, 한림대학교 소프트웨어융합대학 
*  *  *

## [알림] Github 수업 페이지 오픈
## 질문은 [Issues] 생성을 이용해주세요!
## [논리 회로 실습을 위한 동영상 개발](https://www.youtube.com/playlist?list=PLKZ28p5qq0DGBY8ZUcYDZcvjCojZQJCQV)

*  *  *

> 본 수업에서는 현대의 컴퓨터에 대한 내부적인 구조를 배우게 됩니다. 컴퓨터 내부 구조에 대한 이해는 컴퓨터 프로그래밍을 배울 때 최적화된 코드를 작성할 수 있도록 도와줄 것입니다. 본 수업에서는 특히 [MIPS](https://ko.wikipedia.org/wiki/MIPS_%EC%95%84%ED%82%A4%ED%85%8D%EC%B2%98) 프로세서 구조에 대해서 배우게 되며, MIPS 프로세서에서 사용되는 어셈블리 언어를 어셈블리 시뮬레이터인 [QtSim](http://spimsimulator.sourceforge.net/) 실습을 통해 배우게 될 것입니다. 
> MIPS 프로세서의 구조 이해를 향상시키기 위하여 [LogiSim](http://www.cburch.com/logisim/) 시뮬레이션 도구를 활용하여 설계하고 동작을 확인합니다.
>본 수업은 인텔이 제공하는 대학지원 프로그램의 지원을 받는 교과목으로 산업체가 요구하는 교육 내용을 전달하고 있습니다.
>
>  - 실습**
>     - MIPS 프로세서의 어셈블리 언어 시뮬레이션을 위해 오픈소스 소프트웨어인 "**[MIPS 어셈블러 시뮬레이터:QtSim](http://spimsimulator.sourceforge.net/)**"를 사용합니다.
>     - 오픈소스 시뮬레이터인 [LogiSim](http://www.cburch.com/logisim/) 시뮬레이터를 이용한 MIPS 프로세서 구조 설계 및 확인
>
>  - 주요 학습 내용:
>     - Computer Architecture and Assembly Language
>     - Microarchitecture for MIPS Microprocessors
>     - Memory Architecture including cache architectures
>
>  - 이론은 동영상 강의 등을 통한 비대면 강의로 진행되면, 실습은 원활한 진행을 위하여 대면으로 진행됩니다.
>
>  - 이론수업이 비대면 강의로 진행되는 많큼 교수 및 학생간의 신뢰 유지를 위해서 함께 노력해주시기 바랍니다.
>     - 상황에 따라 자율 출석 및 무감독 시험 평가가 진행될 수 있습니다 (교수 - 학생간 조율에 의해서 평가 항목 및 방법 변경가능).
> 


*  *  *

## 강의 스탭
### 담당교수: [이정근](https://sites.google.com/site/embeddedsochallymuniv/esoc/jeonggunlee) (소프트웨어융합대학)
   - 연구실:(성호관 1306호실) / Email: Jeonggun.Lee (AT) gmail.com
   - 전화번호: 033-248-2312 (연구실)
   - 홈페이지: [http://www.onchip.net](http://www.onchip.net)
<img src="https://sites.google.com/site/embeddedsochallymuniv/_/rsrc/1307936693055/esoc/jeonggunlee/jglee.JPG" height="200" width="162">

### 담당조교: 김동영
   - (Email: dongyoung0218@gmail.com, 연구실: 성호관 1211 임베디드 SoC 연구실)
   
## 교재
   - 주교재: "[디지털논리와 컴퓨터설계](http://www.yes24.com/24/goods/3311366)," 데이비드 해리스,사라 해리스 공저/조영완 등역, 사이텍미디어
   
## 평가방법
   - 중간 - 35%
   - 기말 - 35%
   - 실습:숙제&퀴즈 - 30%
   - 결석 3회 이상 "F"
   

## 강의 스케줄 및 자료/노트

  - **CHAPTER 6 구조**
     - 6.1 소개
     - 6.2 어셈블리어 / - 6.3 기계어
     - 6.4 프로그래밍 / - 6.5 어드레싱 모드

     - 1주차: 수업 소개 - 왜 컴퓨터 구조를 공부해야할까 ?
         - 인공지능, IoT (사물인터넷) 시대에 논리회로 및 컴퓨터 구조에 대한 이해는 왜 필요한가?
         - Cloud 컴퓨팅 회사들은 왜 하드웨어 칩을 데이터 센터에 집적하는 것일까 ?
         
            - [자료:인공지능 시대, 인공지능 하드웨어의 현재 상황](https://blog.lgcns.com/1804)
            ```
            최근 데이터 센터에서는 GPU, FPGA, ASIC 형태의 가속기를 서버에 장착 ... 된 프로세서 칩으로 빅데이터 시대에
            엄청난 양의 연산이 필요한 데이터 ...
            
            * GPU : Graphic Processing Unit
            * FPGA : Field Programmable Gate Array
            * ASIC : Application Specific Integrated Circuit
            ```
            
            ```
            빅데이터 및 인공지능이 이 사회에 대두될 수 있었던 것은 고성능 컴퓨팅이 지원했기 때문이며,
            이러한 고성능 컴퓨터는 빠르게 발전한 CPU 및 GPU 등이 없었으면 불가능. 
            ```
            - [동영상:네이버 클라우드 플랫폼의 CPU Intensive 서버](https://www.youtube.com/watch?v=o0fSu1iErGI)
            - 고성능 가속기 데모: 인텔® Movidius **Neural Compute Stick** 2
               - [동영상:Deep Learning with Intel](https://www.youtube.com/watch?time_continue=343&v=KuM67WfTXBQ): 프로젝트에 딥러닝을 쉽게 활용하는 방법에 대해서 설명



  - **CHAPTER 7 마이크로아키텍처**
     - 7.1 서론
     - 7.2 성능 해석
     - 7.3 단일 사이클 프로세서 / - 7.4 다중 사이클 프로세서 / - 7.5 파이프라인 프로세서

  - **CHAPTER 8 메모리와 입출력 시스템**
     - 8.1 서론
     - 8.2 메모리시스템 성능 해석
     - 8.3 캐시 / - 8.4 가상 메모리

   
## 실습
   ![Alt text](https://github.com/jeonggunlee/Computer_Arch_2018_Fall/blob/master/img/openss.png "오픈소스교과목")
   - 실습 소프트웨어로써, **[LogiSim](http://www.cburch.com/logisim/)** 논리회로 설계 및 시뮬레이터를 사용합니다.
      - Logisim은 Open Source Software이며, 누구나 자유롭게 사용가능하며, 소스코드 역시 오픈되어 있고 수정 가능합니다.
         - It is free! (Logisim is open-source (GPL).)
         
   ![Alt text](http://www.cburch.com/logisim/shot-2.7.0.png)         
      

## 참조 사이트
   - 참조 사이트
   - [한림대학교 오픈소스 SW 교육센터](https://github.com/Hallym-OpenSourceSW/Hallym-OpenSourceSW.github.io)
   

