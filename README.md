# Building a Secure Mobile Continuous Integration Pipeline for Android Native Applications GitHub Repository
This repository was created during the bachelor thesis at the FH Campus Wien.

This project is a fork of a project of the OWASP, the 'MASTG Hacking Playground', and was completed with essential documents and some files.

Most important is the folder 'Documents', where all reports and evaluations are located, which were created during this work.

The following important documents are available:
- **Reports**: Several report files in the folder are the results of Bitrise pipeline steps.
- **BitriseSteps.xlsx/BitriseSteps.md**: These files contain a list of all pipeline steps of Bitrise from the category 'Utility' and 'Test'. In addition, they have been organized by category and provided with notes and a website for more information. The Excel file can also be filtered by other criteria using the filter method.
- **checklist.xlsx**: This is the OWASP MAS checklist adapted with the tested tools from Bitrise. The tools were entered into the checklist, and an 'x' was made for each vulnerability that a tool reveals/fixes in order to be able to check and compare the effectiveness at the end.
- **bitrise.yml**: This is the YAML file of the final pipeline created and used after the analysis and research on bitrise. Here the most effective security tools from bitrise have been used in combination.
- **bitrise_primary.yml**: This is a primary Bitrise pipeline without security tools.


The MASTG Hacking Playground is a collection of educational iOS and Android mobile apps intentionally built insecurely to give practical guidance to developers, security researchers, and penetration testers. However, this project's source code was reduced to the Android Kotlin app and stored in this repo. For more information on the app, visit the OWASP project.

