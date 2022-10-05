npx storybook init - установка storybook

npm run storybook - запуск storybook на порту 6006

npm i -D loki - установка loki

npx loki init - инициализация loki

// можно в package.json loki.configurations["chrome.laptop"].target изменить с chrome.docker на chrome.app,
// чтобы не запускать в docker-еyukinying/chrome-headless-browser-stable
sudo docker pull yukinying/chrome-headless-browser-stable - запулить docker образ для работы loki

sudo docker images - просмотр списка образов

sudo docker run yukinying/chrome-headless-browser-stable - запуск образа
//

npm run test:loki - запустить тестирование loki (снимает скриншоты)

npx loki approve - согласование изменении
