
```sh
# Capítulos
sed -i 's/.*\*\*\([0-9]\+\)\.\(..\)\(.*\)\*\*\(.*\)/## \u\2\L\3\ \4 % Bruno: Cap.\1/' 07.md 

# Partes
	

perl -p -e 's/(AAA.*)\n/\1/' test.md
```
