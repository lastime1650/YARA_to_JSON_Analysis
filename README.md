# YARA_to_JSON_Analysis
Save the analysis using "YARA" to JSON.
# YARA모듈기반 분석 도구 개발
YARA는 rule 기반으로 binary 정보를 탐색하여 정해진 규칙에 따라 일치한 지 검사합니다. 
YARA를 도입하려는 경우, 쉽고 빠르게 Threading을 통해 "비동기"적으로 분석을 수행하고, JSON으로 결과를 queue에 반환하는 작업을 합니다.  

# 구성
1. [대표 yara모듈기반 분석 python 코드](https://github.com/lastime1650/YARA_to_JSON_Analysis/blob/main/codes/Intelligence_Analyzer.py)
2. [rules(from the github)](https://github.com/lastime1650/YARA_to_JSON_Analysis/blob/main/codes/Yara_rules.zip)
3. [.yar 경로를 Root에서부터 쭉 하위까지 스캔하는 코드](https://github.com/lastime1650/YARA_to_JSON_Analysis/blob/main/codes/File_Manager.py)

# 사용 방법
[Intelligence_Analyzer.py](https://github.com/lastime1650/YARA_to_JSON_Analysis/blob/main/codes/Intelligence_Analyzer.py)를 실행하기전에, [zip파일](https://github.com/lastime1650/YARA_to_JSON_Analysis/blob/main/codes/Yara_rules.zip)을 해제하고, Python코드에서 적절히 코드를 환경에 맞게 수정하여 사용합니다.
또한 [.yar 경로를 Root에서부터 쭉 하위까지 스캔하는 코드](https://github.com/lastime1650/YARA_to_JSON_Analysis/blob/main/codes/File_Manager.py)를 다운하여, 적절히 import를 하는 것 잊지 마시구요!

# 설명
![initial](https://github.com/lastime1650/YARA_to_JSON_Analysis/blob/main/images/image1.png)

## [비동기 생성 메서드](https://github.com/lastime1650/YARA_to_JSON_Analysis/blob/56b43daa71f9234a69308dfb70d1aa443410e81b/codes/Intelligence_Analyzer.py#L22)
![initial](https://github.com/lastime1650/YARA_to_JSON_Analysis/blob/main/images/image2.png)


## [Running메서드](https://github.com/lastime1650/YARA_to_JSON_Analysis/blob/ec209cbda567f62b53f4e97e977e6f9afbe033fb/codes/Intelligence_Analyzer.py#L30)
![initial](https://github.com/lastime1650/YARA_to_JSON_Analysis/blob/main/images/image3.png)
![initial](https://github.com/lastime1650/YARA_to_JSON_Analysis/blob/main/images/image4.png)

