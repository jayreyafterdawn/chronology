# Chronology

역사 속 인물들의 생애·전성기·주요 작품을 **시대의 한 축 위에** 그린 인터랙티브 연대표 모음입니다.

## 연대표

| 연대표 | 대상 | 범위 |
|---|---|---|
| [한국문학 근현대 작가 연대표](korea-literature/) | 한국 문학 작가 178인 | 1862 – 현재 |
| [세계문학 고전 작가 연대표](world-literature/) | 세계문학 작가 174인 | BC 780 – 현재 |
| [세계영화 거장 감독 연대표](world-cinema/) | 세계 영화감독 136인 | 1861 – 현재 |

연대표는 계속 추가됩니다.

## 특징

- 의존성 없는 단일 HTML 파일 — 각 폴더의 `index.html` 하나로 완결
- 생애(옅은 막대) · 전성기(짙은 구간) · 주요 작품(점) · 주요 수상(★)을 한 축에 표시
- 분야·사조 필터, 인물 검색, 한/영 전환, 라이트·다크 테마
- PNG 내보내기, CSV 다운로드
- 각 폴더의 `*.csv`는 데이터 사본 (원본 데이터는 `index.html` 내장)

## 구조

```
index.html                  # 랜딩 — 연대표 목록 (새 연대표는 TIMELINES 배열에 항목 추가)
korea-literature/index.html # 한국문학 근현대 작가 연대표
world-literature/index.html # 세계문학 고전 작가 연대표
world-cinema/index.html     # 세계영화 거장 감독 연대표
```

---

기획·제작 **이정원** · [@jayr.eyafterdawn](https://www.instagram.com/jayr.eyafterdawn)
