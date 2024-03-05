### Nama: Ansellma Tita Pakartiwuri Putri
### NIM: 10231017
---
1. Pengalaman saya apa ya gatau bang ga perhatiin eh

2.     
   1. Buat suatu object kosong (tanpa property apapun)
      dengan nama `Person1`.  

      ```js
      const Person1 = {};
      ```
   2. Cetak object `Person1` tersebut di console
        ```js
        let Person1 = {};
        console.log(Person1);
        ```

   3. Tambahkan properties berikut:
       ```
        name: "Anastashia",
        height: "178 cm",
        weight: "60 kg",
        skill: "photography, cosplayer"
       ```

       ```js
       let Person1 = {
       name: "Anastashia",
       height: "178 cm",
       weight: "60 kg",
       skill: "photography, cosplayer"
       };
        console.log(Person1);
       ```
   4. Tampilkan nilai nya saja dari properties yang telah ditambahkan

        ```js
        let Person1 = {
       name: "Anastashia",
       height: "178 cm",
       weight: "60 kg",
       skill: "photography, cosplayer"
       };

       let name = Person1.name;            
       let height = Person1.height;
       let weight = Person1.weight;
       let skill = Person1.skill;
       console.log(name, height, weight, skill);
        ```
        
   5. Gandakan `Person1` ke `Person2` dan gunakan data berikut:
       ```
        name: "Kyrlov",
        height: "188 cm",
        weight: "78 kg",
        skill: "game developer, procedural animation"
       ```

        ```js
        let Person1 = {
       name: "Anastashia",
       height: "178 cm",
       weight: "60 kg",
       skill: "photography, cosplayer"
       };

       let Person2 = {
        name: "Kyrlov",
        height: "188 cm",
        weight: "78 kg",
        skill: "game developer, procedural animation"
       };
        ```

   6. Tukarkan data-data `Person1` ke `Person2` demikian pula sebaliknya.   
       *Petunjuk*: Gunakan *destructuring assignment*.

     ```js
     let Person1 = {
        name: "Anastashia",
        height: "178 cm",
        weight: "60 kg",
        skill: "photography, cosplayer"
    };

    let Person2 = {
        name: "Kyrlov",
        height: "188 cm",
        weight: "78 kg",
        skill: "game developer, procedural animation"
    };
        
    // Destructuring assignment to swap values
    [Person1, Person2] = [Person2, Person1];
    ```

   7. Cetak object `Person1` dan `Person2` ke console.

    ```js
    let Person1 = {
        name: "Anastashia",
        height: "178 cm",
        weight: "60 kg",
        skill: "photography, cosplayer"
    };
    
    let Person2 = {
        name: "Kyrlov",
        height: "188 cm",
        weight: "78 kg",
        skill: "game developer, procedural animation"
    };
    
    // Destructuring assignment to swap values
    [Person1, Person2] = [Person2, Person1];

    console.log("Person1:", Person1);
    console.log("Person2:", Person2);
    ```
        