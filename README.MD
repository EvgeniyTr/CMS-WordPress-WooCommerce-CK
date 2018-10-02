#  CloudKassir модуль для WordPress - WooCommerce
Модуль позволяет интегрировать онлайн-кассу [CloudKassir](https://cloudkassir.ru) в интернет-магазин на  WordPress - WooCommerce. 
Для корректной работы модуля необходима регистрация в сервисе.

### Возможности:  
	
* Автоматическая отправка чеков прихода;
* Отправка чеков возврата;
* Отправка чеков на email клиента;
* Отправка чеков по SMS;


### Совместимость:
WordPress 4.9.7 и выше;
WooCommerce 3.4.4 и выше;


## Установка модуля
1) Скопируйте содержимое в /wp-content/plugins
2) В /wp-admin/plugins.php активируйте "WooCommerce CloudKassir Gateway"
3) /wp-admin/admin.php?page=wc-settings&tab=checkout в столбце "Включить" укажите "нет"   
![Настройки](pic/1.png)



## Настройка модуля
Для настройки модуля перейдиет в раздел "WooCommerce"=>"Платежи"=> CloudKassir

Укажите следующие настройки:
* **Статус для печати чека прихода** - статус, при переходе в который по заказу будет печататься чек прихода;
* **Статус для печати чека возврата** - статус, при переходе в который по заказу будет печататься чек возрата;
* **Public ID** — Public id сайта из личного кабинета CloudPayments;
* **Пароль для API** — API Secret из личного кабинета CloudPayments;
* **ИНН** — ИНН организации, на которую зарегистрирована онлайн-касса;
* **Система налогообложения** — Тип системы налогообложения;
* **Ставка НДС** — Указание ставки НДС по умолчанию;
* **Ставка НДС для доставки** — Указание отдельной ставки НДС для доставки.

