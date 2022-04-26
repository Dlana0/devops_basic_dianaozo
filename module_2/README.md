Autors: Diāna

Saite: https://github.com/Dlana0/devops_basic_dianaozo

## 2. Tēma
**Atbildes:**

| Uzd. Nr. | Atbilde |
| ------ | ------ |
| 9. | Lokālais git commit hash pārbaudīts ar komandu `"git rev-parse origin/master"`, tas ir vienāds ar github commit hash |
| 13. | Failu hash salīdzināts ar komandu `"git diff <commit-id> <commit-id>"`. Rezulāts: `Binary files /dev/null and b/module_2/DevOps.png differ` |
| 16. | Lai atrastu iepriekšējās nedēļas laikā veiktās izmaiņas, izmantotas komandas: `"git log --after="2022-04-18" --until="2022-04-24""` un `"git log --since='2 weeks ago'"` |
| 17. | Lai atrastu autora "Laura Pacilio" izmaiņas, izmantota komanda: `"git log --author='Laura Pacilio'"` |
| 18. | Lai atrastu Lauras veiktās izmaiņas pagājušā gada septembrī, izmantota komanda: `"git log --author='Laura Pacilio' --after="2021-09-01" --until="2021-09-30""`. Ja vēlas arī skaitu, cik izmaiņas veiktas: `"git shortlog --author='Laura Pacilio' --after="2021-09-01" --until="2021-09-30" -n"` |
| 19. | Laura vakar, 25.aprīlī, nav veikusi nevienu commit. Pārbaudīts ar komandu: `"git log --author='Laura Pacilio' --after="2022-04-25 00:00" --until="2021-04-25 23:59""` |
| `*` | Ar komandu `"git log --pretty=fuller --after="2021-04-20" --until="2021-04-21""` pārbaudīts, ka 16.aprīlis ir `AuthorDate`, bet `CommitDate` ir 20.aprīlis, ko arī pēc noklusējuma attēlo `Git log`|


##Attēli:

**16.uzdevums:**

![Image](https://github.com/Dlana0/devops_basic_dianaozo/blob/master/module_2/git%20log.PNG)
![Image](https://github.com/Dlana0/devops_basic_dianaozo/blob/master/module_2/git%20log2.png)

**17.uzdevums:**

![Image](https://github.com/Dlana0/devops_basic_dianaozo/blob/master/module_2/LauraPcommits.png)


**18.uzdevums:**
![Image](https://github.com/Dlana0/devops_basic_dianaozo/blob/master/module_2/LauraPcommits2.png)

***.uzdevums:**
![Image](https://github.com/Dlana0/devops_basic_dianaozo/blob/master/module_2/AuthorDate.png)
