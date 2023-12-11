
```bash
break #Bricht den Loop sofort ab.
continue #Springt zur nächsten Iteration des Loops.
exit #Beendet das Skript.
```

###### While:
```bash
while [ Bedingung ]; do
  # Anweisungen
done
```

###### Verschachtelter Loop:
```bash
i=1
while [ $i -le 10 ]; do
  echo "$i"
  j=1
  while [ $j -le 10 ]; do
    echo -n " "
    j=$((j + 1))
  done
  echo
  i=$((i + 1))
done
```

###### Case:
```bash
tag="Montag"

case $tag in
  Montag)
    echo "Der Tag ist Montag."
    ;;
  Dienstag)
    echo "Der Tag ist Dienstag."
    ;;
  ...)
    echo "Der Tag ist unbekannt."
    ;;
esac
```

###### Select:
```bash
echo "Bitte geben Sie Ihre Lieblingsfarbe ein:"

select farbe in
  rot
  grün
  blau
do
  echo "Ihre Lieblingsfarbe ist $farbe."
  break
done

```