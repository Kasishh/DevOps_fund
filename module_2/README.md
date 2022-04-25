## DEVOPS PAMATI IESĀCĒJIEM
### Mājas darbs -  Nr. 2_v2
### Kaspars Gribusts
### _2022_

---
# 🚀🚀🚀Uzdevumi 🚀🚀🚀

## **Salīdzināt vienādu failu (ne README) hash no mapes module_1 un module_2. Vai git redz atšķirību starp šiem failiem?**

![Compare](https://github.com/Kasishh/DevOps_fund/blob/main/module_2/images/same%20file%20different%20hash.png?raw=true)


---

## **Pārbaudīt kādas izmaiņas tika veiktas iepriekšējās nedēļas laikā. Atrast vismaz divus veidus kā to izdarīt.**

#### 1. variants ir ar komandu - _**git log --since=7.days**_

#### 2. variants ir ar komandu -  _**git log --since='Sep 18 2022' --until='Apr 25 2022'**_
---

##  Atrast commit kurus veica autors - “Laura Pacilio”

#### 1. variants ir ar komandu - _**git log --author="Laura Pacilio"**_
![Compare](https://github.com/Kasishh/DevOps_fund/blob/main/module_2/images/Laura%20Pacilio.png?raw=true)

---

## Atrast vai Laura ir veikusi commit pagājušā gada septembrī?

#### To var izdarit ar komandu - _**git log --author="Laura Pacilio" --since='Sep 1 2021' --until='Sep 30 2021'**_

![Compare](https://github.com/Kasishh/DevOps_fund/blob/main/module_2/images/made%20on%20SEP%20by%20Laura.png?raw=true)

---

## Vai Laura ir veikusi commit vakar? 

#### To var izdarīt ar komandu - _**git log --since=yesterday.midnight --author="Laura Pacilio"**_ vai  _**git log --author="Laura Pacilio" --since='Apr 24 2022' --until='Apr 25 2022'**_ 

#### Bet nevienu commit neizdevas atrast
