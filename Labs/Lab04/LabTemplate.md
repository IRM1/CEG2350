## Lab 04

- Name:
- Email: 

## Part 1 Answers

1. `grep -P '[xX]\d{4}$' grepdata.txt`
2. `grep -P '[Cc][Aa]' grepdata.txt`
3. `grep -P '[@]' grepdata.txt`
4. ` grep -P '\b(?:Jan|Feb|Mar|Apr|May|Jun|Jul|Aug|Sep|Oct|Nov|Dec)\. \d{1,2}, 20\d{2}\b' grepdata.txt`
## Part 2 Answers

1.`sed -i 's/<\/[^>]*>//g' sedfile.md`
2.`sed -i 's/\s*<li>/- /g' sedfile.md`
3.` sed -i 's/<h1>/# /g' sedfile.md`
4.`sed -i 's/<h2>/## /g' sedfile.md`
5.`sed -i 's/<ul>//g; s/<html>//g' sedfile.md`
6.  `sed -i 's/Batches/Matches/g' sedfile.md`
7. (Optional notes if needed)

## Part 3 Answers

1.` awk '/^Bil.*/{print $1}' records.txt`
2.` awk '$4==42{print $3}' records.txt`
3.`awk '$3 ~/.*@wright\.edu/ {print $2", "$1":",$3}' records.txt`
4.`awk '$3 ~/.*wright\.edu/ && $6 ~/1234/ {print $2" favorite number is:"$4}' records.txt`
5.`awk '{gsub($6, "NOT@PL@!NP@$$WORD"); print $0}' records.txt > updatedrecords.txt`
