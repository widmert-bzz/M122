######  User Input:
```bash 
read USER_INPUT  
```

```bash
echo -n "Geben Sie Ihren Name ein: "  
read USER_INPUT  
echo "Guten Morgen ${USER_INPUT}!"
```

###### Local variables:
```bash
animal="Tiger"
function f1{
	local animal="Goat"
	echo $animal
}

f1
echo $animal
```

