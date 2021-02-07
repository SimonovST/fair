Лендинг по продаже воздуха написанный во время уроков, для понимния того как оформлять простую страничку при помощи CSS.
Первоначальный формат создания HTML5 + CSS + библиотека JQuery.
Данный Лендинг смонтирован на Rails для сбора данных по заказам.
Лендинг не дописан, есть проблемы с Webpacker.
Суть ошибки:

```
Webpacker::Manifest::MissingEntryError in Orders#index

Showing /media/sf_rubytut2/ror/fair/app/views/layouts/application.html.erb where line #9 raised:

Webpacker can't find application in /media/sf_rubytut2/ror/fair/public/packs/manifest.json. Possible causes:
1. You want to set webpacker.yml value of compile to true for your environment
   unless you are using the `webpack -w` or the webpack-dev-server.
2. webpack has not yet re-run to reflect updates.
3. You have misconfigured Webpacker's config/webpacker.yml file.
4. Your webpack configuration is not creating a manifest.
Your manifest contains:
{
}

Extracted source (around line #9):

7
8     <%= stylesheet_link_tag 'application', media: 'all' %>
9     <%= javascript_pack_tag 'application' %>
10    <link rel="stylesheet" href="/../css/reset.css">
11    <link rel="stylesheet" href="/../css/text.css">
12    <link rel="stylesheet" href="/../css/grid.css">

Rails.root: /media/sf_rubytut2/ror/fair

```