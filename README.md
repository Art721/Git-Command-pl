# Polecenia Git, których używam prawie każdego dnia, czyli najczęsciej używane przeze mnie 21 podstawowych komend.
Polecenia terminala, które mogą ci sie przydać w codziennej pracy.

Zapoznanie się z nimi zajmnie ok 12minut.

# Wstęp
Git jest chyba najczęściej używanym systemem kontroli wersji, czyli VCS.
Oczywiście jest bardzo dużo alternatyw dla git, takich jak: Bitbucket, SVN, GitHub, GitLab oraz wiele innych.
Większość jednak opiera się na podstawowych komendach. Znając je, jesteś w stanie obsłużyć większość VCS.

W codziennej pracy nad jakimkolwiek kodem, textem czy innym typem pracy, który wymaga wersjonowania, używa się określonych poleceń. Te, bezpośrednio z terminala lub za pomoca GUI czy wbudowanej obsługi w dany program, trzeba użyć, żeby panować nad naszą pracą.

Nie przedłużając. Poniżej postarałem się zebrać ogólną listę z krótkim komentrzem dla każdego polecenia.
Są to naprawdę podstawowe komendy, które oczywiście można permutować z wieloma dodatkowymi opcjami. Mam nadzieję, 
że jeżeli zrozumiesz podstawy, to później nie będziesz miał problemu z dodaniem dodatkowych opcji do podstawowej komendy.

Pamiętaj zawsze możesz wpisać:
'''$ git --help```


# No, to co lecimy!!!

1. ```git init```
3. ```git config```
2. ```git clone```
4. ```git status```
5. ```git log```
6. ```git add```
7. ```git commit```
8. ```git branch```
9. ```git checkout```
10. ```git fetch```
11. ```git pull```
12. ```git push```
13. ```git stash```
14. ```git reset```
15. ```git merge```
16. ```git remote```
17. ```git amend```
18. ```git rebase```
19. ```git diff```
20. ```git tag```
21. ```git show``` 



# ...

<b>1. git init</b>

To jest inicjalizacja pustej struktury git w katalogu, w którym obecnie się znajdujemy.<br />
Po wykonaniu tej komendy zostaje utworzony katalog .git z podkatalogami, w których przechowywane sa wszystkie informacje dotyczące git.<br />
Jweli jesteś gotowy to :<br />

```$ git init```<br />

już mamy własnego git.<br />

# ...

<b>2. git config</b>
Następną komendą git jest config, Bardzo ważna komenda którą używa się na początku w celu skonfigurowania naszego zdalnego repozytorium.

```$ git config --global user.name "twoja nazwa"``` - służy do identyfikacji nazwy w twoich komentarzach do wszystkich czynności "twoja nazwa" <br />
to z reguły imie i nazwisko lub jakiś identyfikator który pozwoli na zidentyfikowanie Cię.<br />
```$ git config --global user.email "twojemail@domena.com.pl"``` - dodaje do konfiguracji twój email, ¬eby można się z tobą w łatwy sposób zkomunikować w razie potrzeby.<br />
```$ git config --global -l``` - pozwala nam zobaczyć co znajduje się w naszym config

po wpisaniu <b>git config --global -l</b> otrzynasz coś podobnego:
```
credential.helper=osxkeychain
user.name=Twoja Nazwa
user.email=twojemail@domena.com.pl
core.excludesfile=~/.gitignore_global
gui.recentrepo=/Users/computer1/git/NazwaTwojegoRepozytorium
core.repositoryformatversion=0
core.filemode=true
core.bare=false
core.logallrefupdates=true
core.ignorecase=true
core.precomposeunicode=true
remote.origin.url=ssh://User@222.222.22.22:222/User/home/git/NazwaTwojegoRepozytorium
remote.origin.fetch=+refs/heads/*:refs/remotes/origin/*
branch.master.remote=origin
branch.master.merge=refs/heads/master
gui.wmstate=normal
gui.geometry=888x451+441+290 201 203
```

# ...

<b>3. git clone</b>

Bardzo fajna komenda, która uczyni nas szczęsliwymi posiadaczami kopi zdalnego repozytoriun na naszym komputerze i pozwoli wreszczie zabrać się do wymarzonej pracy nad naszym repozytorium.<br />






