# devsecops
Pre-commit hooks use a regex-based approach to seek out sensitive data.
1. Talisman - pre-commit, pre-push hook software
* prevents sensitive data from leaving the workstation
* also scans repo history to fish out secrets that may have leaked
* can be installed globally or for a single project
* https://github.com/thoughtworks/talisman
2. PIT - mutation test for Java unit tests
3. SonarQube - SAST (Static Application Security Tests)
4. Trivy - Image Scanning
