# Flow of Program

### Assignment Link: [01-flow-of-program.md](https://github.com/kunal-kushwaha/DSA-Bootcamp-Java/blob/main/assignments/01-flow-of-program.md)<br><br>

### Solutions:<br>
1. Input a year and find whether it is a leap year or not:<br>
  -Solution:<br>
  ```
  start
  input year
  if((year%400==0)&&(year%100!==0)
  print "leap year"
  else if (year%4==0)
  print "leap year"
  else
  print "not leap year"
  end
  ```
2. Take two numbers and print the sum of both:<br>
  -Solution:<br>
  ```
  start
  input a,b
  c = a + b
  print c
  end
  ```
3. Take a number as input and print the multiplication table for it:<br>
  -Solution:<br>
  ```
  start
  input num
  for(i=1;i<=10;i++){ //printing the table till 10
  ans = num*i
  print(num+"*"+i+"="+ans)
  }
  end
  ```
4. Take 2 numbers as inputs and find their HCF and LCM:<br>
  -Solution:<br>
  ```
  start
  input num1, num2
  if num1>num2
  max = num1
  else
  max = num2
  for(i=2;i<max;i++)
  if(num1%i==0) && (num2%i==0){
  hcf = i
  break
  }
  for(i=num1;i<num1*num2;i++)
  if(num1%i==0) && (num2%i=0){
  lcm = i
  break
  }
  print hcf
  print lcm
  end
  ```
5. Keep taking numbers as inputs till the user enters ‘x’, after that print sum of all:<br>
  -Solution:<br>
  ```
  start
  while(input!="x"){
  input n
  sum = sum+n
  }
  end
  ```
