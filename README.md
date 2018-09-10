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

  * Всички файлове по които се работи от front-end хората, биват пратени през друг канал на back-end хората. Те правят интеграцията в laravel и обновяват хранилището в github.

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

  * After feature is done, merge feature to master:
    * git checkout master
    * git pull
    * git checkout test
    * git pull
    * git rebase -i master
    * git checkout master
    * git merge test