# GreenMonkApp

## Installation

1. Create a new project using this template.


npx create-react-native-app --template https://github.com/karthik-hallad/GreenMonkApp

2. Make sure to follow these Configurations/Commands

   `What is your app named? ... GreenMonkApp` --while naming the project
   
   `npm i --force` -- while installing the packages

3. Update `.env` with configuration

```shell
# Replace XXXX's with your own Firebase config keys
API_KEY=XXXX
AUTH_DOMAIN=XXXX
PROJECT_ID=XXXX
STORAGE_BUCKET=XXXX
MESSAGING_SENDER_ID=XXXX
APP_ID=XXXX
```

4. Start the project:
- `expo start` --start the project
- `expo start --tunnel` --open on mobile
- `yarn ios` -- open on iOS
- `yarn android` -- open on Android
