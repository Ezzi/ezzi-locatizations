# Вопрос-ответ:

Q: по поводу локализации - давай мы с тобой пройдемся по тому, как делать и заполнять табличку, чтобы избежать потом ошибок. 
1. правильно я понимаю, что нужно перевести содержание ВСЕХ вкладок в файле?
	- да всех
2. при этом, помимо полностью заполненной эксель таблички, на каждый язык нужно сделать 2 файла с правильно оформленным переводом?
	- нет, эксельку надо заполнять все вкладки, КРОМЕ iOS app + Android app (их надо заполнять в файликах , а не эксельке. Чтобы 2 раза одно и тоже не делать ни переводчику, ни нам. Эти файлики сразу вставляются в код приложения и вуаля магия - сразу локализация вставится.
3. в этих файлах содержание только первых 2 вкладок таблички - я имею в виду, что остальные разделы таблички так оформлять не нужно же?)) 
	- Да именно только 2 файла - это приложения, сразу код локализации. Остальное все равно руками мы вставим