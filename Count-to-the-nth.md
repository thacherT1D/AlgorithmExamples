```
var n = 231;


function count(n) {
    for (var i = 1; i < n + 1; i++) {
    var lastNum = i % 10;

        if(i === 11) {
            console.log(i + 'th');
        } else if (i === 12) {
            console.log(i + 'th');
        } else if (i === 13) {
            console.log(i + 'th');
        } else if (lastNum === 1) {
            console.log(i + 'st');
        } else if (lastNum === 2) {
            console.log(i + 'nd');
        } else if (lastNum === 3) {
            console.log(i + 'rd');
        } else {
            console.log(i + 'th');
        }
    }

}

count(n);
```
