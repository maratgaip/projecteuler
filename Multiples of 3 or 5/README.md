```javascript
function multiples(n) {
	sum = 0;
	for (var i=0; i< n; i++) {
		if (i%3==0 || i%5==0) {
			sum=sum+i;
		}
	}
	return sum;
}
```
