# Домашнее задание

(Требуется Xcode 12.2+, иначе могут быть проблемы с билдом. В случае чего, пишите.)

__Реализовать загрузку экрана детальной информации о пользователе.__

1. Запрос описан тут: https://reqres.in, конкретно интересует "SINGLE USER": https://reqres.in/api/users/2 (цифру 2 нужно менять в зависимости от того, какой id пользователя передан).
2. Добавить метод нужно в `UserService`, использовать его нужно из `UserViewController` (он уже создан и интерфейс готов для использования).
3. Для референса используйте метод `UserService.loadUsers`, но в новый метод id нужно устанавливать с помощью метода `URL.appendingPathComponent`, а не `URLQueryItem`.
