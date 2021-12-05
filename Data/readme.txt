부도 정의 자료 정리

파일명에 kind_bankrupt가 포함되어있는 파일들은 부도에 대한 라벨링이 이뤄졌습니다.

kind_bankrupt.csv = 부도(감사의견코드, 해산/파산, 자본잠식, 은행거래정지)
kind_bankrupt_Final.csv = 부도(kind 시장조치 상장폐지 공시 00~20년 자료, 업종 - 전체)

Dataset.csv = ts2000에서 코스닥 기업 약 2000개에 대한 20년치 자료 (변수 약 270개, 결측치 처리 > padding, bfill, 0 순으로 진행)

kind_bankrupt_Final_ver2 = Dataset + kind_bankrupt_Final 를 결합한 파일입니다.

kind_bankrupt_Final_ver2 + 승한쓰가 뽑은 11개 변수 csv 파일을 합치면 1차적으로 최종 데이터셋이 완성됩니다.