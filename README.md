JavaFX Mail Client

A simple desktop email client application built with Java and JavaFX.
This project demonstrates sending, replying, and composing emails using a controller-based architecture with FXML-based user interfaces.

Features

Send emails

Reply to emails

Compose new email messages

JavaFX-based desktop UI

FXML + Controller structure

Configurable mail host settings

Technologies Used

Java

JavaFX

FXML

SMTP (Email sending logic)

MVC-inspired architecture

Project Structure

src/
controllers/
ComposeController.java
ReplyController.java
NewHostController.java
FXMLDocumentController.java

models/
Email.java
HostConfig.java

services/
EmailService.java

views/
FXMLDocument.fxml
ComposeView.fxml
ReplyView.fxml

AdvanceJavaProject3.java

How to Run

Clone the repository:
git clone https://github.com/your-username/javafx-mail-client.git

Open the project in an IDE such as IntelliJ IDEA or NetBeans

Make sure JavaFX is correctly configured in your environment

Run the main class:
AdvanceJavaProject3.java

Application Screens

Main Mail Screen

Compose Email Screen

Reply Email Screen

Host Configuration Screen

All interfaces are built using FXML.

Notes

This project is developed for educational and academic purposes

SMTP host information and credentials must be provided manually

The project can be extended with inbox listing, attachments, database integration, and authentication improvements
