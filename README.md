 # Learn What matters in TypeScript lang(concepts which is maximum used codebase)

<h2>
 <pre>
  <code>
1. Type annotation 
 eg :- 
 let firstName : string = 45;
 let firstName : number = 45;
 let firstName : boolean = true;
 let firstName : undefined
   </code>
  </pre>
</h2>

<h2>
 <pre>
  <code>
2. Type Any & unknown both used in function (***parameter***)=>{...}
:Any = store any type of data without any type checking by the TypeScript compiler   
:unknown = best used when you don't know the type of data being typed. To add a type later
   </code>
  </pre>
</h2>

<h2>
 <pre>
  <code>
3.TypeScript function 
 function greet (value: number): string //compulsory// {
console.log("Hello"+ value)
}
greet(12:number) //compulsory//
  </code>
  </pre>
</h2>

<h2>
 <pre>
  <code>
4. Type Array in TypeScript
eg: 
const names : string [ ] = ["a", "b", "c", "d];
 </code>
  </pre>
</h2>

<h2>
 <pre>
  <code>
5. Type Object in TypeScript

interface CarProps {
  type: string
  model: string
  year: number
}
eg:  const car = {
  type: "Toyota",
  model: "Corolla",
  year: 2009
};
</code>
  </pre>
</h2>

 
