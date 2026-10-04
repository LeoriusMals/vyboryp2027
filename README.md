# Сайт Тишина Ивана Денисовича

Загрузить `index.html` и `.github/workflows/vk-news.yml`.

Создать GitHub Secret:
`Settings → Secrets and variables → Actions → New repository secret`

Name: `VK_TOKEN`

Затем: `Actions → Обновление новостей VK → Run workflow`.

Workflow каждые 30 минут получает 3 последние публикации VK и обновляет `index.html`.
