width: 100%;

b5
w-100
w-75
w-50
w-25         if uh want to give 40 then use css .w-40{ width: 40%;}

Opacity :1;
Opacity: 0.5;
b5:
opacity-25
opacity-50
opacity-75
opacity-100

<!-- note left: start, right : end in bootstrap -->

* floact :left;
b5:
float-start
float-end

* text-decotration: none;
b5:
text-decoration-none

* display : inline;
b5:
d-inline
d-inline-block

*Box model
padding : 1rem;

b5:
p-5
pt-5(top)
pb-5(button)
ps-5(left)
pe-5(right)
py-5(top&button)
pe-5(right&left)

 note:  p is replace with m for using margin in bootstrap

 *display flex
 b5:
 d-flex
 flex-shrink-1
 flex-grow-1
 flex-wrap
 flex-row
 g-5

 justify-content -between
 justify-content -around
 justify-content -evenly

 align-item-center
 align-item-start(top)
 align-item-end(button)

 * Break point
 extra small...<576px
 sm ....small >576px
 md......768px
 lg......992px
 xl....1200pxl
 xxl....1400px

 *shadow-sm
 shadow
 shadow-lg

 * 
 border
 border-primary
 border-5
 border-top-5

 <!-- * border lai design grnay  -->
 rounded
 rounded-circle
 rounded-pill

 * height
 h-100
 h-75
 h-50
 h-25

 <!-- for desisigning the form -->
* <label>
         form-label
<input>
        form-control

 *table
 table......in the table element
 table -bordered
 table-hover
 table-responsive......add it on table's parent element 

 * 
 list-style-type-none
 text-decoration-underline
 text-decoration-linrthrough
 text-decoration-overline

 * position-relative
  position-absolute
  position-sticky
  position-fixed
  position-static

  *
  overflow-auto
  overflow-hidden
  overflow-scroll

  * button
  btn
  btn-primary
  btn-outline-primary(hover)
  btn-lg
  btn-sm

*container.........>center layout design
container-fluid........>full-width design

*flex
b5:
put main div (row like as we put wrapper in flex )

sm....col-sm-12
md.....col-md-6
lg.....col-lg-4

<script src="https://kit.fontawesome.com/6c38b3ccc9.js" crossorigin="anonymous"></script>
<section>
        <div class="container">
            <div class="row p-4 ">
                <div class="col-lg-4 col-md-6 col-sm-12 ">
                   <div class="d-flex  ">
                  <p class="rounded-cicle bg-orange">  <i class="fa-solid fa-book text-warning"></i></p>
                    <h4 class="fw-bold">
                        Quality First
                    </h4>
                   </div>
                </div>

                <div class="col-lg-4 col-md-6 col-sm-12 ">
                    <i class="fa-solid fa-users"></i>
                </div>

                <div class="col-lg-4 col-md-6 col-sm-12 ">
                    <i class="fa-regular fa-clock"></i>
                </div>
            </div>
        </div>
    </section>



