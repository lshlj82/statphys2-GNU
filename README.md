# Statistical Physics 2: Interactive Demos
**경상국립대학교 물리학과 통계물리2 교과목 보조자료**

Landing page for the interactive web demos that accompany *Statistical Physics 2* (통계물리2) in the Department of Physics, Gyeongsang National University.

**Live page:** https://lshlj82.github.io/stat-phys-2/

Created by Claude Opus 5.5, based on the lecture notes by Prof. Sang Hoon Lee.
이상훈 교수의 강의 노트를 바탕으로 Claude Opus 5.5가 만들었습니다.

## Demos · 데모 목록

| # | Demo | 데모 | Links |
|---|------|------|-------|
| 1 | Boltzmann statistics | 볼츠만 통계 | [demo](https://lshlj82.github.io/Boltzmann-statistics-basics/) · [source](https://github.com/lshlj82/Boltzmann-statistics-basics) |
| 2 | Boltzmann statistics of an ideal gas | 이상 기체의 볼츠만 통계 | [demo](https://lshlj82.github.io/Boltzmann-ideal-gas/) · [source](https://github.com/lshlj82/Boltzmann-ideal-gas) |
| 3 | Gibbs statistics | 깁스 통계 | [demo](https://lshlj82.github.io/Gibbs-statistics/) · [source](https://github.com/lshlj82/Gibbs-statistics) |
| 4 | Boson vs Fermion | 보손 대 페르미온 | [demo](https://lshlj82.github.io/boson-vs-fermion/) · [source](https://github.com/lshlj82/boson-vs-fermion) |
| 5 | Degenerate Fermi gas | 축퇴 페르미 기체 | [demo](https://lshlj82.github.io/degenerate-fermi-gas/) · [source](https://github.com/lshlj82/degenerate-fermi-gas) |
| 6 | Photon statistics | 광자 통계 | [demo](https://lshlj82.github.io/photon-statistics/) · [source](https://github.com/lshlj82/photon-statistics) |
| 7 | Debye theory of solids | 고체의 디바이 이론 | [demo](https://lshlj82.github.io/Debye-theory/) · [source](https://github.com/lshlj82/Debye-theory) |
| 8 | Bose–Einstein condensation | 보스–아인슈타인 응축 | [demo](https://lshlj82.github.io/BEC/) · [source](https://github.com/lshlj82/BEC) |
| 9 | Ising model | 이징 모형 | [demo](https://lshlj82.github.io/Ising-model-basics/) · [source](https://github.com/lshlj82/Ising-model-basics) |

## About the page · 페이지 소개

The page is a single self-contained `index.html` with no build step. Its header runs a live version of demo 2: 900 argon atoms shown in a 3D box, in 3D velocity space with a shell at the most probable speed *v*<sub>max</sub>, and as a speed histogram compared with the Maxwell distribution. A temperature slider (100–1000 K) rescales the velocities, and dragging either 3D view rotates both.

The page supports light and dark mode, adapts to phone screens, and starts the animation paused for visitors who have reduced motion turned on.

페이지는 빌드 과정 없이 `index.html` 파일 하나로 이루어져 있습니다. 상단에서는 데모 2를 실시간으로 실행하여, 아르곤 원자 900개를 3차원 상자, 3차원 속도 공간, 맥스웰 분포와 비교한 속력 히스토그램으로 보여줍니다.

## Running locally · 로컬에서 실행

Open `index.html` in any modern browser. Fonts load from Google Fonts when online and fall back to system fonts otherwise.

## Deploying · 배포

1. Put `index.html` and this `README.md` at the root of the repository.
2. In **Settings → Pages**, set the source to the `main` branch, root folder.
3. The page will be served at `https://lshlj82.github.io/<repository-name>/`.

## References · 참고문헌

- Daniel V. Schroeder, *An Introduction to Thermal Physics* (Oxford University Press, 2021; originally Addison Wesley Longman, 2000).
- Prof. Sang Hoon Lee, lecture notes for Statistical Physics 2. (이상훈 교수, 통계물리2 강의 노트)
