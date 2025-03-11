**** Tracing-Dokumentation

Diese Tabelle zeigt die Verbindung zwischen UML-Diagramm und Code-Implementierung:

**** UML-Klassen und ihre Implementierung im Code:
| UML-Klasse              | Code-Klasse                                         | GitLab-Link |
|-------------------------|----------------------------------------------------|-------------|
| User                   | com.example.demo.model.User                        | [User.java]() |
| AccountService         | com.example.demo.service.AccountService            | [AccountService.java](https://git.informatik.uni-rostock.de/softwaretechnik-ws-2024-25/uebung2/team1/projekt-team1-uebung2/-/blob/02c46e1fc77e9cd8fb7b02a03ef2dea1292c11da/Team1_demo_project/src/AccountService.java) |
| DatabaseManager        | com.example.demo.repository.DatabaseManager        | [DatabaseManager.java]()|
| EmailVerificationService | com.example.demo.service.EmailVerificationService | [EmailVerificationService.java]() |
| PasswordHasher         | com.example.demo.service.PasswordHasher           | [PasswordHasher.java]() |

**** UML-Interfaces und ihre Implementierung im Code:
| UML-Interface          | Code-Interface                                     | GitLab-Link |
|------------------------|---------------------------------------------------|-------------|
| IAccountManagement     | com.example.demo.interfaces.IAccountManagement     | [IAccountManagement.java]() |
| IUserAuthentication    | com.example.demo.interfaces.IUserAuthentication    | [IUserAuthentication.java]() |
| IEmailVerification     | com.example.demo.interfaces.IEmailVerification     | [IEmailVerification.java]() |
| IPasswordHasher        | com.example.demo.interfaces.IPasswordHasher        | [IPasswordHasher.java]() |

Diese Annotation-basierte Tracing-Strategie stellt sicher, dass jede Code-Klasse und jedes Interface direkt mit einer UML-Komponente verknüpft ist.
