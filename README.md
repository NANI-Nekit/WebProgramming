# KRAVCHENKO NIKITA
## PROFESSIONAL TITLE
***
## ABOUT ME
### A novice specialist in the field of back end development  motivated to develop his skills in this field  and work on projects designed to improve the daily life of society
![](ava.jfif)
### 
***
## KNOWLEDGE AND PROGRESS
- [x] completed lyceum of BRU
- [x] studying at the bru
- [x] the basic concept of back-end development
- [x] programming microcontrollers
## SOFTWARE SKILLS
+ Arduino IDE
+ Eclipse
+ Visual Studio / VS Code
+ Arduino IDE
+ ERP Systems
+ Android Studio
+ Unity
## Example of Code
```
        static void Main(string[] args)
        {
            while (true)
            {
                Console.Clear();
                Console.Write("операция факториал\nвведите число N = ");
                uint n = Convert.ToUInt32(Console.ReadLine());
                uint result = n;
                ReturnFuctorial(ref n, ref result);
                Console.WriteLine("N! = " + result);
                Console.WriteLine("1 - повторить\n2 - выход");
                string s = Console.ReadLine();
                switch (s)
                {
                    case "1":break;
                    case "2":return;
                }
            }
        }
        static void ReturnFuctorial(ref uint n, ref uint result)
        {
            if (n != 0)
            {
                n--;
                result *= n;
                while (n - 1 != 0)
                {
                    ReturnFuctorial(ref n, ref result);
                }
            }
            else result = 1;
        }
```
### MY CONTACTS
[E-mail](https://mail.google.com/mail/u/0/#search/nikitakosmochev957%40gmail.com)

