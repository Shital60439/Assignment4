<template>
<div>
   <!-- </nav> -->
    <div class="topnav bg-gray-400">
  <a class="active" href="#home">Home</a>
  <a href="#about">About</a>
  <a href="#contact">Contact</a>
  <p>Use filter:</p>
        <select class="p-1" name="filter" id="filter">
                            <option value="Product name" selected>Product name</option>   
                            <option value="Samsung A22">Samsung A22</option>
                            <option value=" ">Roadster sweatshirt</option>
                            <option value="HP Core i3 ">HP Core i3 </option>
                            <option value="Express-08 Grey Sports">Express-08 Grey Sports </option>
                        </select>
        <select class="p-1" name="filter" id="filter">
                            
                            <option value="Price" selected>Price </option>
                            <option value="12,000"> 12,000</option>
                            <option value="2000">2000</option>
                             <option value="39000">39000</option>
                             <option value="699">699</option>

                        </select>
        <select class="p-1" name="filter" id="filter">
                           
                            <option value=" categry" selected> categry</option>
                            <option value="mobile">mobile</option>
                            <option value="cloth">cloth</option>
                            <option value="Laptop">Laptop</option>
                            <option value="Men's shows">Men's shows</option>

                        </select>
        <select class="p-1" name="filter" id="filter">
                            <option value="color" selected>color</option>
                            <option value="black">black</option>   
                            <option value="pink ">pink</option>
                            <option value="Natural Silver "> Natural Silver</option>
                            <option value="Grey, Green">Grey, Green</option>
                        </select>


    </div>
    <div>
        
    </div>
        
</div>
    
    <h1 >Here is home page</h1>
    <h1> Welcome to online Shopping</h1><br><br><br>
   <div class="border-2 bg-cyan-300">
    <h4>Product Card</h4>
    <table class="border-2 bg-transparent">
        <thead>
        <th>Product name</th>
        <th>Price </th>
        <th> categry</th>
        <th>color</th>
        </thead>
        <tbody>
            <tr>
                <td>Samsung A22</td>
                <td> 22,000</td>
                <td>Mobile</td>
                <td>Black</td>
                <td> <img src="image.jfif" alt="mobile"></td>
               
                
                <td><button class="bg-blue-500 hover:bg-blue-700 text-white font-bold py-2 px-4 rounded">
  Submit
</button></td>
                
            </tr>
           
           
        </tbody>  
    </table>
    </div>

    
    <p class="font-semibold">Add Product here</p>
      <input type="text" placeholder="Search .."><button class="bg-blue-500 hover:bg-blue-700 text-white font-bold py-2 px-4 rounded">
  Add Product
</button>



</template>


<script>

</script>