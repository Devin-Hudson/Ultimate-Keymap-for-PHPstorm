<!DOCTYPE html>
<html>

<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Welcome file</title>
  <link rel="stylesheet" href="https://stackedit.io/style.css" />
</head>

<body class="stackedit">
  <div class="stackedit__html"><h1 id="ultimate-keymap-for-phpstorm">Ultimate Keymap for PHPstorm</h1>
<p>In this keymap <strong>(which the layout is based on <em>JIKL</em> words)</strong>, I tried to visualize and bring arrow keys to the middle of keyboard as much as possible to make code and window navigation to be similar to what you already have with your arrow keys. The aim is to do regular stuff that you do with arrow keys in the middle of your keyboard so you won’t have to move your wrist to reach to arrow keys anymore to enhance speed.</p>
<p><em>The reason behind why I created this layout is I wasn’t comfortable with vim’s default movement keys so I tried this layout and tried to bring everything else to it as well.</em><br>
I hope it’ll come in handy!</p>
<blockquote>
<ul>
<li>I tried to set the key bindings in a way that feels sort of given so it feels natural.</li>
<li>Note that you can still perform the same actions with your regular arrow keys like you always did.</li>
</ul>
</blockquote>
<h1 id="the-bindings">The bindings</h1>
<p>So basically the idea is to visualize what you did with arrow keys with a bit minor difference.<br>
To toggle to moving and coding (which is natural considering you are in the middle of keyboard so everything you press should write a letter), I chose to use the <strong><code>ALT</code> key (as in, alternate the behavior of keys)</strong>.<br>
And the rest is pretty much like what you do with arrow keys. You’ll know what I’m talking about in a bit.<br>
So without further ado, let’s dive into the details:</p>

<table>
<thead>
<tr>
<th></th>
<th>You Used To</th>
<th>Now You Do</th>
</tr>
</thead>
<tbody>
<tr>
<td>Move Caret</td>
<td><code>⮜ ⮝⮟ ⮞</code></td>
<td><strong><code>ALT</code></strong>+<strong>J IK L</strong></td>
</tr>
<tr>
<td>Move Caret Selecting</td>
<td><strong><code>SHIFT</code></strong>+<code>⮜ ⮝⮟ ⮞</code></td>
<td><strong><code>Alt</code> <code>SHIFT</code></strong>+<strong>J IK L</strong></td>
</tr>
<tr>
<td>Move Caret Word by Word</td>
<td><strong><code>CTL</code></strong>+<code>⮜ ⮝⮟ ⮞</code></td>
<td><strong><code>ALT</code> <code>CTL</code></strong>+<strong>J IK L</strong></td>
</tr>
<tr>
<td>Move Caret Word by Word Selecting</td>
<td><strong><code>CTL</code> <code>SHIFT</code></strong>+<code>⮜ ⮝⮟ ⮞</code></td>
<td><strong><code>ALT</code> <code>CTL</code> <code>SHIFT</code></strong>+<strong>J IK L</strong></td>
</tr>
<tr>
<td>Move Caret a Page Up</td>
<td><strong><code>PAGE UP</code></strong></td>
<td><strong><code>CTL</code></strong>+<strong>I</strong></td>
</tr>
<tr>
<td>Move Caret a Page Down</td>
<td><strong><code>PAGE DOWN</code></strong></td>
<td><strong><code>CTL</code></strong>+<strong>K</strong></td>
</tr>
<tr>
<td>Move Caret a Line Start</td>
<td><strong><code>HOME</code></strong></td>
<td><strong><code>CTL</code></strong>+<strong>J</strong></td>
</tr>
<tr>
<td>Move Caret a Line End</td>
<td><strong><code>END</code></strong></td>
<td><strong><code>CTL</code></strong>+<strong>L</strong></td>
</tr>
<tr>
<td>Move Caret a Page Up Selecting</td>
<td><strong><code>SHIFT</code> <code>PAGE UP</code></strong></td>
<td><strong><code>CTL</code> <code>SHIFT</code></strong>+<strong>I</strong></td>
</tr>
<tr>
<td>Move Caret a Page Down Selecting</td>
<td><strong><code>SHIFT</code> <code>PAGE DOWN</code></strong></td>
<td><strong><code>CTL</code> <code>SHIFT</code></strong>+<strong>K</strong></td>
</tr>
<tr>
<td>Move Caret a Line Start Selecting</td>
<td><strong><code>SHIFT</code> <code>HOME</code></strong></td>
<td><strong><code>CTL</code> <code>SHIFT</code></strong>+<strong>J</strong></td>
</tr>
<tr>
<td>Move Caret a Line End Selecting</td>
<td><strong><code>SHIFT</code> <code>END</code></strong></td>
<td><strong><code>CTL</code> <code>SHIFT</code></strong>+<strong>L</strong></td>
</tr>
<tr>
<td>backspace</td>
<td><strong><code>⌫</code></strong></td>
<td><strong><code>ALT</code></strong>+<strong>U</strong></td>
</tr>
<tr>
<td>backspace a word</td>
<td><strong><code>CTL</code> <code>⌫</code></strong></td>
<td><strong><code>CTL</code> <code>ALT</code></strong>+<strong>U</strong></td>
</tr>
<tr>
<td>backspace a line</td>
<td></td>
<td><strong><code>CTL</code> <code>ALT</code> <code>SHIFT</code></strong>+<strong>U</strong></td>
</tr>
<tr>
<td>delete a letter</td>
<td><strong><code>Delete</code></strong></td>
<td><strong><code>ALT</code></strong>+<strong>O</strong></td>
</tr>
<tr>
<td>delete a word</td>
<td><strong><code>CTL</code> <code>Delete</code></strong></td>
<td><strong><code>CTL</code> <code>ALT</code></strong>+<strong>O</strong></td>
</tr>
<tr>
<td>delete a line</td>
<td></td>
<td><strong><code>CTL</code> <code>ALT</code> <code>SHIFT</code></strong>+<strong>O</strong></td>
</tr>
<tr>
<td>Switcher</td>
<td><strong><code>CTL</code> <code>TAB</code></strong></td>
<td><strong><code>CTL</code></strong>+<strong>;</strong></td>
</tr>
<tr>
<td>Focus to Editor <em>(back Home)</em></td>
<td><strong><code>Escape</code></strong></td>
<td><strong><code>CTL</code></strong>+<strong>H</strong></td>
</tr>
</tbody>
</table><h2 id="keymap-by-category">Keymap by Category</h2>
<p>It’s the same bindings but categorized, so easier to remember and find.</p>

<table>
<thead>
<tr>
<th>Movement</th>
<th>Used To</th>
<th>Now You Do</th>
</tr>
</thead>
<tbody>
<tr>
<td>Move Caret</td>
<td><code>⮜ ⮝⮟ ⮞</code></td>
<td><strong><code>ALT</code></strong>+<strong>J IK L</strong></td>
</tr>
<tr>
<td>Move Caret Word by Word</td>
<td><strong><code>CTL</code></strong>+<code>⮜ ⮝⮟ ⮞</code></td>
<td><strong><code>ALT</code> <code>CTL</code></strong>+<strong>J IK L</strong></td>
</tr>
<tr>
<td>Move Caret a Page Up</td>
<td><strong><code>PAGE UP</code></strong></td>
<td><strong><code>CTL</code></strong>+<strong>I</strong></td>
</tr>
<tr>
<td>Move Caret a Page Down</td>
<td><strong><code>PAGE DOWN</code></strong></td>
<td><strong><code>CTL</code></strong>+<strong>K</strong></td>
</tr>
<tr>
<td>Move Caret a Line Start</td>
<td><strong><code>HOME</code></strong></td>
<td><strong><code>CTL</code></strong>+<strong>J</strong></td>
</tr>
<tr>
<td>Move Caret a Line End</td>
<td><strong><code>END</code></strong></td>
<td><strong><code>CTL</code></strong>+<strong>L</strong></td>
</tr>
</tbody>
</table>
<table>
<thead>
<tr>
<th>Movement with Selection</th>
<th>Used To</th>
<th>Now You Do</th>
</tr>
</thead>
<tbody>
<tr>
<td>Move Caret Selecting</td>
<td><strong><code>SHIFT</code></strong>+<code>⮜ ⮝⮟ ⮞</code></td>
<td><strong><code>Alt</code> <code>SHIFT</code></strong>+<strong>J IK L</strong></td>
</tr>
<tr>
<td>Move Caret Word by Word Selecting</td>
<td><strong><code>CTL</code> <code>SHIFT</code></strong>+<code>⮜ ⮝⮟ ⮞</code></td>
<td><strong><code>ALT</code> <code>CTL</code> <code>SHIFT</code></strong>+<strong>J IK L</strong></td>
</tr>
<tr>
<td>Move Caret a Page Up Selecting</td>
<td><strong><code>SHIFT</code> <code>PAGE UP</code></strong></td>
<td><strong><code>CTL</code> <code>SHIFT</code></strong>+<strong>I</strong></td>
</tr>
<tr>
<td>Move Caret a Page Down Selecting</td>
<td><strong><code>SHIFT</code> <code>PAGE DOWN</code></strong></td>
<td><strong><code>CTL</code> <code>SHIFT</code></strong>+<strong>K</strong></td>
</tr>
<tr>
<td>Move Caret a Line Start Selecting</td>
<td><strong><code>SHIFT</code> <code>HOME</code></strong></td>
<td><strong><code>CTL</code> <code>SHIFT</code></strong>+<strong>J</strong></td>
</tr>
<tr>
<td>Move Caret a Line End Selecting</td>
<td><strong><code>SHIFT</code> <code>END</code></strong></td>
<td><strong><code>CTL</code> <code>SHIFT</code></strong>+<strong>L</strong></td>
</tr>
</tbody>
</table>
<table>
<thead>
<tr>
<th>Backspacing</th>
<th>Used To</th>
<th>Now You Do</th>
</tr>
</thead>
<tbody>
<tr>
<td>backspace</td>
<td><strong><code>⌫</code></strong></td>
<td><strong><code>ALT</code></strong>+<strong>U</strong></td>
</tr>
<tr>
<td>backspace a word</td>
<td><strong><code>CTL</code> <code>⌫</code></strong></td>
<td><strong><code>CTL</code> <code>ALT</code></strong>+<strong>U</strong></td>
</tr>
<tr>
<td>backspace a line</td>
<td></td>
<td><strong><code>CTL</code> <code>ALT</code> <code>SHIFT</code></strong>+<strong>U</strong></td>
</tr>
<tr>
<td>delete a letter</td>
<td><strong><code>Delete</code></strong></td>
<td><strong><code>ALT</code></strong>+<strong>O</strong></td>
</tr>
</tbody>
</table>
<table>
<thead>
<tr>
<th>Deleting</th>
<th>Used To</th>
<th>Now You Do</th>
</tr>
</thead>
<tbody>
<tr>
<td>delete a letter</td>
<td><strong><code>Delete</code></strong></td>
<td><strong><code>ALT</code></strong>+<strong>O</strong></td>
</tr>
<tr>
<td>delete a word</td>
<td><strong><code>CTL</code> <code>Delete</code></strong></td>
<td><strong><code>CTL</code> <code>ALT</code></strong>+<strong>O</strong></td>
</tr>
<tr>
<td>delete a line</td>
<td></td>
<td><strong><code>CTL</code> <code>ALT</code> <code>SHIFT</code></strong>+<strong>O</strong></td>
</tr>
</tbody>
</table>
<table>
<thead>
<tr>
<th>Extra</th>
<th>Used To</th>
<th>Now You Do</th>
</tr>
</thead>
<tbody>
<tr>
<td>Switcher</td>
<td><strong><code>CTL</code> <code>TAB</code></strong></td>
<td><strong><code>CTL</code></strong>+<strong>;</strong></td>
</tr>
<tr>
<td>Focus to Editor <em>(back Home)</em></td>
<td><strong><code>Escape</code></strong></td>
<td><strong><code>CTL</code></strong>+<strong>H</strong></td>
</tr>
</tbody>
</table><p><em><strong>I Hope You Find it Cool…</strong></em></p>
<h2 id="install">Install</h2>
<p>it’s easy to install, only thing you need to copy the file to the following directory.</p>
<p><strong>IN WINDOWS</strong></p>
<pre><code>%APPDATA%\JetBrains\&lt;product&gt;&lt;version&gt;\keymaps
</code></pre>
<blockquote>
<p>example<br>
C:\Users\JohnS\AppData\Roaming\JetBrains\PhpStorm2020.1\keymaps</p>
</blockquote>
<p><strong>IN macOS</strong></p>
<pre><code>~/Library/Application Support/JetBrains/&lt;product&gt;&lt;version&gt;/keymaps
</code></pre>
<blockquote>
<p>example<br>
C:\Users\JohnS\AppData\Roaming\JetBrains\PhpStorm2020.1\keymaps</p>
</blockquote>
<p><strong>IN LINUX</strong></p>
<pre><code>~/.config/JetBrains/&lt;product&gt;&lt;version&gt;/keymaps
</code></pre>
<blockquote>
<p>example<br>
~/.config/JetBrains/PhpStorm2020.1/keymaps</p>
</blockquote>
</div>
</body>

</html>
