# Microsoft Azure Pass 구독 생성

>[!NOTE] 과정마다 새로 Azure Pass를 교환해야 합니다. 이미 Azure Pass 구독을 생성하셨다면 하단의 **다음 >**를 클릭해 이 섹션을 건너뛰어 계속해도 됩니다.

>[!KNOWLEDGE] 설명에서 번개 표시가 없는 지침의 링크는 ( ![](https://raw.githubusercontent.com/LODSContent/ESI/master/Images/BoltIcon.png) ) 랩이 아닌 로컬 브라우저로 열립니다. 랩 안의 브라우저에 직접 링크를 입력하는 것을 권장합니다.

Azure Pass 구독 생성은 2단계 과정입니다.

1. Azure Pass 프로모션 코드를 교환하세요  
1. 구독을 활성화하세요
1. 교환을 위해 새로운 Microsoft Live ID 이메일 계정을 생성하고 사용해주세요. 기존의 직장/학교 이메일은 사용하지 마십시오. 

## 1단계: Microsoft Azure Pass 프로모션 코드 교환:

1. 브라우저를 열고 다음으로 이동합니다.  +++https://www.microsoftazurepass.com/+++

    > [!KNOWLEDGE] 모든 브라우저를 닫고 새로운 In-Private 브라우저 세션을 열어주세요. 다른 로그인이 유지되면 활성화 단계에서 에러가 발생할 수 있습니다.

1. 시작하려면 "Start" 버튼을 클릭하세요.
	    
    !IMAGE[](https://lodmanuals.blob.core.windows.net/manuals/LODS%20Media/Azure%20Pass%20How-To/Updated_04_28_2020/1.jpg)	

1. 로그인 정보를 입력하고 “Sign In”을 선택하세요.

    !IMAGE[](https://lodmanuals.blob.core.windows.net/manuals/LODS%20Media/Azure%20Pass%20How-To/Updated_04_28_2020/2.jpg)

1. 올바른 이메일 주소가 나열되면 “Confirm”을 클릭하세요.

    !IMAGE[](https://lodmanuals.blob.core.windows.net/manuals/LODS%20Media/Azure%20Pass%20How-To/Updated_04_28_2020/3.jpg)

1. 프로모션 코드 +++@lab.CloudCredential(PromoCode).PromoCode+++를 프로모션 코드 박스에 입력하고“Claim Promo Code”를 클릭하세요.

    !IMAGE[](https://lodmanuals.blob.core.windows.net/manuals/LODS%20Media/Azure%20Pass%20How-To/Updated_04_28_2020/4.jpg)

1. 교환 과정이 최대 5분 정도 걸릴 수 있습니다.

    !IMAGE[](https://lodmanuals.blob.core.windows.net/manuals/LODS%20Media/Azure%20Pass%20How-To/Updated_04_28_2020/5.jpg)

## 2단계: 구독을 활성화하세요.


1. 상환 프로세스가 완료되면 가입 페이지로 리디렉션됩니다.

1. 계약 확인란을 클릭하고 가입 버튼을 클릭합니다.

    !IMAGE[](https://lodmanuals.blob.core.windows.net/manuals/LODS%20Media/Azure%20Pass%20How-To/Updated_12_4_2020/Screenshot_4.jpg)

1. 계정 정보를 입력하고 "Submit"을 클릭합니다.

    !IMAGE[](https://lodmanuals.blob.core.windows.net/manuals/LODS%20Media/Azure%20Pass%20How-To/Updated_12_4_2020/Screenshot_1.jpg)

1. 요청을 처리하는 데 몇 분 정도 걸릴 수 있습니다.

    !IMAGE[](https://lodmanuals.blob.core.windows.net/manuals/LODS%20Media/Azure%20Pass%20How-To/Updated_12_4_2020/Screenshot_3.jpg)

1. 구독이 준비되었습니다.

    !IMAGE[](https://lodmanuals.blob.core.windows.net/manuals/LODS%20Media/Azure%20Pass%20How-To/Updated_04_28_2020/8.jpg)
    
1. Azure Pass 크레딧 잔액을 @[https://www.microsoftazuresponsorships.com/balance][balance]{powershell}에서 확인할 수 있습니다.

    !IMAGE[](https://lodmanuals.blob.core.windows.net/manuals/LODS%20Media/Azure%20Pass%20How-To/Updated_04_28_2020/9.jpg)
    
아래의 **다음 >**를 클릭하여 계속합니다.

[azure-pass]:
```
Start-Process 'www.microsoftazurepass.com'
```

[balance]:
```
Start-Process 'https://www.microsoftazuresponsorships.com/balance'
```