# Lesson 2

## DZ

* Поднять MySQL
* Поднять Wordpress в 1 реплике и связать с MySQL
* Выкинуть Wordpress через NodePort
* Масштабировать до 2 реплик, сохранив историю  
-- использовать volume - желательно (домашняя директория)  
   [https://kubernetes.io/docs/concepts/storage/volumes/#hostpath](https://kubernetes.io/docs/concepts/storage/volumes/#hostpath)  
-- придется использовать env или configMap (плюсом будет использовать secret для env)
   см. примеры тут: [https://kubernetes.io/docs/user-guide/walkthrough/](https://kubernetes.io/docs/user-guide/walkthrough/)  

