# DowNote
My pet note-taking app.

### Launch instructions
Just clone, run `docker-compose up` and open [localhost:3000](http://localhost:3000/)

### Change log
+ 23.12.2019 - Repo created
+ all the time in between - doing some stuff rather chaotically
+ 08.07.2019 - Created repo readme file, will try do stuff in proper way (see me fail), 'cause now I know what Pull requests are :tada: :tada: :tada:
+ 12.07.2019 - Updated project to use Semantic UI
+ 30.07.2019 - Added Note views :grinning:
  - Drag&drop for notes :fire: (I'm glad I went for it)
  - Possibility to adjust number of columns :hushed: (not for the user though :anger: :construction: )
+ 28.09.2019 - Added tests for login and drag'n'drops :wrench: :guardsman:
+ 20.10.2019 - Added notes creation :heavy_plus_sign: editing :memo: and deletion :heavy_multiplication_x:
+ 13.12.2019 - Added /note endpoints to API :satellite:
+ 14.12.2019 - Moved everything into a single docker-compose :family:
+ 15.12.2019 - Removed submodules :tired_face:
  - everything was fine, and submodules look nice on GitHub and don't really cause any serious issues with such small projects, as mine, **BUT** I should have listened to all these numerous articles shouting _"DO NOT USE SUBMODULES"_ :sob: The issue I faced is that submodules don't really have their own .git directory, instead they reference the parent one, and this is OK, unless you want to pack each submodule into a separate container (I wanted to), and interact with git from within a container (wanted this, as well). :hatched_chick:
