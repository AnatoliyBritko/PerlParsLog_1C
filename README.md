# PerlParsLog_1C
Perl cкрипты для парса логов ТЖ
---
**CALL_BD.pl** - выводит время вызова без учета времени затраченное на СУБД (с учетом многострочного контекста собятия DBMSSQL).
Пример результата:

>Система.ПолучитьФорму:ЖурналДокументов.ЖурналОпераций.Форма.ФормаСписка;ОбщаяФорма.ФормаСтарт;ОбщаяФорма.СУ_ПодписаниеДокументов;ОбщаяФор>ма.ФормаВыбораТекущейОрганизации;Обработка.ИнформационныйЦентр.Форма.ИнформационныйЦентр;Обработка.ПолнотекстовыйПоискВДанных.Форма.Упрощ>еннаяФорма-6822000 (~6.82 сек.)
>ОбщийМодуль.Вызов:ОбщийМодуль.ЛицензированиеСервер.Модуль.ПриНачалеРаботыСистемы-6442992 (~6.44 сек.)
>Система.ПолучитьФорму:Документ.РегистрацияОбязательствИСведенийПоДоговорам.ФормаОбъекта-5164006 (~5.16 сек.)
  

