Решение: т.к. при запросе картинки с сервера летит заголовок referrer (содержащий все параметры запуска), то необходимо добавить meta атрибут.
`<meta name="referrer" content="no-referrer" />` 
