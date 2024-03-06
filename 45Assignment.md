//QUESTION 1:

//Installed Node.js, Typescript and Visual Studio Codde.


//QUESTION 2:
let name1 = "sir zia khan";
console.log (name1);
    

//QUESTION 3:
function titlecase (name1)
{ 

let title = ""
for (let i = 0; i<= name1.length; i++)
    { 
        let k = name1.charAt(i); 
        
        if (i == 0) 
        {
           title = title.concat(k.toUpperCase())
        }
        else if (name1.charAt(i-1)==" ")
        {
            title = title.concat(k.toUpperCase())
        }
        else {
            title = title.concat(k.toLowerCase())
            }
                  
        
    }
    console.log(`In Upper Case: ${name1.toUpperCase()} `);
    console.log(name1.toLowerCase());
    console.log(title);
}

titlecase(prompt());

//Question 4:

console.log("Muhammad Ali Jinnah said, ",'\n\t"I do not believe in taking the right decision, I take decision and make it right"')

//Question 5:

let famous_Person = "Muhammad Ali Jinnah"
let message = "I do not believe in taking the right decision, I take a decision and make it right"

console.log(`${famous_Person} said, \n\t"${message}"`);

//Question 6:

let name1 = "    saleem       ";

console.log('I am Learning Typescript\n\tMy name is',name1,'yousuf');

console.log(`I am Learning Typescript\n\tMy name is${name1.trim()}yousuf`);


//Question 7 & 8:
console.log(`6+2 = ${6+2}`);
console.log(`9-1 = ${9-1}`);
console.log(`4*2 = ${4*2}`);
console.log(`16/2 = ${16/2}`);

//Question 9:
let favouriteNum = 1;
console.log(`My favourite number is ${favouriteNum}`);


//Question 10:
//MUHAMMAD SALEEM Dated : 01-Mar-2024
//Print a Sentence
console.log('Pakistan Zindabad');


//Question 11:
let names = ['Faisal','Hammad','Ahmed','Mehmood']
console.log(names[0]);
console.log(names[1]);
console.log(names[2]);
console.log(names[3]);


//Question 12:
let names = ['Faisal','Hammad','Ahmed','Mehmood']
console.log(`Mr ${names[0]} you are invited to learn typescript`);
console.log(`Mr ${names[1]} you are invited to learn typescript`);
console.log(`Mr ${names[2]} you are invited to learn typescript`);
console.log(`Mr ${names[3]} you are invited to learn typescript`);

//Question 13:
let transp = ['Motorcycle', ' Car', 'Truck', 'Bicycle'];
console.log("I would like to own suzuki ",transp[0]);
console.log("My favourit",transp[1], "is Fortuner");
console.log('My Friend is Driving Mazda',transp[2]);
console.log('i gifted my son',transp[3],'on his birthday');


//Question 14:
let guest = ['HAMAD','AHMED','SUBHAN'];
console.log ('Dear '+guest[0]+' You are invited at dinner yesterday');
console.log('Dear '+guest[1]+' You are invited at dinner yesterday');
console.log('Dear '+guest[2]+' You are invited at dinner yesterday');



//Question 15:
let guest = ['HAMAD','AHMED','SUBHAN'];
console.log('\nList of Invited People \n\t',guest);

console.log('\nDear '+guest[0]+' You are invited at dinner yesterday');
console.log('Dear '+guest[1]+' You are invited at dinner yesterday');
console.log('Dear '+guest[2]+' You are invited at dinner yesterday');

console.log("\n",guest[1],"Couldn't come for dinner today\n");

guest.splice(1,1,'Jahanzeb');
console.log('List of Invited People \n\t',guest);

console.log('Dear '+guest[0]+' You are invited at dinner yesterday');
console.log('Dear '+guest[1]+' You are invited at dinner yesterday');
console.log('Dear '+guest[2]+' You are invited at dinner yesterday');


//Question 16:
var guest = ['HAMAD','AHMED','SUBHAN'];
console.log('\nList of Invited People \n\t',guest,'\n');

for (let b = 0; b<guest.length; b++) 
{
    console.log('Dear '+guest[b].toUpperCase()+' You are invited at dinner yesterday')
}

console.log("\nANNOUNCEMENT\n",guest[1],"Couldn't come for dinner today\n");

guest.splice(1,1,'Jahanzeb');
console.log('List of Invited People \n\t',guest,'\n');

//Using for Loop 
for (let b = 0; b<guest.length; b++) 
{
    console.log('Dear '+guest[b].toUpperCase()+' You are invited at dinner yesterday')
}

console.log("\nwe have arrange a bigger table for today's dinner\n");

guest.unshift('Yasmeen');
guest.splice(2,0,'Aiman');


for (let b = 0; b<guest.length; b++) 
{
    console.log('Dear '+guest[b].toUpperCase()+' You are invited at dinner yesterday')
}


//Question 17:
var guest = ['HAMAD','AHMED','SUBHAN'];
console.log('\nList of Invited People \n\t',guest,'\n');

for (let b = 0; b<guest.length; b++) 
{
    console.log('Dear '+guest[b].toUpperCase()+' You are invited at dinner yesterday')
}

console.log("\nANNOUNCEMENT\n",guest[1],"Couldn't come for dinner today\n");

guest.splice(1,1,'Jahanzeb');
console.log('List of Invited People \n\t',guest,'\n');

//Using for Loop 
for (let b = 0; b<guest.length; b++) 
{
    console.log('Dear '+guest[b].toUpperCase()+' You are invited at dinner yesterday')
}

console.log("\nwe have arrange a bigger table for today's dinner\n");

guest.unshift('Yasmeen');
guest.splice(2,0,'Aiman');


for (let b = 0; b<guest.length; b++) 
{
    console.log('Dear '+guest[b].toUpperCase()+' You are invited at dinner yesterday')
}
console.log('\n',guest);
console.log("ANNOUNCEMENT\n\t It is sorry to say that we couldn't \
arranged a bigger table, Now only two people can be invited.\n");


for (var i = guest.length; i>2; i--)
{
    let p = guest.pop();
    console.log(`Sorry Dear ${p} for not inviting you`)
    
}

console.log('\n',guest,'\n');
for (var i=0 ; i<guest.length; i++)
{
    console.log(`Dear ${guest[i]} you are still invited for dinner    `)
    
}

guest.shift();
guest.shift();
console.log('\nGUEST = ',guest,'\n');


//Question 18:

let favPlace = ['maldives', 'aifil tower', 'china wall', 'burj khalifa', 'hawaii']
let sortPlace = [favPlace[0]];;

for (let i = 1 ; i<favPlace.length; i++){
    sortPlace.push(favPlace[i])
    
}
console.log('\nfavPlace = ',favPlace,'\n');
console.log('\nsortPlace = ',sortPlace.sort(),'\n');
console.log('\nfavPlace = ',favPlace,'\n');

console.log('\nreverse sort = ',sortPlace.reverse(),'\n');
console.log('\nfavPlace = ',favPlace,'\n');
console.log('\nfavPlace = ',favPlace.reverse(),'\n');
console.log('\nfavPlace = ',favPlace.reverse(),'\n');


//Question 19:
var guest = ['HAMAD','AHMED','SUBHAN'];
console.log('\nList of Invited People \n\t',guest,'\n');

console.log('No of Guest Invited = ', guest.length);

//Question 20:

let lst = ['k2','MountEverst','Himalya'];
console.log(lst);

//Question 21:
let Mount = ['k2','MountEverst','Himalya'];
let river = ['jehlum','chena','sindh', 'satlej']

let obj = {1:Mount,2:river};

console.log(obj[1]);


//Question 22:
let Mount = ['k2','MountEverst','Himalya'];
let river = ['jehlum','chena','sindh', 'satlej']

//console.log(Mount[Mount.length]); Error 
console.log(Mount[Mount.length-1]);




//Question 23:
let car = 'Fortuner';
if (car == 'Fortuner'){
    console.log("Is car == 'Fortuner'? I predict True.")
};
console.log(car=='Fortuner');

console.log('#1');
let I = 40
console.log(I == 40)
console.log(I== 50)

console.log('\n#2');
let B = 'NOKIA'

console.log(B.toLowerCase()== 'nokia');
console.log(B != 'NOKIA' );

console.log('\n#3');
let c = 'Now_33';
console.log(c ==  'Now_33');
console.log(c.toLowerCase() == c );

console.log('\n#4');
let d = 'donkey'
console.log(d == 'donkey')
console.log(d.length == 4)

console.log('\n#5');
const fruits=["Mango" , "Banana" ,"Apple" , "Cherry"];
console.log(fruits[0]==("Mango"));
console.log(fruits[3]=="Pineapple");



//Question 24:
// Tests for equality and inequality with strings
let strn='Pakitan Zindabad';
console.log(strn.charAt(0)=='P');
console.log(strn.charAt(8)=='z');

// Tests using the lower case function
let B = 'NOKIA'

console.log(B.toLowerCase()== 'nokia');
console.log(B != 'NOKIA' );

// Numerical tests involving equality and inequality, 
// greater than and less than, greater than or equal to,and less than or equal to

let num = [2,5,9,8,15];
console.log(num[0]>3);
console.log(num.length>=5);
console.log(num.length<=4);


// Tests using "and" and "or" operators

console.log(num[0]<3 && num[1] ==5);


// Test whether an item is in a array
// Test whether an item is not in a array


let Mount = [2,3,8,9,6,7];

let k = 2;

for (const j of Mount){
    // console.log(j, Mount[Mount.length-1]);

    if(k==j){
        console.log(k==j);
        break;
    }
              
    else if ((k != j) && (j ==  Mount[(Mount.length)-1])){
        console.log(k==j)
        break;
    }
    else {;

        }
};


//Question 25:
let alien_color = 'green';
if (alien_color == 'green'){
    console.log('Player Just Earned 5 Points')
}
else{
    console.log('Try again')
    
//Question 26:  
alien_color = 'yellow';
if (alien_color == 'green'){
    console.log('Player Just Earned 5 Points')
}
else{}



//Question 27:
let alien_color = 'green'
    if (alien_color == 'green'){
    console.log('Player Just Earned 5 Points')}
else{
    console.log('Player Just Earned 10 Points')};

alien_color = 'yellow'
    if (alien_color == 'green'){
    console.log('Player Just Earned 5 Points')}

    else if (alien_color == 'yellow'){
    console.log('Player Just Earned 10 Points')}

    else{
    console.log('Player Just Earned 15 Points')};

alien_color = 'red';
    if (alien_color == 'green'){
    console.log('Player Just Earned 5 Points')}
    
    else if (alien_color == 'yellow'){
    console.log('Player Just Earned 10 Points')}

    else{
    console.log('Player Just Earned 15 Points')};


//Question 28:

    const  Age = 65;
if (Age < 2) {
    console.log("The Peron is Baby")
}
else if (Age <4) {
    console.log("The Peron is Toddler")
}
else if (Age < 13) {
    console.log("The Peron is Kid")
}
else if (Age < 20) {
    console.log("The Peron is TeenAger")
}
else if (Age < 65) {
    console.log("The Peron is Adult")
    }
else {
        console.log("The Peron is Elder")};


//Question 29:
let favFruits = ['banana', 'mango','pineapple']

let k :string= prompt('Enter Fruit Name');
for (let i of favFruits)
{
    if ( i == k.toLowerCase() )
    {
        console.log(`Your really Like ${k}`)
    }
    else {

    } 

};


//Question 30:
let userName = ['kamran','saleem','admin','mehmood' ];


for (let i of userName)
{console.log('\n',i.toUpperCase());
    if (i === 'admin')
    {
        console.log("\tHi ", i.toUpperCase() ," Would you like to see Status Report ")
    }
    else
    {
        console.log("\tHello " ,i.toUpperCase() ," Welcom to App ")
    }

}  



//Question 31
:
let userName = ['kamran','saleem','admin','mehmood' ];

console.log(userName.length);

userName = [];
console.log(userName.length)

if (userName.length === 0){console.log('we need to find some user')}
else {};



//Question 32:

let New_user = ['saleem','Kamran','hammad','Ahmed','Sobhan']
let Curr_user = ['KAMRAN','Mehmood','Rehab','ahmed','Noman']


for (let nu of New_user){
    
    console.log('\nchecking user name ', nu);

    for (let cu of Curr_user)
    {
       
        if (cu.toLowerCase() === nu.toLowerCase())

        {
            console.log(`${cu} will need to enter a new username`);
            nu = " "
            
            break;
        }
        
        else{
            
        }
    }
   if(nu === " "){

   }
   else {console.log(`${nu} user is available`)
    }
    
}


//Question 33:

let K = [1, 2, 3, 4, 5, 6, 7, 8, 9]

for (let e of K){
    if (e === 1){
        console.log(e+'st');
    }
    else if ( e === 2){
        console.log(e+'nd');
    }
    else if ( e === 3){
        console.log(e+'rd');
    }
    else{
        console.log(e + 'th')
    }
    
}

//Question 34:

let pizzas = ['tikka','fajita','peproni','malai boti','vegitable'];

for (let pizza of  pizzas){
    console.log(pizza.toUpperCase());
    console.log(`I Like ${pizza.toUpperCase()} Flavour Pizza \n` );
}
console.log(`I like all kinds of pizzas flavour and love to eat and \
try different flavors every day . The most i like in pizzas is cheese\
and different yummy sauces.Even I am thinking to open a pizza business\
with name "Pizza's craze"\n "I REALLY LOVE PIZZA"` );


//Question 35:

let pets  = ['cat', 'dog','parrot'];
for (let pet of pets){
    console.log(pet);
    console.log('A '+pet+' make a great pet ')
}
console.log(pets[0]+','+pets[1]+','+' and ' +pets[2] + ' the all are adorable pets')


//Question 36:
function make_shirt(size,msg:string){
console.log(`\nYour T shirt is Ready\n
--------------\n"size"\n--------------\n ${size}\n
you can also see your message on it\n
--------------\n your message\n--------------\n
${msg}`)
}



//Question 37:
make_shirt('Medium','I LOVE PAKISTAN')

function make_shirt(size = 'Large',msg = 'I Love Typescript')

{console.log(`\n
__________________________\n\t
NEW MESSAGE \n__________________________\n
Your T shirt is Ready\n
--------------\n"size"\n--------------\n\t
${size}\n
you can also see your message on it\n--------------\nyour message\n--------------\n
${msg}`)
}

make_shirt();
make_shirt('Medium');
make_shirt('Small');

//Question 38:
function describe_city(a,b='Pakistan'){
    console.log(`${a} is the city of ${b}`);

}
describe_city('Lahore');
describe_city('Karachi');
describe_city('Delhi','India');



//Question 39:
function describe_city(a:string,b:string){
    return console.log(`"${a}, ${b}"`)}

describe_city('Lahore','Pakistan');
describe_city('karachi','Pakistan');
describe_city('Delhi','India');


//Question 40:

function make_album(a:string,b:string ,c:string ='')
{
    let musicAlbum = {'Artist Name':a, 'Album Name':b, 'No of Tracks':c}
    // musicAlbum['Aritist Name'] = a;
    console.log(musicAlbum);
}

make_album('atif','Doori');
make_album('Ali Zafar','Huqa Pani','11');
make_album('Rahat Fateh Ali Khan','Charkha"','8');




//Question 41:
 let magicians = ['aladin','samri','goga']

function show_magicians(){
    for (let magic of magicians){
        console.log(magic);
        
    }
    console.log(magicians);

}

show_magicians()

//Question 42:
let magicians = ['aladin','samri','goga']

function show_magicians(){
    for (let magic of magicians){
        console.log(magic);
        
    }
    console.log(magicians);

}

show_magicians()


function make_great()
{
    for (let i=0; i < magicians.length; i++){
        
        // console.log(magicians[i],magicians.length)
         magicians[i] = 'The Great Magician '.concat(magicians[i]);
       
          }
          console.log(magicians);
}
make_great()

//Question 43:

let magicians = ['aladin','samri','goga']

function show_magicians(){
    for (let magic of magicians){
        console.log(magic);
        
    }
    console.log(magicians);

}

show_magicians()


function make_great()
{
    let new_magicians=[''];
    for (let i=0; i < magicians.length; i++){
        
         new_magicians[i] = 'The Great Magician '.concat(magicians[i]);
         console.log(new_magicians)
        
          }
          console.log(magicians);
}
make_great()
show_magicians()

//Question 44:

function makeSandwich(...items){
    let sandwichItems = [''];
    for (let i =0; i<items.length;i++){
        sandwichItems[i] = items[i]
    
}
console.log(`"Your Sandwich is ready with following ingredients"\n\
[${sandwichItems}]`)
// console.log(sandwichItems)

}

makeSandwich('Butter','Chicken','Mayo');
makeSandwich('Tomato Ketchup','Beef','Mushrooms');
makeSandwich('Cheese','chicken','Mayo','Vegitables');

//Question 45:
let myCar = (X, Y ,...items)=>{
    const car = {};
    car['Manufacturer'] = X;
    car['Model'] = Y;
    car[items[0]]=items[1];
    car[items[2]]=items[3];
    console.log(car);
    return;
};
myCar ("Toyota", "Corola Gli","Color","Green","Milage","120")


