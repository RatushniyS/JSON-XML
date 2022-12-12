# Задача №1

## Исходник:
<req>

        <surname>Иванов</surname>

        <name>Иван</name>

        <patronymic>Иванович</patronymic>

        <birthdate>01.01.1990</birthdate>

        <birthplace>Москва</birthplace>

        <phone>8 926 766 48 48</phone>

</req



## Ошибка в 18й строке. Нет закрывающего знака ">"

## Результат
<req>

    <surname>Иванов</surname>

    <name>Иван</name>

    <patronymic>Иванович</patronymic>

    <birthdate>01.01.1990</birthdate>

    <birthplace>Москва</birthplace>

    <phone>8 926 766 48 48</phone>

</req>



# Задача 2

## Исходник:

{

        ""surname"": ""Иванов""

        ""name"": ""Иван""

        ""patronymic"": ""Иванович""

        ""birthdate"": ""01.01.1990""

        ""birthplace"": ""Москва""

        ""phone"": ""8 926 766 48 48""

}

## Ошибки:
1. Не добавлена общая группа
2. Не проставлены запятые в конце строк
3. Лишние (") в каждой строке

## Результат

{
    "main": {
        "surname": "Иванов",
        "name": "Иван",
        "patronymic": "Иванович",
        "birthdate": "01.01.1990",
        "birthplace": "Москва",
        "phone": "8 926 766 48 48"
    }
}