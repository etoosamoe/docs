# Документация Yandex.Cloud

Приветствуем в репозитории yandex-cloud/docs. Здесь вы можете предложить дополнения и правки для [документации](https://cloud.yandex.ru/docs) Yandex.Cloud или сделать их самостоятельно и получить грант в рамках контент-программы.

## Предложить правки

Откройте Issue и напишите свои замечания и предложения там. Мы вернемся с ответом. Если вам требуется помощь в работе с облаком, обратитесь в техническую поддержку.
 
## Поучаствуйте в контент-программе

Контент-программа Yandex.Cloud позволяет вам самим написать документацию и получить за нее грант на ваш платежный аккаунт. Поучаствовать в контент-программе можно двумя способами:

1. Если вы заметили опечатку или у вас есть небольшая правка, сделайте PR. Такие правки мы рассматриваем быстро и обычно они не требуют обсуждения.
1. Если вы хотите написать большой текст, пошаговое руководство или внести крупные смысловые правки, откройте Issue и расскажите, о чем вы хотите написать. Не нужно сразу приносить большой PR: давайте сначала обсудим ваши идеи и вместе решим, как действовать дальше.

Обратите внимание на [список важных тем](guides/needs-contributing.md) — за них мы начисляем повышенные гранты.

Чтобы мы знали, куда зачислить грант, обязательно укажите идентификатор вашего платежного аккаунта в Issue или PR.

## Про документацию

Документация разработана с использованием [Yandex Flavored Markdown](https://github.com/yandex-cloud/yfm-docs). [Подробнее про синтаксис](guides/yfm-syntax-ru.md).

## Как предложить правки

Чтобы предложить правки, вы должны прочитать «Лицензионное Соглашение Яндекса с Контрибьютором»  и подтвердить свое согласие с его условиями. Подробная информация о том, как это сделать, и ссылки на текст Соглашения приведены в файле [CONTRIBUTING.md](CONTRIBUTING.md).

Если вы заметили опечатку или ошибку в документации или хотите дополнить какой-то раздел, создайте pull request (PR) с правками через GitHub.

## Как собрать документацию локально

Перед тем так создавать pull request, удобно собрать документацию локально и посмотреть на нее вживую. Для этого используется инструмент [yfm-docs](https://github.com/yandex-cloud/yfm-docs).

1. Установите **yfm-docs**:
  
   `npm i @doc-tools/docs -g`
  
   Чтобы обновить версию **yfm-docs**, используйте эту же команду.

1. Соберите документацию: 
  
   `yfm -i docs -o docs-gen`, где `docs` — каталог с исходными текстами, а `docs-gen` — каталог, в котором будет находится сгенерированная документация.

## Лицензии

© YANDEX LLC, 2018. Licensed under Creative Commons Attribution 4.0 International Public License. See [LICENSE](LICENSE) file for more details.
