
This is my first project, gonna do more in the future


def addizione(val1,val2):
     return val1+val2
def sottrazione(val1,val2):
     return val1-val2
def moltiplicazione(val1,val2):
    return val1*val2
def divisione(val1,val2):
     return val1/val2
def scelta(x):
    print("sceglia quale operezaione vuoi fare")
    valori=int(input("scegli il primo valore:"))
    valori1=int(input("inserisci il secondo valore: "))
    
    match x:
        case 1:
            print("hai scelto l'operazione 1")
            add=addizione(valori,valori1)
            print(f"il risullatato dell'addizione è:{add}")
        case 2:
             print("hai scelto l'operazione 2")
             sott=sottrazione(valori,valori1)
             print(f"il risullatato della sottrazione è:{sott}")
        case 3:
              print("hai scelto l'operazione 3")
              molt=moltiplicazione(valori,valori1)
              print(f"il risullatato dellla moltiplicazioe è:{molt}")
        case 4:
             print("hai scelto l'operazione 4")
             divis=divisione(valori,valori1)
             print(f"il risullatato della divisione è:{divis}")             
        case _:
              print("non hai scelto nessuna operazione valida")
valore=int(input("inserisci la scelta che vuoi fare: "))
scelta(valore)

