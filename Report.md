# Отчёт о тестировании Bonus

## Краткое описание

01.04. - 01.04.2021 было проведено функциональное тестирование приложения Bonus.

На тестирование затрачено: 1 час 

В результате тестирования выявлены следующие дефекты:
* [Неточность вычисления результата переменной типа double](https://github.com/laroffi/bonus/issues/1) 


## Описание процесса тестирования

В качестве тестовых данных использовались данные из [Спецификации](https://github.com/netology-code/javaqa-homeworks/tree/master/programming):
* Ввести в файл Main.class следующий код: 
  public class Main {
  public static void main(String[] args) {
    double regularBonus = 0.3;
    double specialBonus = 0.6;
    double totalBonus = regularBonus + specialBonus;
    System.out.println(totalBonus);
  }
}
Результат: 0,9 

Тестирование производилось в следующем окружении:
* Windows 10
* Java 11
