# Getting started

## Repository setup

### Requirements
- A Bitbucket account added to the [frontier repository](https://bitbucket.org/livestyled-dev/android.livestyled/src/master/)
- The [Git CLI](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git) installed

### Instructions
The above repository can be cloned by running the following terminal command within the project's directory via SSH:
SSH
```
git clone git@bitbucket.org:livestyled-dev/android.livestyled.git
```
or HTTPS:
```
git clone https://{yourusername}@bitbucket.org/livestyled-dev/android.livestyled.git
```

## Installing dependencies

### Requirements
- Android SDK 28 , 29 installend in android studio

## Switching between branches/apps
Fetch all branches using:
```
git fetch
```
Check out a branch using:
```
git checkout {branchname}
```
Reset changes using (you should do this when finished, and when switching branches):
```
git checkout .
```

## Running the project

### Instructions
1. Press the "Run app button", it will run the code in your device (if plugged and with debub mode on) or open the wizard to create an emulated device (only if you still don't have configured one before)

## Configuring environments
### To change the environment that the app points to (staging or release):
1. Open the buildVariant dialog box and select the desired environment (Debug, Alpha, Beta, Staging)

### To manually change the endpoints that the app points to:
1. Go to data/[enviroment]/res/values/string.xml
2. Change the endpoint url
3. Run the app
