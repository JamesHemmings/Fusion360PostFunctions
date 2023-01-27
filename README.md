# Fusion360PostFunctions
various things that add functionality to fusion 360 post processors

only includes one function currently "updateTools()"
add this function just before the onOpen() section of any fusion 360 post processor.
function creates and updates a csv file with information about tools used in program and previous programs.
function takes 1 argument "path" which is location you want the tooltable csv.
