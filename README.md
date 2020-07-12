# Covid Cooperation

Living with covid is new normal, biggest challenge is tracking the infected and crowd control. Government does it with huge surveliance machinery and some time crosses personal space. Better way is to keep track of ourself and help the covid fighter. This App will help self tracking and premise crowd control, without compromising your personal space.

# ENV setup steps

1) Set up Amplify
```
$ amplify init
? Enter a name for the project: rnamplify
? Enter a name for the environment: demo
? Choose your default editor: <Your favorite text editor>
? Choose the type of app that you're building: javascript
? What javascript framework are you using: react-native
? Source Directory Path:  /
? Distribution Directory Path: /
? Build Command:  npm run-script build
? Start Command: npm run-script start
? Do you want to use an AWS profile? Y
? Please choose the profile you want to use: <Your AWS profile from the configuration step>
```
2) Install dependencies
```
npm install aws-amplify aws-amplify-react-native amazon-cognito-identity-js @react-native-community/netinfo
```
3) Create authentication service
```
$ amplify add auth
? Do you want to use the default authentication and security configuration? Default configuration
? How do you want users to be able to sign in? Username
? Do you want to configure advanced settings?  No, I am done.
```
4) Deploy the authentication function
```
amplify push
```

# Reference 

https://github.com/itzpradip/react-navigation-v5-mix

https://docs.amplify.aws/start/q/integration/react-native
