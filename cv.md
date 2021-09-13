# Andrey Kashkovskii
## My contact info:
* Tel: +380675720155 ![phone_logo](img\phoneicons.png)
* Telegram: @AndreyKashk ![telega_logo](img\telegram_icon.png)
* Email: andreykashk@gmail.com ![email_logo](img\emailgmaillogo.png)
* GitHub: [andreykashk](https://github.com/andreykashk) ![github_logo](img\githublogo.png)
## about me and __JavaScript__
Recently interested in automating browser actions and after several _successful and simple_ projects, I realized that without JS, nowhere
## __Skills:__
* HTML
* CSS
* JavaScript Basic
* Xpath
* BAS [(Browser Automation Studio)](https://bablosoft.com/shop/BrowserAutomationStudio#)
## _Code examples:_
```
function revrot(str, sz) {
    if (sz <= 0 || str === '' || str.length < sz) {
    return ''
  }

  const reg = new RegExp(`.{1,${sz}}`, 'g');  
  let chunks = str.match(reg);

  chunks = chunks.map(function(item){
    if (item.length < sz) {
      return ''
    };
    let sum = 0;

    for (let i = 0; i < item.length; i++) {
      sum = Math.pow(item[i], 3) + sum;
    };
    let arr;
    if (Number.isInteger(sum/2)) {
      arr = item.split('').reverse().join('');
      return arr;
    } else {
      arr = item.split('');
      let res = arr.shift();
      arr.push(res);
      return arr.join('');
          
    };
  })
  
  return chunks.join('');
}
```

## Education and courses:
1. The Complete JavaScript Course - Udemy
1. YouTube courses
1. JavaScript Manual on <https://learn.javascript.ru>  


## Languages:
* Russian - native
* Ukrainian - Intermediate
* English - level A1