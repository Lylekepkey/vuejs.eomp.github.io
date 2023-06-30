<template>
    <body>
    <header>


    </header>
      <div class="modal" id="myModal">
        <div class="modal-dialog">
          <div class="modal-content bg-black">
              <div class="modal-header" style="color: wheat;">
                  <h4 class="modal-title">Items in cart</h4>
                  <button type="button"  class="btn-close" data-bs-dismiss="modal"></button>
                </div>
                <div id="cart-body" style="color: wheat; text-align: center;">
                    <div id="results"><h5>Total</h5></div>
                    
                </div>
                <div class="modal-footer" style="color:wheat;">            
                    <p>Total: <span id="total"></span></p>
                    <button onclick="checkout()" class="btn btn-primary">Checkout</button>              
            </div>
          </div>
        </div>
      </div>

    <main>
        <button onclick="sortProductsByPrice()" class="btn btn-primary" id="sort-btn">Sort by Price</button>
        
      
        <div class="p-3" id="products">

        </div>
        <div id="cart-container">
            <div id="cart-body"></div>
        </div>
    </main>
</body>
  
</template>

<style>
.addbtn {
    border: 1px solid wheat !important;
    border-radius: 10px;
    background-color: #808080;
    margin: 5px;
    height: 35px;
    width: 110px;
    color: white;
    font-size:20px;
}
.addbtn:hover {
    color:#CCCCFF !important;
    box-shadow: 0 0 9px 5px ;
    -webkit-transition: all 0.2s ease-out;
    -moz-transition: all 0.2s ease-out;
    transition: all 0.2s ease-out;
}

#cart-btn{
    background-color: wheat !important;
    border: 2px solid wheat !important ;
}
#cart-btn:hover{
    box-shadow: 0 0 9px 5px ;
    background-color: wheat !important;
    border: 2px solid white !important ;
}
</style>