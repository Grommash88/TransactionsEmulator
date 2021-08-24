# TransactionsEmulator

    Программа эмулирует денежные переводы между счетами внутри банка.
    Переводы более 50 000 попадают на проверку "мониторинга".
    Если перевод не проходит проверку оба счета блокируются.

    В классе ru.lakeev.Main реализована эмуляция переводов.

    В классе ru.lakeev.bank.Bank описана логика выполнения переводов между счетами.

    В классе ru.lakeev.bank.Account описаны счета.

    Логирование реализовано в классе ru.lakeev.utils.Log, шаблоны сообщений в классе
    ru.lakeev.utils.messages.LogMsg, настройки в файле src/main/resources/log4j2.xml.

    Классы ru.lakeev.Main, ru.lakeev.bank.Bank и ru.lakeev.bank.Account покрыты тестами.

eng

    The program emulates money transfers between accounts within the bank.
    Over 50,000 translations go to the "monitoring" check.
    If the transfer does not pass the check, both accounts are blocked.

    The ru.lakeev.Main class implements translation emulation.

    The ru.lakeev.bank.Bank class describes the logic of making transfers between accounts.

    Accounts are described in the ru.lakeev.bank.Account class.

    Logging is implemented in the ru.lakeev.utils.Log class, message templates in the class
    ru.lakeev.utils.messages.LogMsg, settings in src / main / resources / log4j2.xml file.

    The ru.lakeev.Main, ru.lakeev.bank.Bank and ru.lakeev.bank.Account classes are covered by tests.