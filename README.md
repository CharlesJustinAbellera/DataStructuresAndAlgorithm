import matplotlib.pyplot as plt

print ("Pick a Problem to Plot: ")#Menu of choices
print ("1 - Problem 1: x^2 + 7x + 2")
print ("2 - Problem 2: 3x + 2")
print ("3 - Problem 3: x^2")
print ("4 - Problem 4: x^3")
print ("5 - Problem 5: x^5")
print ("6 - Problem 6: x^3 + 2x^2 +  x + 10")
print ("7 - Problem 7: x^4 - 3x^3 + 2x^2 - x + 11")
print ("8 - Problem 8: sin(x)")
print ("9 - Problem 9: cos(x)")
print ("10 - Problem 10: x^5 + 4x^4 + x^3 - 2x^2 + 100")
print ("11 - Plot All Problem")
print ()
choice = input("Enter your choice: ")#enter ng choice from 1 to 11 

def problem1(): 
    result = []
    file = open('xvalue.txt','r')#read numbers sa txt file
    for x in file.readlines():
        Numbers = int(x)#convert sa int
        result.append((Numbers * Numbers) + (7 * Numbers) + 2)#formula to solve the problem
    with open('output1.txt', 'w') as output_file:#save the answer sa txt file
        for res in result:
            output_file.write(str(res) + '\n')#then iconvert into strings
    return result
problem1()

def problem2():
    result = []
    file = open('xvalue.txt','r')#read numbers sa txt file
    for x in file.readlines():
        Numbers = int(x)#convert sa int
        result.append((3 * Numbers) + 2)#formula to solve the problem
    with open('output2.txt', 'w') as output_file:#save the answer sa txt file
        for res in result:
            output_file.write(str(res) + '\n')
    return result
problem2()

def problem3():
    result = []
    file = open('xvalue.txt','r')#read numbers sa txt file
    for x in file.readlines():
        Numbers = int(x)#convert sa int
        result.append(Numbers * Numbers)#formula to solve the problem
    with open('output3.txt', 'w') as output_file:#save the answer sa txt file
        for res in result:
            output_file.write(str(res) + '\n')
    return result
problem3()

def problem4():
    result = []
    file = open('xvalue.txt','r')#read numbers sa txt file
    for x in file.readlines():
        Numbers = int(x)#convert sa int
        result.append(Numbers * Numbers * Numbers)#formula to solve the problem
    with open('output4.txt', 'w') as output_file:#save the answer sa txt file
        for res in result:
            output_file.write(str(res) + '\n')
    return result
problem4()

def problem5():
    result = []
    file = open('xvalue.txt','r')#read numbers sa txt file
    for x in file.readlines():
        Numbers = int(x)#convert sa int
        result.append(Numbers * Numbers * Numbers * Numbers * Numbers)#formula to solve the problem
    with open('output5.txt', 'w') as output_file:#save the answer sa txt file
        for res in result:
            output_file.write(str(res) + '\n')
    return result
problem5()

def problem6():
    result = []
    file = open('xvalue.txt','r')#read numbers sa txt file
    for x in file.readlines():
        Numbers = int(x)#convert sa int
        result.append((Numbers * Numbers * Numbers) + (2 * (Numbers*Numbers)) + Numbers + 10)#formula to solve the problem
    with open('output6.txt', 'w') as output_file:#save the answer sa txt file
        for res in result:
            output_file.write(str(res) + '\n')
    return result
problem6()

def problem7():
    result = []
    file = open('xvalue.txt','r')#read numbers sa txt file
    for x in file.readlines():
        Numbers = int(x)#convert sa int
        result.append((Numbers * Numbers * Numbers * Numbers) - (3 * (Numbers*Numbers*Numbers)) + (2*(Numbers*Numbers)) - Numbers + 11)#formula to solve the problem
    with open('output7.txt', 'w') as output_file:#save the answer sa txt file
        for res in result:
            output_file.write(str(res) + '\n')
    return result
problem7()

def problem8():
    result = []
    file = open('xvalue.txt','r')#read numbers sa txt file
    for x in file.readlines():
        Numbers = int(x)#convert sa int
        result.append(0.01745240644 * Numbers)#formula to solve the problem
    with open('output8.txt', 'w') as output_file:#save the answer sa txt file
        for res in result:
            output_file.write(str(res) + '\n')
    return result
problem8()

def problem9():
    result = []
    file = open('xvalue.txt','r')#read numbers sa txt file
    for x in file.readlines():
        Numbers = int(x)#convert sa int
        result.append(0.9998476952 * Numbers)#formula to solve the problem
    with open('output9.txt', 'w') as output_file:#save the answer sa txt file
        for res in result:
            output_file.write(str(res) + '\n')
    return result
problem9()

def problem10():
    result = []
    file = open('xvalue.txt','r')#read numbers sa txt file
    for x in file.readlines():
        Numbers = int(x)#convert sa int
        result.append((Numbers * Numbers * Numbers * Numbers * Numbers) + (4 * (Numbers*Numbers*Numbers*Numbers)) + (Numbers*Numbers*Numbers) - (2*(Numbers*Numbers)) + 100)#formula to solve the problem
    with open('output10.txt', 'w') as output_file:#save the answer sa txt file
        for res in result:
            output_file.write(str(res) + '\n')
    return result
problem10()

if choice == "1":#maplot ang answers if 1 ang piliin
    def displayPlot():
        plt.plot(problem1(), "go", label = "Problem 1")
        plt.xlabel("Value of X")
        plt.ylabel("Answer")
        plt.show()
    displayPlot()

if choice == "2":
    def displayPlot():
        plt.plot(problem2(), "go", label = "Problem 2")
        plt.xlabel("Value of X")
        plt.ylabel("Answer")
        plt.show()
    displayPlot()

if choice == "3":
    def displayPlot():
        plt.plot(problem3(), "go", label = "Problem 3")
        plt.xlabel("Value of X")
        plt.ylabel("Answer")
        plt.show()
    displayPlot()

if choice == "4":
    def displayPlot():
        plt.plot(problem4(), "go", label = "Problem 4")
        plt.xlabel("Value of X")
        plt.ylabel("Answer")
        plt.show()
    displayPlot()

if choice == "5":
    def displayPlot():
        plt.plot(problem5(), "go", label = "Problem 5")
        plt.xlabel("Value of X")
        plt.ylabel("Answer")
        plt.show()
    displayPlot()

if choice == "6":
    def displayPlot():
        plt.plot(problem6(), "go", label = "Problem 6")
        plt.xlabel("Value of X")
        plt.ylabel("Answer")
        plt.show()
    displayPlot()

if choice == "7":
    def displayPlot():
        plt.plot(problem7(), "go", label = "Problem 7")
        plt.xlabel("Value of X")
        plt.ylabel("Answer")
        plt.show()
    displayPlot()

if choice == "8":
    def displayPlot():
        plt.plot(problem8(), "go", label = "Problem 8")
        plt.xlabel("Value of X")
        plt.ylabel("Answer")
        plt.show()
    displayPlot()

if choice == "9":
    def displayPlot():
        plt.plot(problem9(), "go", label = "Problem 9")
        plt.xlabel("Value of X")
        plt.ylabel("Answer")
        plt.show()
    displayPlot()

if choice == "10":
    def displayPlot():
        plt.plot(problem10(), "go", label = "Problem 10")
        plt.xlabel("Value of X")
        plt.ylabel("Answer")
        plt.show()
    displayPlot()

if choice == "11":#maplot lahat ng problems from 1 to 10
    def displayPlot():
        plt.plot(problem1(), "r", label = "Problem 1")
        plt.plot(problem2(), "b", label = "Problem 2")
        plt.plot(problem3(), "go", label = "Problem 3")
        plt.plot(problem4(), "r", label = "Problem 4")
        plt.plot(problem5(), "b", label = "Problem 5")
        plt.plot(problem6(), "go", label = "Problem 6")
        plt.plot(problem7(), "r", label = "Problem 7")
        plt.plot(problem8(), "b", label = "Problem 8")
        plt.plot(problem9(), "go", label = "Problem 9")
        plt.plot(problem10(), "r", label = "Problem 10")
        plt.ylabel("Answer")
        plt.xlabel("Value of X")
        plt.show()
    displayPlot()
