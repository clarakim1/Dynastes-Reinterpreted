# Dynastes, Reinterpreted 🪲

장수풍뎅이(*Dynastes*)의 해부 구조를 현대적인 기계·생체 디자인으로 재해석한 3D 프린팅 프로젝트입니다.
3D Cell Project의 "내부 구조를 단면으로 보여주는" 접근을 외골격과 뿔 구조로 확장했습니다.

- 웹 뷰어: https://clarakim1.github.io/Dynastes-Reinterpreted/ 

![preview](images/preview.png)

## 컨셉

| 요소 | 생물학적 원형 | 재해석 |
|---|---|---|
| 뿔 | 두부 뿔 + 흉부 뿔이 맞물리는 집게 구조 | 개폐되는 레버/집게 메커니즘 |
| 딱지날개 | 단단한 앞날개(elytra) | 열리는 힌지형 셸, 격자 구조 |
| 표피 | 키틴 외골격, 표피 세포 패턴 | 보로노이/육각 격자 텍스처 |

자세한 내용은 [docs/concept.md](docs/concept.md).

## 폴더 구조

```
cad/      Fusion 360 원본 (.f3d) 및 파라미터 설명
stl/      출력용 STL
3mf/      출력 프로파일 포함 3MF
docs/     웹 뷰어(index.html), 컨셉/조립/출력 문서
images/   README와 MakerWorld용 이미지
```

## 웹 뷰어

`docs/index.html` 하나로 동작합니다 (three.js r128, CDN 사용).
- 해석 모델: 뿔 개폐, 딱지날개 열기, 분해도, 세포 격자 토글
- 내 STL 보기: 화면에 STL 파일을 끌어다 놓기

GitHub Pages: Settings → Pages → Source `main` / `/docs`.

## 출력 · 조립

- [docs/print-settings.md](docs/print-settings.md)
- [docs/assembly.md](docs/assembly.md)

## 라이선스

- 3D 모델·이미지·문서: CC BY-NC-SA 4.0 ([LICENSE-MODEL.md](LICENSE-MODEL.md))
- 웹 뷰어 코드(`docs/index.html`): MIT ([LICENSE](LICENSE))
