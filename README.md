![header](https://capsule-render.vercel.app/api?type=venom&color=C4C9F1&height=300&section=header&text=Sungmin_Kim%20&fontSize=90&animation=twinkling&fontColor=E3B079)

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&pause=1000&color=E3B079&center=true&vCenter=true&width=500&lines=FPGA/RTL_Engineer;Embedded_Firmware_Engineer;HW/SW_Co-Design_Architect)](https://git.io/typing-svg)

<div align="center">
  <br>
  
  ### "HW와 SW의 경계를 넘나들며 극한을 제어하는 엔지니어"

  안녕하세요! ARM Cortex-M 펌웨어 최적화부터 고속 하드웨어 아키텍처 설계까지,<br>
  단편적인 코딩을 넘어 무결점 시스템을 구현해내는 **FW & FPGA 개발자 김성민**입니다.<br>

</div>

<br>

<h3 align="center">✨ Tech Stack ✨</h3>

<div align="center">
  <img src="https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=white">
  <img src="https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white">
  <img src="https://img.shields.io/badge/Verilog-3776AB?style=for-the-badge&logo=verilog&logoColor=ffdd54">
  <img src="https://img.shields.io/badge/System_Verilog-1269D3?style=for-the-badge&logo=system_verilog&logoColor=white">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=ffdd54">
  <img src="https://img.shields.io/badge/CMake-064F8C?style=for-the-badge&logo=cmake&logoColor=white">
</div>

<div align="center">
  <img src="https://img.shields.io/badge/AXI_Stream-FF0000?style=for-the-badge&logo=xilinx&logoColor=white">
  <img src="https://img.shields.io/badge/Vitis_HLS-FF0000?style=for-the-badge&logo=xilinx&logoColor=white">
  <img src="https://img.shields.io/badge/FreeRTOS-03234B?style=for-the-badge&logo=freertos&logoColor=white">
  <img src="https://img.shields.io/badge/UART/SPI/I2C-000000?style=for-the-badge&logo=microchip&logoColor=white">
</div>

<div align="center">
  <img src="https://img.shields.io/badge/Vivado-FF0000?style=for-the-badge&logo=xilinx&logoColor=white">
  <img src="https://img.shields.io/badge/Zynq_UltraScale+-FF0000?style=for-the-badge&logo=xilinx&logoColor=white">
  <img src="https://img.shields.io/badge/STM32-03234B?style=for-the-badge&logo=stmicroelectronics&logoColor=white">
  <img src="https://img.shields.io/badge/ESP32-E7352C?style=for-the-badge&logo=espressif&logoColor=white">
  <img src="https://img.shields.io/badge/Git-F05033?style=for-the-badge&logo=git&logoColor=white">
  <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black">
</div>

<br>

## 💼 Experience

- **TelePIX (텔레픽스)** | `R&D Intern` (2026.02)
  - Zynq UltraScale+ (ZCU102) 기반 HLS 구름 감지 가속기(OCDS) 아키텍처 설계
  - FPGA 카메라 탑재체 양방향 통신(UART TMTC) 환경 구축
  - FPU 기반 카메라 제어 시스템 단위 테스트 프로그램 개발 및 검증

<br>

## 🛰️ Featured Projects

### OCDS: Zynq SoC 기반 위성 영상 클라우드 디텍션 가속기
> **Role:** Solo Developer (TelePIX Intern)
- **Overview:** 제한된 시간 내에 방대한 위성 영상 데이터를 처리하기 위한 하드웨어 가속 IP 설계
- **Key Tech:**
  - **HW Acceleration:** Vitis HLS C/C++를 활용하여 MLP 알고리즘을 하드웨어 로직으로 변환
  - **Optimization:** Array Partitioning, Pipelining, Loop Unrolling 기법을 적용하여 메모리 병목 해소 및 연산 처리량(Throughput) 극대화

### Project Z-Modem: FPGA 기반 보안 무선 통신 모뎀
> **Role:** Solo Developer
- **Overview:** UART 대역폭 한계를 극복하고 실시간 암호화 및 신호 처리를 구현한 고속 통신 시스템
- **Key Tech:**
  - **Pipeline Architecture:** UART(Stream) ↔ AES(Burst) ↔ QPSK(Stream) 간 속도 차이를 해결하는 3-Stage 파이프라인 구축
  - **CDC & Flow Control:** Async FIFO 및 Ready/Valid Handshake 프로토콜 적용으로 데이터 유실 원천 차단

### OSJ: 범용 IoT 세탁기 모니터링 시스템 아키텍처 리팩토링
> **Role:** Embedded Firmware Developer
- **Overview:** 1600줄 이상의 스파게티 레거시 코드를 전면 재설계하여 확장 가능한 모듈형 펌웨어로 구조화
- **Key Tech:** C, CMake 기반 빌드 환경 자동화, 하드웨어 추상화 계층(HAL) 분리, Doxygen 문서화

### FLP: LoRa 기반 단체 이동 이탈 감지 시스템
> **Role:** PM & Hardware/Firmware Lead
- **Overview:** 1:N 통신 환경의 충돌 제어와 저전력 최적화를 구현한 독립형 웨어러블 디바이스
- **Key Tech:** FreeRTOS Low-level 최적화, 독자적 MAC 프로토콜 도입, RF 노이즈 및 임피던스 매칭 커스텀 PCB 설계

<br>

## 🏆 Honors & Awards

- **제7회 한국코드페어 SW공모전** | `본선 진출 및 전시` (과학기술정보통신부 주최)
- **2025 빛가람 에너지 밸리 소프트웨어 작품 경진대회** | `장려상` (한전KDN)
- **2025 소프트웨어마이스터고 연합 해커톤 대회** | `우수상` (휴컨 기업상)
- **2025 교내 해커톤 대회** | `우수상` 
- **2024 빛가람 에너지 밸리 소프트웨어 작품 경진대회** | `우수상` (한전KDN)
- **2024 코딩역량인증 대회** | `동상`

<br>

## 📜 Certificates & Education

- **대덕소프트웨어마이스터고등학교** (임베디드 소프트웨어과) | `2024.03 ~ 2027.01 (졸업예정)`
- **한국정보보안교육원 교육 (Secure Coding)** | `2025.12`
  - SW 개발보안 이론, 웹 취약점 진단 및 모의해킹 실습 수료
- **국가기술자격증**
  - 정보처리기능사 (2025.04 취득)
  - 전기기능사, 전자기능사, 전자캐드기능사 (필기 합격)

<br>

[![Solved.ac Profile](http://mazassumnida.wtf/api/v2/generate_badge?boj=embksm)](https://solved.ac/embksm/)
<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=EMBKSM&show_icons=true&theme=ambient_gradient">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=EMBKSM&layout=compact" height=195>
</div>

[![EMBKSM's github activity graph](https://github-readme-activity-graph.vercel.app/graph?username=EMBKSM&theme=github-compact)](https://github.com/EMBKSM/github-readme-activity-graph)
