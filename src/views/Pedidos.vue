<template>
  <div class="main-container">
    <h1>Gerenciar pedidos</h1>
    <Dashboard />
  </div> 
</template>

<script>
import Dashboard from "../components/Dashboard"
export default {
  name: "Pedidos",
  components: {
    Dashboard
  }
}
</script>

<style scoped>

#burger-table {
       max-width: 1200px; 
       margin: 0 auto;      
    }

    #burger-table-heading {
        display: flex;
        flex-wrap: wrap;
    }    
    
    .burger-table-row {
        display: flex;
        flex-wrap: wrap;
    }

    #burger-table-heading {
        font-weight: bold;
        padding: 10px;
        border-bottom: 2px solid #333;
    }
    #burger-table-heading div{
        width: 15%;
    }
    .burger-table-row div{
        width: 15%;
    }

    .burger-table-row{
        width: 100%;
        padding: 12px;
        border-bottom: 1px solid#ccc
    }
    #burger-table-heading .order-id,
    .burger-table-row .order-number{
        width: 5%
    }

    select {
        padding: 12px 6px;
        margin-right: 12px;
    }
    .delete-btn {
        background-color: #222;
        color: #FCBA03;
        font-weight: bold;
        border: 2px solid #222;
        padding: 10px;
        font-size: 16px;
        margin: 0 auto;
        cursor: pointer;
        transition: .5s;
     }
    .delete-btn:hover {
        background-color: transparent;
        color: #222;
    }

</style>

