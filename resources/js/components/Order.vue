<template>
<div class="container">
<div class="content-header">
  <div class="container-fluid">
    <div class="row mb-2">
      <div class="col-sm-6">
        <h1 class="m-0 text-dark">Dashboard</h1>
      </div><!-- /.col -->
      <div class="col-sm-6">
        <ol class="breadcrumb float-sm-right">
          <li class="breadcrumb-item"><a href="#">
            <button type="button" class="btn btn-outline-primary">
             <i class="fas fa-file-import"></i> Import CVS
            </button>
          </a>
          </li>
          <li class="breadcrumb-item active">
            <button type="button" class="btn btn-outline-primary">
             <i class="far fa-file-excel"></i> Export CVS
            </button>
          </li>
        </ol>
      </div><!-- /.col -->
    </div><!-- /.row -->
  </div><!-- /.container-fluid -->
</div>


<section class="content">
    <div class="container-fluid">
      
              <div  style="margin:20px auto;">
                <div>
                  <input  type="text" class="form-control in"  placeholder="Leadcode">
        
                  </div> 
                  <button type="button" class="btn btn-primary btn-lg btn-block in">
                    <i class="far fa-paper-plane"></i> Send The Order
                  </button>
               </div>
      
              <!-- Small boxes (Stat box) -->
              <div class="row">
                  <table class="table table-bordered table-hover table-striped">
                      <thead>
                        <tr>
                          <th scope="col">#</th>
                          <th scope="col">  <i class="fas fa-angle-double-down"></i> Leadset</th>
                          <th scope="col"> <i class="fas fa-angle-double-down"></i> Order</th>
                          <th scope="col"> <i class="fas fa-angle-double-down"></i> Adresse Pagode</th>
                          <th scope="col"> <i class="fas fa-angle-double-down"></i> Adresse Satilette</th>
                          <th scope="col"> <i class="fas fa-angle-double-down"></i> Last</th>
                          <th scope="col"> <i class="fas fa-angle-double-down"></i> Action</th>
                        </tr>
                      </thead>
                      <tbody>
                        <tr>
                            <th scope="row">1</th>
                            <td>Mark</td>
                            <td>Otto</td>
                            <td>@mdo</td>
                            <th scope="col">First</th>
                            <th scope="col">Last</th>
                            <th scope="col"> 
                              <button type="button" class="btn btn-outline-danger"><i class="fas fa-trash-alt"></i></button></th>
                          </tr>

                                                  <tr>
                            <th scope="row">1</th>
                            <td>Mark</td>
                            <td>Otto</td>
                            <td>@mdo</td>
                            <th scope="col">First</th>
                            <th scope="col">Last</th>
                            <th scope="col"> 
                              <button type="button" class="btn btn-outline-danger"><i class="fas fa-trash-alt"></i></button></th>
                          </tr>

                                                  <tr>
                            <th scope="row">1</th>
                            <td>Mark</td>
                            <td>Otto</td>
                            <td>@mdo</td>
                            <th scope="col">First</th>
                            <th scope="col">Last</th>
                            <th scope="col"> 
                              <button type="button" class="btn btn-outline-danger"><i class="fas fa-trash-alt"></i></button></th>
                          </tr>
                      </tbody>
                    </table>
      
              </div>

              <nav  aria-label="Page navigation">
                  <ul class="pagination justify-content-center">
                  <li class="page-item"><a class="page-link" href="#">Previous</a></li>
                  <li class="page-item"><a class="page-link" href="#">1</a></li>
                  <li class="page-item"><a class="page-link" href="#">2</a></li>
                  <li class="page-item"><a class="page-link" href="#">3</a></li>
                  <li class="page-item"><a class="page-link" href="#">Next</a></li>
                </ul>
              </nav>

            </div>
</section>
</div>
</template>

<style>
  tr,td{
    text-align:center;
  }  
</style>



