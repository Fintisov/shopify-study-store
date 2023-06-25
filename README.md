# shopify-study-store

<ul>
<li class="has-line-data" data-line-start="8" data-line-end="9">
Откроется браузер, нужно будет залогинится, далее в терминале выбрать под каким из партнерских аккаунтов заходим.
<pre><code class="has-line-data" data-line-start="10" data-line-end="12">shopify login --store https://fintisov1.myshopify.com/</code></pre>
<hr>
</li>
<li class="has-line-data" data-line-start="8" data-line-end="9">
Стягивает тему из стора, в терминале предложит какую именно
<pre><code class="has-line-data" data-line-start="10" data-line-end="12">shopify theme pull</code></pre>
<hr>
</li>
<li class="has-line-data" data-line-start="8" data-line-end="9">
Клонирует Dawn тему с официального репозитория
<pre><code class="has-line-data" data-line-start="10" data-line-end="12">shopify theme init</code></pre>
<hr>
</li>
<li class="has-line-data" data-line-start="8" data-line-end="9">
Запускает локальный эмулятор, создает скрытую development theme ссылки на превью темы в браузере и кастомайзер.
Аналог theme watch с той разницей, что файлы не заливаются в стор.
Из плюсов моментально обновляет страницу, без перезагрузки когда сохраняем файл.
Терминал не показывает какой файл обновился, но если есть ошибка выдаёт её.
<pre><code class="has-line-data" data-line-start="10" data-line-end="12">shopify theme serve</code></pre>
<hr>
</li>
<li class="has-line-data" data-line-start="8" data-line-end="9">
Пушит изменения в стор. Позволяет выбрать в какую тему, есть опции как именно зальёт.
<pre><code class="has-line-data" data-line-start="10" data-line-end="12">shopify theme push</code></pre>
<hr>
</li>
<li class="has-line-data" data-line-start="8" data-line-end="9">
Разлогиниваемся, заканчиваем работу со стором.
<pre><code class="has-line-data" data-line-start="10" data-line-end="12">shopify logout</code></pre>
<hr>
</li>
</ul>
