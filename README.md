# Eines de Google

| Eina | Propòsit | Target |
| :---: | :---: | :---: |
| Gmail | Enviem correus per compartir informació | Persones o empreses |
| Calendar | Organitza el teu horari | Equips i famílies |
| Drive | Organitza els teus arxius | Qualsevol usuari |
| Docs | Fer documents | Estudiants i oficines |
| Maps | Mapes, rutes i llocs | Viatgers i empreses |
| Fulls de càlcul | Organitza despeses | Famílies i empreses |

# Diferència entre IMAP i POP3

* **IMAP:** manté els missatges al servidor i sincronitza tots els canvis en temps real entre els diferents dispositius.
* **POP3:** descarrega els correus directament a un sol dispositiu i acostuma a esborrar-los del servidor.

# Prova de etiqueta, filtres i resposta automàtica

![Prova de etiqueta, filtres i resposta automàtica](https://github.com/user-attachments/assets/4b2ea653-9fc7-4950-8529-26e21d86396e)

# Taula de paràmetres

| Protocol | Direcció | Direcció del servidor | Port | Encriptació | 
| :---: | :---: | :---: | :---: | :---: |
| POP | Entrant (rebre) | pop.gmail.com | 995 | SSL |
| SMTP | Sortint (enviar) | smtp.gmail.com | 465 | SSL/TLS |
| SMTP | Sortint (enviar) | smtp.gmail.com | 587 | TLS (STARTTLS) |

# Prova de etiqueta

![Prova de etiqueta](https://github.com/user-attachments/assets/0cc783e4-71b9-4ff4-b416-5e263a8bda7e)

# Prova de respondre el missatge

![Prova de respondre el missatge](https://github.com/user-attachments/assets/d2bf1001-899c-424f-9be3-901dbda8d42f)

# Que signifiquen SPF, DKIM, DMARC

* **SPF:**  Confirma que el servidor des d'on s'ha enviat el correu està autoritzat pel domini del remitent.
* **DKIM:** Garanteix amb una signatura digital que el contingut del missatge és íntegre i no s'ha alterat durant l'enviament.
* **DMARC:** Valida que tant SPF com DKIM són correctes i assegura que el correu és autèntic i no és una suplantació d'identitat.
