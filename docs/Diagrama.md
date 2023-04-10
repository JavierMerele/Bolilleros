```mermaid

classDiagram

class Bolillero{
    +NroBolilla: int
    +Bolillas: List~int~
    +BollilaJugada: List~int~ 

}



class IAzar{
    <<interface>>
    +numeros: int
}


class Azar{

}
```