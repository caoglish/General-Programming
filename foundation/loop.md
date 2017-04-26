# Loop

## Iterator(foreach):

### Python

```python
for i in [1,2,3,4]:
    print(i)

```

### PHP

```php
<?php
foreach([1,2,3,4] as $i){
    echo $i;
}
```

### JavaScript

```javascript
for(let i in [1,2,3,4]){
  console.log(i);
}
```

## increment inner loop(for)

### Python

```python
for i in range(0,6,1):
    print(i)
```

### PHP

```php
<?php
for($i=0;$i<10;$i++){
    echo $i;
}
```

### JavaScript

```javascript
for(let i=0;i<10;i++){
    console.log(i)
}
```

## Conditional loop

```while(condition)``` syntax defined the loop with condition.

### Python

```python
i=0
while(i<10):
    print(i)
    i += 1

```

### PHP

```php

<?php
$i=0;
while($i<10){
    echo $i++;
}

```

### JavaScript

```javascript

let i=0;
while(i<10){
    console.log(i++);
}

```
----
```do while(condition)``` syntax defined the loop run at least once with condition.

### Python
```python
#python did not have do-while syntax, need hack way to do it.
i = 0;
while True:
	print(i)
	i += 1
	if i >= 10:
		break

```

### PHP
```php
<?php
$i=0;
do
{
	echo $i++;
}while($i<10);
```

### JavaScript
```javascript
let i=0;
do
{
	console.log(i++);
}while(i<10)
```
