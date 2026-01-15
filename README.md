# Pneumonia_Detection_Project
YOLO를 사용한 Pneumonia Detection Project

목표 : 전문의의 판독을 보조할 수 있는 수준의 성능을 달성하고, 오진율을 낮추고 판독 속도 향상


rsna-pneumonia-detector Computer Vision Dataset
- RSNA(북미방사선의학회) Pneumonia Detection Challenge
    
→ 영상의학과 전문의들이 **직접 폐렴 의심 부위를 찾아** 바운딩 박스를 친 고품질 데이터

- **Class**: 단일 클래스 (Pneumonia)
- **데이터 규모**: **13,494장 (**Traion: 11796 / Val: 1140 / Test: 558**)**
- **Annotation**: 이미지 내 폐렴 발생 위치의 좌표(x, y, width, height)가 모두 포함


폐렴이란?
- 폐렴구균에 의한 감염으로 폐포에 염증이 생기는 질병
- 급성 중이염, 폐렴 및 균혈증, 수막염 등 침습성 감염을 유발
- 건강보험심사평가원 통계 기준 2024년 1월까지 폐렴 진료 환자 수 **188만명**
- 2020년 대비 환자수 **115% 증가**
