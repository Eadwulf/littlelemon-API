<html><head><meta http-equiv="Content-Type" content="text/html; charset=utf-8"/><title>API Final Project Documentation</title><style>
/* cspell:disable-file */
/* webkit printing magic: print all background colors */
html {
	-webkit-print-color-adjust: exact;
}
* {
	box-sizing: border-box;
	-webkit-print-color-adjust: exact;
}

html,
body {
	margin: 0;
	padding: 0;
}
@media only screen {
	body {
		margin: 2em auto;
		max-width: 900px;
		color: rgb(55, 53, 47);
	}
}

body {
	line-height: 1.5;
	white-space: pre-wrap;
}

a,
a.visited {
	color: inherit;
	text-decoration: underline;
}

.pdf-relative-link-path {
	font-size: 80%;
	color: #444;
}

h1,
h2,
h3 {
	letter-spacing: -0.01em;
	line-height: 1.2;
	font-weight: 600;
	margin-bottom: 0;
}

.page-title {
	font-size: 2.5rem;
	font-weight: 700;
	margin-top: 0;
	margin-bottom: 0.75em;
}

h1 {
	font-size: 1.875rem;
	margin-top: 1.875rem;
}

h2 {
	font-size: 1.5rem;
	margin-top: 1.5rem;
}

h3 {
	font-size: 1.25rem;
	margin-top: 1.25rem;
}

.source {
	border: 1px solid #ddd;
	border-radius: 3px;
	padding: 1.5em;
	word-break: break-all;
}

.callout {
	border-radius: 3px;
	padding: 1rem;
}

figure {
	margin: 1.25em 0;
	page-break-inside: avoid;
}

figcaption {
	opacity: 0.5;
	font-size: 85%;
	margin-top: 0.5em;
}

mark {
	background-color: transparent;
}

.indented {
	padding-left: 1.5em;
}

hr {
	background: transparent;
	display: block;
	width: 100%;
	height: 1px;
	visibility: visible;
	border: none;
	border-bottom: 1px solid rgba(55, 53, 47, 0.09);
}

img {
	max-width: 100%;
}

@media only print {
	img {
		max-height: 100vh;
		object-fit: contain;
	}
}

@page {
	margin: 1in;
}

.collection-content {
	font-size: 0.875rem;
}

.column-list {
	display: flex;
	justify-content: space-between;
}

.column {
	padding: 0 1em;
}

.column:first-child {
	padding-left: 0;
}

.column:last-child {
	padding-right: 0;
}

.table_of_contents-item {
	display: block;
	font-size: 0.875rem;
	line-height: 1.3;
	padding: 0.125rem;
}

.table_of_contents-indent-1 {
	margin-left: 1.5rem;
}

.table_of_contents-indent-2 {
	margin-left: 3rem;
}

.table_of_contents-indent-3 {
	margin-left: 4.5rem;
}

.table_of_contents-link {
	text-decoration: none;
	opacity: 0.7;
	border-bottom: 1px solid rgba(55, 53, 47, 0.18);
}

table,
th,
td {
	border: 1px solid rgba(55, 53, 47, 0.09);
	border-collapse: collapse;
}

table {
	border-left: none;
	border-right: none;
}

th,
td {
	font-weight: normal;
	padding: 0.25em 0.5em;
	line-height: 1.5;
	min-height: 1.5em;
	text-align: left;
}

th {
	color: rgba(55, 53, 47, 0.6);
}

ol,
ul {
	margin: 0;
	margin-block-start: 0.6em;
	margin-block-end: 0.6em;
}

li > ol:first-child,
li > ul:first-child {
	margin-block-start: 0.6em;
}

ul > li {
	list-style: disc;
}

ul.to-do-list {
	text-indent: -1.7em;
}

ul.to-do-list > li {
	list-style: none;
}

.to-do-children-checked {
	text-decoration: line-through;
	opacity: 0.375;
}

ul.toggle > li {
	list-style: none;
}

ul {
	padding-inline-start: 1.7em;
}

ul > li {
	padding-left: 0.1em;
}

ol {
	padding-inline-start: 1.6em;
}

ol > li {
	padding-left: 0.2em;
}

.mono ol {
	padding-inline-start: 2em;
}

.mono ol > li {
	text-indent: -0.4em;
}

.toggle {
	padding-inline-start: 0em;
	list-style-type: none;
}

/* Indent toggle children */
.toggle > li > details {
	padding-left: 1.7em;
}

.toggle > li > details > summary {
	margin-left: -1.1em;
}

.selected-value {
	display: inline-block;
	padding: 0 0.5em;
	background: rgba(206, 205, 202, 0.5);
	border-radius: 3px;
	margin-right: 0.5em;
	margin-top: 0.3em;
	margin-bottom: 0.3em;
	white-space: nowrap;
}

.collection-title {
	display: inline-block;
	margin-right: 1em;
}

.simple-table {
	margin-top: 1em;
	font-size: 0.875rem;
	empty-cells: show;
}
.simple-table td {
	height: 29px;
	min-width: 120px;
}

.simple-table th {
	height: 29px;
	min-width: 120px;
}

.simple-table-header-color {
	background: rgb(247, 246, 243);
	color: black;
}
.simple-table-header {
	font-weight: 500;
}

time {
	opacity: 0.5;
}

.icon {
	display: inline-block;
	max-width: 1.2em;
	max-height: 1.2em;
	text-decoration: none;
	vertical-align: text-bottom;
	margin-right: 0.5em;
}

img.icon {
	border-radius: 3px;
}

.user-icon {
	width: 1.5em;
	height: 1.5em;
	border-radius: 100%;
	margin-right: 0.5rem;
}

.user-icon-inner {
	font-size: 0.8em;
}

.text-icon {
	border: 1px solid #000;
	text-align: center;
}

.page-cover-image {
	display: block;
	object-fit: cover;
	width: 100%;
	max-height: 30vh;
}

.page-header-icon {
	font-size: 3rem;
	margin-bottom: 1rem;
}

.page-header-icon-with-cover {
	margin-top: -0.72em;
	margin-left: 0.07em;
}

.page-header-icon img {
	border-radius: 3px;
}

.link-to-page {
	margin: 1em 0;
	padding: 0;
	border: none;
	font-weight: 500;
}

p > .user {
	opacity: 0.5;
}

td > .user,
td > time {
	white-space: nowrap;
}

input[type="checkbox"] {
	transform: scale(1.5);
	margin-right: 0.6em;
	vertical-align: middle;
}

p {
	margin-top: 0.5em;
	margin-bottom: 0.5em;
}

.image {
	border: none;
	margin: 1.5em 0;
	padding: 0;
	border-radius: 0;
	text-align: center;
}

.code,
code {
	background: rgba(135, 131, 120, 0.15);
	border-radius: 3px;
	padding: 0.2em 0.4em;
	border-radius: 3px;
	font-size: 85%;
	tab-size: 2;
}

code {
	color: #eb5757;
}

.code {
	padding: 1.5em 1em;
}

.code-wrap {
	white-space: pre-wrap;
	word-break: break-all;
}

.code > code {
	background: none;
	padding: 0;
	font-size: 100%;
	color: inherit;
}

blockquote {
	font-size: 1.25em;
	margin: 1em 0;
	padding-left: 1em;
	border-left: 3px solid rgb(55, 53, 47);
}

.bookmark {
	text-decoration: none;
	max-height: 8em;
	padding: 0;
	display: flex;
	width: 100%;
	align-items: stretch;
}

.bookmark-title {
	font-size: 0.85em;
	overflow: hidden;
	text-overflow: ellipsis;
	height: 1.75em;
	white-space: nowrap;
}

.bookmark-text {
	display: flex;
	flex-direction: column;
}

.bookmark-info {
	flex: 4 1 180px;
	padding: 12px 14px 14px;
	display: flex;
	flex-direction: column;
	justify-content: space-between;
}

.bookmark-image {
	width: 33%;
	flex: 1 1 180px;
	display: block;
	position: relative;
	object-fit: cover;
	border-radius: 1px;
}

.bookmark-description {
	color: rgba(55, 53, 47, 0.6);
	font-size: 0.75em;
	overflow: hidden;
	max-height: 4.5em;
	word-break: break-word;
}

.bookmark-href {
	font-size: 0.75em;
	margin-top: 0.25em;
}

.sans { font-family: ui-sans-serif, -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, "Apple Color Emoji", Arial, sans-serif, "Segoe UI Emoji", "Segoe UI Symbol"; }
.code { font-family: "SFMono-Regular", Menlo, Consolas, "PT Mono", "Liberation Mono", Courier, monospace; }
.serif { font-family: Lyon-Text, Georgia, ui-serif, serif; }
.mono { font-family: iawriter-mono, Nitti, Menlo, Courier, monospace; }
.pdf .sans { font-family: Inter, ui-sans-serif, -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, "Apple Color Emoji", Arial, sans-serif, "Segoe UI Emoji", "Segoe UI Symbol", 'Twemoji', 'Noto Color Emoji', 'Noto Sans CJK JP'; }
.pdf:lang(zh-CN) .sans { font-family: Inter, ui-sans-serif, -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, "Apple Color Emoji", Arial, sans-serif, "Segoe UI Emoji", "Segoe UI Symbol", 'Twemoji', 'Noto Color Emoji', 'Noto Sans CJK SC'; }
.pdf:lang(zh-TW) .sans { font-family: Inter, ui-sans-serif, -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, "Apple Color Emoji", Arial, sans-serif, "Segoe UI Emoji", "Segoe UI Symbol", 'Twemoji', 'Noto Color Emoji', 'Noto Sans CJK TC'; }
.pdf:lang(ko-KR) .sans { font-family: Inter, ui-sans-serif, -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, "Apple Color Emoji", Arial, sans-serif, "Segoe UI Emoji", "Segoe UI Symbol", 'Twemoji', 'Noto Color Emoji', 'Noto Sans CJK KR'; }
.pdf .code { font-family: Source Code Pro, "SFMono-Regular", Menlo, Consolas, "PT Mono", "Liberation Mono", Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK JP'; }
.pdf:lang(zh-CN) .code { font-family: Source Code Pro, "SFMono-Regular", Menlo, Consolas, "PT Mono", "Liberation Mono", Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK SC'; }
.pdf:lang(zh-TW) .code { font-family: Source Code Pro, "SFMono-Regular", Menlo, Consolas, "PT Mono", "Liberation Mono", Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK TC'; }
.pdf:lang(ko-KR) .code { font-family: Source Code Pro, "SFMono-Regular", Menlo, Consolas, "PT Mono", "Liberation Mono", Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK KR'; }
.pdf .serif { font-family: PT Serif, Lyon-Text, Georgia, ui-serif, serif, 'Twemoji', 'Noto Color Emoji', 'Noto Serif CJK JP'; }
.pdf:lang(zh-CN) .serif { font-family: PT Serif, Lyon-Text, Georgia, ui-serif, serif, 'Twemoji', 'Noto Color Emoji', 'Noto Serif CJK SC'; }
.pdf:lang(zh-TW) .serif { font-family: PT Serif, Lyon-Text, Georgia, ui-serif, serif, 'Twemoji', 'Noto Color Emoji', 'Noto Serif CJK TC'; }
.pdf:lang(ko-KR) .serif { font-family: PT Serif, Lyon-Text, Georgia, ui-serif, serif, 'Twemoji', 'Noto Color Emoji', 'Noto Serif CJK KR'; }
.pdf .mono { font-family: PT Mono, iawriter-mono, Nitti, Menlo, Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK JP'; }
.pdf:lang(zh-CN) .mono { font-family: PT Mono, iawriter-mono, Nitti, Menlo, Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK SC'; }
.pdf:lang(zh-TW) .mono { font-family: PT Mono, iawriter-mono, Nitti, Menlo, Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK TC'; }
.pdf:lang(ko-KR) .mono { font-family: PT Mono, iawriter-mono, Nitti, Menlo, Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK KR'; }
.highlight-default {
	color: rgba(55, 53, 47, 1);
}
.highlight-gray {
	color: rgba(120, 119, 116, 1);
	fill: rgba(120, 119, 116, 1);
}
.highlight-brown {
	color: rgba(159, 107, 83, 1);
	fill: rgba(159, 107, 83, 1);
}
.highlight-orange {
	color: rgba(217, 115, 13, 1);
	fill: rgba(217, 115, 13, 1);
}
.highlight-yellow {
	color: rgba(203, 145, 47, 1);
	fill: rgba(203, 145, 47, 1);
}
.highlight-teal {
	color: rgba(68, 131, 97, 1);
	fill: rgba(68, 131, 97, 1);
}
.highlight-blue {
	color: rgba(51, 126, 169, 1);
	fill: rgba(51, 126, 169, 1);
}
.highlight-purple {
	color: rgba(144, 101, 176, 1);
	fill: rgba(144, 101, 176, 1);
}
.highlight-pink {
	color: rgba(193, 76, 138, 1);
	fill: rgba(193, 76, 138, 1);
}
.highlight-red {
	color: rgba(212, 76, 71, 1);
	fill: rgba(212, 76, 71, 1);
}
.highlight-gray_background {
	background: rgba(241, 241, 239, 1);
}
.highlight-brown_background {
	background: rgba(244, 238, 238, 1);
}
.highlight-orange_background {
	background: rgba(251, 236, 221, 1);
}
.highlight-yellow_background {
	background: rgba(251, 243, 219, 1);
}
.highlight-teal_background {
	background: rgba(237, 243, 236, 1);
}
.highlight-blue_background {
	background: rgba(231, 243, 248, 1);
}
.highlight-purple_background {
	background: rgba(244, 240, 247, 0.8);
}
.highlight-pink_background {
	background: rgba(249, 238, 243, 0.8);
}
.highlight-red_background {
	background: rgba(253, 235, 236, 1);
}
.block-color-default {
	color: inherit;
	fill: inherit;
}
.block-color-gray {
	color: rgba(120, 119, 116, 1);
	fill: rgba(120, 119, 116, 1);
}
.block-color-brown {
	color: rgba(159, 107, 83, 1);
	fill: rgba(159, 107, 83, 1);
}
.block-color-orange {
	color: rgba(217, 115, 13, 1);
	fill: rgba(217, 115, 13, 1);
}
.block-color-yellow {
	color: rgba(203, 145, 47, 1);
	fill: rgba(203, 145, 47, 1);
}
.block-color-teal {
	color: rgba(68, 131, 97, 1);
	fill: rgba(68, 131, 97, 1);
}
.block-color-blue {
	color: rgba(51, 126, 169, 1);
	fill: rgba(51, 126, 169, 1);
}
.block-color-purple {
	color: rgba(144, 101, 176, 1);
	fill: rgba(144, 101, 176, 1);
}
.block-color-pink {
	color: rgba(193, 76, 138, 1);
	fill: rgba(193, 76, 138, 1);
}
.block-color-red {
	color: rgba(212, 76, 71, 1);
	fill: rgba(212, 76, 71, 1);
}
.block-color-gray_background {
	background: rgba(241, 241, 239, 1);
}
.block-color-brown_background {
	background: rgba(244, 238, 238, 1);
}
.block-color-orange_background {
	background: rgba(251, 236, 221, 1);
}
.block-color-yellow_background {
	background: rgba(251, 243, 219, 1);
}
.block-color-teal_background {
	background: rgba(237, 243, 236, 1);
}
.block-color-blue_background {
	background: rgba(231, 243, 248, 1);
}
.block-color-purple_background {
	background: rgba(244, 240, 247, 0.8);
}
.block-color-pink_background {
	background: rgba(249, 238, 243, 0.8);
}
.block-color-red_background {
	background: rgba(253, 235, 236, 1);
}
.select-value-color-pink { background-color: rgba(245, 224, 233, 1); }
.select-value-color-purple { background-color: rgba(232, 222, 238, 1); }
.select-value-color-green { background-color: rgba(219, 237, 219, 1); }
.select-value-color-gray { background-color: rgba(227, 226, 224, 1); }
.select-value-color-opaquegray { background-color: rgba(255, 255, 255, 0.0375); }
.select-value-color-orange { background-color: rgba(250, 222, 201, 1); }
.select-value-color-brown { background-color: rgba(238, 224, 218, 1); }
.select-value-color-red { background-color: rgba(255, 226, 221, 1); }
.select-value-color-yellow { background-color: rgba(253, 236, 200, 1); }
.select-value-color-blue { background-color: rgba(211, 229, 239, 1); }

.checkbox {
	display: inline-flex;
	vertical-align: text-bottom;
	width: 16;
	height: 16;
	background-size: 16px;
	margin-left: 2px;
	margin-right: 5px;
}

.checkbox-on {
	background-image: url("data:image/svg+xml;charset=UTF-8,%3Csvg%20width%3D%2216%22%20height%3D%2216%22%20viewBox%3D%220%200%2016%2016%22%20fill%3D%22none%22%20xmlns%3D%22http%3A%2F%2Fwww.w3.org%2F2000%2Fsvg%22%3E%0A%3Crect%20width%3D%2216%22%20height%3D%2216%22%20fill%3D%22%2358A9D7%22%2F%3E%0A%3Cpath%20d%3D%22M6.71429%2012.2852L14%204.9995L12.7143%203.71436L6.71429%209.71378L3.28571%206.2831L2%207.57092L6.71429%2012.2852Z%22%20fill%3D%22white%22%2F%3E%0A%3C%2Fsvg%3E");
}

.checkbox-off {
	background-image: url("data:image/svg+xml;charset=UTF-8,%3Csvg%20width%3D%2216%22%20height%3D%2216%22%20viewBox%3D%220%200%2016%2016%22%20fill%3D%22none%22%20xmlns%3D%22http%3A%2F%2Fwww.w3.org%2F2000%2Fsvg%22%3E%0A%3Crect%20x%3D%220.75%22%20y%3D%220.75%22%20width%3D%2214.5%22%20height%3D%2214.5%22%20fill%3D%22white%22%20stroke%3D%22%2336352F%22%20stroke-width%3D%221.5%22%2F%3E%0A%3C%2Fsvg%3E");
}
	
</style></head><body><article id="d819c208-da41-4c63-8ec2-fd3000f23f90" class="page sans"><header><h1 class="page-title">API Final Project Documentation</h1></header><div class="page-body"><h1 id="8d1f3532-32c5-4d8c-81f0-bfdfc273369e" class="">Description</h1><p id="ac6409dc-03cf-4587-8c30-b7016176c144" class="">The LittleLemon API is the final project for the <a href="https://www.coursera.org/learn/apis">APIs Course</a> part of the <a href="https://www.coursera.org/professional-certificates/meta-back-end-developer">Meta BackEnd Developer Professional Certificate</a> on <a href="https://www.coursera.org/">Coursera</a>. </p><p id="7e5f9083-7c8c-4a69-a86f-c6a9bec67aa5" class="">The API entpoints for this project, provides functionality to create, edit and delete users, roles for each user, such as Customer, Delivery Crew or Manager, menu items, categories for menu-items,  shopping cart and orders. Every API endpoint have authorization and permissions constraints as well as throttling, pagination and filtering.</p><h2 id="9e7c8243-492f-4f01-9ea3-81153aab0fc4" class="">Project Structure</h2><p id="3f992e59-a811-41ef-acd3-650ec017d072" class="">This project consist mainly of two apps, <em>littlelemon</em> and <em>api</em>.</p><p id="da15eec3-a384-41ba-9307-5d5d12705a28" class="">
</p><p id="37ca248c-bf41-471c-9c07-129afd73dc09" class=""><strong>littlelemon app</strong></p><p id="0bfdd877-4cb1-4c0d-8f32-f8f72ba40ec0" class="">This app contains the models definition to create the entity relationships required by <em>api</em> app.</p><p id="cb538eab-b2f9-4944-b7dc-14416725ab16" class="">
</p><p id="13a4a634-ae93-4720-95c8-49854695fe3d" class=""><strong>api app</strong></p><p id="19363fa8-906d-408c-98f8-2cec7c35f1dc" class="">This app contains the URLs dispatchers (routers), serializers, and the views for every endpoint of the API. Additionally, it contains helpers (mixins) that are inherited by the class-based views.  </p><p id="70f4615c-beda-4766-a724-9c292f854616" class="">
</p><p id="500b70b1-623f-433b-a6c2-cca67149adb9" class=""><strong>config dir</strong></p><p id="9b71d0c2-2f5d-46c3-8b4f-132f2bf07615" class="">This directory contains the configuration files of the project, such as the <a href="http://settings.py">settings.py</a> file and the <a href="http://urls.py">urls.py</a> file which contains the main URL dispatchers of the the project.</p><p id="96e719f0-c7af-4433-b145-ff9e268d8fdc" class="">
</p><p id="393fff54-7a77-4e40-aeaf-148277a0fd95" class=""><strong>Note for the peers that will review this project</strong>:</p><p id="6044a87b-d4da-411c-998b-6dbedc080e90" class="">Please be aware that I made certain things different from what is was required, but I met every criteria. I just developed the project in the way that felt right to me. Some of my entity relationships (models) are different as well as the logic within them I even added extra entities and extra constraints. I suggest you read this documentation in order to understand the whole project before attempting to test its endpoints. If you have any doubt, feel free to contact me via email at adolfoj@protonmail.com.</p><p id="00674daa-1707-4a50-a14c-f25fc534b18e" class="">
</p><h2 id="730a7093-6ff7-41a1-b113-b452bf98d8c1" class="">Installation</h2><p id="035ec19d-5585-476a-a3fe-7096fe9a15e4" class="">
</p><p id="7f20b367-8e73-44e6-ba13-4c9c1f49e4ca" class=""><strong>Clone the repository</strong></p><pre id="08b15e94-3d24-4b35-9cb3-4db17e152f44" class="code"><code>git clone https://github.com/Eadwulf/littlelemon.git &amp;&amp; cd littlelemon</code></pre><p id="9690152e-2791-448b-86a6-aedd5f146fb9" class="">
</p><p id="f5f381a0-4ddf-417f-8e88-44aab74e32ca" class=""><strong>Create the virtual environment and install the dependencies</strong></p><pre id="ab88a1ed-b62d-470b-84fa-3f21e26bcaf0" class="code"><code>pipenv install</code></pre><p id="ccff643c-04aa-4773-9492-020064543915" class="">Note that I use <a href="https://djoser.readthedocs.io/en/latest/introduction.html">Djoser</a> but is included within the repository and not as a dependency. <a href="https://djoser.readthedocs.io/en/latest/introduction.html">Djoser</a> has some bugs that creates a compatibility error with the latest version of <a href="https://www.django-rest-framework.org/">DjangoRestFramework</a>, I made the corrections that I needed, and added it to the project as a local app to avoid such compatibility errors.</p><p id="3a7b1c6a-520f-4a65-9449-8ee45741c7a9" class="">
</p><p id="2035e99e-6fc6-4ba3-a74c-2158bddc4fe6" class="">G<strong>enerate and apply the migrations</strong></p><pre id="76c5cd10-c530-404f-951d-3bc565c1dc03" class="code"><code>python manage.py makemigrations &amp;&amp; python manage.py migrate</code></pre><p id="b9db1dde-166d-420f-9b26-b030bda3a4ea" class="">The default sqlite3 database is included in the repository, therefore, the above commands are not required, but if you wish to use a different database, make the pertinent configurations, and generate and apply the migrations.</p><p id="dff34eb0-f139-418a-9eca-9621f629f950" class="">
</p><p id="9615d5a6-46f6-41fb-b08c-545722720afa" class=""><strong>Run the server</strong></p><pre id="26dcf056-87ae-4e0a-90c7-d32818602967" class="code"><code>python manage.py runserver</code></pre><p id="9eec6e9f-1f87-4bd8-aa41-6e1e7043add9" class="">
</p><h1 id="1983c973-e5f1-467c-b2e0-32b0474ac58e" class="">API endpoints and usage explanation</h1><p id="b4a4927e-7992-4ee5-9a97-8e5aa8edc492" class=""><em>For the examples, I added code snippets for usage with curl, but feel free to use whatever tool suits you best.</em></p><h2 id="d113c061-2ada-42db-ac89-37ef06fd5add" class="">Roles</h2><table id="88e08c17-6436-4721-a074-d553a2e0cb44" class="simple-table"><thead class="simple-table-header"><tr id="ee2445eb-e9f7-48fc-99c2-a80d45c7c267"><th id="dvHV" class="simple-table-header-color simple-table-header" style="width:193.0243148803711px">ROLE</th><th id="`=r`" class="simple-table-header-color simple-table-header" style="width:166.9791717529297px">GROUP</th><th id="z~an" class="simple-table-header-color simple-table-header" style="width:203.61459350585938px">HAS RESTRICTION</th></tr></thead><tbody><tr id="fb1b4350-c64e-41dc-8f2e-873a4eb3ee90"><td id="dvHV" class="" style="width:193.0243148803711px">Unauthenticated</td><td id="`=r`" class="" style="width:166.9791717529297px">None</td><td id="z~an" class="" style="width:203.61459350585938px">YES</td></tr><tr id="f0ff11f2-b03f-4078-9f96-89575c00e997"><td id="dvHV" class="" style="width:193.0243148803711px">Customer</td><td id="`=r`" class="" style="width:166.9791717529297px">Customer</td><td id="z~an" class="" style="width:203.61459350585938px">YES</td></tr><tr id="46fd07da-5cdd-4b4f-8e53-09fca31928fe"><td id="dvHV" class="" style="width:193.0243148803711px">Delivery Crew</td><td id="`=r`" class="" style="width:166.9791717529297px">Delivery Crew</td><td id="z~an" class="" style="width:203.61459350585938px">YES</td></tr><tr id="c7c21b21-7518-4eb1-83eb-3b9de2b58929"><td id="dvHV" class="" style="width:193.0243148803711px">Manager</td><td id="`=r`" class="" style="width:166.9791717529297px">Manager</td><td id="z~an" class="" style="width:203.61459350585938px">YES</td></tr><tr id="af326b39-66e4-4688-a10e-61130675e5d2"><td id="dvHV" class="" style="width:193.0243148803711px">System Administrator</td><td id="`=r`" class="" style="width:166.9791717529297px">SysAdmin</td><td id="z~an" class="" style="width:203.61459350585938px">NO</td></tr></tbody></table><p id="73454cd9-5953-438d-8ab0-34da8828d6e2" class="">
</p><h2 id="a9e780cc-32f5-4369-a971-022e22c290ac" class="">Endpoints</h2><h3 id="9ddd6b48-1897-4864-a84b-26d6125d11a3" class=""><strong>Users</strong></h3><p id="b1cac1af-fc01-4987-85a9-92af9932e5a1" class=""><strong>/api/users</strong></p><table id="d79eeff4-426c-445e-8318-4c1544cf9030" class="simple-table"><thead class="simple-table-header"><tr id="1241547f-985e-4e93-b9cc-adcedfc513f3"><th id="V_tb" class="simple-table-header-color simple-table-header" style="width:180.00000762939453px">ROLE</th><th id="SWq}" class="simple-table-header-color simple-table-header" style="width:186.00000762939453px">ALLOWED METHODS</th><th id="}oE`" class="simple-table-header-color simple-table-header" style="width:266.9965515136719px">ACTIONS</th><th id="NTnr" class="simple-table-header-color simple-table-header" style="width:409.00001525878906px">RESTRICTIONS WITHIN ALLOWED METHODS</th></tr></thead><tbody><tr id="f35b8b33-3498-4c2b-a616-0dde2628b55c"><td id="V_tb" class="" style="width:180.00000762939453px">Unauthenticated</td><td id="SWq}" class="" style="width:186.00000762939453px">POST</td><td id="}oE`" class="" style="width:266.9965515136719px">Create a new user</td><td id="NTnr" class="" style="width:409.00001525878906px">None</td></tr><tr id="42dec739-0baf-48e0-b84b-23ad89cc0802"><td id="V_tb" class="" style="width:180.00000762939453px">Manager</td><td id="SWq}" class="" style="width:186.00000762939453px">GET, POST</td><td id="}oE`" class="" style="width:266.9965515136719px">Retrieve the list of users and create new users</td><td id="NTnr" class="" style="width:409.00001525878906px">Can’t retrieve the list of Admin users</td></tr><tr id="51fd4825-cf4c-4e19-b5fb-e4f172b4a9ff"><td id="V_tb" class="" style="width:180.00000762939453px">Admin</td><td id="SWq}" class="" style="width:186.00000762939453px">GET, POST</td><td id="}oE`" class="" style="width:266.9965515136719px">Retrieve the list of users and create new users</td><td id="NTnr" class="" style="width:409.00001525878906px">None</td></tr></tbody></table><p id="db4e5c9f-52c0-4f33-8be7-22b4ebd7beb4" class="">Usage:</p><pre id="5584bb02-365b-438a-9ddb-4240d4a6626c" class="code"><code>curl -X GET localhost:8000/api/users \
   -H &#x27;Content-Type: application/json&#x27; \
   -H &quot;Authorization: Bearer {token}&quot;

curl -X POST localhost:8000/api/users \
   -H &#x27;Content-Type: application/json&#x27; \
   -d &#x27;{&quot;username&quot;: &quot;{username}&quot;, &quot;password&quot;: &quot;{password}&quot;, &quot;email&quot;: &quot;{email}&quot;}&#x27;</code></pre><p id="223da84b-a82f-4d94-83e3-625e35ce86f5" class="">
</p><p id="552a37bf-3e2f-4c9f-acf8-aec5afd856f9" class=""><strong>/api/users/{userId}</strong></p><table id="a8df6093-301e-4c6c-9a74-e08b1377ca3b" class="simple-table"><thead class="simple-table-header"><tr id="819b6406-db49-48d5-b05a-9afcbe404ce6"><th id="V_tb" class="simple-table-header-color simple-table-header" style="width:180.00000762939453px">ROLE</th><th id="SWq}" class="simple-table-header-color simple-table-header" style="width:186.00000762939453px">ALLOWED METHODS</th><th id="}oE`" class="simple-table-header-color simple-table-header" style="width:266.9965515136719px">ACTIONS</th><th id="NTnr" class="simple-table-header-color simple-table-header" style="width:409.00001525878906px">RESTRICTIONS WITHIN ALLOWED METHODS</th></tr></thead><tbody><tr id="b986c02a-a522-4ed7-8b5f-55d74648b850"><td id="V_tb" class="" style="width:180.00000762939453px">Customer</td><td id="SWq}" class="" style="width:186.00000762939453px">GET, PATCH, DELETE</td><td id="}oE`" class="" style="width:266.9965515136719px">Retrieve, edit, and delete the user</td><td id="NTnr" class="" style="width:409.00001525878906px">Can’t reach other users</td></tr><tr id="a9b441cd-a44a-4571-ae55-02f86054b47e"><td id="V_tb" class="" style="width:180.00000762939453px">Delivery Crew</td><td id="SWq}" class="" style="width:186.00000762939453px">GET, PATCH, DELETE</td><td id="}oE`" class="" style="width:266.9965515136719px">Retrieve, edit, and delete the user</td><td id="NTnr" class="" style="width:409.00001525878906px">Can’t reach other users</td></tr><tr id="b22b0076-9339-4cfb-bcdd-aeefc4e7fa06"><td id="V_tb" class="" style="width:180.00000762939453px">Manager</td><td id="SWq}" class="" style="width:186.00000762939453px">GET, PATCH, DELETE</td><td id="}oE`" class="" style="width:266.9965515136719px">Retrieve, update, and delete the user</td><td id="NTnr" class="" style="width:409.00001525878906px">Managers can’t edit or delete other managers or admins </td></tr><tr id="6caa9f5d-fb24-4c49-8078-4340df6298f3"><td id="V_tb" class="" style="width:180.00000762939453px">Admin</td><td id="SWq}" class="" style="width:186.00000762939453px">GET, PATCH, DELETE</td><td id="}oE`" class="" style="width:266.9965515136719px">Retrieve, update, and delete the user</td><td id="NTnr" class="" style="width:409.00001525878906px">None</td></tr></tbody></table><p id="3aaa362d-f6cd-4c20-b1ff-98fe6c265fa9" class=""><strong>Usage</strong>:</p><pre id="29e32dab-5414-4f56-88ed-9e584da0a96b" class="code"><code>curl -X GET localhost:8000/api/users/{userId} \
   -H &#x27;Content-Type: application/json&#x27; \
	 -H &quot;Authorization: Bearer {token}&quot; 

curl -X PATCH localhost:8000/api/users/{userId} \
   -H &#x27;Content-Type: application/json&#x27; \
	 -H &quot;Authorization: Bearer {token}&quot;  \
   -d &#x27;{&quot;email&quot;: &quot;{email}&quot;}&#x27;

curl -X DELETE localhost:8000/api/users/{userId} \
   -H &#x27;Content-Type: application/json&#x27; \
	 -H &quot;Authorization: Bearer {token}&quot;</code></pre><h3 id="b4b56b8d-0751-4d79-8686-36c37190f6b4" class="">Sign Up, Log In, and JWT Generation</h3><p id="3d5ffbfc-ca05-494a-96b6-7f71de1cf7ac" class=""><strong>/api/token/login/</strong></p><table id="acefaf22-558e-4521-87f4-e108a826fe05" class="simple-table"><thead class="simple-table-header"><tr id="a02c339d-5108-4f4f-bb5a-38c221aaa79b"><th id="V_tb" class="simple-table-header-color simple-table-header" style="width:180.00000762939453px">ROLE</th><th id="SWq}" class="simple-table-header-color simple-table-header" style="width:186.00000762939453px">ALLOWED METHODS</th><th id="}oE`" class="simple-table-header-color simple-table-header" style="width:266.9965515136719px">ACTIONS</th><th id="NTnr" class="simple-table-header-color simple-table-header" style="width:409.00001525878906px">RESTRICTIONS WITHIN ALLOWED METHODS</th></tr></thead><tbody><tr id="cd5fc8f3-90a2-45cf-87cc-d1006f760cea"><td id="V_tb" class="" style="width:180.00000762939453px">Customer</td><td id="SWq}" class="" style="width:186.00000762939453px">POST</td><td id="}oE`" class="" style="width:266.9965515136719px">Log in and get token authentication and token refresh</td><td id="NTnr" class="" style="width:409.00001525878906px">None</td></tr><tr id="231357e4-5d19-4f1a-b956-53c58508bac8"><td id="V_tb" class="" style="width:180.00000762939453px">Delivery Crew</td><td id="SWq}" class="" style="width:186.00000762939453px">POST</td><td id="}oE`" class="" style="width:266.9965515136719px">Log in and get token authentication and token refresh</td><td id="NTnr" class="" style="width:409.00001525878906px">None</td></tr><tr id="b5f8bf9c-3999-4383-95a2-e94c230c583f"><td id="V_tb" class="" style="width:180.00000762939453px">Manager</td><td id="SWq}" class="" style="width:186.00000762939453px">POST</td><td id="}oE`" class="" style="width:266.9965515136719px">Log in and get token authentication and token refresh</td><td id="NTnr" class="" style="width:409.00001525878906px">None</td></tr><tr id="587ff17b-40fb-40ba-92ee-fb175445a420"><td id="V_tb" class="" style="width:180.00000762939453px">Admin</td><td id="SWq}" class="" style="width:186.00000762939453px">POST</td><td id="}oE`" class="" style="width:266.9965515136719px">Log in and get token authentication and token refresh</td><td id="NTnr" class="" style="width:409.00001525878906px">None</td></tr></tbody></table><p id="273687d4-34c0-42eb-bf21-83b0e16a3c79" class=""><strong>Usage</strong>:</p><pre id="29c24fff-e091-4843-bbde-00fe83c593ad" class="code"><code>curl -X POST localhost:8000/api/token/login/ \
   -H &#x27;Content-Type: application/json&#x27; \
   -d &#x27;{&quot;username&quot;: &quot;{username}&quot;, &quot;password&quot;: &quot;{password}&quot;}&#x27;</code></pre><p id="8342e84d-8066-4bae-9390-5757d840cd56" class="">
</p><p id="f140a49b-ca98-475a-b492-1c947dceba57" class=""><strong>/api/token/refresh/</strong></p><table id="288fd83b-5881-459b-a43b-0f0c2cd7547d" class="simple-table"><thead class="simple-table-header"><tr id="ed56f913-f072-495b-8be7-947da702cb92"><th id="V_tb" class="simple-table-header-color simple-table-header" style="width:180.00000762939453px">ROLE</th><th id="SWq}" class="simple-table-header-color simple-table-header" style="width:186.00000762939453px">ALLOWED METHODS</th><th id="}oE`" class="simple-table-header-color simple-table-header" style="width:266.9965515136719px">ACTIONS</th><th id="NTnr" class="simple-table-header-color simple-table-header" style="width:409.00001525878906px">RESTRICTIONS WITHIN ALLOWED METHODS</th></tr></thead><tbody><tr id="a6b4315b-3430-4566-b0de-34706bd07fb6"><td id="V_tb" class="" style="width:180.00000762939453px">Customer</td><td id="SWq}" class="" style="width:186.00000762939453px">POST</td><td id="}oE`" class="" style="width:266.9965515136719px">Generate a new access token</td><td id="NTnr" class="" style="width:409.00001525878906px">None</td></tr><tr id="699787f8-38f8-4819-a960-deb02b119e44"><td id="V_tb" class="" style="width:180.00000762939453px">Delivery Crew</td><td id="SWq}" class="" style="width:186.00000762939453px">POST</td><td id="}oE`" class="" style="width:266.9965515136719px">Generate a new access token</td><td id="NTnr" class="" style="width:409.00001525878906px">None</td></tr><tr id="d1573170-2b3f-4f06-8335-26744f0bad0a"><td id="V_tb" class="" style="width:180.00000762939453px">Manager</td><td id="SWq}" class="" style="width:186.00000762939453px">POST</td><td id="}oE`" class="" style="width:266.9965515136719px">Generate a new access token</td><td id="NTnr" class="" style="width:409.00001525878906px">None</td></tr><tr id="8960c8fd-f9c5-4a8a-b739-a2ca2aceecf4"><td id="V_tb" class="" style="width:180.00000762939453px">Admin</td><td id="SWq}" class="" style="width:186.00000762939453px">POST</td><td id="}oE`" class="" style="width:266.9965515136719px">Generate a new access token</td><td id="NTnr" class="" style="width:409.00001525878906px">None</td></tr></tbody></table><p id="9dc7e9f5-5691-4dee-abb9-5db45e8c3506" class=""><strong>Usage</strong>:</p><pre id="ac21579b-f017-480e-94bd-de752774e9c1" class="code"><code>curl -X POST localhost:8000/api/token/refresh/ \
   -H &#x27;Content-Type: application/json&#x27; \
   -d &#x27;{&quot;refresh&quot;: &quot;{refreshToken}&quot;}&#x27;</code></pre><p id="36bde688-5a2a-47d6-b600-104f9ce9d74c" class="">
</p><p id="ebb09464-57d4-4d1a-9f41-7cb8583c7ab3" class=""><strong>/api/token/blacklist/</strong></p><table id="ff2a8431-1ddb-46e3-a8ec-bdd48250387a" class="simple-table"><thead class="simple-table-header"><tr id="0d1fb5ce-3dc8-467e-80e1-21da9dbf0502"><th id="V_tb" class="simple-table-header-color simple-table-header" style="width:180.00000762939453px">ROLE</th><th id="SWq}" class="simple-table-header-color simple-table-header" style="width:186.00000762939453px">ALLOWED METHODS</th><th id="}oE`" class="simple-table-header-color simple-table-header" style="width:266.9965515136719px">ACTIONS</th><th id="NTnr" class="simple-table-header-color simple-table-header" style="width:409.00001525878906px">RESTRICTIONS WITHIN ALLOWED METHODS</th></tr></thead><tbody><tr id="db609ebe-711d-4d69-bb9e-e6883a447243"><td id="V_tb" class="" style="width:180.00000762939453px">Manager</td><td id="SWq}" class="" style="width:186.00000762939453px">POST</td><td id="}oE`" class="" style="width:266.9965515136719px">Blacklist the given refresh token</td><td id="NTnr" class="" style="width:409.00001525878906px">Can’t blacklist refresh tokens that belongs to managers or admin</td></tr><tr id="988c7a88-f696-4826-8d36-1a3e5ea483af"><td id="V_tb" class="" style="width:180.00000762939453px">Admin</td><td id="SWq}" class="" style="width:186.00000762939453px">POST</td><td id="}oE`" class="" style="width:266.9965515136719px">Blacklist the given refresh token</td><td id="NTnr" class="" style="width:409.00001525878906px">None</td></tr></tbody></table><p id="3b7db0f5-6214-4b12-b5c4-a787ad9093ac" class=""><strong>Usage</strong>:</p><pre id="60555d1d-341d-4677-94e6-8d1aecf7f28d" class="code"><code>curl -X POST localhost:8000/api/token/blacklist/ \
   -H &#x27;Content-Type: application/json&#x27; \
   -d &#x27;{&quot;refresh&quot;: &quot;{refreshToken}&quot;}&#x27;</code></pre><p id="19a19cad-73bf-4cca-a87a-b8636dcdfff5" class="">
</p><h3 id="e626d49d-4916-4df3-81b7-8c47a4480dff" class="">Groups</h3><p id="658091b4-9cf1-4b89-8418-db1c606993fe" class=""><strong>/api/groups</strong></p><table id="e9f1668c-eba9-4b22-aeac-d871a6721093" class="simple-table"><thead class="simple-table-header"><tr id="17e86fc5-35d2-4f1e-9610-4ae34ad29da3"><th id="V_tb" class="simple-table-header-color simple-table-header" style="width:180.00000762939453px">ROLE</th><th id="SWq}" class="simple-table-header-color simple-table-header" style="width:186.00000762939453px">ALLOWED METHODS</th><th id="}oE`" class="simple-table-header-color simple-table-header" style="width:297.9861145019531px">ACTIONS</th><th id="NTnr" class="simple-table-header-color simple-table-header" style="width:409.00001525878906px">RESTRICTIONS WITHIN ALLOWED METHODS</th></tr></thead><tbody><tr id="d767c04f-442a-41ca-a8fc-ac40ebd931b7"><td id="V_tb" class="" style="width:180.00000762939453px">Manager</td><td id="SWq}" class="" style="width:186.00000762939453px">GET, POST</td><td id="}oE`" class="" style="width:297.9861145019531px">Create and retrieve groups</td><td id="NTnr" class="" style="width:409.00001525878906px">Can’t reach the Admin group</td></tr><tr id="22901c89-19cf-420b-b1a5-a8de3ce7a709"><td id="V_tb" class="" style="width:180.00000762939453px">Admin</td><td id="SWq}" class="" style="width:186.00000762939453px">GET, POST</td><td id="}oE`" class="" style="width:297.9861145019531px">Create and retrieve groups</td><td id="NTnr" class="" style="width:409.00001525878906px">None</td></tr></tbody></table><p id="4978ced8-7880-4549-aab0-a5110fe67785" class=""><strong>Usage</strong>:</p><pre id="8d4588c1-400a-44c6-bf86-305e50e2189d" class="code"><code>curl -X GET localhost:8000/api/groups \
   -H &#x27;Content-Type: application/json&#x27;\
	 -H &quot;Authorization: Bearer {token}&quot; 

curl -X POST localhost:8000/api/groups \
   -H &#x27;Content-Type: application/json&#x27; \
	 -H &quot;Authorization: Bearer {token}&quot;  \
   -d &#x27;{&quot;name&quot;: &quot;{groupName}&quot;}&#x27;</code></pre><p id="530ec474-19c1-4dee-840f-598b2348bd49" class="">
</p><p id="efe0e9b7-e495-4df4-97e1-0c153975022c" class=""><strong>/api/groups/{groupId}</strong></p><table id="8f185306-e1d6-4ae3-85a5-a1d736825ee5" class="simple-table"><thead class="simple-table-header"><tr id="29015490-2cb0-4f3a-8d2d-db1133bfa71a"><th id="V_tb" class="simple-table-header-color simple-table-header" style="width:180.00000762939453px">ROLE</th><th id="SWq}" class="simple-table-header-color simple-table-header" style="width:186.00000762939453px">ALLOWED METHODS</th><th id="}oE`" class="simple-table-header-color simple-table-header" style="width:297.9861145019531px">ACTIONS</th><th id="NTnr" class="simple-table-header-color simple-table-header" style="width:409.00001525878906px">RESTRICTIONS WITHIN ALLOWED METHODS</th></tr></thead><tbody><tr id="8256a5ec-fe1a-498c-8fdd-cafa45997cfc"><td id="V_tb" class="" style="width:180.00000762939453px">Manager</td><td id="SWq}" class="" style="width:186.00000762939453px">GET, PATCH, DELETE</td><td id="}oE`" class="" style="width:297.9861145019531px">Retrieve, edit, and delete a group</td><td id="NTnr" class="" style="width:409.00001525878906px">Can’t edit or delete Manager and Admin groups</td></tr><tr id="2e2d94b7-65a5-4bad-a451-5333a6735f13"><td id="V_tb" class="" style="width:180.00000762939453px">Admin</td><td id="SWq}" class="" style="width:186.00000762939453px">GET, PATCH, DELETE</td><td id="}oE`" class="" style="width:297.9861145019531px">Retrieve, edit, and delete a group</td><td id="NTnr" class="" style="width:409.00001525878906px">None</td></tr></tbody></table><p id="0e53a04c-b9ac-41b5-af6e-0d2d4c625b96" class=""><strong>Usage</strong>:</p><pre id="c9340579-106c-43d3-b99c-23b0bd7a6e3a" class="code"><code>curl -X GET localhost:8000/api/groups/{groupId} \
   -H &#x27;Content-Type: application/json&#x27;
	 -H &quot;Authorization: Bearer {token}&quot; 

curl -X PATCH localhost:8000/api/groups/{groupId} \
   -H &#x27;Content-Type: application/json&#x27;
	 -H &quot;Authorization: Bearer {token}&quot; 
   -d &#x27;{&quot;name&quot;: &quot;{groupName}&quot;}&#x27;

curl -X DELETE localhost:8000/api/groups/{groupId} \
   -H &#x27;Content-Type: application/json&#x27;
	 -H &quot;Authorization: Bearer {token}&quot;</code></pre><h3 id="31132da5-4541-4fc5-8900-b79523375ee6" class="">Group Customer</h3><p id="95434933-cb04-42a6-a67e-4fec2d8b7306" class=""><strong>/api/groups/customer</strong></p><table id="859ca401-9308-4002-bb09-5df41b7470dd" class="simple-table"><thead class="simple-table-header"><tr id="5a3a13c1-0cca-471b-985d-0a03faf9c26c"><th id="V_tb" class="simple-table-header-color simple-table-header" style="width:180.00000762939453px">ROLE</th><th id="SWq}" class="simple-table-header-color simple-table-header" style="width:186.00000762939453px">ALLOWED METHODS</th><th id="}oE`" class="simple-table-header-color simple-table-header" style="width:297.9861145019531px">ACTIONS</th><th id="NTnr" class="simple-table-header-color simple-table-header" style="width:409.00001525878906px">RESTRICTIONS WITHIN ALLOWED METHODS</th></tr></thead><tbody><tr id="e2f4296c-5224-40b0-8537-e6a791916de9"><td id="V_tb" class="" style="width:180.00000762939453px">Manager</td><td id="SWq}" class="" style="width:186.00000762939453px">GET, POST</td><td id="}oE`" class="" style="width:297.9861145019531px">Retrieve the users in the group, add users to the group</td><td id="NTnr" class="" style="width:409.00001525878906px">None</td></tr><tr id="65722798-d941-4bfa-ac5f-e71fd2c7000b"><td id="V_tb" class="" style="width:180.00000762939453px">Admin</td><td id="SWq}" class="" style="width:186.00000762939453px">GET, POST</td><td id="}oE`" class="" style="width:297.9861145019531px">Retrieve the users in the group, add users to the group</td><td id="NTnr" class="" style="width:409.00001525878906px">None</td></tr></tbody></table><p id="680dba8c-efcd-4914-ad4f-7e55bdc4fd56" class=""><strong>Usage</strong>:</p><pre id="95e16129-26eb-452c-a52a-1a993120ae72" class="code"><code>curl -X GET localhost:8000/api/groups/customers \
   -H &#x27;Content-Type: application/json&#x27; \
	 -H &quot;Authorization: Bearer {token}&quot;

curl -X POST localhost:8000/api/groups/customers \
   -H &#x27;Content-Type: application/json&#x27; \
	 -H &quot;Authorization: Bearer {token}&quot;  \
   -d &#x27;{&quot;id&quot;: &quot;{userId}&quot;}&#x27;</code></pre><p id="fe2100fa-d9e9-4bcc-98b3-a3f52287769a" class="">
</p><p id="ca890f98-1427-464e-bae8-35de2b4c8e43" class=""><strong>/api/groups/customers/{userId}</strong></p><table id="0046080c-6b9a-4ea6-ab4d-a1c05dec4363" class="simple-table"><thead class="simple-table-header"><tr id="11c853e0-5328-4e3e-a709-c6704f2505f6"><th id="V_tb" class="simple-table-header-color simple-table-header" style="width:180.00000762939453px">ROLE</th><th id="SWq}" class="simple-table-header-color simple-table-header" style="width:186.00000762939453px">ALLOWED METHODS</th><th id="}oE`" class="simple-table-header-color simple-table-header" style="width:297.9861145019531px">ACTIONS</th><th id="NTnr" class="simple-table-header-color simple-table-header" style="width:409.00001525878906px">RESTRICTIONS WITHIN ALLOWED METHODS</th></tr></thead><tbody><tr id="36ae1c77-7f5e-49d8-9470-292c6d19862a"><td id="V_tb" class="" style="width:180.00000762939453px">Manager</td><td id="SWq}" class="" style="width:186.00000762939453px">GET, PUT, PATCH, DELETE</td><td id="}oE`" class="" style="width:297.9861145019531px">Retrieve, edit, and delete a user</td><td id="NTnr" class="" style="width:409.00001525878906px">None</td></tr><tr id="aa85f72f-93a2-4018-8aa3-8331e74a43b6"><td id="V_tb" class="" style="width:180.00000762939453px">Admin</td><td id="SWq}" class="" style="width:186.00000762939453px">GET, POST</td><td id="}oE`" class="" style="width:297.9861145019531px">Retrieve, edit, and delete a user</td><td id="NTnr" class="" style="width:409.00001525878906px">None</td></tr></tbody></table><p id="4fc0ba03-6ed2-40b7-8154-1bd3be2f59b0" class=""><strong>Usage</strong>:</p><pre id="ac9e7c97-bf17-43f8-abb9-f185483c68ea" class="code"><code>curl -X GET localhost:8000/api/groups/customers/{userId} \
   -H &#x27;Content-Type: application/json&#x27; \
	 -H &quot;Authorization: Bearer {token}&quot; 

curl -X PATCH localhost:8000/api/groups/customers/{userId} \
   -H &#x27;Content-Type: application/json&#x27; \
	 -H &quot;Authorization: Bearer {token}&quot;  \
   -d &#x27;{&quot;username&quot;: &quot;{username}&quot;}&#x27;

curl -X DELETE localhost:8000/api/groups/customers/{userId} \
   -H &#x27;Content-Type: application/json&#x27; \
	 -H &quot;Authorization: Bearer {token}&quot; </code></pre><h3 id="27638440-6204-4968-bc05-5c9e1ee4f207" class="">Group Delivery Crew</h3><p id="4de2c3a9-a03d-4ca4-92b4-1f44163bcd12" class=""><strong>/api/groups/delivery-crew</strong></p><table id="277a6c40-a816-4b60-9670-0f6e23b6a698" class="simple-table"><thead class="simple-table-header"><tr id="f1eb246d-dbb7-4d98-8e08-1216e596fba4"><th id="V_tb" class="simple-table-header-color simple-table-header" style="width:180.00000762939453px">ROLE</th><th id="SWq}" class="simple-table-header-color simple-table-header" style="width:186.00000762939453px">ALLOWED METHODS</th><th id="}oE`" class="simple-table-header-color simple-table-header" style="width:297.9861145019531px">ACTIONS</th><th id="NTnr" class="simple-table-header-color simple-table-header" style="width:409.00001525878906px">RESTRICTIONS WITHIN ALLOWED METHODS</th></tr></thead><tbody><tr id="0ce17aec-4799-45f5-8e09-5f42359c6b7e"><td id="V_tb" class="" style="width:180.00000762939453px">Manager</td><td id="SWq}" class="" style="width:186.00000762939453px">GET, POST</td><td id="}oE`" class="" style="width:297.9861145019531px">Retrieve the users in the group, add users to the group</td><td id="NTnr" class="" style="width:409.00001525878906px">None</td></tr><tr id="03c5753c-a17d-4108-99d1-12dbb45d91b8"><td id="V_tb" class="" style="width:180.00000762939453px">Admin</td><td id="SWq}" class="" style="width:186.00000762939453px">GET, POST</td><td id="}oE`" class="" style="width:297.9861145019531px">Retrieve the users in the group, add users to the group</td><td id="NTnr" class="" style="width:409.00001525878906px">None</td></tr></tbody></table><p id="a0ca66ff-4a50-4e79-82d7-560969d2c52b" class=""><strong>Usage</strong>:</p><pre id="ebb3b087-bed1-43b9-8801-ae199940dc20" class="code"><code>curl -X GET localhost:8000/api/groups/delivery-crew \
   -H &#x27;Content-Type: application/json&#x27; \
	 -H &quot;Authorization: Bearer {token}&quot;

curl -X POST localhost:8000/api/groups/delivery-crew \
   -H &#x27;Content-Type: application/json&#x27; \
	 -H &quot;Authorization: Bearer {token}&quot;  \
   -d &#x27;{&quot;id&quot;: &quot;{userId}&quot;}&#x27;</code></pre><p id="b2ac3fbe-4925-4172-bc0f-6816cae9f8ea" class="">
</p><p id="d99e0a10-70ff-4e38-86d2-2ddc7d156b78" class=""><strong>/api/groups/delivery-crew/{userId}</strong></p><table id="94242482-0e9b-4624-a3d5-6fa136cff72f" class="simple-table"><thead class="simple-table-header"><tr id="a7bb6618-9053-47d6-8235-7bd3cd26165e"><th id="V_tb" class="simple-table-header-color simple-table-header" style="width:180.00000762939453px">ROLE</th><th id="SWq}" class="simple-table-header-color simple-table-header" style="width:186.00000762939453px">ALLOWED METHODS</th><th id="}oE`" class="simple-table-header-color simple-table-header" style="width:297.9861145019531px">ACTIONS</th><th id="NTnr" class="simple-table-header-color simple-table-header" style="width:409.00001525878906px">RESTRICTIONS WITHIN ALLOWED METHODS</th></tr></thead><tbody><tr id="833ce563-8f45-4930-a726-0c8a43f6cc64"><td id="V_tb" class="" style="width:180.00000762939453px">Delivery Crew</td><td id="SWq}" class="" style="width:186.00000762939453px">GET, PATCH, DELETE</td><td id="}oE`" class="" style="width:297.9861145019531px">Retrieve, edit, and delete a user</td><td id="NTnr" class="" style="width:409.00001525878906px">A delivery crew can only reach its own user </td></tr><tr id="b23288b3-df5a-43a0-b5fd-f4a30697ba53"><td id="V_tb" class="" style="width:180.00000762939453px">Manager</td><td id="SWq}" class="" style="width:186.00000762939453px">GET, PATCH, DELETE</td><td id="}oE`" class="" style="width:297.9861145019531px">Retrieve, edit, and delete a user</td><td id="NTnr" class="" style="width:409.00001525878906px">None</td></tr><tr id="f4e2f9d5-f643-4da9-baab-25d4e40a159a"><td id="V_tb" class="" style="width:180.00000762939453px">Admin</td><td id="SWq}" class="" style="width:186.00000762939453px">GET, PATCH, DELETE</td><td id="}oE`" class="" style="width:297.9861145019531px">Retrieve, edit, and delete a user</td><td id="NTnr" class="" style="width:409.00001525878906px">None</td></tr></tbody></table><p id="4b9c8342-071e-42ba-a1fb-4df949e31738" class=""><strong>Usage</strong>:</p><pre id="2e8f1a49-0a19-4a31-b8c4-3c01ab06d9bd" class="code"><code>curl -X GET localhost:8000/api/groups/delivery-crew/{userId} \
   -H &#x27;Content-Type: application/json&#x27; \
	 -H &quot;Authorization: Bearer {token}&quot;

curl -X PATCH localhost:8000/api/groups/delivery-crew/{userId} \
   -H &#x27;Content-Type: application/json&#x27; \
	 -H &quot;Authorization: Bearer {token}&quot;  \
   -d &#x27;{&quot;username&quot;: &quot;{username}&quot;}&#x27;

curl -X DELETE localhost:8000/api/groups/delivery-crew/{userId} \
   -H &#x27;Content-Type: application/json&#x27; \
	 -H &quot;Authorization: Bearer {token}&quot;</code></pre><h3 id="9148cb03-2dd4-4ed6-bf15-722fdf00e65e" class="">Group Manager</h3><p id="cba53f79-69e2-4918-887d-adf35f6fcf6c" class=""><strong>/api/groups/managers</strong></p><table id="8357727f-dae6-4f74-91e6-cde60f5f149f" class="simple-table"><thead class="simple-table-header"><tr id="f0268c8c-e53b-4130-a5f6-ab5ff53c3cd0"><th id="V_tb" class="simple-table-header-color simple-table-header" style="width:180.00000762939453px">ROLE</th><th id="SWq}" class="simple-table-header-color simple-table-header" style="width:186.00000762939453px">ALLOWED METHODS</th><th id="}oE`" class="simple-table-header-color simple-table-header" style="width:297.9861145019531px">ACTIONS</th><th id="NTnr" class="simple-table-header-color simple-table-header" style="width:409.00001525878906px">RESTRICTIONS WITHIN ALLOWED METHODS</th></tr></thead><tbody><tr id="aa34a6cf-44e8-403b-9138-3c472573f9ff"><td id="V_tb" class="" style="width:180.00000762939453px">Manager</td><td id="SWq}" class="" style="width:186.00000762939453px">GET, POST</td><td id="}oE`" class="" style="width:297.9861145019531px">Retrieve the users in the group, add users to the group</td><td id="NTnr" class="" style="width:409.00001525878906px">None</td></tr><tr id="85ab1a80-704b-4cb1-9640-a8c00ced223e"><td id="V_tb" class="" style="width:180.00000762939453px">Admin</td><td id="SWq}" class="" style="width:186.00000762939453px">GET, POST</td><td id="}oE`" class="" style="width:297.9861145019531px">Retrieve the users in the group, add users to the group</td><td id="NTnr" class="" style="width:409.00001525878906px">None</td></tr></tbody></table><p id="c0234f1c-6fd8-46db-89fd-7804de63b375" class=""><strong>Usage</strong>:</p><pre id="f001a22b-8695-4ff4-ab22-71cf06dfafa1" class="code"><code>curl -X GET localhost:8000/api/groups/managers \
   -H &#x27;Content-Type: application/json&#x27; \
	 -H &quot;Authorization: Bearer {token}&quot;

curl -X POST localhost:8000/api/groups/managers \
   -H &#x27;Content-Type: application/json&#x27; \
	 -H &quot;Authorization: Bearer {token}&quot;  \
   -d &#x27;{&quot;id&quot;: &quot;{userId}&quot;}&#x27;</code></pre><p id="a6c9d762-54d6-4a7e-9036-9dd112ff79a1" class="">
</p><p id="0f65586e-e416-4175-b490-e7dfb90722ad" class=""><strong>/api/groups/managers/{userId}</strong></p><table id="f58084ba-b713-4b55-9199-8a51a1a0152d" class="simple-table"><thead class="simple-table-header"><tr id="ffb05549-b872-46b9-8b71-770382e9a321"><th id="V_tb" class="simple-table-header-color simple-table-header" style="width:180.00000762939453px">ROLE</th><th id="SWq}" class="simple-table-header-color simple-table-header" style="width:186.00000762939453px">ALLOWED METHODS</th><th id="}oE`" class="simple-table-header-color simple-table-header" style="width:297.9861145019531px">ACTIONS</th><th id="NTnr" class="simple-table-header-color simple-table-header" style="width:409.00001525878906px">RESTRICTIONS WITHIN ALLOWED METHODS</th></tr></thead><tbody><tr id="87ebdb07-2981-46b7-afec-f186dc15a5e5"><td id="V_tb" class="" style="width:180.00000762939453px">Manager</td><td id="SWq}" class="" style="width:186.00000762939453px">GET</td><td id="}oE`" class="" style="width:297.9861145019531px">Retrieve user details</td><td id="NTnr" class="" style="width:409.00001525878906px">None</td></tr><tr id="cda96374-403b-4530-84e0-bfea55e1cbb6"><td id="V_tb" class="" style="width:180.00000762939453px">Admin</td><td id="SWq}" class="" style="width:186.00000762939453px">GET, PATCH, DELETE</td><td id="}oE`" class="" style="width:297.9861145019531px">Retrieve, edit, and delete the user</td><td id="NTnr" class="" style="width:409.00001525878906px">None</td></tr></tbody></table><p id="e1f4852a-5a7b-4fc9-a59c-2dc506a2c44b" class=""><strong>Usage</strong>:</p><pre id="aa40bad9-9fc6-4cbd-9a7a-55cad34d6e6b" class="code"><code>curl -X GET localhost:8000/api/groups/managers/{userId} \
   -H &#x27;Content-Type: application/json&#x27; \
	 -H &quot;Authorization: Bearer {token}&quot;

curl -X PATCH localhost:8000/api/groups/managers/{userId} \
   -H &#x27;Content-Type: application/json&#x27; \
	 -H &quot;Authorization: Bearer {token}&quot;  \
   -d &#x27;{&quot;username&quot;: &quot;{username}&quot;}&#x27;

curl -X DELETE localhost:8000/api/groups/managers/{userId} \
   -H &#x27;Content-Type: application/json&#x27; \
	 -H &quot;Authorization: Bearer {token}&quot;</code></pre><h3 id="5abe5e82-28ef-4421-b16f-657999552480" class="">Group Admin</h3><p id="929ca5af-36b9-40f0-a956-db961e6399d4" class=""><strong>/api/groups/admins</strong></p><table id="2fa41a63-3660-4301-9ff4-bbb3323155bc" class="simple-table"><thead class="simple-table-header"><tr id="55f33827-1ca5-444d-b786-d75b4fb1f726"><th id="V_tb" class="simple-table-header-color simple-table-header" style="width:180.00000762939453px">ROLE</th><th id="SWq}" class="simple-table-header-color simple-table-header" style="width:186.00000762939453px">ALLOWED METHODS</th><th id="}oE`" class="simple-table-header-color simple-table-header" style="width:297.9861145019531px">ACTIONS</th><th id="NTnr" class="simple-table-header-color simple-table-header" style="width:409.00001525878906px">RESTRICTIONS WITHIN ALLOWED METHODS</th></tr></thead><tbody><tr id="8e3f526e-1253-441b-b80a-d48720c348b3"><td id="V_tb" class="" style="width:180.00000762939453px">Admin</td><td id="SWq}" class="" style="width:186.00000762939453px">GET, POST</td><td id="}oE`" class="" style="width:297.9861145019531px">Retrieve the users in the group, add users to the group</td><td id="NTnr" class="" style="width:409.00001525878906px">None</td></tr></tbody></table><p id="c4b9ab9c-d927-45de-aee3-676e7d7d8c61" class=""><strong>Usage</strong>:</p><pre id="c34c3267-6211-4eae-b56c-1ec46d6131a1" class="code"><code>curl -X GET localhost:8000/api/groups/admins \
   -H &#x27;Content-Type: application/json&#x27; \
	 -H &quot;Authorization: Bearer {token}&quot;

curl -X POST localhost:8000/api/groups/admins \
   -H &#x27;Content-Type: application/json&#x27; \
	 -H &quot;Authorization: Bearer {token}&quot;  \
   -d &#x27;{&quot;id&quot;: &quot;{userId}&quot;}&#x27;</code></pre><p id="37be9ee1-af33-48d6-864d-1320c5238988" class="">
</p><p id="40749609-7c0b-4e6f-96a0-02a49f0b9bca" class=""><strong>/api/groups/admins/{userId}</strong></p><table id="dbb1e761-9a6e-461c-9b43-e2dc3b1870cf" class="simple-table"><thead class="simple-table-header"><tr id="7558197a-6d6c-4774-9455-0cb785a6ec3b"><th id="V_tb" class="simple-table-header-color simple-table-header" style="width:180.00000762939453px">ROLE</th><th id="SWq}" class="simple-table-header-color simple-table-header" style="width:186.00000762939453px">ALLOWED METHODS</th><th id="}oE`" class="simple-table-header-color simple-table-header" style="width:297.9861145019531px">ACTIONS</th><th id="NTnr" class="simple-table-header-color simple-table-header" style="width:409.00001525878906px">RESTRICTIONS WITHIN ALLOWED METHODS</th></tr></thead><tbody><tr id="06629e07-37ea-4156-8ac8-c2a5c107352d"><td id="V_tb" class="" style="width:180.00000762939453px">Admin</td><td id="SWq}" class="" style="width:186.00000762939453px">GET, PUT, PATCH, DELETE</td><td id="}oE`" class="" style="width:297.9861145019531px">Retrieve, edit, and delete the user</td><td id="NTnr" class="" style="width:409.00001525878906px">None</td></tr></tbody></table><p id="62412ba1-08d0-4c8c-9129-c91ddde69753" class=""><strong>Usage</strong>:</p><pre id="424b4ced-69ab-461b-a926-22e84a47e105" class="code"><code>curl -X GET localhost:8000/api/groups/admins/{userId} \
   -H &#x27;Content-Type: application/json&#x27; \
	 -H &quot;Authorization: Bearer {token}&quot;

curl -X PATCH localhost:8000/api/groups/admins/{userId} \
   -H &#x27;Content-Type: application/json&#x27; \
	 -H &quot;Authorization: Bearer {token}&quot;  \
   -d &#x27;{&quot;username&quot;: &quot;{username}&quot;}&#x27;

curl -X DELETE localhost:8000/api/groups/admins/{userId} \
   -H &#x27;Content-Type: application/json&#x27; \
	 -H &quot;Authorization: Bearer {token}&quot;</code></pre><h3 id="03dc9c88-c158-4949-945e-2731cc8e1253" class="">Menu Items</h3><p id="d2965f90-ad6a-43ca-87da-da6834ac72ed" class=""><strong>/api/menu-items</strong></p><table id="67ea83f4-565c-4a8d-824e-342e707ed246" class="simple-table"><thead class="simple-table-header"><tr id="3d4f9946-20dd-4b9a-8c22-0d77afdac3f5"><th id="V_tb" class="simple-table-header-color simple-table-header" style="width:180.00000762939453px">ROLE</th><th id="SWq}" class="simple-table-header-color simple-table-header" style="width:186.00000762939453px">ALLOWED METHODS</th><th id="}oE`" class="simple-table-header-color simple-table-header" style="width:297.9861145019531px">ACTIONS</th><th id="NTnr" class="simple-table-header-color simple-table-header" style="width:409.00001525878906px">RESTRICTIONS WITHIN ALLOWED METHODS</th></tr></thead><tbody><tr id="629f28cc-2788-4236-a4eb-4927d8ad1eaa"><td id="V_tb" class="" style="width:180.00000762939453px">Customer</td><td id="SWq}" class="" style="width:186.00000762939453px">GET</td><td id="}oE`" class="" style="width:297.9861145019531px">Retrieve the list of menu-items</td><td id="NTnr" class="" style="width:409.00001525878906px">None</td></tr><tr id="9268d395-8e2a-4087-960c-064b6d70edb6"><td id="V_tb" class="" style="width:180.00000762939453px">Delivery Crew</td><td id="SWq}" class="" style="width:186.00000762939453px">GET</td><td id="}oE`" class="" style="width:297.9861145019531px">Retrieve the list of menu-items</td><td id="NTnr" class="" style="width:409.00001525878906px">None</td></tr><tr id="01955d7a-8ed2-4526-8653-8846f75b011b"><td id="V_tb" class="" style="width:180.00000762939453px">Manager</td><td id="SWq}" class="" style="width:186.00000762939453px">GET, POST</td><td id="}oE`" class="" style="width:297.9861145019531px">Retrieve the list of menu-items, add new menu-items</td><td id="NTnr" class="" style="width:409.00001525878906px">None</td></tr><tr id="30b7e4d4-779f-4a79-ae4d-e654eb43729d"><td id="V_tb" class="" style="width:180.00000762939453px">Admin</td><td id="SWq}" class="" style="width:186.00000762939453px">GET, POST</td><td id="}oE`" class="" style="width:297.9861145019531px">Retrieve the list of menu-items, add new menu-items</td><td id="NTnr" class="" style="width:409.00001525878906px">None</td></tr></tbody></table><p id="82e8cd0f-b2cd-4608-aaea-dd5f51c5d261" class=""><strong>Usage</strong>:</p><pre id="9c40946c-9246-4a9b-bf9f-cb7df1baa179" class="code"><code>curl -X GET localhost:8000/api/menu-items \
   -H &#x27;Content-Type: application/json&#x27;    \
	 -H &quot;Authorization: Bearer {token}&quot;

curl -X POST localhost:8000/api/menu-items \
   -H &#x27;Content-Type: application/json&#x27;     \
	 -H &quot;Authorization: Bearer {token}&quot;      \
	 -d &#x27;{&quot;title&quot;: &quot;{title}&quot;, &quot;price&quot;: &quot;{value}&quot;, &quot;feature&quot;: &quot;{value}&quot;, &quot;category_id&quot;: &quot;{id}&quot;}&#x27;</code></pre><p id="57a40625-3734-4837-9f4c-200ca98ed8f1" class="">
</p><p id="cca99ba9-8ca9-4a7b-8299-6d291efe17fb" class=""><strong>/api/menu-items/{menu-itemId}</strong></p><table id="14ea8098-3939-4af0-82b7-c9d0f9c51089" class="simple-table"><thead class="simple-table-header"><tr id="65338afd-c698-4804-8ebf-d2e6f54b4890"><th id="V_tb" class="simple-table-header-color simple-table-header" style="width:180.00000762939453px">ROLE</th><th id="SWq}" class="simple-table-header-color simple-table-header" style="width:186.00000762939453px">ALLOWED METHODS</th><th id="}oE`" class="simple-table-header-color simple-table-header" style="width:297.9861145019531px">ACTIONS</th><th id="NTnr" class="simple-table-header-color simple-table-header" style="width:409.00001525878906px">RESTRICTIONS WITHIN ALLOWED METHODS</th></tr></thead><tbody><tr id="0fcd1843-0de1-45ad-a2f4-e86abddc1e85"><td id="V_tb" class="" style="width:180.00000762939453px">Customer</td><td id="SWq}" class="" style="width:186.00000762939453px">GET</td><td id="}oE`" class="" style="width:297.9861145019531px">Retrieve menu-item details</td><td id="NTnr" class="" style="width:409.00001525878906px">None</td></tr><tr id="4cd0d2ac-2747-4021-a0f8-4077b042d98d"><td id="V_tb" class="" style="width:180.00000762939453px">Delivery Crew</td><td id="SWq}" class="" style="width:186.00000762939453px">GET</td><td id="}oE`" class="" style="width:297.9861145019531px">Retrieve menu-item details</td><td id="NTnr" class="" style="width:409.00001525878906px">None</td></tr><tr id="090b449f-b215-4d04-b775-9019b37efa50"><td id="V_tb" class="" style="width:180.00000762939453px">Manager</td><td id="SWq}" class="" style="width:186.00000762939453px">GET, PATCH, DELETE</td><td id="}oE`" class="" style="width:297.9861145019531px">Retrieve, edit, and delete the menu-item</td><td id="NTnr" class="" style="width:409.00001525878906px">None</td></tr><tr id="68b86d1c-2ecf-44fa-84c6-fa32a30b57d3"><td id="V_tb" class="" style="width:180.00000762939453px">Admin</td><td id="SWq}" class="" style="width:186.00000762939453px">GET, PATCH, DELETE</td><td id="}oE`" class="" style="width:297.9861145019531px">Retrieve, edit, and delete the menu-item</td><td id="NTnr" class="" style="width:409.00001525878906px">None</td></tr></tbody></table><p id="ca439e22-40b8-4f7f-aee3-384eb441e72e" class=""><strong>Usage</strong>:</p><pre id="6dde3d1f-50c6-4563-aa8a-2b301d3efc2d" class="code"><code>curl -X GET localhost:8000/api/menu-items/{menu-itemId} \
   -H &#x27;Content-Type: application/json&#x27;    \
	 -H &quot;Authorization: Bearer {token}&quot;

curl -X PATCH localhost:8000/api/menu-items/{menu-itemId} \
   -H &#x27;Content-Type: application/json&#x27;     \
	 -H &quot;Authorization: Bearer {token}&quot;      \
	 -d &#x27;{&quot;title&quot;: &quot;{title}&quot;, &quot;price&quot;: &quot;{value}&quot;, &quot;feature&quot;: &quot;{value}&quot;, &quot;category_id&quot;: &quot;{id}&quot;}&#x27;

curl -X DELETE localhost:8000/api/menu-items/{menu-itemId} \
   -H &#x27;Content-Type: application/json&#x27;    \
	 -H &quot;Authorization: Bearer {token}&quot;</code></pre><h3 id="30d5c1d7-c28b-4584-9aca-1f80f8e8ce00" class="">Categories</h3><p id="dc515e76-9e23-4034-8324-cd0d7ec2a857" class=""><strong>/api/categories</strong></p><table id="6d38dc45-c2f9-43ac-9b31-2cecda375762" class="simple-table"><thead class="simple-table-header"><tr id="e1e337ed-40a4-4e65-93c8-be407c424354"><th id="V_tb" class="simple-table-header-color simple-table-header" style="width:180.00000762939453px">ROLE</th><th id="SWq}" class="simple-table-header-color simple-table-header" style="width:186.00000762939453px">ALLOWED METHODS</th><th id="}oE`" class="simple-table-header-color simple-table-header" style="width:297.9861145019531px">ACTIONS</th><th id="NTnr" class="simple-table-header-color simple-table-header" style="width:409.00001525878906px">RESTRICTIONS WITHIN ALLOWED METHODS</th></tr></thead><tbody><tr id="58f15316-0991-4a5c-acc8-a7e2800d87dc"><td id="V_tb" class="" style="width:180.00000762939453px">Customer</td><td id="SWq}" class="" style="width:186.00000762939453px">GET</td><td id="}oE`" class="" style="width:297.9861145019531px">Retrieve the list of categories</td><td id="NTnr" class="" style="width:409.00001525878906px">None</td></tr><tr id="143a3039-c4d6-4611-afa3-39f967427284"><td id="V_tb" class="" style="width:180.00000762939453px">Delivery Crew</td><td id="SWq}" class="" style="width:186.00000762939453px">GET</td><td id="}oE`" class="" style="width:297.9861145019531px">Retrieve the list of categories</td><td id="NTnr" class="" style="width:409.00001525878906px">None</td></tr><tr id="4ddb387c-950b-49a8-86be-6deb63d072ff"><td id="V_tb" class="" style="width:180.00000762939453px">Manager</td><td id="SWq}" class="" style="width:186.00000762939453px">GET, POST</td><td id="}oE`" class="" style="width:297.9861145019531px">Retrieve the list of categories, add new categories</td><td id="NTnr" class="" style="width:409.00001525878906px">None</td></tr><tr id="d298fea2-bc6a-46d4-bd1a-30d7169df5ac"><td id="V_tb" class="" style="width:180.00000762939453px">Admin</td><td id="SWq}" class="" style="width:186.00000762939453px">GET, POST</td><td id="}oE`" class="" style="width:297.9861145019531px">Retrieve the list of categories, add new categories</td><td id="NTnr" class="" style="width:409.00001525878906px">None</td></tr></tbody></table><p id="25525816-2814-4415-b38f-2a5dfacbec0e" class=""><strong>Usage</strong>:</p><pre id="55f3bf7f-b54c-41a9-b941-18e6bc2f7373" class="code"><code>curl -X GET localhost:8000/api/categories \
   -H &#x27;Content-Type: application/json&#x27;    \
	 -H &quot;Authorization: Bearer {token}&quot;

curl -X POST localhost:8000/api/categories \
   -H &#x27;Content-Type: application/json&#x27;     \
	 -H &quot;Authorization: Bearer {token}&quot;      \
	 -d &#x27;{&quot;title&quot;: &quot;{title}&quot;, &quot;slug&quot;: &quot;{slug}&quot;}&#x27;</code></pre><p id="c7f6b8b7-a24c-45cd-abe1-1c3fcf9c6d78" class="">
</p><p id="1e7e08ff-9d9d-432c-b8c2-eb9b0bfc5877" class=""><strong>/api/categories/{categoryId}</strong></p><table id="d98d1c81-60f5-4d2e-aeeb-5992a3ef20a7" class="simple-table"><thead class="simple-table-header"><tr id="97efd6cf-8b7f-47ad-a826-e63f5ca7cd49"><th id="V_tb" class="simple-table-header-color simple-table-header" style="width:180.00000762939453px">ROLE</th><th id="SWq}" class="simple-table-header-color simple-table-header" style="width:186.00000762939453px">ALLOWED METHODS</th><th id="}oE`" class="simple-table-header-color simple-table-header" style="width:297.9861145019531px">ACTIONS</th><th id="NTnr" class="simple-table-header-color simple-table-header" style="width:409.00001525878906px">RESTRICTIONS WITHIN ALLOWED METHODS</th></tr></thead><tbody><tr id="f3fd2070-35db-46ac-b848-7472fdb306a4"><td id="V_tb" class="" style="width:180.00000762939453px">Customer</td><td id="SWq}" class="" style="width:186.00000762939453px">GET</td><td id="}oE`" class="" style="width:297.9861145019531px">Retrieve category details</td><td id="NTnr" class="" style="width:409.00001525878906px">None</td></tr><tr id="2e66d267-b561-47aa-9be0-1fb46463437b"><td id="V_tb" class="" style="width:180.00000762939453px">Delivery Crew</td><td id="SWq}" class="" style="width:186.00000762939453px">GET</td><td id="}oE`" class="" style="width:297.9861145019531px">Retrieve category details</td><td id="NTnr" class="" style="width:409.00001525878906px">None</td></tr><tr id="0fba963d-7f93-4f6c-b289-505979f0d888"><td id="V_tb" class="" style="width:180.00000762939453px">Manager</td><td id="SWq}" class="" style="width:186.00000762939453px">GET, PATCH, DELETE</td><td id="}oE`" class="" style="width:297.9861145019531px">Retrieve, edit, and delete the category</td><td id="NTnr" class="" style="width:409.00001525878906px">None</td></tr><tr id="6e7d1465-2875-446a-888a-8a2a6569af1e"><td id="V_tb" class="" style="width:180.00000762939453px">Admin</td><td id="SWq}" class="" style="width:186.00000762939453px">GET, PATCH, DELETE</td><td id="}oE`" class="" style="width:297.9861145019531px">Retrieve, edit, and delete the category</td><td id="NTnr" class="" style="width:409.00001525878906px">None</td></tr></tbody></table><p id="c6ad4523-1ade-469f-a47a-aea0333484ac" class=""><strong>Usage</strong>:</p><pre id="20b9ce52-f6ec-42b7-aba8-25bfb9f8a14b" class="code"><code>curl -X GET localhost:8000/api/categories/{categoryId} \
   -H &#x27;Content-Type: application/json&#x27;                 \
	 -H &quot;Authorization: Bearer {token}&quot;

curl -X PATCH localhost:8000/api/categories/{categoryId} \
   -H &#x27;Content-Type: application/json&#x27;                   \ 
	 -H &quot;Authorization: Bearer {token}&quot;                    \
	 -d &#x27;{&quot;title&quot;: &quot;{title}&quot;, &quot;slug&quot;: &quot;{slug}&quot;}&#x27;

curl -X DELETE localhost:8000/api/categories/{categoryId} \
   -H &#x27;Content-Type: application/json&#x27;                   \
	 -H &quot;Authorization: Bearer {token}&quot; </code></pre><h3 id="8b00dd37-9a76-4bc6-add4-a82724e3690c" class="">Order Items</h3><p id="842a2262-0a94-4a43-96a7-2e24731aeb45" class=""><strong>/api/order-items</strong></p><table id="0ccbb414-69d7-4763-81fc-82c8cb2d2953" class="simple-table"><thead class="simple-table-header"><tr id="b8dcedbd-230e-4fc1-b64e-e54cfc3459d8"><th id="V_tb" class="simple-table-header-color simple-table-header" style="width:180.00000762939453px">ROLE</th><th id="SWq}" class="simple-table-header-color simple-table-header" style="width:186.00000762939453px">ALLOWED METHODS</th><th id="}oE`" class="simple-table-header-color simple-table-header" style="width:297.9861145019531px">ACTIONS</th><th id="NTnr" class="simple-table-header-color simple-table-header" style="width:409.00001525878906px">RESTRICTIONS WITHIN ALLOWED METHODS</th></tr></thead><tbody><tr id="29c3c22b-abfc-4a9c-81ec-3ad6c4cc2efd"><td id="V_tb" class="" style="width:180.00000762939453px">Customer</td><td id="SWq}" class="" style="width:186.00000762939453px">GET, POST</td><td id="}oE`" class="" style="width:297.9861145019531px">Retrieve users’ order-items, create a new order-item</td><td id="NTnr" class="" style="width:409.00001525878906px">Other users’ order-items are unreachable</td></tr><tr id="25d42920-e01c-447a-b8d1-aaefb133bf5c"><td id="V_tb" class="" style="width:180.00000762939453px">Manager</td><td id="SWq}" class="" style="width:186.00000762939453px">GET, POST</td><td id="}oE`" class="" style="width:297.9861145019531px">Retrieve users’ order-items, create a new order-item</td><td id="NTnr" class="" style="width:409.00001525878906px">None</td></tr><tr id="a1038720-7bc7-4d59-beea-2343d7f2664b"><td id="V_tb" class="" style="width:180.00000762939453px">Admin</td><td id="SWq}" class="" style="width:186.00000762939453px">GET, POST</td><td id="}oE`" class="" style="width:297.9861145019531px">Retrieve users’ order-items, create a new order-item</td><td id="NTnr" class="" style="width:409.00001525878906px">None</td></tr></tbody></table><p id="143faa8f-72d7-4b3f-89da-ed33ea8256a6" class=""><strong>Note</strong>:</p><p id="846ad50f-ef9b-4fa7-a010-f93640b6ef9e" class="">While creating an order-item the default user will be automatically set to the currently logged user. If a manager or and admin creates an order-item, they should edit it in order to change the user assigned to that order-item.</p><p id="f013c853-83c5-4772-9664-c3206d6b8a61" class=""><strong>Usage</strong>:</p><pre id="1a7c4db1-739a-465f-8123-8792da3268b4" class="code"><code>curl -X GET localhost:8000/api/order-items \
   -H &#x27;Content-Type: application/json&#x27;     \
	 -H &quot;Authorization: Bearer {token}&quot;

curl -X POST localhost:8000/api/order-items \
   -H &#x27;Content-Type: application/json&#x27;      \
	 -H &quot;Authorization: Bearer {token}&quot;       \
   -d &#x27;{&quot;id&quot;: &quot;{menu-itemId}&quot;, &quot;quantity&quot;: &quot;{value}&quot;}&#x27;</code></pre><p id="a70ee366-63c3-4834-afb9-371f5aeb4b43" class="">
</p><p id="88b83f0b-2da7-4a02-954b-3f49fd52034f" class=""><strong>/api/order-items/{order-itemId}</strong></p><table id="99a11345-bead-44c0-bf75-c97518b85a58" class="simple-table"><thead class="simple-table-header"><tr id="26a7150a-29d6-4f8d-8d92-1c8369dd8b04"><th id="V_tb" class="simple-table-header-color simple-table-header" style="width:180.00000762939453px">ROLE</th><th id="SWq}" class="simple-table-header-color simple-table-header" style="width:186.00000762939453px">ALLOWED METHODS</th><th id="}oE`" class="simple-table-header-color simple-table-header" style="width:297.9861145019531px">ACTIONS</th><th id="NTnr" class="simple-table-header-color simple-table-header" style="width:409.00001525878906px">RESTRICTIONS WITHIN ALLOWED METHODS</th></tr></thead><tbody><tr id="1f803592-bfc7-49d3-88ab-70048dcb780f"><td id="V_tb" class="" style="width:180.00000762939453px">Customer</td><td id="SWq}" class="" style="width:186.00000762939453px">GET, PATCH, DELETE</td><td id="}oE`" class="" style="width:297.9861145019531px">Retrieve, edit, and delete the order-item</td><td id="NTnr" class="" style="width:409.00001525878906px">Other users’ order-items are unreachable</td></tr><tr id="a8d18445-24c7-4d81-8e96-b8539077123d"><td id="V_tb" class="" style="width:180.00000762939453px">Manager</td><td id="SWq}" class="" style="width:186.00000762939453px">GET, PATCH, DELETE</td><td id="}oE`" class="" style="width:297.9861145019531px">Retrieve, edit, and delete the order-item</td><td id="NTnr" class="" style="width:409.00001525878906px">None</td></tr><tr id="6e710100-1732-484a-bcf9-b8d03d57dde4"><td id="V_tb" class="" style="width:180.00000762939453px">Admin</td><td id="SWq}" class="" style="width:186.00000762939453px">GET, PATCH, DELETE</td><td id="}oE`" class="" style="width:297.9861145019531px">Retrieve, edit, and delete the order-item</td><td id="NTnr" class="" style="width:409.00001525878906px">None</td></tr></tbody></table><p id="c538b80d-5186-48ec-8a00-0b047af2df3c" class=""><strong>Usage</strong>:</p><pre id="7db9b70e-a560-47e4-b7cb-684f2ba56631" class="code"><code>curl -X GET localhost:8000/api/order-items/{order-itemId} \
   -H &#x27;Content-Type: application/json&#x27;     \
	 -H &quot;Authorization: Bearer {token}&quot;

curl -X PATCH localhost:8000/api/order-items/{order-itemId} \
   -H &#x27;Content-Type: application/json&#x27;      \
	 -H &quot;Authorization: Bearer {token}&quot;       \
   -d &#x27;{&quot;quantity&quot;: &quot;{menu-itemId}&quot;}&#x27;

curl -X DELETE localhost:8000/api/order-items/{order-itemId} \
   -H &#x27;Content-Type: application/json&#x27;     \
	 -H &quot;Authorization: Bearer {token}&quot;</code></pre><h3 id="91ac5363-c670-4c2a-ac3d-96061e54e789" class="">Cart</h3><p id="a5b67038-de7c-4b8f-bed0-8f75693fd9d1" class=""><strong>/api/cart</strong></p><table id="3d86f512-8818-49dc-b0a5-b444f8c12fe6" class="simple-table"><thead class="simple-table-header"><tr id="5ff561b6-d9a9-49fc-b929-f8740ec20faf"><th id="V_tb" class="simple-table-header-color simple-table-header" style="width:180.00000762939453px">ROLE</th><th id="SWq}" class="simple-table-header-color simple-table-header" style="width:186.00000762939453px">ALLOWED METHODS</th><th id="}oE`" class="simple-table-header-color simple-table-header" style="width:297.9861145019531px">ACTIONS</th><th id="NTnr" class="simple-table-header-color simple-table-header" style="width:409.00001525878906px">RESTRICTIONS WITHIN ALLOWED METHODS</th></tr></thead><tbody><tr id="cfa20ac9-5653-46ff-b6d6-667cc4f46cf5"><td id="V_tb" class="" style="width:180.00000762939453px">Customer</td><td id="SWq}" class="" style="width:186.00000762939453px">GET, POST, DELETE</td><td id="}oE`" class="" style="width:297.9861145019531px">Retrieve users’ cart, add order-items to the cart, delete order-items</td><td id="NTnr" class="" style="width:409.00001525878906px">The cart of other users are unreachable </td></tr></tbody></table><p id="678a574b-1507-4f79-8355-be0ba127b644" class=""><strong>Usage</strong>:</p><pre id="20319624-b0b8-4fbe-8b2a-27fd35c8387e" class="code"><code>curl -X GET localhost:8000/api/cart    \
   -H &#x27;Content-Type: application/json&#x27; \
	 -H &quot;Authorization: Bearer {token}&quot; 

curl -X POST localhost:8000/api/cart   \
   -H &#x27;Content-Type: application/json&#x27; \
	 -H &quot;Authorization: Bearer {token}&quot;  \
   -d &#x27;{&quot;id&quot;: &quot;{order-itemId}&quot;}&#x27;

curl -X DELETE localhost:8000/api/cart \
   -H &#x27;Content-Type: application/json&#x27; \
	 -H &quot;Authorization: Bearer {token}&quot;  \
   -d &#x27;{&quot;id&quot;: &quot;{order-itemId}&quot;}&#x27;

curl -X DELETE localhost:8000/api/cart \
   -H &#x27;Content-Type: application/json&#x27; \
	 -H &quot;Authorization: Bearer {token}&quot; </code></pre><p id="17efd5b7-5d1c-4757-9282-188d16c9b2f3" class="">A DELETE request requires the id of the order-item that should be deleted. If no id is provided, all the order-items in the cart will be deleted.</p><h3 id="40e429cc-fda9-4ccc-ac0d-ce3f4e96387b" class="">Orders</h3><p id="9a6c7160-4755-4501-997e-76d89fc0b92c" class=""><strong>/api/orders</strong></p><table id="aef8106e-8116-48e6-86af-62d7399f2f76" class="simple-table"><thead class="simple-table-header"><tr id="ab5e6262-e8ec-46e1-aba4-305c54d3582b"><th id="V_tb" class="simple-table-header-color simple-table-header" style="width:180.00000762939453px">ROLE</th><th id="SWq}" class="simple-table-header-color simple-table-header" style="width:186.00000762939453px">ALLOWED METHODS</th><th id="}oE`" class="simple-table-header-color simple-table-header" style="width:297.9861145019531px">ACTIONS</th><th id="NTnr" class="simple-table-header-color simple-table-header" style="width:409.00001525878906px">RESTRICTIONS WITHIN ALLOWED METHODS</th></tr></thead><tbody><tr id="f714ee4c-6acb-44ed-915f-889a074ad1a1"><td id="V_tb" class="" style="width:180.00000762939453px">Customer</td><td id="SWq}" class="" style="width:186.00000762939453px">GET, POST</td><td id="}oE`" class="" style="width:297.9861145019531px">Retrieve the list of orders, create new orders</td><td id="NTnr" class="" style="width:409.00001525878906px">Other users’ orders are unreachable</td></tr><tr id="b32c3634-8449-41ce-93f0-35941557e231"><td id="V_tb" class="" style="width:180.00000762939453px">Manager</td><td id="SWq}" class="" style="width:186.00000762939453px">GET</td><td id="}oE`" class="" style="width:297.9861145019531px">Retrieve the list of orders</td><td id="NTnr" class="" style="width:409.00001525878906px">None</td></tr><tr id="df7a852f-92e3-4222-872e-d24fdf16b4c0"><td id="V_tb" class="" style="width:180.00000762939453px">Admin</td><td id="SWq}" class="" style="width:186.00000762939453px">GET</td><td id="}oE`" class="" style="width:297.9861145019531px">Retrieve the list of orders</td><td id="NTnr" class="" style="width:409.00001525878906px">None</td></tr><tr id="0d65689c-ec59-4354-848f-4b79b32709af"><td id="V_tb" class="" style="width:180.00000762939453px">Delivery Crew</td><td id="SWq}" class="" style="width:186.00000762939453px">GET</td><td id="}oE`" class="" style="width:297.9861145019531px">Retrieve the list of orders</td><td id="NTnr" class="" style="width:409.00001525878906px">Members of this group can only reach those orders assigned to them.</td></tr></tbody></table><p id="a93d91ba-355e-460b-9243-bfb723234871" class=""><strong>Usage</strong>:</p><pre id="198cefe9-6aae-40f7-9a7a-12975347a180" class="code"><code>curl -X GET localhost:8000/api/orders  \
   -H &#x27;Content-Type: application/json&#x27; \
	 -H &quot;Authorization: Bearer {token}&quot; 

curl -X POST localhost:8000/api/orders \
   -H &#x27;Content-Type: application/json&#x27; \
	 -H &quot;Authorization: Bearer {token}&quot;</code></pre><p id="0ca18c6c-ac79-4543-88d3-95dc1200d44b" class=""><em>A </em><em><strong>POST</strong></em><em> request creates a new order with the order-items present in the user’s cart. This request creates purchase-items instances from the order-items, and adds them to a Purchase instance which will be added to an Order instance. The last step is to delete all the order-items from the cart.  </em></p><p id="ba24d1f7-8474-4631-9e94-d7eedaf640e7" class="">This procedure ensures that a user doesn’t add repeated menu-items to the order-items giving its unique together (user, menu-item) constraint and, once the order has been created, deletes the order-item allowing the user to create new orders with the same menu-items.</p><p id="4624b953-ef60-4191-8bdd-a64882f76bbb" class="">
</p><p id="b797d6f6-4d08-41d8-9827-3befd4822c18" class=""><strong>/api/orders/{orderId}</strong></p><table id="ae6c30ff-7f3a-4fa9-bc24-fe8d79717504" class="simple-table"><thead class="simple-table-header"><tr id="760467a2-e459-48a9-a4a6-411be0fd8cc3"><th id="V_tb" class="simple-table-header-color simple-table-header" style="width:180.00000762939453px">ROLE</th><th id="SWq}" class="simple-table-header-color simple-table-header" style="width:186.00000762939453px">ALLOWED METHODS</th><th id="}oE`" class="simple-table-header-color simple-table-header" style="width:297.9861145019531px">ACTIONS</th><th id="NTnr" class="simple-table-header-color simple-table-header" style="width:409.00001525878906px">RESTRICTIONS WITHIN ALLOWED METHODS</th></tr></thead><tbody><tr id="98cd7db4-bdb8-429c-a0c6-4fb2d59687bf"><td id="V_tb" class="" style="width:180.00000762939453px">Customer</td><td id="SWq}" class="" style="width:186.00000762939453px">GET</td><td id="}oE`" class="" style="width:297.9861145019531px">Retrieve order details</td><td id="NTnr" class="" style="width:409.00001525878906px">Other users’ orders are unreachable</td></tr><tr id="bd6c9629-14d7-47e0-ae0a-1ab86056d4e3"><td id="V_tb" class="" style="width:180.00000762939453px">Delivery Crew</td><td id="SWq}" class="" style="width:186.00000762939453px">GET, PATCH</td><td id="}oE`" class="" style="width:297.9861145019531px">Retrieve order details, change the status</td><td id="NTnr" class="" style="width:409.00001525878906px">Members of this group can only reach those orders assigned to them.</td></tr><tr id="022752e8-8076-4cab-84ee-baf31ecfb220"><td id="V_tb" class="" style="width:180.00000762939453px">Manager</td><td id="SWq}" class="" style="width:186.00000762939453px">GET, PATCH, DELETE</td><td id="}oE`" class="" style="width:297.9861145019531px">Retrieve, edit, and delete the order</td><td id="NTnr" class="" style="width:409.00001525878906px">None</td></tr><tr id="d4943bef-c3f1-439f-ad96-7e1c3517abff"><td id="V_tb" class="" style="width:180.00000762939453px">Admin</td><td id="SWq}" class="" style="width:186.00000762939453px">GET, PATCH, DELETE</td><td id="}oE`" class="" style="width:297.9861145019531px">Retrieve, edit, and delete the order</td><td id="NTnr" class="" style="width:409.00001525878906px">None</td></tr></tbody></table><p id="fdbfad51-e58d-4c31-93e2-4ee6b74f04af" class=""><strong>Usage</strong>:</p><pre id="c9cc654c-7f6d-47ae-8c32-13c4e518b48c" class="code"><code>curl -X GET localhost:8000/api/orders/{orderId}  \
   -H &#x27;Content-Type: application/json&#x27;  \
	 -H &quot;Authorization: Bearer {token}&quot; 

curl -X PATCH localhost:8000/api/orders/{orderId} \
   -H &#x27;Content-Type: application/json&#x27;  \
	 -H &quot;Authorization: Bearer {token}&quot;   \
   -d &#x27;{&quot;status&quot;: &quot;{value}&quot;}&#x27;

curl -X DELETE localhost:8000/api/orders/{orderId}  \
   -H &#x27;Content-Type: application/json&#x27;  \
	 -H &quot;Authorization: Bearer {token}&quot; </code></pre><p id="5c2de8db-676b-48b4-b482-fe4e124f3c2d" class=""><em>Allowed status values are 0 and 1, for True and False respectively.</em></p><h3 id="b43b0154-1f71-4cd5-90ea-0c4a03d95e79" class="">Purchase</h3><p id="731ecdac-91ae-48c6-8264-15717b39cac6" class=""><strong>/api/purchases</strong></p><table id="ff66c260-dbf5-43e8-b115-20875044b2ad" class="simple-table"><thead class="simple-table-header"><tr id="9cf3a0d4-37be-418c-bc69-e4d7e1160aee"><th id="V_tb" class="simple-table-header-color simple-table-header" style="width:180.00000762939453px">ROLE</th><th id="SWq}" class="simple-table-header-color simple-table-header" style="width:186.00000762939453px">ALLOWED METHODS</th><th id="}oE`" class="simple-table-header-color simple-table-header" style="width:297.9861145019531px">ACTIONS</th><th id="NTnr" class="simple-table-header-color simple-table-header" style="width:409.00001525878906px">RESTRICTIONS WITHIN ALLOWED METHODS</th></tr></thead><tbody><tr id="a7ffcff4-898d-49a2-a57e-8164cac67a19"><td id="V_tb" class="" style="width:180.00000762939453px">Customer</td><td id="SWq}" class="" style="width:186.00000762939453px">GET</td><td id="}oE`" class="" style="width:297.9861145019531px">Retrieve purchases list</td><td id="NTnr" class="" style="width:409.00001525878906px">Other users’ purchases are unreachable</td></tr><tr id="fbf86c14-11e5-46cf-917b-3964f3548459"><td id="V_tb" class="" style="width:180.00000762939453px">Delivery Crew</td><td id="SWq}" class="" style="width:186.00000762939453px">GET</td><td id="}oE`" class="" style="width:297.9861145019531px">Retrieve purchases list</td><td id="NTnr" class="" style="width:409.00001525878906px">Can only retrieve purchases related to orders assign to them</td></tr><tr id="66de4a74-3ee9-475d-9749-e7088661f69e"><td id="V_tb" class="" style="width:180.00000762939453px">Manager</td><td id="SWq}" class="" style="width:186.00000762939453px">GET</td><td id="}oE`" class="" style="width:297.9861145019531px">Retrieve purchases list</td><td id="NTnr" class="" style="width:409.00001525878906px">None</td></tr><tr id="3a337101-04d5-4896-84a9-bda950574744"><td id="V_tb" class="" style="width:180.00000762939453px">Admin</td><td id="SWq}" class="" style="width:186.00000762939453px">GET</td><td id="}oE`" class="" style="width:297.9861145019531px">Retrieve purchases list</td><td id="NTnr" class="" style="width:409.00001525878906px">None</td></tr></tbody></table><p id="f5fb541b-ed3f-4e39-b235-11894964446d" class=""><strong>Usage</strong>:</p><pre id="32f4036e-1051-4535-a23c-96ccbce9a0dd" class="code"><code>curl -X GET localhost:8000/api/purchases \
   -H &#x27;Content-Type: application/json&#x27;   \
	 -H &quot;Authorization: Bearer {token}&quot;</code></pre><p id="d870c7d7-0647-419c-b72b-3bb7e72f05ea" class="">
</p><p id="15804617-bb7a-4474-9034-d20e9400e2a6" class=""><strong>/api/purchases/{purchaseId}</strong></p><table id="db7720db-faad-4c05-8455-053192506207" class="simple-table"><thead class="simple-table-header"><tr id="954fef07-379c-4924-8212-2bcc2747fecd"><th id="V_tb" class="simple-table-header-color simple-table-header" style="width:180.00000762939453px">ROLE</th><th id="SWq}" class="simple-table-header-color simple-table-header" style="width:186.00000762939453px">ALLOWED METHODS</th><th id="}oE`" class="simple-table-header-color simple-table-header" style="width:297.9861145019531px">ACTIONS</th><th id="NTnr" class="simple-table-header-color simple-table-header" style="width:409.00001525878906px">RESTRICTIONS WITHIN ALLOWED METHODS</th></tr></thead><tbody><tr id="40e8e988-37a5-4111-a976-6a9eb96674c0"><td id="V_tb" class="" style="width:180.00000762939453px">Customer</td><td id="SWq}" class="" style="width:186.00000762939453px">GET</td><td id="}oE`" class="" style="width:297.9861145019531px">Retrieve the purchase</td><td id="NTnr" class="" style="width:409.00001525878906px">Other users’ purchases are unreachable</td></tr><tr id="2cc89ee7-37a0-4b7d-ae95-92f0024b7f5f"><td id="V_tb" class="" style="width:180.00000762939453px">Delivery Crew</td><td id="SWq}" class="" style="width:186.00000762939453px">GET</td><td id="}oE`" class="" style="width:297.9861145019531px">Retrieve the purchase</td><td id="NTnr" class="" style="width:409.00001525878906px">Can only retrieve purchases related to orders assign to them</td></tr><tr id="c3d7d3dd-9338-4d61-a8b1-e557c74153f8"><td id="V_tb" class="" style="width:180.00000762939453px">Manager</td><td id="SWq}" class="" style="width:186.00000762939453px">GET, DELETE</td><td id="}oE`" class="" style="width:297.9861145019531px">Retrieve and delete the purchase</td><td id="NTnr" class="" style="width:409.00001525878906px">None</td></tr><tr id="cfbe6968-b93f-4d0e-92d4-3f3a0eeb0a43"><td id="V_tb" class="" style="width:180.00000762939453px">Admin</td><td id="SWq}" class="" style="width:186.00000762939453px">GET, DELETE</td><td id="}oE`" class="" style="width:297.9861145019531px">Retrieve and delete the purchase</td><td id="NTnr" class="" style="width:409.00001525878906px">None</td></tr></tbody></table><p id="83f73880-0926-49b0-9f32-eb00f45f2514" class=""><strong>Usage</strong>:</p><pre id="26fce78a-ce7f-47cc-8525-92ecdcbc75cc" class="code"><code>curl -X GET localhost:8000/api/purchases/{purchaseId} \
   -H &#x27;Content-Type: application/json&#x27;  \
	 -H &quot;Authorization: Bearer {token}&quot;

curl -X DELETE localhost:8000/api/purchases/{purchaseId} \
   -H &#x27;Content-Type: application/json&#x27;  \
	 -H &quot;Authorization: Bearer {token}&quot;  </code></pre><h3 id="6521e918-4ea8-4b65-bf1d-81a56dadf943" class="">Purchase Items</h3><p id="f3316be6-fb41-4b2d-af83-1fc39d230009" class=""><strong>/api/purchase-items</strong></p><table id="fe83b637-3d07-4fa7-9f81-6279b2f387c4" class="simple-table"><thead class="simple-table-header"><tr id="51b8425a-89ef-47c2-8bc6-2316d57c70bb"><th id="V_tb" class="simple-table-header-color simple-table-header" style="width:180.00000762939453px">ROLE</th><th id="SWq}" class="simple-table-header-color simple-table-header" style="width:186.00000762939453px">ALLOWED METHODS</th><th id="}oE`" class="simple-table-header-color simple-table-header" style="width:297.9861145019531px">ACTIONS</th><th id="NTnr" class="simple-table-header-color simple-table-header" style="width:409.00001525878906px">RESTRICTIONS WITHIN ALLOWED METHODS</th></tr></thead><tbody><tr id="0db4dfdf-5435-45c3-8d5c-3595e8349af5"><td id="V_tb" class="" style="width:180.00000762939453px">Customer</td><td id="SWq}" class="" style="width:186.00000762939453px">GET</td><td id="}oE`" class="" style="width:297.9861145019531px">Retrieve purchase-items lust</td><td id="NTnr" class="" style="width:409.00001525878906px">Other users’ purchase-items are unreachable</td></tr><tr id="2a38133a-0700-48c8-bf8f-9f063454c863"><td id="V_tb" class="" style="width:180.00000762939453px">Delivery Crew</td><td id="SWq}" class="" style="width:186.00000762939453px">GET</td><td id="}oE`" class="" style="width:297.9861145019531px">Retrieve purchase-items lust</td><td id="NTnr" class="" style="width:409.00001525878906px">Can only retrieve purchase-items related to orders assign to them</td></tr><tr id="fe29eb18-9ad2-4202-8e27-df954fd616a0"><td id="V_tb" class="" style="width:180.00000762939453px">Manager</td><td id="SWq}" class="" style="width:186.00000762939453px">GET</td><td id="}oE`" class="" style="width:297.9861145019531px">Retrieve purchase-items lust</td><td id="NTnr" class="" style="width:409.00001525878906px">None</td></tr><tr id="8d60001c-d7c4-4f3a-bc83-faed0acc04c5"><td id="V_tb" class="" style="width:180.00000762939453px">Admin</td><td id="SWq}" class="" style="width:186.00000762939453px">GET</td><td id="}oE`" class="" style="width:297.9861145019531px">Retrieve purchase-items lust</td><td id="NTnr" class="" style="width:409.00001525878906px">None</td></tr></tbody></table><p id="e68ce86a-51b5-4650-9115-405c5ee83b58" class=""><strong>Usage</strong>:</p><pre id="2ff57e21-b644-44c8-bf0f-53c1a7b0d6f4" class="code"><code>curl -X GET localhost:8000/api/purchases/{purchaseId} \
   -H &#x27;Content-Type: application/json&#x27;  \
	 -H &quot;Authorization: Bearer {token}&quot;

curl -X DELETE localhost:8000/api/purchases/{purchaseId} \
   -H &#x27;Content-Type: application/json&#x27;  \
	 -H &quot;Authorization: Bearer {token}&quot;  </code></pre><p id="ebfb9c15-2493-4315-bbc3-a8c67f8989df" class="">
</p><p id="8c691fd7-eea2-46b5-82df-299252f93bf3" class=""><strong>/api/purchase-items/{purchase-itemId}</strong></p><table id="5ee43bab-6867-42a0-a5b9-58d87365d937" class="simple-table"><thead class="simple-table-header"><tr id="2bcc1dc8-5f0c-4d71-923f-fdb2f09de676"><th id="V_tb" class="simple-table-header-color simple-table-header" style="width:180.00000762939453px">ROLE</th><th id="SWq}" class="simple-table-header-color simple-table-header" style="width:186.00000762939453px">ALLOWED METHODS</th><th id="}oE`" class="simple-table-header-color simple-table-header" style="width:297.9861145019531px">ACTIONS</th><th id="NTnr" class="simple-table-header-color simple-table-header" style="width:409.00001525878906px">RESTRICTIONS WITHIN ALLOWED METHODS</th></tr></thead><tbody><tr id="65f58bca-4d1e-4de1-9e65-6d03ae3aa9cf"><td id="V_tb" class="" style="width:180.00000762939453px">Customer</td><td id="SWq}" class="" style="width:186.00000762939453px">GET</td><td id="}oE`" class="" style="width:297.9861145019531px">Retrieve the purchase-item</td><td id="NTnr" class="" style="width:409.00001525878906px">Other users’ purchases are unreachable</td></tr><tr id="fff0de99-a3f0-488f-b334-9eb5653db3ac"><td id="V_tb" class="" style="width:180.00000762939453px">Delivery Crew</td><td id="SWq}" class="" style="width:186.00000762939453px">GET</td><td id="}oE`" class="" style="width:297.9861145019531px">Retrieve the purchase-item</td><td id="NTnr" class="" style="width:409.00001525878906px">Can only retrieve purchases related to orders assign to them</td></tr><tr id="dfa3596f-3142-418e-b770-30998be8c8a9"><td id="V_tb" class="" style="width:180.00000762939453px">Manager</td><td id="SWq}" class="" style="width:186.00000762939453px">GET, PATCH, DELETE</td><td id="}oE`" class="" style="width:297.9861145019531px">Retrieve, edit, and delete the purchase-item</td><td id="NTnr" class="" style="width:409.00001525878906px">None</td></tr><tr id="1ecdb7d7-a02f-4af6-a2ac-a0f49f69aaf9"><td id="V_tb" class="" style="width:180.00000762939453px">Admin</td><td id="SWq}" class="" style="width:186.00000762939453px">GET, PATCH, DELETE</td><td id="}oE`" class="" style="width:297.9861145019531px">Retrieve, edit, and delete the purchase-item</td><td id="NTnr" class="" style="width:409.00001525878906px">None</td></tr></tbody></table><p id="2cf89856-044a-462d-bf92-c345c758665b" class=""><strong>Usage</strong>:</p><pre id="010d2f61-0f55-415d-b017-d8aae2bd4141" class="code"><code>curl -X GET localhost:8000/api/purchases/{purchaseId} \
   -H &#x27;Content-Type: application/json&#x27;  \
	 -H &quot;Authorization: Bearer {token}&quot;

curl -X PATCH localhost:8000/api/purchases/{purchaseId} \
   -H &#x27;Content-Type: application/json&#x27;  \
	 -H &quot;Authorization: Bearer {token}&quot;   \
   -d &#x27;{&quot;quantity&quot;: &quot;{value}&quot;}&#x27;

curl -X DELETE localhost:8000/api/purchases/{purchaseId} \
   -H &#x27;Content-Type: application/json&#x27;  \
	 -H &quot;Authorization: Bearer {token}&quot;  </code></pre></div></article></body></html>