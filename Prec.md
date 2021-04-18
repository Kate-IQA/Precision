# Отчёт о тестировании <Precision>

## Проверка бонусной системы

<09.04.2021> - <09.04.2021> было проведено <позитивное тестирование> приложения <Стартап Validator>.

На тестирование затрачен <1 час>

В результате тестирования выявлен следующий дефект:

<https://github.com/Kate-IQA/Precision/issues/1#issue-855307636>


В процессе тестирования использовался следующий артефакт*:
* <Тест-кейс на проверку данных>



В качестве тестовых данных использовались исходные данные кода:
* <public class Main {
  public static void main(String[] args) {
  double regularBonus = 0.3;
  double specialBonus = 0.6;
  double totalBonus = regularBonus + specialBonus;
  System.out.println(totalBonus);
  }
  }>
  
Тестирование производилось в следующем окружении:
* <Windows 10 и разрядность ОС 64 >
* <версия Java 11.0>
