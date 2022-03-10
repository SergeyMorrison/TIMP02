# TIMP02
# Part 1
1. Создайте пустой репозиторий на сервисе github.com
    `https://github.com/SergeyMorrison/TIMP02`
2. Выполните инструкцию по созданию первого коммита на странице репозитория, созданного на предыдещем шаге.
<img width="523" alt="image" src="https://user-images.githubusercontent.com/99497212/157735315-41d42c34-f64b-4b83-859f-35d0384614d3.png">
3. Создайте файл hello_world.cpp в локальной копии репозитория (который должен был появиться на шаге 2). Реализуйте программу Hello world на языке C++ используя плохой стиль кода. Например, после заголовочных файлов вставьте строку using namespace std;.
<img width="294" alt="image" src="https://user-images.githubusercontent.com/99497212/157737032-628a0ab5-5b98-48cd-91e1-dee617455171.png">

```
    #include <iostream>
    using namespace std;
    int main()
    {
    cout << "hello world" << endl;
    return 0;
    }
```

4. Добавьте этот файл в локальную копию репозитория.
<img width="551" alt="image" src="https://user-images.githubusercontent.com/99497212/157737095-5903467e-419b-462b-a252-ceab382e73f9.png">
5. Закоммитьте изменения с осмысленным сообщением.
  <img width="383" alt="image" src="https://user-images.githubusercontent.com/99497212/157737600-871cbf83-4808-452a-8312-92d38a72ab9a.png">
6. Изменитьте исходный код так, чтобы программа через стандартный поток ввода запрашивалось имя пользователя. А в стандартный поток вывода печаталось сообщение Hello world from @name, где @name имя пользователя.
<img width="259" alt="image" src="https://user-images.githubusercontent.com/99497212/157737866-47c1183b-0586-45f2-9d81-cd44e716d4be.png">
  <img width="315" alt="image" src="https://user-images.githubusercontent.com/99497212/157738501-786bacb3-9f0c-4291-b691-bbe9243c580c.png">
7. Закоммитьте новую версию программы. Почему не надо добавлять файл повторно git add?
<img width="284" alt="image" src="https://user-images.githubusercontent.com/99497212/157738869-cd63d5fe-61f4-4582-9a57-b01268981358.png">
8. Запуште изменения в удалёный репозиторий.
  <img width="296" alt="image" src="https://user-images.githubusercontent.com/99497212/157739082-c5bc811b-d9a4-4d47-8d1c-e9cd481d29b7.png">
9. Проверьте, что история коммитов доступна в удалёный репозитории.
  <img width="883" alt="image" src="https://user-images.githubusercontent.com/99497212/157740881-8ddf58f6-96da-49d8-abb4-9e33e6c20be5.png">

# Part 2
1. В локальной копии репозитория создайте локальную ветку patch1.
<img width="271" alt="image" src="https://user-images.githubusercontent.com/99497212/157742784-5d940bde-013b-444c-b886-b59778ff66a4.png">
2. Внесите изменения в ветке patch1 по исправлению кода и избавления от using namespace std;.
<img width="311" alt="image" src="https://user-images.githubusercontent.com/99497212/157743121-88249566-b6a8-446d-81bd-9780657251d1.png">
3. commit, push локальную ветку в удалённый репозиторий.
<img width="364" alt="image" src="https://user-images.githubusercontent.com/99497212/157743620-6da288d7-abda-44f2-ae68-97dce5437e1e.png">
4. Проверьте, что ветка patch1 доступна в удалёный репозитории.
<img width="908" alt="image" src="https://user-images.githubusercontent.com/99497212/157743833-33544ccf-9121-4842-baa8-30d2b7bcbb50.png">
5. Создайте pull-request patch1 -> master.
<img width="676" alt="image" src="https://user-images.githubusercontent.com/99497212/157745952-13656c0e-9a9b-488a-bcfc-ad6f201b013d.png">
6. В локальной копии в ветке patch1 добавьте в исходный код комментарии.
<img width="384" alt="image" src="https://user-images.githubusercontent.com/99497212/157746558-71cfa61a-5ebc-400b-ba32-f4f2f6f6aedf.png">
7.commit, push.
<img width="343" alt="image" src="https://user-images.githubusercontent.com/99497212/157747501-40a5a89d-83e9-4fc0-ae1c-641e05bc7745.png">
8. Проверьте, что новые изменения есть в созданном на шаге 5 pull-request
<img width="481" alt="image" src="https://user-images.githubusercontent.com/99497212/157747299-ead2e380-ba2f-4e6f-8973-de9624d4fa86.png">
9. В удалённый репозитории выполните слияние PR patch1 -> master и удалите ветку patch1 в удаленном репозитории. 
<img width="309" alt="image" src="https://user-images.githubusercontent.com/99497212/157749236-16e22e22-2125-495e-b47a-7e4418d96af3.png">
10. Локально выполните pull.
<img width="374" alt="image" src="https://user-images.githubusercontent.com/99497212/157749295-4de83e15-9dd6-43f1-b47d-0ad592014422.png">
11. С помощью команды git log просмотрите историю в локальной версии ветки master.
<img width="436" alt="image" src="https://user-images.githubusercontent.com/99497212/157749563-a5ef1610-6729-490d-8f74-f23eac25d14a.png">
12. Удалите локальную ветку patch1.
<img width="298" alt="image" src="https://user-images.githubusercontent.com/99497212/157749825-c766b3ea-538d-49ac-9b9c-934ef0509233.png">

# Part 3
1. Создайте новую локальную ветку patch2.
<img width="298" alt="image" src="https://user-images.githubusercontent.com/99497212/157751631-8457a032-7bb4-4195-b6d0-c326278a3f2e.png">
2. Измените code style с помощью утилиты clang-format. Например, используя опцию -style=Mozilla.
<img width="411" alt="image" src="https://user-images.githubusercontent.com/99497212/157752050-ed44d138-479d-4bc6-8266-ea774dee37bd.png">
3. commit, push, создайте pull-request patch2 -> master.
<img width="385" alt="image" src="https://user-images.githubusercontent.com/99497212/157752500-0fdb698d-2ac4-4155-838d-fb9b8c99b788.png">
<img width="400" alt="image" src="https://user-images.githubusercontent.com/99497212/157752638-035e0486-6d21-47c0-8cf5-7d53009db5d5.png">
4. В ветке master в удаленном репозитории измените комментарии, например, расставьте знаки препинания, переведите комментарии на другой язык.

5. Убедитесь, что в pull-request появились конфликтны.
 <img width="565" alt="image" src="https://user-images.githubusercontent.com/99497212/157753487-baae3ab3-825f-405a-8482-edec323a5ebe.png">
6. Для этого локально выполните pull + rebase (точную последовательность команд, следует узнать самостоятельно). Исправьте конфликты.
<img width="355" alt="image" src="https://user-images.githubusercontent.com/99497212/157773306-474bafa2-8564-4470-810c-b720f7c89f63.png">
<img width="356" alt="image" src="https://user-images.githubusercontent.com/99497212/157773436-505aa431-c173-4579-9fc1-8f770eade6d4.png">
<img width="327" alt="image" src="https://user-images.githubusercontent.com/99497212/157773459-e7848042-7845-4751-b400-9938f54689ea.png">

7. Сделайте force push в ветку patch2
<img width="336" alt="image" src="https://user-images.githubusercontent.com/99497212/157773511-41435ec0-a141-4c85-a83f-49601880a936.png">
8. Убедитеcь, что в pull-request пропали конфликтны.
<img width="398" alt="image" src="https://user-images.githubusercontent.com/99497212/157773577-2553a70e-8ba2-43ff-9f28-5db78397fbc2.png">
9. Вмержите pull-request patch2 -> master.
<img width="376" alt="image" src="https://user-images.githubusercontent.com/99497212/157773636-410caac4-27b8-4aaa-98cc-8d26e20f5ad8.png">






