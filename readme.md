#SyntaxHighlighter Extra for MODx Revolution

**Author:** Alex Gorbatchev <http://alexgorbatchev.com/SyntaxHighlighter/> [Syntax Highlighter](http://alexgorbatchev.com/SyntaxHighlighter/)

**Author:** Bob Ray <http://bobsguides.com> [Bob's Guides](http://bobsguides.com)

Documentation is available at [Bob's Guides](http://bobsguides.com/syntaxhighlighter-tutorial.html)

SyntaxHighlighter is fairly straight port of Alex Gorbatchev's great JS syntax highlighter, adapted for MODX Revolution. The package includes both a plugin and a snippet version of the highlighter. All of the code in this component, other than the plugin, snippet, and install script, was written by Alex Gorbatchev.

##Usage
###Step 1

Add the SyntaxHighlighter snippet on the page that needs syntax highlighting.

[[!SyntaxHighlighter? &brushes=`{BRUSH,BRUSH}` &theme=`{THEME}`]]

1. `&brushes` - Default: `JScript,Xml,Php,Css,Plain`
2. `&theme` - Default: `Default`

**List of available brushes:**

AppleScript, AS3, Bash, ColdFusion, Cpp, CSharp, Css, Delphi, Diff, Erlang, Groovy, Java, JavaFX, JScript, Perl, Php, Plain, PowerShell, Python, Ruby, Sass, Scala, Sql, Vb, Xml

**List of available themes:**

Default, Django, Eclipse, Emacs, FadeToGrey, MDUltra, Midnight, RDark

###Step 2

Wrap your code in a `<pre>` tag and specify the brush along with additional options found [here](http://alexgorbatchev.com/SyntaxHighlighter/manual/configuration/)

**Example:**

	<pre class="brush: jscript; toolbar: false;">
	console.log('Hello World!');
	</pre>