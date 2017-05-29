# ViliData
A nice and readable data format !

# Examples :

## Animals (Simple tree-like structure)
```
Animalia:
  Chordate:
    Mammal:
      Carnivora:
        Felidae:
          Felis:
            Domestica:
              HouseCat:
                name:"House Cat"
                size:24.5
                cool:True
            Leo:
              Lion:
                name:"Lion"
                size:280.7
                cool:True
    Primate:
      Pongidae:
        Pan:
          Troglodytes:
            Chimpanzee:
              name:"Chimpanzee"
              size:81.6
              cool:True
      Hominidae:
        Homo:
          Sapiens:
            Human:
              name:"Human"
              size:170
              cool:False
  Arthropoda:
    Insect:
      Diptera:
        Muscidae
          Musca:
            Domestica:
              Housefly:
                name:"Housefly"
                size:0.12
                cool:False
```
## Countries and Cities (Lists)

```
France:
  cities:["Paris", "Marseille", "Lyon", "Nice"]
Germany:
  cities:["Berlin", "Hamburg", "Munich", "Cologne"]
UnitedKingdom:
  cities:["London", "Manchester", "Liverpool", "Glasgow"]
```
