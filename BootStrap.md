# BootStrap CSS
## What is BootStrap?
        BootStrap is a Stylesheet for html. 
        It is used to create a responsive and consistent design for your webb application
        without any knowledge of advanced CSS coding. 
        
        BootStrap offers lots of premade CSS classes that can be used to create good looking web 
        applications. Here is a link to their tutorial website that covers almost everything
        you need to know. 
        
        Link: https://www.tutorialrepublic.com/twitter-bootstrap-tutorial/
        
        Because of the complexity of BootStraps different classes, the learning
        process would be a lot easier if you use their own tutorial. Here is some examples of what
        BootStrap offers.
       


### Containers
#### .container-{inset size: xs, sm, md, lg, xl and xll }
        Containers is the most basic layout element and should always be used with BootStrap css.
        Different sizes for different uses.
        
### Grids - rows and collumns
#### .row and .col-md-{insert column size}
        BootStrap utilizes a grid system, wich can be used to make a simple calendar, for example.
        A row can contain a maximum of 12 columns or 12 column spaces.
        For exmaple, you can have one column that is 12 column spaces large, that takes up the entire row.
        Or 3 equally large columns and each of them is 4 column spaces large, adding up to a total of 12 column spaces wich is the maxmimum.
        The code for the latter would look like this:
        
        <div class="row">               //The row class is being assigned.
            <div class="col-md-4">      //Each column has the class "col-md-4", "4" specifies the ammount of space that the column takes up.
                <div>  Column text    </div>
            </div>
            <div class="col-md-4">
                <div>  Column text   </div>
            </div>
            <div class="col-md-4">
                <div>  Column text    </div>
            </div>
        </div>
        
        Example Link : https://www.tutorialrepublic.com/codelab.php?topic=bootstrap&file=three-column-grid-layouts-for-tablets-in-landscape-mode-and-desktops 
        

