[TOC]

PS C:\VSCode> mkdir nlw5


    Diretório: C:\VSCode


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d-----        29/07/2021     12:33                nlw5


PS C:\VSCode> dir


    Diretório: C:\VSCode


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d-----        22/06/2021     20:25                Download
d-----        22/07/2021     08:14                Emoji
d-----        28/07/2021     14:44                nlw
d-----        29/07/2021     12:33                nlw5
d-----        29/07/2021     11:13                nlw5Copia
d-----        26/06/2021     14:48                nlw_together
d-----        28/06/2021     08:49                projeto
-a----        02/05/2021     19:33          46708 Shinji.JPG

__PS C:\VSCode> cd nlw5__
PS C:\VSCode\nlw5> dir
PS C:\VSCode\nlw5> expo init plantmanager
┌─────────────────────────────────────────────────────────────────────────┐
│                                                                         │
│   There is a new version of expo-cli available (4.9.0).                 │
│   You are currently using expo-cli 4.5.2                                │
│   Install expo-cli globally using the package manager of your choice;   │
│   for example: `npm install -g expo-cli` to get the latest version      │
│                                                                         │
└─────────────────────────────────────────────────────────────────────────┘
√ Choose a template: » blank (TypeScript)    same as blank but with TypeScript configuration
√ Downloaded and extracted project files.
🧶 Using Yarn to install packages.  Pass --npm to use npm instead.
√ Installed JavaScript dependencies.

✅ Your project is ready!

To run your project, navigate to the directory and run one of the following yarn commands.

- cd plantmanager
- yarn start # you can open iOS, Android, or web from here, or run them directly with the commands below.
- yarn android
- yarn ios # requires an iOS device or macOS for access to an iOS simulator
- yarn web



##### PS C:\VSCode\nlw5>

Windows PowerShell
Copyright (C) Microsoft Corporation. Todos os direitos reservados.

Experimente a nova plataforma cruzada PowerShell https://aka.ms/pscore6

PS C:\VSCode\nlw5\plantmanager> 

##### npm install --save react-native-emoji

npm WARN deprecated @hapi/address@2.1.4: Moved to 'npm install @sideway/address'
npm WARN deprecated @hapi/topo@3.1.6: This version has been deprecated and is no longer supported or maintained
npm WARN deprecated @hapi/bourne@1.3.2: This version has been deprecated and is no longer supported or maintained
npm WARN deprecated @hapi/hoek@8.5.1: This version has been deprecated and is no longer supported or maintained
npm WARN deprecated urix@0.1.0: Please see https://github.com/lydell/urix#deprecated
npm WARN deprecated resolve-url@0.2.1: https://github.com/lydell/resolve-url#deprecated
npm WARN deprecated @hapi/joi@15.1.1: Switch to 'npm install joi'
npm WARN deprecated core-js@2.6.12: core-js@<3.3 is no longer maintained and not recommended for usage due to the number of issues. Because of the V8 engine whims, feature detection in old core-js versions could cause a slowdown up to 100x even if nothing is polyfilled. Please, upgrade your dependencies to the actual version of core-js.
npm WARN deprecated fsevents@1.2.13: fsevents 1 will break on node v14+ and could be using insecure binaries. Upgrade to fsevents 2.
npm WARN deprecated sane@4.1.0: some dependency vulnerabilities fixed, support for node < 10 dropped, and newer ECMAScript syntax/features added
npm WARN deprecated uglify-es@3.3.9: support for ECMAScript is superseded by `uglify-js` as of v3.13.0
npm WARN deprecated uuid@3.4.0: Please upgrade  to version 7 or higher.  Older versions may use Math.random() in certain circumstances, which is known to be problematic.  See https://v8.dev/blog/math-random for details.
npm WARN deprecated core-js@1.2.7: core-js@<3.3 is no longer maintained and not recommended for usage due to the number of issues. Because of the V8 engine whims, 
feature detection in old core-js versions could cause a slowdown up to 100x even if nothing is polyfilled. Please, upgrade your dependencies to the actual version 
of core-js.
npm WARN deprecated deep-assign@3.0.0: Check out `lodash.merge` or `merge-options` instead.
npm WARN rm not removing C:\VSCode\nlw5\plantmanager\node_modules\.bin\semver.cmd as it wasn't installed by C:\VSCode\nlw5\plantmanager\node_modules\semver        
npm WARN rm not removing C:\VSCode\nlw5\plantmanager\node_modules\.bin\semver as it wasn't installed by C:\VSCode\nlw5\plantmanager\node_modules\semver
npm WARN rm not removing C:\VSCode\nlw5\plantmanager\node_modules\.bin\json5.cmd as it wasn't installed by C:\VSCode\nlw5\plantmanager\node_modules\json5
npm WARN rm not removing C:\VSCode\nlw5\plantmanager\node_modules\.bin\json5 as it wasn't installed by C:\VSCode\nlw5\plantmanager\node_modules\json5

> core-js@2.6.12 postinstall C:\VSCode\nlw5\plantmanager\node_modules\core-js
> node -e "try{require('./postinstall')}catch(e){}"

Thank you for using core-js ( https://github.com/zloirock/core-js ) for polyfilling JavaScript standard library!

The project needs your help! Please consider supporting of core-js on Open Collective or Patreon: 
> https://opencollective.com/core-js 
> https://www.patreon.com/zloirock 

Also, the author of core-js ( https://github.com/zloirock ) is looking for a good job -)

npm notice created a lockfile as package-lock.json. You should commit this file.
npm WARN optional SKIPPING OPTIONAL DEPENDENCY: fsevents@^1.2.7 (node_modules\jest-haste-map\node_modules\fsevents):
npm WARN notsup SKIPPING OPTIONAL DEPENDENCY: Unsupported platform for fsevents@1.2.13: wanted {"os":"darwin","arch":"any"} (current: {"os":"win32","arch":"x64"}) 
npm WARN optional SKIPPING OPTIONAL DEPENDENCY: fsevents@^1.2.7 (node_modules\jest-haste-map\node_modules\fsevents):
npm WARN notsup SKIPPING OPTIONAL DEPENDENCY: Unsupported platform for fsevents@1.2.13: wanted {"os":"darwin","arch":"any"} (current: {"os":"win32","arch":"x64"}) 
npm WARN react-native-safe-area-context@3.2.0 requires a peer of react-native@* but none is installed. You must install peer dependencies yourself.

+ react-native-emoji@1.8.0

24 packages are looking for funding
  run `npm fund` for details

found 2 low severity vulnerabilities
  run `npm audit fix` to fix them, or `npm audit` for details

PS C:\VSCode\nlw5\plantmanager>

##### expo install expo-font @expo-google-fonts/jost

┌─────────────────────────────────────────────────────────────────────────┐
│                                                                         │
│   There is a new version of expo-cli available (4.9.0).                 │
│   You are currently using expo-cli 4.5.2                                │
│   Install expo-cli globally using the package manager of your choice;   │
│   for example: `npm install -g expo-cli` to get the latest version      │
│                                                                         │
└─────────────────────────────────────────────────────────────────────────┘
Installing 1 SDK 42.0.0 compatible native module and 1 other package using Yarn.

> yarn add expo-font@~9.2.1 @expo-google-fonts/jost
> yarn add v1.22.5
> warning package-lock.json found. Your project contains lock files generated by tools other than Yarn. It is advised not to mix package managers in order to avoid resolution inconsistencies caused by unsynchronized lock files. To clear this warning, remove package-lock.json.
> [1/4] Resolving packages...
> [2/4] Fetching packages...
> info fsevents@1.2.13: The platform "win32" is incompatible with this module.
> info "fsevents@1.2.13" is an optional dependency and failed compatibility check. Excluding it from installation.
> [3/4] Linking dependencies...
> [4/4] Building fresh packages...
> success Saved lockfile.
> success Saved 4 new dependencies.
> info Direct dependencies
> ├─ @expo-google-fonts/jost@0.2.0
> info All dependencies
> ├─ @expo-google-fonts/jost@0.2.0
> ├─ lodash.toarray@4.4.0
> ├─ node-emoji@1.10.0
> └─ react-native-emoji@1.8.0
> Done in 106.97s.
>
> PS C:\VSCode\nlw5\plantmanager>
>
> ##### yarn add @react-navigation/native
>
> yarn add v1.22.5
> warning package-lock.json found. Your project contains lock files generated by tools other than Yarn. It is advised not to mix package managers in order to avoid resolution inconsistencies caused by unsynchronized lock files. To clear this warning, remove package-lock.json.
> [1/4] Resolving packages...
> [2/4] Fetching packages...
> info fsevents@1.2.13: The platform "win32" is incompatible with this module.
> info "fsevents@1.2.13" is an optional dependency and failed compatibility check. Excluding it from installation.
> [3/4] Linking dependencies...
> [4/4] Building fresh packages...
> success Saved lockfile.
> success Saved 7 new dependencies.
> info Direct dependencies
> └─ @react-navigation/native@5.9.4
> info All dependencies
> ├─ @react-navigation/core@5.15.3
> ├─ @react-navigation/native@5.9.4
> ├─ @react-navigation/routers@5.7.2
> ├─ filter-obj@1.1.0
> ├─ query-string@6.14.1
> ├─ split-on-first@1.1.0
> └─ strict-uri-encode@2.0.0
> Done in 17.71s.
> PS C:\VSCode\nlw5\plantmanager>

PS C:\VSCode\nlw5\plantmanager> 

##### expo install react-native-gesture-handler react-native-reanimated react-native-screens react-native-safe-area-context @react-native-community/masked-view

┌─────────────────────────────────────────────────────────────────────────┐
│                                                                         │
│   There is a new version of expo-cli available (4.9.0).                 │
│   You are currently using expo-cli 4.5.2                                │
│   Install expo-cli globally using the package manager of your choice;   │
│   for example: `npm install -g expo-cli` to get the latest version      │
│                                                                         │
└─────────────────────────────────────────────────────────────────────────┘
Installing 5 SDK 42.0.0 compatible native modules using Yarn.

> yarn add react-native-gesture-handler@~1.10.2 react-native-reanimated@~2.2.0 react-native-screens@~3.4.0 react-native-safe-area-context@3.2.0 @react-native-community/masked-view@0.1.10
> yarn add v1.22.5
> warning package-lock.json found. Your project contains lock files generated by tools other than Yarn. It is advised not to mix package managers in order to avoid resolution inconsistencies 
> caused by unsynchronized lock files. To clear this warning, remove package-lock.json.
> [1/4] Resolving packages...
> [2/4] Fetching packages...
> info fsevents@1.2.13: The platform "win32" is incompatible with this module.
> info "fsevents@1.2.13" is an optional dependency and failed compatibility check. Excluding it from installation.
> [3/4] Linking dependencies...
> [4/4] Building fresh packages...

success Saved lockfile.
success Saved 11 new dependencies.
info Direct dependencies
├─ @react-native-community/masked-view@0.1.10
├─ react-native-gesture-handler@1.10.3
├─ react-native-reanimated@2.2.0
└─ react-native-screens@3.4.0
info All dependencies
├─ @egjs/hammerjs@2.0.17
├─ @react-native-community/masked-view@0.1.10
├─ @types/hammerjs@2.0.40
├─ cross-fetch@3.1.4
├─ hoist-non-react-statics@3.3.2
├─ mockdate@3.0.5
├─ react-native-gesture-handler@1.10.3
├─ react-native-reanimated@2.2.0
├─ react-native-screens@3.4.0
├─ string-hash-64@1.0.3
└─ warn-once@0.1.0
Done in 18.28s.

PS C:\VSCode\nlw5\plantmanager> 

##### npm install @react-navigation/stack

npm WARN rm not removing C:\VSCode\nlw5\plantmanager\node_modules\.bin\semver.cmd as it wasn't installed by C:\VSCode\nlw5\plantmanager\node_modules\semver
npm WARN rm not removing C:\VSCode\nlw5\plantmanager\node_modules\.bin\semver as it wasn't installed by C:\VSCode\nlw5\plantmanager\node_modules\semver
npm WARN rm not removing C:\VSCode\nlw5\plantmanager\node_modules\.bin\json5.cmd as it wasn't installed by C:\VSCode\nlw5\plantmanager\node_modules\json5

> core-js@2.6.12 postinstall C:\VSCode\nlw5\plantmanager\node_modules\core-js
> node -e "try{require('./postinstall')}catch(e){}"

Thank you for using core-js ( https://github.com/zloirock/core-js ) for polyfilling JavaScript standard library!

The project needs your help! Please consider supporting of core-js on Open Collective or Patreon: 
> https://opencollective.com/core-js 
> https://www.patreon.com/zloirock 

Also, the author of core-js ( https://github.com/zloirock ) is looking for a good job -)

npm WARN @react-navigation/stack@5.14.5 requires a peer of @react-native-community/masked-view@>= 0.1.0 but none is installed. You must install peer dependencies yourself.
npm WARN @react-navigation/stack@5.14.5 requires a peer of @react-navigation/native@^5.0.5 but none is installed. You must install peer dependencies yourself.
npm WARN @react-navigation/stack@5.14.5 requires a peer of react-native@* but none is installed. You must install peer dependencies yourself.
npm WARN @react-navigation/stack@5.14.5 requires a peer of react-native-gesture-handler@>= 1.0.0 but none is installed. You must install peer dependencies yourself.
npm WARN @react-navigation/stack@5.14.5 requires a peer of react-native-screens@>= 2.0.0-alpha.0 || >= 2.0.0-beta.0 || >= 2.0.0 but none is installed. You must install peer dependencies yourself.
npm WARN react-native-iphone-x-helper@1.3.1 requires a peer of react-native@>=0.42.0 but none is installed. You must install peer dependencies yourself.

added 26 packages from 53 contributors, removed 467 packages, updated 405 packages and audited 437 packages in 134.653s

24 packages are looking for funding
  run `npm fund` for details

found 2 low severity vulnerabilities
  run `npm audit fix` to fix them, or `npm audit` for details
PS C:\VSCode\nlw5\plantmanager> npm audit fix
npm ERR! code ELOCKVERIFY
npm ERR! Errors were found in your package-lock.json, run  npm install  to fix them.
npm ERR!     Missing: @expo-google-fonts/jost@^0.2.0
npm ERR!     Missing: @react-native-community/masked-view@0.1.10
npm ERR!     Missing: @react-navigation/native@^5.9.4
npm ERR!     Missing: react-native@https://github.com/expo/react-native/archive/sdk-42.0.0.tar.gz
npm ERR!     Missing: react-native-gesture-handler@~1.10.2
npm ERR!     Missing: react-native-reanimated@~2.2.0
npm ERR!     Missing: react-native-screens@~3.4.0

npm ERR! A complete log of this run can be found in:
npm ERR!     C:\Users\lsf_b\AppData\Roaming\npm-cache\_logs\2021-07-29T16_20_44_907Z-debug.log
PS C:\VSCode\nlw5\plantmanager> npm install
npm WARN deprecated @hapi/joi@15.1.1: Switch to 'npm install joi'
npm WARN deprecated @hapi/bourne@1.3.2: This version has been deprecated and is no longer supported or maintained
npm WARN deprecated @hapi/address@2.1.4: Moved to 'npm install @sideway/address'
npm WARN deprecated @hapi/hoek@8.5.1: This version has been deprecated and is no longer supported or maintained
npm WARN deprecated @hapi/topo@3.1.6: This version has been deprecated and is no longer supported or maintained
npm WARN deprecated fsevents@1.2.13: fsevents 1 will break on node v14+ and could be using insecure binaries. Upgrade to fsevents 2.
npm WARN deprecated sane@4.1.0: some dependency vulnerabilities fixed, support for node < 10 dropped, and newer ECMAScript syntax/features added
npm WARN deprecated urix@0.1.0: Please see https://github.com/lydell/urix#deprecated
npm WARN deprecated resolve-url@0.2.1: https://github.com/lydell/resolve-url#deprecated
npm WARN deprecated uglify-es@3.3.9: support for ECMAScript is superseded by `uglify-js` as of v3.13.0
npm WARN optional SKIPPING OPTIONAL DEPENDENCY: fsevents@^1.2.7 (node_modules\jest-haste-map\node_modules\fsevents):
npm WARN notsup SKIPPING OPTIONAL DEPENDENCY: Unsupported platform for fsevents@1.2.13: wanted {"os":"darwin","arch":"any"} (current: {"os":"win32","arch":"x64"})

added 493 packages from 247 contributors, removed 5 packages, updated 27 packages and audited 958 packages in 136.939s

29 packages are looking for funding
  run `npm fund` for details

found 5 low severity vulnerabilities
  run `npm audit fix` to fix them, or `npm audit` for details
PS C:\VSCode\nlw5\plantmanager> npm audit fix
npm WARN react-native-web@0.17.1 requires a peer of react@>=17.0.1 but none is installed. You must install peer dependencies yourself.
npm WARN react-native-web@0.17.1 requires a peer of react-dom@>=17.0.1 but none is installed. You must install peer dependencies yourself.
npm WARN optional SKIPPING OPTIONAL DEPENDENCY: fsevents@1.2.13 (node_modules\fsevents):
npm WARN notsup SKIPPING OPTIONAL DEPENDENCY: Unsupported platform for fsevents@1.2.13: wanted {"os":"darwin","arch":"any"} (current: {"os":"win32","arch":"x64"})

+ react-native-web@0.17.1
added 1 package, removed 8 packages and updated 2 packages in 10.017s

29 packages are looking for funding
  run `npm fund` for details

fixed 1 of 5 vulnerabilities in 958 scanned packages
  4 vulnerabilities required manual review and could not be updated
PS C:\VSCode\nlw5\plantmanager> 



PS C:\VSCode\nlw5\plantmanager> 

##### expo install expo-app-loading

┌─────────────────────────────────────────────────────────────────────────┐
│                                                                         │
│   There is a new version of expo-cli available (4.9.0).                 │
│   You are currently using expo-cli 4.5.2                                │
│   Install expo-cli globally using the package manager of your choice;   │
│   for example: `npm install -g expo-cli` to get the latest version      │
│                                                                         │
└─────────────────────────────────────────────────────────────────────────┘
Installing 1 other package using Yarn.

> yarn add expo-app-loading
> yarn add v1.22.5
> warning package-lock.json found. Your project contains lock files generated by tools other than Yarn. It is advised not to mix package managers in order to avoid resolution inconsistencies 
> caused by unsynchronized lock files. To clear this warning, remove package-lock.json.
> [1/4] Resolving packages...
> [2/4] Fetching packages...
> info fsevents@1.2.13: The platform "win32" is incompatible with this module.
> info "fsevents@1.2.13" is an optional dependency and failed compatibility check. Excluding it from installation.
> [3/4] Linking dependencies...
> [4/4] Building fresh packages...
> success Saved lockfile.
> success Saved 26 new dependencies.
> info Direct dependencies
> ├─ @react-navigation/stack@5.14.5
> ├─ expo-app-loading@1.1.2
> └─ react-native-web@0.17.1
> info All dependencies
> ├─ @expo/configure-splash-screen@0.5.0
> ├─ @expo/image-utils@0.3.16
> ├─ @expo/prebuild-config@2.0.6
> ├─ @expo/spawn-async@1.5.0
> ├─ @react-navigation/stack@5.14.5
> ├─ color-convert@1.9.3
> ├─ color-name@1.1.4
> ├─ color-string@1.6.0
> ├─ color@3.2.1
> ├─ create-react-class@15.7.0
> ├─ crypto-random-string@1.0.0
> ├─ expo-app-loading@1.1.2
> ├─ expo-splash-screen@0.11.2
> ├─ hyphenate-style-name@1.0.4
> ├─ inline-style-prefixer@6.0.0
> ├─ is-arrayish@0.3.2
> ├─ jimp-compact@0.16.1
> ├─ parse-png@2.1.0
> ├─ pngjs@5.0.0
> ├─ react-native-iphone-x-helper@1.3.1
> ├─ react-native-web@0.17.1
> ├─ simple-swizzle@0.2.2
> ├─ temp-dir@1.0.0
> ├─ tempy@0.3.0
> ├─ unique-string@1.0.0
> └─ xml-js@1.6.11
> Done in 117.37s.
> PS C:\VSCode\nlw5\plantmanager> 



>##### PS C:\VSCode\nlw5\plantmanager> npm i react-native-iphone-x-helper --save
> 
> npm WARN rm not removing C:\VSCode\nlw5\plantmanager\node_modules\.bin\semver.cmd as it wasn't installed by C:\VSCode\nlw5\plantmanager\node_modules\semver
> npm WARN rm not removing C:\VSCode\nlw5\plantmanager\node_modules\.bin\semver as it wasn't installed by C:\VSCode\nlw5\plantmanager\node_modules\semver
> npm WARN rm not removing C:\VSCode\nlw5\plantmanager\node_modules\.bin\json5.cmd as it wasn't installed by C:\VSCode\nlw5\plantmanager\node_modules\json5
> npm WARN rm not removing C:\VSCode\nlw5\plantmanager\node_modules\.bin\json5 as it wasn't installed by C:\VSCode\nlw5\plantmanager\node_modules\json5    

> core-js@2.6.12 postinstall C:\VSCode\nlw5\plantmanager\node_modules\core-js

Thank you for using core-js ( https://github.com/zloirock/core-js ) for polyfilling JavaScript standard library!

> https://opencollective.com/core-js 
> https://www.patreon.com/zloirock 

Also, the author of core-js ( https://github.com/zloirock ) is looking for a good job -)

npm WARN react-native-iphone-x-helper@1.3.1 requires a peer of react-native@>=0.42.0 but none is installed. You must install peer dependencies yourself.
npm WARN optional SKIPPING OPTIONAL DEPENDENCY: fsevents@1.2.13 (node_modules\fsevents):
npm WARN notsup SKIPPING OPTIONAL DEPENDENCY: Unsupported platform for fsevents@1.2.13: wanted {"os":"darwin","arch":"any"} (current: {"os":"win32","arch":"x64"})

+ react-native-iphone-x-helper@1.3.1
added 162 packages from 78 contributors, removed 104 packages, updated 787 packages and audited 957 packages in 173.421s

29 packages are looking for funding
  run `npm fund` for details

found 4 low severity vulnerabilities
  run `npm audit fix` to fix them, or `npm audit` for details

##### PS C:\VSCode\nlw5\plantmanager> yarn add axios

yarn add v1.22.5
warning package-lock.json found. Your project contains lock files generated by tools other than Yarn. It is advised not to mix package managers in order to avoid resolution inconsistencies 
caused by unsynchronized lock files. To clear this warning, remove package-lock.json.
[1/4] Resolving packages...
[2/4] Fetching packages...
info fsevents@1.2.13: The platform "win32" is incompatible with this module.
info "fsevents@1.2.13" is an optional dependency and failed compatibility check. Excluding it from installation.
[3/4] Linking dependencies...
warning " > react-native-web@0.17.1" has incorrect peer dependency "react@>=17.0.1".
warning " > react-native-web@0.17.1" has incorrect peer dependency "react-dom@>=17.0.1".
[4/4] Building fresh packages...
success Saved lockfile.
success Saved 2 new dependencies.
info Direct dependencies
└─ axios@0.21.1
info All dependencies
├─ axios@0.21.1
└─ follow-redirects@1.14.

PS C:\VSCode\nlw5\plantmanager> 

##### npm install -g json-server

C:\Users\lsf_b\AppData\Roaming\npm\json-server -> C:\Users\lsf_b\AppData\Roaming\npm\node_modules\json-server\lib\cli\bin.js

+ json-server@0.16.3
  updated 9 packages in 20.661s

  

  

  PS C:\VSCode\nlw5\plantmanager> 
  
  ##### expo install react-native-svg
  
  ┌─────────────────────────────────────────────────────────────────────────┐
  │                                                                         │
  │   There is a new version of expo-cli available (4.9.0).                 │
  │   You are currently using expo-cli 4.5.2                                │
  │   Install expo-cli globally using the package manager of your choice;   │
  │   for example: `npm install -g expo-cli` to get the latest version      │
  │                                                                         │
  └─────────────────────────────────────────────────────────────────────────┘
  Installing 1 SDK 42.0.0 compatible native module using Yarn.
> yarn add react-native-svg@12.1.1
> yarn add v1.22.5
> warning package-lock.json found. Your project contains lock files generated by tools other than Yarn. It is advised not to mix package managers in order to avoid resolution inconsistencies 
> caused by unsynchronized lock files. To clear this warning, remove package-lock.json.
> [1/4] Resolving packages...
> [2/4] Fetching packages...
> info fsevents@1.2.13: The platform "win32" is incompatible with this module.
> info "fsevents@1.2.13" is an optional dependency and failed compatibility check. Excluding it from installation.
> [3/4] Linking dependencies...
> [4/4] Building fresh packages...
> success Saved lockfile.
> success Saved 11 new dependencies.
> info Direct dependencies
> └─ react-native-svg@12.1.1
> ├─ boolbase@1.0.0
> ├─ css-select@2.1.0
> ├─ css-tree@1.1.3
> ├─ css-what@3.4.2
> ├─ dom-serializer@0.2.2
> ├─ domelementtype@1.3.1
> ├─ domutils@1.7.0
> ├─ entities@2.2.0
> ├─ mdn-data@2.0.14
> ├─ nth-check@1.0.2
> └─ react-native-svg@12.1.1
> Done in 19.45s.
>
> ##### PS C:\VSCode\nlw5\plantmanager> expo install lottie-react-native
>
> ┌─────────────────────────────────────────────────────────────────────────┐
> │                                                                         │
> │   There is a new version of expo-cli available (4.9.0).                 │
> │   You are currently using expo-cli 4.5.2                                │
> │   Install expo-cli globally using the package manager of your choice;   │
> │   for example: `npm install -g expo-cli` to get the latest version      │
> │                                                                         │
> └─────────────────────────────────────────────────────────────────────────┘
> Installing 1 SDK 42.0.0 compatible native module using Yarn.
> yarn add lottie-react-native@4.0.2
> yarn add v1.22.5
> warning package-lock.json found. Your project contains lock files generated by tools other than Yarn. It is advised not to mix package managers in order to avoid resolution inconsistencies 
> caused by unsynchronized lock files. To clear this warning, remove package-lock.json.
> [1/4] Resolving packages...
> [2/4] Fetching packages...
> info fsevents@1.2.13: The platform "win32" is incompatible with this module.
> info "fsevents@1.2.13" is an optional dependency and failed compatibility check. Excluding it from installation.
> [3/4] Linking dependencies...
> [4/4] Building fresh packages...
> success Saved lockfile.
> success Saved 3 new dependencies.
> info Direct dependencies
> └─ lottie-react-native@4.0.2
> info All dependencies
> ├─ dedent@0.6.0
> ├─ lottie-react-native@4.0.2
> └─ react-native-safe-modules@1.0.3
> Done in 12.37s.
>
> ##### PS C:\VSCode\nlw5\plantmanager> expo install @react-native-async-storage/async-storage
>
> ┌─────────────────────────────────────────────────────────────────────────┐
> │                                                                         │
> │   There is a new version of expo-cli available (4.9.0).                 │
> │   You are currently using expo-cli 4.5.2                                │
> │   Install expo-cli globally using the package manager of your choice;   │
> │   for example: `npm install -g expo-cli` to get the latest version      │
> │                                                                         │
> └─────────────────────────────────────────────────────────────────────────┘
> Installing 1 SDK 42.0.0 compatible native module using Yarn.
> yarn add @react-native-async-storage/async-storage@~1.15.0
> yarn add v1.22.5
> warning package-lock.json found. Your project contains lock files generated by tools other than Yarn. It is advised not to mix package managers in order to avoid resolution inconsistencies 
> caused by unsynchronized lock files. To clear this warning, remove package-lock.json.
> [1/4] Resolving packages...
> warning @react-native-async-storage/async-storage > deep-assign@3.0.0: Check out `lodash.merge` or `merge-options` instead.
> [2/4] Fetching packages...
> info fsevents@1.2.13: The platform "win32" is incompatible with this module.
> info "fsevents@1.2.13" is an optional dependency and failed compatibility check. Excluding it from installation.
> [3/4] Linking dependencies...
> [4/4] Building fresh packages...
> success Saved lockfile.
> success Saved 3 new dependencies.
> info Direct dependencies
> └─ @react-native-async-storage/async-storage@1.15.5
> info All dependencies
> ├─ @react-native-async-storage/async-storage@1.15.5
> ├─ deep-assign@3.0.0
> └─ is-obj@1.0.1
> Done in 9.13s.
> PS C:\VSCode\nlw5\plantmanager> 



Unable to resolve module @react-navigation/bottom-tabs from C:\VSCode\nlw5\plantmanager\src\routes\tab.routes.tsx: @react-navigation/bottom-tabs could not be found within the project.

If you are sure the module exists, try these steps:
 1. Clear watchman watches: watchman watch-del-all
 2. Delete node_modules and run yarn install
 3. Reset Metro's cache: yarn start --reset-cache
 4. Remove the cache: rm -rf /tmp/metro-*
    1 | import React from 'react';
> 2 | import { createBottomTabNavigator } from '@react-navigation/bottom-tabs';
> |                                           ^
> 3 | import colors from '../styles/colors';
> 4 | import { PlantSelect } from '../pages/PlantSelect';
> 5 | import { MaterialIcons } from '@expo/vector-icons';

