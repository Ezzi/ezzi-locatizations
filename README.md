# Библиотека локализаций #

[Открываем гугл док](https://docs.google.com/spreadsheets/d/14inhPXIGcEfE2mMIJT80JKmYVstMNAvs6Hk3PzmSY_A/edit#gid=0) и экспортируем себе на компьютер как эксельку

Разделы, которые необходимо локализовать, выражены вкладками в эксельке

Локализация приложений:

	- iOS app : приложение для iOS
	- OS X App : приложение для OS X

Метаданные приложений:

	- iTunesConnect Metadata : текстовое описание того, как приложение выглядит в iOS App Store
	- iOS Screenshot texts
	- OS X Metadata
	- Keywords
	- Android metadata

# Как работать

Скачиваем эксельку и обращаем внимание на вышеуказанные вкладки.

Локализацию приложений надо делать через файлики - их можно скачать тут:

iOS: https://raw.githubusercontent.com/Ezzi/ezzi-locatizations/master/cidertv/strings/english/ios.strings

OS X: https://raw.githubusercontent.com/Ezzi/ezzi-locatizations/master/cidertv/strings/english/osx.strings

Эти файлики открываем в текстовом редакторе и в кавыках после знака = выставляем значения вашего перевода.
Справа от знака равенства - значение поля, слева - ключ. Ключи это поле "key" в эксельке. Там же показано оригинальное англоязычное значение. Для OS X версии добавлен даже скриншот.

Локализацию метаданных надо сразу писать в эксельке

## Как скачать CiderTV, если у меня есть айфон, андроид или мак?

[iOS](https://itunes.apple.com/ru/app/cidertv-free-remote-tv-volume/id1017677047?mt=8)

[OS X](https://itunes.apple.com/us/app/cidertv/id1065907486?mt=12)

[Android](https://play.google.com/store/apps/details?id=com.ezzi.cidertv&utm_source=global_co&utm_medium=prtnr&utm_content=Mar2515&utm_campaign=PartBadge&pcampaignid=MKT-AC-global-none-all-co-pr-py-PartBadges-Oct1515-1)

### Зачем этот репозиторий? ###

* Чтобы сразу вставлять локализацию в приложение
* При этом разработчик не будет тратить лишнего времени на вбивание нужных локализованных строк

### Какой результат должен быть от вас ###

Три вещи:
	- Экселька с метаданными
	- файлики ios.strings & osx.strings с полностью заполненными полями

### Who do I talk to? ###

Алмас - almas@ezzi.com

Если что-то изменится - на этой странице будет объявления

### Объявления ###

Пока ничего нового на 11 февраля