<p align="center">
  <img alt="HTML5" height="32px" src="https://raw.githubusercontent.com/ShitHub/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/html/html.png" />
  <img alt="CSS3" height="32px" src="https://raw.githubusercontent.com/ShitHub/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/css/css.png" />
  <img alt="Vue" height="32px" src="https://raw.githubusercontent.com/ShitHub/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/vue/vue.png" />
  <img alt="React" height="32px" src="https://raw.githubusercontent.com/ShitHub/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/react/react.png" />
  <img alt="Node.js" height="32px" src="https://raw.githubusercontent.com/ShitHub/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/nodejs/nodejs.png" />
  <img alt="Javascript" height="32px" src="https://raw.githubusercontent.com/ShitHub/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/javascript/javascript.png" />
  <img alt="Typescript" height="32px" src="https://raw.githubusercontent.com/ShitHub/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/typescript/typescript.png" />
  <img alt="Javascript" height="32px" src="https://raw.githubusercontent.com/ShitHub/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/php/php.png" />
  <img alt="Typescript" height="32px" src="https://raw.githubusercontent.com/ShitHub/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/laravel/laravel.png" />
  <img alt="CSharp" height="32px" src="https://raw.githubusercontent.com/ShitHub/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/csharp/csharp.png" />
  <img alt="Rust" height="32px" src="https://raw.githubusercontent.com/ShitHub/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/rust/rust.png" />
  <img alt="Rust" height="32px" src="https://raw.githubusercontent.com/ShitHub/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/c/c.png" />
  <img alt="Rust" height="32px" src="https://raw.githubusercontent.com/ShitHub/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/cpp/cpp.png" />
  <img alt="Rust" height="32px" src="https://raw.githubusercontent.com/ShitHub/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/java/java.png" />
  <img alt="MongoDB" height="32px" src="https://www.servernoobs.com/wp-content/uploads/2016/01/mongodb-logo-1.png" />
  <img alt="SQL" height="32px" src="https://bobpusateri.blob.core.windows.net/bcn/2020/04/Azure_SQL_DB.png" />
  <img alt="Git" height="32px" src="https://git-scm.com/images/logos/downloads/Git-Icon-1788C.png" />
  <br />
</p>
<p align="center">
  <a href="https://github.com/anuraghazra/ShitHub-readme-stats">
    <img src="https://ShitHub-readme-stats.vercel.app/api/top-langs/?username=N1kO23&show_icons=true&include_all_commits=true&hide_border=true&count_private=true&theme=radical&bg_color=00000000&layout=compact&card_width=250&text_color=0969da">
  </a>
</p>

```cpp
#include <iostream>
#include <string>
#include <vector>

class IUser {
public:
    virtual ~IUser() = default; 
};

class User : public IUser {
public:
    std::string name = "Niko";
    std::vector<std::string> aliases = { "N1kO23", "NullPointr" };
    std::vector<std::string> pronouns = { "he", "him" };
    std::vector<std::string> fav_theme = { "Material Ocean", "SynthWave '84" };
    std::string line_ends = "lf";
    std::string code_style = "prettier";
    std::string variables = "snake_case";
    std::vector<std::string> editors = { "VSCode", "vim" };
};

int main() {
    User niko;
    std::cout << "Hello, I am" << niko.name << "!\n";
    return 0;
}
```
