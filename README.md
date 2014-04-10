AC-RGS-openssl
==============
Un fichier de configuration openssl pour créer une autorité de certification compatible RGS
Le projet n'a pas objectif d'être utilisé pour une AC en production. L'objectif est surtout de fournir un outil pour réaliser des tests.

Note: l'extension QCstatement n'est volontairement pas utilisée dans les certificats de signature.

Reste à faire:
- le numéro de CRL (crlnumber) ne fonctionne pas
- la durée de validée de la CRL indiquée dans le fichier de configuration ne fonctionne pas
- la base doit contenir la raison de la révocation mais pas le fichier généré
