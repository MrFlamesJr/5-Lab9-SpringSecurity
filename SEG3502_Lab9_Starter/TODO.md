# TODO

Add the second user: user2 with pass2


- Start the app:
  ```powershell
  .\gradlew.bat bootRun
  ```

- Screenshot an unauthenticated request (should return 401 Unauthorized):
  ```powershell
  curl.exe http://localhost:8080/temperature-converter/celsius-fahrenheit/50
  ```

- Screenshot a successful request with user1:
  ```powershell
  curl.exe -u user1:pass1 http://localhost:8080/temperature-converter/celsius-fahrenheit/50
  ```

- Screenshot a successful request with user2:
  ```powershell
  curl.exe -u user2:pass2 http://localhost:8080/temperature-converter/fahrenheit-celsius/122
  ```
