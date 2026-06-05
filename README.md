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
