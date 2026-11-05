//1
//void main() {
  //String name = 'Иван';
  //String surname = 'Иванов';
  //int age = 19;
  //String city = 'Бишкек';
  //int course = 2;
  //double averageGrade = 4.8;
  //print('Имя: $name');
  //print('Фамилия: $surname');
  //print('Возраст: $age');
  //print('Город: $city');
  //print('Курс: $course');
  //print('Средний балл: $averageGrade');
  //print('');

  
  
//2
  //double num1 = 15.0;
  //double num2 = 4.0;
  //print('Число 1: $num1');
  //print('Число 2: $num2');
  //print('Сумма: ${num1 + num2}');
  //print('Разность: ${num1 - num2}');
  //print('Произведение: ${num1 * num2}');
  //print('Деление: ${num1 / num2}');
  //print('');


  
  //3
  //double item1Price = 1200.0;
  //double item2Price = 850.0;
  //double item3Price = 450.0;
  //double totalBeforeDiscount = item1Price + item2Price + item3Price;
  //double discountAmount = totalBeforeDiscount * 0.10; // Скидка 10%
  //double finalPrice = totalBeforeDiscount - discountAmount;
  //print('Стоимость товаров: $totalBeforeDiscount');
  //print('Скидка (10%): $discountAmount');
  //print('Итоговая стоимость: $finalPrice');
  //print('');


  
  //доп
 // int studentAge = 19;
  //print('Возраст: $studentAge');
  //if (studentAge >= 18) {
    //print('Совершеннолетний');
  //} else {
    //print('Несовершеннолетний');
  //}
//}







//Дз номер:2
//1
//void main() {
  //int age = 16;
  //if (age >= 18) {
    //print('Доступ разрешён');
  //} else {
    //print('Доступ запрещён');
  //}
  //print('');


  //2
  //int number = 7;
  //if (number % 2 == 0) {
    //print('Число чётное');
  //} else {
    //print('Число нечётное');
  //}
  //print('');

  
  
 //3
  //int score = 85;
  //if (score < 0 || score > 100) {
    //print('Некорректное значение балла');
  //} else if (score >= 90) {
    //print('Отлично');
  //} else if (score >= 70) {
    //print('Хорошо');
  //} else if (score >= 50) {
    //print('Удовлетворительно');
  //} else {
    //print('Неудовлетворительно');
  //}
  //print('');

  
  
  //4
  //String login = 'rertttw432';
  //String password = 'secretpassword';
  //String correctLogin = 'rertttw432';
  //String correctPassword = 'secretpassword';
  //if (login == correctLogin && password == correctPassword) {
    //print('Вход в приложение выполнен успешно');
  //} else {
    //print('Неверный логин или пароль');
  //}
  //print('');

  
  
//5
  //int buyerAge = 16;
  //bool hasStudentId = true;
  //if (buyerAge < 18 || hasStudentId) {
    //print('Вам положена скидка 10%!');
  //} else {
    //print('Скидка не предоставляется');
  //}
  //print('');

//6
  //int userAge = 20;
  //bool isRegistered = true;
  //bool isBanned = false; 
  //if (userAge >= 18 && isRegistered && !isBanned) {
    //print('Доступ разрешён');
  //} else {
    //print('Доступ запрещён');
  //}
//}









//Дз номер:3
//1
//void main() {
  //int age = 17;
  //bool isStudent = true;
  //bool isBlocked = false;

  //if (isBlocked) {
    //print('Доступ запрещён');
  //} else if (!isBlocked && age >= 18) {
    //print('Доступ разрешён');
  //} else if (age < 18 && isStudent) {
    //print('Доступ разрешён для студента');
  //} else {
    //print('Доступ запрещён');
  //}
  //print('');

  
  
//2
  //List<int> numbers = [12, 5, 8, 21, 16, 3, 10];
  //print('Элементы списка:');
  //for (int i = 0; i < numbers.length; i++) {
    //print(numbers[i]);
  //}

//2
  //int sum = 0;
  //for (int i = 0; i < numbers.length; i++) {
    //sum += numbers[i];
  //}
  //print('Сумма всех элементов: $sum');

  //3
  //int evenCount = 0;
  //int oddCount = 0;
  //for (int i = 0; i < numbers.length; i++) {
    //if (numbers[i] % 2 == 0) {
      //evenCount++;
    //} else {
      //oddCount++;
    //}
  //}
  //print('Чётных чисел: $evenCount, Нечётных чисел: $oddCount');

  //4
  //print('Числа больше 10:');
  //for (int i = 0; i < numbers.length; i++) {
    //if (numbers[i] > 10) {
      //print(numbers[i]);
    //}
  //}

//5
  //int maxNumber = numbers[0];
  //for (int i = 1; i < numbers.length; i++) {
    //if (numbers[i] > maxNumber) {
      //maxNumber = numbers[i];
    //}
  //}
  //print('Самое большое число: $maxNumber');
  //print('');

//Задание 3
 // List<int> grades = [85, 42, 90, 67, 55, 100, 38];

  //int passedCount = 0;
  //int failedCount = 0;
  //int totalGradesSum = 0;

  //print('Оценки и результат:');
  //for (int i = 0; i < grades.length; i++) {
    //int grade = grades[i];
    //totalGradesSum += grade;
    //String result = '';
    //if (grade >= 90) {
      //result = 'Отлично';
    //} else if (grade >= 70) {
      //result = 'Хорошо';
    //} else if (grade >= 50) {
      //result = 'Удовлетворительно';
    //} else {
      //result = 'Неудовлетворительно';
    //}
    //print('Балл $grade — $result');
    //if (grade >= 50) {
      //passedCount++;
    //} else {
      //failedCount++;
    //}
  //}

  //print('Количество сдавших: $passedCount');
  //print('Количество не сдавших: $failedCount');
  //double averageGrade = totalGradesSum / grades.length;
  //print('Средний балл группы: $averageGrade');
  //if (averageGrade >= 70 && passedCount > failedCount) {
    //print('Группа успешно сдала экзамен');
  //} else {
    //print('Результаты группы необходимо улучшить');
  //}
  //print('');



  //List<String> products = ['Хлеб', 'Молоко', 'Яйца'];
  //List<int> prices = [40, 80, 120];
  //print('Товары в корзине:');
  //for (int i = 0; i < products.length; i++) {
    //print('${products[i]} — ${prices[i]} сом');
  //}
  //int cartTotal = 0;
  //for (int i = 0; i < prices.length; i++) {
    //cartTotal += prices[i];
  //}
  //print('Общая стоимость без скидки: $cartTotal сом');
  //double finalCartPrice = cartTotal.toDouble();
  //if (cartTotal > 500) {
    //finalCartPrice = cartTotal - (cartTotal * 0.20); // Скидка 20%
    //print('Применена скидка 20%');
  //} else if (cartTotal > 200) {
    //finalCartPrice = cartTotal - (cartTotal * 0.10); // Скидка 10%
    //print('Применена скидка 10%');
  //} else {
    //print('Скидка не применяется');
  //}
  //print('Итоговая стоимость с учётом скидки: $finalCartPrice сом');
//}




//dart-game
void main() {
    print ('Мини Арена');
    
    // In DartPad, we simulate the name input
    String name = 'Beka';
    print('Имя игрока: $name');

    int health = 100;
    int attack = 20;
    int potions = 2;
    int defeated = 0;
 
    
    print ('\nГерой: $name');
    print ('Здоровье: $health');
    print ('Атака: $attack');
    print ('Зелья: $potions');

    List<String> enemies = ['Слизень', 'Скелет', 'Дракон'];
    List<int> enemyHealth = [30, 40, 50];
    List<int> enemyAttack = [10, 15, 20];

    for (int i = 0; i < enemies.length; i++) {
        print ('\n== ${enemies[i]} ==');

        while (health > 0 && enemyHealth[i] > 0) {
            print('\nВаше здоровье: $health');
            print('Здоровье противника: ${enemyHealth[i]}');
            print ('Зелья: $potions');
            
            // Simulating an aggressive strategy (always attack) 
            // since stdin is not available in DartPad
            print ('Авто-атака против ${enemies[i]}');
            
            enemyHealth[i] -= attack;
            print('Вы нанесли $attack урон');
            
            if (enemyHealth[i] > 0) {
                health -= enemyAttack[i];
                print('Противник атаковал, ваше здоровье: $health');
            }

            if (health <= 0) {
                print('\nИгра окончена');
                return;
            }
        }
        
        if (health > 0) {
            print('\nВы победили: ${enemies[i]}');
            defeated++;
        }
    }
    print('\nПоздравляем! Вы прошли арену. Всего повержено врагов: $defeated');
}
