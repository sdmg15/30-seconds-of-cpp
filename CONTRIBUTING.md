
## Welcome :smile:
### To start contributing follow below steps :point_down::

1. Star :star: the Repository.
2. Fork :fork_and_knife: it.
3. Create Branch with your feature `<feature>`.
4. Push Changes.
5. Send Pull Request :smile:.
6. Enjoy Contributing :yum:.

For Adding functions in **header.md** files, 
Use the below template (Copy from Raw Format): 

```
# name
**Description :**  < description >.
  
**Example** :

```cpp
    std::vector<int> v{ 1, 2, 3, 4, 4, 3, 7, 8, 9, 10 };
 
    // determine how many integers in a std::vector match a target value.
    int target1 = 3;
    int num_items1 = count(v.begin(), v.end(), target1);
    cout << "number: " << target1 << " count: " << num_items1 << '\n';
 ```

---

# Style Guide
Follow this style guide to add sample programs.

1. Naming Style : 
    Name your program just the same as listed in the header.md file 

2. Comment Header:Add the following comment header in every program.The comment header should always be at the top of program.
```cpp
/*
    Author : this must be your name ;)
    Date : Date format dd/mm/yyyy
    Time : Time format hh:mm
    Description : description should be small & one liner.
*/
```
 

3. Add Opening braces on the same line.
```cpp
    int main()
    {
                            // DO NOT DO THIS    
    }

    int main(){
                            // DO THIS.
    }
```
4. Use **1 Tab** or **4 Spaces**. Be consistent with whatever you choose
    Use only one indenting format for the whole program.

5. Add appropriate comments wherever necessary to explain the code.
> Programs wth NO Comments at all will not be merged.

6. Expression should be readable, Use 1 space between different TOKENS.
```cpp 
    galaxy=stars+asteroids          // DO NOT USE THIS FORMAT.
    galaxy = stars + asteroids      // USE THIS FORMAT.
```
7. Always add braces in a for/while loop even its a one liner loop.
```cpp    
    for(int i=0;i<45;i++)
        cout<<i<<" ";               //DO NOT DO THIS.
    
    for(int i=0;i<45;i++){
        cout<<i<<" ";               //DO THIS.
    }
```


