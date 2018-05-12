## Basic on Javascropt

### Return in Javascript 
  * Return is not necessery in Every function . If you need to end with particular task the use return to get particular execution from function. 
  * If dont need your function hold a spacefice data, your function is for modifiy another data then no need to return . just holding a data from function necessery return. 
  
  ````
  var name = 'name'
  var changeName = ()=> name = `updated ${name}`  // no need return kewords
  
  var name = 'name';
  var holdname = () => {return name};  // this function hold a value so return mandetory to avoid undefind
  
  name = holdname() // now name holds a string value;
  
  // If you stop excuting on particular task then
   
   function particulartask(x){
   
      if(x){                             // if x is truty then work inside the statement. 
          console.log(x, ' is a valid')  // if x is a truthy value then show this console.
          return;                        // finally return end the funciotn execution. 
      } 
      console.log(' x is not valied/ falsy') // function cann't read if upper statement is true; 
      
      // Here No need to use return becaue the function no need to hold data.
      
   }
  

   
  ````
  
  *  Note : If inside function with retrn keyword in it skipes next code on function. And use if without return is for just skipping if statement's element.
