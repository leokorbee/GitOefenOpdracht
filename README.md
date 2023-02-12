# Oefenproject Git Deployment
Dit is de oefenopdracht:
 
1. Clone deze naar je locale machine
   
2. verwijder de .git directory

Powershell (PS):

```
Remove-Item '.git' -Recurse
```

CMD: 
    
```
rmdir .git
```

unix: 
    
```
rm -rf .git
```

3. maak een nieuwe lokale repository
    
4. Pas het project aan en maak een aantal commits:
    - Zet er een ander plaatje in!
    - Maak van index.html index.php
    - Zorg dat de actuele datum en tijd op de pagina komt te staan
    - Zet je naam op de pagina
    
5. Zorg dat dit project via een private github repository naar je linux machine wordt gedeployed.
    
6. Laat de docent de website zien draaien vanaf je lokale unix machine.
