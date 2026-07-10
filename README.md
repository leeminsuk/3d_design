# 3d_design

새롭고 다양한 3D 웹 디자인 실험 모음. 각 HTML 파일은 의존성 없이 단독 실행되는 한 장짜리 작품입니다 (Three.js CDN 사용).

**라이브 갤러리**: https://leeminsuk.github.io/3d_design/

**브랜치 정책**: 01은 `main`에, 02부터는 작품별 브랜치(`design/NN-slug`)에 올라갑니다.

| # | 작품 | 컨셉 | 기법 | 위치 |
|---|------|------|------|------|
| 01 | [심해 개화 — Abyssal Bloom](https://leeminsuk.github.io/3d_design/01-abyssal-bloom.html) | 수심 4,000m의 발광 해파리 떼 | 커스텀 정점/프래그먼트 셰이더, 가산 블렌딩, UnrealBloom, 파티클 | `main` |
| 02 | [달항아리 — Moon Jar](https://raw.githack.com/leeminsuk/3d_design/design/02-moon-jar/02-moon-jar.html) | 하루의 해가 둘레를 도는 백자 | 레이마칭 SDF(지오메트리 0), 소프트 섀도, AO, 서브서피스 근사 | [`design/02-moon-jar`](https://github.com/leeminsuk/3d_design/tree/design/02-moon-jar) |
| 03 | [만 개의 창 — Ten Thousand Windows](https://raw.githack.com/leeminsuk/3d_design/design/03-ten-thousand-windows/03-ten-thousand-windows.html) | 창문 9,096개가 하나씩 잠드는 서울의 밤 | InstancedMesh, 인스턴스 어트리뷰트 셰이더, 결정적 소등 데이터+실시간 카운터 | [`design/03-ten-thousand-windows`](https://github.com/leeminsuk/3d_design/tree/design/03-ten-thousand-windows) |
| 04 | [비단 — Silk](https://raw.githack.com/leeminsuk/3d_design/design/04-silk/04-silk.html) | 마우스가 바람이 되는 자주빛 비단 | 베를레 클로스 물리(CPU), MeshPhysicalMaterial iridescence+sheen, 레이캐스트 바람 | [`design/04-silk`](https://github.com/leeminsuk/3d_design/tree/design/04-silk) |
| 05 | [군무 — Murmuration](https://raw.githack.com/leeminsuk/3d_design/design/05-murmuration/05-murmuration.html) | 십만 마리 찌르레기의 해질녘 군무, 커서는 매 | GPGPU 핑퐁 FloatType RT, 컬 노이즈 조향, 텍셀당 삼각형 렌더, 블룸 | [`design/05-murmuration`](https://github.com/leeminsuk/3d_design/tree/design/05-murmuration) |
| 06 | [왕관을 쓴 행성 — The Ringed Giant](https://raw.githack.com/leeminsuk/3d_design/design/06-ringed-giant/06-ringed-giant.html) | 부서진 달의 기억으로 만든 왕관 | 해석적 광선-구/평면 교차(무왜곡), 일식 반그림자, 절차적 구름 띠, 대기 림 | [`design/06-ringed-giant`](https://github.com/leeminsuk/3d_design/tree/design/06-ringed-giant) |

> 각 작품은 렌더 검증(콘솔 에러 0, 스크린샷 확인) 후 커밋됩니다.
