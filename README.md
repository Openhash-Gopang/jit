# K-JIT — 사회효용 우선 적시조달 메커니즘

혼디(Hondi) K-서비스 중 하나. 가계·기업·기관이 필요로 하는 물자·
인원·서비스의 조달을 계획하는 메커니즘이며, 기존 JIT(Just-In-Time)과
달리 개별 주체의 비용 최소화가 아니라 **사회 전체의 효용 극대화·총
비용 최소화**를 목적함수로 삼는다.

- 상태: 초안 (v0.1) — 아직 sp-catalog.json에 등록되지 않았고,
  worker.js 라우팅에도 연결되지 않았다.
- 설계 문서: [`SP-26_kjit_v0_1.txt`](./SP-26_kjit_v0_1.txt)
- 관련 저장소: [hondi](https://github.com/Openhash-Gopang/hondi)(메인),
  이 저장소는 K-Logistics·K-Market이 하는 "실행"과 분리된 "계획" 레이어를
  다룬다.

## 다음 단계

1. `SP-26_kjit_v0_1.txt`를 hondi 메인 저장소의 `prompts/`에 반영하고
   sp-catalog.json에 등록
2. K-Logistics·K-Market과의 §0 경계 실사 재검증
3. §OBJECTIVE-FUNCTION 외부효과 계량 모델·§COMPENSATION 보상 재원
   구조 확정
4. worker.js 라우팅 연결 및 desktop.html#k-services 탭 추가
