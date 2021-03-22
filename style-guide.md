# Front-end Style Guide

## Layout

The designs were created to the following widths:

- Mobile: 375px
- Desktop: 1440px

## Colors

### Primary

Very Dark Magenta: hsl(300, 43%, 22%)
Soft Pink: hsl(333, 80%, 67%)

### Neutral

Dark Grayish Magenta: hsl(303, 10%, 53%)
Light Grayish Magenta: hsl(300, 24%, 96%)
White: hsl(0, 0%, 100%)

## Typography

### Body Copy

- Font size: 15px

### Font

- Family: [Spartan](https://fonts.google.com/specimen/Spartan)
- Weights: 400, 500, 700


phone media query


.container{
      width:100%;
      margin: auto;
      padding: 60px 60px ;
   }
    
    .title h1{
      font-size: 1.45em;
      text-align: center;
      font-weight: 800;
     }

     .toptext p{
      font-size: 0.65em; 
  }


  .first{
    font-size: 0.6em;
    font-weight: 500;
    color:var(--white);
 }
 
 .purp{
    font-size:0.6em ;
    font-weight: 500;
    color:var(--soft-pink);
 }
 
 .info{
   
   color:var(--white);
   margin-top:20px;
 }
 
 .info p{
   font-size:5px ;
 }








 .container{
    width:100%;
    margin: auto;
    padding: 100px 60px ;
 }

 .title h1{
  font-size: 2.5em;
  text-align: center;

 }

 .toptext{
   margin-top:10px;
   /*width:63%;*/
 }

 .toptext p{
  font-size: 0.9em;
  font-weight: 300;
  width:100%;
  text-align: center;
  color:var(--dark-grayish-magenta);

 }

 .rightsection{
   margin-top: 30px;
 }

      
    .topbox{
      display: flex;
      flex-direction: column;
    }

    .ratingcontain{
      display: flex;
      flex-direction: column-reverse;
      justify-content:space-around;
      align-items:center ;
      width:100%;
      padding:15px 0;
    }

    .ratingcontain:nth-child(1){
      margin-left: 0%;
    }
  
    .ratingcontain:nth-child(2){
      margin-left:0%;
      margin-top:2%;
      margin-bottom: 2%;
    }
  
    .ratingcontain:nth-child(3){
      margin-left:0%;
    }

    .starbox{
      padding:0;
      margin:1%;
    }

    .cardinfo{
      display:flex;
      align-items:center;
    }

      
  }


bottom section


@media (max-width:888px){

  .bottomsection{
    width:100%;
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    align-items: center;
    margin-top: 50px;
  }

  .box{
    width:100%;
    min-width:50%;
    border-radius:5px;
    background-color: var(--very-dark-magenta);
    padding: 50px 20px;  
}


}



/****************** TABLET ****************/
/******** BOTTOM SECTION MEDIA QUERIES *********/
/******** BOTTOM SECTION MEDIA QUERIES *********/
/******** BOTTOM SECTION MEDIA QUERIES *********/



/****************** PHONE ****************/
  /******** TOP SECTION MEDIA QUERIES *********/
  /******** TOP SECTION MEDIA QUERIES *********/
  /******** TOP SECTION MEDIA QUERIES *********/





