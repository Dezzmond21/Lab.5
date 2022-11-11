# Lab.5
Lab.5

1. Створення нового репозиторію

![image](https://user-images.githubusercontent.com/46502035/201253178-b5a5c533-15e2-43ff-95b6-6cd0ece64898.png)

2. Створення першого commit’у

![image](https://user-images.githubusercontent.com/46502035/201253590-173b302e-3526-4fa2-98f7-c10d643819a1.png)

![image](https://user-images.githubusercontent.com/46502035/201254035-c375a15d-d321-470b-9b8b-a7872c68a8ea.png)

3.Створення гілки develop

![image](https://user-images.githubusercontent.com/46502035/201255274-8f94560b-bd72-4e40-9eb6-8b9817770d70.png)

![image](https://user-images.githubusercontent.com/46502035/201255979-fc12d483-d07d-4117-8233-69be23c2a5d8.png)

![image](https://user-images.githubusercontent.com/46502035/201256374-47dc102b-6d7e-40be-bdd9-aa90cb6a0eea.png)

4.Створення гілки release

![image](https://user-images.githubusercontent.com/46502035/201256780-3d766ee7-68fc-4f5a-b83a-dd3b609dbaf1.png)

![image](https://user-images.githubusercontent.com/46502035/201257171-04c36ac6-cab4-4f98-a322-ecbf962d7d42.png)

![image](https://user-images.githubusercontent.com/46502035/201257300-404a40b9-3d9c-4d20-a9bf-5acb71e39c1e.png)

5. Створення гілки hotfix

![image](https://user-images.githubusercontent.com/46502035/201257607-d1cbd154-1510-4548-b989-5367b05271f8.png)

![image](https://user-images.githubusercontent.com/46502035/201257685-0307b368-5ef5-4380-b4ea-f82832d9acc7.png)

6. Перенесення на віддалений репозиторій

![image](https://user-images.githubusercontent.com/46502035/201260716-d6557e5c-26d0-4f87-a680-cc803b334575.png)


Висновок
У ході роботи познайомилися з паттерном роботи з гілками у git та
освоїли ще один інструмент роботи з git – SourceTree.

Контрольні запитання
1. Скільки типів гілок у git-flow існує?

Всього існує декілька гілок у git-flow: головна main(або ж master), потім develop, feature, release, hotfix

2. Для чого призначена гілка master?

Гілка master створюється при ініціалізації репозиторію, що
має бути знайомим кожному користувачеві Git. В git-flow – це гілка, куди
надходять найстабільніші зміни, які йдуть в реліз. Існує протягом усього
процесу розробки. В гілку master зливаються тільки зміни з гілок release і
hotfix. На кожне таке злиття створюється тег з ім’ям версії.

3. Для чого призначена гілка develop?

Гілка develop вважається головною гілкою для розробки. Код, що зберігається в ній, в будь-який момент часу повинен містити найостанніші
видані зміни, необхідні для наступного релізу.
Суть в тому, що вся робота відбувається в гілці develop, а в гілці
master зміни зливаються, коли є якась готова версія продукту – реліз

4. У чому різниця між гілками feature та hotfix?

Feature гілка використовується для створення нових функцій у самій програмі, а hotfix для вирішення проблем які уже є в релізному продукті

5. Для чого застосовується команда Start a New Release?

Для того аби створити гілку Release у Sourcetree

6. Для чого застосовується команда Publish to Remote…?

Аби перемістити репозиторій із локального місця перебування у віддалений
