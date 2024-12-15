# YARA_to_JSON_Analysis
Save the analysis using "YARA" to JSON.
# YARA모듈기반 분석 도구 개발
YARA는 rule 기반으로 binary 정보를 탐색하여 정해진 규칙에 따라 일치한 지 검사합니다. 
YARA를 도입하려는 경우, 쉽고 빠르게 Threading을 통해 "비동기"적으로 분석을 수행하고, JSON으로 결과를 queue에 반환하는 작업을 합니다.  
