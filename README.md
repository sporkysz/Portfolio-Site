# Portfolio-Site


 * Github Repo sisteminin api kullanmamız için gerekli komut.
  ```html
 const apiUrl = `https://api.github.com/users/${username}/repos`;
```



* Github repo'lardan kaç tanesinin gözükmesini istediğinizi ayarlayabilmenize yarayan kısımdır. 
* 6 sayısını kaç yaparsanız o kadar repo site de gözükecektir.
 ```html
repos.slice(0, 6).forEach(repo => {
```
