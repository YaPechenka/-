# -.css {
  color: #010101cc;
}

.l-top_menu-v2 {
  position: sticky;
  top: 0;
}

.l-top_menu-v2 .active .submenu {
  max-height: calc(100vh - 46px);
  overflow: auto;
}

body:after {
  content: '';
  width: 100%;
  height: 100%;
  position: fixed;
  top: 0;
  left: 0;
  z-index: 0;
  background-repeat: no-repeat;
  background-position-x: center;
  background-attachment: fixed;
  -webkit-background-size: cover;
  -moz-background-size: cover;
  -o-background-size: cover;
  background-size: cover;
  background-attachment: fixed;
}

body {
  background-image: none;
  background-size: cover !important;
  background-repeat: no-repeat;
  background-position: center center !important;
  background-attachment: fixed;
}

html {
  height: 100%;
  min-height: 100%;
}

body {
  min-height: 100%;
}

body {
  color:  rgba(var(--light-color), var(--hundred));
}

.b-shiki_editor footer .about-bb_codes:hover:before {
  color:  rgba(var(--dark-color), var(--hundred));
}

/* цвет текста */
.b-input label {
  color:  rgba(var(--dark-color), var(--hundred));
  display: block;
  line-height: 1.65;
}

/* цвет вкладок под никнеймом */
.b-link {
  color:  rgba(var(--bright-color), var(--hundred)) !important;
  cursor: pointer;
}

.b-link:hover {
  color:  rgba(var(--hover-color), var(--hundred)) !important;
}

header.head .misc {
  max-width: 100%;
  width: 100%;
}

* .c-brief header.head h1 {
  border-bottom: none;
  color:  rgba(var(--white-color), var(--hundred)) !important;
  font-family: 'Comfortaa';
  text-shadow: 2px -2px 0px  rgba(var(--nick-cover), var(--hundred)), -2px 2px 0px  rgba(var(--nick-cover), var(--hundred)), -2px -2px 0px  rgba(var(--nick-cover), var(--hundred)), 2px 2px 0px  rgba(var(--nick-cover), var(--hundred)), 0px -2px 0px  rgba(var(--nick-cover), var(--hundred)), 0px 2px 0px  rgba(var(--nick-cover), var(--hundred)), 2px 0px 0px  rgba(var(--nick-cover), var(--hundred)), -2px 0px 0px  rgba(var(--nick-cover), var(--hundred));
  font-size: 34px;
  line-height: 38px;
  pointer-events: none;
}

/* цвет заголовков */
header.head h2, header.head h1 {
  border-bottom: none;
  color:  rgba(var(--white-color), var(--hundred)) !important;
  font-family: 'Comfortaa';
  display: block;
}

/* цвет описания аниме */
.b-prgrph, .b-spoiler_prgrph {
  color:  rgba(var(--light-color), var(--hundred));
}

/* цвет смотрю, планы и т.д. */
.b-db_entry-note .name-container .note .relation, .b-db_entry-note .name-container .note .additional {
  color:  rgba(var(--dark-color), var(--hundred)) !important;
}

/* кнопка смотреть онлайн */
.b-link_button.dark {
  background-color: rgba(var(--buttoms-color), 0.7);
  color:  rgba(var(--white-color), var(--hundred));
  transition: 0.2s ease;
  box-shadow: 0 2px 6px 2px rgba(0, 0, 0, 0.2);
  border-radius: 14px;
  border: none;
}

.b-link_button:hover, .b-link_button.dark:hover {
  background-color:  rgba(var(--hover-buttoms-2), var(--hundred));
  color: white !important;
  border: none;
}

.b-link_button {
  background-color: rgba(var(--buttoms-color), 0.7);
  border: none;
  color:  rgba(var(--white-color), var(--hundred)) !important;
  box-shadow: 0 2px 6px 2px rgba(0, 0, 0, 0.2);
}

/* инфо-описание */
.line .value {
  color:  rgba(var(--light-color), var(--hundred))!important;
}

/* инфо тег */
.line .key {
  color:  rgba(var(--dark-color), var(--hundred))!important;
  font-weight: bold;
}

textarea {
  border: none !important;
}

/* нет комментариев */
.b-nothing_here {
  color:  rgba(var(--dark-color), var(--hundred));
}

.buttons .cancel {
  margin-right: 10px !important;
  margin-left: 10px !important;
}

.b-form .cancel {
  background-color: rgba(var(--block-color), 0.4);
  border-radius: 6px;
  padding: 6px 10px 6px 10px;
}

.b-form .cancel:hover {
  background-color:  rgba(var(--hover-buttoms-2), var(--hundred));
  color:  rgba(var(--white-color), var(--hundred)) !important;
  box-shadow: none !important;
}

/* история-время */
.p-profiles .profile-head .c-history .entry .misc.date {
  color:  rgba(var(--dark-color), var(--hundred)) !important;
}

/* история-история */
.p-profiles .profile-head .c-history .entry .misc {
  color:  rgba(var(--bright-color), var(--hundred)) !important;
  text-overflow: clip !important;
  overflow: hidden;
  white-space: nowrap;
}

.b-add_to_list.completed .trigger, .b-add_to_list.completed .option {
  background: #1c4c20;
  border-color: rgba(var(--block-color), 0.4);
  color: #C4E9ED;
}

.b-add_to_list.dropped .trigger, .b-add_to_list.dropped .option {
  background: #77251c;
  border-color: rgba(var(--block-color), 0.4);
  color: #F2DDcc;
}

/* кнопка "Отложено" на страничке аниме*/
.b-add_to_list.on_hold .trigger, .b-add_to_list.on_hold .option {
  background: #864e13;
  border-color: rgba(var(--block-color), 0.4);
  color: #EBEEF1;
}

/* кнопка "Запланировано" на страничке аниме*/
.b-add_to_list.planned .trigger, .b-add_to_list.planned .option {
  background: #173969;
  border-color: rgba(var(--block-color), 0.4);
  color: #CFE0EC;
}

/* кнопка "Смотрю" на страничке аниме*/
.b-add_to_list.watching .trigger, .b-add_to_list.watching .option {
  background: #382f7b;
  border-color: rgba(var(--block-color), 0.4);
  color: #D8F8F6;
}

/* кнопка "Пересмотравиваю" на страничке аниме*/
.b-add_to_list.rewatching .trigger, .b-add_to_list.rewatching .option {
  background: #115652;
  border-color: rgba(var(--block-color), 0.4);
  color: #D8F8F6;
}

.b-add_to_list.planned.expanded .trigger, .b-add_to_list.planned .trigger, .b-add_to_list.completed.expanded .trigger, .b-add_to_list.completed .trigger, .b-add_to_list.dropped.expanded .trigger, .b-add_to_list.dropped .trigger, .b-add_to_list.on_hold.expanded .trigger, .b-add_to_list.on_hold .trigger, .b-add_to_list.watching.expanded .trigger, .b-add_to_list.watching .trigger, .b-add_to_list.rewatching.expanded .trigger, .b-add_to_list.rewatching .trigger {
  border: 2px solid #cfe0ec26;
  box-shadow: 0 2px 6px 2px rgba(0, 0, 0, 0.2) !important;
  border-radius: 6px;
}

/* надпись красным "Удалить из списка" */
.b-add_to_list .expanded-options .remove-trigger .text {
  color: #ffa09e;
}

.b-add_to_list .expanded-options {
  border-radius: 7px;
}

/* жанр, ссылка на него */
.tags .b-tag, .line .b-tag, .line .tag, .b-forums .reload, .p-animes-show .other-names, .p-mangas-show .other-names, .p-ranobe-show .other-names {
  padding: 1px 12px !important;
  margin: 2px !important;
  color:  rgba(var(--bright-color), var(--hundred)) !important;
  background: rgba(var(--block-color), 0.6) !important;
  transition: 0.3s ease !important;
  border: none !important;
  border-radius: 10px;
}

.tags .b-tag:hover, .line .b-tag:hover, .line .tag:hover, .b-forums .reload:hover, .p-animes-show .other-names:hover, .p-mangas-show .other-names:hover, .p-ranobe-show .other-names:hover, a.b-anime_status_tag.studio:hover {
  background-color:  rgba(var(--hover-buttoms-2), var(--hundred)) !important;
  color: white !important;
  box-shadow: 0 2px 6px 2px rgba(0, 0, 0, 0.2) !important;
  margin: 2px !important;
  border: none !important;
}

.block.genres .b-spoiler label, .b-show_more, .b-show_more-more .hide-more {
  padding: 2px 0px !important;
  color:  rgba(var(--bright-color), var(--hundred)) !important;
  background: rgba(var(--block-color), 0.6) !important;
  transition: 0.3s ease !important;
  border: none !important;
  border-radius: 10px;
  display: inline-block;
  width: 100%;
  text-align: center;
}

.block.genres .b-spoiler label:hover, .b-table .actions a:hover, .b-show_more:hover, .b-show_more-more .hide-more:hover {
  background-color: rgba(var(--hover-buttoms-2), 0.7) !important;
  color: white !important;
  box-shadow: 0 2px 6px 2px rgba(0, 0, 0, 0.2) !important;
  border: none !important;
  animation: none;
}

.block.genres .b-spoiler {
  border: none !important;
}

.b-table .actions a {
  padding: 4px 18px !important;
  color:  rgba(var(--bright-color), var(--hundred)) !important;
  background: rgba(var(--block-color), 0.6) !important;
  transition: 0.3s ease !important;
  border: none !important;
  border-radius: 10px;
  text-align: center;
}

.b-forums .reload {
  width: 100%;
  padding: 5px 12px !important;
  text-align: center;
  box-shadow: 0 2px 6px 2px rgba(0, 0, 0, 0.2) !important;
}

/* жанр, ссылка на него d ghjcjvnht hfcrhsdftittujcz fybv */
.p-user_rates-index .list-lines tr td .episodes_total:after, .p-user_rates-index .list-lines tr td .episodes_total:before {
  color:  rgba(var(--hover-color), var(--hundred));
}

.p-user_rates-index .l-content .b-options-floated span:before, .p-user_rates-index .l-content .b-options-floated span:after {
  color:  rgba(var(--dark-color), var(--hundred));
  font-size: 0px;
}

.p-user_rates-index .l-content .b-options-floated span:hover {
  color:  rgba(var(--hover-color), var(--hundred));
}

/* напрямую, хронология франшиза */
.b-options-floated a, .b-options-floated .link {
  font-size: 13px;
  color:  rgba(var(--bright-color), var(--hundred));
  padding: 0 8px 0 8px;
}

.b-options-floated.mobile-phone_portrait a {
  color:  rgba(var(--bright-color), var(--hundred));
}

.b-options-floated a:after, .b-options-floated .link:after {
  display: none;
}

/* цвет кликабельных текстов на блоках как Авторы, Избранное и т.д. */
/* Цвета шкал от темного до светлого - сверху вниз */
.bar.simple .bar.s3 {
  background:  rgba(var(--small-rating), var(--hundred));
  transition: 0.2s ease-out;
}

.bar.simple .bar.s2 {
  background:  rgba(var(--average-rating), var(--hundred));
  transition: 0.2s ease-out;
}

.bar.simple .bar.s1 {
  background:  rgba(var(--high-rating), var(--hundred));
  transition: 0.2s ease-out;
}

.bar.simple .bar.s0 {
  background:  rgba(var(--very-high-rating), var(--hundred));
  transition: 0.2s ease-out;
}

.bar.simple .bar {
  border-radius: 8px;
}

.bar.horizontal {
  padding: 0px 3px 0px 0px;
}

.activity .bar.simple .bar {
  border-radius: 8px 8px 0px 0px;
}

.bar.simple .bar.s3:hover, .bar.simple .bar.s2:hover, .bar.simple .bar.s1:hover, .bar.simple .bar.s0:hover {
  background:  rgba(var(--hover-color), var(--hundred));
}

/* цвет никнеймов */
.p-dashboards-show .v2 .db-update .name, .b-comment>.inner .name-date .name, .b-comment > .inner header .name-date a.name, .b-topic > .inner header .name-date a.name, .b-dialog > .inner header .name-date a.name, .b-message > .inner header .name-date a.name {
  font-size: 15.5px;
}

.b-comment > .inner .name-date .name:hover, .b-comment > .inner header .name-date a.name:hover, .b-dialog > .inner header .name-date a.name:hover, .b-topic > .inner header .name-date a.name:hover, .b-message > .inner header .name-date a.name:hover, .b-message > .inner header .name-date a.name:hover {
  color:  rgba(var(--hover-color), var(--hundred)) !important;
}

/* цвет кнопки троеточие у описания аниме */
.p-animes-show .other-names.click-loader span, .p-mangas-show .other-names.click-loader span, .p-ranobe-show .other-names.click-loader span {
  display: none;
}

.p-animes-show .other-names.click-loader, .p-mangas-show .other-names.click-loader, .p-ranobe-show .other-names.click-loader {
  background: none;
  color:  rgba(var(--bright-color), var(--hundred));
  border: none !important;
  margin-top: 0px;
  transition: 0.1s ease !important;
}

.p-animes-show .other-names.click-loader:hover, .p-mangas-show .other-names.click-loader:hover, .p-ranobe-show .other-names.click-loader:hover {
  background: none;
  color: white;
}

.p-animes-show .other-names.click-loader:before, .p-mangas-show .other-names.click-loader:before, .p-ranobe-show .other-names.click-loader:before {
  content: 'показать';
  font-size: 12px;
  display: block;
  box-shadow: 0 2px 6px 2px rgba(0, 0, 0, 0.2) !important;
  background: rgba(var(--block-color), 0.6);
  border-radius: 10px;
  padding: 2px 11px;
  transition: 0.1s ease !important;
}

.p-animes-show .other-names.click-loader:hover:before, .p-mangas-show .other-names.click-loader:hover:before, .p-ranobe-show .other-names.click-loader:hover:before {
  background-color:  rgba(var(--hover-buttoms-2), var(--hundred));
}

/* загрузить еще комментарии */
.b-comments .comments-loader, .b-comments .comments-hider, .b-comments .comments-expander, .b-comments .faye-loader, .collapsed, .b-forum .faye-loader, .b-topic .faye-loader, .collapsed + .spoiler .hide-expanded {
  background: rgba(var(--block-color), 0.4);
  color:  rgba(var(--dark-color), var(--hundred));
  border: none;
  transition: 0.3s ease;
  border-radius: 14px;
  box-shadow: 0 2px 6px 2px rgba(0, 0, 0, 0.05) !important;
}

/* когда наводишь на загрузку*/
.b-comments .comments-loader:hover, .b-comments .comments-hider:hover, .b-comments .comments-expander:hover, .b-comments .faye-loader:hover, .collapsed:hover, .b-forum .faye-loader:hover, .b-topic .faye-loader:hover, .collapsed + .spoiler .hide-expanded:hover {
  background: rgba(var(--hover-bottoms-1), 0.8) !important;
  color:  rgba(var(--white-color), var(--hundred)) !important;
  border: none;
  border-radius: 6px;
}

.b-comments .comments-loader:active, .b-comments .comments-hider:active, .b-comments .comments-expander:active {
  background: rgba(var(--block-color), 0.4);
  color:  rgba(var(--dark-color), var(--hundred));
  border: none;
}

/* цвет рейтенга текста */
.b-rate .score-notice {
  color:  rgba(var(--dark-color), var(--hundred));
}

.b-rate .text-score {
  color:  rgba(var(--light-color), var(--hundred));
}

/* цвет значка отзыв */
.locale-ru .b-summary_marker:before {
  background-color: #1A421D;
  border: rgba(var(--block-color), 0.4);
  color: #C4E9ED;
}

/* цвет значка оффтоп */
.locale-ru .b-offtopic_marker.off:before, .locale-ru .b-offtopic_marker.active.off:before {
  color: #F6E5EC;
  border-color: #54263A;
  background-color: #54263A;
}

.locale-ru .b-offtopic_marker.off:hover:before {
  border-color:  rgba(var(--hover-color), var(--hundred));
  background-color:  rgba(var(--hover-color), var(--hundred));
  color:  rgba(var(--white-color), var(--hundred));
}

.locale-ru .b-offtopic_marker.active:before {
  color: #F6E5EC;
  border-color: #7C3152;
  background-color: #7C3152;
}

.locale-ru .b-offtopic_marker.active:hover:before {
  border-color:  rgba(var(--hover-color), var(--hundred));
  background-color:  rgba(var(--hover-color), var(--hundred));
  color:  rgba(var(--white-color), var(--hundred));
}

.locale-ru .b-offtopic_marker:before {
  background-color: #C05986;
  border: 1px solid;
  border-color: #7876bf;
  color: #F6E5EC;
}

/* открываюшееся при наводке на героя окно */
.tooltip-inner {
  background: none repeat scroll 0 0  rgba(var(--popup-color), var(--hundred));
  border: none;
  color: black;
  box-shadow: 0 2px 6px 2px rgba(0, 0, 0, 0.3);
  border-radius: 6px;
}

/* цвета аниме шкалы */
.b-stats_bar .bar .third {
  background:  rgba(var(--time-empty), var(--hundred));
  opacity: 0.7;
}

.b-stats_bar.anime .bar .second {
  background:  rgba(var(--anime-inprocess), var(--hundred));
  opacity: 0.7;
}

.b-stats_bar.anime .bar .first {
  background:  rgba(var(--anime-complete), var(--hundred));
  opacity: 0.7;
}

/* цвета манга шкалы */
.b-stats_bar.manga .bar .first {
  background:  rgba(var(--manga-complete), var(--hundred));
  opacity: 0.7;
}

.b-stats_bar.manga .bar .second {
  background:  rgba(var(--manga-inprocess), var(--hundred));
  opacity: 0.7;
}

/* название аниме в списке моем */
.p-user_rates-index .list-lines tr .name a {
  color:  rgba(var(--white-color), var(--hundred));
}

.p-user_rates-index .list-lines tr .name a:hover, .b-user.detailed .history .line a .event:hover {
  background: none;
  box-shadow: none;
  color:  rgba(var(--hover-color), var(--hundred));
  text-decoration: none;
  border: none;
}

.p-user_rates-index .list-lines tr.editable {
  transition: 0.1s ease-out;
}

/* оценки справа в аниме */
.bar.horizontal .line .x_label {
  color:  rgba(var(--light-color), var(--hundred));
}

/* текст отзывы, комментарии и т.д. под вкладкой У аниме: */
.b-db_entry > .c-about .additional-links .line-container > .link, .b-db_entry > .c-about .additional-links .line-container > a {
  color:  rgba(var(--bright-color), var(--hundred));
}

.b-db_entry > .c-about .additional-links .line-container > .link:hover, .b-db_entry > .c-about .additional-links .line-container > a:hover {
  color:  rgba(var(--hover-color), var(--hundred));
}

/* закрашенные звезды */
.b-rate .stars.score {
  color:  rgba(var(--white-color), var(--hundred));
}

.l-top_menu-v2 .logo-container .logo {
  background: url(https://cdn1.savepice.ru/uploads/2020/1/5/3ac9bd0bb9cf45be1e80b08cc6e76042-full.png) no-repeat
  height: 32px;
  margin-top: 8px;
}

/* при наводке звезды */
.b-rate .stars.hover {
  color: #E7A61D;
}

/* пустые звезды */
.b-rate .stars.background {
  color: rgba(var(--block-color), 0.4);
}

/* список аниме и манги */
.b-stats_bar a.title {
  color:  rgba(var(--white-color), var(--hundred));
}

.b-stats_bar a.title:hover {
  color:  rgba(var(--hover-color), var(--hundred));
  box-shadow: none;
  background: none;
}

/* под списком кол-во просмотреных прочитанных и т.д. */
.b-stats_bar .stat_names .stat_name a, .b-stats_bar .stat_names .stat_name .size:before, .b-stats_bar .stat_names .stat_name .size:after {
  color:  rgba(var(--dark-color), var(--hundred));
}

/* под списком кол-во просмотреных прочитанных и т.д. */
.b-stats_bar .stat_names .stat_name a:hover {
  color:  rgba(var(--hover-color), var(--hundred));
}

.b-animes-menu .total-rates {
  color:  rgba(var(--dark-color), var(--hundred));
}

.p-profiles .profile-head .c-info .c-lists-info .b-stats_bar .compatibility a {
  color:  rgba(var(--bright-color), var(--hundred));
}

.p-profiles .profile-head .c-info .c-lists-info .b-stats_bar .compatibility a:hover {
  color:  rgba(var(--hover-color), var(--hundred));
}

.b-shiki_editor .body .editor textarea, .b-input input[disabled], .b-input input[type=submit], .b-input input[type=text], .b-input input[type=password], .b-input input[type=email], .b-input textarea[type=submit], .b-input textarea[type=text], .b-input textarea[type=password], .b-input textarea[type=email] {
  color:  rgba(var(--light-color), var(--hundred));
  border-radius: 10px;
  background-color: rgba(var(--block-color), 0.4) !important;
  border: none !important;
  font-family: 'Comfortaa';
  box-shadow: 0 2px 6px 2px rgba(0, 0, 0, 0.1) !important;
}

/* цвет кнопки написать */
.b-form input[type=submit], .b-shiki_editor.previewed footer .unpreview, .b-poll .poll-actions .vote, .b-poll .poll-actions .abstain, a.stop.b-button, .b-button, .b-form .cancel, .b-button.preview, a.start.b-button, .b-form input[type=submit][disabled], .b-form input[type=submit].disabled, .block.edit-page.pages a.cancel, .b-shiki_editor footer .hide {
  padding: 6px 11px;
  line-height: 1;
  font-family: 'Comfortaa';
  color:  rgba(var(--light-color), var(--hundred)) !important;
  background-color: rgba(var(--block-color), 0.4);
  border-radius: 11px !important;
  transition: 0.3s ease-out;
  border: none;
  box-shadow: 0 2px 6px 2px rgba(0, 0, 0, 0.2);
}

.b-form input[type=submit]:hover, .b-shiki_editor footer .preview:hover, .b-shiki_editor.previewed footer .unpreview:hover, .b-poll .poll-actions .vote:hover, .b-poll .poll-actions .abstain:hover, a.stop.b-button:hover, .b-button:hover, .b-form .cancel:hover, .b-button.preview:hover, a.start.b-button:hover, .b-form input[type=submit][disabled]:hover, .b-form input[type=submit].disabled:hover, .block.edit-page.pages a.cancel:hover, .b-shiki_editor footer .hide:hover {
  background-color: rgba(var(--hover-buttoms-2), 0.6);
  color: #e4e4e4 !important;
  box-shadow: 0 2px 6px 2px rgba(0, 0, 0, 0.3) !important;
  opacity: 1;
}

.b-shiki_editor footer input[type=submit], .b-shiki_editor footer .unpreview, .b-shiki_editor footer .preview, .b-shiki_editor footer .hide, .b-shiki_editor footer .cancel {
  margin: 0 20px 10px 0;
  box-shadow: 0 2px 6px 2px rgba(0, 0, 0, 0.3) !important;
}

.b-comments .comments-loader:hover, .b-comments .comments-hider:hover, .b-comments .comments-expander:hover {
  background-color: white;
  color: white;
}

/* полоса оттеняющая, если не развернуто */
.b-height_shortener .shade {
  background-image: none;
  height: 30px;
  z-index: 0;
}

/* слово развернуть */
.b-height_shortener .expand {
  color:  rgba(var(--bright-color), var(--hundred));
}

.b-height_shortener .expand:hover {
  color:  rgba(var(--hover-color), var(--hundred));
}

/* в списке аниме : планы смотрю и т.д. */
.b-options-floated.mobile-desktop a {
  color:  rgba(var(--dark-color), var(--hundred));
}

.b-options-floated.mobile-desktop a:hover {
  color:  rgba(var(--hover-color), var(--hundred));
}

/* под шкалой в профиле сколько пробыл на сайте */
.bar.vertical .line .x_label {
  color: #5B6AD7;
}

/* Поиск по названию в списке аниме */
input {
  color:  rgba(var(--light-color), var(--hundred));
  border: rgba(var(--block-color), 0.4);
  background: rgba(var(--block-color), 0.4);
}

/* свернуть списки в списке аниме */
.b-options-floated .action {
  color:  rgba(var(--bright-color), var(--hundred));
  border: none;
}

.b-options-floated .action:hover {
  color:  rgba(var(--hover-color), var(--hundred));
}

.b-list_switchers .switcher.lines:before:hover, .b-list_switchers .switcher.lines:hover {
  color:  rgba(var(--hover-color), var(--hundred));
}

.b-list_switchers .switcher.posters:before:hover {
  color:  rgba(var(--hover-color), var(--hundred));
}

.b-list_switchers .switcher.posters:after {
  cursor: pointer;
  display: inline-block;
  font-size: 12px;
  line-height: 20px;
  font-variant: normal;
  text-transform: none;
  color: white;
}

.p-user_rates-index .stat-categories .category {
  color:  rgba(var(--bright-color), var(--hundred));
  line-height: normal !important;
  margin: 0 0 0 2px;
  padding: 0px 7px;
  transition: 0.2s ease-out;
}

.p-user_rates-index .stat-categories .category:hover {
  color:  rgba(var(--hover-color), var(--hundred)) !important;
  transform: scale(1.1);
  box-shadow: none;
  background: none;
}

.p-user_rates-index .stat-categories .category.active {
  color:  rgba(var(--hover-color), var(--hundred));
}

/* справа выборы фильтров в списке аниме */
.b-block_list li {
  color:  rgba(var(--light-color), var(--hundred));
  transition: 0.1s ease-out;
  font-family: 'Comfortaa';
}

/* сводка по разным спискам  */
.p-user_rates-index .list-groups .summary.lines {
  color:  rgba(var(--dark-color), var(--hundred));
}

.item-add:before, .item-add:after {
  color:  rgba(var(--dark-color), var(--hundred));
}

.item-add:hover:before, .item-add:hover:after {
  color:  rgba(var(--hover-color), var(--hundred)) !important;
}

/* оценка, эпизоды и т.д. столбики */
.p-user_rates-index .l-content .order-control {
  color:  rgba(var(--dark-color), var(--hundred));
}

.p-user_rates-index .l-content .order-control:hover {
  color:  rgba(var(--hover-color), var(--hundred));
}

/* стрелка назад */
header.head h1 a.back:before, header.head h2 a.back:before {
  color:  rgba(var(--white-color), var(--hundred));
}

header.head a.misc:hover {
  color:  rgba(var(--hover-color), var(--hundred));
}

.b-options-floated .selected, .b-options-floated.mobile-phone_portrait a.selected {
  color:  rgba(var(--hover-color), var(--hundred));
  font-size: 13px;
}

.b-options-floated a:hover, .b-options-floated .link:hover {
  color:  rgba(var(--hover-color), var(--hundred));
}

/* цвет тегов в настройки -уведомления*/
.b-table th {
  color:  rgba(var(--white-color), var(--hundred));
}

a {
  color:  rgba(var(--white-color), var(--hundred));
  transition: 0.3s ease;
}

a:hover {
  color:  rgba(var(--hover-color), var(--hundred)) !important;
  text-decoration: none !important;
}

a.name:hover {
  color:  rgba(var(--hover-color), var(--hundred)) !important;
  text-decoration: none !important;
  background: none !important;
  box-shadow: none !important;
}

.b-comment > .inner div.body, .b-message > .inner div.body {
  color:  rgba(var(--light-color), var(--hundred));
  font-size: 13px !important;
}

.b-mention {
  color:  rgba(var(--white-color), var(--hundred));
}

/* название в новостях */
.b-message > .inner header .name-date a.name {
  color:  rgba(var(--white-color), var(--hundred));
}

.b-message > .inner header .name-date {
  line-height: 24px;
  overflow: visible;
  white-space: normal;
}

.p-user_rates-index .list-lines .selectable:hover, .p-userlist_comparer .comparer table .selectable:hover {
  color:  rgba(var(--hover-color), var(--hundred)) !important;
  transform: scale(1.01);
  background: transparent;
}

tr.user_rate.selectable.editable:hover:after {
  background: rgba(var(--shadows-color), 0.15);
  border-radius: 10px;
  box-shadow: 0 2px 6px 2px rgba(0, 0, 0, 0.2) !important;
  transform: scale(1.01);
}

tr.user_rate.selectable.editable:after {
  content: '';
  width: 100%;
  height: 22px;
  padding-top: 2px;
  position: absolute;
  left: 0px;
  top: -2px;
  z-index: -1;
}

.p-user_rates-index .list-lines .selectable, .p-userlist_comparer .comparer table .selectable {
  transition: 0.15s ease;
}

.p-userlist_comparer .comparer table .exact-same, .p-userlist_comparer .legend .exact-same {
  background-color: rgba(0, 160, 35, 0.4);
  border-radius: 4px;
}

.p-userlist_comparer .comparer table .almost-same, .p-userlist_comparer .legend .almost-same {
  background-color: rgba(0, 86, 20, 0.4);
  border-radius: 4px;
}

.p-userlist_comparer .comparer table .slightly-difr, .p-userlist_comparer .legend .slightly-difr {
  background-color: rgba(160, 0, 0, 0.4);
  border-radius: 4px;
}

.p-userlist_comparer .comparer table .abslt-difr, .p-userlist_comparer .legend .abslt-difr {
  background-color: rgba(117, 21, 1, 0.4);
  border-radius: 4px;
}

.b-message > .inner header .name-date a.name:hover {
  color:  rgba(var(--hover-color), var(--hundred));
}

/* знак в новостях эпизод*/
.b-anime_status_tag.episode:before {
  background: #3d249e;
  color: #e9f1f3;
}

.b-js-link {
  color:  rgba(var(--bright-color), var(--hundred));
  border: none;
  padding: 0 8px 0 8px;
  transition: 0.2s ease;
}

.b-js-link:hover {
  color:  rgba(var(--hover-color), var(--hundred));
  border: none;
}

.p-messages .mass-actions .action:after {
  display: none;
}

.c-brief header.head .notice, .c-brief header.head .misc, .c-brief header.head a.edit, .p-profiles .profile-head .c-info .c-additionals b, .p-profiles .profile-head .c-brief header h1.aliases::after, .p-profiles .profile-head .c-brief header .notice a {
  color:  rgba(var(--light-color), var(--hundred)) !important;
  transition: 0.3s ease;
}

.p-profiles .profile-head .c-brief header .notice span:after {
  color:  rgba(var(--light-color), var(--hundred));
}

.b-tooltipped.dotted {
  border: none;
}

.p-profiles .profile-head .c-info .c-additionals div a:hover {
  color:  rgba(var(--hover-color), var(--hundred)) !important;
  transform: scale(1.1) !important;
}

.b-spoiler label {
  color:  rgba(var(--light-color), var(--hundred));
  border: 2px dashed rgba(165, 170, 230, 0.2);
  border-radius: 6px;
  padding: 0px 6px;
  transition: 0.3s ease;
}

.b-spoiler {
  transition: 0.5s ease;
}

.b-spoiler label:hover {
  color:  rgba(var(--hover-color), var(--hundred));
  animation: spoilzero 2s ease infinite;
}

.b-spoiler .b-poll label {
  border: none;
}

.b-input input, .b-input textarea {
  background: rgba(var(--block-color), 0.4);
  color:  rgba(var(--light-color), var(--hundred));
  border: none !important;
  box-shadow: 0 2px 6px 2px rgba(0, 0, 0, 0.07) !important;
}

.p-user_rates-index .list-lines tr.edit-form form {
  background-color: rgba(var(--menu-back), 0.8);
  border: none;
  box-shadow: 2px 2px 8px 1px rgba(0, 0, 0, 0.2);
  border-radius: 10px;
}

input, select, button, textarea {
  background-color: rgba(var(--block-color), 0.4);
  font-family: 'Comfortaa';
  border: none !important;
}

/* стоп */
.b-quote {
  background: rgba(var(--block-color), 0.4) !important;
  border: none !important;
  color:  rgba(var(--light-color), var(--hundred));
  box-shadow: 0 2px 6px 2px rgba(0, 0, 0, 0.07) !important;
  border-radius: 6px !important;
  font-style: normal;
}

.b-comments .comments-collapser, .b-spoiler .content .after:before {
  color:  rgba(var(--bright-color), var(--hundred));
}

.p-dashboards-show .v2 .db-update .name:hover, .b-comment>.inner .name-date .name:hover, .b-comments .comments-collapser:hover, .b-topic > .inner header .name-date a.name:hover, .p-user_rates-index .list-lines tr td .episodes_total {
  color:  rgba(var(--hover-color), var(--hundred));
}

.p-dashboards-show .v2 .db-update .name, .b-comment>.inner .name-date .name, .b-topic > .inner header .name-date a.name, .b-dialog > .inner header .name-date a.name, .b-message > .inner header .name-date a.name {
  color:  rgba(var(--white-color), var(--hundred));
  top: 2px;
  position: relative;
  padding-top: 2px;
}
.p-dashboards-show .v2 .db-updates {
    overflow: visible;
}
.b-dialog > .inner div.body {
  color:  rgba(var(--light-color), var(--hundred));
}

.b-dialog, .p-dashboards-show .cc-news .c-news_topics .b-topic, b-user.detailed, .b-comment, .b-db_entry-note, .p-topics .l-menu .sticky-topics .topic, .b-comments .comments-loaded, .b-message .comments-loaded, .b-user.detailed {
  border-bottom: 1px solid rgba(var(--light-color), 0.1) !important;
}

.b-dialog, .p-dashboards-show .cc-news .c-news_topics .b-topic, b-user.detailed, .b-comment, .b-db_entry-note, .p-topics .l-menu .clubs .entry, .p-topics .l-menu .sticky-topics .topic {
  margin: 4px 0px;
  border-top: none;
  padding-top: 10px;
  padding-bottom: 10px;
}

.b-comments .comments-loaded, .b-message .comments-loaded {
  padding-bottom: 10px !important;
}

.b-dialog:first-child {
  padding-top: 15px;
}

.b-show_more-more .b-db_entry-note:first-child, .cc .b-db_entry-note:last-child, .block_m .b-db_entry-note:last-child, .b-comments .b-comment:last-child {
  border-bottom: none !important;
  padding-bottom: 0px;
}

.p-dashboards-show .cc-news .c-news_topics .b-topic {
  margin-bottom: 0px !important;
  margin: 10px 0px !important;
}

.b-user.named_avatar .name {
  color:  rgba(var(--white-color), var(--hundred));
  transition: 1s ease-out;
  text-decoration: none !important;
  margin: auto;
}

.b-user.named_avatar:hover .name {
  color:  rgba(var(--hover-color), var(--hundred));
  text-decoration: none !important;
}

.b-user.named_avatar img:hover, .b-user.named_avatar .avatar:hover {
  border-color:  rgba(var(--hover-color), var(--hundred));
  border-radius: 50%;
  text-decoration: none !important;
}

.b-clubs-menu .admin .b-user {
  transition: 1s ease-out;
  text-decoration: none !important;
}

.b-clubs-menu .admin .b-user:hover {
  transform: scale(1.2);
  border-color:  rgba(var(--hover-color), var(--hundred));
  color:  rgba(var(--hover-color), var(--hundred));
  text-decoration: none !important;
}

.b-block_list li a {
  color:  rgba(var(--dark-color), var(--hundred));
}

.b-shiki_editor footer .about-bb_codes {
  color:  rgba(var(--dark-color), var(--hundred));
}

.b-lang_trigger span {
  color:  rgba(var(--dark-color), var(--hundred));
}

.b-user16 {
  color:  rgba(var(--white-color), var(--hundred));
  font-weight: bold;
}

.b-user16:hover, .b-user.named_avatar img:hover, .b-user16:hover a {
  color:  rgba(var(--hover-color), var(--hundred)) !important;
}

.b-comment > .inner header .name-date .time {
  color:  rgba(var(--bright-color), var(--hundred));
}

.c-actions .new_comment:before {
  transition: 0.3s ease;
  color:  rgba(var(--bright-color), var(--hundred));
}

.c-actions .new_comment:hover:before, .c-actions .fav-remove:before {
  color:  rgba(var(--hover-color), var(--hundred));
}

.c-actions .new_review:before {
  transition: 0.3s ease;
  color:  rgba(var(--bright-color), var(--hundred));
}

.c-actions .new_review:hover:before {
  color:  rgba(var(--hover-color), var(--hundred));
}

.c-actions .fav-add:before {
  color:  rgba(var(--bright-color), var(--hundred));
  transition: 0.3s ease;
}

.c-actions .fav-add:hover:before {
  color:  rgba(var(--hover-color), var(--hundred));
}

.c-actions .edit:before {
  transition: 0.3s ease;
  color:  rgba(var(--bright-color), var(--hundred));
}

.c-actions .edit:hover:before {
  color:  rgba(var(--hover-color), var(--hundred));
}

.b-video_variant .episode-num, .b-video_variant .video-id {
  color:  rgba(var(--light-color), var(--hundred));
}

.b-video_variant a {
  color:  rgba(var(--dark-color), var(--hundred));
}

.b-video_variant .episode-hostings, .b-video_variant .video-hosting, .b-video_variant .video-language {
  color:  rgba(var(--dark-color), var(--hundred));
}

.b-video_variant.active a {
  color: #1F75FE;
  border-bottom: none;
}

.b-video_variant.active a:hover {
  border-bottom: none;
}

.p-anime_videos-index .c-anime_video_episodes .title, .p-anime_videos-index .c-videos .title {
  color:  rgba(var(--white-color), var(--hundred));
  font-size: 11px;
}

.p-anime_videos-index .c-videos .video-variant-switcher {
  color:  rgba(var(--bright-color), var(--hundred));
}

.p-anime_videos-index .c-videos .video-variant-switcher.active {
  color: #1F75FE;
}

.b-video_variant .video-author {
  color:  rgba(var(--white-color), var(--hundred));
}

.b-video_player .cc-player_controls .prev .icon:before {
  color:  rgba(var(--white-color), var(--hundred));
}

.b-video_player .cc-player_controls .episode-num {
  color:  rgba(var(--white-color), var(--hundred)) !important;
}

.b-video_player .cc-player_controls .next .icon:before {
  color:  rgba(var(--white-color), var(--hundred));
}

.b-video_player .cc-player_controls .increment-user_rate .icon:before {
  color:  rgba(var(--white-color), var(--hundred));
}

.b-video_player .cc-player_controls .show-options .icon:before {
  color:  rgba(var(--white-color), var(--hundred));
}

.b-video_player .cc-player_controls .report .icon:before {
  color:  rgba(var(--white-color), var(--hundred));
}

.b-catalog_entry .cover .misc, .p-dashboards-show .midheadline .b-link, .p-dashboards .user_list .list-type > .title .switch, .p-dashboards .user_list .list-type > .title .link, .p-dashboards .user_list .history > .title .switch, .p-dashboards .user_list .history > .title .link, .p-dashboards .user_list .list-change .note, .p-dashboards .c-my_list .list-change .note, .bar.vertical .line .x_label, .p-dashboards-show .contests .contest .notice, .b-forums .forum .topics, .name-date .time, .p-profiles .profile-head .c-history .entry .misc, .p-profiles-show .lifetime .times .time, .p-profiles .profile-head .c-info .c-lists-info .b-stats_bar .compatibility span.link-replacement, .b-comment > .inner header .name-date .time, .b-replies, .b-options-floated, .p-messages .mass-actions .action, .p-animes_collection-index .pagination, .p-mangas_collection-index .pagination, .p-recommendations-index .pagination, .p-userlist_comparer-show .pagination, .b-rate .score-notice, .b-animes-menu .block-list .date, .bar.horizontal .line .x_label, .b-animes-menu .friend-rate .status, .b-summary_marker::before, .b-offtopic_marker::before, .tipsy, header.head .misc, header.head a.edit, .p-studios .studio .animes, .p-studios .studio .years, .p-contests .contest-match .vs .help, .p-contests .contest-match .vs .next, .p-contests .contest-match .vs .finish, .p-contests .contest-match .vs .refrain, .p-contests .contest-match .vs .refrained, .p-contests .match-day .matches-num, .b-lang_trigger, .b-club .info, .b-new_marker::before, .b-user.detailed .info .last-online, .b-user.detailed .history .line .date, .p-recommendations-index .b-header_filters .hint, .p-recommendations-favourites .b-header_filters .hint, .p-userlist_comparer .comparer table .notice, .p-topics .l-menu .calendar .entry .misc, .p-topics .l-menu .reviews .entry .misc, .p-topics .l-menu .clubs .entry .misc, .p-topics .l-menu .contests .contest .notice, .p-topics .l-menu .sticked-topics .topic .notice, .b-video_player .cc-player_controls .label, .b-video_player .cc-player_controls .episode-title .video-link, .b-log_entry .date, .b-log_entry .spoiler.collapse, .b-log_entry .spoiler.collapsed, .b-log_entry .spoiler.collapse span, .b-log_entry .spoiler.collapsed span, .b-js-action, .b-input .hint, .b-review-topic .review-votes_count, .p-dashboard .l-menu .ongoing .misc, .p-dashboard .l-menu .season .notice, .p-topics .l-menu .sticky-topics .topic .notice, .b-hot_topics .topic {
  font-size: 12px !important;
  color:  rgba(var(--dark-color), var(--hundred));
}

.bar.vertical .line .bar-container .value {
  color: #fff;
}

.b-show_more, .b-show_more-more .hide-more {
  color:  rgba(var(--bright-color), var(--hundred));
  font-size: 12px !important;
}

.p-profiles .profile-head .c-info .c-lists-info .b-stats_bar .compatibility a {
  font-size: 12px;
}

.b-dialog .to_dialog {
  font-size: 12px !important;
  background: none !important;
  box-shadow: none !important;
  color:  rgba(var(--bright-color), var(--hundred));
}

.b-forums .forum .link-with-input .link {
  color:  rgba(var(--white-color), var(--hundred));
}

.p-dashboards-show .c-content .options .option {
  color:  rgba(var(--bright-color), var(--hundred));
  border: none !important;
}

.p-dashboards-show .c-content .options .option.selected {
  color:  rgba(var(--hover-color), var(--hundred)) !important;
}

.p-dashboards-show .c-content .options .option:hover {
  color:  rgba(var(--hover-color), var(--hundred));
}

.p-dashboards-show .c-content .options .option.active {
  color:  rgba(var(--hover-color), var(--hundred));
}

.b-message {
  margin: 10px 0px;
  border-top: none;
  padding-bottom: 15px;
  border-bottom: 1px solid rgba(var(--light-color), 0.1);
}

.b-message:last-child {
  border-bottom: none;
  padding-bottom: 0px;
}

.b-catalog-entry-embedded .b-catalog_entry {
  padding-bottom: 0px !important;
  background: none;
}

.b-dialog .b-message {
  padding-bottom: 0px;
  margin-bottom: 0px !important;
  margin-top: 0px;
}

.p-user_history-index .history-page .history-interval p .destroy, .buttons .item-reply, .buttons .item-moderation, .buttons .item-edit, .buttons .item-delete, .buttons .item-ignore, .buttons .item-apply, .buttons .item-request-confirm, .buttons .item-delete-confirm, .buttons .item-cancel, .buttons .item-request-reject, .buttons .item-delete-cancel, .buttons .item-moderation-cancel {
  color:  rgba(var(--bright-color), var(--hundred));
}

.buttons .item-reply:before, .buttons .item-moderation:before, .buttons .item-edit:before, .buttons .item-delete:before, .buttons .item-ignore:before, .buttons .item-apply:before, .buttons .item-request-confirm:before, .buttons .item-delete-confirm:before, .buttons .item-cancel:before, .buttons .item-request-reject:before, .buttons .item-delete-cancel:before, .buttons .item-moderation-cancel:before {
  font-size: 16px !important;
}

.buttons .item-ignore:hover, .buttons .item-delete:hover, .buttons .item-edit:hover, .buttons .item-reply:hover, .buttons .item-moderation:hover, .buttons .item-apply:hover, .buttons .item-request-confirm:hover, .buttons .item-delete-confirm:hover, .buttons .item-cancel:hover, .buttons .item-request-reject:hover, .buttons .item-delete-cancel:hover, .buttons .item-moderation-cancel:hover, .buttons .item-delete-confirm:hover {
  color:  rgba(var(--hover-color), var(--hundred)) !important;
}

.p-topics header h1 a.reload {
  color:  rgba(var(--white-color), var(--hundred));
}

.p-anime_videos-index .c-videos .b-video_variant .video-quality.dvd {
  background: url(https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTG-2yy4R8Xi5mO1N_ZurIpznxCgpOuDzpRZGu-K9dUBwrClokYAg) no-repeat !important;
  display: none;
}

.b-video_player .cc-player_controls .episode-num .video-link a {
  color:  rgba(var(--dark-color), var(--hundred));
  cursor: pointer;
  border-bottom: 1px dotted  rgba(var(--dark-color), var(--hundred));
}

.b-video_player .cc-player_controls .create-user_rate .icon:before {
  color:  rgba(var(--white-color), var(--hundred));
}

.b-spoiler .content .before:before {
  content: '[spoiler]';
  color:  rgba(var(--bright-color), var(--hundred));
  animation: spoil 2s ease infinite;
}

.b-spoiler .content .after:before {
  animation: spoil 2s ease infinite;
}

.b-spoiler .content .inner, .b-spoiler .content .inner-prgrph {
  border-bottom: 0;
  border-radius: 6px;
  padding: 0px 6px;
  text-shadow: 0px 0px 8px rgba(255, 255, 255, 0.3);
}

.b-video_player .cc-player_controls .episode-num .video-link a {
  border: none;
}

.b-video_player .cc-player_controls .episode-num .video-link a:hover {
  background: none !important;
  color:  rgba(var(--white-color), var(--hundred));
  border: none;
  box-shadow: none !important;
}

.b-video_player .cc-player_controls .episode-num input {
  background: transparent !important;
  border-color: transparent !important;
}

.b-tag {
  border-bottom: 1px dashed  rgba(var(--bright-color), var(--hundred));
  color:  rgba(var(--bright-color), var(--hundred));
}

.b-source .contributors .key {
  color:  rgba(var(--dark-color), var(--hundred));
}

.b-animes-menu .menu-topics-block a.entry .name:hover {
  color:  rgba(var(--hover-color), var(--hundred));
  text-decoration: none;
}

.b-animes-menu .menu-topics-block a.entry .name {
  color:  rgba(var(--white-color), var(--hundred));
}

.b-animes-menu .menu-topics-block a.entry .date {
  color:  rgba(var(--dark-color), var(--hundred));
}

.p-contests .results .cc-result .c-rounds .label {
  color:  rgba(var(--bright-color), var(--hundred));
}

.b-db_entry > .c-about .additional-links .key {
  float: left;
  color:  rgba(var(--dark-color), var(--hundred));
}

.p-contests .results a {
  color:  rgba(var(--dark-color), var(--hundred));
}

header.head .notice {
  color:  rgba(var(--dark-color), var(--hundred));
}

.p-animes_collection-index .pagination .link {
  color:  rgba(var(--bright-color), var(--hundred));
}

.p-animes_collection-index .pagination .link.disabled {
  color:  rgba(var(--light-color), var(--hundred));
}

.linkheadline.midheadline > a:hover {
  color:  rgba(var(--hover-color), var(--hundred));
}

.b-topic-minified > .inner .status-line .additional .comments:before {
  color:  rgba(var(--bright-color), var(--hundred));
}

.b-topic {
  border: none !important;
}

.p-dashboards-show .cc-news .c-generated_news .b-topic {
  border: 1px;
}

.p-contests-index .contest a {
  color:  rgba(var(--white-color), var(--hundred));
}

.p-contests-index .contest a:hover {
  color:  rgba(var(--hover-color), var(--hundred));
}

.b-forums .forum .link-with-input .link:hover {
  color:  rgba(var(--hover-color), var(--hundred));
}

.b-topic-minified > .inner .status-line .additional {
  border: none !important;
}

.b-topic-minified > .inner .status-line .time.changed_at {
  border: 1px;
}

.b-topic > .inner header .name-date .time {
  color:  rgba(var(--dark-color), var(--hundred));
}

.p-topics .l-menu .reviews .entry .misc {
  color:  rgba(var(--bright-color), var(--hundred)) !important;
}

.b-collection_search .field input {
  border: 0px solid rgba(172, 177, 180, 0.13);
  background-color: rgba(var(--block-color), 0.4) !important;
  border-color: rgba(var(--block-color), 0.4);
}

.p-topics header h1 a.reload:hover {
  color:  rgba(var(--hover-color), var(--hundred));
}

.p-topics .l-menu .reviews .entry {
  border: none !important;
}

.p-topics .l-menu .reviews .entry .misc.date {
  color:  rgba(var(--dark-color), var(--hundred)) !important;
}

.midheadline > a:hover {
  color:  rgba(var(--hover-color), var(--hundred));
}

.p-topics .l-menu .reviews .entry .title, .p-topics .l-menu .clubs .entry .title {
  color:  rgba(var(--white-color), var(--hundred));
  text-decoration: none !important;
}

.p-topics .l-menu .reviews .entry .title:hover, .p-topics .l-menu .clubs .entry:hover .title {
  color:  rgba(var(--hover-color), var(--hundred)) !important;
  text-decoration: none !important;
}

.p-topics .l-menu .clubs .entry .misc {
  color:  rgba(var(--dark-color), var(--hundred)) !important;
}

.p-topics .l-menu .sticky-topics .topic .title:hover {
  color:  rgba(var(--hover-color), var(--hundred));
}

.b-club .name {
  color:  rgba(var(--white-color), var(--hundred));
}

.b-club .info .number {
  color:  rgba(var(--dark-color), var(--hundred));
  padding-right: 4px;
}

.b-club .info .value {
  color:  rgba(var(--dark-color), var(--hundred));
}

header.head a.misc {
  font-family: 'Comfortaa';
  font-size: 12px !important;
  margin-bottom: 5px;
  background: rgba(var(--block-color), 0.4);
  padding: 5px 50px;
  border-radius: 14px;
  color:  rgba(var(--light-color), var(--hundred));
  transition: 0.3s ease-out;
  margin: 8px;
  pointer-events: auto;
  box-shadow: 0 2px 6px 2px rgba(0, 0, 0, 0.2) !important;
  display: block;
  width: max-content;
  text-transform: capitalize;
}

header.head a.misc:hover {
  background-color: rgba(var(--hover-buttoms-2), 0.6);
  color: #e4e4e4 !important;
  box-shadow: 0 2px 6px 2px rgba(0, 0, 0, 0.2) !important;
}

/* надпись коллекция на зеленом */
.b-anime_status_tag.collection:before {
  background-color: #265E2B;
  border: 1px solid #122113;
}

.b-collection-topic > .inner .status-line .collection-size, .b-topic-minified > .inner .status-line .additional .comments:before, .b-review_votes:before, .b-topic-minified > .inner .status-line .time.changed_at:before, .b-topic-preview > .inner .status-line .additional .comments {
  color:  rgba(var(--dark-color), var(--hundred));
}

.b-topic .footer-vote {
  border: none;
  background-color: rgba(var(--block-color), 0.4);
  padding: 5px 10px 5px 10px;
  color:  rgba(var(--light-color), var(--hundred));
  border-radius: 10%;
}

.b-topic .footer-vote .vote-group .vote {
  color:  rgba(var(--light-color), var(--hundred));
}

.b-topic .footer-vote .vote-group .vote.yes.selected, .b-topic .footer-vote .vote-group .vote.yes:hover, .b-topic .footer-vote .vote-group .vote, .b-topic .footer-vote .vote-group .vote:hover, .b-topic .footer-vote .vote-group .vote.no.selected, .b-topic .footer-vote .vote-group .vote.no:hover {
  border: none;
}

.buttons .editor-italic:before, .buttons .editor-spoiler:before, .buttons .editor-smiley:before, .buttons .editor-quote:before, .buttons .editor-image:before, .buttons .editor-link:before, .buttons .editor-strike:before, .buttons .editor-underline:before, .buttons .editor-bold:before {
  font-family: 'shikimori';
  text-align: center;
  width: 20px;
  color:  rgba(var(--bright-color), var(--hundred));
  font-size: 14px;
  border: none !important;
}

.buttons .editor-italic, .buttons .editor-spoiler, .buttons .editor-smiley,
.buttons .editor-quote, .buttons .editor-image, .buttons .editor-link, .buttons .editor-strike, .buttons .editor-underline, .buttons .editor-bold, .buttons .editor-file {
  border: none !important;
}

.buttons .editor-file input:before {
  color:  rgba(var(--bright-color), var(--hundred));
}

.b-stats_bar .title, .p-profiles-show .profile-content .activity .title {
  color:  rgba(var(--dark-color), var(--hundred));
}

.b-tooltipped:not(a) {
  border: none;
}

.p-profiles-show .lifetime .times .time.checked {
  color:  rgba(var(--dark-color), var(--hundred));
  font-weight: bold;
  white-space: normal;
  min-width: 50px;
  line-height: 20px;
}

.p-profiles-show .lifetime .times .time {
  white-space: normal;
  min-width: 50px;
  line-height: 20px;
}

.p-profiles-edit .account .change-password a {
  color:  rgba(var(--bright-color), var(--hundred)) !important;
}

.p-profiles-edit .account .change-password a:hover {
  color:  rgba(var(--hover-color), var(--hundred));
}

.p-profiles-edit .list .profile-action a:not(.b-button) {
  padding: 0 8px;
  color:  rgba(var(--bright-color), var(--hundred)) !important;
}

.p-profiles-edit .list .profile-action a:not(.b-button):hover {
  color:  rgba(var(--hover-color), var(--hundred)) !important;
  box-shadow: none !important;
  background: none !important;
}

time {
    color: rgba(var(--dark-color), var(--hundred)) !important;
}

.subheadline .misc-link {
  color:  rgba(var(--dark-color), var(--hundred));
}

.subheadline .misc-link:hover {
  transform: scale(1) !important;
  background: none !important;
  box-shadow: none !important;
  font-size: 12px !important;
}

.buttons .main-controls a {
  color:  rgba(var(--bright-color), var(--hundred));
}

.buttons .main-controls a:hover {
  color:  rgba(var(--hover-color), var(--hundred));
}

.p-profiles-show .about a {
  color:  rgba(var(--bright-color), var(--hundred));
}

.p-profiles-show .about a:hover {
  color:  rgba(var(--hover-color), var(--hundred));
}

.b-options-floated .selected:hover, .b-options-floated.mobile-phone a.selected:hover, .b-options-floated.mobile-phone a.selected {
  color:  rgba(var(--hover-color), var(--hundred));
}

.b-options-floated.mobile-phone a {
  color:  rgba(var(--bright-color), var(--hundred));
}

.p-user_history-index .history-page .history-interval p a:hover {
  color:  rgba(var(--hover-color), var(--hundred)) !important;
  font-weight: bold;
}

.p-user_history-index .history-page .history-interval p a {
  color:  rgba(var(--white-color), var(--hundred));
  font-weight: bold;
}

body.localized_names-ru .name-ru:hover {
  color:  rgba(var(--hover-color), var(--hundred)) !important;
  text-decoration: none !important;
}

.p-user_history-index .history-page .history-interval p .date {
  color:  rgba(var(--dark-color), var(--hundred)) !important;
}

.p-user_rates-index .list-lines tr td .new-value input {
  border-radius: 4px;
  border: none;
  background: rgba(18, 18, 35, 0.4);
}

p-userlist_comparer .comparer table a {
  color:  rgba(var(--white-color), var(--hundred)) !important;
}

.p-userlist_comparer .comparer table .name a {
  color:  rgba(var(--white-color), var(--hundred));
}

.p-userlist_comparer .comparer table .name a:hover {
  color:  rgba(var(--hover-color), var(--hundred)) !important;
}

.b-table tr.border {
  border-top: none;
}

.p-user_rates-index .list-lines tr .index {
  color:  rgba(var(--light-color), var(--hundred)) !important;
}

.b-shiki_editor .body .preview {
  background: rgba(var(--block-color), 0.4);
  border: none !important;
}

.b-shiki_editor footer .unpreview:not(.link) {
  color:  rgba(var(--light-color), var(--hundred));
}

.b-shiki_editor footer .preview, .b-shiki_editor footer .cancel {
  color:  rgba(var(--light-color), var(--hundred)) !important;
}

.b-shiki_editor footer .cancel {
  border: none !important;
}

.p-profiles .profile-head .c-info .c-additionals div a {
  font-size: 12px !important;
}

.b-code {
  background: rgba(103, 103, 103, 0.2);
  border-radius: 6px;
}

.b-code:before {
  background-color: rgba(var(--bright-color), 0.3);
  border-radius: 6px;
}

.tooltip-inner .close {
  color:  rgba(var(--bright-color), var(--hundred));
  background: none;
}

.tooltip-inner .close:hover {
  background: none;
  color: #ddd;
}

.b-options-floated a span.brackets:after, .b-options-floated .link span.brackets:after {
  color:  rgba(var(--dark-color), var(--hundred));
  content: ')';
}

.b-options-floated a span.brackets:before, .b-options-floated .link span.brackets:before {
  color:  rgba(var(--dark-color), var(--hundred));
  content: '(';
}

.b-options-floated a:after, .b-options-floated .link:after {
  color:  rgba(var(--dark-color), var(--hundred));
  content: '/';
}

.p-anime_videos-index .c-video_stats .views_count {
  color:  rgba(var(--dark-color), var(--hundred));
}

.b-video_variant .episode-hostings:before, .b-video_variant .episode-hostings:after, .b-video_variant .video-hosting:before, .b-video_variant .video-hosting:after, .b-video_variant .video-language:before, .b-video_variant .video-language:after {
  color:  rgba(var(--dark-color), var(--hundred));
}

.b-video_player .cc-player_controls .upload .icon:before {
  color:  rgba(var(--white-color), var(--hundred));
}

.b-video_player .cc-player_controls .edit .icon:before {
  color:  rgba(var(--white-color), var(--hundred));
}

.p-anime_videos-index .same-videos .title {
  color:  rgba(var(--white-color), var(--hundred));
}

.b-comment .inner .name-date a.name .normal {
  color:  rgba(var(--light-color), var(--hundred));
}

.b-log_entry a, .b-log_entry .link {
  color:  rgba(var(--white-color), var(--hundred));
}

.b-log_entry a:hover, .b-log_entry .link:hover {
  color:  rgba(var(--hover-color), var(--hundred));
}

.b-log_entry .id-label {
  padding-right: 1px;
  color:  rgba(var(--white-color), var(--hundred));
}

.b-log_entry .id-label:hover {
  color:  rgba(var(--hover-color), var(--hundred));
}

.b-log_entry .change-details .field-changes .label {
  color:  rgba(var(--dark-color), var(--hundred));
}

.b-log_entry .spoiler.collapsed span:hover {
  color:  rgba(var(--hover-color), var(--hundred));
}

.b-shiki_editor footer .about-bb_codes:hover {
  color:  rgba(var(--hover-color), var(--hundred));
}

.b-bb_codes-examples .example .title, .b-bb_codes-examples .result .title {
  color:  rgba(var(--dark-color), var(--hundred));
}

.b-bb_codes-examples .notice {
  color:  rgba(var(--dark-color), var(--hundred));
}

.b-bb_codes-examples .example .textarea {
  background: rgba(var(--block-color), 0.4);
  border: rgba(var(--block-color), 0.4);
  color:  rgba(var(--light-color), var(--hundred));
  border: none !important;
  border-radius: 8px;
}

.b-bb_codes-examples .result a {
  color:  rgba(var(--white-color), var(--hundred));
}

.b-bb_codes-examples .result a:hover {
  color:  rgba(var(--hover-color), var(--hundred));
}

.b-quote .quoteable:before {
  color:  rgba(var(--bright-color), var(--hundred));
}

.b-bb_codes-examples .example span {
  color:  rgba(var(--dark-color), var(--hundred));
}

.b-video .marker, .b-image .marker, .b-video .name {
  color:  rgba(var(--light-color), var(--hundred));
  background: rgba(var(--block-color), 0.8);
  padding: 2px 2px 0 0;
  line-height: 12px;
  margin-left: 3px;
  margin-bottom: 3px;
}

.b-bb_codes-examples .result a:hover {
  color:  rgba(var(--hover-color), var(--hundred));
}

.b-bb_codes-examples .example span:after {
  color:  rgba(var(--dark-color), var(--hundred));
  content: ')';
}

.b-bb_codes-examples .example span:before {
  color:  rgba(var(--dark-color), var(--hundred));
  content: '(';
}

.buttons .editor-file {
  color:  rgba(var(--bright-color), var(--hundred));
}

.buttons .editor-file:hover {
  color:  rgba(var(--hover-color), var(--hundred));
}

/* history-yeah */
.p-profiles .profile-head .c-history .entry:hover, .p-topics .l-menu .reviews .entry:hover, .p-topics .l-menu .clubs .entry:hover {
  transform: scale(1.03);
  padding-left: 2px;
  padding-right: 5px;
  text-decoration: none !important;
  border: none !important;
  background: rgba(var(--shadows-color), 0.15);
  border-radius: 10px;
  box-shadow: 0 2px 6px 2px rgba(0, 0, 0, 0.2) !important;
}

body.localized_names-ru .name-ru {
  color:  rgba(var(--white-color), var(--hundred));
  font-weight: bold;
  text-decoration: none !important;
  transform: scale(1.05);
}

.p-profiles .profile-head .c-history .entry, .p-topics .l-menu .reviews .entry, .p-topics .l-menu .clubs .entry {
  padding-top: 0px;
  margin-bottom: 0px;
  padding: 0px 3px 0px;
  transition: 0.2s ease;
  border-top: none;
  text-decoration: none !important;
}

body.localized_names-ru .name-ru:before {
  transition: 0.3s ease;
}

.p-profiles .profile-head .c-history .entry img {
  float: left;
  margin: 2px 10px 2px 2px;
  max-height: 60px;
  max-width: 40px;
  border-radius: 10px;
}

.b-shiki_editor .images .link-value, .b-shiki_editor .links .link-value, .b-shiki_editor .images .link-value, .b-shiki_editor .quotes .link-value, .b-shiki_editor .email .link-value, .b-shiki_editor .upload .link-value, .b-shiki_editor .links .link-value, .b-shiki_editor .images .link-value, .b-shiki_editor .quotes .link-value, .b-shiki_editor .email .link-value, .b-shiki_editor .upload .link-value {
  background: rgba(var(--block-color), 0.4) !important;
  border-color: rgba(var(--block-color), 0.4) !important;
  color:  rgba(var(--light-color), var(--hundred));
  line-height: 20px;
  border-radius: 8px;
}

.p-profiles .profile-head .c-history .entry:hover .title {
  color:  rgba(var(--white-color), var(--hundred)) !important;
  text-decoration: none;
}

.p-profiles .profile-head .c-history .entry a:hover {
  color:  rgba(var(--bright-color), var(--hundred)) !important;
}

.headline, .midheadline, .subheadline {
  border: none;
  border-radius: 13px;
  box-shadow: 0 2px 6px 2px rgba(0, 0, 0, 0.2);
  background: rgba(var(--block-color), 0.6);
  transition: 0.3s ease;
  font-size: 14px;
  color:  rgba(var(--dark-color), var(--hundred));
}

.subheadline {
  line-height: 1;
  padding: 8px 10px 6px;
}

.headline > a, .midheadline > a, .subheadline > a {
  color:  inherit!important;
}

.headline > a:before, .midheadline > a:before, .subheadline > a:before {
  color:  rgba(var(--bright-color), var(--hundred)) !important;
  position: absolute;
  right: 10px !important;
  margin-left: 240px;
}

.headline > a:hover:before, .midheadline > a:hover:before, .subheadline > a:hover:before {
  color:  rgba(var(--hover-color), var(--hundred)) !important;
}





.profile-actions .mail::before, .profile-actions .talk::before, .profile-actions .fav-remove::before, .profile-actions .ban::before, .profile-actions .fav-add::before, .profile-actions .settings::before, .profile-actions .ignore-add::before, .profile-actions .ignore-remove::before {
  color: rgba(var(--light-color), 0.6) !important;
  transition: 0.3s ease;
  font-size: 24px !important;
}

.profile-actions .ignore-remove::before, .profile-actions .fav-remove::before {
  color: #ffc24eab !important;
  transition: 0.3s ease;
  font-size: 24px !important;
}

a.name {
  font-size: 12px;
}

.b-user.avatar img:hover {
  border-radius: 50%;
  border: 2px solid  rgba(var(--hover-color), var(--hundred));
  transform: scale(1.3);
}

.b-club .logo:hover {
  border: 2px solid  rgba(var(--hover-color), var(--hundred));
  transform: scale(1.3);
}

.b-clubs.one-line .b-club {
  transition: 0.2s ease-out;
}

.bar.vertical {
  border-bottom: none !important;
}

.b-db_entry-note .name-container .name {
  color:  rgba(var(--white-color), var(--hundred));
}

.b-db_entry-note .name-container .name:hover {
  color:  rgba(var(--hover-color), var(--hundred));
}

.subheadline-input {
  background-color:  rgba(var(--menu-back), var(--hundred)) !important;
  color:  rgba(var(--light-color), var(--hundred));
  border: 1px solid  rgba(var(--menu-back), var(--hundred)) !important;
  border-radius: 4px !important;
  padding: 5px 0px 3px 4px !important;
  line-height: 14px !important;
  right: 10px;
}

.b-comment > .inner .was_updated div, .b-topic > .inner .was_updated div, .was_updated div {
  color:  rgba(var(--dark-color), var(--hundred));
}

.b-comment > .inner .was_updated, .b-topic > .inner .was_updated, .was_updated {
  margin-left: 58px;
}

.buttons .item-quote:before {
  color:  rgba(var(--bright-color), var(--hundred));
}

.p-profiles-show .cc-favourites .c-column {
  width: 11.97%;
  box-sizing: border-box;
  float: left;
  margin-right: 0.5%;
  position: relative;
}

.b-db_entry-note .name-container .b-user_rate .b-add_to_list .trigger {
  font-size: 13px;
}

a:-webkit-any-link {
  text-decoration: none;
  color:  rgba(var(--bright-color), var(--hundred));
}

.p-moderations-show .b-list .size:after {
  color:  rgba(var(--dark-color), var(--hundred));
}

.p-moderations-show .b-list .size:before {
  color:  rgba(var(--dark-color), var(--hundred));
}

.b-user16:hover a:hover {
  text-decoration: none !important;
  color:  rgba(var(--hover-color), var(--hundred));
}

.b-animes-menu .friend-rate .b-user16 {
  overflow: visible;
}

.b-animes-menu .friend-rate .b-user16:hover {
  text-decoration: none !important;
  color:  rgba(var(--hover-color), var(--hundred));
}

.b-stats_bar.lifetime .bar .first {
  background:  rgba(var(--time-filled), var(--hundred));
}

.b-image img {
  transition: 0.3s ease !important;
}

img {
  -webkit-filter: brightness(0.9);
}

.b-separator.inline {
  color: rgba(var(--light-color), 0.5) !important;
}

.p-profiles .profile-head .c-history .entry .misc.date.unprocessed {
  color:  rgba(var(--dark-color), var(--hundred)) !important;
  text-align: center;
  text-indent: 0em !important;
  animation: none !important;
  width: auto;
}

.p-profiles .profile-head .c-history .entry .misc {
  animation: runningtext 18s ease-in-out infinite;
  animation-delay: 2s;
  text-align: center;
}

.profile-actions .mail:hover::before, .profile-actions .talk:hover::before, .profile-actions .fav-remove:hover::before, .profile-actions .ban:hover::before, .profile-actions .fav-add:hover::before, .profile-actions .settings:hover::before, .profile-actions .ignore-add:hover::before, .profile-actions .ignore-remove:hover::before {
  color:  rgba(var(--hover-color), var(--hundred)) !important;
  transform: scale(1.3);
}

.profile-actions .mail:before, .profile-actions .talk:before {
  transition: 0.3s ease;
  content: '\\_f0e0';
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
}

.profile-actions .mail:hover:before {
  color:  rgba(var(--hover-color), var(--hundred)) !important;
  transform: scale(1.3);
}

.profile-actions .settings:before {
  transition: 0.3s ease;
  content: '\\_f085';
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
}

.profile-actions .settings:hover:before {
  color:  rgba(var(--hover-color), var(--hundred)) !important;
  transform: scale(1.3);
}

.profile-actions .ban:before {
  transition: 0.3s ease;
  content: '\\_f06a';
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  line-height: 38px !important;
}

.profile-actions .ban:hover:before {
  color:  rgba(var(--hover-color), var(--hundred)) !important;
  transform: scale(1.3);
}

.activity .graph.vertical .line .bar {
  box-sizing: content-box;
  transform: translateY(1px);
  transform-origin: center bottom;
  animation-fill-mode: both;
  animation-timing-function: linear;
  animation-iteration-count: infinite;
  animation-duration: 1.5s;
  animation-name: activity;
}

.profile-actions .fav-add::before {
  transition: 0.3s ease;
  content: '\\_f234';
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
}

.profile-actions .fav-remove::before {
  transition: 0.3s ease;
  content: '\\_f235';
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
}

.profile-actions .ignore-add:before {
  transition: 0.3s ease;
  content: '\\_f2a8';
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
}

.profile-actions .ignore-remove:before {
  transition: 0.3s ease;
  content: '\\_f25b';
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
}

.buttons .item-delete:before {
  content: '\\_f1f8';
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
}

.buttons .item-edit:before {
  content: '\\_f040';
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
}

.buttons .item-reply:before {
  content: '\\_f27a';
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
}

.b-quote .quoteable:before {
  content: '\\_f10d';
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
}

.activity .graph.vertical .line .bar:hover {
  animation-name: none;
  transform: none;
}

.activity .graph.vertical .line:nth-of-type(6n+2) .bar {
  animation-delay: -.25s;
}

.activity .graph.vertical .line:nth-of-type(6n+4) .bar {
  animation-delay: -.5s;
}

.activity .graph.vertical .line:nth-of-type(6n+3) .bar {
  animation-delay: -.75s;
}

.activity .graph.vertical .line:nth-of-type(6n+6) .bar {
  animation-delay: -1s;
}

.activity .graph.vertical .line:nth-of-type(6n+5) .bar {
  animation-delay: -1.25s;
}

.tipsy.tipsy-s {
  opacity: 1 !important;
}

.tipsy-inner {
  background:  rgba(var(--time-empty), var(--hundred)) !important;
  padding: 6px 12px;
  font-size: 13px;
  box-shadow: 0px 0px 20px rgba(var(--shadows-color), 0.3);
  transition: 0.1s ease;
  color:  rgba(var(--white-color), var(--hundred));
  border-radius: 4px;
}

.tipsy-arrow-s {
  border-top-color:  rgba(var(--time-empty), var(--hundred));
}

.tipsy-arrow {
  border: 5px dashed  rgba(var(--time-empty), var(--hundred));
}

.club-actions .invite, .club-actions .upload, .club-actions .broadcast, .club-actions .edit-club, .club-actions .leave {
  margin: 0 10px;
  text-align: center;
}

.club-actions .invite:before, .club-actions .upload:before, .club-actions .broadcast:before, .club-actions .edit-club:before, .club-actions .leave:before {
  transition: 0.3s ease;
  color:  rgba(var(--bright-color), var(--hundred));
}

.club-actions .invite:hover:before, .club-actions .upload:hover:before, .club-actions .broadcast:hover:before, .club-actions .edit-club:hover:before, .club-actions .leave:hover:before {
  color:  rgba(var(--hover-color), var(--hundred));
  transform: scale(1.3);
}

.club-actions a:hover {
  background: none;
  box-shadow: none;
}

.b-comments-notifier {
  background:  rgba(var(--hover-color), var(--hundred));
  color: #f9f9f9;
  line-height: 41px;
  transition: 0.5s ease;
  font-size: 19px;
  font-weight: bold;
  width: 37px;
  height: 37px;
  margin: 0;
  top: 80px !important;
  right: 20px;
  border-radius: 50%;
  z-index: 9;
}

.b-comments-notifier:hover {
  background-color:  rgba(var(--hover-color), var(--hundred));
}

.b-animes-menu .menu-topics-block .history-entry-tooltip .tooltip-details a {
  color:  rgba(var(--white-color), var(--hundred)) !important;
  transition: 0.3s ease;
}

.b-animes-menu .menu-topics-block .history-entry-tooltip .tooltip-details a:hover {
  color:  rgba(var(--hover-color), var(--hundred)) !important;
}

.avatar img, .profile img {
  border-radius: 50%;
}

.l-page {
  overflow: visible !important;
  border-radius: 12px;
}

body#dashboards_show .l-page {
  margin: 40px auto 15px;
}

.b-mention:hover span, .b-mention s:hover {
  text-decoration: none !important;
  color:  rgba(var(--hover-color), var(--hundred)) !important;
}

.b-mention, .b-mention s {
  color:  rgba(var(--bright-color), var(--hundred));
  bottom: 1px;
  position: relative;
}

.p-studios .studio .name {
  color:  rgba(var(--white-color), var(--hundred));
  width: 150px;
}

.p-studios .studio .name:hover {
  color:  rgba(var(--hover-color), var(--hundred));
}

.p-studios .studio .animes .num, .p-studios .studio .years .num {
  color:  rgba(var(--light-color), var(--hundred));
}

.p-dashboards .user_list .list-type > .title .switch:hover, .p-dashboards .user_list .history > .title .switch:hover, .p-dashboards .user_list .list-type > .title .link:hover, .p-dashboards .user_list .history > .title .link:hover {
  color:  rgba(var(--hover-color), var(--hundred));
  box-shadow: 0px 0px 20px rgba(var(--shadows-color), 0.5);
  background: rgba(var(--shadows-color), 0.25);
}

.p-dashboards .user_list .list-type > .title .switch, .p-dashboards .user_list .history > .title .switch, .p-dashboards .user_list .list-type > .title .link, .p-dashboards .user_list .history > .title .link {
  color:  rgba(var(--dark-color), var(--hundred));
  text-decoration: none !important;
  border-bottom: none;
  transition: 0.2s ease;
}



@media screen and (max-width: 1200px) {
  body.p-achievements.p-profiles .block.m0:before {
    content: '★ ▬▬ ACHIEVEMENTS ▬▬ ★';
    font-size: 32px;
  }
  .p-achievements-index .cc-achievements .b-achievement, .p-achievements-index .cc-franchises-genres .c-genres .b-achievement {
    width: calc(300px - 36px);
  }
  .p-achievements-index .cc-achievements, .p-achievements-index .cc-franchises-genres .c-genres .cc-achievements, .c-franchises .cc {
    display: flex;
    flex-wrap: wrap;
    align-items: center;
    align-content: center;
    justify-content: center;
  }
  .b-achievement .c-about .title {
    height: 33px;
    line-height: 18px !important;
    display: table-cell;
    vertical-align: middle;
  }
  .p-achievements-index .c-franchises .b-badge {
    width: 280px;
    margin-right: 1% !important;
  }
  .p-achievements-index .c-franchises .b-badge[data-progress='100']:after {
    background: linear-gradient(135deg, transparent 283px, #483d1c 0);
  }
  body.p-achievements.p-profiles .b-list_switchers {
    margin-top: 2px !important;
  }
  .p-profiles-show .cc-favourites .c-column:nth-child(n+9) {
    display: none;
  }
}

@media screen and (min-width: 736px) and (max-width: 880px) {
  .p-achievements-index .cc-achievements .b-achievement, .p-achievements-index .cc-franchises-genres .c-genres .b-achievement {
    width: calc(250px - 36px);
  }
  .p-achievements-index .cc-achievements .b-achievement .c-about .text {
    font-size: 11px;
  }
  .b-achievement .c-about {
    padding: 14px;
  }
  .b-achievement .c-about a.title {
    font-size: 12px;
  }
  .p-achievements-index .cc-achievements .b-achievement, .p-achievements-index .cc-franchises-genres .c-genres .b-achievement {
    min-height: 314px;
  }
  span.switcher.b-tooltipped.popularity, span.switcher.b-tooltipped.alphabet {
    width: 80px;
  }
  .b-list_switchers .switcher.popularity:before, .b-list_switchers .switcher.alphabet:before {
    content: '===';
    font: bold 20px "Comfortaa" !important;
    width: 51px;
  }
}

@media screen and (min-width: 600px) and (max-width: 735px) {
  .p-achievements-index .cc-achievements .b-achievement, .p-achievements-index .cc-franchises-genres .c-genres .b-achievement {
    width: calc(200px - 36px);
  }
  .p-achievements-index .cc-achievements .b-achievement .c-about .text {
    font-size: 11px;
  }
  .b-achievement .c-about {
    padding: 12px;
  }
  .b-achievement .c-about a.title {
    font-size: 12px;
  }
  .b-achievement .c-about .hint {
    font-size: 10px;
  }
  .b-achievement .c-about .percent {
    float: right;
    font-size: 12px;
  }
  .p-achievements-index .cc-achievements .b-achievement, .p-achievements-index .cc-franchises-genres .c-genres .b-achievement {
    min-height: 314px;
  }
  span.switcher.b-tooltipped.popularity, span.switcher.b-tooltipped.alphabet {
    width: 30px;
  }
  .b-list_switchers .switcher.popularity:before, .b-list_switchers .switcher.alphabet:before {
    content: '';
    font: bold 20px "Comfortaa" !important;
    width: 50px;
  }
}

@media screen and (max-width: 599px) {
  .p-achievements-index .cc-achievements .b-achievement, .p-achievements-index .cc-franchises-genres .c-genres .b-achievement {
    width: 100%;
    max-width: 300px;
  }
  body.p-achievements.p-profiles .block.m0:before {
    content: '★ ACHIEVEMENTS ★';
    font-size: 32px;
  }
  .p-achievements-index .cc-achievements .b-achievement, .p-achievements-index .cc-franchises-genres .c-genres .b-achievement {
    min-height: 274px;
  }
  span.switcher.b-tooltipped.popularity, span.switcher.b-tooltipped.alphabet {
    width: 30px;
  }
  .b-list_switchers .switcher.popularity:before, .b-list_switchers .switcher.alphabet:before {
    content: '';
    font: bold 20px "Comfortaa" !important;
    width: 50px;
  }
  .p-achievements-index .c-franchises .b-badge {
    margin: 6px !important;
  }
  .p-achievements-index .c-franchises .b-badge[data-progress='100']:after {
    background: linear-gradient(135deg, transparent 280px, #483d1c 0);
  }
}
