# FreeCodeCamp-5



81    const HIGH_TEMPERATURES = {
  yesterday: 75,
  today: 77,
  tomorrow: 80
};

// Only change code below this line

const {today,tomorrow} = HIGH_TEMPERATURES;


// Only change code above this line


82   const HIGH_TEMPERATURES = {
  yesterday: 75,
  today: 77,
  tomorrow: 80
};

// Only change code below this line
  
const {today:highToday,tomorrow:highTomorrow } = HIGH_TEMPERATURES;


// Only change code above this line


83   const LOCAL_FORECAST = {
  yesterday: { low: 61, high: 75 },
  today: { low: 64, high: 77 },
  tomorrow: { low: 68, high: 80 }
};

// Only change code below this line
  
const {today: {low:lowToday, high:highToday} } = LOCAL_FORECAST;


// Only change code above this line


84  let a = 8, b = 6;


// Only change code below this line

[a,b]=[b,a]



85   const source = [1,2,3,4,5,6,7,8,9,10];
function removeFirstTwo(list) {

  // Only change code below this line
  const [a,b,...arr] = list  ; // Change this line
  // Only change code above this line
  return arr; 
}
const arr = removeFirstTwo(source);



86  const stats = {
  max: 56.78,
  standard_deviation: 4.34,
  median: 34.54,
  mode: 23.87,
  min: -0.75,
  average: 35.85
};

// Only change code below this line
const half = ({max, min}) => (max + min )/ 2.0; 
// Only change coХde above this line


87   const result = {
  success: ["max-length", "no-amd", "prefer-arrow-functions"],
  failure: ["no-var", "var-on-top", "linebreak"],
  skipped: ["no-extra-semi", "no-dup-keys"]
};
function makeList(arr) {
  // Only change code below this line
  const failureItems = [];
  for(let i = 0; i< arr.length; i++){
    failureItems.push(`<li class="text-warning">${arr[i]}</li>`);
  }
  // Only change code above this line

  return failureItems;
}

const failuresList = makeList(result.failure);


88  const createPerson = (name, age, gender) => {
  // Only change code below this line
  return ({name,age,gender})
  // Only change code above this line
};


89   // Only change code below this line
const bicycle = {
  gear: 2,
  setGear(newGear) {
    this.gear = newGear;
  }
};
// Only change code above this line
bicycle.setGear(3);
console.log(bicycle.gear);


90  // Only change code below this line

// Only change code above this line
class Vegetable {
 constructor(name) { 
   this.name = name
   }
   
 }
 const carrot = new Vegetable("carrot");
console.log(carrot.name); // Should display 'carrot'



91   // Only change code below this line
class Thermostat {
  constructor(fahrenheit) {
    this.fahrenheit = fahrenheit;
  }
  
  get temperature() {
    return (5 / 9) * (this.fahrenheit - 32);
  }
  
  set temperature(celsius) {
    this.fahrenheit = (celsius * 9.0) / 5 + 32;
  }
}
// Only change code above this line

const thermos = new Thermostat(76); // Setting in Fahrenheit scale
let temp = thermos.temperature; // 24.44 in Celsius
thermos.temperature = 26;
temp = thermos.temperature; // 26 in Celsius


92  <html>
<body>
  <!-- Only change code below this line -->
<script type = "module" src = "index.js"></script>
  <!-- Only change code above this line -->
</body>
</html>


93
