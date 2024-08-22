```
gantt
    title Fuzzing Project Work Breakdown Structure
    dateFormat  YYYY-MM-DD
    section Beta Version Development (2024-07-24 to 2024-08-22)
    FInding Attack Surface with Parsing         :done, a1, 2024-07-24, 7d
    FInding Attack Surface with LLM             :done, a2, after a1, 7d
    Fine-tuning                                 :done, a3, after a2, 5d
    seed mutation                               :done, a4, after a3, 5d
    Secure Coding with LLM                      :done, a5, after a4, 7d
    Fuzzengine 개발                             :done, a6, after a5, 7d
    Fuzz target 취약한 웹페이지 개발             :done, a7, parallel with a5, 14d

    section Beta Version Improvement (2024-08-23 to 2024-09-12)
    LLM의 seed mutation 강화 및 초기 Seed 생성 알고리즘 수정 :active, b1, 2024-08-23, 10d
    Seed 생성 및 조정 특화 인공지능 모델 개발          :active, b2, after b1, 5d
    모델 검증                                    :active, b3, after b2, 5d
    모델 성능 비교                                :active, b4, after b3, 5d
    유효 크래시 판별 자동화 - selenium 활용        :active, b5, parallel with b4, 5d
    자동화 검증                                  :active, b6, parallel with b5, 5d
    code coverage 개발 및 디자인                  :active, b7, after b6, 5d
    report screen 개선                           :active, b8, parallel with b7, 5d
    Fuzz target 취약한 웹페이지 추가개발           :active, b9, parallel with b7, 10d

    section Documentation (~2024-09-12)
    개발문서 작성                               :crit, c1, 2024-09-05, 7d
    코드검증 및 코드컨벤션 작성                   :crit, c2, parallel with c1, 7d
    업무 메뉴얼 작성                             :crit, c3, parallel with c1, 7d
```
