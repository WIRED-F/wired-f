# 💫 About Me:
CURRENTLY STUDYING MAPUA COLLEGE


## 🌐 Socials:
[![Pinterest](https://img.shields.io/badge/Pinterest-%23E60023.svg?logo=Pinterest&logoColor=white)](https://pinterest.com/https://pin.it/1m28IpUcS) 

# 💻 Tech Stack:
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) ![PowerShell](https://img.shields.io/badge/PowerShell-%235391FE.svg?style=for-the-badge&logo=powershell&logoColor=white) ![Bash Script](https://img.shields.io/badge/bash_script-%23121011.svg?style=for-the-badge&logo=gnu-bash&logoColor=white) ![Windows Terminal](https://img.shields.io/badge/Windows%20Terminal-%234D4D4D.svg?style=for-the-badge&logo=windows-terminal&logoColor=white)
# 💻 Tech Stack:
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) ![PowerShell](https://img.shields.io/badge/PowerShell-%235391FE.svg?style=for-the-badge&logo=powershell&logoColor=white) ![Bash Script](https://img.shields.io/badge/bash_script-%23121011.svg?style=for-the-badge&logo=gnu-bash&logoColor=white) ![Windows Terminal](https://img.shields.io/badge/Windows%20Terminal-%234D4D4D.svg?style=for-the-badge&logo=windows-terminal&logoColor=white)
# 💻 Tech Stack:
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) ![PowerShell](https://img.shields.io/badge/PowerShell-%235391FE.svg?style=for-the-badge&logo=powershell&logoColor=white) ![Bash Script](https://img.shields.io/badge/bash_script-%23121011.svg?style=for-the-badge&logo=gnu-bash&logoColor=white) ![Windows Terminal](https://img.shields.io/badge/Windows%20Terminal-%234D4D4D.svg?style=for-the-badge&logo=windows-terminal&logoColor=white)
# 📊 GitHub Stats:
![](https://github-readme-stats.vercel.app/api?username=WIRED-F&theme=shadow_green&hide_border=true&include_all_commits=false&count_private=false)<br/>
![](https://nirzak-streak-stats.vercel.app/?user=WIRED-F&theme=shadow_green&hide_border=true)<br/>
![](https://github-readme-stats.vercel.app/api/top-langs/?username=WIRED-F&theme=shadow_green&hide_border=true&include_all_commits=false&count_private=false&layout=compact)

## 🏆 GitHub Trophies
![](https://github-profile-trophy.vercel.app/?username=WIRED-F&theme=highcontrast&no-frame=true&no-bg=false&margin-w=4)

### ✍️ Random Dev Quote
![](https://quotes-github-readme.vercel.app/api?type=horizontal&theme=radical)

### 🔝 Top Contributed Repo
![](https://github-contributor-stats.vercel.app/api?username=WIRED-F&limit=5&theme=dark&combine_all_yearly_contributions=true)

---
[![](https://visitcount.itsvg.in/api?id=WIRED-F&icon=2&color=3)](https://visitcount.itsvg.in)

  ## 💰 You can help me by Donating
  [![PayPal](https://img.shields.io/badge/PayPal-00457C?style=for-the-badge&logo=paypal&logoColor=white)](https://paypal.me/@Feybruce) 

  
<!-- Proudly created with GPRM ( https://gprm.itsvg.in ) -->
#include <iostream>
#include <string>

class HackerProfile {
private:
    std::string name;
    std::string alias;
    std::string favoriteLanguage;
    int yearsOfExperience;
    bool likesCoding;

public:
    HackerProfile(std::string n, std::string a, std::string lang, int exp, bool likes)
        : name(n), alias(a), favoriteLanguage(lang), yearsOfExperience(exp), likesCoding(likes) {}

    void displayProfile() const {
        std::cout << "Hacker Profile:\n";
        std::cout << "Name: " << name << "\n";
        std::cout << "Alias: " << alias << "\n";
        std::cout << "Favorite Programming Language: " << favoriteLanguage << "\n";
        std::cout << "Years of Experience: " << yearsOfExperience << "\n";
        std::cout << "Likes Coding: " << (likesCoding ? "Yes" : "No") << "\n";
    }
};

int main() {
    HackerProfile hacker("Alice", "CyberShadow", "C++", 5, true);
    hacker.displayProfile();
    return 0;
}
