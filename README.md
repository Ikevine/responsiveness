# responsiveness

In responsive design we have difference unit for making website responsive
-relative unit , Absolute unit and percentage unit

relative unit depend on their parent we have two types _font-size unit and _viewport unit
Absolute unit they don't depend on anything they are fixed they can't change
Parcentage unit they depend on their parent

Many it too me too much time to know about font-size responsiveness

we always us em for the media query / on each break_point we setup the width to be the base width 
and when we set them we don't put them in pixel becouse we take into consinderation that same people
might change the size of the browser defoult size so we change the body element which is the child
of the html element ,  

we use em for media query becouse same places rem doesn't work properly

Examples  
@media (min-width:600px){
    body{
        font-size: 12px;
    }
}

improve version is
 600px/16px = 37.5 where 16 is the base font-size

@media (min-width: 37.5rem ){
    body{
        font-size:12px
    }
}

I suggested that we should use rem instead of em becouse it will help me even if the user decide to change the font size
so we can only use em in padding and margin when we want consistent on out elements

Percentage only depend on it parent and it good ideal to use it on width to mantain consistency


The auto value when set to any properties mostly when it is on the width of the element this means that the element will resize
based on the content inside it

I'm currently working on responsiveness of a website and doing gradients

I have added same examples on the responsive web development soon I will add link to my figma design.




# Thank you