# Erstellen eines Microsoft Azure Pass-Abonnements

> [!NOTE] Sie werden Ihren Azure Pass einmal für jeden Kurs einlösen müssen. Falls Sie bereits ein Azure Pass-Abonnement erstellt haben, können Sie diesen Abschnitt überspringen, indem Sie unten auf **Weiter >** klicken.

> [!Knowledge] Links ohne Blitz-Symbol ( ![](https://raw.githubusercontent.com/LODSContent/ESI/master/Images/BoltIcon.png) )  werden in Ihrem lokalen Browser und nicht im Lab geöffnet. Es ist ratsam, jegliche Links direkt in den Browser im Lab einzutippen.

Das Erstellen eines Azure Pass-Abonnements ist ein zweistufiger Prozess.

1. Lösen Sie Ihren Azure Pass-Gutscheincode ein  
1. Aktivieren Sie Ihr Abonnement
1. Bitte erstellen und nutzen Sie für die Einlösung ein neues Microsoft Live ID-E-Mail-Konto. Bitte verwenden Sie zur Einlösung keine existierende E-Mail Ihres Arbeitgebers oder Bildungsinstituts. 

## Schritt 1: Einlösen eines Microsoft Azure Pass-Gutscheincodes:

1. Öffnen Sie einen Browser und navigieren Sie zu: @[www.microsoftazurepass.com][azure-pass]{powershell}

    > [!KNOWLEDGE] Es ist ratsam, sämtliche Browser zunächst zu schließen und eine neue InPrivate-Browsersitzung zu starten. Eventuell bestehende Anmeldedaten können zu Fehlern während des Aktivierungsschritts führen.

1. Klicken Sie die Start-Schaltfläche, um den Vorgang zu starten.
	
    !IMAGE[](https://lodmanuals.blob.core.windows.net/manuals/LODS%20Media/Azure%20Pass%20How-To/Updated_04_28_2020/1.jpg)	

1. Geben Sie die Anmeldeinformationen Ihres Kontos ein und wählen Sie „Anmelden“.

    !IMAGE[](https://lodmanuals.blob.core.windows.net/manuals/LODS%20Media/Azure%20Pass%20How-To/Updated_04_28_2020/2.jpg)
	
1. Wenn die korrekte E-Mail-Adresse aufgelistet wird, klicken Sie auf „Bestätigen“.

    !IMAGE[](https://lodmanuals.blob.core.windows.net/manuals/LODS%20Media/Azure%20Pass%20How-To/Updated_04_28_2020/3.jpg)
	
1. Geben Sie Ihren Gutscheincode +++@lab.CloudCredential(PromoCode).PromoCode+++ im Gutscheincode-Feld ein und klicken Sie auf „Gutscheincode einlösen“.

    !IMAGE[](https://lodmanuals.blob.core.windows.net/manuals/LODS%20Media/Azure%20Pass%20How-To/Updated_04_28_2020/4.jpg)
	
1. Es kann bis zu 5 Minuten dauern, bis der Einlösevorgang abgeschlossen ist.

    !IMAGE[](https://lodmanuals.blob.core.windows.net/manuals/LODS%20Media/Azure%20Pass%20How-To/Updated_04_28_2020/5.jpg)
	
## Schritt 2: Aktivieren Ihres Abonnements:

1. Sobald der Einlösevorgang abgeschlossen ist, werden Sie zur Anmeldeseite weitergeleitet.

1. Klicken Sie auf das Kontrollkästchen zur Einwilligung und anschließend auf die Registrieren-Schaltfläche.

    !IMAGE[](https://lodmanuals.blob.core.windows.net/manuals/LODS%20Media/Azure%20Pass%20How-To/Updated_12_4_2020/Screenshot_4.jpg)
	
1. Geben Sie Ihre Kontoinformationen ein und klicken Sie auf „Weiter“.

    !IMAGE[](https://lodmanuals.blob.core.windows.net/manuals/LODS%20Media/Azure%20Pass%20How-To/Updated_12_4_2020/Screenshot_1.jpg)
1. Es kann einige Minuten dauern, bis der Vorgang abgeschlossen ist.
    
    !IMAGE[](https://lodmanuals.blob.core.windows.net/manuals/LODS%20Media/Azure%20Pass%20How-To/Updated_12_4_2020/Screenshot_3.jpg)
	
1. Ihr Abonnement ist bereit.
	
    !IMAGE[](https://lodmanuals.blob.core.windows.net/manuals/LODS%20Media/Azure%20Pass%20How-To/Updated_04_28_2020/8.jpg)
    
1. Sie können den Stand Ihres Azure Pass Guthabens überprüfen unter @[https://www.microsoftazuresponsorships.com/balance][balance]{powershell}

    !IMAGE[](https://lodmanuals.blob.core.windows.net/manuals/LODS%20Media/Azure%20Pass%20How-To/Updated_04_28_2020/9.jpg)
    
Klicken Sie unten auf **Weiter >**, um fortzufahren.

[azure-pass]:
```
Start-Process 'www.microsoftazurepass.com'
```

[balance]:
```
Start-Process 'https://www.microsoftazuresponsorships.com/balance'
```