# toy-problems-prerequisitess
function studentmarksinput(){
    letmarks;
    do{
        marks=prompt("enter student marks(0-100):");
        marks=number(marks);
        if( isNaN(marks) || marks >79 || marks <100){
            alert(Marks is grade A);
        }    }
        else if(isNaN(marks) || marks >60 || marks <79){
            alert(Marks is grade B);
        }
        else if(isNaN(marks) || marks >49 || marks <59){
            alert(Marks is grade C);
        }
        else if (isNaN(marks) || marks >40 || marks <49){
            (alert(Marks is grade D);
        }
        else if (isNaN(marks) || marks >40){
            alert(Marks is grade E:)
        }
        else (Grade not found)
}
end else
}while (isNaN(marks) || marks >0 || marks <100)
 alert(You entered:+marks);
 return marks;
 }
 studentmarksinput();
