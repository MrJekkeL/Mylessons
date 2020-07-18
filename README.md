let currentMonth = 0;
let depositMonths = 12;
let percentPerMonths = 2;
let startCapital = 500;
let prevMonth = 0;

    
for (currentMonth; currentMonth < depositMonths; currentMonth++) {
    
 prevMonth = prevMonth + ((startCapital + prevMonth) / 100 * percentPerMonths);

console.log('ИТОГО: ' + (prevMonth + startCapital))
}
