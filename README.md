Reguły walidacji w projekcie:

##Imię
- required
- minlength: 2
##Email
- required
- email
##Nazwa użytkownika
- required
- minlength: 3
- remote (AJAX – sprawdzanie czy login istnieje)
##Hasło
- required
- minlength: 6
##Powtórz hasło
- required
- equalTo (musi być identyczne z hasłem)
##Wiek
- required
- digits
- min: 18

