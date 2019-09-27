# infbomber
Бомбер c Top.Запускается немного дольше с Тором, но отлично работает, если жалуется на 64 бита вместо 32, то ниже как исправить, переписывать в точно так как написано.

Как правильно установить СНАЧАЛА ПРОПИСЫВАЕМ ВСЕ ЭТО В Termux, а потом уже исправляем проблему с "64 бит"

apt update

apt upgrade

pkg install git

pkg install tsu

pkg install python

pkg install python2

pkg install openssh

git clone https://https://github.com/eden13378/infbomber

cd infbomber

tsu

chmod +x ./infbomber

./infbomber


Проблема с 64 бит

$ su

$ which su

$ sh -x su

$ sh -x $(which su)

$ unset LD_PRELOAD После этого пишем ./infbomber и все должно запуститься. После перезапуска прийдется прописывать заново условие $ which su $ sh -x su $ sh -x $(which su) $ unset LD_PRELOAD И только потом можно

cd infbomber
./infbomber
После запуска можно запустить так же командной ./infbomber 79123456789 3 1 60

3 Это режим SMS + Звонок
1 Показывать только удачные
60 Время в секундах ( Если значение 0 то бесконечно )
Разработчик notBrut0r https://codeby.net/threads/infinite-bomber-sms-call-flud.68693/
