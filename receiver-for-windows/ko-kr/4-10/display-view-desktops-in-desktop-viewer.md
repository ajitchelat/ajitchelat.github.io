---
layout: leftnav
title: Desktop Viewer에서 사용자 장치 표시
menu: subnav
---

Citrix Receiver for Windows에서 컴퓨터에 연결한 장치가 검색되며 호스트된 데스크톱 및 응용 프로그램에 사용할 장치를 선택할 수 있습니다.

* **Preferences(기본 설정)** > **Connections(연결)**의 설정을 사용하여 마이크 및 웹캠과 같은 장치를 가상 세션에 연결할지 여부를 사용자 지정할 수 있습니다.
* 로컬 컴퓨터에 연결된 장치가 **Preferences(기본 설정)** > **Devices(장치)**의 Device(장치) 목록에 표시됩니다.
* 장치를 연결했는데 Device(장치) 목록에 표시되지 않는 경우 **새로 고침**를 클릭합니다.
* 연결된 장치는 **최적화**, **Policy Restricted(정책 제한됨)** 또는 **Generic(일반)**으로 표시됩니다.

| 장치 | 설명 |
| --- | --- |
| 최적화 | 장치에 Citrix 가상 채널이 있고 원격 세션과 로컬 컴퓨터 모두에서 동시에 장치를 자동으로 사용할 수 있습니다. 최적화 장치의 Current Connection(현재 연결) 열에는 장치가 Local machine(로컬 컴퓨터) 및 **Remote session(원격 세션)** 모두에 연결되어 있다고 표시됩니다. Redirect(리디렉션) 확인란은 선택되어 있고 편집할 수 없습니다. Virtual Channel(가상 채널) 열의 Switch to(전환) 단추를 사용하여 최적화 및 Generic(일반) 간을 전환할 수 있습니다. 예를 들어 가상 채널에서 장치의 전체 기능을 지원하지 않는 경우 일반으로 전환을 선택합니다. |
| 일반 | 장치에 Citrix 가상 채널이 없고 원격 세션과 로컬 컴퓨터에서 동시에 장치를 사용할 수 없습니다. 장치의 가용성을 원격 세션과 로컬 컴퓨터 간에 전환하려면 Redirect(리디렉션) 확인란을 선택합니다. Current Connection(현재 연결) 열에서 현재 연결 상태를 확인할 수 있습니다. |
| 정책 제한됨 | 관리자가 이 장치 유형을 제한할 정책을 설정했습니다. 예를 들어 USB 마우스 및 키보드는 USB를 지원하지 않는 원격 세션에서 동작이 자동으로 처리되므로 기본적으로 정책에 따라 제한됩니다. 네트워크 장치와 같은 다른 장치는 보안을 위해 제한될 수도 있습니다. Policy Restricted(정책 제한됨) 장치의 Current Connection(현재 연결) 열에는 **Local machine(로컬 컴퓨터)**만 표시됩니다. Policy Restricted(정책 제한됨) 장치에서는 Redirect(리디렉션) 확인란을 선택할 수 없습니다. |

