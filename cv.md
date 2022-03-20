# Alexander Markov
---
### Contact information:

**Phone:** +375 29 6107172<br>
**E-mail:** advisor@tut.by<br>
**Telegram:** @ADVISOR_BY<br>
[VK](https://vk.com/advisorby)

---

### Briefly About Myself:

---

### Skills and Proficiency:


---

### Code example:


```
function duplicateCount(text){
    arr = text.toUpperCase().split('');
    count = arr.reduce((arr_tmp, x) => (arr_tmp[x] = (arr_tmp[x] || 0) + 1, arr_tmp), {});
    duplicate = Object.values(count).filter(x => x > 1);
    return duplicate;
}
```
---