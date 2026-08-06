# JuCheon Lee
### Vision / VLM / Medical AI Researcher

* **Vision Transformer & VLM (Gemma, Qwen-VL etc)**
* **Visual Question Answering (VQA)**
* **Ordinal Classification**
* **Medical Image Analysis & Industrial AI**
* **Multimodal Learning**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/주천-이-ba0741377)
[![GitHub Issues](https://img.shields.io/badge/Contact-GitHub_Issues-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/JcLee96/JcLee96/issues)
[![Naver](https://img.shields.io/badge/Naver-03C75A?style=flat-square&logo=naver&logoColor=white)](mailto:jucheon0618@naver.com)

<br/>

## 💼 Experience

#### **SteelDefectX 결함 이미지 기반 Decoder-Only VLM 적용** | *Personal Project* | 2026.07 ~ 
* Long-CLIP(ViT-L/14) 기반 논문 재현 및 분류·세그멘테이션·속성 ablation·검색 4개
* CLIP 계열을 VLM2Vec-V2(Qwen2-VL-2B bi-encoder)로 교체 후 LoRA 적응 — 분류 94.49, 검색 i2t R@1 26.03 (Long-CLIP 5.77 대비 4.5배)
* Gemma-4-12B(생성형 디코더) 적용 시 임베딩 공간 부재로 우도 랭킹이 강제되는 구조적 한계 규명 — 공유 접두사 편향이 클래스 신호의 19배임을 [N,25] 점수 행렬로 정량화
* 예측 CSV·점수 행렬 전량 보존하는 평가 파이프라인 설계 — GPU 재실행 없이 12개 채점 규칙을 오프라인 재계산 가능

#### **TechMB 논문 재현 및 GRPO 도메인 전이 검증** | *Personal Project* | 2026.07 ~ 
* 공개 코드가 없는 논문(DFX2025)을 프롬프트·채점 규칙까지 재구성해 재현 > 947 QA / 180 기술도면, VLM 5종 평가
* 모델 규모 확장 실험 — SmolVLM2(2.2B) 27.0% → Qwen3.6-27B 77.9%, 논문의 "OCR 강점 / 제조 추론 취약" 주장을 태스크 타입별로 검증
* MechVQA GRPO 학습 및 TechMB 평가 — 70.12% vs zero-shot 69.06%

#### **Grow AI Team @ Daedong AI Lab** | *Researcher* | 2024.09.23 ~ 2026.06.30
* 스마트팜 생육 계측 모델 개발 및 실데이터(Inter Realsense RGB-D Camera) 기반 비전 알고리즘 연구
* 농경지 이용 판독 AI 모델 개발 | 수분 스트레스 AI 모델 개발
* Vision 및 Multimodal 모델을 실제 시스템에 적용하는 Applied Research 수행

#### **Quantitative Imaging & Informatics Laboratory** | *MS* | 2022.03.01 ~ 2024.02.23
* 병리학 이미지(Pathology Image) 분류 연구
* EEG 데이터 기반 뇌졸중 환자 분류 연구
* 디블러링(Deblurring) 모델 연구

#### **Quantitative Imaging & Informatics Laboratory** | *Intern* | 2021.09.16 ~ 2022.02.30
* EEG 데이터 기반 뇌졸중 환자 분류 연구
* CS231n 강의 기반 컴퓨터 비전 학습 및 CNN, ViT 논문 세미나 발표

#### **CodeState AI 부트캠프 2기** | *Student* | 2021.03.01 ~ 2021.09.15
* Machine Learning (Scikit-learn), Deep Learning (TensorFlow/PyTorch), SQL
* 정형 및 비정형 데이터 분석 기법 학습 및 알고리즘 구현 실습
* AI 모델 추론 결과 서빙을 위한 웹 프레임워크 기초 및 API 연동 경험
* 뇌 이미지 기반 Segmentation 개인프로젝트 2건 수행

<br/>

## 🛠 Tech Stack
| Category | Tools & Technologies |
| :--- | :--- |
| Category | Tools & Technologies |
| :--- | :--- |
| **Languages** | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) |
| **Frameworks** | ![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white) |
| **Infrastructure & Cloud** | ![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white) ![RunPod](https://img.shields.io/badge/RunPod-7B2CBF?style=flat-square&logo=runpod&logoColor=white) |
| **AI Assistants & Tools** | ![ChatGPT](https://img.shields.io/badge/ChatGPT-74AA9C?style=flat-square&logo=openai&logoColor=white) ![Claude](https://img.shields.io/badge/Claude-D97706?style=flat-square&logo=anthropic&logoColor=white) ![Gemini](https://img.shields.io/badge/Gemini-8E75B5?style=flat-square&logo=google-gemini&logoColor=white) |
| **IDE** | ![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=flat-square&logo=visual-studio-code&logoColor=white) ![PyCharm](https://img.shields.io/badge/PyCharm-000000?style=flat-square&logo=pycharm&logoColor=white) |

<br/>

## 📖 Publications & Projects
### 🔬 Peer-Reviewed Publications
* **[DIOR-ViT]** [DIOR-ViT: Dual-branch implicit ordinal relationship vision transformer for ordinal classification](https://www.sciencedirect.com/science/article/pii/S1361841525002555)
  * ***Medical Image Analysis (MedIA)***, 2025 (**IF: 14.0**)
* **[DELECA]** [DELECA: Dual-exposure learning via cross-attention for high dynamic range image enhancement](https://www.sciencedirect.com/science/article/pii/S2405959525000785)
  * ***ICT Express***, 2025 (**IF: 4.6**)
  * **Core Contribution**: Model architecture design & Extensive experimental validation
* **[Order-ViT]** [Order-ViT: Order-Learning Vision Transformer for Cancer Classification in Pathology](https://openaccess.thecvf.com/content/ICCV2023W/CVAMD/html/Lee_Order-ViT_Order_Learning_Vision_Transformer_for_Cancer_Classification_in_Pathology_ICCVW_2023_paper.html)
  * *Computer Vision for Automated Medical Diagnosis (CVAMD), **ICCV Workshop 2023***
    
<br/>

## 🏆 Challenges & Awards
* **[AI Samsung Challenge 2023]** [3D Metrology & Semiconductor Image Quality Assessment (IQA)](https://dacon.io/en/competitions/official/236134/talkboard/409957)
    * **Final Winner (Ranked 3th)** | Team: *Quiil Lab* | [Winner Interview](https://dacon.io/forum/410484)
* **[AI Samsung Challenge 2022]** [Semiconductor Image Captioning & Reconstruction](https://dacon.io/en/competitions/official/235954/talkboard/406931)
    * **Final Winner (Ranked 8th)** | Team: *웅싸*

<br/>

## 💡 Patents
* **차량의 전력 소모량을 관리하기 위한 원격 차량 관리 서버 및 이를 이용한 차량 제어 방법**
  * *Patent Application No. 10-2025-0177389* (2025.11.20)
* **AI 기반의 작물 생육 계측 방법 및 컴퓨팅 장치**
  * *Patent Application No. 10-2025-0167351* (2025.11.07)
* **차등순서학습 기반 딥러닝 모델 학습 방법 및 그 장치**
  * *Patent Application No. 10-2023-0091585* (2023.07.14)

<br/>

## 🎯 Research Interests
- **Architectures**: Vision Transformer (ViT), Multimodal Learning
- **Tasks**: Ordinal Classification, Segmentation, Image Restoration
- **Domain**: Medical AI, Smart Farming, Real-world AI
