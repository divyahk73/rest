1.[link](https://edabit.com/challenge/uAGzHNBWbNj2iNqLr)
```javascript
function bbqSkewers(grill) {
	return [grill.length - grill.filter(x=>x.includes('-x')).length, grill.filter(x=>x.includes('-x')).length];
}
```
