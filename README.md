# telegram-bot-php

* just require everyfile in it (require all files in '/src' also '/src/types')

# Main Repo
* main repo is on GitLab ((https://gitlab.com/ReloadLife/Telegram-Bot-PHP)[https://gitlab.com/ReloadLife/telegram-bot-php])


# some examples

```php
<?php

namespace TEST;
use TelegramBotPHP;

$telegram = new methods ( 'TOKEN' );
$updates = new getUpdates ();

if ( $updates->text ) {
    $telegram->sendMessages([
        'chat_id' => $updates->from->id,
        'text' => $updates->text,
    ]);
}

// :)

```


# ?

* if you have any question about it you can contact me right there [Telegram](tg://resolve?domain=reloadlife) [Email: me@reloadlife.me](mailto:me@reloadlife.me)
* if you liked it star project to support me and if you like me [Get me A cup of coffee](https://zarinp.al/216172)
* enjoy :)
