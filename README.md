# BeatMaker
Creates a drum beat based on Machine Learning

# BeatMaker Plan

 Tensorflow를 이용하여 **장르별 비트라인을 생성해주는 프로그램** 개발
 
 프로젝트를 진행하기 앞서 우선 머신러닝에 대한 기초 이론 공부시간을 약 1달 정도 진행 

## 머신러닝 스터디

참여 인원에 따라 머신러닝 관련 책을 2-3권 구매,매주 1-2파트씩 내용 공유 및 정리하여 매주 토요일 오전까지 Git에 commit 진행\
모든 스터디는 항상 아웃풋 스터디가 기억에 가장 잘 남기 때문에 **스터디 기간 동안은 매주 만나 내용을 공유(각자 공부한 내용을 상대방에게 알려줌)**, 실제 프로젝트 시작시에는 필요에 따라 오프라인 모임 진행

내용 정리에 정해진 형식은 없지만 Git에서 보거나 외부에 노출되는 경우 Markdown으로 정리한 문서가 보기도 좋고 쓰기도 좋음 (이 문서도 Markdown)

**프로젝트 진행에 대한 일정은 아주 아주 러프하게 잡았음** \
스터디를 하면서 프로젝트에 대한 일정은 언제든지 변경될 수 있음

## 1차 프로젝트 (4월 말)

- 임의로 정의한 데이터를 Beat 소리로 변환하는 프로그램(Web || App) 개발  
    - 참고 사이트 : [Splice](https://splice.com/sounds/beatmaker/wakaflocka)
    - Beat <-> Data
    - 비트를 교육시키기 위해 Tensorflow에서 사용가능하며 패턴으로 인식하고 표현 할 수 있는 범위내  데이터를 임의의 규칙으로 생성
    - 그렇게 생성된 데이터를 소리로 바꾸는 프로그램
- 데이터로 변환된 비트를 교육시켜 결과물을 만드는 ML 프로젝트
    - 참고 블로그 : [기계 학습은 즐겁다 - Part 2](https://medium.com/@jongdae.lim/%EA%B8%B0%EA%B3%84-%ED%95%99%EC%8A%B5-machine-learning-%EC%9D%80-%EC%A6%90%EA%B2%81%EB%8B%A4-part-2-b35f3d327761)
    - 슈퍼마리오 레벨 디자인 참고
    - 기계 학습은 즐겁다 블로그는 1~8 파트로 작성되어 있음 모든 파트 다 읽어보면 아주 도움이 많이 되는 블로그

## 2차 프로젝트 (6월 말)
 - 오디오 파일(mp3, wav, mp4, m4a 등)을 읽어 비트를 데이터로 변환하는 프로그램 개발
    - 음원 사이트(멜론, 네이버 뮤직, 벅스 등)를 통해 동일 장르 음악 교육
    - 오디오 파일에서 비트를 텍스트로 변환하는 작업
- ML 프로젝트 리팩토링
    - 프로젝트 진행여부에 따라 많이 변경될 계획
