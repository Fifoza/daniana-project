# daniana-project

This a Team Project. It include to follow people:
- Daniana Koeva
- Nadia Rogova
- Iva Milanova
- Tihomir Todorov
- Martin Nikolov
- Stoyan Zashev
- Georgi Petrov

# work-flow

* За front-end:

* Всички файлове по които се рaботи от front-end, да се съхраняват в папката Iva. Когато има промени или нови файлове, да се следва следният начин на работа:
  * бъдете сигурни, че сте отворили bash в папката където се намира проекта на локалната ви машина.
  * git add .
  * git commit -m "описателно съобщение за промените"
  * git pull origin master
  * git push origin master

* За back-end:

  * Start with the master branch:
    * git checkout master
    * git fetch origin
    * git reset --hard origin/master

  * Create new branch:
    * git checkout -b feature-name

  * Update, add, commit, and push changes:
    * git status
    * git add <some-file>
    * git commit -m "описателно съобщение за промените"
  
  * Push feature branch to remote for the first time:
    * git push -u origin new-feature

  * Push feature branch to remote every next time:
    * git push origin new-feature

  * After feature is done:
    * git checkout master
    * git pull
    * git pull origin feature-name
    * git push