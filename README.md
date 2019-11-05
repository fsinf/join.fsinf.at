# mm.fsinf.at

Um sich einen Account über [mattermost.fsinf.at](https://mattermost.fsinf.at/) zu erstellen, muss man bei Email seine `e<matrikel>@student.tuwien.ac.at` E-Mail-Adresse angeben, wissen wo die TU Student Webmail ist und wissen, dass man dort nicht seine E-Mail-Adresse sondern `e<matrikel>` als Usernamen verwenden muss.

Um künftigen Studierenden diese Einstiegshürde zu ersparen, wurde https://mm.fsinf.at/ entwickelt. Die Seite besteht nur aus einer einzigen HTML-Datei mit einem (Matrikel, Username, Password) Formular und einem JavaScript Code welcher die [Mattermost account creation API](https://api.mattermost.com/#tag/users%2Fpaths%2F~1users%2Fpost) verwendet. Die Same-Origin-Policy wird mittels einer NGINX reverse proxy umgangen.
