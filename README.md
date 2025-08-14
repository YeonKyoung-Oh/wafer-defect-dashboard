# 반도체 웨이퍼 결함 분석 대시보드

63,909건의 반도체 제조 공정 웨이퍼 결함 검사 데이터를 분석하고,  
결함 패턴 시각화 및 머신러닝 기반 결함 예측을 제공하는 **Streamlit 웹 대시보드**입니다.

🔗 **배포 페이지**: [Streamlit에서 실행하기](https://wafer-defect-dashboard-by7.streamlit.app)
📂 **GitHub 저장소**: [프로젝트 코드](https://github.com/YeonKyoung-Oh/wafer-defect-dashboard)

---

## 📌 주요 기능
- **공정별/슬롯별 결함 통계 분석**
- **웨이퍼 맵 시각화** (RADIUS, ANGLE 기반)
- **결함 예측 모델 시뮬레이션** (Random Forest, XGBoost)
- **주요 Feature 중요도 확인** 및 인사이트 제공

---

## 🛠 사용 기술
- **Python** 3.9+
- **Streamlit**
- **Pandas, NumPy**
- **Plotly**
- **Scikit-learn**
- **XGBoost**

---

## 🚀 실행 방법

### 1. 저장소 클론
```bash
git clone https://github.com/username/project-name.git
cd project-name
```

### 2. 라이브러리 설치
```bash
pip install -r requirements.txt
```

### 3. 모델 학습 후 저장
```bash
python train_and_save_models.py
```

### 4. Streamlit 대시보드 실행
```bash
streamlit run project.py
```
