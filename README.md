PL:

Opis projektu:

Projekt działu wsparcia z podstawowymi funkcjonalnościami takimi jak:
- Rejestracja oraz logowanie z walidacją
- Sesja
- Dodawanie zgłoszeń przez użytkowników
- Odpowiedanie na zgloszenia przez moderatorow
- Przydzielanie moderatorow do zgloszen przez administratorow
Frontend: React, JavaScript, Bootstrap, HTML oraz CSS. Backend: Node.js. Baza danych: MySQL.


Instalacja oraz obsługa:

Aby aplikacja działała należy zainstalować odopwiednie moduły w folderach frontend oraz backend poleceniami w terminalu np. w Visual Studio Code(crtl + `):
cd frontend/backend - aby wejsc do folderu frontend lub backend
npm install - instalacja potrzebnych modułów

Aby prawidłowo włączyć aplikację będą potrzebne dwa terminale np. w programie Visual Studio Code.
Aby włączyć terminal można kliknąc crtl+` lub z górnego menu wybrać Terminal>New terminal.
W celu uruchomienia serwera należy wejść do katalogu backend (cd backend) oraz uruchomić serwer poleceniem npm start.
Teraz można włączyć drugie okienko terminalu, po prawej stronie należy kliknąc + koło terminala. W nowym terminalu musimy wejść do katalagu frontend (cd frontend) i znowu użyć polecenia npm start, teraz aplikacja będzie w pełni gotowa.

Import bazy danych:

Należy też pamiętać o zimportowaniu bazy danych o nazwie dzial_wsparcia z pliku baza_danych.sql na platforme XAMPP, phpMyAdmin, oraz aby w XAMPP control mieć włączone moduły Apache i MySQL.
W bazie danych są trzy konta, uprawnienia kont zależne są od pola "level_id", gdzie wartość 1 oznacza administratora, 2  moderatora, 3  zwykłego użykownika. Konta zostały stworzone w celu testowania funkcjonalności.
level_id domyślnie jest ustawiane na 3.



EN:

Project Description:

This is a support department project with basic functionalities such as:
- Registration and login with validation
- Session management
- Users can submit tickets
- Moderators can respond to tickets
- Administrators can assign moderators to tickets
Frontend: React, JavaScript, Bootstrap, HTML, and CSS. Backend: Node.js. Data base: MySQL.

Installation and Usage:

To run the application, you need to install the required modules in the frontend and backend folders using terminal commands, e.g., in Visual Studio Code (Ctrl + `):
cd frontend/backend - to enter the frontend or backend folder
npm install - to install the required modules

To run the application properly, you will need two terminals, e.g., in Visual Studio Code.
To open a terminal, press Ctrl + ` or select Terminal > New Terminal from the top menu.
To start the server, go to the backend directory (cd backend) and run the server with npm start.
Now you can open a second terminal window by clicking the + next to the terminal. In the new terminal, go to the frontend directory (cd frontend) and again use npm start. The application will now be fully operational.

Database Import:

Remember to import the database named dzial_wsparcia from the file baza_danych.sql using a platform like XAMPP and phpMyAdmin. Also, make sure the Apache and MySQL modules are running in the XAMPP control panel.
The database contains three accounts. Account permissions are dependent on the "level_id" field, where value 1 is the administator, 2 is the moderator, and 3 is the default user. Accounts were made to test the functionality of the application.
level_id is set to 3 by default.
