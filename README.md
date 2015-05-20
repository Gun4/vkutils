## VK utils
Збірник скриптів для полегшення роботи з [VK](http://vk.com)

### Зміст
**DownloadVkAlbum** — завантаження альбому спыльноти/користувача.

**VKSpySystem** — стеження за користувачем. На даний момент вміє знаходити вік користувача та перевіяти, що останнім часом він лайкав.

###  Розгортання 
Для роботи потрібен Python 3. Також потрібно встановити залежності. Це можна зробити як лише для окремого скрипа, так і всі одразу. Зараз це не має значення, оскільки використовується лише 1 модуль (vk).
```bash
# Окремий скрипт
pip install -r VKSpySystem/requirements.txt
# Всі разом
pip install -r requirements.txt
```
Також в кожному скрипті потрібно логінитися, тому заповніть змінні login та password. 

### Ліцензія
Цей проект розповсюджується за ліцензією [GNU General Public License, version 3](http://opensource.org/licenses/GPL-3.0)