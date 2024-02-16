# YOLOv5를 활용한 건물균열탐지헬멧

- `2023 조선대학교 캡스톤디자인 프로젝트` : Building Crack Detector 건물균열탐지헬멧
## 프로젝트 참여 학생
김의중 - `조선대학교 정보통신공학부 정보통신전공4`

김주한 - `조선대학교 정보통신공학부 정보통신전공4`

송민우 - `조선대학교 정보통신공학부 정보통신전공4`

정홍렬 - `조선대학교 정보통신공학부 정보통신전공4`

진범종 - `조선대학교 정보통신공학부 정보통신전공4`


## 수행일자

- 프로젝트 수행기간: `2023.04` ~ `2023.11`

## 프로젝트 설명

- 건물 균열은 건축물의 안전성과 구조적 튼튼함에 직접적인 영향을 미칩니다. 기존에는 수동적으로 균열 탐지 작업을 수행했습니다. 이는 비용과 시간을 많이 소모하게 하는 단점을 가지고 있었습니다. 근로자의 안전사고 예방과 앞서 언급한 문제 해결을 목표로 저희 ECL 팀은 인공지능 컴퓨터비전 기술 YOLOv5를 활용하여 자동화된 균열 탐지 시스템이라는 아이디어를 고안하게 되었습니다. 건물 균열은 시공과정에서 시간이 지남에 따라 발생할 수 있으며, 균열의 크기와 심각성은 점차 악화될 수 있습니다. 균열을 빠르게 탐지하고 대응함으로써 건물의 구조적 결함을 조기에 파악할 수 있게 됩니다. 이를 통해 건물의 안전성과 근로자의 안전을 확보하고 예방적 유지보수를 수행할 수 있습니다.
  
- 과제의 목적은 YOLOv5를 활용하여 실시간으로 건물의 균열을 자동으로 탐지하는 것입니다. 이를 통해 건물 소유자(시공을 의뢰한 자)나 유지보수 담당자에게 신속하고 정확한 정보를 제공하여 적절한 조치를 취할 수 있도록 도움을 줄 수 있게 됩니다. 이 프로젝트를 수행함으로써 건물 균열 탐지 작업의 자동화를 통한 작업의 효율성 증대, 건물의 안전과 구조적 신뢰성을 향상시킬 수 있습니다.


## 수행환경
- YOLOv5를 사용하여 실시간으로 균열 인식을 하기 위한 JetsonNano의 Ubuntu 기반 환경이용

![image](https://github.com/kimdevspace/Building-Crack-Detector-csu-capstone-/assets/158041455/01c97f8c-4660-432b-90ff-cb77a99d70d7)

- roboflow에서 수집한 균열데이터 가공

![image](https://github.com/kimdevspace/Building-Crack-Detector-csu-capstone-/assets/158041455/edf7e154-7652-4780-ad1a-b307e6366d50)

- PyTorch로 데이터 학습

![image](https://github.com/kimdevspace/Building-Crack-Detector-csu-capstone-/assets/158041455/1367c6fe-7bb8-44d8-9d7d-f6cbded5763e)

- 텐서플로우 시각화


![스크린샷 2023-06-05 134004](https://github.com/kimdevspace/Building-Crack-Detector-csu-capstone-/assets/158041455/3382a8ed-1835-466b-be5d-b18d24c21b9a)

- 학습결과


![스크린샷 2023-06-05 134031](https://github.com/kimdevspace/Building-Crack-Detector-csu-capstone-/assets/158041455/b841adb7-2099-4300-9128-7f7b587d0ce7)

- 실시간 균열 탐지 프로그램

![image](https://github.com/kimdevspace/Building-Crack-Detector-csu-capstone-/assets/158041455/20493398-d24b-4b7f-9b51-add6a1226ab4)

- 하드웨어 `기존 안전모에 Intel RealSense Depth 카메라를 결합`


![image](https://github.com/kimdevspace/Building-Crack-Detector-csu-capstone-/assets/158041455/dbc7d78a-ce25-45f4-a8eb-2ba03fff740b)


## 수상내역
- 2023.06 조선대학교 AI융합사업단주관 정보통신공학부 상반기 캡스톤디자인시연경진대회 🏅**금상**
- 2023.11 조선대학교 IT Festival (제17회 종합학술대회) 캡스톤디자인지식디자인창출경진대회 🏅**금상**
- 2023.01 조선대학교 AI융합사업단주관 정보통신공학부 하반기 캡스톤디자인시연경진대회 🏅**대상**
