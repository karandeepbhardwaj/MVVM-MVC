# Battleship Game

### Installing Maven (Mac Only)
```shell
brew install maven
```

## Import Project in IntelliJ
`Open > pom.xml > Open as Project`

## Firebase Admin Credentials
Copy `firebase-admin-key.example.json` to `firebase-admin-key.json` and fill it with a local Firebase service account key. The real key file is ignored by git.

 Run:
 ```shell
 mvn install
 ```


## Run the project (direct)
```shell
mvn exec:java -Dexec.mainClass="com.soen6441.battleship.app.AppWithGUI"
```
