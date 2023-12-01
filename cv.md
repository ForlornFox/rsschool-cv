# Ilya Vlasov
## Contact information
* Location: Russia, Ekaterinburg
* Phone: +7-902-259-30-71
* Email: zzennoxx@mail.ru
* GitHub: [ForlornFox](https://github.com/ForlornFox)
* Telegram: @Forlorn_Fox
* Discord: for1orn
## About me
I am 22 years old. I graduated from the Ural State College named after Polzunov with a degree in Information Security. After finishing my studies, I realized that I had made a mistake in choosing a profession. Although I learned a lot of skills, I was always more drawn to programming. Now I am striving for self-development and I hope that rsschool courses will help me with this.
## Skills
* JavaScript
* C++
* Git/GitHub
* Photoshop
## Code Example
```
function high(string){
  let words = string.split(' '); // Splitting a string into an array of words 
  let high_score = 0;
  let high_word = '';
  for (let i = 0; i < words.length; i++) { // Search for the highest score word
    let nums = words[i].toLowerCase().split('').map(char => char.charCodeAt() - 96);
    let score = nums.reduce(function(x, y){return x + y;}, 0);
    if (score > high_score) {
      high_score = score;
      high_word = words[i];
    }  
  }
  return high_word; 
}
```
## Education
Secondary vocational education at Polzunov Ural State College
## Languages
* Russian: native speaker
* English: A2 (keep learning)