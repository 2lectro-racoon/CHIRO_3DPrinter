# CHIRO_3DPrinter_GUIDE
이 repo는 중앙대학교 통일공대 로봇 동아리 CHIRO를 위한 3D 프린터 사용 가이드 및 정비 가이드 관련 문서입니다.

# [예약 구글 스프레드 시트](https://docs.google.com/spreadsheets/d/1wqA8Xc8Nbucf8mbVy7zQWF-za3Rr88YbO-wAvKrq4g4/edit?usp=sharing)

### 꼭 위 시트에서 예약하시고 사용해주세요. 시트에 적혀있지 않는 경우, 취소시킬 수 있습니다.

### 소요시간은 슬라이서에서 나오는 시간보다 한시간정도 여유롭게 작성해주세요.

### 필라멘트 사용량또한 기록 해주세요.

![슬라이서 정보](images/slice_info.png)
우측 하단에 보면 소요시간, 필라멘트 사용량이 계산되어 나옵니다.

이 내용을 링크에 있는 스프레드 시트에 작성해주시면 되는데, 프린터를 맞게 선택하였는지 확인하시고 작성해주세요.

작성되어있지 않는 상태로 출력중인 경우, 취소될 가능성이 있습니다.

(https://docs.google.com/spreadsheets/d/1wqA8Xc8Nbucf8mbVy7zQWF-za3Rr88YbO-wAvKrq4g4/edit?usp=sharing)

#

# [동아리 Prusa Slicer 사용법](https://github.com/2lectro-racoon/CHIRO_3DPrinter/tree/main/PrusaSlicer)
슬라이서는 프루사슬라이서를 선택하였습니다.

위의 제목을 클릭하면 프루사슬라이서 초기 설정법 화면으로 이동합니다.

#

# [필라멘트 교체방법](https://github.com/2lectro-racoon/CHIRO_3DPrinter/tree/main/Maintenance_Guide/Filament_Change)
필라멘트 교체 방법입니다.

작성예정입니다.

#

# Voron 2.4 300mm
![Voron](images/voron_2.4.jpeg)
빌드 사이즈 300 * 300 * 200을 가진 프린터로 기본적으로 PLA 세팅만 제공합니다. 추후 ABS사용에도 문제는 없습니다.

기본적으로 Voron 2.4의 bom 및 조립 가이드 기반으로 빌드하였지만, 프레임에 사용된 프로파일이 미스미 규격이 아닌 국산 프로파일로 홈이 5mm입니다.

이에 따라 수정된 출력 파일을 사용하였고 해당 파일을 정비가이드에 첨부하였습니다.

#

# Sapphire plus trident
![Sapphire](images/sapphire_plus.jpeg)
사파이어 플러스 v3 기반으로 Voron trident로 개조한 프린터 입니다.

300 * 300 * 250의 빌드 사이즈를 가졌으며 기본적으로 PLA 세팅만 제공됩니다.

미스미 프로파일을 사용하였으며, 사용된 출력파일의 출처는 아래와 같습니다만 약간에 변형이 들어갔습니다.

https://github.com/pure100kim/Sapphire_Plus_Trident/tree/main

#

# Ender3
![ender3](images/ender3.jpeg)
Ender3 v2에서 듀얼 z축, 툴헤드만 Voron stealthburner로 변경된 프린터 입니다.

툴헤드 변경에 따라 y축 빌드 영역이 감소하였습니다. 235 * 200 * 150

이 부분을 해결하기 위해 추후 Voron SwitchWire로 변경할 작업을 고민중에 있습니다.

#

# [Klipper Firmware](https://www.klipper3d.org)
현재 동아리방에 있는 프린터 모두 Klipper 펌웨어를 사용합니다.

관련 문서는 https://www.klipper3d.org 여기서 확인 할 수 있습니다.

#

# [Voron](https://vorondesign.com)
동아리의 프린터들은 대다수 Voron Design 기반으로 제작되었습니다.

https://vorondesign.com

오픈소스 프린터로, 제작을 위한 bom과 조립 메뉴얼, 기본 설정법들이 공유되어있습니다.

#