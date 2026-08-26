# Gemensamt repository i utvecklingsteam

>Ett utvecklingsteam använder ett repository så att alla jobbar mot samma kodbas, men i var sin *branch*. Var och en kan jobba ostört i sin egen *branch* utan att påverkas av de andras tillfälliga buggar under utvecklingen. När de är färdiga med sina ändringar *mergas* *branchen* in till en gemensam *branch* för testning, så att de olika ändringarna fungerar tillsammans innan deployment.
>
>Om någon ändring inte fungerar önskvärt, tar man bort de *commits* som innehåller ändringen före deployment. Utan repository kan det bli ett väldigt pilligt och tidskrävande arbete med stor risk för misstag och nya buggar.

---
### Sammanfattning
- Alla använder samma kodbas
- Var och en jobbar ostört med sina ändringar
- Ändringarna samlas i gemensam *branch* för test innan deployment
- Oönskade ändringar tas enkelt bort innan deployment
