# myplaygound - README.md

## BEST USE proposal

### external urls                    -> use absolute pathes
[Google.de](https://www.google.de)

### repo markdown to markdown links  -> use relative pathes
[Getting started...](Getting_started.md)<br>
[a description in a subfolder...](subfolder/description.md)<br>

### repo markdown to wiki links      -> use 'blob/main'-relative pathes
use <b><i>../../</i></b> to move up to repo-root and add <b><i>wiki</i></b>/<i>wiki/folder/structure/to.md></i><br>
[My wiki - Home - rel works from main](../../wiki/Home)<br>
[My wiki - Page 1 - rel works from main](../../wiki/Page-1)<br>


----------------------------------------------------------
<br><br>
----------------------------------------------------------

## funktioniert

### external linking
[Google.de](https://www.google.de)

### repo markdown linking
[Getting started...](Getting_started.md)<br>
[a description in a subfolder...](subfolder/description.md)<br>

#### functional, but full path needs full branch info
[Getting started... (full path / main)](https://github.com/Shinobi-Warrior/myplayground/blob/main/Getting_started.md)<br>
[Getting started... (full path / task/main/test_wiki)](https://github.com/Shinobi-Warrior/myplayground/blob/task/main/test_wiki/Getting_started.md)<br>
[a description in a subfolder... (full path / main)](https://github.com/Shinobi-Warrior/myplayground/blob/main/subfolder/description.md)<br>
[a description in a subfolder... (full path / task/main/test_wiki)](https://github.com/Shinobi-Warrior/myplayground/blob/task/main/test_wiki/subfolder/description.md)


### linking to wiki (page name without .md)
[My wiki - Home - rel works from main](../../wiki/Home)<br>
[My wiki - Page 1 - rel works from main](../../wiki/Page-1)<br>
[My wiki - Home - abs ](https://github.com/Shinobi-Warrior/myplayground/wiki/Home)<br>
[My wiki - Page 1 - abs](https://github.com/Shinobi-Warrior/myplayground/wiki/Page-1)<br>

#### functional, but depending on branch name
[My wiki - Home - rel works from task/main/test_wiki](../../../../wiki/Home)<br>
[My wiki - Page 1 - rel works from task/main/test_wiki](../../../../wiki/Page-1)<br>

### link to wiki with .md suffix: opens raw file
[My wiki (full path)](https://github.com/Shinobi-Warrior/myplayground/wiki/Home.md)<br><br>


## to be checked

## funktioniert nicht
[My wiki no .md](wiki/Home)<br>
[My wiki](wiki/Home.md)<br>
[Getting started... no .md](Getting_started)<br>
[Getting started... no .md (full path)](https://github.com/Shinobi-Warrior/myplayground/Getting_started)
[Getting started... (full path no branch info)](https://github.com/Shinobi-Warrior/myplayground/Getting_started.md)
[My wiki - repo absolute?](/wiki/Home)<br>
[My wiki - repo absolute?](~/wiki/Home)<br>



## wiki page only linking
[[My wiki home|Home]]

