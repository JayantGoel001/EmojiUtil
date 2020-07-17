# Find-Emoji

A Simple Library To Find And Remove Emojis

![](https://github.com/CormacKrum/Find-Emoji/blob/master/emojis.png)

<div class="row">
		<div class="col-lg-10">
			<h1 class="page-header" id="howto">How to</h1>
		</div>
	</div>
  
  <div class="row">
		<div class="col-lg-12">
				<p>To get a Git project into your build:</p>
		</div>
	</div>

## Step 1. Add the JitPack repository to your build file

Add it in your root build.gradle at the end of repositories:
  
  <pre class="kode language-css code-toolbar"><code class=" kode language-css">	<span class="token selector">allprojects</span> <span class="token punctuation">{</span>
		<span class="token selector">repositories</span> <span class="token punctuation">{</span>
			<span class="token selector">...
			maven</span> <span class="token punctuation">{</span> url <span class="token string">'https://jitpack.io'</span> <span class="token punctuation">}</span>
		<span class="token punctuation">}</span>
	<span class="token punctuation">}</span></code></pre>
  
  ## Step 2. Add the dependency
  
  <pre class="kode code-toolbar  language-css"><code id="depCodeGradle" class=" kode  language-css">	<span class="token selector">dependencies</span> <span class="token punctuation">{</span>
	        implementation <span class="token string">'com.github.CormacKrum:Find-Emoji:Tag'</span>
	<span class="token punctuation">}</span>
</code></pre>

<p>Share this release:</p>

[![](https://jitpack.io/v/CormacKrum/Find-Emoji.svg)](https://jitpack.io/#CormacKrum/Find-Emoji)
