## Добро пожаловать к нам в сообщество! 👋

Здесь вы найдете людей, увлеченных **ChatGPT** и его внедрением в повседневную жизнь.
Мы реализуем это через телеграм бот, подключенный к ChatGPT и имеющий широкий набор функций которые мы пишем.
Каждый день функций становится всё больше!

🧙 бот умеет:
* понимает контекст в 10 сообщений
* ищет в интернете через **DuckDuckGo**
* выполняет любую **bash** команду в изолированном окружении

🌈 Мотивация для участников:
* бесплатный доступ к боту с лимитом на сообщения (вам не нужно заботится об оплате)
* можно легко и быстро доставить новую фичу в релиз (настроен CI/CD)


## Развертывания телеграм бота в собственном окружении

Для оркестрации docker-контейнеров будем использовать **Nomad**.

1. [Установим Nomad](https://developer.hashicorp.com/nomad/tutorials/get-started/gs-install)
2. [Настраиваем демон](https://developer.hashicorp.com/nomad/tutorials/enterprise/production-deployment-guide-vm-with-consul#configure-systemd) (проверьте пути, могут не совпадать в энтерпрайз версии)
3. Будет полезно настроить файрвол, например [UFW](https://www.digitalocean.com/community/tutorials/how-to-set-up-a-firewall-with-ufw-on-ubuntu-18-04).

<!--

**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->
