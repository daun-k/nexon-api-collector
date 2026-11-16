# NEXON Open API 게임 거래 데이터 수집·분석

🌐 **한국어** | [English](README.en.md)

넥슨 오픈 API로 게임 거래 데이터를 자동 수집하고, 수집한 데이터를 분석하는 프로젝트입니다.

- 수집 파이프라인: [notebooks/01_collection](notebooks/01_collection/README.md)
- 분석: notebooks/02_analysis (예정)

## 레포지토리 구조

```
nexon-api-collector/
├── .github/
│   └── workflows/
│       ├── mabinogi.yml             # 마비노기 경매장 수집 워크플로
│       └── mabinogi_heroes.yml      # 마비노기 영웅전 거래소·공지 수집 워크플로
├── notebooks/
│   ├── 01_collection/
│   │   ├── mabinogi_collect.ipynb          # 마비노기 수집, 적재, 중복 정리
│   │   ├── mabinogi_heroes_collect.ipynb   # 마비노기 영웅전 수집, 적재, 중복 정리
│   │   ├── README.md                       # 수집 파이프라인 (한국어)
│   │   └── README.en.md                    # 수집 파이프라인 (영어)
│   └── 02_analysis/                 # 수집 데이터 분석 (예정)
├── requirements.txt
├── .gitignore
├── README.md
└── README.en.md
```