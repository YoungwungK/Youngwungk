# 김영웅 (Youngwung Kim)


`Network`

---

### About

인프라를 제대로 다루려면 네트워크의 근간을 먼저 이해해야 한다고 판단했습니다.
그래서 국비지원 DevOps 과정의 네트워크 커리큘럼을 수강하는 동안 **CCNA(200-301)를 직접 취득**했고,
앞으로 다룰 쿠버네티스와 AWS 과정도 수강에서 멈추지 않고 **CKA · AWS 자격증으로 검증**할 계획입니다.
자격증을 나열하려는 것이 아니라, 네트워크 → 컨테이너 → 클라우드 플랫폼으로 이어지는 스택을 단계적으로 쌓는 과정입니다.

문서에는 **"설정했다"가 아니라 "장애를 주입해 확인했다"**를 적으려고 합니다.
직전 프로젝트에서는 12개 시나리오에 대해 실제로 인터페이스를 내리고 장애 전·중·후 상태를 캡처했으며,
**검증하지 못한 항목은 생략하지 않고 한계 섹션에 그대로 남겼습니다.**
"동작하는 설계"와 "장애에도 견디는 설계"는 다르다는 것을 그 과정에서 배웠습니다.

영어(미국 중고교 졸업)와 일본어(독학, JLPT N2)로 기술 문서를 직접 읽고 씁니다.
글로벌 벤더 문서나 해외 리전 이슈 대응에서 번역본을 기다리지 않아도 되는 것이,
트러블슈팅에서는 실제 속도 차이가 된다고 생각합니다.

---

### Certifications

| | 자격증 | 상태 |
|---|---|---|
| 🌐 | **Cisco CCNA 200-301** | 2026.08 취득 · [Credly](https://www.credly.com/badges/1f991f31-251a-43f0-bf9a-d1a6704fb8e4/public_url) |
| ☁️ | AWS Certified Solutions Architect – Associate | 준비 중 |
| ⚙️ | Certified Kubernetes Administrator (CKA) | 준비 중 |

---

### Projects

**[본사–지사 이중화 네트워크 및 보안 통신망 구축](https://github.com/Youngwungk/network-redundancy-portfolio)**

게이트웨이 · 링크 · 경로 · WAN 4개 계층의 단일 장애점(SPOF)을 각각 다른 기술로 제거하고,
12개 시나리오에 장애를 직접 주입해 검증했습니다.

`HSRP + track` `LACP EtherChannel` `EIGRP 상호 재분배` `GRE over IPsec` `NAT / ACL`

→ **담당**: 토폴로지 설계 · 기술 선정 · 검증 시나리오 작성 (3인 팀, 구현 공동)
→ 초기 설계에서 코어 스위치 간 연결이 단일 트렁크로 남아 SPOF가 된다는 점을 발견하고, Port-channel 이중화로 개선했습니다.

---

### Currently

- 🎓 국비지원 DevOps 교육과정 수강 중 — Linux · Network · Database · Container · Cloud
- 📖 AWS SAA · CKA 병행 학습 중 — Kubernetes 아키텍처 / 워크로드 / 네트워킹
- 🎯 다음 목표: 위 네트워크 설계를 AWS VPC로 이식해 온프레미스 ↔ 클라우드 대응 관계를 문서화

---

### Stack

![Cisco](https://img.shields.io/badge/Cisco-1BA0D7?style=flat&logo=cisco&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazonwebservices&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat&logo=kubernetes&logoColor=white)
![MySQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=mysql&logoColor=white)

---

<details>
<summary><b>English</b></summary>


</details>

---

📫 mrwung366@gmail.com
