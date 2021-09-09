# assignment2-nagireddy
# Akhil Reddy Nagireddy
### My Favourite place ,i wish to visit in my life is Amazon Forests
Amazon forests are the **most unexplored**,the remoteness in that place makes us feel everybit of **peace** and **wildlife**.<br>
**I used bold for above line and this line**

---
# Directions from Maryville to Newyork city,Statue of liberty
1. From Missouri to newyork by car
2. trip begins in the state of Missouri. It ends in the state of New York
3. total driving distance from Missouri to New York is 1,115 miles or 1 794 kilometers
4. U can also take plane from kansas city to Newyork.
5. Start at Maryville,wallmart and go staraight to kansas city
6. book a flight ticket and take a boarding pass
7. get into the plane and have an nap
   1. have some food 
   2. watch some content and entertain yourself.
   3. wakeup when the plane arrives newyork airport
   4. Get out of the airport.
   5. take a cab
   6. go to statue of liberty
   7. Have fun

* have Backpacks, strollers for kids
* take big umberellas,
* A camera to take pics
* All the above items are not allowed at the Statue of liberty location
* Don't forget to take id for sure.
* Minors are not required to take any id

[Link of Aboutme](https://github.com/nagireddyakhilredddy/assignment2-nagireddy/blob/main/AboutMe.md)


-----------------------------
## Tables

 The Table here shows the best food to try once in a lifetime,that I would recommend someone.

  | Food              | Location                |  Amount  |
  | ---               | ---                     |---       |
  |Chefs Biryani      |Hyderabad                | $15      |
  |Biscuits           |Charminar                | $5       |
  |Kaju Chicken       |Kritunga,Hyderabad       | $14      |
  |Mutton Biryani     |Mehfil Restaurant        | $13      |
  |Pav Bhaji          |Mumbai                   | $5       |

  ---------------------------

  # Pithy quotes

  > Money is a tool, so I don't have to be. - *Eddie Mumford*

  >Nobody reaches anywhere by believing. - *Osho*

  ------

  # code fencing

   
Hashing is an algorithm that calculates a fixed-size bit string value from a file. A file basically contains blocks of data. Hashing transforms this data into a far shorter fixed-length value or key which represents the original string. ... A hash is usually a hexadecimal string of several characters.

Source:https://www.2brightsparks.com/resources/articles/introduction-to-hashing-and-its-uses.html



  long long compute_hash(string const& s) {
    const int p = 31;
    const int m = 1e9 + 9;
    long long hash_value = 0;
    long long p_pow = 1;
    for (char c : s) {
        hash_value = (hash_value + (c - 'a' + 1) * p_pow) % m;
        p_pow = (p_pow * p) % m;
    }
    return hash_value;
}

code source: https://cp-algorithms.com/string/string-hashing.html