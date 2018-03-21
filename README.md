# Vapor-CheatSheet

### Vapor
| Command | Description |
| ----------- | ----------- |
| vapor new PROJECT_NAME | Creates a new Vapor Project for you |
| vapor new PROJECT_NAME --branch=beta | Uses beta version of vapor to create new project |
| vapor build | The Swift Package Manager will first start by downloading the appropriate dependencies from git. It will then compile and link these dependencies together. |
| vapor run serve | You should see a message Server starting.... You can now visit localhost:8080/plaintext in your browser or run |
| vapor xcode | Creates a xcode project for you |
| vapor heroku init | create new heroku app for you and deploys to it |
| vapor heroku push | deploys your app to heroku |
| vapor run prepare --revert --all | drop the db and run all preparations |

### Heroku
| Command | Description |
| ----------- | ----------- |
| vapor heroku push | pushes master to heroku |
| heroku run .build/release/Run prepare --revert | revert the db and run all preparations|

### Vapor Cloud

| Command | Description |
| ----------- | ----------- |
| vapor login | login in on vapor.cloud |
| vapor deploy | deploy all of your projects |
| vapor cloud logs --since=2h | show logs |
