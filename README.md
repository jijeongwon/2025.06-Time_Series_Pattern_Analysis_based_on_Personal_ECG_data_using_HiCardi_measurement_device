# [2025.06] Time Series Pattern Analysis Based on Personal ECG Data Using the HiCardi Measurement Device

> 병원인공지능실무I 과목에서 진행한 HiCardi 측정 장치를 이용한 개인 심전도 데이터 기반 시계열 패턴 분석 프로젝트입니다. <br>

HiCardi 기기로 수집한 개인 ECG를 시각화하고 R-peak 기반 BPM·이상구간을 추정했습니다. <br>
LSTM으로 다음 시점 전압을 예측해 정상 ECG의 시계열 패턴이 학습 가능함을 확인했습니다. <br>
본 프로젝트는 질환 분류가 아닌 정상 신호 표현 학습과 이상 탐지 가능성에 초점을 두었으며, 향후 개인 맞춤형 심장 모니터링의 기반을 제시합니다.

---

### 목차
1. Motivation for this research <br>
2. FlowChart <br>
3. Data & HiCardi <br>
4. PreProcessing <br>
5. Model <br>
6. Experiments <br>
7. Results <br>
8. Limitations & Future Work <br>
9. Report <br>
 
---

## 1. Motivation for this research
기존 병원 중심의 ECG 검사는 일정 시간 동안만 측정이 이루어지기 때문에, 일상생활 중 불규칙하게 발생하는 부정맥이나 이상 신호를 놓칠 가능성이 존재한다. 이에 따라, 휴대용 ECG 기기를 활용한 개인 맞춤형 실시간 모니터링의 필요성이 점차 증가하고 있다. <br>
본 연구에서는 HiCardi 개인용 ECG 기기를 통해 수집한 실제 데이터를 기반으로, 정상 심전도 신호의 구조와 시계열 패턴을 분석하고, 딥러닝 모델이 이를 어떻게 학습하고 예측할 수 있는지를 탐색하였다. 이러한 분석은 향후 부정맥 탐지 또는 이상 징후 감지와 같은 실시간 건강 모니터링 기술로 확장될 수 있는 가능성을 내포하고 있다.

---

## 2. Data & HiCardi

---

## 3. FlowChart
<img width="100%" src="https://github.com/user-attachments/assets/11dad4e7-9a72-44e1-97e0-af5d4f5786f6" />

---

## 4. Report

| | |
|---|---|
| <img src="https://github.com/user-attachments/assets/06ec3731-bfee-4d66-a0c6-7db7af4cb210" width="100%"/> | <img src="https://github.com/user-attachments/assets/7b6c12c5-398a-4188-a06e-57736bce6991" width="100%"/> |
|---|---|
| <img src="https://github.com/user-attachments/assets/50bb5158-fe0e-47ef-a902-f5b06d015ebb" width="100%"/> | <img src="https://github.com/user-attachments/assets/77f7b900-1e26-46c8-b701-2fa7dcab9cab" width="100%"/> |
