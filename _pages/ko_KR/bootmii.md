---
title: "BootMii 백업"
---

{% include toc title="Table of Contents" %}

이 자습서와 관련하여 도움이 필요하면 [RiiConnect24 디스코드 서버](https://discord.gg/rc24) (추천)에 가입하시거나, [support@riiconnect24.net](mailto:support@riiconnect24.net)로 이메일을 보내주세요.
{: .notice--info}

![BootMii 로고](/images/bootmii.png)

BootMii를 사용하여 NAND 백업을 생성하려면 **SD 카드**가 필요합니다. 백업이 없는 경우 이 페이지를 건너뛰어도 되지만, 가능하면 NAND 백업을 만드는 것이 좋습니다.
{: .notice--warning}

BootMii를 boot2로 설치하는 것이 좋지만 초기 Wii 콘솔에만 설치할 수 있습니다. 그렇지 않으면 IOS로만 설치할 수 있습니다.
{: .notice--info}

BootMii의 가장 중요한 기능 중 하나는 Wii의 NAND 스토리지를 백업하고 복원하는 기능입니다. NAND 백업을 수행하는 방법을 살펴보겠습니다. 그런 다음 어떤 이유로든 해당 백업에서 복원할 수 있습니다. 정기적으로 또는 콘솔에 위험한 작업을 수행하기 전에 NAND 백업을 하는 것이 좋습니다 (수행 방법을 알고 있다면 위험한 작업을 수행할 필요가 없습니다).

#### 필요한 것

- 적어도 512MB 이상의 SD 카드

#### 사용 방법

BootMii를 boot2로 설치한 경우 콘솔을 재시작하여 BootMii를 시작해야 합니다. 이 경우 1단계와 2단계를 건너뜁니다.
{: .notice--info}

1. 홈브류 채널을 시작합니다.

2. 홈 버튼을 누른 다음 "BootMii 실행"을 선택합니다.![BootMii_Main](/images/BootMii/BootMii_Main.png)

`BootMii 실행` 버튼이 나타나지 않으면, [HackMii 설치 프로그램을 재실행](hackmii)하고 BootMii를 설치하세요.
{: .notice--info}

Wii 리모컨으로는 BootMii를 탐색할 수 없습니다. 콘솔의 전원 및 재설정 버튼 또는 포트 1에 연결된 게임큐브 컨트롤러를 사용해야 합니다. 옵션 사이를 탐색하려면 Wii에서 전원 버튼을 누릅니다 (또는 게임큐브 컨트롤러의 +컨트롤 패드 의 왼쪽/오른쪽 버튼을 누릅니다.) 옵션을 선택하려면 Wii에서 RESET을 누르거나 게임큐브 컨트롤러에서 A 버튼을 누릅니다.
{: .notice--info}

화면이 검은색으로 유지되고 파란색 디스크 드라이브 표시등이 깜박이면 SD 카드에 BootMii 파일이 누락된 것입니다. [이 zip 파일](https://static.hackmii.com/bootmii_sd_files.zip)을 다운로드하여 SD 카드의 루트에 압축을 푼 다음 다시 시도하세요.
{: .notice--warning}

3. 옵션 버튼 (톱니바퀴가 있는 아이콘) 을 선택합니다.![BootMii_Gears_Icon](/images/BootMii/BootMii_Gears_Icon.png)

4. BackupMii 버튼을 선택합니다.![BootMii_Green_Arrow](/images/BootMii/BootMii_Green_Arrow.png)

   - NAND 백업이 시작됩니다. 화면에서 진행 상황을 확인할 수 있습니다.
   - "배드 블록"은 정상적입니다. NAND 백업 중 일부가 보이더라도 걱정하지 마세요.
   - 이 단계가 끝나면, 백업을 확인합니다. 권장되는 기능이지만, Wii의 EJECT 버튼을 눌러 건너뛸 수도 있습니다. 디스크 드라이브에 디스크가 삽입되어 있는 경우 EJECT를 누르면 디스크도 꺼집니다.

5. 백업이 완료되면 아무 버튼이나 눌러 NAND 백업 화면을 종료합니다.![BootMii_NAND_Backup](/images/BootMii/BootMii_NAND_Backup.png)

6. BootMii를 종료하려면 뒤로 버튼 (화살표가 있는 버튼) 을 누른 다음 Wii 메뉴 버튼 또는 홈브류 채널 버튼을 눌러 원하는 위치에서 종료할 수 있습니다.![BootMii_Return_Arrow](/images/BootMii/BootMii_Return_Arrow.png)

SD 카드의 NAND 백업에서 복원하려면 RestoreMii를 사용하여 다음 지침을 따르세요. 이 기능은 혹시라도 Wii가 고장 났을 때 유용합니다. ![BootMii_Red_Arrow](/images/BootMii/BootMii_Red_Arrow.png)
{: .notice--info}

파일이 손실되지 않도록 하려면 SD 카드의 루트에서 `nand.bin` 및 `keys.bin`을 컴퓨터로 복사하는 것이 좋습니다.
{: .notice--info}

[Priiloader 설치하기로 계속하기](priiloader)<br> Priiloader는 벽돌 보호 수준을 추가하며, 특히 BootMii를 IOS로만 설치할 수 있는 경우 적극 권장합니다.
{: .notice--info}
