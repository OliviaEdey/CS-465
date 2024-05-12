# CS-465
Windows PowerShell
Copyright (C) Microsoft Corporation. All rights reserved.

Install the latest PowerShell for new features and improvements! https://aka.ms/PSWindows

PS C:\WINDOWS\system32> npm install
npm ERR! code ENOENT
npm ERR! syscall open
npm ERR! path C:\Windows\System32\package.json
npm ERR! errno -4058
npm ERR! enoent Could not read package.json: Error: ENOENT: no such file or directory, open 'C:\Windows\System32\package.json'
npm ERR! enoent This is related to npm not being able to find a file.
npm ERR! enoent

npm ERR! A complete log of this run can be found in: C:\Users\olivi_m8hyaip\AppData\Local\npm-cache\_logs\2024-05-12T22_51_41_398Z-debug-0.log
PS C:\WINDOWS\system32> cd travlr
cd : Cannot find path 'C:\WINDOWS\system32\travlr' because it does not exist.
At line:1 char:1
+ cd travlr
+ ~~~~~~~~~
    + CategoryInfo          : ObjectNotFound: (C:\WINDOWS\system32\travlr:String) [Set-Location], ItemNotFoundExcep
   tion
    + FullyQualifiedErrorId : PathNotFound,Microsoft.PowerShell.Commands.SetLocationCommand

PS C:\WINDOWS\system32> cd ~/travlr
PS C:\Users\olivi_m8hyaip\travlr> npm install
npm ERR! code ENOENT
npm ERR! syscall open
npm ERR! path C:\Users\olivi_m8hyaip\travlr\package.json
npm ERR! errno -4058
npm ERR! enoent Could not read package.json: Error: ENOENT: no such file or directory, open 'C:\Users\olivi_m8hyaip\travlr\package.json'
npm ERR! enoent This is related to npm not being able to find a file.
npm ERR! enoent

npm ERR! A complete log of this run can be found in: C:\Users\olivi_m8hyaip\AppData\Local\npm-cache\_logs\2024-05-12T22_52_22_746Z-debug-0.log
PS C:\Users\olivi_m8hyaip\travlr> cd ~/-force
cd : Cannot find path 'C:\Users\olivi_m8hyaip\-force' because it does not exist.
At line:1 char:1
+ cd ~/-force
+ ~~~~~~~~~~~
    + CategoryInfo          : ObjectNotFound: (C:\Users\olivi_m8hyaip\-force:String) [Set-Location], ItemNotFoundEx
   ception
    + FullyQualifiedErrorId : PathNotFound,Microsoft.PowerShell.Commands.SetLocationCommand

PS C:\Users\olivi_m8hyaip\travlr> -force
-force : The term '-force' is not recognized as the name of a cmdlet, function, script file, or operable program.
Check the spelling of the name, or if a path was included, verify that the path is correct and try again.
At line:1 char:1
+ -force
+ ~~~~~~
    + CategoryInfo          : ObjectNotFound: (-force:String) [], CommandNotFoundException
    + FullyQualifiedErrorId : CommandNotFoundException

PS C:\Users\olivi_m8hyaip\travlr> cd ~/-force
cd : Cannot find path 'C:\Users\olivi_m8hyaip\-force' because it does not exist.
At line:1 char:1
+ cd ~/-force
+ ~~~~~~~~~~~
    + CategoryInfo          : ObjectNotFound: (C:\Users\olivi_m8hyaip\-force:String) [Set-Location], ItemNotFoundEx
   ception
    + FullyQualifiedErrorId : PathNotFound,Microsoft.PowerShell.Commands.SetLocationCommand

PS C:\Users\olivi_m8hyaip\travlr> npm install

added 63 packages, and audited 64 packages in 3s

7 vulnerabilities (1 moderate, 4 high, 2 critical)

To address all issues, run:
  npm audit fix --force

Run `npm audit` for details.
PS C:\Users\olivi_m8hyaip\travlr> npm audit
# npm audit report

express  <=4.19.1 || 5.0.0-alpha.1 - 5.0.0-alpha.7
Severity: high
Express.js Open Redirect in malformed URLs - https://github.com/advisories/GHSA-rv95-896h-c2vc
Depends on vulnerable versions of body-parser
Depends on vulnerable versions of qs
fix available via `npm audit fix --force`
Will install express@4.19.2, which is outside the stated dependency range
node_modules/express

handlebars  <=4.7.6
Severity: critical
Arbitrary Code Execution in handlebars - https://github.com/advisories/GHSA-q2c6-c6pm-g3gh
Prototype Pollution in handlebars - https://github.com/advisories/GHSA-g9r4-xpmj-mj65
Denial of Service in handlebars - https://github.com/advisories/GHSA-f52g-6jhx-586p
Remote code execution in handlebars when compiling templates - https://github.com/advisories/GHSA-f2jv-r9rf-7988
Arbitrary Code Execution in Handlebars - https://github.com/advisories/GHSA-3cqr-58rm-57f8
Regular Expression Denial of Service in Handlebars - https://github.com/advisories/GHSA-62gr-4qp9-h98f
Prototype Pollution in handlebars - https://github.com/advisories/GHSA-765h-qjxv-5f44
Arbitrary Code Execution in handlebars - https://github.com/advisories/GHSA-2cf5-4w76-r9qv
Depends on vulnerable versions of optimist
fix available via `npm audit fix --force`
Will install hbs@4.2.0, which is outside the stated dependency range
node_modules/handlebars
  hbs  <=4.1.2
  Depends on vulnerable versions of handlebars
  node_modules/hbs


minimist  <=0.2.3
Severity: critical
Prototype Pollution in minimist - https://github.com/advisories/GHSA-vh95-rmgr-6w4m
Prototype Pollution in minimist - https://github.com/advisories/GHSA-xvch-5gv4-984h
fix available via `npm audit fix --force`
Will install hbs@4.2.0, which is outside the stated dependency range
node_modules/minimist
  optimist  >=0.6.0
  Depends on vulnerable versions of minimist
  node_modules/optimist

qs  6.5.0 - 6.5.2
Severity: high
qs vulnerable to Prototype Pollution - https://github.com/advisories/GHSA-hrpp-h998-j3pp
fix available via `npm audit fix --force`
Will install express@4.19.2, which is outside the stated dependency range
node_modules/qs
  body-parser  1.18.0 - 1.18.3
  Depends on vulnerable versions of qs
  node_modules/body-parser

7 vulnerabilities (1 moderate, 4 high, 2 critical)

To address all issues, run:
  npm audit fix --force
PS C:\Users\olivi_m8hyaip\travlr> npm audit fix –force
npm ERR! arg Argument starts with non-ascii dash, this is probably invalid: –force

up to date, audited 64 packages in 912ms

# npm audit report

express  <=4.19.1 || 5.0.0-alpha.1 - 5.0.0-alpha.7
Severity: high
Express.js Open Redirect in malformed URLs - https://github.com/advisories/GHSA-rv95-896h-c2vc
Depends on vulnerable versions of body-parser
Depends on vulnerable versions of qs
fix available via `npm audit fix --force`
Will install express@4.19.2, which is outside the stated dependency range
node_modules/express

handlebars  <=4.7.6
Severity: critical
Arbitrary Code Execution in handlebars - https://github.com/advisories/GHSA-q2c6-c6pm-g3gh
Prototype Pollution in handlebars - https://github.com/advisories/GHSA-g9r4-xpmj-mj65
Denial of Service in handlebars - https://github.com/advisories/GHSA-f52g-6jhx-586p
Remote code execution in handlebars when compiling templates - https://github.com/advisories/GHSA-f2jv-r9rf-7988
Arbitrary Code Execution in Handlebars - https://github.com/advisories/GHSA-3cqr-58rm-57f8
Regular Expression Denial of Service in Handlebars - https://github.com/advisories/GHSA-62gr-4qp9-h98f
Prototype Pollution in handlebars - https://github.com/advisories/GHSA-765h-qjxv-5f44
Arbitrary Code Execution in handlebars - https://github.com/advisories/GHSA-2cf5-4w76-r9qv
Depends on vulnerable versions of optimist
fix available via `npm audit fix --force`
Will install hbs@4.2.0, which is outside the stated dependency range
node_modules/handlebars
  hbs  <=4.1.2
  Depends on vulnerable versions of handlebars
  node_modules/hbs


minimist  <=0.2.3
Severity: critical
Prototype Pollution in minimist - https://github.com/advisories/GHSA-vh95-rmgr-6w4m
Prototype Pollution in minimist - https://github.com/advisories/GHSA-xvch-5gv4-984h
fix available via `npm audit fix --force`
Will install hbs@4.2.0, which is outside the stated dependency range
node_modules/minimist
  optimist  >=0.6.0
  Depends on vulnerable versions of minimist
  node_modules/optimist

qs  6.5.0 - 6.5.2
Severity: high
qs vulnerable to Prototype Pollution - https://github.com/advisories/GHSA-hrpp-h998-j3pp
fix available via `npm audit fix --force`
Will install express@4.19.2, which is outside the stated dependency range
node_modules/qs
  body-parser  1.18.0 - 1.18.3
  Depends on vulnerable versions of qs
  node_modules/body-parser

7 vulnerabilities (1 moderate, 4 high, 2 critical)

To address all issues, run:
  npm audit fix --force
PS C:\Users\olivi_m8hyaip\travlr> npm audit fix --force
npm WARN using --force Recommended protections disabled.
npm WARN audit Updating express to 4.19.2, which is outside your stated dependency range.
npm WARN audit Updating hbs to 4.2.0, which is outside your stated dependency range.

added 43 packages, removed 1 package, changed 18 packages, and audited 106 packages in 2s

13 packages are looking for funding
  run `npm fund` for details

found 0 vulnerabilities
PS C:\Users\olivi_m8hyaip\travlr> set DEBUG=travlr:*
PS C:\Users\olivi_m8hyaip\travlr> npm start

> force@0.0.0 start
> node ./bin/www

GET / 200 41.333 ms - 204
GET /stylesheets/style.css 200 2.718 ms - 111
GET /favicon.ico 404 3.782 ms - 1147
GET / 304 2.567 ms - -
GET /stylesheets/style.css 304 0.743 ms - -
Terminate batch job (Y/N)? y
PS C:\Users\olivi_m8hyaip\travlr> npm start

> force@0.0.0 start
> node ./bin/www

GET / 304 52.196 ms - -
GET /stylesheets/style.css 200 2.457 ms - 10192
GET /images/bg-body.jpg 200 0.752 ms - 1951
GET / 304 9.107 ms - -
GET /stylesheets/style.css 304 0.546 ms - -
GET /images/bg-body.jpg 304 0.429 ms - -
GET / 304 13.541 ms - -
GET /stylesheets/style.css 304 0.304 ms - -
GET / 304 3.114 ms - -
GET /stylesheets/style.css 304 0.465 ms - -
GET / 304 2.276 ms - -
GET /stylesheets/style.css 304 0.388 ms - -
Terminate batch job (Y/N)? Y
PS C:\Users\olivi_m8hyaip\travlr> npm start

> force@0.0.0 start
> node ./bin/www

GET / 304 45.008 ms - -
GET /stylesheets/style.css 304 0.841 ms - -
GET /images/bg-body.jpg 304 0.359 ms - -
Terminate batch job (Y/N)? y
PS C:\Users\olivi_m8hyaip\travlr> npm start

> force@0.0.0 start
> node ./bin/www

GET / 304 38.485 ms - -
GET /stylesheets/style.css 304 0.848 ms - -
GET /images/bg-body.jpg 304 0.881 ms - -
GET / 304 2.839 ms - -
GET /stylesheets/style.css 304 0.431 ms - -
GET / 304 7.371 ms - -
GET /stylesheets/style.css 304 0.328 ms - -
GET / 304 1.981 ms - -
GET /stylesheets/style.css 304 0.363 ms - -
GET / 304 3.617 ms - -
GET /stylesheets/style.css 304 0.422 ms - -
Terminate batch job (Y/N)?
Terminate batch job (Y/N)? y
PS C:\Users\olivi_m8hyaip\travlr> npm start

> force@0.0.0 start
> node ./bin/www

GET / 304 43.114 ms - -
GET /stylesheets/style.css 304 0.988 ms - -
GET / 304 2.288 ms - -
GET /stylesheets/style.css 304 0.329 ms - -
GET /images/bg-body.jpg 404 3.575 ms - 1147
GET / 304 2.953 ms - -
GET /stylesheets/style.css 304 0.469 ms - -
GET / 304 10.832 ms - -
GET /stylesheets/style.css 304 0.550 ms - -
GET / 304 5.778 ms - -
GET /stylesheets/style.css 304 0.375 ms - -
GET / 304 2.129 ms - -
GET /stylesheets/style.css 304 0.293 ms - -
Terminate batch job (Y/N)? y
PS C:\Users\olivi_m8hyaip\travlr> npm start

> force@0.0.0 start
> node ./bin/www

GET / 304 51.803 ms - -
GET /stylesheets/style.css 304 0.863 ms - -
GET / 304 7.531 ms - -
GET /stylesheets/style.css 304 0.468 ms - -
GET /images/bg-body.jpg 404 4.619 ms - 1147
GET / 304 13.068 ms - -
GET /stylesheets/style.css 304 0.391 ms - -
GET / 304 2.210 ms - -
GET /stylesheets/style.css 304 0.648 ms - -
GET / 304 2.743 ms - -
GET /stylesheets/style.css 304 0.415 ms - -
GET / 304 3.380 ms - -
GET /stylesheets/style.css 304 0.323 ms - -
GET / 304 2.712 ms - -
GET /stylesheets/style.css 304 0.348 ms - -
GET / 304 5.364 ms - -
GET /stylesheets/style.css 304 0.445 ms - -
GET / 304 3.717 ms - -
GET /stylesheets/style.css 304 0.453 ms - -
GET / 304 2.324 ms - -
GET /stylesheets/style.css 304 0.344 ms - -
GET / 304 4.595 ms - -
GET /stylesheets/style.css 304 0.439 ms - -
GET / 304 4.693 ms - -
GET /stylesheets/style.css 304 0.444 ms - -
GET / 304 8.698 ms - -
GET /stylesheets/style.css 304 0.388 ms - -
GET / 304 5.778 ms - -
GET /stylesheets/style.css 304 0.321 ms - -
GET / 304 1.537 ms - -
GET /stylesheets/style.css 304 0.413 ms - -
GET / 304 2.787 ms - -
GET /stylesheets/style.css 304 0.361 ms - -
GET / 304 2.153 ms - -
GET /stylesheets/style.css 304 0.373 ms - -
GET / 304 4.268 ms - -
GET /stylesheets/style.css 304 0.350 ms - -
GET / 304 5.546 ms - -
GET /stylesheets/style.css 304 0.355 ms - -
GET / 304 5.996 ms - -
GET /stylesheets/style.css 304 0.367 ms - -
GET / 304 1.928 ms - -
GET /stylesheets/style.css 304 0.675 ms - -
GET / 304 1.395 ms - -
GET /stylesheets/style.css 304 0.316 ms - -
GET / 304 1.695 ms - -
GET /stylesheets/style.css 304 0.359 ms - -
GET / 304 1.106 ms - -
GET /stylesheets/style.css 304 0.295 ms - -
GET / 304 1.863 ms - -
GET /stylesheets/style.css 304 0.309 ms - -
GET / 200 1.405 ms - 204
GET /stylesheets/style.css 200 3.112 ms - 10192
GET /images/bg-body.jpg 404 2.183 ms - 1147
GET /favicon.ico 404 1.710 ms - 1147
GET / 304 1.940 ms - -
GET /stylesheets/style.css 304 0.384 ms - -
GET / 304 1.986 ms - -
GET /stylesheets/style.css 304 0.480 ms - -
GET / 304 7.171 ms - -
GET /stylesheets/style.css 304 0.947 ms - -
GET / 304 2.278 ms - -
GET /stylesheets/style.css 304 0.306 ms - -
GET / 304 3.625 ms - -
GET /stylesheets/style.css 304 0.349 ms - -
Terminate batch job (Y/N)?
Terminate batch job (Y/N)? y
PS C:\Users\olivi_m8hyaip\travlr> npm start

> force@0.0.0 start
> node ./bin/www

GET / 304 38.866 ms - -
GET /stylesheets/style.css 304 0.859 ms - -
GET / 304 4.661 ms - -
GET /stylesheets/style.css 304 0.425 ms - -
GET / 304 10.076 ms - -
GET /stylesheets/style.css 304 0.391 ms - -
GET / 304 3.302 ms - -
GET /stylesheets/style.css 304 0.319 ms - -
GET / 304 4.471 ms - -
GET /stylesheets/style.css 304 0.382 ms - -
GET / 304 2.199 ms - -
GET /stylesheets/style.css 304 0.515 ms - -
GET / 304 3.947 ms - -
GET /stylesheets/style.css 304 0.413 ms - -
GET / 304 2.674 ms - -
GET /stylesheets/style.css 304 0.356 ms - -
GET / 304 2.473 ms - -
GET /stylesheets/style.css 304 0.367 ms - -
GET / 304 2.402 ms - -
GET /stylesheets/style.css 304 0.385 ms - -
GET / 304 2.919 ms - -
GET /stylesheets/style.css 304 0.403 ms - -
GET / 304 3.540 ms - -
GET /stylesheets/style.css 304 0.358 ms - -
GET / 304 3.524 ms - -
GET /stylesheets/style.css 304 0.556 ms - -
GET / 304 3.195 ms - -
GET /stylesheets/style.css 304 0.336 ms - -
GET / 304 2.724 ms - -
GET /stylesheets/style.css 304 0.294 ms - -
GET / 304 3.464 ms - -
GET /stylesheets/style.css 304 0.461 ms - -
GET / 304 1.434 ms - -
GET /stylesheets/style.css 304 0.404 ms - -
GET / 304 1.319 ms - -
GET /stylesheets/style.css 304 0.709 ms - -
GET / 304 1.499 ms - -
GET /stylesheets/style.css 304 0.353 ms - -
GET / 304 1.660 ms - -
GET /stylesheets/style.css 304 0.397 ms - -
Terminate batch job (Y/N)?
Terminate batch job (Y/N)? y
PS C:\Users\olivi_m8hyaip\travlr> npm start

> force@0.0.0 start
> node ./bin/www

GET / 200 5.322 ms - 4209
GET /images/logo.png 200 31.209 ms - 10526
GET /images/sea-sound.jpg 200 4.002 ms - 55656
GET /images/rooms.png 200 3.558 ms - 48262
GET /images/dive-site.png 200 3.873 ms - 58387
GET /images/food.png 200 5.841 ms - 58849
GET /css/style.css 404 46.086 ms - 1147
Terminate batch job (Y/N)?
Terminate batch job (Y/N)? y
PS C:\Users\olivi_m8hyaip\travlr> npm start

> force@0.0.0 start
> node ./bin/www

GET / 304 7.247 ms - -
GET /images/sea-sound.jpg 304 1.485 ms - -
GET /images/logo.png 304 2.050 ms - -
GET /css/style.css 200 5.175 ms - 10192
GET /images/dive-site.png 304 2.699 ms - -
GET /images/rooms.png 304 3.239 ms - -
GET /images/food.png 304 3.357 ms - -
GET /images/bg-pattern.jpg 200 2.588 ms - 57554
GET /images/bg-body.jpg 200 3.015 ms - 1951
GET /images/bg-navigation.png 200 3.115 ms - 1479
GET /images/bg-menu.png 200 3.434 ms - 1129
GET /images/bg-adbox.png 200 3.343 ms - 3171
GET /images/bg-box.png 200 4.173 ms - 1485
GET /images/icons.png 200 0.489 ms - 6190
GET /travel.html 200 0.997 ms - 3991
GET /css/style.css 304 1.107 ms - -
GET /images/logo.png 304 1.230 ms - -
GET /images/reef1.jpg 200 3.164 ms - 46505
GET /images/reef2.jpg 200 1.480 ms - 45070
GET /images/reef3.jpg 200 2.436 ms - 45273
GET /images/content-box.png 200 0.603 ms - 1548
GET /rooms.html 200 0.578 ms - 3474
GET /css/style.css 304 0.825 ms - -
GET /images/logo.png 304 1.240 ms - -
GET /images/first-class.jpg 200 2.958 ms - 34421
GET /images/deluxe.jpg 200 1.678 ms - 51303
GET /images/suite.jpg 200 2.096 ms - 32018
GET /meals.html 200 0.886 ms - 3443
GET /css/style.css 304 0.579 ms - -
GET /images/logo.png 304 1.117 ms - -
GET /images/seafoods.jpg 200 2.839 ms - 48301
GET /images/desserts.jpg 200 1.028 ms - 42893
GET /images/buffet.jpg 200 0.751 ms - 48534
GET /rooms.html 304 0.338 ms - -
GET /css/style.css 304 0.743 ms - -
GET /images/logo.png 304 1.027 ms - -
GET /images/first-class.jpg 304 1.802 ms - -
GET /images/deluxe.jpg 304 0.476 ms - -
GET /images/suite.jpg 304 0.592 ms - -
GET /meals.html 304 0.330 ms - -
GET /css/style.css 304 0.769 ms - -
GET /images/logo.png 304 1.079 ms - -
GET /images/seafoods.jpg 304 2.440 ms - -
GET /images/desserts.jpg 304 0.385 ms - -
GET /images/buffet.jpg 304 0.478 ms - -
GET /news.html 200 0.509 ms - 4710
GET /css/style.css 304 0.377 ms - -
GET /images/logo.png 304 0.286 ms - -
GET /images/kayak.jpg 200 1.533 ms - 53502
GET /meals.html 304 0.466 ms - -
GET /css/style.css 304 0.991 ms - -
GET /images/logo.png 304 1.427 ms - -
GET /images/seafoods.jpg 304 3.343 ms - -
GET /images/desserts.jpg 304 0.473 ms - -
GET /images/buffet.jpg 304 1.085 ms - -
GET /news.html 304 0.284 ms - -
GET /css/style.css 304 0.602 ms - -
GET /images/logo.png 304 0.854 ms - -
GET /images/kayak.jpg 304 1.583 ms - -
Terminate batch job (Y/N)? y
PS C:\Users\olivi_m8hyaip\travlr> git status
fatal: not a git repository (or any of the parent directories): .git
PS C:\Users\olivi_m8hyaip\travlr> npm start

> force@0.0.0 start
> node ./bin/www

Terminate batch job (Y/N)? y
PS C:\Users\olivi_m8hyaip\travlr> git status
fatal: not a git repository (or any of the parent directories): .git
PS C:\Users\olivi_m8hyaip\travlr> git add .
fatal: not a git repository (or any of the parent directories): .git
PS C:\Users\olivi_m8hyaip\travlr> cd ~
PS C:\Users\olivi_m8hyaip> git clone https://github.com/OliviaEdey/cs-465-fullstack.git travlr
fatal: destination path 'travlr' already exists and is not an empty directory.
PS C:\Users\olivi_m8hyaip> cd ~/travlr
PS C:\Users\olivi_m8hyaip\travlr> git clone https://github.com/OliviaEdey/cs-465-fullstack.git travlr
Cloning into 'travlr'...
info: please complete authentication in your browser...
remote: Repository not found.
fatal: repository 'https://github.com/OliviaEdey/cs-465-fullstack.git/' not found
PS C:\Users\olivi_m8hyaip\travlr> git status
fatal: not a git repository (or any of the parent directories): .git
PS C:\Users\olivi_m8hyaip\travlr> git clone https://github.com/OliviaEdey/CS-465.git travlr
Cloning into 'travlr'...
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
Receiving objects: 100% (3/3), done.
PS C:\Users\olivi_m8hyaip\travlr> git status
fatal: not a git repository (or any of the parent directories): .git
PS C:\Users\olivi_m8hyaip\travlr> dir


    Directory: C:\Users\olivi_m8hyaip\travlr


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d-----         5/12/2024   6:41 PM                bin
d-----         5/12/2024   7:00 PM                node_modules
d-----         5/12/2024   7:23 PM                public
d-----         5/12/2024   6:41 PM                routes
d-----         5/12/2024   7:41 PM                travlr
d-----         5/12/2024   6:41 PM                views
-a----         5/12/2024   6:57 PM           1065 .gitignore
-a----         5/12/2024   6:41 PM           1074 app.js
-a----         5/12/2024   7:00 PM          40586 package-lock.json
-a----         5/12/2024   7:00 PM            291 package.json


PS C:\Users\olivi_m8hyaip\travlr> type README.md
type : Cannot find path 'C:\Users\olivi_m8hyaip\travlr\README.md' because it does not exist.
At line:1 char:1
+ type README.md
+ ~~~~~~~~~~~~~~
    + CategoryInfo          : ObjectNotFound: (C:\Users\olivi_m8hyaip\travlr\README.md:String) [Get-Content], ItemN
   otFoundException
    + FullyQualifiedErrorId : PathNotFound,Microsoft.PowerShell.Commands.GetContentCommand

PS C:\Users\olivi_m8hyaip\travlr>
