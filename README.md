# ubilling-sms

кусочек конфига из config/alter.ini.sms нужно вставить в alter.ini заменив старые параметры

открывай документацию к апи, например
http://smsaero.ru/api/description и читай какие параметры нужны

TSMS_MESSAGE_KEY ставишь ключик, который перед сообщением - для смсаеро "text"

TSMS_PHONE_KEY ставишь имя параметра с телефоном

TSMS_GATEWAY - только то что до знака "?" в запросе

TSMS_PHONEPREFIX - если в билинге телефоны через 9123456789, а шлюз хочет 79123456789 то "7" - добавляется к номеру телефона вообщем

остальные параметры указываешь в поле TSMS_PASSWORD в формате user=USERNAME&password=PA$$W0rD&from=MyTelecom
