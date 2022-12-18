# rsschool-cv

## **Roman Barkovets**

### **Contacts**

- **Location:** Minsk, Belarus
- **GitHub:** [DingDogen](https://github.com/DingDogen)
- **LinkedIn:** [Roman Barkovets](https://www.linkedin.com/in/romanbarkovets/)
- **Telegram:** @dingdogen
- **Discord:** Uranum #7150 (in RSS Discord: Raman(@DingDogen))
- **E-mail:** romanbarkovets@yandex.ru

### About me

I am student of Belarusian National Technical University.
In university I got basic knowledges about C++, Python, Assembler, C#, Computer Sciense and Software development technology.
My current goal is learn JavaScript + HTML + CSS because I want to become Front-End Developer.  
As a person I am quite calm and diligent but I don't like super-big difficulties.

### Skills

- Basic knowledges about C++ and Python;
- C# + Windows Forms Pre-Intermediate(my opinion)
- Photoshop
- Git basics
- Visual Studio

### Code example

```C#
        private int CountNeighbours(int x, int y)
        {
            int count = 0;
            for (int i = -1; i < 2; i++)
            {
                for (int j = -1; j < 2; j++)
                {
                    int col = (x + i + columns) % columns;
                    int row = (y + j + rows) % rows;

                    bool IsSelfChecking = col == x && row == y;
                    bool hasLife = field[col, row];

                    if (hasLife && !IsSelfChecking)
                    {
                        count++;
                    }
                }
            }

            return count;
        }
```

### Work experience

- [Conway's Game of Life](https://github.com/DingDogen/Conway-s-Game-Of-Life)
- [Tic-Tac Toe](https://github.com/DingDogen/Tic-Tac-Toe)

### Education

- Belarusian National Technical University, Software Engineer (current time);
- Microsoft Learn Power BI course (beginner level);

### Languages

- Russian - native
- Belarusian - Belarusian language school
- English - A2
