###Возвращает текущий тип пользователя. Для менеджера возвращается manager, а для пользователя на сайте web

*Замечание: метод учитывает соответствие типа пользователя. Поэтому для авторизованного менеджера на самом сайте тип определяться не будет (вернется пустое значение).*

mixed getLoginUserType();

***

####Пример

	echo 'Тип пользователя: ' . $modx->getLoginUserType(); 
	
	// полученный результат: 
	// Тип пользователя: web