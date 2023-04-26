=============Json format=============

{
  "Name": "Название теста",
  "Questions": [
    {
      "Name": "Question1",
      "Answers": [
        {
          "Name": "Answer1",
          "IsTrue": true
        },
        {
          "Name": "Answer2",
          "IsTrue": false
        }
      ]
    },
    {
      "Name": "Question2",
      "Answers": [
        {
          "Name": "Answer1",
          "IsTrue": false
        },
        {
          "Name": "Answer2",
          "IsTrue": true
        }
      ]
    }
  ]
}

=========TXT Format================

  Вопрос
  1) Ответ1; 2) Ответ2; 3) Ответ3; 4) Ответ4; 5) Ответ5;
  Правильный вариант ответа
  [Пустая строка] (1)

=========================================================================================================================

!!!!!!! Для считывания тестов в формате TXT, раскомментировать метод ReadTestFromFile(string filepath) в CustomFileService !!!!!!!!!