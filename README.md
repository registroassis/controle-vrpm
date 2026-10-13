# Controle VRPM

Site do sistema Controle VRPM (imóveis, parcelas, lançamentos, contas fixas, locação e curta temporada).

- Hospedagem: GitHub Pages (este repositório, branch `main`, pasta raiz).
- Login e dados: Firebase (Authentication por e-mail/senha + Cloud Firestore).
- `config.js`: dados do projeto Firebase e e-mail da administradora.
- `firestore.rules`: regras de acesso (cole no Firebase console › Firestore › Regras).

Nenhum dado financeiro fica neste repositório: tudo fica no Firestore, protegido pelas regras.
Acesso: só a administradora e os e-mails incluídos na tela **Usuários** do sistema, com e-mail confirmado.
