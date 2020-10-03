//main program


let result = 0

for (i=1;i>0;i++){

    let choose = prompt("You want to calculate car loan or home loan? Answer 'Car' or 'Home'. If you want to stop this, please return 'Stop'")

    if (choose=='Car'){
  
      let total = Number(prompt("How much you need pay for total?"))
      let t= Number(prompt("How many year you need to pay the loan? "))
      let r= Number(prompt("What is the interest rate for this loan? ex.'5.7%' input'5.7"))
      result = carLoanPayment(total,t,r)
      alert(`A car loan for $${total} over ${t} years at ${r}% interest would have a monthly payment of $${result}.`)
    }else if (choose == 'Home'){
      //three argument
      let total = Number(prompt("How much you need pay for total?"))
      let t= Number(prompt("How many year you need to pay the loan? Only enter 15 or 30"))
      let r= Number(prompt("What is the interest rate for this loan? ex.'5.7%' input'5.7"))
      result = homeLoanPayment(total,t,r)
      alert(`A home loan for $${total} over ${t} years at ${r}% interest would have a monthly payment of $${result}.`)
    }else if (choose == 'Stop'){
      alert("Thank you for using this program.")
      i=0
      break
    }else{
      alert(" Please write 'Car'or'Home'or'Stop'")
    }
}