# Markdown_cheet_sheet
Basic Markdown cheet sheet  
<!DOCTYPE html>
<html>
<head>
<title>mardown_cheet_sheet.md</title>

body {
	font-family: var(--vscode-markdown-font-family, -apple-system, BlinkMacSystemFont, "Segoe WPC", "Segoe UI", "Ubuntu", "Droid Sans", sans-serif);
	font-size: var(--vscode-markdown-font-size, 14px);
	padding: 0 26px;
	line-height: var(--vscode-markdown-line-height, 22px);
	word-wrap: break-word;
}

#code-csp-warning {
	position: fixed;
	top: 0;
	right: 0;
	color: white;
	margin: 16px;
	text-align: center;
	font-size: 12px;
	font-family: sans-serif;
	background-color:#444444;
	cursor: pointer;
	padding: 6px;
	box-shadow: 1px 1px 1px rgba(0,0,0,.25);
}

#code-csp-warning:hover {
	text-decoration: none;
	background-color:#007acc;
	box-shadow: 2px 2px 2px rgba(0,0,0,.25);
}

body.scrollBeyondLastLine {
	margin-bottom: calc(100vh - 22px);
}

body.showEditorSelection .code-line {
	position: relative;
}

body.showEditorSelection .code-active-line:before,
body.showEditorSelection .code-line:hover:before {
	content: "";
	display: block;
	position: absolute;
	top: 0;
	left: -12px;
	height: 100%;
}

body.showEditorSelection li.code-active-line:before,
body.showEditorSelection li.code-line:hover:before {
	left: -30px;
}

.vscode-light.showEditorSelection .code-active-line:before {
	border-left: 3px solid rgba(0, 0, 0, 0.15);
}

.vscode-light.showEditorSelection .code-line:hover:before {
	border-left: 3px solid rgba(0, 0, 0, 0.40);
}

.vscode-light.showEditorSelection .code-line .code-line:hover:before {
	border-left: none;
}

.vscode-dark.showEditorSelection .code-active-line:before {
	border-left: 3px solid rgba(255, 255, 255, 0.4);
}

.vscode-dark.showEditorSelection .code-line:hover:before {
	border-left: 3px solid rgba(255, 255, 255, 0.60);
}

.vscode-dark.showEditorSelection .code-line .code-line:hover:before {
	border-left: none;
}

.vscode-high-contrast.showEditorSelection .code-active-line:before {
	border-left: 3px solid rgba(255, 160, 0, 0.7);
}

.vscode-high-contrast.showEditorSelection .code-line:hover:before {
	border-left: 3px solid rgba(255, 160, 0, 1);
}

.vscode-high-contrast.showEditorSelection .code-line .code-line:hover:before {
	border-left: none;
}

img {
	max-width: 100%;
	max-height: 100%;
}

a {
	text-decoration: none;
}

a:hover {
	text-decoration: underline;
}

a:focus,
input:focus,
select:focus,
textarea:focus {
	outline: 1px solid -webkit-focus-ring-color;
	outline-offset: -1px;
}

hr {
	border: 0;
	height: 2px;
	border-bottom: 2px solid;
}

h1 {
	padding-bottom: 0.3em;
	line-height: 1.2;
	border-bottom-width: 1px;
	border-bottom-style: solid;
}

h1, h2, h3 {
	font-weight: normal;
}

table {
	border-collapse: collapse;
}

table > thead > tr > th {
	text-align: left;
	border-bottom: 1px solid;
}

table > thead > tr > th,
table > thead > tr > td,
table > tbody > tr > th,
table > tbody > tr > td {
	padding: 5px 10px;
}

table > tbody > tr + tr > td {
	border-top: 1px solid;
}

blockquote {
	margin: 0 7px 0 5px;
	padding: 0 16px 0 10px;
	border-left-width: 5px;
	border-left-style: solid;
}

code {
	font-family: Menlo, Monaco, Consolas, "Droid Sans Mono", "Courier New", monospace, "Droid Sans Fallback";
	font-size: 1em;
	line-height: 1.357em;
}

body.wordWrap pre {
	white-space: pre-wrap;
}

pre:not(.hljs),
pre.hljs code > div {
	padding: 16px;
	border-radius: 3px;
	overflow: auto;
}

pre code {
	color: var(--vscode-editor-foreground);
	tab-size: 4;
}

/** Theming */

.vscode-light pre {
	background-color: rgba(220, 220, 220, 0.4);
}

.vscode-dark pre {
	background-color: rgba(10, 10, 10, 0.4);
}

.vscode-high-contrast pre {
	background-color: rgb(0, 0, 0);
}

.vscode-high-contrast h1 {
	border-color: rgb(0, 0, 0);
}

.vscode-light table > thead > tr > th {
	border-color: rgba(0, 0, 0, 0.69);
}

.vscode-dark table > thead > tr > th {
	border-color: rgba(255, 255, 255, 0.69);
}

.vscode-light h1,
.vscode-light hr,
.vscode-light table > tbody > tr + tr > td {
	border-color: rgba(0, 0, 0, 0.18);
}

.vscode-dark h1,
.vscode-dark hr,
.vscode-dark table > tbody > tr + tr > td {
	border-color: rgba(255, 255, 255, 0.18);
}

</style>

<style>
/* Tomorrow Theme */
/* http://jmblog.github.com/color-themes-for-google-code-highlightjs */
/* Original theme - https://github.com/chriskempson/tomorrow-theme */

/* Tomorrow Comment */
.hljs-comment,
.hljs-quote {
	color: #8e908c;
}

/* Tomorrow Red */
.hljs-variable,
.hljs-template-variable,
.hljs-tag,
.hljs-name,
.hljs-selector-id,
.hljs-selector-class,
.hljs-regexp,
.hljs-deletion {
	color: #c82829;
}

/* Tomorrow Orange */
.hljs-number,
.hljs-built_in,
.hljs-builtin-name,
.hljs-literal,
.hljs-type,
.hljs-params,
.hljs-meta,
.hljs-link {
	color: #f5871f;
}

/* Tomorrow Yellow */
.hljs-attribute {
	color: #eab700;
}

/* Tomorrow Green */
.hljs-string,
.hljs-symbol,
.hljs-bullet,
.hljs-addition {
	color: #718c00;
}

/* Tomorrow Blue */
.hljs-title,
.hljs-section {
	color: #4271ae;
}

/* Tomorrow Purple */
.hljs-keyword,
.hljs-selector-tag {
	color: #8959a8;
}

.hljs {
	display: block;
	overflow-x: auto;
	color: #4d4d4c;
	padding: 0.5em;
}

.hljs-emphasis {
	font-style: italic;
}

.hljs-strong {
	font-weight: bold;
}
</style>

<style>
/*
 * Markdown PDF CSS
 */

 body {
	font-family: -apple-system, BlinkMacSystemFont, "Segoe WPC", "Segoe UI", "Ubuntu", "Droid Sans", sans-serif, "Meiryo";
	padding: 0 12px;
}

pre {
	background-color: #f8f8f8;
	border: 1px solid #cccccc;
	border-radius: 3px;
	overflow-x: auto;
	white-space: pre-wrap;
	overflow-wrap: break-word;
}

pre:not(.hljs) {
	padding: 23px;
	line-height: 19px;
}

blockquote {
	background: rgba(127, 127, 127, 0.1);
	border-color: rgba(0, 122, 204, 0.5);
}

.emoji {
	height: 1.4em;
}

code {
	font-size: 14px;
	line-height: 19px;
}

/* for inline code */
:not(pre):not(.hljs) > code {
	color: #C9AE75; /* Change the old color so it seems less like an error */
	font-size: inherit;
}

/* Page Break : use <div class="page"/> to insert page break
-------------------------------------------------------- */
.page {
	page-break-after: always;
}

</style>

<script src="https://unpkg.com/mermaid/dist/mermaid.min.js"></script>
</head>
<body>
  <script>
    mermaid.initialize({
      startOnLoad: true,
      theme: document.body.classList.contains('vscode-dark') || document.body.classList.contains('vscode-high-contrast')
          ? 'dark'
          : 'default'
    });
  </script>
<blockquote>
<h1 id="markdow-simple-cheet-sheet">Markdow Simple Cheet Sheet</h1>
</blockquote>
<p><a href="#1--heading">Heading</a><br>
<a href="#2--block-of-words">Block of Words</a><br>
<a href="#3--line-break">line break</a><br>
<a href="#4--face-of-text">Text</a><br>
<a href="#bullets-and-points">Bullets and Points</a><br>
<a href="#page-break">Page Break</a><br>
<a href="#link-and-hyper-link">Link and Huperlink</a><br>
<a href="#adding-code-or-block-of-code">Block of Code</a><br>
<a href="#adding-table">Table</a><br>
<a href="#images-and-files">Images</a></p>
<h1 id="how-to-giving-headings-in-markdown-files">How to giving headings in markdown files?</h1>
<h1 id="heading">Heading</h1>
<h2 id="1--heading">1- Heading</h2>
<h1 id="2--block-of-words">2- Block of words</h1>
<blockquote>
<p>This a block of special text</p>
<p>This is second line</p>
</blockquote>
<h1 id="3--line-break">3- Line break</h1>
<p>This is six months course data science and ai with baba meer<br>
also know as sayed meer</p>
<blockquote>
<h1 id="4--face-of-text">4- Face of text</h1>
</blockquote>
<blockquote>
<h1 id="data-science-is-all-about-the-science-of-data"><em>Data Science is all about The Science of Data</em></h1>
</blockquote>
<blockquote>
<h1 id="data-mining-deals-with-pattern-and-association"><em><strong>Data Mining deals with pattern and association</strong></em></h1>
</blockquote>
<blockquote>
<h1 id="you-can-also-use-uderscore-single-underscore-for-italic-and-double-underscore-for-bold">you can also use (uderscore) single underscore for italic and double underscore for bold</h1>
</blockquote>
<p><strong>bold</strong></p>
<p><em>italic</em></p>
<h1 id="bullets-and-points">bullets and points</h1>
<ul>
<li>day1</li>
<li>day2
<ul>
<li>
<p>day2 a</p>
<ul>
<li>subheading</li>
</ul>
</li>
<li>
<p>day2 b</p>
</li>
</ul>
</li>
<li>day3</li>
</ul>
<ol>
<li>day1
<ol>
<li>day1 a</li>
<li>day1 b</li>
</ol>
</li>
<li>day2</li>
</ol>
<blockquote>
<h1 id="using-and"><strong>using *and+</strong></h1>
</blockquote>
<ul>
<li>one</li>
<li>two</li>
<li>three</li>
</ul>
<ul>
<li>four</li>
<li>five</li>
</ul>
<h1 id="page-break">page break</h1>
<p>this is page 1</p>
<hr>
<hr>
<hr>
<p>this is page two</p>
<h1 id="link-and-hyper-link">Link and hyper link</h1>
<p><a href="https://codanics.com/courses/six-months-of-ai-and-data-science-mentorship-program/lesson/learn-markdown-language-in-72-minutes/">https://codanics.com/courses/six-months-of-ai-and-data-science-mentorship-program/lesson/learn-markdown-language-in-72-minutes/</a></p>
<p><a href="https://www.coursera.org/programs/dlsei-phase-2-52jvh?currentTab=CATALOG">cousera</a></p>
<p>the whole course is <a href="https://www.coursera.org/programs/dlsei-phase-2-52jvh?currentTab=CATALOG">here</a></p>
<blockquote>
<h1 id="images-and-files">Images and files</h1>
</blockquote>
<p><img src="10 truth.jpg" alt="programming qoute"></p>
<blockquote>
<h2 id="adding-code-or-block-of-code">Adding code or block of code</h2>
</blockquote>
<p><code>print(&quot;Heelo Baba Meer&quot;)</code></p>
<pre class="hljs"><code><div><span class="hljs-function"><span class="hljs-keyword">def</span> <span class="hljs-title">wrangle</span><span class="hljs-params">(file)</span>:</span>
    df = pd.read_csv(file)
    <span class="hljs-keyword">return</span> df
</div></code></pre>
<pre class="hljs"><code><div><span class="hljs-built_in">cout</span>&lt;&lt;<span class="hljs-string">"Hello Baba Meer"</span>;
</div></code></pre>
<h1 id="adding-table">Adding table</h1>
<table>
<thead>
<tr>
<th style="text-align:center">Name</th>
<th style="text-align:center">Program</th>
<th style="text-align:center">Semester</th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align:center">Meer</td>
<td style="text-align:center">Data Science</td>
<td style="text-align:center">5th</td>
</tr>
<tr>
<td style="text-align:center">Mutuza</td>
<td style="text-align:center">Data Science</td>
<td style="text-align:center">7th</td>
</tr>
<tr>
<td style="text-align:center">Shair</td>
<td style="text-align:center">Data Science</td>
<td style="text-align:center">7th</td>
</tr>
<tr>
<td style="text-align:center">Hassan</td>
<td style="text-align:center">Account &amp; finance</td>
<td style="text-align:center">7th</td>
</tr>
</tbody>
</table>
<p>Note: left side :--- for align left, right side ----: for right align and both side :------: for middle align</p>

</body>
</html>
