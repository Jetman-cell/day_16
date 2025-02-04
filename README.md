# day_16
    //Обьекты

const phoneBook = {
  list: {
  "Peter Naumow" : +78952425388,
  "Julia" : +495627856321,
  "Dmitriy" : +7529754123,
  "Donald Trump" : +16457358678,
  "Helena More": +5297462351,
  "Peter Ivanov" : 587431225
   },
   log() {
    console.log (this.list)
   }
};

phoneBook.log();

let a = 1;
let b = a; // здесь копируем значения переменной "а" в переменную "b"
console.log(a, b) // 1 1 
a = 0; // поменяем только одну из переменных 
console.log(a, b) // 0 1 - изменится только a, b останется нетронутой
    
    
