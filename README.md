# ense471_project

Running:
    It is possible to navigate through the app via web browser, to do so:
        - clone git repo
        - open PROJECT_ROOT/www/index.html in a web browser (navigation from page to page may not work)
        *If the WebStorm IDE is installed, running the project through WebStorm via the browser should allow navigation to work

    Android emulator (This might be a pain to get working):
        - install node.js
        - install npm (node package manager)
        - install phonegpa
        - install cordova
        - install Android Sdk (Android studio not required)
        - through the the Android SDK Manager (ANDROID_SDK_ROOT/tools/android executable), download and install the following for Android 5.0.1 (API 21):
            - Google APIs ARM EABI v7a System Image
            - Google APIs Intel x86 Atom_64 System Image
            - Google APIs Intel x86 Atom System Image
            *Only one is required however for the sake of sanity just download and install them all
        - clone the git repository
        - within the git repository, run 'cordova run android' and with any luck the emulator should boot up and the app should run


