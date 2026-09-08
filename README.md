## 홍진규 (Jin Gyu Hong)

**Computer Vision 석사 · CVPR 2024 Workshop 공동 제1저자**

영상에서 필요한 정보를 뽑아내는 모델을 만들고, 그 모델이 실제 환경에서도 흔들리지 않게 만드는 일을 해왔습니다.
평균 성능보다 **어떤 조건에서든 일정한 품질**이 더 어렵고 더 중요하다고 생각합니다.

현재 **삼성 청년 SW·AI 아카데미(SSAFY) 15기** 과정에서 Java·웹 개발을 익히며, 연구 역량을 서비스로 잇는 방향으로 확장하고 있습니다.

---

### 대표 작업

| | |
|---|---|
| **[3D Clothed Human Reconstruction](https://github.com/JinGyu5175/3d-clothed-human-reconstruction)** | 소수의 다시점 이미지로 옷 입은 사람의 3D 형상·질감을 복원. **CVPRW 2024** 게재, 직전 SOTA 대비 형상 28%·질감 16% 개선 |
| **[Ssabway](https://github.com/JinGyu5175/ssabway)** | 외국인 철도 이용자를 위한 역내 안내 서비스. 표지판 인식으로 실내 위치를 특정하고 경로를 안내. **SSAFY 공통 프로젝트 우수상** |

---

### 연구 이력

- **3D Clothed Human Reconstruction from Sparse Multi-View Images** — IEEE/CVF CVPR 2024 Workshops (3DMV), 공동 제1저자 · 미국 시애틀 현장 발표
- **캘리브레이션 된 2시점 영상으로부터의 3차원 휴먼 복원** — 한국방송미디어공학회 추계학술대회 2023
- **「다시점 영상으로부터의 3차원 휴먼 복원 방법」** — 한국·미국 특허 출원

**참여 과제**

| 과제 | 발주 | 담당 |
|---|---|---|
| 다시점 이미지를 이용한 옷을 입은 인간의 3D 복원 | ETRI | 3D 복원 모델 구현, 학습 성능 개선, 논문 작성 |
| 심신안정 및 스트레스 완화 기능성 콘텐츠 플랫폼 | ETRI | 실시간 얼굴 랜드마크 추정 모델 개발 |
| 무인점포 환경 대응형 영상보안시스템 (2D/3D 영상 통합 분석) | IITP | 사람의 3D 메쉬 복원 모델 개발 |

---

### 기술

| | |
|---|---|
| **AI / Vision** | Python, PyTorch, OpenCV, YOLO, ResNet, Transformer, Object Detection, Multi-view / RGB-D, 3D Reconstruction |
| **모델 개발** | 데이터셋 구축·라벨링, 전처리, Data Augmentation, Fine-tuning, 성능 평가, Ablation Study |
| **서버 / 웹** | FastAPI, Java, Spring Boot, MySQL, React |
| **협업 / 배포** | Git, GitLab, Docker, Jenkins |

---

### 하는 방식

- **비교 없이 개선을 주장하지 않습니다.** 석사 연구에서 기존 특징 융합 방식 4종을 동일 조건에서 전부 재구현해 비교한 뒤에야 어떤 방식이 나은지 말할 수 있었습니다.
- **평균이 아니라 무너지는 구간을 봅니다.** 평균 정확도가 높아도 특정 조건에서 결과가 깨지면 쓸 수 없습니다. 성능이 낮은 구간을 먼저 찾아 보완합니다.
- **모르면 모른다고 하게 만듭니다.** 표지판 인식에서 확신도가 낮은 예측은 내보내지 않고 걸러냈습니다. 틀린 답을 확신에 차서 내놓는 것이 가장 나쁩니다.

