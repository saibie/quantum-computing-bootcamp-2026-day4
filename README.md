# 양자컴퓨팅 이론 및 실습 (12시간 집중 부트캠프) - Day 4

본 저장소는 **[양자컴퓨팅 이론 및 실습]** 4주(총 12시간) 집중 강좌 중 **4주차 (Day 4: QubitSquare 산업용 웹 양자 플랫폼 종합 실습)** 공식 학생용 실습 및 배포 저장소입니다.  
강의 슬라이드, Day 4 렉처노트 및 참조 실습 파일(Jupyter Notebook), 원클릭 구동 스크립트가 포함되어 있습니다.

- **강사**: 서상협 ((주)큐렌스 / QRens)
- **주제**: 4주차 - QubitSquare 산업용 웹 양자 플랫폼 종합 실습 및 결과 비교
- **플랫폼 접속**: 별도 설치 없이 웹 브라우저로 QubitSquare 접속 후 드래그 앤 드롭 실습

---

## 📥 저장소 다운로드

### 방법 1. Git 사용 (추천)
```bash
git clone https://github.com/saibie/quantum-computing-bootcamp-2026-day4.git
cd quantum-computing-bootcamp-2026-day4
```

### 방법 2. ZIP 파일 다운로드
1. 페이지 우측 상단의 **`Code`** -> **`Download ZIP`** 클릭
2. 다운로드한 파일의 **압축을 해제**한 후 해당 폴더로 진입

---

## 🚀 3초 만에 실습 환경 시작하기 (파이썬 참조 모델)

### 🪟 Windows 사용자
1. 폴더 내의 **`start_windows.bat`** 파일을 더블 클릭하여 실행합니다.
2. 검은색 터미널 창에서 자동 환경 구성 후 브라우저에 **Jupyter Lab**이 실행됩니다.

### 🍎 macOS 및 Linux 사용자
1. 터미널에서 아래 명령어 실행:
   ```bash
   chmod +x start_mac.sh
   ./start_mac.sh
   ```

---

## 📂 폴더 구조 안내

```text
├── docs/                               # 강의 교재 및 참고 문서 (PDF)
│   ├── day4_qubitsquare.pdf            # Day 4 강의 슬라이드 (QubitSquare 플랫폼 종합 실습)
│   └── lecture_notes_day4.pdf          # Day 4 핵심 플랫폼 아키텍처 집중 렉처노트
│
├── hands_on/                           # 실습 코드 (참조 모델)
│   └── day4_qubitsquare.ipynb          # [Day 4 참조 실습] 자동 측정, 엔디언 변환, Compare 알고리즘
│
├── start_windows.bat                   # Windows 원클릭 실습 실행기
├── start_mac.sh                        # Mac/Linux 원클릭 실습 실행기
├── pyproject.toml                      # 프로젝트 메타데이터 및 의존성 정의
└── uv.lock                             # 라이브러리 버전 고정 락파일
```

---

## 💡 Day 4 핵심 학습 내용
- **Session 1**: 코딩 장벽과 웹 GUI 당위성, QubitSquare 6단계 데이터 계층, 5대 Puzzle Pieces, Bell 회로 조립 및 QPlayer 서버 100샷 실행
- **Session 2**: Duplicate 실험 분기, 2-qubit Grover 1,000샷 서버 실행, Compare 다중 런(100샷 vs 1,000샷) 통계 오차 수렴 비교, 산업 문제 템플릿(Max-Cut, TSP)

---

## 📬 문의 및 지원
- 저작권: 본 자료의 저작권은 **(주)큐렌스** 및 강사 **서상협**에게 있습니다. 교육 목적 외 무단 배포 및 상업적 이용을 금합니다.
