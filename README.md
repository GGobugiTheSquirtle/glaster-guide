# 글래스터 완전 공략 · Another Eden

[📖 Live Guide](https://ggobugithesquirtle.github.io/glaster-guide/)

어나더 에덴(Another Eden)의 **글래스터(Grasta) 시스템** 비공식 통합 가이드.
일본판 / 영문판 / 한국 공략 커뮤니티의 자료를 한국어로 체계화해 단일 문서로 정리.

## 특징

- **Research Paper 톤** — 기존 [ae-story-guide](https://github.com/GGobugiTheSquirtle/AE-Story-Kor-) / [tierlist-guide](https://github.com/GGobugiTheSquirtle/tierlist-guide) 의 다크 네이비+골드와 의도적으로 대비되는 **크림+딥 틸** 편집 디자인
- **다크/라이트 토글** · OS 감지 + 사용자 선택 저장
- **좌측 고정 목차** · 스크롤 따라 현재 섹션 하이라이트
- **모바일 반응형** · 900px 이하 세로 배치
- **단일 HTML** · 외부 의존 = Google Fonts / Pretendard CDN
- **이미지 전량 로컬** · `images/` 에 보관, 출처는 각 캡션에 명기 (제3자 핫링크 없음)
- **용어 기준 = 한국어 원본 자료** · `한글판 공략내용.md` · `글래스터 획득처.md` 표기를 따르고, 대응어가 없을 때만 일본판 표기를 `JP` 표시와 함께 병기

## 구조

```
I    기초 시스템         — 4계열, 등급, 슬롯 개방
II   강화와 연성         — 활성화/각성 비용, 연성 광석
III  던전별 획득처       — 14개 Another Dungeon
IV   추천 세팅 원칙     — 페페페/독독독/중중중/셔틀
V    VC · 진 · 극한 증표 — 캐릭터 전용 글래스터
VI   고급 최적화         — 원턴덱, 닦이, 천명 200
부록 용어 통일표         — KO/EN/JP/약칭
```

## 용어 · 출처 원칙

1. **한국어 표기는 한국어 원본 자료가 기준.** 일본판 altema 나 영문 위키 표기를 그대로 음차하지 않는다.
   (예: `분향로` → `고양이 신사`, `분서(奉納)` → `봉헌(오타키아게)`, `직업서` → `직서`, `표류물` → `표착물`)
2. **한국 자료에 대응어가 없으면 기능 설명 + JP 원표기 병기.** 임의 음차 금지.
3. **출처 범위 명시.** 현대·고대·미래 가를레아 / 명협계는 한국어 자료로 교차검증. 오메가폴리스 · 엔트라나 ·
   지스몬데 · 기타 7종은 altema(일본판) 단독 출처이므로 본문 footnote 3 에 그 사실을 표기한다.

## 출처 / Credits

본 문서는 비영리 팬 가이드입니다. 이미지는 각 원본 사이트에서 직접 링크되며, 저작권은 각 게시자에게 있습니다.

- [altema.jp/anaden](https://altema.jp/anaden) — 일본 공략 사이트 (던전 지도/키 아이템 사용처)
- [anothereden-game-info wiki](https://anothereden.game-info.wiki/) — 글래스터 시스템 아이콘
- [arca.live 어나더 에덴 채널](https://arca.live/b/anothereden) — 한국 커뮤니티 게시글 다수

문의/삭제 요청: [GitHub Issues](https://github.com/GGobugiTheSquirtle/glaster-guide/issues)

## 로컬 실행

```bash
cd glaster-guide
python -m http.server 8080
```
→ http://localhost:8080

## License

- 코드(HTML/CSS/JS): MIT
- 텍스트 콘텐츠: CC BY-NC-SA 4.0
- 이미지: 각 원본 사이트의 저작권 적용
