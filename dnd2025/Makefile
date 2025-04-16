index.html: chargen.md
	sed -E 's/(.*)%MARKDOWN%(.*)/echo "\1$$(markdown -html5 chargen.md)\2"/e' template.html > index.html
