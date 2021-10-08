# Отчёт о тестировании Precision

## Краткое описание

06.10.2021 было проведено дымовое тестирование базового приложения с бонусной системой Precision.

На тестирование затрачено: 0,15 часа

В результате тестирования выявлены следующие дефекты:
* [Неверный итоговый бонус после регистрации нового клиента](https://github.com/Prizma96/hw2-2/issues/1)


## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты*:
* [Последовательность действий из Задача №2 - Precision](https://github.com/netology-code/javaqa-homeworks/tree/master/programming)


В качестве тестовых данных использовались [данные из задачи №2 - Precision:](https://github.com/netology-code/javaqa-homeworks/tree/master/programming)
* Кусок кода для бонусной системы
 
* `public class Main {
  public static void main(String[] args) {
  double regularBonus = 0.3;
  double specialBonus = 0.6;
  double totalBonus = regularBonus + specialBonus;
  System.out.println(totalBonus);
  }
  }`


Тестирование производилось в следующем окружении:
* ОС Windows7, x64
* Java 11.0.12
