
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

