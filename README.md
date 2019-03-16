# Testowanie jednostkowe :: Zadania
## JUnit 4 i TDD
- Z wykorzystaniem biblioteki `JUnit` w wersji 4, dostarcz testy jednostkowe dla metod z klas 
`SimpleCalculator` oraz `StackExercise`. 
- Wykorzystaj metodykę *Test-driven development* i dostarcz (najpierw) testy oraz (potem) 
implementację dla metod w klasach `FizzBuzz` i/lub `Divisibility`.


## Parametryzowanie z `JUnitParamsRunner`
Dostarcz testy parametryczne z uzyciem `RunWith(JUnitParamsRunner.class)` dla Twoich klas testowych.
Wykorzystaj dwa przedstawione sposoby: 
- przez adnotację
- przez oddzielną metodę


## AssertJ
Przeanalizuj klasy w pakiecie `pl.lodz.p.zzpj.testing.assertj`, a następnie 
otwórz klasę `FellowshipAssertionTest` i uzupełnij metody testujące zgodnie z ich opisem.
Wykorzystaj API biblioteki *AssertJ*.


## Exceptions handling
Wykorzystaj sposoby testowania wyjątków przedstawione na wykładzie w swojej klasie testowej.
Użyj:
- `@Test(expected = YourException.class)`
- `ExpectedException` 
- asercji z biblioteki *AssertJ*: `assertThatExceptionOfType` oraz `assertThatThrownBy`


## Junit 5
*TODO*

## Junit 5 Extensions
*TODO*
