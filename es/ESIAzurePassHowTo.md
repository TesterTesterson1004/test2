# Crear una suscripción a Microsoft Azure Pass

> [!NOTE] Deberá canjear su Azure Pass una vez por curso. Si ya ha creado una suscripción de Azure Pass, puede omitir esta sección haciendo clic en **Siguiente>** abajo para continuar.

> [!Knowledge]  Los enlaces en las instrucciones que no tienen un icono de rayo ( ![](https://raw.githubusercontent.com/LODSContent/ESI/master/Images/BoltIcon.png) )  intentarán abrirse en su navegador local, no en el laboratorio. Se recomienda escribir los enlaces directamente en el navegador del laboratorio.

Crear una suscripción a Azure Pass es un proceso en dos pasos.

1. Canjee su código promocional de Azure Pass  
1. Active su suscripción
1. Cree y use una cuenta de correo electrónico de New Microsoft Live ID para el canje. No haga el canje con su correo electrónico laboral o escolar existente. 

## Paso 1: Canjear un código promocional de Microsoft Azure Pass:

1. Abra un navegador y vaya a: @[www.microsoftazurepass.com][azure-pass]{powershell}

    > [!KNOWLEDGE] Se recomienda cerrar todos los navegadores y abrir una nueva sesión privada en el navegador. De lo contrario, pueden quedar otras sesiones abiertas y generar errores durante el paso de la activación.

1. Haga clic en el botón de inicio para comenzar.
	
    !IMAGE[](https://lodmanuals.blob.core.windows.net/manuals/LODS%20Media/Azure%20Pass%20How-To/Updated_04_28_2020/1.jpg)	

1. Ingrese la información de inicio de sesión de su cuenta y seleccione "Iniciar sesión".

    !IMAGE[](https://lodmanuals.blob.core.windows.net/manuals/LODS%20Media/Azure%20Pass%20How-To/Updated_04_28_2020/2.jpg)
	
1. Haga clic en "Confirmar" si aparece la dirección de correo electrónico correcta.

    !IMAGE[](https://lodmanuals.blob.core.windows.net/manuals/LODS%20Media/Azure%20Pass%20How-To/Updated_04_28_2020/3.jpg)
	
1. Ingrese el código promocional +++@lab.CloudCredential(PromoCode).PromoCode+++ en el cuadro Código de promoción y haga clic en "Validar código de promoción".

    !IMAGE[](https://lodmanuals.blob.core.windows.net/manuals/LODS%20Media/Azure%20Pass%20How-To/Updated_04_28_2020/4.jpg)
	
1. El proceso de canje puede tardar hasta 5 minutos.

    !IMAGE[](https://lodmanuals.blob.core.windows.net/manuals/LODS%20Media/Azure%20Pass%20How-To/Updated_04_28_2020/5.jpg)
	
## Paso 2: Activar la suscripción:

1. Una vez terminado el proceso de canje, se redireccionará a la página de registro.

1. Haga clic en la casilla de verificación del acuerdo y haga clic en el botón Registrarse.

    !IMAGE[](https://lodmanuals.blob.core.windows.net/manuals/LODS%20Media/Azure%20Pass%20How-To/Updated_12_4_2020/Screenshot_4.jpg)
	
1. Escriba la información de su cuenta y haga clic en "Enviar".

    !IMAGE[](https://lodmanuals.blob.core.windows.net/manuals/LODS%20Media/Azure%20Pass%20How-To/Updated_12_4_2020/Screenshot_1.jpg)
1. El procesamiento de la solicitud puede tardar algunos minutos.
    
    !IMAGE[](https://lodmanuals.blob.core.windows.net/manuals/LODS%20Media/Azure%20Pass%20How-To/Updated_12_4_2020/Screenshot_3.jpg)
	
1. La suscripción está lista.
	
    !IMAGE[](https://lodmanuals.blob.core.windows.net/manuals/LODS%20Media/Azure%20Pass%20How-To/Updated_04_28_2020/8.jpg)
    
1. Puede consultar el saldo de sus créditos de Azure Pass en @[https://www.microsoftazuresponsorships.com/balance][balance]{powershell}

    !IMAGE[](https://lodmanuals.blob.core.windows.net/manuals/LODS%20Media/Azure%20Pass%20How-To/Updated_04_28_2020/9.jpg)
    
Haga clic en **Siguiente >** abajo para continuar.

[azure-pass]:
```
Start-Process 'www.microsoftazurepass.com'
```

[balance]:
```
Start-Process 'https://www.microsoftazuresponsorships.com/balance'
```