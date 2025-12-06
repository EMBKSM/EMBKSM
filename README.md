![header](https://capsule-render.vercel.app/api?type=venom&color=C4C9F1&height=300&section=header&text=Sungmin_Kim%20&fontSize=90&animation=twinkling&fontColor=E3B079)

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&pause=1000&color=E3B079&center=true&vCenter=true&width=435&lines=FPGA/RTL_Engineer;Embedded_Firmware_Engineer;Hardware_Software_Co-Design)](https://git.io/typing-svg)

<div align="center">
  <br>
  
  ### "단순 개발을 넘어, 깊은 곳까지 잠수하는 엔지니어"

  안녕하세요! 하드웨어의 바닥부터 소프트웨어의 끝단까지 연결하는 **FW & FPGA 개발자 김성민**입니다.<br>

</div>

<br>

<h3 align="center">✨ Tech Stack ✨</h3>

<div align="center">
  <img src="https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=white">
  <img src="https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white">
  <img src="https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=csharp&logoColor=white">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=ffdd54">
  <img src="https://img.shields.io/badge/Verilog-3776AB?style=for-the-badge&logo=verilog&logoColor=ffdd54">
  <img src="https://img.shields.io/badge/System_Verilog-1269D3?style=for-the-badge&logo=system_verilog&logoColor=white">
  <img src="https://img.shields.io/badge/Tcl-A8B9CC?style=for-the-badge&logo=tcl&logoColor=white">
</div>

<div align="center">
  <img src="https://img.shields.io/badge/AXI4-FF0000?style=for-the-badge&logo=xilinx&logoColor=white">
  <img src="https://img.shields.io/badge/OCP-000000?style=for-the-badge&logo=OCP&logoColor=white">
  <img src="https://img.shields.io/badge/Ethernet-000000?style=for-the-badge&logo=ethernet&logoColor=white">
  <img src="https://img.shields.io/badge/PCIe-000000?style=for-the-badge&logo=pcie&logoColor=white">
  <img src="https://img.shields.io/badge/MQTT-3C873A?style=for-the-badge&logo=mqtt&logoColor=white">
  <img src="https://img.shields.io/badge/FreeRTOS-03234B?style=for-the-badge&logo=freertos&logoColor=white">
</div>

<div align="center">
  <img src="https://img.shields.io/badge/Vivado-FF0000?style=for-the-badge&logo=xilinx&logoColor=white">
  <img src="https://img.shields.io/badge/Vitis-FF0000?style=for-the-badge&logo=xilinx&logoColor=white">
  <img src="https://img.shields.io/badge/Zynq_7000-FF0000?style=for-the-badge&logo=xilinx&logoColor=white">
  <img src="https://img.shields.io/badge/STM32-03234B?style=for-the-badge&logo=stmicroelectronics&logoColor=white">
  <img src="https://img.shields.io/badge/ESP32-E7352C?style=for-the-badge&logo=espressif&logoColor=white">
  <img src="https://img.shields.io/badge/Git-F05033?style=for-the-badge&logo=git&logoColor=white">
  <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black">
</div>

<br>

## 🛰️ Featured Projects

### Project Z-Modem: FPGA-based Secure QPSK Image Transceiver
> **Role:** Solo Developer (Architecture, RTL Design, Signal Processing)
- **Overview:** UART 대역폭 한계를 극복하고 보안성을 확보한 FPGA 기반 이미지 무선 송수신 시스템
- **Key Tech:**
  - **Pipeline Design:** UART(Stream) ↔ AES(Burst) ↔ QPSK(Stream) 간 속도 차이(Mismatch)를 해결하는 3-Stage 파이프라인 구축
  - **Signal Processing:** Costas Loop & Gardner Loop를 Verilog로 직접 구현하여 위상/동기화 복원
  - **Communication:** Ready/Valid Handshake 프로토콜을 통한 안정적인 Flow Control

### FLP (Find Lost People): LoRa-based Location Tracker
> **Role:** PM & Hardware/Firmware Lead
- **Overview:** 인터넷이 없는 환경에서도 장거리 위치 추적이 가능한 LoRa 기반 이탈 감지 웨어러블 디바이스
- **Key Tech:**
  - **Custom PCB:** RF 임피던스 매칭 및 전원 노이즈 분리를 고려한 회로 설계 및 제작
  - **Firmware:** FreeRTOS 기반 태스크 스케줄링 및 선점형 MAC 프로토콜 설계로 패킷 충돌 방지
- **Achievement:** 제6회 한국코드페어 SW공모전 본선 진출 및 전시

### Health-Run: AI Posture Correction System
> **Role:** FPGA Implementation & HW Acceleration
- **Overview:** 5축 IMU 센서 데이터와 FPGA 내장 CNN 가속기를 활용한 실시간 러닝 자세 교정 시스템
- **Key Tech:**
  - **CDC:** 서로 다른 클럭 도메인 간 데이터 동기화를 위한 Async FIFO 설계
  - **Acceleration:** PS(Zynq)와 PL(FPGA) 간 AXI Interconnect를 통한 CNN 연산 오프로딩

<br>

## 🏆 Honors & Awards

- **2025 소프트웨어마이스터고 연합 해커톤 대회** | `우수상`
  - 휴컨(주) 기업상 수상
- **2024 빛가람 에너지 밸리 소프트웨어 작품 경진대회** | `우수상`
- **2025 빛가람 에너지 밸리 소프트웨어 작품 경진대회** | `장려상`
- **2025 교내 해커톤 대회** | `우수상`
- **2024 코딩역량인증 대회** | `동상`
- **제6회 한국코드페어(Korea Code Fair) SW공모전**
  - 본선 진출 및 전시 (과학기술정보통신부 주최)

<br>

## 📜 Certificates & Education

- **대덕소프트웨어마이스터고등학교** (임베디드 소프트웨어과) | `2023.03 ~ 2026.02 (졸업예정)`
- **정보보안 입문교육 (Secure Coding & Web Security)** | `KISA / 대전정보문화산업진흥원`
  - SW 보안약점(Weakness)과 취약점(Vulnerability) 분석 및 정적/동적 진단 실습
- **국가기술자격증**
  - 정보처리기능사
  - 전기기능사 (필기 합격)
  - 전자기능사 (필기 합격)
  - 전자캐드기능사 (필기 합격)

<br>

[![Solved.ac Profile](http://mazassumnida.wtf/api/v2/generate_badge?boj=embksm)](https://solved.ac/embksm/)


[![EMBKSM's github activity graph](https://github-readme-activity-graph.vercel.app/graph?username=EMBKSM&theme=github-compact)](https://github.com/EMBKSM/github-readme-activity-graph)
