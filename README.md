## Welcome to Dfish_Z Pages

Time will tell you the love for the simple things lasts long and the people loving you are the warmest.

- YY Group: M8808633
- Steam: Dfish_Z
- Weibo: [pemodeyu](http://weibo.com/penmodeyu)

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your repository settings. The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Binary Search

There are numerous variations of binary search. In particular, fractional cascading speeds up binary searches for the same value in multiple arrays.

```javascript
function binary_search(arr, key) {
    var low = 0, high = arr.length - 1;
    while(low <= high){
        var mid = parseInt(low + (high - low) / 2); 
        if(key === arr[mid]){
            return  mid;
        } else if (key > arr[mid]){
            low = mid + 1;
        } else if (key < arr[mid]){
            high = mid -1;
        } else {
            return -1;
        }
    }
};
```

### Contact

Having trouble with Pages? [contact support](mailto:065193@163.com) and I’ll help you sort it out.
