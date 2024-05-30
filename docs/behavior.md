# Поведенческие модели

## Диаграмма обновления состояния игры "Змейка"

[Посмотреть код диаграммы](lab5/gameprocess)
![Сост](https://www.plantuml.com/plantuml/png/dLPDJrD15DtFhvYm0XF-W0k3SU6IXKlZekAB4lf1sih6aDGQGCMa2qbeJ51PkFQrfT8-wFWNplr7djx9ovlcFUehXCmCRyuvzvux7yDMgrrfjj_MgeQ3TcJNqCT8EeZNRALbdrPgaNrdB7-UFtXXDpSVMLmWbXF4k86p3oqcc64Yn-pvYUqrf_cNzEQi7Bf_5vf2O5mvDJcUXatJmbYw59BtqYMYmxRlUUiRdgas5k7Um8A9CmmPy0_6O3vipt7BTee44whN6WVHitfbBw9eIlqF1Tynu8GZw2Q5MCuvEEPnfMMAcGj6S4GG9wSMrvc6AHT9i_yX7OqqPf_GvALqLJM1py0Jfqnhvqsqi_UaKQtkjdORzLRWfxn83ghLByI6XeZYBs9-SPXoo6wWGyxvrV6RGI4JQrPFZSKeB3n-Ow159fdv5wVBzZ80EjncrIcZMh8gqjD2zC90fdmSjVWJJiN3ZQ2sFZCu9-HBQ6I9uonkiIJET97YC1tBJhUh756NNqTAcMc4eKKIhlfO5zSLdGKd9-f-Q9PdeOw_Ae-LJUy7NAYUq_Epk12lethKvA5_lBzV3K_iIY9vC7rdw701OtEV4CMsT1EDyLTwqjLA33LqPchx9I-qdT1NQPKIhaWf89hLGwcxRt0AFiOlZgvyNNd3-pCY7zEza4w7dWgvvtckbIw7YNoGJ-nrPOuymImJAt7fOvOzEU4gPjdUyuRAqadVgldwycNTFeYQwnlBZgi6FDIkM2Pzv_9rZkyYvHznniTWReXzzfeUcgse_eh_6Vm3)

## Диаграмма определение победы/поражения, счётчик очков и состояния выхода из игры.

[Посмотреть код диаграммы](lab5/hodigri)
![[ходигры]](https://www.plantuml.com/plantuml/png/bLF1IiD04BtlL-Giz0SyIFz390ZsfXuqdaGm1HNieU1912tY3snhLwIXxI-y-IFVx93j9SLi80axy-RDcxUxm-lgzAgwkJXtnmSdnM1mLE0Ltt8FxvYfHcbPtEuGCmOsM23mlu8lfSP6QXdpEyKQlp9r1PyUEEFxm9nBHJO8ca0eiMMWuVjZ8M8FanXc8_LICKHujXXBdTjtHjGSWJHUoR-8QxGm2R2iJB9fLMIh7A6RF67CCUtHsugzjb7FavfX4ttAimwWMUgrIRFxz9ZRnFydA8yiRKvR-SR0cdMF9Obv36nRkkpU1xzphZr1XdcHYJmGjrIptYE7LwabLd6GRPI8HGkZUnsyaOkNm-tuKcWukZpZxVe3)

## Диаграмма обработки столкновения змейки с самой собой и границами

[Посмотреть код диаграммы](lab5/obrabotka)
![Столк](https://www.plantuml.com/plantuml/png/hL8zJeH05EuvnLp02rWeLp7HJYqKUw7GncGgevKKNc3OpMI1WTahVEz6-yqZ96GB4f9D83Eyx-TxBu_yjRXxATwU7ZFKY0ZoXGFF7PnKyEdRNDqO_68lxt3N1dzeC2gZbOgeb8XIaXp54cZXivcjoXyCyEZGgxg69-9JJKNgmPlDbiIpo9fd2gHq3jL019B72PgY2V21erL4fxsXqIjQC_abedmeXQMZpcnNMjwQRXaOMEtv3cjJVKkvqUrshKtk9I5fNFgv2pRwhyB0uJyN-yeVdk_vsvm0)

## Диаграмма последовательности обновления состояния игры

[Посмотреть код диаграммы](lab5/sostojania)
![Состо](https://www.plantuml.com/plantuml/png/hLDDJi905DxFAUO2Ni25uIe4NP0WRR3k1HDrOTA5CRhHNg4W4mUhS8NltSZljKy3JOqQ9M6QllVzVFDcsZl9-fFiz7Za-eCicNWKMAEIQpppkK0fCmHzTobXmy4mxOypZtiyoHdAtU8TNebTuQNTkCMoNIf83zX8BZEPqcE1ABbpeoH9JLtj-LzvkK2aPkKyVr_5yti7dwdsFHxOkTGkEuXQblE6RnZYjmF_b6Dx8Vg6p3S4rgDbDMR0qdZDPZGm3RoYFMENX98cLxL0QLOeQyet4Hyn9qVDOcqcKwnrV5npDYB2XyeEipMSmW8pXUaq6gW8RkGr6W_4rBf7y6UTpZlm7xhTLqJdLylC5Sbkt3fgkst1OwDi6-JH-D3zGjvG7QViLAd7XH_QEm00)

## Документация к обновления состояния игры "Змейка"
### Эта схема состоит из двух основных состояний: "Игра" и "Играет", которые представляют основной игровой процесс.

* _Описание схемы состояний_:
1. "Игра" - начальное состояние, отображающее процесс инициализации игры и переход к режиму игры.
2. "Играет" - основное состояние, описывающее игровой процесс, включая движение змейки, проверку столкновений, обновление яблока, рост змейки, генерацию препятствий и завершение хода.

* _Описание взаимодействия состояний_:
Игра начинается с инициализации, переходя в режим "Играет" после старта игры.
В режиме "Играет" происходит последовательный процесс: движение змейки, проверка столкновений (самой с собой и границами), обновление яблока, рост змейки, генерация нового яблока, генерация препятствия, завершение хода и начало нового хода.
Если происходит столкновение, игра переходит к состоянию "КонецИгры", где отображается результат игры.
После завершения игры можно сбросить игру и вернуться к начальному состоянию "Начало".

* _Пример использования_: 
Состояние "Обработка столкновений" позволяет игре корректно определить ситуацию, когда змейка сталкивается с препятствием или самой собой, что приводит к завершению игры в состоянии "КонецИгры". Диаграмма последовательности "Обновление состояния игры" показывает процесс от инициализации до завершения игры, подчеркивая важность ввода пользователя, обновления состояния и проверки условий для завершения игры.


## Схема состояния "Обработка столкновений змейки с самой собой и границами":
### Эта схема состояния представляет процесс обработки столкновений змейки с самой собой и границами в игре "Змейка".

* _Начальное состояние (Столкновение не обнаружено)_:
В этом состоянии игра находится до момента обнаружения столкновения змейки с бомбой.

* _Конечное состояние (Обнаружение столкновения)_:
Игра обнаруживает столкновение змейки с самой собой или границами поля в текущем расположении.


## Диаграмма последовательности "Обновление состояния игры":
### Эта диаграмма последовательности иллюстрирует процесс обновления состояния игры в игре "Змейка".

* _Инициализация игры_:
Игра начинается с инициализации, включая установку начального состояния, загрузку игровых объектов и отображение начального экрана.

* _Получение ввода пользователя_:
Игра ожидает ввода пользователя, включая управление змейкой (нажатие клавиш для движения).

* _Обновление состояния игры_:
После получения ввода пользователя, игра обновляет состояние в соответствии с действиями пользователя и текущим состоянием игрового процесса.

* _Отображение изменений на экране_:
После обновления состояния игры, происходит отображение всех изменений на экране, включая новое положение змейки, еды и т. д.

* _Проверка условий завершения игры_:
Игра проверяет условия, при которых игра может завершиться (например, столкновение змейки с препятствием(самой собой или границами поля) или съедание определенного количества яблок).

* _Завершение игры_:
Если условия завершения игры выполнены, игра завершается, и пользователю предоставляется информация о результате игры (победа/поражение, счёт, время и рекордное время).