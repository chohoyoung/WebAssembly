WebAssembly
===========

# 1. WebAssembly
WebAssembly또는 wasm는 웹에 컴파일하기에 적합한 새롭고 이식이 가능한 새로운 포터블입니다. 그리고 WebAssembly는 현재 모든 브라우저를 대표하는 W3C 커뮤니티 그룹에 의해서 공개 표준으로 설계 되고 있습니다.
## 1.1 특징
### 1.1.1 Efficient and fast 
wasm 스택 머신은 크기도 작을 뿐만 아니라 로드 시간도 효율적인 바이너리 형식으로 인코딩 되도록 설계가 되어 있습니다. 또한 모든 플랫폼에서 일반적인 속도로 실행이 되도록 설계를 했습니다.
### 1.1.2 Safe
WebAssembly는 기존 JavaScript 가상 머신에서 구현 될 수 있는 메모리 safe send box 실행 환경을 구성합니다. 그리고 웹에 삽입되면 WebAssembly는 브라우저의 동일 출처 및 권한 보안정책을 적용합니다.
### 1.1.3 Open and debuggable
WebAssembly는 프로그램을 디버깅, 테스트, 실험, 최적화, 학습, 교육등을 위한 텍스트 형태로 표시 해줍니다. 텍스트 형태는 웹에서 wasm모듈의 소스를 볼때 사용됩니다.
### 1.1.4 Part of the open web platform
WebAssembly는 이전 버전의 브라우저와의 호환성을 유지 합니다. WebAssembly모듈은 Javascript에서 접근 할 수 있는 동일한 웹 API를 통해 JavaScript 컨텍스트를 호출할 수 있으며 브라우저 기능에 접근 할 수 있습니다. WebAssembly는 non-webembeddings을 지원합니다.