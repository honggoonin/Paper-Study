# 1. Embedded Security

## Embedded Device Hacking
* Fyrbiak, Marc, et al. **"Hardware reverse engineering: Overview and open challenges."** 2017 IEEE 2nd International Verification and Security Workshop (IVSW). IEEE, 2017. 

* Quadir, Shahed E., et al. **"A survey on chip to system reverse engineering."** ACM journal on emerging technologies in computing systems (JETC) 13.1 (2016): 1-34.
  * _칩, 보드, 시스템 리버싱 및 안티리버싱 기법 정리한 서베이 논문 (우선 시스템 리버싱만 정리)_

## Firmware Emulation
* Zaddach, Jonas, et al. **"AVATAR: A Framework to Support Dynamic Security Analysis of Embedded Systems' Firmwares."** NDSS. Vol. 14. 2014.
  * _펌웨어 에뮬레이팅을 위해 AVATAR 도구가 물리 장치와 외부 에뮬레이터 사이의 중간 인터페이스 역할 수행_
  
* Gustafson, Eric, et al. **"Toward the analysis of embedded firmware through automated re-hosting."** 22nd International Symposium on Research in Attacks, Intrusions and Defenses ({RAID} 2019). 2019.
  * _펌웨어 동적분석을 위한 에뮬레이팅 기법으로 '펌웨어 리호스팅' 제시. 펌웨어를 하드웨어 환경에서 가상환경으로 옮겨 오는 절차. 주변장치 모델 생성하는 방식으로, 분석을 위한 가상환경 자동 생성 (PRETENDER)_


## Code Deobfuscation
* Yadegari, Babak, et al. **"A generic approach to automatic deobfuscation of executable code."** 2015 IEEE Symposium on Security and Privacy. IEEE, 2015.
  * _에뮬레이션 기반 난독화, ROP 방식 난독화에 대해 taint analysis를 적용해 프로그램의 semantic 파악하고, 로직을 단순화하여 CFG 생성하는 기법_

* Liang, Mingyue, et al. **"Deobfuscation of virtualization-obfuscated code through symbolic execution and compilation optimization."** International Conference on Information and Communications Security. Springer, Cham, 2017.
  * _가상화 난독화(virtualization-obfuscation)에 대해 recording, symbolic execution, 컴파일 최적화를 이용해 역난독화 시도_

* Baldoni, Roberto, et al. **"A survey of symbolic execution techniques."** ACM Computing Surveys (CSUR) 51.3 (2018): 1-39.
  * _역난독화를 위한 symbolic execution 서베이 논문 분석_
 

## Code Obfuscation and Diversification
* Zheng, Jason X., Dongfang Li, and Miodrag Potkonjak. **"A secure and unclonable embedded system using instruction-level PUF authentication.”** 2014 24th International Conference on Field Programmable Logic and Applications (FPL). IEEE, 2014.
  * _PUF를 이용하여 실행 머신코드와 실행 환경이 명령어 수준에서 서로 인증하도록 하는 기법_

* Chang, Chip-Hong, Yue Zheng, and Le Zhang. **"A retrospective and a look forward: Fifteen years of physical unclonable function advancement."** IEEE Circuits and Systems Magazine 17.3 (2017): 32-62.
  * _PUF의 개념, 특징, 활용 및 공격 정리 (논문 + a)_

* Hosseinzadeh, Shohreh & Hyrynsalmi, Sami & Leppänen, Ville. **'Obfuscation and Diversification for Securing the Internet of Things (IoT)'** (2016). 10.1016/B978-0-12-805395-9.00014-9. 
  * 경량화 된 보안 기법 필요 (다양화, 난독화)  

* Fyrbiak, Marc, et al. **"Hybrid obfuscation to protect against disclosure attacks on embedded microprocessors."** IEEE Transactions on Computers 67.3 (2017): 307-321. 
