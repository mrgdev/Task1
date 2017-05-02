# Task1
Текст не может храниться в string ресурсах под одинаковым id в обоих модулях т.к. при сборке все ID обьеденятся в общий R класс, поэтому во всех id библиотеки нужно использовать какой-нибудь уникальный префикс вроде названия библиотеки.

Разница между 22 и 23 targetSdkVersion будет в том что с 6 версии (23 sdk) добавили runtime permissions и при установке пользователю не будет показываться никаких предложений согласиться с разрешениями (их нужно будет вызывать вручную, по мере необходимости) , в то время как раньше , самой установкой, пользователь подтверждал своё согласие на все разрешения.