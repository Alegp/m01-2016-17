## Funcionament bàsic de GitHub

### Clonar el Github
Per a clonar el contingut d'un repositori de GitHub, s'ha de fer el següent:

+ Copiar l'enllaç del repositori
+ Introduir la següent comanda a la terminal


    git clone (enllaç del repositori)
    

### Guardar canvis i pujar-los un altre cop
Una vegada efectuats els canvis comprobem l'estat del repositori local amb la comanda 

    git status
    
Despres desem els canvias amb:

    git commit -am (missatge describint els canvis;opcional)
    
Y ho pujem amb la comanda

    git push
    

### Descarregar nous canvis al repositori local
Si resulta que s'han canviat arxius al repositori online es poden descarregar els canvis amb la comanda:

    git pull
