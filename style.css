function EBcal(){
    const unit = Number(document.getElementById("input").value)

    //for first 50 units RS.0.75/unit
    //for next 100 inits RS.1.00/unit
    //for next 100 units RS.1.30/unit
    //for unit above 250 RS.1.50/unit

    //for example
    // input - 75
    //output -62.5
    
    if(unit<=50)
      rate = unit*0.75
    else if(unit>50 && unit<=150)
      rate = 50*0.75+(unit-50)*1
    else if(unit>150 && unit<=250)
      rate = 50*0.75+100*1+(unit-150)*1.30
    else
       rate = 50*0.75+100*1+100*1.30+(unit-250)*1.50

  let result=document.getElementById("result")
  result.innerHTML="your EB bill amount is: " + rate 


}
