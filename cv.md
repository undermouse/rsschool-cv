# Alexey Smirnov

## Contacts:
#### E-mail: plur@live.ru
#### Tel: +79000013576
#### Discord: @undermouse
#### Codewars: https://www.codewars.com/users/undermouse/
---

## About me:
<p>Graduated from RANEPA in 2014. I have been doing 1C and system administration for the last 10 years. I've always wanted to do frontend and I think the time has come.</p>

## Skills: 
- Git
- JavaScript (beginner)
- CSS 3 / HTML 5
- Webpack
- Python (beginner)

## Education:
- RANEPA '14
- Rolling Scopes School Stage#0 '22

## Projects:
https://github.com/undermouse/momentum

## Code example:
```
function formatDuration(seconds) {
  if (seconds === 0) return 'now';
  let s = seconds % 60;
  seconds = (seconds - s) / 60;
  let m = seconds % 60;
  seconds = (seconds - m) / 60;
  let h = seconds % 24;
  seconds = (seconds - h) / 24;
  let d = seconds % 365;
  seconds = (seconds - d) / 365;
  let y = seconds;

  let human = [];
  if (y) human.push(y + ' year' + (y > 1 ? 's' : ''));
  if (d) human.push(d + ' day' + (d > 1 ? 's' : ''));
  if (h) human.push(h + ' hour' + (h > 1 ? 's' : ''));
  if (m) human.push(m + ' minute' + (m > 1 ? 's' : ''));
  if (s) human.push(s + ' second' + (s > 1 ? 's' : ''));

  return human.join(', ').replace(/,([^,]*)$/, ' and$1');
}
```

## English:
**B1-B2**<p> I can easily read and write in English (technical and fiction). Colloquial is a little worse.</p>









