# Python-projects
def small():
  def greet():
 	  name=(input("enter your name"))
 	  age=(input("enter your age"))
 	  city=(input("enter your city"))
 	  print(f"good morning {name}.{age} welcome to {city}")
  def calc():
 	  a=int(input("enter 1st num"))
 	  op=(input("enter operation"))
 	  b=int(input("enter second num"))
 	  if(op == "+"):
 	    print(a+b)
 	  elif(op == "-"):
 	    print(a-b)
 	  elif(op == "×"):
 	    print(a*b)
 	  elif(op == "÷" or "/"):
 	    print(a/b)
 	  else:
 	    print("invalid opretion")
  def num_checker():
 	  num=int(input("enter a number"))
 	  if(num % 2 == 0):
 	    print("num was odd")
 	  else:
 	    print("the number was odd")
  def vowel():
 	  v=input("enter a string")
 	  num1=v.count("a")
 	  num2=v.count("e")
 	  num3=v.count("i")
 	  num4=v.count("o")
 	  num5=v.count("u")
 	  print(num1+num2+num3+num4+num5)
  def table():
 	  N=int(input("enter the number of table"))
 	  for i in range(0,N):
 	    n=i+1
 	    print("------------------------------")
 	    for i in range(10):
 	      print(f"{n}×{i+1}={n*(i+1)}")
  def temp():
    t=int(input("enter the magnitude of temperature"))
    u=input("enter the unit of given temp c or f")
    if(u == "c"):
      print((t*(9/5))+32)
    elif(u == "f"):
      print((t-32)*(5/9))
    else:
      print("error 404")
  def si():
 	  p=float(input("enter the value of money"))
 	  r=float(input("enter percentage rate"))
 	  t=float(input("enter time perion in years"))
 	  si=(p*r*t)/100
 	  print("interest :",si)
 	  print(f"total money :{p+si}")
  def area():
 	  shape=input("enter the shape")
 	  if(shape == "circle"):
 	    r=float(input("enter radius"))
 	    a=(3.14)*(r*r)
 	    print(a)
 	  elif(shape == "square"):
 	    s=float(input("enter side"))
 	    print(s*s)
 	  elif(shape == "rectangle"):
 	    l=float(input("enter lenght"))
 	    w=float(input("enter width"))
 	    print(l*w)
 	  else:
 	    print("only circle,square and rectangle shapes are aviable")
  def grade():
 	  p=float(input("enter your percentage"))
 	  if(p >= 90):
 	    print("A+")
 	  elif(p >= 80):
 	    print("A")
 	  elif(p >= 70):
 	    print("B")
 	  elif(p >= 60):
 	    print("C")
 	  elif(p >= 50):
 	    print("D")
 	  elif(p >= 40):
 	    print("E")
 	  elif(p >= 30):
 	    print("F")
 	  else:
 	    print("failed")
  def divisbility():
 	  n=float(input("enter a number"))
 	  if(n % 2 == 0):
 	    print(f"{n} is divisble by 2")
 	  elif(n % 3 == 0):
 	    print(f"{n} is divisble by 3")
 	  elif(n % 5 == 0):
 	    print(f"{n} is divisble by 5")
 	  elif(n % 7 == 0):
 	    print(f"{n} is divisble by 7")
 	  elif(n % 11 == 0):
 	    print(f"{n} is divisble by 11")
 	  elif(n % 13 == 0):
 	    print(f"{n} is divisble by 13")
 	  elif(n % 17 == 0):
 	    print(f"{n} is divisble by 17")
 	  elif(n % 19 == 0):
 	    print(f"{n} is divisble by 19")
 	  elif(n % 23 == 0):
 	    print(f"{n} is divisble by 23")
 	  elif(n % 29 == 0):
 	    print(f"{n} is divisble by 29")
 	  elif(n % 31 == 0):
 	    print(f"{n} is divisble by 31")
  def str():
 	  str=input("enter a string")
 	  print(str[::-1])
  def palindrome():
 	  str=input("enter a string")
 	  str1=(str[::-1])
 	  if(str == str1):
 	    print("the string is palindrome")
 	  else:
 	    print("the str is not palindrome")
  def digit():
 	  n=input("enter a number")
 	  sum=0
 	  for i in n:
 	      sum += int(i)
 	  print(sum)
  def case():
 	  str=input("enter a string")
 	  up=0
 	  low=0
 	  for i in str:
 	    if i.isupper():
 	      up += 1
 	    elif i.islower():
 	      low += 1
 	  print(f"number of uppercase letter: {up}")
 	  print(f"number of lowercase letter: {low}")
  def all_def():
 	  print("for 1st question input : greet")
 	  print("for 2nd question input : calc ")
 	  print("for 3nd question input : num_checker")
 	  print("for 4th question input :vowel")
 	  print("for 5th question input: table")
 	  print("for 6th question input: temp")
 	  print("for 7th question input: interest")
 	  print("for 8th question input: area")
 	  print("for 10th question input: grade")
 	  print("for 11th question input: divis")
 	  print("for 12th question input: str")
 	  print("for 13th question input: palindrome")
 	  print("for 14th question input: digit")
 	  print("for 15th question inpur: cade")
 	  print("---------------------------------------------------------------------------")
 	  func=input("enter your function")
 	  if(func == "calc"):
 	    calc()
 	  elif(func == "greet"):
 	    greet()
 	  elif(func == "num_checker"):
 	    num_checker()
 	  elif(func == "vowel"):
 	    vowel()
 	  elif(func == "table"):
 	    table()
 	  elif(func == "temp"):
 	    temp()
 	  elif(func == "interest"):
 	    si()
 	  elif(func == "area"):
 	    area()
 	  elif(func == "grade"):
 	    grade()
 	  elif(func == "divis"):
 	    divisbility()
 	  elif(func == "str"):
 	    str()
 	  elif(func == "interest"):
 	    si()
 	  elif(func == "palindrome"):
 	    palindrome()
 	  elif(func == "digit"):
 	    digit()
 	  elif(func == "case"):
 	    case()
 	  elif(func == "done"):
 	    main()
 	  else:
 	    print("invalid def")
  for i in range(9999999999):
 	  all_def()
 	  print("---------------------------------------------------------------------------")
def medium():
  def bank():
    pin=(input("enter your pin"))
    if(pin == "1234"):
      amt=1000
      print(f"balance={amt}, withdrawl=0, deposit=0")
      wd=float(input("enter the amount of with withdrawl"))
      if(wd <= amt):
        print("withdrwal successful")
        print(f"balance={amt-wd}, withdrawl={wd}, deposite=0")
      else:
          print("insufficent amount")
    else:
      print("incorrect pin")
    print("---------------------------------------------------------------------------")
  def do_list():
    tasks=[]
    while True:
      task=input("enter task (or 'done')")
      if task.lower() == 'done':
        break
      tasks.append(task)
    print("your task")
    for i, t in enumerate(tasks, 1):
      print(f"{i}.{t}")
    print("---------------------------------------------------------------------------")
  def contact():
    contacts = {}  
    while True:
      name = input("Enter 'name' or 'done' if all name entered: ")
      num = input("Enter 'number' or 'done' if all num entered: ")
      if name.lower() and num.lower() == "done":
        break
      contacts[name] = num
    while True:
      n=input("search name to get number or 'stop' for cloce contact list")
      if n.lower() == "stop":
        break
      print(contacts.get(n))
    print("contact list has closed")
  def marks_avg():
    marks=[]
    for i in range(5):
      mark=int(input("enter your marks in top 5 subjects")) 
      marks.append(mark)
    sum=0
    for i in marks:
      sum += int(i)
      p=sum/len(marks)
    print(f"your percentage: {p}")
  def count_list():
    list=[]
    while True:
      ele=input("enter list element")
      if ele.lower() == "done":
        break
      list.append(ele)
    count=0
    for i in list:
      count += 1
    print(count)
  def vote():
    A=0
    B=0
    C=0
    D=0
    while True:
      party=input("enter party sumbol and 'done' for stop")
      if party.lower() == "done":
        break
      if(party == "a"):
        A += 1
      elif(party == "b"):
        B += 1
      elif(party == "c"):
        C += 1
      elif(party == "d"):
        D += 1
      else:
        print("invalid party name")
    if(A > B or A > C or A > D):
      print(f"party 'A' win the election with vote '{A}'")
    elif(B > A or B > C or B > D):
      print(f"party 'B' win the election with vote '{B}'")
    elif(C > A or C > B or C > D):
      print(f"party 'C' win the election with vote '{C}'")
    elif(D > A or D > C or D > B):
      print(f"party 'D' win the election with vote '{D}'")
    else:
      print("the election happened draw")
  def all_def():
    print("give input 'bank' to run bank functiom")
    print("give input 'contact' to run contact functiom")
    print("give input 'do_list' to run do_list function")
    print("give input 'marks_avg' to run marks_avg function")
    print("give input 'count_list' to run count_list function")
    func=input("enter your function name")
    if(func == "bank"):
      bank()
    elif(func == "do_list"):
      di_list()
    elif(func == "contact"):
      contact()
    elif(func == "restart"):
      main()
    elif(func == "marks_avg"):
      marks_avg()
    elif(func == "count_list"):
      count_list()
    elif(func == "vote"):
      vote()   
    else:
      print("invalid function name")
  all_def()
def main():
  while True:
    print("---------------------------------------------------------------------------")
    print("1.small programs")
    print("2.medium programs")
    print("3.hard question")
  
    print("---------------------------------------------------------------------------")
    a=(input("enter a number"))
    if a.lower() == "done":
      print("programe has closed")
      break
    if(int(a) == 1):
      small()
    elif(int(a) == 2):
      medium()
    elif(int(a) == 3):
      hard()
    else:
      print("enter valid number")
main()  
