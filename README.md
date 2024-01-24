
<p>
    <a href="#"><img src="https://img.shields.io/github/followers/777-FOXik-777?style=social&label=follow"></a>
    <a href="#"><img src="https://img.shields.io/github/stars/777-FOXik-777?style=social"></a>
</p>


<hr />
<p align=center>
    <a href="https://t.me/SYPEXHACK" target="_blank"><img
            src="https://img.shields.io/badge/Telegram-%232CA5E0?style=for-the-badge&logoColor=white&logo=telegram"
            alt="Telegram"></a>
</p>
<hr />


<br/>

### `Информация о системе`
<h3 align="center">
    
<table border="1">
  <tr>
    <th>Девайсы</th>
    <th>Операционка</th>
    <th>Процесор</th>
  </tr>
  <tr>
    <td>Ноутбук</td>
    <td>Windows 11 Pro</td>
    <td>Intel Core i5</td>
  </tr>
  <tr>
    <td>Samsung Galaxy</td>
    <td>Android 14, OneUI 6</td>
    <td>Unisoc</td>
  </tr>
</table>

<h3>

<hr />















- uses: Platane/snk@v3
  with:
    # github user name to read the contribution graph from (**required**)
    # using action context var `github.repository_owner` or specified user
    github_user_name: ${{ github.repository_owner }}

    # list of files to generate.
    # one file per line. Each output can be customized with options as query string.
    #
    #  supported options:
    #  - palette:     A preset of color, one of [github, github-dark, github-light]
    #  - color_snake: Color of the snake
    #  - color_dots:  Coma separated list of dots color.
    #                 The first one is 0 contribution, then it goes from the low contribution to the highest.
    #                 Exactly 5 colors are expected.
    outputs: |
      dist/github-snake.svg
      dist/github-snake-dark.svg?palette=github-dark
      dist/ocean.gif?color_snake=orange&color_dots=#bfd6f6,#8dbdff,#64a1f4,#4b91f1,#3c7dd9
