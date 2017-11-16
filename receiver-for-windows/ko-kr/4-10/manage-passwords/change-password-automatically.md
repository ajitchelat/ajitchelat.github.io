---
layout: leftnav
title: 자동으로 암호 변경
menu: subnav
cagegory: 내 암호 관리
---

Single Sign-on 암호 변경 마법사는 식별된 프로그램에 대한 사용자 암호를 변경하는 프로세스를 자동화합니다. 회사의 Single Sign-on 설정 방식에 따라 사용자가 고유의 암호를 생성할 수도 있고 Single Sign-on이 사용자의 암호를 대신 생성할 수도 있습니다.

**참고:** 암호 변경 마법사가 생성한 암호는 문자, 숫자 및 기타 문자의 임의 조합으로 구성되므로 해당 암호의 보안 수준은 매우 높습니다. Single Sign-on에서 암호를 관리하고 사용자는 이를 기억할 필요가 없으므로 이 기능의 사용을 고려해 보십시오.

회사의 설정 방식에 따라 다음 두 가지 방법 중 하나로 암호 변경 마법사가 시작됩니다.

* 프로그램에서 사용자 암호 변경을 요구하는 경우
* 사용자가 프로그램의 암호 변경 프로세스를 시작하는 경우

경우에 따라 Single Sign-on이 암호 변경 프로세스를 감지하지 못해 암호 변경 마법사가 시작되지 않을 수 있습니다. 이 경우, 웹 사이트 또는 프로그램과 Single Sign-on 모두에서 사용자 암호를 수동으로 변경하여 암호가 일치하도록 해야 합니다.

## Choose how to create your new password(새 사용자 암호 생성 방법 선택)

회사에서 사용 가능하도록 설정한 경우, 암호 변경 마법사의 **Choose how to create your new password(새 사용자 암호 생성 방법 선택)** 페이지에서 새 사용자 암호의 생성 방법을 선택할 수 있습니다. 옵션은 다음과 같습니다.

* **Choose a system-generated password(시스템에서 생성한 암호 선택)**: 이 옵션을 선택하고 **Next(다음)**를 클릭하면 암호 변경 마법사가 보안성 높은 암호를 생성합니다. 이 암호는 Single Sign-on에 저장되고 사용자가 알 필요가 없으므로 이 프로세스 동안 사용자에게 표시되지 않습니다. 하지만 회사에서 이 기능을 수행하도록 Single Sign-on을 설정한 경우에는 사용자가 필요에 따라 마법사 종료 후에 암호를 볼 수 있습니다.

**참고**: 암호 변경 마법사가 생성한 암호는 문자, 숫자 및 기타 문자의 임의 조합으로 구성되므로 해당 암호의 보안 수준은 매우 높습니다. Single Sign-on에서 암호를 관리하고 사용자는 이를 기억할 필요가 없으므로 이 기능의 사용을 고려해 보십시오.

* **Create your own password(사용자 고유의 암호 생성)**: 이 옵션을 선택하고 **Next(다음)**를 클릭하면 암호 변경 마법사에서 사용자 고유의 암호를 생성하여 제출할 수 있습니다. 이 암호는 길이, 복잡성 및 보안에 영향을 미칠 수 있는 기타 요소와 관련하여 회사가 설정한 암호 정책을 따라야 합니다.

## Wait for confirmation(확인 대기)

암호 변경 마법사가 암호 변경의 성공 또는 실패 여부를 결정하는 동안 해당 마법사의 **Waiting for confirmation(확인 대기)** 페이지가 나타납니다.

암호 변경 마법사가 **Waiting for confirmation(확인 대기)** 페이지를 닫기 전에 사용자가 암호 변경이 성공했다고 판단한 경우 **Skip(건너뛰기)**을 클릭하여 **Confirm password change(암호 변경 확인)** 페이지로 이동합니다.

## 암호 변경 확인

회사에서 활성화한 경우 암호 변경 마법사의 Confirm password change(암호 변경 확인) 페이지가 나타날 수 있습니다. 이 페이지는 암호 변경의 성공 여부를 묻습니다. 이 경우 다음과 같은 3개의 옵션을 사용할 수 있습니다.

* **Yes(예)**: 프로그램의 암호 다시 설정 창이 나타나지 않거나 성공 메시지가 나타나면 암호 변경이 성공한 것입니다. **Yes(예)**를 선택하고 **Next(다음)**를 클릭하여 암호 변경이 성공적으로 완료되었음을 암호 변경 마법사에 알립니다. 마법사가 해당 프로세스를 종료합니다.

* **No(아니요)**: 프로그램의 암호 다시 설정 창이 계속 나타나거나 실패 메시지가 나타나면 암호 변경이 실패한 것입니다. **No(아니요)**를 선택하고 **Next(다음)**를 클릭하여 프로그램에서 새 암호가 수락되지 않았음을 암호 변경 마법사에 알립니다. 마법사가 암호를 변경하지 않고 해당 프로세스를 종료합니다.

* **I don't know(모름)**: **I don't know(모름)**를 선택하고 **Next(다음)**를 클릭하면 암호 변경 성공 여부의 확인 방법을 설명하는 페이지가 표시됩니다. 사용자 고유의 암호를 생성한 경우 마법사의 성공 여부를 확인하는 또 다른 방법은 Single Sign-on을 일시 중지하고 새 암호를 사용하여 프로그램에 로그온해 보는 것입니다.

**참고**: 프로그램의 암호 다시 설정 창이 아직 열려 있는지 또는 프로그램이 암호 관련 피드백을 제공했는지 여부를 확인하기 위해 암호 변경 마법사 창을 이동할 필요가 있을 수 있습니다.

## 암호 미변경 확인

암호 변경 마법사가 암호 변경 실패를 감지하거나 사용자가 **Confirm password change(암호 변경 확인)** 페이지에서 **No(아니요)**를 선택한 경우 **Password not changed(암호 미변경)** 페이지가 나타납니다.

**Password not changed(암호 미변경)** 페이지는 다음 두 가지 옵션을 제공합니다.

* **Try a different password(다른 암호 시도)**: 프로그램의 암호 변경 폼이 아직 열려 있는 경우에만 이 옵션을 사용합니다. 폼이 닫힌 후 사용하면 프로그램과 Single Sign-on의 암호가 일치하지 않을 수 있습니다. **Try a different password(다른 암호 시도)**를 선택하고 **Next(다음)**를 클릭하면 다른 암호를 프로그램에 제출해 볼 수 있습니다. 회사의 암호 변경 마법사 설정 방식에 따라 다음 중 하나가 나타납니다.
   * Choose how to create your new password(새 사용자 암호 생성 방법 선택) 페이지가 나타납니다. 시스템에서 생성한 암호와 사용자 자신이 생성한 암호 중에서 선택할 수 있습니다.
   * Create your own password(사용자 고유의 암호 생성) 페이지가 나타납니다.
   * 시스템에서 생성한 암호가 생성되어 제출됩니다. 그런 다음 암호 변경 마법사가 암호 변경의 성공 여부를 확인합니다.

* Exit the wizard without further action(추가 동작 없이 마법사를 종료합니다). **Exit the wizard without further action(추가 동작 없이 마법사를 종료합니다)**를 선택하면 프로그램 암호 변경의 추가 시도를 종료합니다. 하지만 나중에 암호 변경 마법사를 다시 시작하여 재시도할 수 있습니다.

## Exit the wizard without further action(추가 동작 없이 마법사를 종료합니다).

암호 변경 프로세스가 실패하거나 사용자가 **Confirm password change(암호 변경 확인)** 페이지에서 **No(아니요)**를 선택한 경우 암호 변경 마법사의 Password Not Changed(암호 미변경) 페이지가 나타납니다.

암호 변경 마법사가 실패한 경우 다음을 시도하여 사용자 암호를 변경하십시오.

* **Password Not Changed(암호 미변경)** 페이지에서 **Finish(마침)**를 클릭하여 마법사를 종료한 후 마법사를 다시 시작하여 재시도합니다.
* 프로그램과 Single Sign-on에서 암호를 수동으로 변경합니다.
* 회사의 컴퓨터 지원 부서에 도움을 요청합니다.

## 암호 변경 성공 후 마법사 종료

암호 변경 마법사가 암호 변경 성공을 감지하거나 사용자가 **Confirm password change(암호 변경 확인)** 페이지에서 **Yes(예)**를 선택한 경우 **Password Change Successful(암호 변경 성공)** 페이지가 나타납니다.

이 시점에서 새 사용자 암호가 프로그램에서 수락되고 Single Sign-on에 저장됩니다.

## 프로그램이 새 암호를 수락했는지 여부 확인

**Confirm password change(암호 변경 확인)** 페이지에서 **I don't know(모름)**를 선택하고 **Next(다음)**를 클릭하면 암호 변경 성공 여부의 확인 방법을 설명하는 페이지가 표시됩니다.

마법사의 성공 여부를 확인하는 또 다른 방법은 Single Sign-on을 일시 중지하고 새 암호를 사용하여 프로그램에 로그온해 보는 것입니다.

이 페이지에서 **Next(다음)**를 클릭하면 **Confirm password change(암호 변경 확인)** 페이지가 다시 나타납니다.

## Create your own password(사용자 고유의 암호 생성)

**Choose how to create your new password(새 사용자 암호 생성 방법 선택)** 페이지에서 Create your own password(사용자 고유의 암호 생성)를 선택한 경우 암호 변경 마법사의 **Create your own password(사용자 고유의 암호 생성)** 페이지가 나타납니다. 회사에서 사용자 고유의 암호 생성 옵션을 제공하지 않은 경우 이 페이지가 나타나지 않을 수 있습니다.

잘못 입력한 암호를 제출하지 않도록 **New Password(새 암호)**와 **Confirm new password(새 암호 확인)** 상자에 암호를 입력해야 합니다. 암호 변경 마법사는 암호가 일치하지 않을 경우 이를 알려 줍니다. 암호가 일치하면 **Next(다음)** 단추가 사용 가능하게 됩니다.

암호 변경 마법사에서는 회사가 설정한 암호 정책을 따라야 합니다. 회사가 설정할 수 있는 정책의 예는 다음과 같습니다.

* 이전 암호를 재사용할 수 없습니다.
* 암호는 숫자와 문자의 조합을 포함해야 합니다.
* 암호는 특수 문자를 포함할 수 없습니다.
* 암호는 일정한 길이여야 합니다.
